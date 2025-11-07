```mermaid
classDiagram
     Acteur <|-- Personne
   Acteur <|-- Association
    Personne <|-- Citoyen
     Association <|-- CitoyenActif
    Citoyen <|-- CitoyenActif
    Personne <|-- CitoyenProfessionnel
    CitoyenProfessionnel <|-- CitoyenPublic
    CitoyenProfessionnel <|-- CitoyenPrive


    Acteur : +String Name
    Acteur : +String adresse
    Acteur: +communiquer()
    Acteur: +collaborer()
  class Personne {
     +Date   dateDeNaissance
     +String genre
     +String nom
  }

  class Citoyen {
     +String statut 
     +String implication
     +participerProjet()
  }

   class Association{

    +array membres 
    + alerterprobleme()
    + organiserActions()
    }
  class CitoyenActif {
     +String association
     +exprimerAvis()
  }

  class CitoyenProfessionnel {
     +String fonction
     +String domaine
     +agirEnFonction()
  }

  class CitoyenPublic {
     +String service
     +String nomInstitution
     +gererProjet()
  }

  class CitoyenPrive {
     +String entreprise
     +String secteur
     +realiserProjet()
  }
```

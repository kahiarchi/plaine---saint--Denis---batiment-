```mermaid
classDiagram
    %% Hiérarchie des individus
    Personne <|-- Citoyen
    Personne <|-- CitoyenProfessionnel
    Citoyen <|-- CitoyenActif

    %% Associations du citoyen professionnel avec les structures
    CitoyenProfessionnel --> InstitutionPublique : travailleDans >
    CitoyenProfessionnel --> ActeurPrive : collaboreAvec >

  class Personne {
     +int age
     +String genre
     +String nom
  }

  class Citoyen {
     +String statut 
     +String implication
     +participerProjet()
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

  class InstitutionPublique {
     +String nom
     +String service
     +gererProjet()
  }

  class ActeurPrive {
     +String entreprise
     +String secteur
     +realiserProjet()
  }
  
```

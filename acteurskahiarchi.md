```mermaid
classDiagram
    Personne <|-- Citoyen
    Citoyen <|-- CitoyenActif
    Citoyen <|-- CitoyenProfessionnel
    CitoyenActif --> ProjetUrbain : Participe à >
    CitoyenProffessionnel --> InstitutionPublique : Travaille pour >
    CitoyenProffessionnel --> ActeurPrive : Travaille pour >
    ProjetUrbain --> InstitutionPublique : est piloté par >
    ProjetUrbain --> ActeurPrive : est réalisé par >
    ProjetUrbain --> Citoyen : concerne >

  class Personne {
     +int age
     +String genre
     +String nom ()
    }
  class Citoyen {
     +String statut 
     +String implication
     +participerProjet()
    }
  class CitoyenActif{
          +String association
          +exprimerAvis()
          }
    class CitoyenProfessionnel{
      +String fonction
      +String domaine
      +AgireEnFonction()
     }
   class InstitutionPublique{
      +String nom
      +String service
      +gererProjet()
     }
   class ActeurPrive{
      +String entreprise
      +String secteur
      +realiserProjet()
     }
  class ProjetUrbain{
      +String nomProjet
      +String localisation
      +String objectif
      +String etatAvancement()
     }
```

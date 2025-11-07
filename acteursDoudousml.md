```mermaid
classDiagram
    Acteur <|-- Citoyen
    Acteur <|-- Association
    Acteur <|-- Institution
    Institution <|-- InstitutionPublique
    Institution <|-- InstitutionPrivee
    Acteur : +String Name
    Acteur : +String adresse
    Acteur: +communiquer()
    Acteur: +collaborer()
    class Citoyen{
      +date date_de_naissance 
      + participerConsultation()
      + signalerProbleme()
    }
class Institution {
        +array role
        +regulerProjet()
        +piloterProjet()
        +delivrerAutorisationUrbanisme()
    }
    class Association{

    +array membres 
    + alerterprobleme()
    + organiserActions()
    }
     class InstitutionPublique {
      +String nomMinistere 
    }

    class InstitutionPrivee {
      +String secteurActivite 
    }
```

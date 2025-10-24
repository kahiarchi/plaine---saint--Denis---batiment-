```mermaid
classDiagram
    Acteur <|-- Citoyen
    Acteur <|-- Association
    Acteur <|-- Institution
    Institution <|-- Mairie
    Acteur : +String Name
    Acteur : +String adresse
    Acteur: +communiquer()
    Acteur: +collaborer()
    class Citoyen{
      +int age
      + participerConsultation()
      + signalerProbleme()
    }
class Institution {
        +array role
        +regulerProjet()
    }
    class Association{

    +array membres 
    + alerterprobleme()
    + organiserActions()
    }
   class Mairie {
    + piloterProjetsUrbains()
    + delivrerAutorisationUrbanisme()
}
```

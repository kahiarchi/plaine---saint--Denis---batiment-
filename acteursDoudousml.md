```
classDiagram
    Acteur <|-- Citoyen
    Acteur <|-- Association
    Acteur <|-- Mairie
    Acteur : +int age
    Acteur : +String Name
    Acteur : +String gender
    Acteur : +String adresse
    Acteur: +communiquer()
    Acteur: +collaborer()
    class Citoyen{
      + participerConsultation()
      + signalerProbleme()
    }
    class Association{

    +int membres 
    + alerterprobleme()
    + organiserActions()
    }
   class Mairie {
    + piloterProjetsUrbains()
    + delivrerAutorisationUrbanisme()
}
```

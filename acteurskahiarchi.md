```mermaid
classDiagram
    pesonne <|-- associationetcitoyen
    pesonne <|-- institutions publiques
    pesonne <|-- acteur privé 

    pesonne : +int age
    pesonne : +String gender
    pesonne : fonction()

  class association citoyen {
     +implication 
     +collaboration
     +critique ()
    }
    class institutions publiques{
          +lieu de travail
          +outils de travail
          +fonction ()
    }
    class acteu pivé{
      + statut
     +  role
     }
```

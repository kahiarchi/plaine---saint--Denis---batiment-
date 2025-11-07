classDiagram
    class Acteur {
        +String nom
        +Date dateNaissance
        +String type
        +participerProjet()
    }

    Acteur <|-- Resident
    Acteur <|-- Promoteur
    Acteur <|-- Institution

    class Resident {
        +String compositionFoyer
        +String logement
        +donnerAvis()
    }

    class Promoteur {
        +String entreprise
        +List~Projet~ projets
        +construire()
    }

    Promoteur <|-- GroupeConstruction
    Promoteur <|-- GroupeImmobilier

    class GroupeConstruction {
        +realiserGrandsChantiers()
    }

    class GroupeImmobilier {
        +developperProjetsImmobiliers()
    }

    class Institution {
        +String role
        +regulerProjet()
    }

    Institution <|-- ServiceUrbanisme
    Institution <|-- ServiceBatiment

    class ServiceUrbanisme {
        +analyserProjet()
        +validerConformite()
    }

    class ServiceBatiment {
        +suiviControl()
        +payementConformite()
    }

    class Projet {
        +String nom
        +String statut
        +String localisation
    }

    Promoteur "1" --> "n" Projet : réalise
    Institution "1" --> "n" Projet : supervise

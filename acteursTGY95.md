classDiagram
    
    class Acteur {
        +String type
        +participerProjet()
    }

    Acteur <|-- ActeurInstitutionnel
    Acteur <|-- ActeurPrive
    Acteur <|-- ActeurCommunautaire
    Acteur <|-- Resident

    
    ActeurInstitutionnel <|-- Collectivite
    ActeurInstitutionnel <|-- ServiceUrbanisme
    ActeurInstitutionnel <|-- Architecte
    ActeurInstitutionnel <|-- BureauEtudes

 
    ActeurPrive <|-- Promoteur
    ActeurPrive <|-- EntrepriseConstruction

 
    ActeurCommunautaire <|-- Association
    ActeurCommunautaire <|-- ComiteRiverains

   

    class Resident {
        +int nombreMembres
        +String typeLogement
        +donnerAvis()
    }

    class Promoteur {
        +String entreprise
        +String projet
        +construire()
    }

    class EntrepriseConstruction {
        +String nomEntreprise
        +realiserTravaux()
    }

    class Collectivite {
        +String nomCollectivite
        +coordonnerProjet()
    }

    class ServiceUrbanisme {
        +gererPermisConstruire()
        +planifierAmenagement()
    }

    class Architecte {
        +concevoirBatiment()
    }

    class BureauEtudes {
        +analyserProjet()
        +validerConformite()
    }

    class Association {
        +String nomAssociation
        +organiserReunions()
    }

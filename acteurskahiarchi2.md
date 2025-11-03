
CITOYEN ||--o{ PROJET : "participe à"
    PROJET ||--|{ TYPE_PROJET : "appartient à"
    TYPE_PROJET ||--o{ TYPE_PROJET : "sous-type de"
    PROJET ||--o{ BATIMENT : "comprend"
    CITOYEN ||--o{ COMMENTAIRE : "écrit"
    COMMENTAIRE }o--|| PROJET : "sur"
    PLATEFORME ||--o{ COMMENTAIRE : "héberge"
    CITOYEN ||--o{ PLATEFORME : "utilise"
    CITOYEN {
        string id
        string nom
        string email
    }

    PROJET {
        string id
        string nom
        string statut
        date dateCreation
        string localisation
    }

    TYPE_PROJET {
        string id
        string nom
        string categorie
        string description
        string parentTypeId
    }

    BATIMENT {
        string id
        string nom
        float cout
        string adresse
    }

    PLATEFORME {
        string id
        string nom
        string url
    }

    COMMENTAIRE {
        string id
        string texte
        date datePublication
    }

... mermaid
erDiagram
    citoyen ||--o{ projet : places
    projet ||--|{ typeprojet : contains
    batiment ||--o{ typeprojet : includes
    citoyen {
        string id
        string name
        string email
    }
    projet {
        string id
        date orderDate
        string status
    }
    batiment {
        string id
        string name
        float price
    }
    typeprojet {
        int quantity
    }
...

## 1_ LES SOURCES DE DONNEES 
- Données INSEE sur la population et le logement : https://www.insee.fr/fr/statistiques
- Données sur les équipements urbains : https://data.gouv.fr
- Territoire-de-projets-urbains : https://plaine-commune-developpement.fr
- Territoire du quartier de la plaine : https://fr.wikipedia.org/wiki/La_Plaine_Saint-Denis 
- Renouvellementurbain : https://odyssea-paris.com/renouvellement-urbain-plaine-saint-denis/
- Plainemémoire : https://plaine-memoirevivante.fr
- Permis de construire : https://www.data.gouv.fr/datasets/base-des-permis-de-construire-et-autres-autorisations-durbanisme 
- Projetsdamenagement : https://www.data.gouv.fr/datasets/projets-damenagement-dile-de-france/
- Projetsdamenagement : https://www.institutparisregion.fr/cartographies-interactives/tableau-de-bord-des-projets-damenagement/
- Projetsdamenagement : https://www.institutparisregion.fr/uploads/ExportData/projets_amenagement.html
- Projetsdamenagement : https://data.iledefrance.fr/explore/dataset/urbanisme-transitoire/export/?refine.departement=93&refine.commune=Saint-Denis 
- Projetsurbains : https://plainecommune.fr/projets/grands-projets-urbains/le-canal-saint-denis-reamenage/
- Reglementation : https://plainecommune.fr/revision-plui/
- Participationcitoyenne : https://www.saintdenis.fr/actualites/franc-moisin-zac-avis
- Amenagementurbain : https://www.saintdenis.fr/nouveau-coeur-ville
- Prandprojet : https://www.apur.org/fr/amenagement-urbain/quartier-gare/quartier-gare-saint-denis-pleyel
- Acteurimmobilier : https://www.apur.org/fr/amenagement-urbain/urbanisme-temporaire/acteurs-immobiliers 
- Grandparis : https://www.apur.org/fr/amenagement-urbain/quartier-gare/mutations-68-quartiers-gare-gpe-2021-projets-urbains-grand-paris
- Participationcitoyenne : https://www.apur.org/fr/population-societe/social-inclusion/solidarites-proximite-resilience-0 
- Le territoire : https://data.seinesaintdenis.fr/explore/?sort=-title 
- Association : https://ressources.seinesaintdenis.fr/Appel-a-projets-2024-en-faveur-des-habitants-des-quartiers-prioritaires-de-la
 ## 2_ LE LIEN DATA TABLES ( xlsx)
[data_table.xlsx](https://github.com/user-attachments/files/23320020/data_table.xlsx)
## 3_ DATA TABLES
### - Table 01 - persone
| ID | Nom | Âge | Genre |
|----|-----|-----|-------|
| 1  | Sam Bentounsi | 30 | M |
| 2  | Bruno Maguer | 50 | M |
| 3  | Association Union des Riverains | 1 | F |
| 4  | Claire Dupont | 40 | F |
| 5  | Jean Martin | 35 | M |
| 6  | Sophie Leroy | 28 | F |
| 7  | Paul Durand | 45 | M |
| 8  | Marie Dubois | 32 | F |
| 9  | Antoine Bernard | 38 | M |
| 10 | Élodie Moreau | 27 | F |
### - Table 02 - citoyen 
| ID | Statut / Rôle | Description / Fonction | Référence |
|----|----------------|------------------------|------------|
| 1  | Habitant | Nouveau propriétaire en BRS – résidence Les Météores | 1.1 |
| 2  | Professionnel | Président de réseau d’entreprises territoriales | 2 |
| 3  | Actif associatif | Membre du comité de riverains Stade de France | 3 |
| 4  | Habitant | Locataire à Plaine Commune | 4 |
| 5  | Professionnel | Architecte urbaniste | 5 |
| 6  | Actif associatif | Président d’association locale | 6 |
| 7  | Habitant | Propriétaire d’un appartement | 7 |
| 8  | Professionnel | Directeur d’entreprise immobilière | 8 |
| 9  | Actif associatif | Membre d’association citoyenne | 9 |
| 10 | Habitant | Résident du quartier des Mureaux | 10 |
### - Table 03 - citoyenActif 
| ID | Nom de l’association / collectif | Référence Citoyen |
|----|----------------------------------|-------------------|
| 1  | Comité Vigilance Plaine          | 3 |
| 2  | Association Plaine Citoyenne     | 6 |
| 3  | Réseau des habitants             | 9 |
### - Table 04 - citoyenProfessionnel
| ID | Fonction | Domaine | Référence Citoyen |
|----|-----------|----------|-------------------|
| 1  | Dirigeant | Développement territorial | 2 |
| 2  | Architecte | Urbanisme | 5 |
| 3  | Directeur | Immobilier | 8 |
### - Table 05 - institutionPublique
| ID | Nom de l’institution | Service / Domaine | Référence CitoyenProfessionnel |
|----|-----------------------|-------------------|--------------------------------|
| 1  | Plaine Commune Développement | Aménagement urbain | 1.1 |
| 2  | Mairie de Saint-Denis | Urbanisme | 2 |
| 3  | Service Habitat Plaine | Logement | 3 |
### - Table 06 - acteurPrive
| ID | Nom de l'acteur                  | Secteur d'activité             | Catégorie |
|----|---------------------------------|-------------------------------|----------|
| 1  | WO2 - Immobilier Bas Carbone     | Construction & bureau          | 1.1      |
| 2  | Sogeprom                         | Immobilier résidentiel         | 2        |
| 3  | Bouygues Construction            | Grands projets urbains         | 3        |
### - Table 07 - projet
| ID  | Nom du projet                          | Statut     | Localisation           |
|-----|---------------------------------------|-----------|-----------------------|
| 2   | Projet Bois Bas Carbone - Pôle siège GRDF | En cours  | La Plaine Saint-Denis |
| 3   | Quartier du Canal                      | Planifié  | La Plaine Saint-Denis |
| 4   | Réhabilitation Stade de France         | En cours  | La Plaine Saint-Denis |
| 5   | ZAC Franc Moisin                        | Achevé    | La Plaine Saint-Denis |
| 6   | Projet Pleyel                           | En cours  | La Plaine Saint-Denis |
| 7   | Réaménagement gare Saint-Denis         | Planifié  | La Plaine Saint-Denis |
| 8   | Extension ZAC Mairie                    | En cours  | La Plaine Saint-Denis |
| 9   | Résidence sociale La Plaine            | Achevé    | La Plaine Saint-Denis |
| 10  | Parc urbain Canal Saint-Denis          | Planifié  | La Plaine Saint-Denis |
### - Table 08 - participation 
| ID  | ID Projet | ID Acteur | Rôle                     |
|-----|-----------|-----------|--------------------------|
| 1   | 3         | 1.1       | Membre comité            |
| 2   | 2         | 2         | Promoteur entreprise     |
| 3   | 6         | 3         | Membre association       |
| 4   | 9         | 4         | Consultant citoyen       |
| 5   | 1         | 5         | Résident participant     |
| 6   | 4         | 6         | Habitant suivi           |
| 7   | 7         | 7         | Propriétaire suivi       |
| 8   | 5         | 8         | Professionnel partenaire |
| 9   | 8         | 9         | Promoteur                |
| 10  | 10        | 10        | Habitant observateur     |
### - Table 09 - Realisation
| ID  | ID Acteur 1 | ID Acteur 2 | ID Rôle | Type d'intervention         |
|-----|------------|------------|---------|----------------------------|
| 1   | 1.1        | \N         | 1.2     | Maître d’ouvrage           |
| 2   | \N         | 1          | 2       | Construction spécialisée bois |
| 3   | 2          | \N         | 3       | Supervision                |
| 4   | \N         | 2          | 4       | Construction résidentielle |
| 5   | 3          | \N         | 5       | Pilotage                   |
| 6   | \N         | 3          | 6       | Construction bureaux       |
| 7   | 1          | \N         | 7       | Maîtrise d’ouvrage         |
| 8   | \N         | 2          | 8       | Construction immobilière   |
| 9   | 2          | \N         | 9       | Suivi                       |
| 10  | \N         | 3          | 10      | Aménagement espaces        |
## 4_ STRUCTURE VISUELLE 
Le diagramme suivant montre les relations entre les différents acteurs du projet .
```mermaid
classDiagram
    Personne <|-- Citoyen
    Citoyen <|-- CitoyenActif
    Citoyen <|-- CitoyenProfessionnel

    CitoyenProfessionnel <|-- InstitutionPublique
    CitoyenProfessionnel <|-- ActeurPrive

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
  
```
## 5_ REPRESENTATIONS ET ANALYSE DES DONNEES 

Cette étude analyse la participation des citoyens, des acteurs publics et privés dans différents projets urbains à La Plaine Saint-Denis. Les visualisations suivantes permettent de comprendre la répartition des acteurs, le type de participation et la localisation des projets.

Afin d'analyser la participation citoyenne dans les projets urbains au quartier de la plaine Saint Denis , nous avons envisagé les représentations suivantes  :
- **Histogramme** pour comparer le nombre de citoyens selon leur statut ( habitant , professionnel , actif associatif )
- ![Histogramme citoyens](histogramme_citoyens.png)
- **Camembert** pour montrer la proportion de chaque acteur ( public , privé et citoyen )
- ![Camembert acteur](camembert_acteur.png)
- **Carte interactive** pour localiser les projets participatifs dans le quartier ou la ville .
- ![projet_localisation](https://github.com/user-attachments/assets/40fcdab6-17f2-46ba-9797-b2eb6e5f7ee3)

- **Graphique en barres empilées** pour visualiser la participation selon les types de projets ( culturels , educatifs , sportifs , détentes.....)
-![Barres empilées](projet_participation.png)

** OBSERVATIONS :**
###  Nombre de citoyens par statut
**Observation **
- Les habitants représentent la majorité des participants.
- Les professionnels et acteurs associatifs sont également présents, mais en plus faible proportion.
###  Répartition des acteurs (citoyens, publics, privés)
**Observation **
- Les citoyens constituent la plus grande part des acteurs.
- Les acteurs publics et privés sont équilibrés, apportant un soutien institutionnel et économique aux projets.
### Participation par type de projet et type d’acteur
**Observation **
- Les projets culturels et éducatifs attirent le plus de participation citoyenne.
- Les professionnels interviennent surtout dans les projets économiques ou d’infrastructure.
- Les acteurs associatifs sont engagés dans des projets citoyens et communautaires.
### Localisation des projets participatifs à La Plaine Saint-Denis
*Observation **
- Les projets sont concentrés dans le centre de La Plaine Saint-Denis.
- Cette localisation montre où la participation citoyenne est la plus forte et met en évidence des zones moins couvertes.
## 6_ INTERACTIONS AVEC L'ENVIRONNEMENT 
- Les projets participatifs se situent près des zones résidentielles et services publics, ce qui facilite la mobilisation des habitants.  
- Les projets culturels et éducatifs créent des points d’interaction sociale et environnementale dans le quartier.  
- La répartition spatiale des projets montre comment l’engagement citoyen influence directement l’aménagement urbain.
## 7_ Conclusion
- Les habitants sont les principaux participants, confirmant l’importance de la mobilisation locale.  
- Les acteurs publics et privés apportent un soutien structurant et complémentaire.  
- Les projets culturels et éducatifs génèrent le plus d’engagement citoyen.  
- La localisation des projets met en évidence des zones à forte participation et d’autres à renforcer pour une couverture territoriale optimale.

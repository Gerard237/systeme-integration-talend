# systeme-integration-talend

Nous avons réalisé un système d'intégration des données commerciales journalières.

#### Source de donnée

Nous avons un répertoire(20241008) contenant les ventes journalières sur Mobilier, Technologie et Fournitures de bureau.

![alt text](https://github.com/Gerard237/systeme-integration-talend/blob/main/repertoire.png)

![alt text](https://github.com/Gerard237/systeme-integration-talend/blob/main/fichier_csv.png)

#### Création du job Talend

Nous avons créé plusieurs jobs Talend pour l'ingestion des données dans la base de données PostgreSQL. Les différentes tables sont :

- Categorie, Customer, Produit, Sous_categorie, Type_client, Vente.

Ci-dessous, le job qui charge les données provenant du fichier Catégorie : 

![alt text](https://github.com/Gerard237/systeme-integration-talend/blob/main/job.png)

#### Résultat

La creation d'un référentiel client et produit

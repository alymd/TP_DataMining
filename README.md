# TPDataMining — Pipeline KDD

## C'est quoi ce projet ?
L'objectif est de collecter des données depuis plusieurs sources
et les fusionner dans un seul DataFrame avec Pandas.

## Comment lancer le projet ?
Pour exécuter ce projet, installez les dépendances nécessaires :
```bash
pip install -r requirements.txt
```
## Structure du projet
```TPDataMiningL2/
├── data/
│   ├── student-mat.csv
│   └── movies.json
├── notebooks/
│   └── TP-KDD.ipynb
├── README.md 
└── requirements.txt
```


## Sources de données

- CSV : Dataset des étudiants (notes, âge, école)
- JSON : Dataset des films (titre, genre)
- SQL : Étudiants filtrés avec G3 > 15 (simulé)
- Web Scraping : Titres depuis Wikipedia

## Ce que fait le notebook

1. Charge le fichier CSV des étudiants
2. Charge le fichier JSON des films
3. Simule une requête SQL en filtrant les étudiants avec G3 > 15
4. Scrape des titres depuis Wikipedia
5. Fusionne les étudiants et les films en un seul DataFrame final

## Auteur

[C28916] — DA2I 

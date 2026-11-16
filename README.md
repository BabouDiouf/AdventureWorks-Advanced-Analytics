# AdventureWorks Advanced Analytics

## Analyse avancée des performances commerciales avec Python et Power BI

## 1. Présentation du projet

**AdventureWorks Advanced Analytics** est un projet d'analyse de données commerciales visant à exploiter les données de ventes d'AdventureWorks afin d'identifier les tendances commerciales, d'évaluer la performance des produits et de mieux comprendre le comportement des clients.

Le projet repose principalement sur Python pour la compréhension, la préparation, l'exploration et l'analyse des données. Power BI intervient en complément pour mettre en pratique des fonctionnalités avancées de visualisation, d'interactivité et de navigation dans les rapports.

Ce projet s'inscrit dans une démarche de Business Intelligence et d'analyse décisionnelle, avec une attention particulière portée à la qualité des données, à la pertinence des indicateurs et à leur interprétation métier.

## 2. Objectifs métier

- Comprendre la structure et les caractéristiques des données AdventureWorks.
- Évaluer et améliorer la qualité des données.
- Préparer les données pour les analyses.
- Analyser l'évolution du chiffre d'affaires et des ventes.
- Étudier la performance et la rentabilité des produits.
- Segmenter et analyser les comportements des clients.
- Identifier les tendances, les anomalies et les opportunités commerciales.
- Construire une synthèse des principaux enseignements métier.
- Mettre en pratique des fonctionnalités avancées de Power BI pour concevoir des rapports interactifs.

## 3. Technologies utilisées

| Technologie      | Utilisation                                           |
| ---------------- | ----------------------------------------------------- |
| Python           | Analyse et traitement des données                     |
| Pandas           | Manipulation et préparation des données               |
| NumPy            | Calculs numériques                                    |
| Matplotlib       | Visualisation des données                             |
| Seaborn          | Analyse graphique et visualisations statistiques      |
| Jupyter Notebook | Développement et documentation des analyses           |
| Power BI         | Visualisation interactive et fonctionnalités avancées |
| DAX              | Création de mesures et d'indicateurs dynamiques       |
| Power Query      | Préparation et transformation des données             |
| Git / GitHub     | Versionnement et publication du projet                |

## 4. Architecture du projet

```text
AdventureWorks-Advanced-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Quality.ipynb
│   ├── 03_Data_Preparation.ipynb
│   ├── 04_Exploratory_Data_Analysis.ipynb
│   ├── 05_Sales_Performance.ipynb
│   ├── 06_Product_Analytics.ipynb
│   ├── 07_Customer_Analytics.ipynb
│   ├── 08_Advanced_Analytics.ipynb
│   └── 09_Business_Insights.ipynb
│
├── powerbi/
│
├── .gitignore
├── README.md
└── requirements.txt
```

## 5. Démarche analytique

Le projet est organisé en neuf notebooks complémentaires.

| Notebook | Description |
|---|---|
| 01 - Data Understanding | Compréhension de la structure et du contenu des données |
| 02 - Data Quality | Contrôle de la qualité et identification des anomalies |
| 03 - Data Preparation | Nettoyage et préparation des tables analytiques |
| 04 - Exploratory Data Analysis | Exploration statistique et visualisation initiale |
| 05 - Sales Performance | Analyse des ventes, commandes, tendances et performances géographiques |
| 06 - Product Analytics | Analyse des catégories, produits, contributions au chiffre d'affaires et rentabilité estimée |
| 07 - Customer Analytics | Analyse démographique, comportementale et commerciale des clients |
| 08 - Advanced Analytics | Cadre méthodologique destiné aux analyses multivariées, à la segmentation avancée et aux tests statistiques |
| 09 - Business Insights | Synthèse transversale, enseignements métier et recommandations stratégiques |

## 6. Visualisation et fonctionnalités avancées avec Power BI

La partie Power BI constitue un **complément aux analyses réalisées avec Python**.

Elle a principalement pour objectif de démontrer la maîtrise de fonctionnalités avancées de Power BI, notamment en matière de personnalisation, d'interactivité, de navigation et d'exploration des données.

Les fonctionnalités mises en pratique comprennent :

- **Paramètres de champs (Field Parameters)** : permettre à l'utilisateur de sélectionner dynamiquement les indicateurs et les dimensions à analyser.
- **Info-bulles personnalisées (Custom Tooltips)** : afficher des informations complémentaires et des indicateurs détaillés au survol des éléments visuels.
- **Exploration détaillée (Drillthrough)** : accéder à des pages d'analyse spécifiques à partir d'une sélection dans un graphique ou un tableau.
- **Titres dynamiques** : adapter automatiquement les titres des visuels selon les indicateurs, dimensions et filtres sélectionnés.
- **Segments et filtres (Slicers)** : rendre les analyses interactives selon différentes dimensions, comme les périodes, les catégories de produits, les clients ou les territoires.
- **Navigation entre les pages** : faciliter le parcours du rapport et l'accès aux différentes analyses.
- **Mesures DAX dynamiques** : construire des indicateurs et des calculs qui s'adaptent au contexte de filtrage.
- **Interactions entre les visuels** : exploiter les interactions pour permettre une exploration plus flexible des données.

Cette partie permet de mettre en évidence la capacité à concevoir des rapports Power BI interactifs et personnalisables, tout en illustrant l'utilisation de fonctionnalités avancées adaptées aux besoins d'analyse métier.

## 7. Principaux résultats

L'analyse porte sur les données de ventes Internet de 2014 à 2016.

| Indicateur | Résultat |
|---|---:|
| Lignes de ventes | 58 189 |
| Commandes distinctes | 26 683 |
| Clients acheteurs | 17 918 |
| Produits vendus | 158 |
| Quantité totale vendue | 91 321 |
| Chiffre d'affaires | 29 307 836,59 |
| Coût total estimé | 27 073 480,62 |
| Bénéfice brut estimé | 2 234 355,98 |
| Taux de marque estimé | 7,62 % |

### Principaux constats métier

- La catégorie Bikes représente environ 96,6 % du chiffre d'affaires.
- La catégorie Accessories présente un taux de marque estimé d'environ 41,06 %.
- Les catégories Bikes et Clothing présentent des taux de marque estimés plus faibles.
- Les produits Jerseys et Caps présentent un déficit brut estimé cumulé d'environ 40 680,67.
- Le chiffre d'affaires diminue de 18,52 % en 2015, puis augmente de 185,89 % en 2016.
- Le panier moyen en chiffre d'affaires diminue entre 2014 et 2016, passant de 3 205,84 à 775,05.
- Les clients âgés de 45 à 64 ans constituent un segment important de la clientèle analysée.

Les coûts et bénéfices présentés sont des estimations calculées à partir des coûts standards des produits et des quantités vendues. Ils ne représentent pas des résultats comptables réels.

## 7. Limites méthodologiques

- L'analyse porte uniquement sur le périmètre des ventes Internet disponible dans le jeu de données.
- Les coûts et indicateurs de rentabilité sont estimés à partir des coûts standards.
- La période étudiée couvre les années 2014 à 2016.
- Les analyses descriptives permettent d'identifier des associations et des tendances, mais ne démontrent pas de relations causales.

## 8. Installation et utilisation

### Prérequis

- Python 3.14 ou version compatible avec les dépendances.
- Git.
- Jupyter Notebook ou JupyterLab.

### Cloner le dépôt

```bash
git clone https://github.com/BabouDiouf/AdventureWorks-Advanced-Analytics.git
cd AdventureWorks-Advanced-Analytics
```

### Créer un environnement virtuel

```bash
python -m venv .venv
```

Sous Windows :

```powershell
.\.venv\Scripts\Activate.ps1
```

### Installer les dépendances

```bash
python -m pip install -r requirements.txt
```

### Préparer les données

Les données ne sont pas fournies dans ce dépôt en raison de l'absence de licence de redistribution clairement identifiée.

Le jeu de données original est disponible sur Kaggle :

[AdventureWorks Database Sales and Budget - Kaggle](https://www.kaggle.com/datasets/nhidayahmisa/adventureworks-database-sales-and-budget)

Télécharger le fichier source, puis le placer dans :

```text
data/raw/AdventureWorks_Database.xlsx
```

Les fichiers préparés doivent ensuite être générés en exécutant les notebooks dans l'ordre, de 01 à 03.

### Lancer Jupyter

```bash
jupyter notebook
```

Ouvrir ensuite les notebooks dans l'ordre de progression.

## 9. Auteur

**Babou Diouf**

Data Analyst | Business Intelligence

- LinkedIn : [linkedin.com/in/baboudiouf](https://www.linkedin.com/in/baboudiouf/)
- GitHub : [github.com/BabouDiouf](https://github.com/BabouDiouf)

---

*Projet réalisé dans le cadre du développement d'un portfolio professionnel en Data Analytics et Business Intelligence.*
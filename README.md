# DataViz — Guide Complet de Révision

<div align="center">

![Badge](https://img.shields.io/badge/2ème%20Année-Informatique%20Décisionnelle-4fffb0?style=for-the-badge&labelColor=0d0f14)
![Badge](https://img.shields.io/badge/EST%20El%20Kelaa-2025%2F2026-7eb8ff?style=for-the-badge&labelColor=0d0f14)
![Badge](https://img.shields.io/badge/QCM-120%20Questions-ffc857?style=for-the-badge&labelColor=0d0f14)
![Badge](https://img.shields.io/badge/Licence-MIT-ff6b6b?style=for-the-badge&labelColor=0d0f14)

**Guide interactif de révision pour les examens de Visualisation des Données**  
Cours complet · Nettoyage · Visualisation · Dashboard · Power BI · 3 simulations d'examen

[ Démo Live](#démo) · [ Contenu](#contenu) · [ Installation](#installation) · [ Contribution](#contribution)

</div>

---

## Aperçu

Ce projet est une **application web interactive** conçue pour préparer les examens du module **Visualisation des Données** (2ème année ID, EST El Kelaa). Il regroupe en une seule page HTML autonome :

- Un **cours complet** avec exemples de code Python annotés
- Des **fiches de révision** couvrant tous les thèmes du programme
- **3 simulations d'examen** (QCM) de 40 questions chacune avec correction automatique et explications détaillées

> **Aucune installation requise** — un seul fichier `.html` à ouvrir dans n'importe quel navigateur.

---

##  Contenu

Le guide est structuré en **9 sections** accessibles via une navigation collante :

| # | Section | Description |
|---|---------|-------------|
| 1 | **Cours** | DataFrame, Series, GroupBy, dates, statistiques descriptives |
| 2 | **Nettoyage** | Valeurs manquantes, doublons, types, outliers, encodage |
| 3 | **Visualisation** | Matplotlib, Seaborn — syntaxe, personnalisation, subplots |
| 4 | **Graphiques** | Plotly Express, types de graphiques, graphiques interactifs |
| 5 | **Dashboard** | Dash (Plotly), callbacks, layout, déploiement |
| 6 | **Power BI** | Modèle en étoile, DAX, mesures, relations, rapports |
| 7 | **Exam 1** | Simulation QCM — 40 questions (Pandas & Nettoyage) |
| 8 | **Exam 2** | Simulation QCM — 40 questions (Visualisation & Graphiques) |
| 9 | **Exam 3** | Simulation QCM — 40 questions (Dashboard & Power BI) |

###  Technologies couvertes

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4878cf?style=flat-square&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=flat-square&logo=plotly&logoColor=white)

---

##  Fonctionnalités

- **Navigation par onglets** — passage instantané entre les sections sans rechargement
- **120 QCM interactifs** répartis en 3 examens de 40 questions
- **Correction immédiate** — feedback visuel (vert / rouge) à chaque réponse
- **Explications détaillées** affichées après chaque réponse
- **Score en temps réel** avec barre de progression
- **Message de performance** personnalisé selon le score final
- **Réinitialisation** de chaque examen en un clic
- **Blocs de code annotés** avec coloration syntaxique personnalisée
- **Tableaux de référence** pour toutes les fonctions clés
- **Design responsive** — fonctionne sur mobile, tablette et desktop
- **Zéro dépendance** — aucune installation, aucun framework externe requis

---

##  Installation

### Option 1 — Utilisation directe (recommandée)

```bash
# 1. Cloner le dépôt
git clone https://github.com/Samah-boudallaa/DataViz_Guide_Complet.git

# 2. Aller dans le dossier
cd DataViz_Guide_Complet

# 3. Ouvrir le fichier dans votre navigateur
# Sur Windows :
start DataViz_Guide_Complet.html

# Sur macOS :
open DataViz_Guide_Complet.html

# Sur Linux :
xdg-open DataViz_Guide_Complet.html
```

>  C'est tout ! Aucune installation de Python, Node.js ou autre n'est nécessaire.

### Option 2 — Téléchargement direct

1. Cliquer sur **Code → Download ZIP** en haut de cette page
2. Extraire le fichier ZIP
3. Double-cliquer sur `DataViz_Guide_Complet.html`

### Option 3 — GitHub Pages (hébergement en ligne)

Si vous avez forké ce dépôt, activez **GitHub Pages** pour y accéder depuis n'importe quel appareil :

1. Aller dans **Settings → Pages**
2. Source : `Deploy from a branch`
3. Branch : `main` / `root`
4. Cliquer sur **Save**

Votre guide sera accessible à l'URL :  
`https://<votre-username>.github.io/DataViz_Guide_Complet/`

---

## Structure du projet

```
DataViz_Guide_Complet/
│
├── DataViz_Guide_Complet.html   # Application complète (fichier unique autonome)
└── README.md                    # Ce fichier
```

> Le projet est intentionnellement contenu dans **un seul fichier HTML** pour une portabilité maximale : pas de dossiers `css/`, `js/` ou `assets/` à gérer.

---

## Design

Le guide utilise un thème **dark mode** personnalisé avec :

| Variable | Couleur | Usage |
|----------|---------|-------|
| `--bg` | `#0d0f14` | Fond principal |
| `--accent` | `#4fffb0` | Vert — éléments principaux, réponses correctes |
| `--accent2` | `#ff6b6b` | Rouge — alertes, réponses incorrectes |
| `--accent3` | `#ffc857` | Jaune — titres de cartes, avertissements |
| `--accent4` | `#7eb8ff` | Bleu — liens, notes informatives |

**Polices utilisées :**
- [Syne](https://fonts.google.com/specimen/Syne) — titres et headers
- [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) — code et badges
- [Karla](https://fonts.google.com/specimen/Karla) — corps de texte

---

## Guide d'utilisation

```
1. Ouvrir le fichier HTML dans votre navigateur
        ↓
2. Utiliser la barre de navigation sticky pour changer de section
        ↓
3. Lire les cours et fiches de révision dans les sections 1 à 6
        ↓
4. Passer les examens dans les sections Exam 1, Exam 2, Exam 3
        ↓
5. Cliquer sur une option → voir la correction + explication
        ↓
6. Vérifier votre score final et relire les sections concernées
```

### Conseils de révision

- Commencez par relire la section **Cours** puis **Nettoyage** avant de passer les QCM
- Passez l'**Exam 1** en premier (Pandas & Nettoyage) — c'est la base
- Lisez attentivement **chaque explication** même quand vous avez bon
- Visez **≥ 85%** sur chaque examen avant l'épreuve réelle
- Utilisez le bouton **Recommencer** pour repasser le même examen et consolider

---

##  Programme couvert

<details>
<summary><strong> Pandas & DataFrames</strong></summary>

- Création de DataFrames (dict, listes, CSV, Excel)
- Sélection : `loc`, `iloc`, filtres booléens
- Manipulation : `rename`, `drop`, `sort_values`, `reset_index`
- Jointures : `merge`, `concat`, `join`
- Pivot : `pivot_table`, `melt`, `stack`, `unstack`
- GroupBy : `agg`, `transform`, `filter`, `apply`
- Dates : `to_datetime`, `.dt`, `resample`, `date_range`
- Statistiques : `describe`, `corr`, `quantile`, `pct_change`

</details>

<details>
<summary><strong> Nettoyage des Données</strong></summary>

- Détection valeurs manquantes : `isnull`, `isna`, `info`
- Traitement NaN : `fillna`, `dropna`, `interpolate`
- Doublons : `duplicated`, `drop_duplicates`
- Conversion de types : `astype`, `pd.to_numeric`, `pd.Categorical`
- Outliers : IQR, Z-score, Winsorization
- Encodage : `get_dummies`, `LabelEncoder`, `OrdinalEncoder`
- Normalisation : `MinMaxScaler`, `StandardScaler`

</details>

<details>
<summary><strong> Matplotlib & Seaborn</strong></summary>

- Interface `pyplot` vs orientée objet (`fig, ax`)
- Types : `plot`, `bar`, `barh`, `scatter`, `hist`, `pie`, `boxplot`
- Personnalisation : couleurs, styles, marqueurs, annotations
- Subplots : `plt.subplot`, `fig.add_subplot`, `plt.subplots`
- `plt.tight_layout`, `plt.savefig`
- Seaborn : `heatmap`, `pairplot`, `violinplot`, `lmplot`, `FacetGrid`

</details>

<details>
<summary><strong> Plotly & Dash</strong></summary>

- Plotly Express : `px.bar`, `px.scatter`, `px.line`, `px.pie`, `px.box`
- Graphiques avancés : `px.funnel`, `px.treemap`, `px.sunburst`, `px.choropleth`
- Plotly Graph Objects : `go.Figure`, `go.Scatter`, `go.Bar`
- `update_layout`, `update_traces`, `add_trace`
- Dash : `dcc`, `html`, `@callback`, `Input`, `Output`
- Layout Dash : `dbc.Row`, `dbc.Col`, `dbc.Card`

</details>

<details>
<summary><strong> Power BI</strong></summary>

- Modèle en étoile (Star Schema) : tables de faits vs dimensions
- Relations : cardinalité 1:N, direction du filtre
- DAX : `CALCULATE`, `SUMX`, `FILTER`, `ALL`, `RELATED`, `DIVIDE`
- Mesures vs colonnes calculées
- Types de visualisations natives
- Slicers et interactions entre visuels

</details>

---

## Contribution

Les contributions sont les bienvenues ! Pour proposer une amélioration :

```bash
# 1. Forker le dépôt
# 2. Créer une branche
git checkout -b amelioration/nom-de-la-feature

# 3. Faire vos modifications dans DataViz_Guide_Complet.html

# 4. Commiter
git commit -m "feat: ajout de X questions sur le thème Y"

# 5. Pousser
git push origin amelioration/nom-de-la-feature

# 6. Ouvrir une Pull Request
```

### Idées de contribution

- [ ] Ajouter des questions sur les nouvelles versions de Pandas / Plotly
- [ ] Ajouter un mode **dark/light** toggle
- [ ] Ajouter un **minuteur** par examen
- [ ] Ajouter un **historique des scores** (localStorage)
- [ ] Traduction en anglais
- [ ] Ajout d'un 4ème examen sur des thèmes avancés

---

## Auteure

**Samah BOUDALLAA**  
Étudiante en Informatique Décisionnelle — EST El Kelaa  
Promotion 2025/2026

[![GitHub](https://img.shields.io/badge/GitHub-Samah--boudallaa-181717?style=flat-square&logo=github)](https://github.com/Samah-boudallaa)

---

##  Licence

Ce projet est distribué sous licence **MIT**.  
Libre de l'utiliser, le modifier et le partager — une étoile est toujours appréciée !

```
MIT License — Copyright (c) 2025 Samah BOUDALLAA
```

---

<div align="center">

Fait avec pour les étudiants ID d'EST El Kelaa · Bon courage pour les examens ! 🎓

 **Star ce repo si ce guide t'a aidé !** 

</div>

# movies-insights

Fournit des informations sur les habitudes de visionnage des utilisateurs au cours des différentes saisons via l'API Trakt.

## Prérequis

- Vous devez posséder une version récente de Python (3.10 ou supérieure).
- Vous devez avoir Visual Studio Code ou un éditeur permettant de lancer les Jupyter Notebooks (comme Anaconda Jupyter Notebook).
- Vous devez avoir les librairies Pandas et Matplotlib installées si ce n'est  pas le cas lancez:

```bash
pip install pandas
```
```bash
pip install matplotlib
```

## Installation

1. Clonez le repository :

    ```bash
    git clone https://github.com/amaellounkokobi/movies-insights.git
    ```

2. Accédez au répertoire du projet :

    ```bash
    cd movies-insights
    ```

## Utilisation

1. Ouvrez le Jupyter Notebook `Data_engineer_junior_NOTEBOOK.ipynb` dans un éditeur (VS Code, Anaconda Jupyter Notebook, ...).

2. Le script va effectuer une extraction de 2000 données, ce qui prendra environ 5 minutes.

3. Pour éviter cette attente, vous pouvez lancer le Notebook `analyse_NOTEBOOK.ipynb` avec un dataset déjà généré pour voir les insights.

# Insights 

Voici un résumé des insights pour un dataset d'environ 35 000 films :

# 🎬 Analyse de la Visualisation de Films & Séries 📺

## Aperçu des Données 📊

- **Personnes Concernées**: 41 cinéphiles du nord 🌍
- **Durée**: 24 ans (2000 - 2024) d'exploration de données 🕰️
- **Nombre Total de Vues**: Total de 35 983 films et séries binge-watchés ! 🍿

## Confrontation Saisonnière 🌱🌞🍁❄️

- **Hiver**: 9 097 vues 
- **Été**: 9 077 vues
- **Automne**: 8 940 vues
- **Printemps**: 8 869 vues
  
![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img1.png?raw=true)
## Palette de Genres 🎭🚀👻

- **Meilleurs Genres**:
  - **Sci-Fi**: 6 666 vues
  - **Drame**: 5 625 vues
  - **Thriller**: 5 138 vues
  - **Comédie**: 4 285 vues
  - **Horreur**: 3 931 vues
  - **Animation**: 2 542 vues
  - **Aventure**: 1 606 vues
  - **Famille**: 1 219 vues
  - **Action**: 450 vues
    
![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img2.png?raw=true)
## Visualisation par lieux 🌍🎥

- **Points Chauds**:
  - 🇸🇰 **Bratislava, Slovaquie**: 4 283 vues
  - 🏴 **Glasgow, Écosse, Royaume-Uni**: 3 718 vues
  - 🇬🇧 **Royaume-Uni**: 3 117 vues
    
![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img3.png?raw=true)
## Préférences Saisonnieres de Genre 🌟

### Hiver Enneigé
- **Sci-Fi**: 1 690 vues ❄️👽

![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img6.png?raw=true)

### Printemps Ensoleillé
- **Sci-Fi**: 1 706 vues = 🌸🚀

![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img4.png?raw=true)

### Été Chaud
- **Sci-Fi**: 1 808 vues = ☀️👾

![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img7.png?raw=true)

### Aventures Automnales
- **Sci-Fi**: 1 462 vues = 🍁👽

![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img5.png?raw=true)
  
## Connexion Âge-Genre 🧑‍🎤🧟‍♂️

- **Horreur**: Âge moyen de 37 ans,
- **Thriller**: Âge moyen de 39 ans,
- **Drame**: Âge moyen de 39 ans,
- **Comédie**: Âge moyen de 37 ans,
- **Sci-Fi**: Âge moyen de 38 ans,
  
![alt text](https://github.com/amaellounkokobi/movies-insights/blob/main/plot-images/img8.png?raw=true)


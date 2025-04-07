# Analyse-Statistique-Sarra



## Introduction

Ce répertoire GitHub est destiné à expliquer le processus utilisé pour générer des graphiques et effectuer des analyses statistiques dans le cadre de la thèse de [Votre Nom]. Tous les graphiques générés et les analyses statistiques sont présentés dans le chapitre des résultats de la thèse.

Ce code sert à illustrer comment les graphiques et les tests statistiques sont réalisés pour analyser les relations entre les variables, telles que les espèces bactériennes, le sexe, les groupes d'âge, et la résistance aux antibiotiques. Les résultats obtenus permettent d’explorer les patterns de résistance et de comparer les groupes selon des critères définis, tels que l’espèce bactérienne (*Staphylococcus saprophyticus* et *Enterobacteriaceae*) et le sexe des individus.

L'objectif de ce répertoire est de fournir un code explicatif, accompagné de visualisations détaillées et d'analyses statistiques, afin d'aider à comprendre les démarches méthodologiques et les résultats de l'analyse des données.

## Prérequis

### 1. Installer Python et Jupyter

Avant de pouvoir exécuter ce code, vous devez installer Python et Jupyter.

#### 1.1 Télécharger et installer Python

- Allez sur le site officiel de Python : [https://www.python.org/downloads/](https://www.python.org/downloads/)
- Téléchargez la version la plus récente de Python et installez-la sur votre machine.
- Assurez-vous de cocher l'option "Add Python to PATH" lors de l'installation.

#### 1.2 Installer Jupyter Notebook

- Ouvrez un terminal ou une invite de commande et tapez la commande suivante pour installer Jupyter via pip :
```bash
pip install -r requirements.txt
```

Si vous ne disposez pas de ce fichier, vous pouvez installer chaque bibliothèque individuellement en utilisant pip.

#### Liste des bibliothèques nécessaires :

- **`pandas`** : Utilisé pour la manipulation et l'analyse des données. Il permet de lire, transformer et analyser les données structurées (par exemple, les fichiers CSV).
  ```bash
  pip install pandas
  ```

- **`matplotlib`** : Utilisé pour la création de graphiques statiques. Il permet de générer des graphiques simples comme des histogrammes, des courbes, des diagrammes en barres, etc.
  ```bash
  pip install matplotlib
  ```

- **`seaborn`** : Une extension de `matplotlib`, qui simplifie la création de graphiques plus complexes et visuellement attrayants. Il est particulièrement utile pour des visualisations statistiques comme les heatmaps.
  ```bash
  pip install seaborn
  ```

- **`scipy`** : Utilisé pour effectuer des tests statistiques. Dans ce projet, il est utilisé pour le test du chi-carré afin de vérifier les relations entre différentes variables.
  ```bash
  pip install scipy
  ```

## Utilisation

Une fois que les bibliothèques sont installées et que votre environnement est prêt, vous pouvez exécuter les scripts pour générer les analyses statistiques et les graphiques. 

1. **Lancer Jupyter Notebook** : 
   Pour lancer Jupyter Notebook, tapez la commande suivante dans votre terminal :

   ```bash
   jupyter notebook
   ```

   Cela ouvrira Jupyter dans votre navigateur, où vous pourrez exécuter le code de manière interactive.

2. **Exécuter le code** : 
   Vous pouvez exécuter les notebooks  pour effectuer les analyses et générer les résultats. Assurez-vous que les fichiers de données nécessaires sont dans le bon répertoire avant d'exécuter les scripts.


Cela lancera le code et générera les résultats de l'analyse, y compris les graphiques et les fichiers CSV dans le répertoire `results/`.






# Analyse de l'Utilisation du Sol - Ville de Québec

## Description
Ce projet analyse les données géospatiales d'utilisation du sol de la Ville de Québec. Il permet de visualiser et d'analyser les différentes catégories d'utilisation du territoire urbain (résidentiel, commercial, espaces verts, etc.) afin de comprendre la distribution spatiale et les proportions des différentes utilisations du sol dans la ville.

## Structure du Projet
- `utilisation_sol.ipynb` : Notebook Jupyter principal contenant l'analyse et les visualisations
- `data/` : Dossier contenant les données géospatiales (non inclus dans le dépôt)

## Prérequis
- Python 3.6+
- Bibliothèques Python:
  - geopandas
  - dask-geopandas
  - matplotlib
  - holoviews
  - geoviews
  - jupyter_bokeh (pour les visualisations interactives)
  - datashader

## Installation
```bash
# Créer un environnement virtuel (recommandé)
conda create -n geospatial_env python=3.11
conda activate geospatial_env

# Installer les dépendances
conda install -c conda-forge geopandas dask-geopandas matplotlib holoviews geoviews jupyter_bokeh datashader
```

## Utilisation
1. Cloner ce dépôt
2. Télécharger les données d'utilisation du sol de la Ville de Québec
3. Exécuter le notebook Jupyter `utilisation_sol.ipynb`

## Données
Les données utilisées dans ce projet proviennent du portail de données ouvertes de la Ville de Québec. Le shapefile `vdq-utilisationdusol.shp` contient les polygones représentant les différentes zones d'utilisation du sol avec leurs attributs descriptifs.

Source: [Données ouvertes - Ville de Québec](https://www.donneesquebec.ca/recherche/dataset/vque_9/)

## Fonctionnalités
- Visualisation de la distribution spatiale des différentes catégories d'utilisation du sol
- Analyse statistique des proportions de chaque type d'utilisation
- Graphiques statistiques (diagrammes à barres et camemberts) montrant les proportions des principales utilisations du sol
- Cartes interactives et statiques en haute résolution

## Visualisations
Le projet permet de générer plusieurs types de visualisations:
- Cartes choroplèthes montrant la distribution spatiale des utilisations du sol
- Diagrammes à barres des 10 principales utilisations du sol par pourcentage de superficie
- Graphiques circulaires montrant la répartition des 7 principales catégories d'utilisation du sol

## Licence
Ce projet est distribué sous licence MIT. Les données utilisées sont soumises aux conditions d'utilisation des données ouvertes de la Ville de Québec.

## Contact
Pour toute question ou suggestion concernant ce projet, n'hésitez pas à ouvrir une issue sur ce dépôt.
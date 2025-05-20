# Géovisualiser pour explorer la robustesse des données, explorer la robustesse des géovisualisations 🌎 📊
## Ecole méthodologique GdR MAGIS / 2025


Cette page centralise les contenus (cours et TP) de la demi-journée d'intervention de l'AR9 "Géovisualisation" lors de **l'école méthodologique 2025 du GdR MAGIS** (Avignon).

## 📚 Cours 

<table align="center">
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/magisAR9/EcoleMAGIS/main/contenus/CM.PNG" alt="alt text" width="600"/>
    </td>
  </tr>
</table>



➡️ [support de cours](lien à venir)

<hr>

## 💻 TP 

### Objectifs 🌎
Analyser les variations des prix des transactions immobilières à partir du jeu de données fourni, proposer des facteurs qui les influencent et différentes (géo)visualisations.
<br>
<br>
**Votre objectif est de produire une ou plusieurs géovisualisations "robustes" (données, méthodes, représentation) pour explorer des logiques spatiales et territoriales du marché de l'immobilier résidentiel autour d'Avignon**.

<table align="center">
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/magisAR9/EcoleMAGIS/main/contenus/DVFpreview.PNG" alt="alt text" width="600"/>
    </td>
  </tr>
</table>

Rappel : le travail s'effectue dans l’environnement familier (logiciel, environnement de développement, langage de programmation) 

### Jeux de données 💾

 Nom de la couche | Descriptif | Producteur | Année | Téléchargement
| --- | --- | --- | --- | --- |
| DVF |Mutations DVF entre 2014 et 2023| DGFiP | 2023 | [Télécharger](https://github.com/magisAR9/EcoleMAGIS/raw/main/contenus/Mutations_DVF.gpkg)
| Departements |Contours des départements de la zone | IGN | 2024 | [Télécharger](https://github.com/magisAR9/EcoleMAGIS/raw/main/contenus/Departements.gpkg)
| EPCI |Contours des EPCI de la zone | IGN | 2024 | [Télécharger](https://github.com/magisAR9/EcoleMAGIS/raw/main/contenus/EPCI.gpkg)
| Cantons |Contours des cantons de la zone | IGN | 2024 | [Télécharger](https://github.com/magisAR9/EcoleMAGIS/raw/main/contenus/Cantons.gpkg)
| Communes |Contours des communes de la zone | IGN | 2024 | [Télécharger](https://github.com/magisAR9/EcoleMAGIS/raw/main/contenus/Communes.gpkg)
| Sectionscadastrales | Contours des sections cadastrales de la zone | DGFiP | 2024 | [Télécharger](https://github.com/magisAR9/EcoleMAGIS/raw/main/contenus/Sections_cadastrales.gpkg)


### Description du jeu de données DVF 📋

Mutations immobilières (ventes des maisons et des appartements) issus du jeux de données de Demandes de Valeurs Foncières produit par la DGFiP sur une zone autour d'Avignon pour la période 2014-2023

Le jeu de données source a été préparé pour le TP ([Méthode de préparation](https://journals.openedition.org/cybergeo/39583) / [Script R utilisé](https://htmlpreview.github.io/?https://github.com/ESO-Rennes/Analyse-Donnees-DVF/blob/main/ScriptDVF1.html))

| Champ | Description |
| --- | --- |
| `annee` | Année de la mutation |
| `nom_com` | Nom de la commmune de la mutation |
| `nom_dep` | Département de la mutation |
| `nom_EPCI` | EPCI de la muation |
| `type` | Type de mutation (*maison* ou *appartement* |
| `Prix` | Prix de la mutation |
| `Surface` | Surface de la muation |
| `Prix_m2` | Prix au m² de la mutation |
| `latitude` | Latitude  de la mutation (4326) |
| `longitude` | Longitude  de la mutation (4326) |


### Pistes de travail 🧭

Vous pouvez travailler sur une multitude de dimensions des dynamiques du marché de l'immobilier résidentiel (prix, prix au m², volume des ventes, surfaces) et ce à différetes échelles (locales, régionales) et selon différentes périodes (10 ans de mutations).

#### Graphiques exploratoires pour comprendre les données (histogramme de distribution, nuage de points,...)
#### Agrégations spatiales
* Agrégation statistiques (comptage, moyenne) dans des périmètres existants (sections cadastrales, IRIS, commmunes...)
* Agrégation statistiques (comptage, moyenne) dans des mailles (carreaux, hexagones,...)
#### Techniques cartographiques avancées
* Représentations continues
  * Lissage spatial
  * Carte de chaleur
  * Interpolations spatiales
#### Choix dans les couleurs, les méthodes de discrétisation

### Modalités pédagos 🎓
N'hésitez pas à nous solliciter pour, le cas échéant, lever des points de blocage, partager des idées ou identifier des pistes, solliciter un regard extérieur, ne pas partir dans tous les sens.
Notre objectif est d’aider chacun·e à aboutir à quelque chose en 1h30 même a minima sur la démarche, dans l'idéal à une production concrète.
Après le TP, nous souhaitons collecter les réalisations afin d'alimenter un dossier qui compile les pistes d'analyse "robustes" d'un jeu de données type DVF.

1. Exporter ou faire une capture d'écran de votre géovisualisation
2. [Uploader votre géovisualisation](https://fr.imgbb.com)
3. [Partager l'URL de votre géovisualisation dans ce document en ligne](https://mensuel.framapad.org/p/partage-geovizdvf-ael2?lang=fr)

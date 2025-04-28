# Géovisualiser pour explorer la robustesse des données, explorer la robustesse des géovisualisations 🌎 📊
## Ecole méthodologique GdR MAGIS / 2025


Cette page centralise les contenus de la demi-journée d'intervention de l'AR9 "Géovisulisation" lors de l'école thématique 2025 du GdR MAGIS (Avignon).

## Cours 📚

<p align="center">
  <img src="https://raw.githubusercontent.com/magisAR9/EcoleMAGIS/main/contenus/CM.PNG" alt="alt text" width="600" style="border: 1px solid black;"/>
</p>

➡️ [support de cours](lien à venir)

<hr>

## TP 💻

### Objectifs 🌎
A partir du jeu de données, proposer des facteurs qui influencent les prix des transactions immobilières, analyser les variations, proposer différentes (géo)visualisation sur la zone d’étude.
**Votre objectif est de produire la carte la plus "robuste" selon vous à la fois en termes de données, de méthodes comme de représentation**

Rappel : travail dans l’environnement familier (logiciel, langage de programmation) 

### Données du TP 💾

 Nom de la couche | Descriptif | Producteur | Année
| --- | --- | --- | --- |
| DVF |Mutations DVF (114756) | DGFiP | 2023
| Departements |Contours des départements (5) | IGN | 2024
| Communes |Contours des communes (648) | IGN | 2024
| Sectionscadastrales | Contours des sections cadastrales (9200) | DGFiP | 2024


### Description du jeu de données 📋

Mutations issus du jeux de données de Demandes de Valeurs Foncières produit par la DGFiP sur une zone autour d'AVignon pour la période 2014-2023

Le jeu de données source a été retravaillé pour le TP ([Méthode de préparation](https://journals.openedition.org/cybergeo/39583) / [Script R utilisé](https://htmlpreview.github.io/?https://github.com/ESO-Rennes/Analyse-Donnees-DVF/blob/main/ScriptDVF1.html))

| Champ | Description |
| --- | --- |
| `id` |ID unique pour chaque mutation |
| `annee` | Année de la mutation |
| `nom_com` | Nom de la commmune de la mutation |
| `typo_insee` | Type de commune selon l'INSEE|
| `nom_dep` | Département de la mutation |
| `nom_EPCI` | EPCI de la muation |
| `type_EPCI` | Type d'EPCI |
| `type` | Type de mutation (*maison* ou *appartement* |
| `Prix` | Prix de la mutation |
| `Surface` | Surface de la muation |
| `Prix_m2` | Prix au m² de la mutation |
| `latitude` | Latitude  de la mutation (4326) |
| `longitude` | Longitude  de la mutation (4326) |


### Pistes de travail 🧭

Vous pouvez travailer sur une multitude de dimensions des dynamiques du marché de l'immobilier résidentiel (prix, prix au m², volume des ventes, surfaces) et ceux  différetes échelles (locales, régionales) et selon différentes périodes (10 ans de mutations).

### Graphiques exploratoires pour comprendre les données (histogramme de distribution, nuage de points,...)
### Agrégations spatiales
* Agrégation statistiques (comptage, moyenne) dans des périmètres existants (sections cadastrales, IRIS, commmunes...)
* Agrégation statistiques (comptage, moyenne) dans des mailles (scarreaux, hexagones,...)
### Techniques cartographiques avancées
* Lissage spatial
* Carte de chaleur
* Interpolations spatiales
* Cartogrames (lissés)
### Choix dans les couleurs, les méthodes de discrétisation




### Modalités pédagos 🎓
On passe dans les groupes pour lever le cas échéant des points de blocage, donner une impulsion à une
personne bloquée (ou à l’inverse recentrer si une persone se perd à partir dans tous les sens ou à côté
(par ex. chercher d’autres variables). Objectif est d’aider chacune/chacun d’aboutir à quelque chose en
1h30 même si pas résultat concret, au moins la démarche.
Après le TP, ouvrir l’accès à quelques réalisations, des stagiaires en premier lieu et que nous aurons
testés. Dossier ouvert (pourra être alimenté après l’école).


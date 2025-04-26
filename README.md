# Géovisualiser pour explorer la robustesse des données, explorer la robustesse des géovisualisations
## Ecole méthodologique GdR MAGIS / 2025


Cette page centralise les contenus de la demi-journée d'intervention de l'AR9 "Géovisulisation" lors de l'école thématique 2025 du GdR MAGIS (Avignon).

## Cours 📚

<p align="center">
  <img src="https://raw.githubusercontent.com/magisAR9/EcoleMAGIS/main/contenus/CM.PNG" alt="alt text" width="600"/>
</p>

➡️ https://docs.google.com/presentation/d/1DkPvZVDv6ZATgW1UAh62uqZzWE9Ff30nfmMVGPIz7P0/edit?usp=drive_web&ouid=116972543743949717826

<hr>

## TP 💻

A partir du jeu de données, proposer des facteurs qui influencent les prix des transactions immobilières,
analyser les variations, proposer différentes (géo)visualisation sur la zone d’étude.

Rappel : travail dans l’environnement de développement / logiciel / outil familier

### Description du jeu de données
Source : .....
Le jeu de données source a été retravaillé pour le TP (lien vers topo ou script des opérations effectuées,
pour info – pas nécessaire de lire)

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


### Pistes de travail (pas nécessaire de les développer, voire simplement les énoncer à l’oral)
– Tester la forme du maillage
– Tester la position du maillage
– Tester la taille de la maille (niveaux d’agrégation)
– Tester ce qu’on “mesure” = quelle variable brute/dérivée/indicateur
– Tester ce qu’on donne “à voir”/analyse visuelle = camaieu, viridis/magma/rainbow...
– ? Tester ce qu’on donne à comprendre = avec choix titre, indicateur, discrétisation (message
cartographique) pour les cartes statiques ou les possibilité de filtrage, de mise en relation entre
données/graphiques et carte pour les interfaces dynamiques


### Modalités pédagos
On passe dans les groupes pour lever le cas échéant des points de blocage, donner une impulsion à une
personne bloquée (ou à l’inverse recentrer si une persone se perd à partir dans tous les sens ou à côté
(par ex. chercher d’autres variables). Objectif est d’aider chacune/chacun d’aboutir à quelque chose en
1h30 même si pas résultat concret, au moins la démarche.
Après le TP, ouvrir l’accès à quelques réalisations, des stagiaires en premier lieu et que nous aurons
testés. Dossier ouvert (pourra être alimenté après l’école).


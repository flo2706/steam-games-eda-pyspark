<h1 align="center">Steam Games EDA - Pyspark</h1>

<p align="center">Analyse Big Data – <em>Exploration des tendances du marché du jeu vidéo sur Steam 👾</em></p>

<br>

---

### Contexte de l'entreprise

Steam est une plateforme de distribution numérique de jeux vidéo développée par Valve, lancée en 2003.  
Elle permet notamment :

- la distribution et la mise à jour automatique des jeux (DRM)
- le jeu en ligne, le cloud gaming, et le stockage des sauvegardes
- l’accès à une communauté (chat, messagerie, marketplace)

Steam héberge aujourd'hui plusieurs dizaines de milliers de jeux, allant des productions indépendantes aux blockbusters.

---

### Objectif du projet

Ce projet vise à réaliser une analyse exploratoire des données (EDA) du catalogue Steam afin de :

- identifier les tendances majeures du marché
- comprendre les facteurs associés à la popularité et au succès commercial des jeux
- analyser la répartition des jeux par genre, éditeur et plateforme

L'étude s'inscrit dans une logique d'aide à la décision pour un éditeur de jeux vidéo souhaitant mieux positionner ses futures productions.


---

### Périmètre de l’analyse

- Données issues de la marketplace Steam
- Données semi-structurées (JSON)
- Traitement et analyse réalisés avec PySpark sur Databricks

---

### Questions d’analyse proposées

#### Analyse macro

- Quels éditeurs publient le plus de jeux ?
- Quelles périodes concentrent le plus de sorties ? 
- Quelle est la distribution des prix et des promotions ?
- Quelles langues sont les plus représentées ?
- Quelle part des jeux sont classés 16+/18+ ?

#### Analyse par genre

- Genres les plus représentés
- Genres les mieux notés 
- Genres les plus lucratifs (estimation)
- Spécialisation éventuelle de certains éditeurs

#### Analyse par plateforme

- Disponibilité des jeux sur Windows, Mac et Linux
- Spécificités de certains genres selon les plateformes

---

### Technologies utilisées

| Outil / Tech              | Rôle                                      |
| ------------------------- | ----------------------------------------- |
| **PySpark**               | Traitement distribué des données          |
| **Databricks**            | Environnement d'analyse et de visualisation |
| **Amazon S3**             | Stockage des données                      |


---

### Consultation des résultats (Analyse complète avec visualisations interactives)

- [Ouvrir l’analyse exploratoire – Steam EDA (HTML)](./Steam.html)
- Clicker sur `Download raw file`
- Ouvrir le fichier téléchargé dans votre navigateur



---

### Source des données

Données hébergées sur Amazon S3 (données pédagogiques - Jedha) :  
`s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json`

---

## Contexte

Projet initialement réalisé dans le cadre de la certification **« Concepteur Développeur en Sciences des Données » (RNCP 35288 – Jedha)**  
Bloc 2 : *Analyse exploratoire des données*. 







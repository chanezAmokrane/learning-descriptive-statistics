# Statistiques descriptives (Learning)

Ce notebook est un support d’apprentissage dédié aux bases des statistiques descriptives utilisées en data analysis.  
Chaque famille de caractéristiques regroupe plusieurs indicateurs, chacun servant à décrire un aspect précis des données.

---

## Caractéristiques de position
Indicateurs qui décrivent où se situent les valeurs dans une distribution.

- Moyenne : valeur moyenne des données, sensible aux valeurs extrêmes.
- Médiane : valeur qui partage les données en deux parties égales.
- Mode : valeur la plus fréquente.
- Quantiles : valeurs qui découpent les données en parts égales.
- Quartiles : quantiles particuliers divisant les données en quatre parties.
- Boîte à moustaches : représentation graphique de la position et de la dispersion des données.

---

## Caractéristiques de dispersion
Indicateurs qui mesurent la variabilité des données.

- Étendue : différence entre la valeur maximale et la valeur minimale.
- Écart interquartile : dispersion des données centrales (entre Q1 et Q3).
- Variance : mesure moyenne de l’écart des valeurs à la moyenne.
- Écart-type : racine de la variance, exprimée dans la même unité que les données.
- Coefficient de variation : dispersion relative par rapport à la moyenne.

---

## Caractéristiques de forme
Indicateurs qui décrivent la forme de la distribution.

- Asymétrie (skewness) : mesure du décalage de la distribution vers la gauche ou la droite.
- Aplatissement (kurtosis) : mesure de la concentration des valeurs autour de la moyenne.

## Indicateurs vérifiés lors du nettoyage des données

Les indicateurs suivants sont analysés afin d’évaluer la qualité des données avant toute analyse statistique.

- Valeurs manquantes : comptage et pourcentage de valeurs manquantes par variable afin d’identifier les données incomplètes.
- Doublons : détection des lignes dupliquées pour éviter les biais dans les calculs statistiques.
- Valeurs aberrantes : identification à l’aide des quartiles et de l’écart interquartile (IQR), complétée par des visualisations (boîtes à moustaches).
- Cohérence des données : vérification des types de variables (numérique, catégorielle, date) et des formats.
- Valeurs incohérentes : contrôle des valeurs impossibles ou hors bornes définies par le contexte des données.
- Distribution des variables : analyse de la moyenne, de la médiane et de l’asymétrie afin d’anticiper d’éventuelles transformations.


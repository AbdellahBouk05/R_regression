R Regression Analysis Notebook

Ce projet contient un notebook Jupyter avec du code R pour étudier un modèle de régression linéaire.

## Contenu du projet

Le fichier principal est :

regression_R_explique.ipynb

Ce notebook contient :

- génération de données simulées
- création d’un modèle de régression linéaire
- sélection de variables avec les méthodes :
  - forward
  - backward
  - stepwise
- analyse des résidus
- tests statistiques :
  - Shapiro-Wilk
  - Kolmogorov-Smirnov
  - Durbin-Watson
  - Breusch-Pagan
- détection des observations influentes :
  - leviers
  - résidus standardisés
  - résidus studentisés
  - distance de Cook

## Bibliothèques nécessaires

Le notebook utilise principalement le package R suivant :

```r
install.packages("lmtest")
library(lmtest)

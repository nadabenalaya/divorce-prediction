# Prédiction du Divorce — ML

J'ai choisi ce sujet parce que l'idée de prédire quelque chose 
d'aussi humain que la rupture d'un couple à partir de données 
me semblait à la fois ambitieux et contre-intuitif.

## Ce que j'ai fait
- EDA sur 170 couples, 54 features psychologiques
- Comparaison de 3 modèles : Logistic Regression (88%), 
  Random Forest (91%), XGBoost (94%)
- Interprétation psychologique des features les plus importantes

## Ce qui m'a surprise
La question la plus prédictive n'est pas sur l'amour ou 
l'attirance, mais sur la résolution des conflits (Q18). 
Ça m'a donné envie de lire la littérature de Gottman sur 
le sujet après.

## Limites
Dataset petit (170 couples), pas de cross-validation — 
je veux ajouter ça en v2.

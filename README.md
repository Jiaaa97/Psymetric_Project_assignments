# Analyse Psychométrique et Modélisation par Équations Structurelles (SEM)

Ce projet porte sur l'évaluation de la fiabilité et de la validité d'instruments de mesure psychologiques (Impulsivité et Santé Mentale) à l'aide de données d'enquêtes longitudinales (1987-1991).

### Objectifs du Projet
* **Validation de mesures :** Comparaison entre la Théorie Classique des Tests (CTT) et la Théorie de Réponse aux Items (IRT).
* **Analyse de l'Invariance :** Vérifier si les concepts (ex: satisfaction de vie) sont mesurés de manière constante dans le temps (Invariance factorielle, métrique et scalaire).
* **Détection de Biais :** Identification du Fonctionnement Différentiel des Items (DIF) selon le genre ou l'âge.

### Méthodologie & Outils
* **Langage :** R (Librairies : `lavaan`, `mirt`, `ggplot2`).
* **Modélisation :** - Analyse Factorielle Confirmatoire (CFA) longitudinale.
  - Modèles d'Équations Structurelles (SEM) pour tester les relations entre variables latentes.
  - Estimation de la fiabilité (Alpha de Cronbach, Oméga).
* **Données :** Nettoyage et traitement de fichiers SPSS (.SAV), gestion des données manquantes (Listwise deletion).

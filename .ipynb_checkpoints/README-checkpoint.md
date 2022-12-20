# Projet :  Analyse de données <span style='color:Blue'> Twitter  </span>


## Présentation

Ce projet a été effectué dans le cadre de l'unité d'enseignement "Python pour la data-science" dispensé à l'ENSAE. Conformément aux attendus de cet enseignement, ce projet est divisé en trois parties : une partie "récupération et traitement des données", une partie "modélisation", ainsi qu'une partie "analyse descriptive et représentation graphique".


## Problématique

Dans ce projet, nous tenterons de répondre à la problématique suivante : **Dans quelle mesure l'analyse de cluster de graphes permet-elle de mettre en évidence des caractéristiques propres à différents groupes d'utilisateurs de Twitter ?**

Ce projet s'est articulé autour des tweets français récoltés lors du match 🇦🇷 - 🇭🇷 du mardi 13 décembre. Nous avons souhaité travailler sur ce jeu de données dans une volonté de traiter un exemple d'actualité, mais ce projet peut évidemment s'étendre à l'étude d'autre types de requêtes Twitter.


## Lien vers le Notebook de présentation du projet

https://github.com/jveillon/Projet-Python/blob/main/Pr%C3%A9sentation_Projet.ipynb

## Lien vers le Notebook de présentation des résultats obtenus (notebook final)

https://github.com/jveillon/Projet-Python/blob/main/Analyse_descriptive_et_repr%C3%A9sentation_graphique/Cluster_analysis.ipynb

## Recommandations d'exécution

La création des bases de données via les deux API de Twitter a nécessité l'utilisation de bearers liés à différents comptes. Nous ne mettons évidemment pas à disposition ces bearers, et invitons le lecteur, s'il le souhaite, à utiliser ses propres bearers, pouvant facilement être générés en créant un compte développeur Twitter. Pour plus d'information à ce sujet, veuillez consulter l'adresse suivante : https://developer.twitter.com/en/support/twitter-api/developer-account

Par ailleurs, la visualisation sur Python des graphes obtenus, que ce soit avec scikit-network ou avec pyvis, est très coûteuse. Ainsi, nous invitons le lecteur à utiliser la petite base de données pour la visualisation des graphes, et la grosse base de données pour la détermination des différents clusters - qui elle en revanche est très rapide.



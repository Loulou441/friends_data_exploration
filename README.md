# friends_data_exploration

## Résumé du projet

Ce projet d'analyse de données a pour objectif de mettre en oeuvre diverses techniques afin d'extraire autant d'informations que possible d'un jeu de données. Il a été réalisé dans le cadre du cours SY09 (Analyse de données) de l'Université de Technologie de Compiègne.

## Data Set

Le data set est disponible sur le dépot [TidyTuesday](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-09-08/readme.md).

Le jeu de données est composé de trois fichiers CSV :
— friends.csv regroupe 67373 lignes de dialogue extraites du script de la série américaine Friends ;
— friends_emotions.csv associe à certaines de ces lignes de dialogue des émotions ;
— friends_info.csv fournit des informations sur les 236 épisodes des 10 saisons de la série.

Un rapide pré-traitement des données a été effectué, notamment des transtypages et des éliminations de doublons, ainsi qu’une jointure entre les 3 tables (jointure externe gauche pour ne perdre aucune donnée dû au caractère partiel de la table friends_emotions.csv).

## Rapport final

Le rapport final de ce projet est disponible sous format PDF sous le nom "Analyse exploratoire de données Friends". 


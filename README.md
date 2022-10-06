# Ford GoBike System Data
## Fait par MANESSONG Vanessa


## Dataset

L'ensemble de données comprend des informations sur les trajets individuels effectués dans un système de partage de vélos couvrant la grande région de la baie de San Francisco sur en février 2019. Le dataset fournit des informations sur les points de départ et les points d'arrivée de chaque voyage, le sexe des utilisateurs, le temps mis pour parcourir un trajet, la date de naissance des utilisateurs. Il est possible de trouver le dataset à cette adresse [ici](https://www.kaggle.com/datasets/chirag02/ford-gobike-2019feb-tripdata).


## Summary of Findings

Les trajets sont effectués en moins d'un jour et la plupart se font sur des distances de moins de 4000m. La durée d'un voyage ne dépend pas forcément de la distance. Car les trajets les plus longs (proche de 10000m) se font généralement en moins de temps par rapport aux trajets plus courts (moins de 6000m). La plupart de voyages s'effectuent entre 300s et 1000s. 

Les personnes dont la tranche d'âge se situe entre 23 et 40 sont les plus actives, avec une mojorité ayant près de 35 ans. Les utilisateurs majoritaires sont de type 'subscriber' et sont majoritairement des hommes. Ces derniers bien que plus nombreux effectuent des trajets plus courts que la moyenne des femmes.

Les trajets sont généralement effectués du lundi au vendredi. Pendant les weekends on observe une baisse du nombre de voyages. Le jeudi étant le jours où la plupart des activités sont entreprises. On observe également que beaucoup de trajets sont enregistrés entre 7h et 9h du matin, puis entre 16h et 18h.

Dans l'ensemble, nous il n'existe pas une forte correlation entre nos données. Ceci serait majoritairement dû au fait que les données ne concernent que le mois de février. C'est pourquoi notre analyse univariée est plus pertinente.

## Key Insights for Presentation

Pour la présentation je mets en avant la proportion des utilisateurs par rapport à leur genre et aussi par rapport au fait qu'ils soient 'subscriber' ou 'customer'. Pour se faire j'utilise des countplot vu que ce sont des variables catégorielles. Par la suite je présente la relation qui existe entre la durée d'un voyage et la distance du trajet. Je mets également en exergue comment le jour et de l'heure peuvent influencer sur la durée d'un voyage. 

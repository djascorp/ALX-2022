# Diamonds Data Exploration

## Dataset
Les données étudiées ici présent correspondent à 174 880 lignes extrait du Dataset **Ford GoBike**. Elles contiennes les données sur les trajets individuels effectués dans un système de partage de vélos couvrant la grande région de la baie de San Francisco. Le données en question contiennent les informations sur la **durée** de chaques usages, les informations sur les **stations** de départ et d'arriver. On y trouve aussi des informations sur les **velos** et sur les **utilisateurs** comme leurs années de naissance et leurs types. 

## Summary of Findings
Dans cette exploration, nous avons pu constaté que, le dataset de départ comporte des valeurs manquantes et des colonnes dans la mauvaise format qui necéssite de la nettoyage au début de l'opération. Puis, lors des exploration des données, la majorité des tours ont un temps inférieur à 1500 secondes.<br>
Il peut aussi être important de retenir le fait que les utilisateurs sont plus actif lors des **week-days** que les **week-end** plus précisement les utilisateurs de type **Subscriber**. Bien que les Subscriber sont plus nombreuses que les **Customer** notre analyse s'est basée sur les proportions. En faisant l'exploration par rapport à l'âge, on peut dire que la majorité les utilisateurs les plus actifs sont entre 25 et 40 ans et la durée des utilisations diminues avec l'âge. <br>
Lors de l'analyse de la distribution horaire, on constate que les utilisateurs en général sont actifs dans l'utilisation des velos entre 7h et 20h. Le préférence des utilisateurs sont les velos qui ne sont pas tout trajet.


## Key Insights for Presentation
Pour la présentation, nous nous sommes focalisés sur les principaux facteurs qui pourraient être utilisé pour augmenter le nombre d'utilisateurs des velos. Pour cela, nous avons analysé la durée des utilisations, le nombre des utilisations et leurs relation avec l'**age** de l'utilisateur, les **jours de la semaine** et les **heures d'utilisation**.

Ces analyses nous a permis de voir que:
- Les utilisateurs les plus actifs sont âgé de 25 à 40 ans
- Il y a plus d'utilisation les **weekday** que le **weekend**
- Une sur-utilisation survient à **8h** et à **17h**, soit les heures de pointe

À partir de cela, nous pouvons alors en conclure que ces velos sont très utilisées comme moyen de locomaution pour se rendre au travail. 

### Rendu

Lien GitHub ou dans un zip en fichier joint dans l'email, peu importe.


### Objectif

Réaliser une petite application Vue.js qui affichera sous forme de liste les posts ProductHunt pour un jour sélectionné.

Au dessus de la liste, des statistiques de la journée sont affichées : nombre de posts, votes, commentaires, et makers.

Au dessus des statistiques, un select permet de choisir une journée parmi les 30 jours précédents (voir ressource 4).


### Résultat attendu

Résultat attendu en images : screen1.jpg + screen2.jpg.

Résultat attendu en vidéo (le select n'est pas visible sur l'enregistrement, voir screen2.jpg) :
https://www.useloom.com/share/3f1ba556240e40f2be18ebd5aacb788d

Respecter le plus fidèlement possible le design des screens.


### Contraintes techniques

Stack obligatoire :
- Vue.js
- GraphQL avec Apollo
- Le package "apollo-datasource-rest" qui permet de connecter Apollo avec l'API de Product Hunt

Pour intégrer Apollo à Vue.js, il est conseillé d'utiliser le package "vue-apollo" https://vue-apollo.netlify.com/guide/

Le rendu final doit comporter 2 dossiers : un dossier "client" qui contient toute l'application Vue.js, et un dossier "server" qui contient toute la gestion des données avec Apollo.

Ne pas hésiter à utiliser Vue CLI pour la mise en place de l'architecture client.

Ne pas hésiter à mettre en place des outils comme vuex ou vue-router afin de démontrer que vous avez une bonne connaissance du framework et des bonnes pratiques, même si ils ne sont pas forcément nécessaires pour ce petit projet. Côté CSS, l'utilisation d'un préprocesseur ou d'un framework tel que Tailwind CSS est recommandé.


### Ressources

Pour utiliser l'API ProductHunt, il faut avoir un compte sur ProductHunt. 
Pour ce test, il est demandé d'utiliser l'API V1, et non la V2.
Pour accéder aux données de l'API il suffit de générer un token en créant une application sur ProductHunt (voir ressource 1). 

- (1) https://api.producthunt.com/v1/oauth/applications
- (2) https://api.producthunt.com/v1/docs/oauth_client_only_authentication/oauth_test_use_the_client_level_token_for_read_api_access
- (3) https://api.producthunt.com/v1/docs/posts/posts_index_get_the_tech_posts_of_today
- (4) https://api.producthunt.com/v1/docs/posts/posts_index_request_previous_day_with_%60days_ago%60_parameter_(tech_category)

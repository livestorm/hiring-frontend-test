### Rendu

Lien GitHub ou dans un zip en fichier joint dans l'email, peu importe.


### Objectif

Réaliser une petite application Vue.js qui affichera sous forme de liste les posts ProductHunt pour un jour sélectionné.

Au dessus de la liste, des statistiques de la journée sont affichées : nombre de posts, votes, commentaires, et makers.

Au dessus des statistiques, un select permet de choisir une journée parmi les 30 jours précédents.


### Résultat attendu

Résultat attendu en images : screen1.jpg + screen2.jpg.

Important : **Respecter le plus fidèlement possible le design des screens**.

Résultat attendu en vidéo (le select n'est pas visible sur l'enregistrement, voir screen2.jpg) :
https://www.useloom.com/share/3f1ba556240e40f2be18ebd5aacb788d


### Contraintes techniques

Stack obligatoire :
- Vue.js
- GraphQL avec Apollo

Pour intégrer Apollo à Vue.js, il est conseillé d'utiliser le package "vue-apollo" https://vue-apollo.netlify.com/guide/

Le rendu final doit comporter 2 dossiers : un dossier "client" qui contient toute l'application Vue.js, et un dossier "server" qui contient toute la gestion des données avec Apollo.

Ne pas hésiter à utiliser Vue CLI pour la mise en place de l'architecture client.

Ne pas hésiter à mettre en place des outils comme vuex ou vue-router afin de démontrer que vous avez une bonne connaissance du framework et des bonnes pratiques, même si ils ne sont pas forcément nécessaires pour ce petit projet. Côté CSS, l'utilisation d'un préprocesseur ou d'un framework tel que Tailwind CSS est recommandé.


### Ressources

Pour utiliser l'API ProductHunt, il faut avoir un compte sur ProductHunt.

Pour ce test, il est demandé d'utiliser l'API V2.

Pour accéder aux données de l'API il suffit de générer un token en créant une application sur ProductHunt (voir ressource 1). 

- (1) https://api.producthunt.com/v2/oauth/applications
- (2) https://api.producthunt.com/v2/docs/oauth_user_authentication/oauth_token_use_the_access_grant_code_you_received_through_the_redirect_to_request_an_access_token
- (3) https://ph-graph-api-explorer.herokuapp.com/

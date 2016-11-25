## Boucles Jekyll

 
 {% for page in site.pages %}
  < a href="page.url">{{page.title}}</a >
 {% endfor %}
 
 
 Permet d'afficher le titre de la page dans la page elle-même, sans fichier de template ou autre.
 
 
 ## Billets de blog
 
 Créer dossier _posts pour les posts et dans le dossier _layouts le fichier posts.html.
 
 
 2016-11-09-titre.md
 
 post.date / post.title
 
 
 Utiliser les boucles pour afficher les articles.
 
  Dans index.html :
 
 {% for post in site.posts %}
  < h3>{{post.title}}</h3 >
  < p>{{post.content}}</p >
  < a href="{{post.url}}">Lire l'article seul</a >
 {% endfor %}
 

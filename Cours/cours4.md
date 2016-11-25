## Structure fichiers partagés

* flatfiles
  * index.html
  * _config.yml
  * _layouts --> dossier comportant les fichiers template
    * default.html
    
Dans index.html, placer "layout: default" dans l'en-tête du fichier, entre les tirets.

Dans le default.html, appeler le contenu par {{content}}.

Création de 3 fichiers template, head.html / header.html / footer.html.

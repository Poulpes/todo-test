# Task Manager

### Sommaire

Il s’agit ici de développer un outil simple (type Trello) qui permettra à l’utilisateur de gérer ses projets et la liste des tâches relatives à ces projets.

### User stories

* Je dois pouvoir sign-in/sign-up avec un email/mot de passe ou via Facebook ;
* Je dois pouvoir create/delete des projets ;
* Je dois pouvoir ajouter/supprimer des tâches à un projet ;
* Je dois pouvoir donner un ordre de priorité à des tâches au sein d’un projet ;
* Je dois pouvoir attribuer une deadline à une tâche ;
* Je dois pouvoir marquer une tâche comme “réalisée” ;
* Je dois pouvoir ajouter des commentaires à une tâche ;
* Je dois pouvoir supprimer un commentaire ;

### Pré-requis techniques

* Il doit s’agir d’une application web avec un backend RubyOnRails et une database relationnelle (Postgresql) ;
* Il est nécessaire de gérer à la fois l’authentication ET l’authorization : l’utilisateur ne doit pouvoir accéder qu’à ses propres projets.
* L’utilisation de gems (notamment [Devise](https://github.com/plataformatec/devise) et [Pundit](https://github.com/elabs/pundit)) est recommandée.
* Les validations doivent se faire aussi bien côté client que côté serveur ;
* L’application doit fonctionner entièrement en mode “single page” avec des requêtes AJAX (sans rechargement de la page) ;
* La stack front est libre. En plus de HTML5/CSS3, le candidat est libre d'utiliser un framework css ou non (ex: Materialize, Booststrap) et un framework JS ou non (ex: React) ;
* Toute attention portée à l’UX de l’application sera appréciée 🙂

### Workflow

* Créer un repo et invite @Poulpes à collaborer
* Commit et push le plus régulièrement possible.
* Prévois un déploiement sur Heroku ou CleverCloud ou autres solutions de Hosting

* Tu as 96h pour réaliser ce test. Si tu n'as pas terminé, ce n'est pas grave du tout 😉 L'idée est juste d'évaluer la façon dont tu travailles et tu t'organises.
* Bon courage 🚀

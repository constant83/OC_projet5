# Blog OC-P5

## Auteur
[Constant Cuvelier - 2022]
[cuvelier.constant@gmail.com](mailto:cuvelier.constant@gmail.com)

## Badge  

## Introduction

Ça y est, vous avez sauté le pas ! Le monde du développement web avec PHP est à portée de main et vous avez besoin de visibilité pour pouvoir convaincre vos futurs employeurs/clients en un seul regard. Vous êtes développeur PHP, il est donc temps de montrer vos talents au travers d’un blog à vos couleurs.
Description du besoin

Le projet est donc de développer votre blog professionnel. Ce site web se décompose en deux grands groupes de pages :

    les pages utiles à tous les visiteurs ;
    les pages permettant d’administrer votre blog.

Voici la liste des pages qui devront être accessibles depuis votre site web :

    la page d'accueil ;
    la page listant l’ensemble des blog posts ;
    la page affichant un blog post ;
    la page permettant d’ajouter un blog post ;
    la page permettant de modifier un blog post ;
    les pages permettant de modifier/supprimer un blog post ;
    les pages de connexion/enregistrement des utilisateurs.

Vous développerez une partie administration qui devra être accessible uniquement aux utilisateurs inscrits et validés.

Les pages d’administration seront donc accessibles sur conditions et vous veillerez à la sécurité de la partie administration.

Commençons par les pages utiles à tous les internautes.

Sur la page d’accueil, il faudra présenter les informations suivantes :

    votre nom et votre prénom ;
    une photo et/ou un logo ;
    une phrase d’accroche qui vous ressemble (exemple : “Martin Durand, le développeur qu’il vous faut !”) ;
    un menu permettant de naviguer parmi l’ensemble des pages de votre site web ;
    un formulaire de contact (à la soumission de ce formulaire, un e-mail avec toutes ces informations vous sera envoyé) avec les champs suivants :
        nom/prénom,
        e-mail de contact,
        message,
    un lien vers votre CV au format PDF ;
    et l’ensemble des liens vers les réseaux sociaux où l’on peut vous suivre (GitHub, LinkedIn, Twitter…).

Sur la page listant tous les blogs posts (du plus récent au plus ancien), il faut afficher les informations suivantes pour chaque blog post :

    le titre ;
    la date de dernière modification ;
    le chapô ;
    et un lien vers le blog post.

Sur la page présentant le détail d’un blog post, il faut afficher les informations suivantes :

    le titre ;
    le chapô ;
    le contenu ;
    l’auteur ;
    la date de dernière mise à jour ;
    le formulaire permettant d’ajouter un commentaire (soumis pour validation) ;
    les listes des commentaires validés et publiés.

Sur la page permettant de modifier un blog post, l’utilisateur a la possibilité de modifier les champs titre, chapô, auteur et contenu.

Dans le footer menu, il doit figurer un lien pour accéder à l’administration du blog.

## Build with 

- [Startbootstrap Clean Blog](https://github.com/startbootstrap/startbootstrap-clean-blog)
- [AdminLTE-3.0.5](https://adminlte.io/themes/v3/)
- Twig
- Jquery
- Bootstrap
- PHPMailer

## Requirements 

- PHP 7.4
- COMPOSER
- MYSQL
- Web Server

## Installation

- Clone / Download the project
- Config your webserver to point on the project directory
- Composer install in src directory
- Unzip and Import Database with blog-oc-p5.sql.zip file
- Rename config/config.php.sample in config/config.php and add your database and email smtp server infos

## Demo Datas 
The database contains already some data so you can test the blog.

There is already some users so you can see different views of the blog. If you want to create a new admin register you and modify in the database the role property ROLE_USER to ROLE_ADMIN of your new user and deletes demo users to secure.
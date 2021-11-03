# first-mvc-with-admin
first MVC with administration in PHP 7 procedural - MariaDB with InnoDB engine - Session management

## GIT

## Structure

### Dossiers de base 

Ce sont nos dossier "non  MVC"

`/.git`
Contient nos changement git, ne jamais envoyer sur ftp

`/data`
Nos données de préparation et de création du site, peut se trouver sur github ou pas, inutile en ftp 

`/public`
Dossier accessible à l'utilisateur de votre site, c'est ici que l'on met le controleur frontal `index.php` et dossiers publiques `css`,`js`,`img`, ...

- index.php -> notre front controller

### Dossiers MVC

`MVC` est un design pattern (patron de conception) signifie 
- Model
- View
- Controler

C'est une manière de diviser le code pour : 

1. Avoir unse structure commune
2. Déléguer les taches sans risque d'ecrasement de fichier
3. Pouvoir séparer en logique métier la structure du site(web design sur vue, web dev sur modèles et controleurs, chef de projet impose la structure)

## Virtualhost

On crée en local un virtualhost avec wamp vers `votre_chemain.../first-mvc-with-admin/public`

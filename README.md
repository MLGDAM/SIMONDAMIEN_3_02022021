# ohmyfood
Troisième projet de la formation "Développeur web" chez OpenClassroom. L'objectif de ce projet est d'intégrer des effets CSS avancés, de mettre en place une structure de navigation via le pré-processeur Sass et d'assurer la cohérence graphique à tout niveau en responsive.
Le site  Ohmyfood! est une entreprise de commande de repas en ligne. Le concept permet aux utilisateurs de composer leur menu en avance parmi 4 restaurants parisiens et d'éviter une perte de temps à consulter la carte !

## Livrables attendus

### Contenu des pages :

- Effectuer la réalisation de la page d'accueil et des 4 pages de détails des restaurants parisiens.
 
### Effets graphiques et animations :

##### Boutons :

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible. 
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic. 

##### Page d’accueil :

- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.
 
##### Pages de menu :

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

## Les contraintes techniques

- Le développement devra se faire en CSS, sans JavaScript.
- Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus. 
- Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML. 
- Le code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte au validateur W3C HTML et CSS.
- L’ensemble du site devra être responsive sur mobile, tablette et desktop. 
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox. 

## Notes sur la réalisation

- Le site respecte bien les fonctionnalités et les contraintes techniques pour l'intégration de la maquette.
- Afin de faciliter le code, la maquette a été délimité en différentes parties via les balises sémantiques afin de structurer les page (des notes additionnelles sont disponible aussi bien dans le HTML que dans le CSS afin de faciliter la lecture).
- Le code est structuré avec l'utilisation du pré-processeur SASS, et son architecture le PATTERN -1.
- La version du projet a été réalisée en partie sur le navigateur Chrome en version MOBILE-FIRST, puis adapté dans un second temps pour les tablettes, puis les écrans et très grands écrans .
- Le code ne contient aucune erreur au validateur W3C HTML et CSS.
- Le code a été versionner sur GIT et déployé sur GITHUB a l'addresse suivante https://mlgdam.github.io/SIMONDAMIEN_3_02022021/ 

## Notes sur l'utilisation de mes outils

Pour ce projet, j'ai utilisé l'éditeur **VISUAL STUDIO CODE**, les plugins **LIVE SERVER**, **PRETTIER**, **SASS**, **GITHUB**, et son terminal de commande **GITBASH**.

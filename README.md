 - Spring web: création des services web flexible et manipuler  des charges xml
 - JPA: est une interface de programmation Java permettant aux développeurs d'organiser des données relationnelles dans des applications utilisant la plateforme Java
 - Hibernate : Hibernate est une solution open source de type ORM (Object Relational Mapping) qui permet de faciliter le développement de la couche persistance d'une application. Hibernate permet donc de représenter une base de données en objets Java et vice versa
 - H2 :  H2 est un système de gestion de base de données relationnelles écrit en Java. Il peut être intégré à une application Java ou bien fonctionner en mode client-serveur. 
 - Thymeleaf : Thymeleaf est un moteur de template, sous licence Apache 2.0, écrit en Java pouvant générer du XML/XHTML/HTML5. Thymeleaf peut être utilisé dans un environnement web ou non web. Son but principal est d'être utilisé dans un environnement web pour la génération de vue pour les applications web basées sur le modèle MVC.

Etape 13:

1. avec le getmapping
3.avec cette partie du code <p th:text="'bonjour, ' + ${nomTemplate} + '!' "/> /*${nomTemplate} etant la variable pris en compte*/

Etape 17:

Une table Address est créée dans la base de donnée

Etape 20:

On voit les données qui s'affiche a l'écran

Etape 23:

L’annotation @Autowired permet de faire l’injection de dépendances entre les beans de l’application, le conteneur Spring va creer le bean, le chercher et l’injecter automatiquement

Liens GIT: https://github.com/Origami0067/DM_POO.git

J'ai eu un soucis avec mon premier projet et en suivant les instructions, j'arriver a compiler mon projet. J'ai dû reproduire un tuto pour le faire marcher.le nom de l'artifact n'est pas le même mais le code a l'interieur est exactement pareil

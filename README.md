# FinalforPrezP3
projet P3 open classroom

Compilation et lancement de l’application du projet P3 :

1. via Eclipse, ou autres IDE :

- Menu File → Open project from file system – puis se positionner sur le dépôt GIT téléchargé.

- Intégration de la librairie Log4j, qui se situe dans le dépôt GIT, à l’intérieur du dossier «Lib» :

clic droit sur le projet à l’intérieur d’éclipse, puis «Build Path» →	Configure Build Path
Add Jar et on selectionne le fichier jar, situé dans le dossier Lib téléchargé de GIT.


- Lancement de l’application via la commande Run

- le logiciel demande immédiatement de donner le nom du fichier à lister.
On indique alors config.properties.txt


2- via le fichier Application.jar qui est également inclut dans le dépôt GIT.
Ici il faut utiliser l’invite de commande (ou terminal), via la commande
java -jar

3- compilation et exécution via le terminal :
- Compilation du projet à l’aide de la commande javac (qui vient transformé les classes .java en .class).
- Exécution du projet, en utilisant la commande java
dans ce contexte, il est nécessaire d’indiquer le classpath via la commande -cp
ce dernier doit inclure le jar log4j / le fichier log4j.xml (fichier spécifiant les propriétés du logger) et la classe Main,




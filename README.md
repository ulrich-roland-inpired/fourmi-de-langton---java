# FOURMI DE LANGTON
Url     : https://github.com/ulrich-roland-inpired/fourmi-de-langton---java
Licence : Creative Commons
================================================================================================================================

On nomme fourmi de Langton un automate cellulaire (voir machine de Turing) bidimensionnel  comportant un jeu de règles très
simples. On lui a donné le nom de Christopher Langton, son inventeur. Elle constitue l'un des systèmes les plus simples
permettant de mettre en évidence un exemple de comportement émergent.

================================================================================================================================

Ce document intitulé « FOURMI DE LANGTON » est mis à disposition sous les termes de la licence Creative Commons.
Vous pouvez copier, modifier des copies de cette source, dans les conditions fixées par la licence, tant que cette note y
apparaît clairement.

================================================================================================================================
Description :
================================================================================================================================

Voici un code modélisant l'évolution d'une fourmi de Langton pour lequel je me suis attaché à suivre le design pattern MVC.
L'interface graphique est réalisée avec Swing.

Le déplacement de la fourmi sur le damier suit l'algorithmique suivante :

- Si la fourmi arrive sur une case blanche, elle tourne à  gauche et la case du damier devient rouge.

- Si la fourmi arrive sur une case rouge, elle tourne à  droite et la case du damier devient blanche.

L'évolution est interessante, alors que le comportement de la fourmi semble chaotique, l'ordre revient apres 
un nombre de pas suffisant!

N'ésitez pas à  me dire si une partie du code vous semble obscure et me faire part de toute remarque. 

J'ai écrit ce programme dans le but de travailler sur Java, ma compréhension du pattern MVC et des méthodes du Génie Logiciel.
================================================================================================================================

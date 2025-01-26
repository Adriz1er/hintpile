## objectif du projet
Le projet a pour objectif de fournir un support web de bonnes pratiques pour les personnes de chez Thalès qui veulent envoyer des satellites dans l'espace.
### périmètre du projet
Ce projet a pour utilisateur les ingénieurs de chez Thalès Alenia Space ; et être compatible avec le plus de navigateurs possibles.
Il doit donc y avoir une documentation.
Il faut que le support de bonnes pratiques soit suffisament minimaliste pour tourner sur un raspberry pi.
## contexte de l'entreprise
Thalès doit révolutionner l'accès à l'espace pour la France et l'Italie, les pays où l'entreprise est implantée.
## description de la solution retenue
On a une base de donnée en mysql, le language pour envoyer des informations au serveur est php
### pré-requis
- Version PHP : 8.2 minimum
- Version MySQL : 3.4 minimum
- Extensions PHP requises :
    - PDO
    - MySQL
    - JSON
# organisation du projet
## type de kanban utilisé
l'outil est clickup
![[kanban-1.png]]
![[kanban-2.png]]
## explication
chaque tâche a une priorité et est décomposé en sous-tâches, ses sous-tâches peuvent avoir des statuts, par exemple si c'est un problème, une action etc... ; et à qui elle est assignée

Les différents lotissements sont : 
- la base de donnée 
- le php pour discuter avec le serveur web
- la gestion des versions avec git
- la configuration d'un raspberry pi pour faire tourner le programme
## charges
5 étudiants 5 jours par semaine.
un raspberry pi (petit ordinateur qu'on branche à un écran)
## risques
- difficultés liées au fait que ça doit tourner sur un raspberry
- respecter les délais
- s'assurer que tout soit bien fonctionnel et que chaque étudiant remplie bien son rôle
- bug
## outil
- clickup : permet de faire kanban, liste et gantt

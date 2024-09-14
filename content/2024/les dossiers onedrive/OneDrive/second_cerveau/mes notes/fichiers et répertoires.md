---
tag:
---
`-` sert pour les fichiers
`.` sert pour les dossiers

Pour copier un fichier ou répertoire il faudra écrire quelque chose du type : 
`cp [chemin source] [chemin destination]` ^[[[arborescence#chemin relatif et chemin absolu]]]
Et pour si copier les "sous" répertoires on écrit : `cp -R [chemin source] [chemin destination]`

Pour déplacer un fichier ou un répertoire, il faudra écrire quelque chose du type : 
`mv [chemin source] [chemin destination]`

un `.` dans le nom fait en sorte qu'un élément soit caché
`- a` permet de voir ce qui est caché
`-l` permet de voir plus d'infos 
## fichier
contient des données

Pour supprimer un fichier quelque chose du type : 
`rm [fichier à supprimer]`
Pour lister les informations concernant un fichier : `ls -l [chemin du fichier]`. 1° colonne : droits 3° propriétaire 4° groupe 5° taille 6° date de création 7° nom du répertoire
Afficher le contenu d'un fichier : `cat [chemin fichier]` et `more [chemin fichier]` ; `cat` affiche une page alors que `more` affiche ligne par ligne
## répertoire
peut contenir des [[#fichier]].
Il contient toujours un raccourci `.` vers lui-même, et `..` vers dossier père

Pour créer un répertoire on peut faire quelque chose du type : 
`mkdir [chemin répertoire]` 

Pour supprimer un répertoire vide : `rmdir [chemin du répertoire]`
Pour supprimer un répertoire et ce qu'il contient `rm -R [chemin du répertoire]`
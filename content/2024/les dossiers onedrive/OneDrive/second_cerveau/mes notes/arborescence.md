---
tag:
---
tous les [[fichiers et répertoires#répertoires|répertoires]] et [[fichiers et répertoires#fichiers|fichiers]], et le tout premier est `/`
L'arborescence Linux regroupe : 
- le noyau du système
- les données de tous les utilisateurs
	- un repertoire personnel
	- le root (administrateur) est la seule personne qui peut modifier les accès d'une machine

Pour se déplacer dans l'arborescence `cd [chemin]`
Pour afficher le répertoire courant (où on est actuellement) `pwd`
Pour lister le contenu d'un répertoire `ls [chemin du répertoire]` ^947702

Pour émuler une machine : `xterm &`
`SSH [nom de la machine]` permet de nous connecter sur une autre machine et (`-l` affiche les processus de login) et exit pour quitter d'une autre machine.

## Droits des [[fichiers et répertoires]] 
`u` propriétaire, , `g` groupe, `o` autres utilisateurs, `a` tous
changer les droits d'un fichier ou répertoire en mode relatif `chmod [droits en fonction des types d'utilisateurs] [chemin]`, on peut regrouper plusieurs utilisateur dans une même commande
`r` lire
`w` écrire
`x` executer

`u`|`g`|`o`
--|--|--
`r``w``x`|`r``w``x`|`r``w``x`
[trois chiffres en binaire]|101|010

Pour exprimer les droits en mode absolu : 
On doit autoriser les 3 droits aux 3 groupes d'utilisateurs en utilisant le binaire
Pour définir les droits initiaux : 
`umask [3 chiffres décimaux correspondant au code binaire du masque]`. Pour trouver quel code appliquer : 

le [[binaire]] est inverse : 0 donner le droit, 1 ne pas donner le droit
	droits initiaux d'un fichier : un fichier n'aura jamais les droits d'execution
	droits d'execution pour un repertoire : avoir le droit de s'y déplacer

who permet de savoir qui est connecter en même temps que nous sur la machine et `wc -l` permet d'afficher
`man [commande]` permet de savoir quoi faire avec une commande une sorte de documentation
## répertoire personnel
là où les données nous appartiennent personnellement et là où on se trouve au démarrage. Le raccourci est ~ généralement (pas forcément pour un en particulier, mais on ne précise pas c'est votre le notre personnellement qu'il ramène)

Mais n'est pas forcément le répertoire où on est ^[[[arborescence#^947702]]]
## chemin relatif et chemin absolu
lors d'une commande on peut simplement marquer `./`
### chemin absolu
chemin exprimé à partir de la racine et commence toujours par un `/`
Exemple : `/ect/passwd`, le nom du fichier est `passwd.`, dans un sous répertoire de `/` 
### chemin relatif
chemin exprimé à partir de l'endroit où on est et commence toujours par `./` (on descend) ou par `../` (on remonte)
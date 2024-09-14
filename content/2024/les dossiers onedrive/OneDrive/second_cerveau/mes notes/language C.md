---
aspiration: []
---
toujours très utilisé car libre et indépendant de la machine et du système d'exploitation

développé en 1973 par Denis Ritchie

- code enregistré dans un fichier *.c*
- compilation du code : `gcc -o <nomfic à exe> <nom fic code.c>`. 
	- ce qui se passe c'est évaluation et execution 
- le code ascii est utilisé pour donner à un caractère une valeur à stocker

commandes récurrentes :
- les `{` permet de lister les variables
- on doit mettre des `;` quand on va à la ligne
- `#` s'execute avant le programme
	- `#include` permet d'utiliser une bibliothèque

## 3 types de base en C :
- type entier : `int`
	- valeur entière signée ^[[[binaire#complément à 2]]]
	- taille : 2 octets

## type pointeur :
valeur stockée dans une variable de type pointeur : une adresse mémoire où se trouve une autre variable
- déclaration d'un pointeur : `<type>* <Nomptr>`
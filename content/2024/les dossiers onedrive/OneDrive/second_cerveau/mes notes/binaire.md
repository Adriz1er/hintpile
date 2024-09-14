---
tag:
---
Pour passer de binaire à base de 10 : à chaque colonne vers la gauche on ajoute $1$ à la puissance de $2$ et on part de $0$
Pour passer de base $10$ à binaire on peut diviser par $2$ puis diviser par $2$ le quotient etc... jusqu'à ce que ce soit impossible. Une méthode plus pratique on peut faire un tableau avec chaque colonne associée à une puissance de deux qu'on peut retirer.
Pour signifier que l'on passe en binaire on peut utiliser $\%$  

Les chiffres binaires sont regroupés par $8$ par l'ordinateur, ce qu'on appelle les octets.
Pour savoir combien d'octets sont nécessaire on fait $$\log_{2} [valeur]$$(et $\log_{2}=\frac{\log_{10}}{\log2}$) 

Pour écrire des réels en binaire :
1. on encode la partie entière 
2. et la partie décimale séparément, 
	- [ ] que la partie décimale on multiplie par $2$ jusqu'à ce qu'il n'y ait plus de chiffre derrière la virgule #noté 
		- [ ] prendre ce qui dépasse de la virgule #noté 
		- [ ] écrire en écriture scientifique #noté
3. mettre un nombre pour exposant en excédent ...
	- [ ] on prend l'exposant et (si simple précision) on ajoute 127 #noté

La norme IEEE 754 pour encoder les informations
	- la simple précision 23 bits pour la mantisse
	- double précision 52 bits pour la mantisse
## Valeur absolue signée
Pour indiquer si positif ou négatif, le bit de poids le plus fort indique le signe :
$$0 \to \text{positif}$$
$$1 \to \text{negatif}$$ ^3670e3

Elle n'est pas pratique.

L'intervalle est décalé : $[-(2^{N-1}-1);2^{N-1}-1]$
## complément à 2
le Cà2 est la technique la plus utilisée pour coder les entiers négatifs.
le complément à 2 ne marche pas quand la retenu qui dépasse est différente de la retenue sur le dernier bit
Pour convertir en Cà2 un entier négatif :
1. on écrit sa valeur absolue
2. inverse les bits
3. ajoute 1

pour convertir en binaire cà2 c'est pareil

L'intervalle est décalé : $[-2^{N-1};2^{N-1}-1]$

Lorsqu'une machine encode un entier signé,
- si positif -> RBNS
- si négatif -> cà2

Avantage n°2 la méthode du complément à 2 permet de faire des opérations d'entiers signés justes. On retrouve que : 
![[binaire#^3670e3]]
La dernière bit pose donc toujours problème et le dépassement de capacité aussi

Autre méthode pour convertir en Cà2 :
1. chercher premier 1
2. inverser tout les chiffres après

Et pour convertir en décimal tout est pareil sauf que $2^{7}$ devient $-2^{7}$.
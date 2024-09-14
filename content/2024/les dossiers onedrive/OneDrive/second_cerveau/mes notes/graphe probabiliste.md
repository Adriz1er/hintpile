---
MOC: []
---
Un graphe probabiliste est 
- un graphe pondéré
- orienté
- tel que la somme des arêtes partant d'un sommet fait toujours 1
## matrice d'état
Une matrice *d'état* est une matrice **ligne** représente la loi  de probabilité des états possibles

Exemple : $$P=(p;1-p) \text{ pour 2 sommets}$$
Une matrice de *transition* est une matrice carrée d'ordre $n$ où $n= \text{nombre de sommets}$ tel que $\begin{pmatrix}m_{i,j}\end{pmatrix}$ poids de l'arête de $i$ vers $j$ 

Exemple : 
$$M=\begin{pmatrix}0,1 & 0,5 & 0,4 \\
0,4 & 0,2 & 0,5 \\
0,1 & 0,1 & 0,8\end{pmatrix}$$
### théorème
On a : 
$$P_{n+1}=P_{n} \times M$$
$$P_{n}=P_{0} \times M^{n}$$
#### théorème
Si le graphe est d'ordre $2$ ou $3$, alors : 
Il existe un état stable lorsque il existe une puissance de $M$ ne contenant pas de $0$
##### théorème
Dans ce cas, $P_{n}$ tend vers $P$ l'état stable et $$P=P \times M$$
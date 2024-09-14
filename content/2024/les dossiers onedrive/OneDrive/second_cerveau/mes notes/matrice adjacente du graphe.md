$$\text{ligne }i\begin{pmatrix} & a_{i,j} &  \\
 & \end{pmatrix}\text{colonne }j$$ où $a_{i,j}= \text{nombres d'arrêtes}$
## théorème
Soit $M$ la matrice d'adjacence d'un graphe $G$. Alors : $$M^{l}=\begin{pmatrix}m_{i,j}\end{pmatrix}$$ 
où $m_{i,j}=$ nombre de chaînes de longueur $l$ partant du sommet $i$ vers $j$.

### exemple 
![[un graphe orienté|300]]
$$M\begin{pmatrix}0 & 1 & 0 & 1 \\
0 & 0 & 1 & 0 \\
1 & 0 & 0 & 1 \\
0 & 1 & 0 & 0\end{pmatrix}$$
$$M \times M=M^{2}=\begin{pmatrix}0 & 1 & 1 & 0 \\
1 & 0 & 0 & 1\end{pmatrix}$$
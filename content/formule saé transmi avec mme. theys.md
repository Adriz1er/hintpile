# Étapes clés pour le codage RS :
- **Nombre total de symboles dans un bloc :** 
    N représente la taille totale du bloc de données, incluant les données utiles (K) et les données de redondance (N−K).
    
- **Données utiles (ou message) :** K
    K est le nombre de symboles utiles, c'est-à-dire les données brutes avant ajout des symboles de redondance.
    
- **Taux de code :**  
    Le taux de code (Rc) est calculé comme :
    $$Rc=\frac{K}{N}$$
## poiçonnage
1. Calcul des bits d'entree avant redondance

Le nombre de bits d'entrée avant redondance (Be) est calculé à
partir du nombre de symboles (N) et de la taille d'un octet (8
bits):

Be=N ×8

2. Calcul des bits apres redondance
Si une redondance de 100 % est appliquee (ce qui double les bits
d'entrée), les bits après redondance (Br) sont:

Br=Be×2

3. Poinçonnage
Si le poinçonnage conserve
restants (P) après poinçonnage sont:

P= 3/4 × Br

des bits après redondance, les bits
## fonctionnement additionneur modulo 2 à 3 entrées
Fonctionnement logique de l'additionneur complet

L'additionneur complet suit les règles de l'addition binaire :

Si= (ai XOR bi) XOR Ri-1

Ri = (ai AND bi) OR [(ai XOR bi) AND Ri-1]

## conversion octal en binaire
1. Prenez chaque chiffre octal séparément.
2. Convertissez chaque chiffre octal en son équivalent binaire de 3 bits.
3. Assemblez les groupes de 3 bits pour former le nombre binaire complet.

si le M=8 alors le premier bit va céder ça place au 9° ; à chaque saut d'horloge
# durée d'un bit 
-Modulation 64-QAM alors on a ln(64)/ln(2)=6 => donc on a 6 bits par symbole 

-6817 sous-porteuses utiles (Sur chaque porteuse est utilisée une modulation 16-QAM ou 64-QAM) donc on a 6 bits par porteuses le nombre de bits total => 6*6817=40902 bits sur 6817 sous-porteuses  

-Durée d’un symbole 896 micro S (alors 6 bits sur 896 microS)  

-Largeur d’un canal 8MHz
## formules 
Formules à utiliser :
1. Durée d'un bit (Tbit) :
La duree d'un bit peut etre obtenue par la formule :
![[Pasted image 20250120154557.png]]

2. Débit en bits par seconde (D) :

Le debit en bits par seconde est l'inverse de la duree d'un bit :

![[Pasted image 20250120154611.png]]

Application des formules :
1. Calcul de la durée d'un bit :

896×10-6 / 149.3x10-6 seconds

Donc, la durée d'un bit est 149.3 microsecondes (us).

2. Calcul du débit en bits par seconde :

1 / 149.3×10-6 = 6.7 x103bits/s= 6.7kbps

Donc, le débit en bits par seconde est 6.7 kbits/s.

# code de gray
- **Axe I en abscisse** : Utilise les **3 premiers bits** du symbole.
- **Axe Q en ordonné** : Utilise les **3 derniers bits** du symbole.
# symboles transmi à .. hz avec N=>1 symboles
![[Pasted image 20250120164957.png]]
![[Pasted image 20250120165037.png]]
![[Pasted image 20250120165102.png]]


([[formule saé transmi avec mme. theys]])
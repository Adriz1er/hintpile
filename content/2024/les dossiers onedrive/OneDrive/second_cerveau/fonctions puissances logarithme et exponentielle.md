---
aspiration:
  - mathématiques du signal
---
**1. Fonctions puissances**

**1.1 Définition (puissance rationnelle d’un nombre réel)**
Soit _a_ un réel non nul.

**-** _a_^0 = 1
**-** pour tout entier naturel _n_ non nul :
    _an_ = _a_ × _a_ ×....× _a_ = produit de _n_ facteurs égaux à _a_

```
a − n =^1
an
```
**-** Si _a_ > 0 : _a_

```
1
n est l’unique réel positif que tel que ( a
```
```
1
n ) n = a ,
```
Si _a_ < 0 : _a_

```
1
n n’existe que si n est impair,
```
c’est l’unique réel négatif tel que ( _a_

```
1
n ) n = a.
```
On note alors _a_

```
1
n =√ na , on l’appelle racine n ème de a.
```
**-** _a_

```
m
n =( am )
```
```
1
n (sous réserve d’existence)
```
Pour tout nombre rationnel _p_ non nul (ie _p_ ∈ Q*) : 0 _p_ = 0 ; 00 n’existe pas.

```
1.2 Propriétés
```
**Propriétés :** (^) _a_ et _b_ deux réels non nuls, _p_ et _q_ deux nombres rationnels non nuls, sous
réserve d’existence des expressions ci-dessous :
_apaq_ =
_ap
aq_
= ( _ap_ ) _q_ =( _aq_ ) _p_ =
_apbp_ =
_ap
bp_
=
**Remarque** : Attention avec les sommes et les différences...( _a_ + _b_ ) _n_ ≠ _an_ + _bn_.
**Définition :** On appelle **fonction puissance** toute fonction g s’écrivant _g_ ( _t_ )= _tp_ où _p_ ∈ Q*.
**Propriétés :** Les fonctions puissances sont dérivables sur leur ensemble de définition, sauf peut
être en 0 et ( _tp_ ) _'_ = _ptp_ −^1.
Plus généralement pour toute fonction _u_ dérivable convenablement choisie : ( _up_ ) _'_ = _pu'up_ −^1.


R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

**1.3 Cas particuliers**

_g_ ( _t_ )= _tp_

```
Fonction carré
( p = 2 )
```
```
Fonction racine carrée
( p =
1
2
```
```
)
```
```
Fonction inverse
( p =− 1 )
```
```
Expression g 1 ( t )= t^2 g 2 ( t )=√ t g 3 ( t )=
1
t
```
```
Ensemble de
définition R [0;+∞[ R*
```
```
Parité paire Pas de parité impaire
```
```
Dérivée
(expression
simplifiée)
```
_g_ 1 _'_ ( _t_ )=........._. g_ 2 _'_ ( _t_ )=..........._. g_ 3 _'_ ( _t_ )=........._._

```
Tableau de
variation avec
limites
```
t –∞ +∞

_t_^2

t^0 +∞

√ _t_

t –∞^0 +∞

```
1
t
```
```
Courbe et
asymptotes
```
**Dérivée de g ○ u**

_Rappels_ :

**-** g est **paire** si **Dg est centré en 0** (ie t ∈ Dg - ⇒t ∈ Dg) **et** que ∀ **t** ∈ **Dg g ( - t) = g (t)**

La courbe représentative de g est symétrique par rapport à l’axe des ordonnées.

**-** g est **impaire** si **Dg est centré en 0** (ie t ∈ Dg - ⇒t ∈ Dg) **et** que ∀ **t** ∈ **Dg g ( - t) = - g (t)**

La courbe représentative de g est symétrique par rapport à l’origine du repère.


R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

**2. Fonction exponentielle et logarithme népérien**

```
2 .1 La fonction exponentielle
```
**Définition** : La fonction **exponentielle** , notée **exp** , est la seule fonction dérivable définie sur R
**égale à sa dérivée** et telle que **exp(0)=**.

**Remarque** : les propriétés (admises) qui découlent de cette définition permettent de simplifier

l’écriture exp( _x_ ) en e _x_ où e est le nombre d’Euler, e = exp(1) ≈ 2,72 à 10 −^2 près.

**Propriétés** : Quels que soient les nombres réels _x_ et _y_ :

**-** e^0 = e^1 =
**-** e _x_ + _y_ = e− _y_ = e _x_ − _y_ =
**-** e _xy_ =
**- Signe :** e _x_ > 0
**-** (e _x_ ) _'_ = (e _u_ ( _x_ )) _'_ = _u'_ ( _x_ )e _u_ ( _x_ )

```
2. 2 La fonction logarithme népérien
```
**Définition** : La fonction **logarithme népérien** , notée ln, est la fonction réciproque de la fonction

##### exponentielle, elle est donc définie sur ] 0 ;+ ∞ [ : {

```
x ∈] 0 ;+ ∞ [
y =ln( x )
```
##### ⇔{

```
y ∈ℝ
x =e y
```
.

R ] 0 ;+ _∞_ [

**Propriétés** :

**-** ∀ _x_ ∈ R ln(e _x_ )= _x_ **•** ∀ _x_ ∈ ] 0 ;+ _∞_ [ e
    ln( _x_ )= _x_

Quels que soient les nombres réels _x_ et _y_ strictement positifs et le nombre rationnel _q_ :

**-** ln( 1 )= ln(e)=
**-** ln( _xy_ )= ln(
    1
       _y_

```
)= ln(
x
y
```
)=

**-** ln( _xq_ )= ln(√ _x_ )=
**- Signe** : Si 0 < _x_ < 1 ln( _x_ ) Si _x_ > 1 ln( _x_ )
**-** (ln( _x_ )) _'_ = (ln( _u_ ( _x_ ))) _'_ =

```
u' ( x )
u ( x )
```
**exp**

**ln**


R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

**2. 3 Face à face**

g(t) **Fonction exponentielle Fonction logarithme népérien**

**Expression** _g_ 1 ( _t_ )=e _t g_ 2 ( _t_ )=ln( _t_ )

```
Ensemble de
définition R ]0;+∞[
```
```
Parité Pas de parité Pas de parité
```
**Dérivée** _g_ 1 _'_ ( _t_ )=........._. g_ 2 _'_ ( _t_ )=..........._._

```
Tableau de
variation avec
limites et
valeurs
particulières
```
t –∞ +∞

e _t_

t^0 +∞

ln( _t_ )

```
Courbe et
asymptotes
```
**Dérivée de g ○ u**

```
Propriétés
```
```
Transforme :
```
**-** les sommes en produits
**-** les différences en quotients
**-** les multiplications en puissances

```
Transforme :
```
**-** les produits en sommes
**-** les quotients en différences
**-** les puissances en multiplications

**Remarque :** les courbes des deux fonctions sont symétriques par
rapport à la droite d’équation y = t
(propriétés de deux fonctions réciproques).


R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

**3. Fonctions logarithmes et exponentielles de base** **_a_**

**3 .1 Le logarithme de base** **_a_** **(** **_a_** **>0,** **_a ≠_** **1)**

**Définition :** Le **logarithme de base** **_a_** est noté log _a_ ,

il est défini sur ] 0 ;+ _∞_ [ par log _a_ ( _x_ )=

```
ln( x )
ln( a )
```
```
.
```
**Propriétés** : **Analogues à celles de ln sur les produits, quotients, puissances**
Quels que soient les nombres réels _x_ et _y_ strictement positifs et le nombre rationnel _q_ : :

**-** log _a_ ( 1 )= log _a_ ( _a_ )=
**-** log _a_ ( _xy_ )= log _a_ (
    1
       _y_

```
)= log a ( x
y
```
)=

**-** log _a_ ( _xq_ )=
**- Signe** : Si 0 < _x_ < 1 log _a_ ( _x_ ) Si _x_ > 1 log _a_ ( _x_ )
**-** (log _a_ ) _'_ ( _x_ )= (log _a_ ( _u_ ( _x_ ))) _'_ =

```
u' ( x )
u ( x )ln( a )
```
**Tableau de variation complété :**

**0 <** **_a_** **< 1** **_a_** **> 1**

t^0 +∞

log _a_ ( _t_ )

t^0 +∞

log _a_ ( _t_ )

**3. 2 Fonction exponentielle de base** **_a_** **(** **_a_** **>0)**

**Définition** : La fonction **exponentielle de base** **_a_** ( **_a_** **>0** donné) , est la fonction définie sur R par

_g_ ( _x_ )= _ax_ =e _x_ ln( _a_ ).

**Propriétés** : Les fonctions logarithme de base _a_ et exponentielle de base _a_ sont des fonctions
réciproques.

R ] 0 ;+ _∞_ [

Ainsi : _y_ = _ax_ ⇔ _x_ =log _a_ ( _y_ ) ∀ _x_ ∈ R et ∀ _y_ ∈ (^) ] 0 ;+ _∞_ [
∀ _x_ ∈ R log _a_ (a _x_ )= _x_ **•** ∀ _x_ ∈ (^) ] 0 ;+ _∞_ [ (^) _a_ log _a_ ( _x_ )= _x_
**loga**
**_a□_**


R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

Quels que soient les nombres réels _x_ et _y_ : **propriétés analogues à celles de l’exponentielle**

**-** _a_^0 = _a_^1 =
**-** _ax_ + _y_ = _a_ − _y_ = _ax_ − _y_ =
**-** _axy_ =
**- Signe :** _ax_ > 0
**-** ( _ax_ ) _'_ = ( _au_ ( _x_ )) _'_ = _u'_ ( _x_ )ln( _a_ ) _au_ ( _x_ )

**Tableau de variation complété :**

**0 <** **_a_** **< 1** **_a_** **>**

t - ∞ +∞

_at_

t - ∞ +∞

_at_

**Exemples de courbes :**

**Remarque :** les courbes des fonctions _x_  _ax_ et _x_  (^) log _a_ ( _x_ ) sont symétriques par
rapport à la droite d’équation _y_ = _x_.


R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

**4. Utilisation du logarithme décimal**

```
4 .1 Définition
```
**Définition :** Le **logarithme décimal est le logarithme en base 10** , il est noté log 10 (parfois

seulement log). Il est défini sur ] 0 ;+ _∞_ [ par log 10 ( _t_ )=

```
ln( t )
ln( 10 )
```
. (ln(10) ≈ 2,3)

**Propriétés** : Le logarithme décimal et la fonction exponentielle de base 10 sont des fonctions
réciproques.

Ainsi ∀ _t_ ∈ R et ∀ _y_ ∈ ] 0 ;+ _∞_ [ _y_ = 10 _t_ ⇔ _t_ =log 10 ( _y_ )

**-** ∀ _t_ ∈ R log 10 ( 10 _t_ )= _t_ **•** ∀ _t_ ∈ ] 0 ;+ _∞_ [ 10 log^10 ( _t_ )= _t_

**Cas particuliers** : Pour tout réel _k_ strictement positif et tout entier relatif _n_ :

**-** log 10 ( 1 ) = **•** log 10 ( 10 ) =
**-** log 10 ( 10 _n_ ) = **•** log 10 ( _k_ × 10 _n_ ) =

**4. 2 Echelle logarithmique
Définitions :**

**-** Une échelle **linéaire** est construite de telle façon que l’ **écart** entre deux unités successives est
toujours représenté par la même distance, la distance entre _a_ et _b_ ( _a_ < _b_ ) est proportionnelle à

_b_ − _a_.

**-** Une échelle **logarithmique** est construite de telle façon que le **rapport** entre deux puissances
de 10 successives est toujours représenté par la même distance, la distance entre _a_ et _b_

( _a_ < _b_ ) est proportionnelle à log (^10) (
_b
a_ )
=log 10 ( _b_ )−log 10 ( _a_ ).
L’échelle logarithmique amplifie les variations proches de 0 et atténue les grandes variations.
On peut aussi noter seulement les décades en abscisse :
0 1 10 20 30

- ∞

```
0,1 1 10 100
```
```
0
0,
```
```
t
```
```
log 10 (t)
-2 -1 0 1 2
```
```
1 décade
```

R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

**Exemple** : Diagramme de Bode (électronique) : réalisé en repère semi-logarithmique (axe des
abscisses en échelle logarithmique, axe des ordonnées en échelle linéaire)

On considère un gain donné par G _dB_ = 20 log (^10) (

## √

```
1 +(
f
100 )
```
```
2
```
### )

(associé à la fonction transfert H( _f_ )= 1 +j _f_
100

).

**On cherche d’abord les courbes asymptotes :**

**-** Si _f_ tend vers 0 alors GdB tend vers 20 log 10 ( 1 )= 0
**-** Si _f_ tend vers +∞ alors GdB se comporte comme

20 log (^10) (

## √(

```
f
100 )
```
```
2
```
### )=^20 log^10 (

```
f
100
```
)= 20 log 10 ( _f_ )− 20 log 10 ( 100 )= 20 log 10 ( _f_ )− 40

En repère semi-logarithmique, il s’agit de l’équation d’une droite de coefficient directeur 20 ( G
diminue de 20 dB par décade) et d’ordonnée à l’origine -40.

**On relève des valeurs particulières puis on réalise la courbe** :


R114 : Mathématiques des transmissions Chap 1 : Fonctions puissances, logarithmes et exponentielles

```
4.2 les décibels
```
**Définitions :** Le **décibel** (noté dB) est une unité définie comme 10 fois le logarithme décimal du
rapport entre deux puissances :

Gain en décibels : G[ _dB_ ]= 10 log (^10) (
Psortie

#### Pentrée)

**Propriétés :**

**-** Lorsque la puissance de sortie **double** :

10 log (^10) (
2 Psortie

#### Pentrée )

= 10 log 10 ( 2 )+ 10 log (^10) (
Psortie

#### Pentrée)

_≈_ 3 +G[ _dB_ ] : le gain **augmente de 3 dB**

**-** Lorsque la puissance de sortie **triple** :

10 log (^10) (
3 Psortie

#### Pentrée )

= 10 log 10 ( 3 )+ 10 log (^10) (
Psortie

#### Pentrée)

_≈_ 4,77+G[ _dB_ ] : le gain **augmente de 4,77 dB**

**-** Lorsque la puissance de sortie **est multipliée par 10** :

10 log (^10) (
10 Psortie

#### Pentrée )

= 10 log 10 ( 10 )+ 10 log (^10) (
Psortie

#### Pentrée)

_≈_ 10 +G[ _dB_ ]^ : le gain **augmente de 10 dB**

**-** On parle d’ **amplification** si

```
Psortie
Pentrée
```
> 1 , cela signifie que G[ _dB_ ]> 0 car la fonction log 10 est

croissante sur ] 0 ;+ _∞_ [.

**-** On parle d’ **atténuation** si

```
Psortie
Pentrée
```
< 1 , cela signifie que G[ _dB_ ]< 0 car la fonction log 10 est

croissante sur ] 0 ;+ _∞_ [.


R114 : Mathématiques des transmissions TD1: Fonctions puissances, logarithmes et exponentielles

```
TD1 : FONCTIONS PUISSANCES, LOGARITHME ET EXPONENTIELLE
```
**Exercice 1** Calculs et exposants

Effectuer les calculs à la main, donner le résultat en valeur exacte réduite.

```
A= 52 – ( 5 − 3 )^2 B= 2 ( 3 +√ 3 )^2 − 2 C=(^2
3 )
```
```
11
×(^3
5 )
```
```
12
×(^5
2 )
```
```
10
```
```
D=
− 23 ×(− 3 )^2 × 10 −^2
22 ×( 32 )^3 × 102
```
```
E=
e^3 x +^1 ×(e^2 x )^3
√e×e^5 x
```
```
F=(e^3 x − 1 )^2 + 2 e^3 x − 1
```
**Exercice 2** Fonctions puissances et exponentielle

Déterminer les fonctions puissances

(du type t  (^) _tp_ ) ou exponentielles
(du type t  _at_ ) représentées,
grâce aux informations graphiques.
(Proposer des éléments de
justification.)
**Exercice 3** logarithmes et exponentielle (Justifier les réponses)

**1.** À quoi est égal log 10 (205)?

 205 ln _⁡_^10  ln(205)ln(10) 

```
ln ⁡ ( 10 )
ln ⁡ ( 205 )

```
```
ln ⁡ ( 205 )
ln ⁡ ( 10 )

ln ⁡ ( 205 )
10
 10 ln ⁡ (^205 )
```
**2.** À quoi est égal log 2 (16)?



```
ln ⁡ ( 2 )
ln ⁡ ( 16 )

```
```
ln ⁡ ( 16 )
ln ⁡ ( 2 )

ln ⁡ ( 16 )
2
 2 ln ⁡ (^16 )  16 ln ⁡ (^2 )  4 
1
4
```
**3.** Simplifier le plus possible l’écriture des nombres suivants :

N 1 = ln(12) – ln(36) N 2 = 4 ln(3) + 3 ln(12) – 2 ln(
8
3 ) N^3 =

```
2 e^4 e −^6 e^8 − (e^2 )^4
8 e^7
```
**4.** Donner l’ensemble de définition des fonctions suivantes **puis** simplifier le plus possible leur
    expression, enfin déterminer la fonction dérivée.
       g 1 (t) = t

(^8) _−_ 5 t 3
_t_^2
g 2 (x) = e2 ln(x) – 4 ln(ex) g 3 (x) = ln(3 e2x)


R114 : Mathématiques des transmissions TD1: Fonctions puissances, logarithmes et exponentielles

**Exercice 4** Logarithme décimal et logarithme de base 2

Simplifier le plus possible l’écriture des nombres suivants :

N 1 = log (^10) (
36
5 ) – log^10 (12)
N 2 = log 10 (50 - (^) √ 100 ) + log 10 (50 + √ 100 )
N 3 = log 2 (5^4 ) – log 2 (1000)
Calculer ces nombres à 10-3 près.
**Exercice 5** Fonctions usuelles et quelques points clés de leur étude

**1.** Associer à chaque fonction sa courbe.
**2.** Déterminer l’ensemble de définition, la dérivée, et les limites aux bornes de l’ensemble de
    définition pour chacune des fonctions.

```
Fonction courbeSa
```
```
Son
ensemble de
définition D
```
```
Sa dérivée
```
g 1 (t) = √ 3 _t_ + 10

```
g 2 (t) = ( 3 t + 10 )^2
```
```
g 3 ( x )=ln( 3 x + 10 )
```
```
g 4 ( f )= – 2 ln( 3 f + 10 )
```
```
g 5 (x) = e^3 x +^10
```
```
g 6 ( f )=−^1
3
```
```
e
```
```
3 f + 10
```

R114 : Mathématiques des transmissions TD1: Fonctions puissances, logarithmes et exponentielles

```
Courbe A Courbe B Courbe C
```
```
Courbe D Courbe E Courbe F
```
**Exercice 6** Résolutions d’équations
Résoudre les équations :

(E1) log (^2) (
2 _p_ + 1
_p−_ 1 ) = – 3 (E^2 ) log^10 (P + 2) + log^10 (2P - 4) = log^10 (120) – log^10 (5)
(E 3 ) 10 _x−_^3 = 107 _−x_
**Exercice complémentaire**

**1.** Simplifier le plus possible l’écriture des nombres suivants :

M 1 = (e^6 )^2 + e^3 – 2e^15 e-^6 M 2 = log (^2) (
1
28 ) – log^2 (4)
M 3 = 4 log 10 (8) - 3 log 10 (12) – log (^10) (
8
3 )

**2.** Donner l’ensemble de définition des fonctions suivantes **puis** simplifier le plus possible leur
    expression.
       h 1 (f) = 3 ln( _f_^2 ) – 8 ln(√ _f_ ) + 2 ln(f^ -^3 ) + 5 ln(

```
2
f^4 )
h 2 (t) = e^4 ln( t ) −^3
```
**3.** Résoudre les équations (E 1 ) log 10 (4 - x) = log 10 (5x²) et (E 2 ) log (^10) (
2 _x_ + 1
_x−_ 1 ) = - 3.

**4.** Résoudre l’inéquation 5 ×0,3 _x_ > 2.
**5.** Soit _g_ ( _x_ )=5.^10 −^6 ×^10

```
x
```
(^20)**.**
a) Déterminer son ensemble de définition.
b) Déterminer sa dérivée.


```
Magnitude
```
```
Énergie
libérée
```
R114 : Mathématiques des transmissions TD2: Utilisations du logarithme

```
TD2 : UTILISATIONS DU LOGARITHME
```
**Exercice 1** Puissances W, V ou dBm

**Soit P[dBm] = 10 log** (^10) (
_P_ [ _W_ ]
0,001)

**1.** Calculer P[dBm] pour P[W] = 0,3.
**2.** Calculer P[W] pour P[dBm] = - 80 puis pour P[dBm] = 110.

**3.** Dans la formule : _Psignal_ [ _dB_ / _Préf_ ] = 10 log (^10) (
_Psignal_ [ _W_ ]
_Préf_ [ _W_ ] )
, exprimer Psignal[W] en fonction des autres
grandeurs, puis Préf[W].
**Exercice 2** Échelle de Richter
Instaurée en 1935, l’échelle de Richter indique la magnitude d’un séïsme en fonctlion de l’énergie
(en Joules) qu’il libère à l’épicentre. Magnitude = _a_ log 10 (Énergie) + _b_
La représentation de cette magnitude en fonction de l’énergie libérée à l’épicentre nécessite
l’emploi de papier semi-logarithmique car les valeurs d’énergie enregistrées sont très étendues
(entre 107 et 108 ). La représentation est faite sur papier semi-logarithmique horizontal.

**1.** Le point J correspond à une énergie de 2. 107 Joules.
Déterminer l’énergie en joules correspondant aux points
    A : B : C : D :
**2.** Déterminer graphiquement l’énergie libérée par le séisme de magnitude 7 survenu en Haïti en
2010.
**3.** Déterminer graphiquement l’énergie libérée par le séisme de magnitude 9 survenu au Japon le
11 mars 2011.
**4.** Déterminer graphiquement la magnitude d’un séisme ayant libéré une énergie de 7. 109 Joules.

```
0,
```

R114 : Mathématiques des transmissions TD2: Utilisations du logarithme

**5.** Si l’énergie libérée par un 2e séisme est dix fois plus grande que celle du 1er séisme, quelle est
la différence de magnitude entre ces deux séismes?
En déduire la pente par décade de cette courbe.
**6.** À partir du résultat précédent, calculer l’augmentation de magnitude pour un 3e séisme dont
l’énergie libérée est deux fois plus grande que celle du 1er séisme.
En déduire la pente par octave de cette courbe, vérifier le résultat par lecture graphique.
(1 octave sépare deux grandeurs doubles)

Source : [http://www.physiquemaths.fr/documents/mathsterminalebac/2.4%20Exercices%20Papier%20semi-log.pdf](http://www.physiquemaths.fr/documents/mathsterminalebac/2.4%20Exercices%20Papier%20semi-log.pdf)

**Exercice 3** Travail sur une échelle semi logarithmique

Le niveau d’intensité sonore est donné par la formule : L= 10 log (^10) (I
I 0 )
,
avec L exprimée en dB, I l’intensité sonore exprimée en W/m²
et I 0 l’intensité du seuil d’audibilité pour l’oreille humaine.

**1.** Tracer la courbe représentant la fonction L = g ( _I_
    _I_ 0 )
       après avoir complété le tableau de valeurs:

(

```
I
I 0 )^1251020501005001000
L
```
**2.** Pour quelle valeur de (
    _I
I_ 0 ), L est-elle égale à 26^? **3.**^ Si on rajoute à une enceinte délivrant un

son dont le niveau acoustique est de 26 dB, une deuxième enceinte délivrant une même intensité

acoustique, quelle sera la valeur L produite par les deux enceintes?


R114 : Mathématiques des transmissions TD2: Utilisations du logarithme

**Exercice complémentaire 1** Magnitude d’un astre

La magnitude apparente d’un astre d’éclat E est définie à partir d’un éclat de référence E 0 (éclat de

l’étoile de Véga) par M=log _a_ (E
E 0 )

```
avec la convention : la magnitude augmente de 5 lorsque l’éclat
```
est divisé par 100.

**1.** Calculer ln(a).
**2.** Justifier mathématiquement que la magnitude diminue lorsque l’éclat augmente.
**3.** Déterminer la magnitude apparente du Soleil (E=4,786.10^10 E 0 ) et de la Lune (E=1,2.10^5 E 0 ).

**4.** On admet que le seuil de visibilité d’une étoile correspond à une magnitude égale à 6. Une étoile
ayant une magnitude égale à 6 est à peine visible, tandis qu’une étoile ayant une magnitude égale à
1 se situe parmi les étoiles les plus visibles.
Le télescope Hubble est capable de trouver des étoiles de magnitude 30. Exprimer l’éclat de cette
étoile en fonction de E 0.

**5.** Sirius est une des étoiles les plus visibles, sa magnitude approche celle d’une planète, elle vaut
environ -1,47. Déterminer l’éclat E de cette étoile par rapport à celui de Véga.

**Exercice complémentaire 2** Gain en décibels

**Soit G[dB] = 10 log** (^10) (
_Ps_ [ _W_ ]
_Pe_ [ _W_ ])**.**

**1.** Calculer G **[dB]** pour Ps **[W]** = 72 et Pe **[W]** = 60.
**2.** Calculer Ps **[W]** pour Pe **[W]** = 50 et G **[dB]** = - 2,5.
**3.** Calculer Pe **[W]** pour Ps **[W]** = 32 et G **[dB]** = 20.

**Exercice complémentaire 3**

L’échelle de Beaufort, qui mesure la force du vent, comporte 13 degrés (de 0 à 12). Le degré

Beaufort B est lié à la vitesse moyenne du vent v (en km.h-1) par B^3 = _v_

```
2
9
```
```
.
```
**1. a.** Calculer le degré Beaufort, arrondi à l’unité, pour une vitesse v = 90 km.h-1.

```
b. Calculer la vitesse du vent v (en km.h-1) correspondant à un vent de force 10 Beaufort.
```
**2.** Démontrer que la relation entre B et v peut s’écrire log 10 ( _v_ )=^3
    2
       ×log 10 (B)+log 10 ( 3 )
**3.** Si on représente, dans un repère logarithmique, v en fonction de B, quelle est l’allure de la

représentation graphique?


R114 : Mathématiques des transmissions **Compte-rendu du TP n°**

**Exercice 1 : Courbes représentatives de fonctions usuelles**

```
Tracer à main levée une courbe représentative des fonctions. Tracer en rouge les points remarquables.
y = ln(t) y = e t y = √
```
```
y = t² y =  y = | t |
```
Quelles sont les courbes qui ont un lien entre elles? Préciser le lien.

**Exercice 2 : Fonction logarithme décimal** Soit la fonction h(a) = 10 log 10 ,

```
1) son tableau de variation
```
```
2) Sachant que P [dBm] = 10 log 10 
```
(^) []
,^ , calculer avec Maple
P[dBm] =
P[W] = 0,
P[W] = 6.10 - 4
P[W] = 40
a^
h’(a) =^
h(a)
P[W] =
P[dBm] = − 60
P[dBm] = 120
P[dBm] = 25
L’énoncé complet du TP se trouve sur
Moodle : https://lms.univ-cotedazur.fr/


```
R114 : Mathématiques des transmissions Compte-rendu du TP n°
Exercice 3 : Équations avec log 10
```
équations équivalentes
sans log 10

```
forme de l’ensemble
des solutions
```
```
Vérification avec Maple :
ensemble des solutions
```
log 10 (x + 3) + log 10 (x + 2) = log 10 (x + 11)

log 10 (1 − x) – log 10 (x + 1) = – 2

(log 10 (x))² – 3log 10 (x) – 4 = 0

**Exercice 4 : Conjugué d’un nombre complexe**

```
Écrire la forme algébrique des conjugués des nombres suivants.
```
```
W 1 = 4j – 2(4 – 5j) W  =
```
```
W 2 = (4 – 2j)( – 4 + 5j) W  =
```
```
W 3 = –  W  =
```
```
Exercice 5 : Nombres complexes sous forme algébrique
Écrire les nombres complexes suivants sous forme algébrique.
```
```
Z 1 = – 2j – (20 + 3 j) + 2(8 – 5j) =
```
```
Z 2 = (4 – 2j)(7 + 3j) – (2j – 3)(3 + 2j) =
```
```
Z 3 = (3 + j√ 5 )(3 – j√ 5 ) =
```

R114 : Mathématiques des transmissions **Compte-rendu du TP n°1**

Y 1 =  –  =^

Y 2 =  –  =^

Y 3 = (3 – 4j)^2 – 5  +  =^

**Exercice 6 : Réel et imaginaire**

1. Déterminer la ou les valeurs du réel x telle(s) que le nombre A = (4 x + 5j) + (3jx – 9) soit un nombre réel.
2. Déterminer la ou les valeurs du réel x telle(s) que le nombre B = (4 x + 5j)(3jx – 9) soit un nombre imaginaire pur.

**Exercice 7 : Résolution d’équations**

Résoudre dans ℂ les équations suivantes. Donner la solution sous forme algébrique.

(E1) 4jz + 2 = 3z

(E2) ( 2 + 3j)z – 1 – 4j = (− 4 + j)z

(E3)  = 4j


R114 : Mathématiques des transmissions Chap 2 : Nombres complexes et forme algébrique

**Chapitre 2**

**NOMBRES COMPLEXES ET FORME ALGÉBRIQUE**

**1. Forme algébrique
2. Opérations
3. Plan complexe**

**4. Racines d’un polynôme de degré 2 à coefficients réels**


R114 : Mathématiques des transmissions Chap 2 : Nombres complexes et forme algébrique

**1. Forme algébrique**

**Définition :** Un **nombre complexe** _z_ est un nombre s’écrivant sous la forme dite « **algébrique** »

_z_ = _a_ + _b_ j où ( _a_ ; _b_ )∈ R^2 et j^2 =− 1 (noté j pour ne pas le confondre avec l’intensité i)
On note C l’ensemble des nombres complexes.

**_Vocabulaire_** _: a_ est la **partie réelle** de _z_ , on note _a_ =Re( _z_ ),

_b_ est la **partie imaginaire** de _z_ , on note _b_ =Im( _z_ )
Les nombres complexes dont la partie réelle est nulle sont appelés **imaginaires purs**.
L’ensemble des imaginaires purs est noté j R.

**Remarque** : la forme algébrique d’un nombre complexe est **unique** : deux nombres sont égaux si
et seulement si ils ont même partie réelle et même partie imaginaire.

**Exemples** : • 1- j est le nombre complexe de partie réelle égale à 1 et de partie imaginaire -1.

- 3j – 2 est le nombre complexe de partie réelle égale à -2 et de partie imaginaire égale à 3.
- j est le nombre complexe de partie réelle nulle et de partie imaginaire égale à 1.
- 0 est le nombre complexe de partie réelle nulle et de partie imaginaire nulle.

**Propriété** : _z_ ∈ R Im(z)=0⇔

**Conséquence** : R ⊂ C

**2. Opérations**

**2.1 Addition et multiplication
Propriétés :** L' **addition** et la **multiplication** des nombres réels se prolongent aux nombres

complexes et les règles de calcul restent les mêmes, avec la règle supplémentaire j^2 =− 1.

**Exemples** : • (^) ( 1 − 2 _j_ ) _–_ ( 3 + _j_ ) =
• (^) ( 1 − 2 _j_ )( 3 + _j_ ) =
• (^) ( 3 + _j_ )^2 =

- Résoudre dans C l'équation 3 _z_ − 2 _j_ = 1 + _j_ , préciser les parties réelle et imaginaire des solutions
éventuelles.


R114 : Mathématiques des transmissions Chap 2 : Nombres complexes et forme algébrique

**2.2 Conjugué**

**Définition** : Soit z un nombre complexe de forme algébrique _z_ = _a_ + _b_ j (donc avec ( _a_ ; _b_ )∈ R^2 ).

Le **conjugué** de z est le nombre complexe s'écrivant sous forme algébrique **_a_** **–** **_b_** **j** , noté ̄ _z_.

Ainsi z et ̄ _z_ ont la même partie réelle et des parties imaginaires opposées.

**Exemples** : 2 + _j_ = ; − 1 − 3 _j_ = ; 4 = ; _j_ =

**Propriétés :** Soit z ∈C, z’ ∈C, k ∈R, _n_ ∈ N

- _z_ =
- _z_ + _z'_ = • _kz =_
- _zz' =_ • _zn =_

• _z_ ∈R ⇔ (^) ̄ _z_ = ....... • z ∈ j R ⇔ (^) ̄ _z_ = .......
• (^) _z_ + ̄ _z_ = • _z_ − ̄ _z_ =
**Exemples :** • ( 3 − _j_ )^2 =
• (^) _z_ = _j_ + 2 .....⇔

- _z_ ̄ _z_ = ( _a_ + _b_ j)(................) =

**Conséquence importante** : le nombre _z_ ̄ _z_ est un nombre ...........

**Exemple** : (1+2 j)(1-2j)=

**2.3 Division
Propriété** : Pour déterminer la forme algébrique d’un quotient, on peut multiplier le numérateur et le

dénominateur par le conjugué du dénominateur: _z
z'_
=........................ (où z ∈C et z' ∈C*)

**Exemples :** • Déterminer la forme algébrique des nombres complexes suivants :
1
2 + _j_

```
=
```
```
1 + j
1 − 3 j
```
```
=
```
```
1 + j
2 j
```
```
=
```
- Résoudre dans C l'équation : ( _j_ − 3 ) _z_ = 2 _j_


R114 : Mathématiques des transmissions Chap 2 : Nombres complexes et forme algébrique

**Propriété :** Soit z ∈C, z’ ∈C*, (^) (
_z
z'_ )
= ̄
_z
z'_
.
**Exemple :** Ecrire sous forme algébrique : _Z_ =(
1 − _j_
2 + 2 _j_ )
.

**3. Plan complexe**

Le plan est muni d'un repère (O ; ⃗ _u_ , ⃗ _v_ ) orthonormé direct (( ^⃗ _u;_ ⃗ _v_ )= π
2
).
**3.1 Affixe d'un point ou d’un vecteur
Définitions** :
A tout nombre complexe _z = a + b j_ (où _a_ et _b_ sont deux nombres
réels), on associe le point M de coordonnées ( _a_ ; _b_ ) dans le repère
(O ; ⃗ _u_ , ⃗ _v_ ).
On dit que le point M est le **point image** de _z_ et que ⃗OM est le
vecteur image de _z_.
Réciproquement tout point M( _a_ ; _b_ ) est le point image d'un seul
nombre complexe _z = a + b j_.
On dit que _z_ est l' **affixe** du point M, ainsi que du vecteur ⃗OM. On
note alors M( _z_ ) (qui se lit « M d'affixe _z_ ») et ⃗OM(z).

**Remarques :**

- Les **nombres réels** sont les affixes des points situés sur ................................................, pour
cette raison on appelle aussi celui-ci ..............................................
- Les nombres **imaginaires purs** sont les affixes des points situés sur ..........................................,
pour cette raison on appelle aussi celui-ci .................................................

**Exemples** :
Placer dans le plan complexe ci-contre les points A(-2 j), B(4 - j),
C(4 j - 1) et D(4 + j).
Construire un représentant de ⃗ _w_ (− 2 − 3 j).

```
3.2 Propriétés (z et z’ sont des nombres complexes)
```
- M( _z_ ) et _M'_ ( _z_ ) sont ..........................................................
- Deux vecteurs sont égaux leurs affixes sont égales.⇔
- Soient ⃗ _s_ ( _z_ ) et ⃗ _t_ ( _z_ ') alors ⃗ _s_ +⃗ _t_ ( _z_ + _z'_ ) et _k_ ⃗ _s_ ( _kz_ ) où _k_ ∈ R.
- Si A( _z_ A) et B( _z_ B) alors ⃗AB( _z_ B− _z_ A) et I le milieu de [AB] a pour affixe

```
z A+ z B
2
```
```
.
```

R114 : Mathématiques des transmissions Chap 2 : Nombres complexes et forme algébrique

**Exemple :** Dans le plan complexe on considère les points A(2+ j), B(1 – 2 j), C(– 1+2 j) et D(5 j).
Démontrer de deux façons différentes (utilisant les complexes) que ABCD est un
parallélogramme.

**4. Racines d’un polynôme de degré 2 à coefficients réels**

On souhaite déterminer les racines complexes du polynôme P( _z_ )= _az_^2 + _bz_ + _c_ où _a_ , _b_ , _c_ sont

trois nombres réels, _a_ ≠ 0 (i.e. les antécédents de 0 par P).
On calcule
Δ= _b_^2 _–_ 4 _ac_

(^) Δ> 0 (^) Δ= 0 Δ< 0 et Δ=(jδ)^2
P admet **deux racines réelles
distinctes** :
_x_ 1 = .........
et
_x_ 2 = .........
P admet une **unique racine
réelle** :
_x_ 0 = .........
( _x_ 0 est dite « **racine double** »
du polynôme P **)**
P admet **deux racines
complexes conjuguées** :
_z_ 1 = .........
et
_z_ 2 = .........
**Forme factorisée de P**
P( _z_ )= _a_ ( _z–x_ 1 )( _z_ − _x_ 2 ) P( _z_ )= _a_ ( _z–x_ 0 )^2 P( _z_ )= _a_ ( _z–z_ 1 )( _z_ − _z_ 2 )
**Exemple :** Déterminer les racines complexes de P 1 défini par P 1 ( _z_ )= _z_^2 + _z_ +^1.
**Cas particuliers** : Si _b_ = 0 ou _c_ = 0 on trouve les racines de P en résolvant l’équation P(z)=0 (en
isolant l’inconnue z ou en factorisant).
**Exemples :** Déterminer les racines complexes de P 2 et P 3.
P 2 ( _z_ )= 3 _z_^2 + 4 P 3 ( _z_ )= 3 _z_^2 + 5 _z_


R114 : Mathématiques des transmissions TD3 : Nombres complexes : calculs avec la fome algébrique

**TD 3 : Nombres complexes : calculs avec la forme algébrique**

**Exercice 1**
Ecrire sous forme algébrique les nombres complexes suivants :
a.( 4 +j)−( 3 − 2 j) b. ( 4 +j)(− 5 + 3 j) c. ( 2 −j)^2 d. j^3

e. (^) j^4 f. ( 2 − 3 j)( 2 + 3 j) g.^1
2 + 3 j
h. 3 +j
2 −j
**Exercice 2**
On considère les nombres complexes : _z_ 1 =√ 3 −j et _z_ 2 =− 1 −j.
Déterminer la forme algébrique de chacun des nombres :
_z_ 2 _z_ 1 × _z_ 2
_z_ 1
_z_ 2
( _z_ 1 )^2 j _z_ 1
**Exercice 3**

**1.** Déterminer l’ensemble des nombres complexes z tels que A= _z_ − _z_^3 soit réel.
**2.** Déterminer le nombre complexe _z_ 2 tel que _z_ 22 = 8 _–_ 6 j.

**Exercice 4**
En utilisant le graphique ci-contre, donner les affixes
des points A et B, puis des vecteurs ⃗ _w_ 1 et ⃗ _w_ 2.

**Exercice 5**
Dans le plan complexe on considère les points A, B et C d’affixes respectives

```
−^1
2
```
```
+ 3 j ; −^1
4
```
+ 2 j ; 3 j_._

Déterminer les affixes des points D, E, F, G et H définis par :

**1.** ⃗BD=
    2
    3

⃗CA

**2.** ⃗AE= 5 ⃗AB _–_ ⃗BC
**3.** F est le milieu du segment [AC]
**4.** G est le symétrique de B par rapport à l’axe des imaginaires purs.
**5.** H est le point d’intersection de la droite parallèle à (AB) passant par C et de l’axe des réels.
**6.** Construire une figure pour vérifier les résultats obtenus.


R114 : Mathématiques des transmissions TD4 : Racines d’un polynôme de degré 2

**TD 4  : Racines d’un  polynôme de  degré  2**

**Exercice  1**
Pour chacune des équations suivantes indiquer le nombre et la nature des solutions :

**a.** _z_^2 + 3 = 4 _z_ − 1 **b.**
1
3

```
z^2 −^1
3
```
```
z +^1
4
```
= (^0) **c.** − _z_^2 −^1
2
_z_ = 0
**d.**^1
2
_z_^2 + 3 _z_ − 4 = 0 **e.** 2 _z_^2 + (^5) √ 2 _z_ +^25
2
= 0
**Exercice  2**

**1.** Déterminer les racines complexes des polynômes suivants :

**a.** _P_ 1 ( _z_ )= _z_^2 + _z_ − 6 **b.** _P_ 2 ( _z_ )= 3 _z_^2 − 5 _z_ + 3 **c.** _P_ 3 ( _z_ )=( _z_^2 + 1 )( 2 _z_^2 + 4 _z_ + 3 )

**2.** En utilisant l’un des résultats précédents, résoudre dans C l’équation _z_^4 + _z_^2 − 6 = 0.

**Exercice complémentaire**

**Exercice  3**

Soit _f_ la fonction de variable complexe z, définie pour z ≠ 1 par _f_ ( _z_ )=^2 _z_ +^1
_z_ − 1
.

**1.** Soit A le point d’affixe _z_ A= _f_ (^1
    4
       _-_^3
          4
             j). Montrer que A est sur l’axe des imaginaires purs.
**2.** On dit qu’un point M(z) est invariant par _f_ lorsque _f_ ( _z_ )= _z_.

Déterminer l’ensemble des points invariants par _f_.


R114 : Mathématiques des transmissions TD6 : Produit scalaire

**TD5 : Produit scalaire**

Le plan étant muni d’une distance, le produit salaire de deux vecteurs ⃗ _u_ et ⃗ _v_ peut être défini de
façon équivalente par l’une des formules ci-dessous :

- **Avec normes et angles** :
Si ⃗ _u_ = ⃗ 0 ou ⃗ _v_ = ⃗ 0 : ⃗ _u_ ⋅⃗ _v_ = 0
Si ⃗ _u_ ≠ ⃗ 0 et ⃗ _v_ ≠ ⃗ 0 : ⃗ _u_ ⋅⃗ _v_ =‖⃗ _u_ ‖×‖⃗ _v_ ‖×cos(α),

soit ⃗ _AB_ ⋅⃗ _AC_ = _AB_ × _AC_ ×cos(^ _BAC_ )

- **Avec projeté orthogonal** : ⃗ _AB_ ⋅⃗ _AC_ =⃗ _AB_ ⋅⃗ _AH_ où H est le projeté
orthogonal de C sur (AB),
soit ⃗ _AB_ ⋅⃗ _AC_ = _AB_ × _AH_ si ⃗AB et ⃗AH ont même sens, ⃗ _AB_ ⋅⃗ _AC_ =− _AB_ × _AH_ sinon
- **Avec les coordonnées** (repère orthonormé obligatoire) :

⃗ _u_ ⋅⃗ _v_ = _xx'_ + _yy'_ où ⃗ _u_ ( _x
y_ )

```
et ⃗ v ( x'
y' )
```
- **Dans un triangle** :

(^) ⃗ _u_ ⋅⃗ _v_ =^1
2
(‖⃗ _u_ ‖
2
+‖⃗ _v_ ‖
2
−‖⃗ _v_ −⃗ _u_ ‖
2
)
soit ⃗ _AB_ ⋅⃗ _AC_ =^1
2
( _AB_^2 + _AC_^2 − _BC_^2 )
**Cas particuliers** :
• (^) ⃗ _u_ ⋅⃗ _v_ =

#### {

```
‖⃗ u ‖×‖⃗ v ‖ si ⃗ u et ⃗ v sont colinéaires de même sens
−‖⃗ u ‖×‖⃗ v ‖ si ⃗ u et ⃗ v sont colinéaires de sens contraire
```
- ⃗ _u_ ⋅⃗ _v_ = 0 caractérise deux vecteurs ⃗ _u_ et ⃗ _v_ orthogonaux.

**Remarque :** ⃗ _u_ ⋅⃗ _v_ =⃗ _v_ ⋅⃗ _u_


```
R114 : Mathématiques des transmissions TD6 : Produit scalaire
```
```
Exercice 1 :Quelle formule du produit scalaire?
```
```
Dans chaque cas, calculer le produit scalaire ⃗AB ⋅ ⃗AC, puis une mesure de ^BAC si elle n’est
pas donnée.
```
```
Exercice 2 : Perpendiculaire?
```
```
Les diagonales du trapèze ABCD ci-contre sont-elles
perpendiculaires?
```
```
Exercices complémentaires
```
```
Exercice 3 :
```
```
Calculer le produit scalaire ⃗AB ⋅ ⃗AC, puis une
mesure de ^BAC si elle n’est pas donnée.
```
```
Exercice 4 : Angle et repère
```
```
Dans un repère orthonormé du plan on considère A(4;1), B(0;5) et C(-2 ;-1).
```
```
Déterminer une mesure de ^BAC.
```
```
a) b)
```
c)
d)


R114 : Mathématiques des transmissions Chap 3 : Nombres complexes : forme exponentielle

**Chapitre 3**

**NOMBRES COMPLEXES : FORME EXPONENTIELLE**

**1. Forme trigonométrique
2. Forme exponentielle
3. Interprétations géométriques**


R114 : Mathématiques des transmissions Chap 3 : Nombres complexes : forme exponentielle

Le plan est muni d'un repère (O ; ⃗ _u_ , ⃗ _v_ ) orthonormé direct ( (^⃗ _u;_ ⃗ _v_ )=π
2

```
).
```
**1. Forme trigonométrique**

```
1 .1 Module et argument
```
**Définitions :**
Soit z un nombre complexe **non nul** de point image M dans le plan complexe. On appelle :

**- module de** **_z_** , noté | _z_ |, la distance OM= ρ.
**- argument de z** , noté **arg z** , toute mesure en radians de l'angle orienté Φ= ( ^⃗ _u;_ ⃗OM).

0 n'a pas d'argument car ( ^⃗ _u;_ ⃗OM) n'est pas défini.

**_Remarques_** : Un nombre complexe **non nul** z a une **infinité d'arguments** , si Φ est l'un d'entre

eux, les autres sont de la forme Φ + 2 _k_ π. L'argument principal est celui appartenant à ]–π;π].

**Exemples :** Si z = 2 alors ..............................................................................................................

Si z = - 3 alors .................................................................................................................................

Si z = 4j alors ..................................................................................................................................

Si z = 1 + j alors ..............................................................................................................................

**1.2 Premières propriétés**

**Propriétés :**
Soient z et z’ deux nombres complexes non nuls.

**- z = z’** ⇔ **|z|= |z’| et arg z = arg z’ + 2** **_k_** **π (** **_k_** ∈Z **)
-** Si M( _z_ ) alors | _z_ | = OM donc∣ _z_ B− _z_ A∣= ..............
**-** Si z ∈ R alors | _z_ | correspond à ..................
**-** | − _z_ | =......... et pour z ≠ 0 arg (− _z_ )= ........................
**-** | ̄ _z_ | =............. et pour z ≠ 0 arg ( ̄ _z_ )= ........................
**-** z ∈ R* arg(z) =......................................... ⇔
**-** z ∈ j R* arg(z) =........................................ ⇔


R114 : Mathématiques des transmissions Chap 3 : Nombres complexes : forme exponentielle

**-** **_Si z = a + b j_** (z ≠ 0, _a_ et _b_ réels), **|** **_z_** **|= ρ et** Φ **un argument de z
alors a = ρ cos(** Φ **) et b = ρ sin(** Φ **)** (ainsi z = ρ cos( Φ) + ρ sin( Φ) j )
et réciproquement **ρ**^ **= ......................**

**et un argument** Φ **est tel que**

## {

```
cos(Φ)= a
| z |
sin(Φ)=| b
z |
```
```
, soit Φ=
```
# {

```
arctan( b
a
```
```
) si a > 0
```
```
arctan( b
a
)+π si a<0
π
2
si a = 0 et b > 0
−π
2
si a = 0 et b < 0
```
**Exemples** : Déterminer le module et un argument de _z_ 1 =− 2 + 2 j, puis de _z_ 2 = 1 _–_ √ 3 j.

```
1.3 Forme trigonométrique
```
**Définition** : (avec les notations précédentes, pour z ∈ C*)
La **forme trigonométrique** de z est **ρ (cos( Φ) + j sin( Φ) )**.

**Exemples** : **•** _z_ 1 =−^2 +^2 j a pour forme trigonométrique :

_z_ 2 = 1 _–_ √ 3 j a pour forme trigonométrique :

**-** Compléter le tableau ci-dessous :

```
Forme algébrique Calculs intermédiaires Forme trigonométrique
z 3 =− 3
```
```
z 4 = 4 (cos(^2 π
3
```
```
)+jsin(^2 π
3
```
```
))
```
_z_ 5 =− (^2) (cos(π
5
)+jsin(π
5
))


R114 : Mathématiques des transmissions Chap 3 : Nombres complexes : forme exponentielle

**Conséquence** : **Produit de deux nombres complexes non nuls**
Soit z et z’ deux nombres connus par leur forme trigonométrique :
z = ρ (cos(Φ) + j sin(Φ)) et z’ = ρ’ (cos(Φ’) + j sin(Φ’))
alors z z’ = ρ (cos(Φ) + j sin(Φ)) × ρ’ (cos(Φ’) + j sin(Φ’))
z z’ = ρ ρ’ (cos(Φ) cos(Φ’)+cos(Φ) sin(Φ’) j+ sin(Φ)cos(Φ’) j- sin(Φ) sin(Φ’))
z z’ = ρ ρ’ (cos(Φ) cos(Φ’) - sin(Φ) sin(Φ’))+ j (cos(Φ) sin(Φ’)+ sin(Φ)cos(Φ’)))
z z’ = ρ ρ’ (cos(Φ+Φ‘)+ j sin(Φ+Φ’))
Comme ρ ρ’ >0, alors l’écriture ci-dessus est la forme trigonométrique de z z’, donc :

```
|zz’|=ρ ρ’ et arg(zz’) = Φ+Φ’+2 k π ( k ∈ Z )
( les modules se multiplient, les arguments s’ajoutent )
```
**Remarque** : de façon analogue, on obtient :

|

```
z
z' |
```
```
= ρρ' et arg ( z
z' )
```
**= Φ–Φ’+2** **_k_** **π (** **_k_** ∈ Z **)**

```
(les modules se divisent, les arguments se soustraient)
```
**2. Forme exponentielle**

```
2 .1 Définitions
```
**-** On note ejΦ le nombre complexe de **module 1** et d’argument Φ :

```
ejΦ = cos ( Φ )+ sin ( Φ ) j
```
**-** Tout nombre complexe non nul admet une **forme exponentielle** :

```
z = ρejΦ où ρ = |z| et Φ = arg(z)
```
**Exemples** : 1 = ........ j = .......... -1 = .........

_z_ 1 =− 2 + 2 j = ............. _z_ 2 = 1 _–_ √ 3 j= ............ 6 e

```
j^56 π
=...................
```
**2. 2 Propriétés**
Les propriétés ci-dessous, démontrées en utilisant la forme trigonométrique, sont évidentes avec
la forme exponentielle et les opérations sur l’exponentielle étendue aux complexes...
Pour z ≠ 0 , z’ ≠ 0, _k_ ∈Z :

**Conjugué** : | _z_ |=| _z_ | et arg _z_ =−arg _z_ + 2 π _k_

**Produit :** | _zz'_ |=| _z_ || _z'_ | et arg( _zz'_ )=arg _z_ +arg _z'_ + 2 π _k_

**Inverse :** |
1
_z_ |

```
=
1
| z |
```
```
et arg(
1
z
```
)=−arg _z_ + 2 π _k_

**Quotient :** |
_z
z'_ |

```
=
| z |
| z' |
et arg(
z
z'
```
)=arg _z_ −arg _z'_ + 2 π _k_

**Puissance :** | _zn_ |=| _z_ |
_n_
et arg( _zn_ )= _n_ arg _z_ + 2 π _k_ ( _n_ ∈ Z)


R114 : Mathématiques des transmissions Chap 3 : Nombres complexes : forme exponentielle

**_Conséquences_** : |j _z_ |=| _z_ | et arg(j _z_ )=arg _z_ +
π
2

+ 2 π _k_

**Exemples** : Ecrire sous forme exponentielle les nombres complexes suivants :

```
z 1 = –^1
4
```
_-_^1
    4
       j _z_ 2 _= – 2_ e

```
j 6
z 3 = z 12 z 4 =
```
```
z 1
z 2
```
**_Remarques_** **:** | _z + z'_ | ≠ | _z_ | + | _z'_ | : |1+ 3 j | =........................ alors que |1|+| 3 j | =.......... ;
arg(z+z’) ≠ arg(z)+arg(z’)
**Pas de règle générale sur les sommes et différences en forme exponentielle.**

Des relations : (ejΦ) _n_ =ej _n_ Φ et cos(Φ)=Re(ejΦ), sin(Φ)=Im(ejΦ),
on déduit les formules fondamentales :

```
Formule de Moivre, n ∈Z
(cos(Φ)+jsin(Φ)) n =cos( n Φ)+jsin( n Φ)
```
```
Formules d’Euler
cos(Φ)=e
```
```
jΦ+e−jΦ
2
```
```
et sin(Φ)=e
```
```
jΦ−e−jΦ
2 j
```
**3. Interprétations géométriques
Propriétés :**

Si A( _z_ A) et B( _z_ B) alors : **•** ⃗AB a pour affixe ( _z_ B− _z_ A) ;

**-** AB=| _z_ B− _z_ A|
**-** (⃗ _u_ ;⃗AB)=arg( _z_ B− _z_ A) (pour _z_ A _≠z_ B)

###### Si de plus C( z C) et D( z D) ( z C ≠z D) alors (⃗AB;⃗CD)=arg(

```
z D – z C
```
###### z B− z A)

```
.
```
**_Cas particuliers_** :

**-** (AB) et (CD) sont **parallèles** ssi ⃗AB et ⃗CD sont **colinéaires** , soit arg(

```
z D – z C
```
###### z B− z A)

```
= k π, k ∈Z
```
**-** A, B et C sont **alignés** ssi ⃗AB et ⃗AC sont **colinéaires** , soit arg(

```
z C – z A
```
###### z B− z A)

```
= k π, k ∈Z
```
**-** (AB) et (CD) sont **perpendiculaires** ssi ⃗AB et ⃗CD sont **orthogonaux** ,

###### soit arg(

```
z D – z C
```
###### z B− z A)

```
=π
2
+ k π, k ∈Z
```

R114 : Mathématiques des transmissions TD6 : Nombres complexes : forme exponentielle

**TD6 : NOMBRES COMPLEXES : FORME EXPONENTIELLE**

**Exercice  1** D’une forme à l’autre

**1.** Écrire sous forme trigonométrique, puis sous forme exponentielle les nombres complexes
suivants :

```
z 1 = 3 z 2 =− 4 z 3 = 2 j z 4 =−√ 3 +j z 5 = 4 − 4 j z 6 =−^3
7
```
```
j
```
**2.** Écrire sous forme algébrique les nombres complexes suivants :

```
z 1 =e
```
```
jπ 4
z 2 = 2 e
```
```
−jπ 6
z 3 =e
```
```
jπ 6
+e
```
```
−jπ 6
```
**Exercice  2** Opérations
On considère les nombres complexes : _z_ 1 =√ 3 −j et _z_ 2 =− 1 −j.

**1.** Déterminer la forme exponentielle de _z_ 1 et de _z_ 2.
**2.** En déduire le module et un argument des nombres :

```
z 2 z 1 × z 2
z 1
z 2
( z 1 )^2 j z 1
```
**Exercice  3** QCM
Pour chacune des questions, une seule des quatre réponses proposées est exacte.

**1.** La forme exponentielle du nombre complexe _z_ =− 5 + 5 j est :

**a.** _z_ = 5 e

```
j^34 π
```
**b.** _z_ = (^5) √ 2 e
j^34 π
**c.** _z_ = 5 e
−jπ 4
**d.** _z_ = (^5) √ 2 e
−jπ 4

**2.** Si _z_ 1 =^2 √^2 e

```
j^34 π
et z 2 =√^2 e
```
```
−jπ 3
alors z 1 z 2 est un nombre complexe :
```
**a.** de module 4 et dont un argument est^2 π
7

**b.** de module (^2) √ 2 et dont un argument est^5 π
12
**c.** de module 4 et dont un argument est^5 π
12
**d.** de module (^2) √ 2 et dont un argument est^13 π
12

**3.** Le nombre complexe √^2 _–_ j√^2
    √^2 +j√^2

```
est égal à : a. 1 b. j c. - 1 d. - j
```
**4.** Le nombre complexe de module (^2) √ 3 et dont un argument est^2 π
3
a pour forme algébrique :
**a.** (^) √ 3 _–_ 3 j **b.** 3 _–_ j√ 3 **c.** −√ 3 + 3 j **d.** − 3 +j√ 3

**5.** Le nombre complexe _z_ =−^3 e

```
jπ 6
a pour argument :
```
**a.** π
6
**b.** −π
6
** c.**^5 π
6
** d.** −^5 π
6


R114 : Mathématiques des transmissions TD6 : Nombres complexes : forme exponentielle

**Exercice  4 ** Angles non remarquables
Déterminer une valeur d’un argument de _z_ 1 = 3 − 2 j puis de _z_ 2 =− 2 + 5 j.

**Exercice complémentaire**

**Exercice  5** Circuit RC
Le quadripôle représenté ci-contre est constitué d’un résistor de
résistance R exprimée en Ω et d’un condensateur de capacité
C exprimée en μF.
On associe respectivement à la tension d’entrée et à la tension
de sortie les nombres complexes _z_ e et _zs_.

On appelle transmittance le nombre complexe Z défini par Z=

```
zs
z e
.
```
On admet que Z=^1
1 +jRCω
où ω désigne la pulsation exprimée en radians par seconde.

Dans tout l’exercice, on suppose que : R = 50 Ω, C = 2 μF et ω =^1
100

(^) rad.s−^1.

**1.** Vérifier que Z=^1
    1 +j
       puis déterminer le module et un argument de Z.

**2.** Le module de _zs_ peut-il être le double de celui de _z_ e? Justifier la réponse.

**3.** Dans cette question seulement, on suppose qu’un argument de _zs_ est π
2
.

Déterminer alors un argument de _z_ e.

**4.** On suppose dans cette question que _z_ e= 150 (−√ 3 +j).
    **a.** Déterminer la forme exponentielle de _z_ e.
    **b.** Déterminer la forme exponentielle du nombre complexe _zs_ correspondant.
    **c.** Le plan complexe est rapporté au repère orthonormal (O;⃗ _u,_ ⃗ _v_ ) de telle manière qu’un
centimètre représente 100 unités. Placer les points Me et M _s_ images respectives des nombres
complexes _z_ e et _zs_.


R114 : Mathématiques des transmissions TD7 : Nombres complexes et géométrie

**TD7 : NOMBRES COMPLEXES ET  GEOMETRIE**

**Exercice  1**

**1.** Résoudre dans C l’équation : _z_^2 _–_ 8 _z_ + 32 = 0.
**2.** Écrire les solutions de cette équation sous forme exponentielle.
**3.** Soit le nombre complexe 4 e

```
jπ 3
```
. Déterminer sa forme algébrique.
**4.** Dans le plan complexe rapporté à un repère orthonormal (O;⃗ _u,_ ⃗ _v_ ) d’unité graphique 1 cm, on

donne les points A, B et C d’affixes respectives : _z_ A=^4 +^4 j ; _z_ B=^4 −^4 j et _z_ C= 2 + 2 j√ 3.

```
a. Placer les points A, B et C dans le repère (O;⃗ u, ⃗ v ).
b. Montrer que le triangle ABC est rectangle.
```
**Exercice  2**

Le plan est muni d’un repère orthonormal (O;⃗ _u,_ ⃗ _v_ ) d’unité graphique 1 cm.

**1.** Résoudre dans C l’équation : _z_^2 _–_ 6 _z_ + 34 = 0.
**2.** Soient A, B et C les points d’affixes respectives _z_ A= 3 + 5 j, _z_ B= 3 − 5 j et _z_ C= 4 j.

```
a. Placer A, B, C dans le repère.
b. Calculer les modules des nombres complexes : z A – 3 ; z B – 3 et z C – 3.
c. Déduire de la question précédente que les points A, B, C sont sur un même cercle dont
on précisera le centre et le rayon.
d. Quelle est la nature du triangle ABC?
```
**Exercice complémentaire**

Soit _z'_ =
_z_ − 1
̄ _z_ −^1

```
pour z ≠ 1. Le plan est muni d’un repère orthonormal (O;⃗ u, ⃗ v ).
```
On considère dans ce repère les points A(1), B(-1), M(z) et M _'_ ( _z'_ ).

Le but de cet exercice est de développer une méthode de construction du point M _'_ connaissant
le point M.

**1.** Calculer | _z'_ | puis interpréter le résultat obtenu.
_Indication : On se servira des propriétés des modules et conjugués._


R114 : Mathématiques des transmissions TD7 : Nombres complexes et géométrie

**2.** Soit z ≠ 1.
    **a.** Démontrer _z_ + ̄ _z_ , _z_ ̄ _z_ sont des nombres réels, ainsi que ( _z_ − 1 )( ̄ _z_ − 1 ).
    **b.** On définit _r_ = _z'_ +^1
       _z_ − 1
         . Montrer que r est un nombre réel.
    **c.** On suppose que M _'≠_ B.
    Déduire de la question précédente une mesure de l’angle (⃗AM;⃗BM _'_ ).
    **d.** Que peut-on en déduire pour les vecteurs ⃗AM et ⃗BM _'_? Et pour les droites (AM)et
       (BM _'_ )?
**3.** Proposer une méthode de construction du point M _'_ sans calculer son affixe. On pourra mettre
en œuvre ce protocole pour M 1 (j), puis pour M 2 (−^2 −j).


R114 : Mathématiques des transmissions **Compte-rendu du TP n°2 : Nombres complexes**

```
Une aide pour utiliser le logiciel Maple se trouve sur Moodle dans l’onglet TP 1.
```
```
Vocabulaire : « idoine » signifie « Qui convient parfaitement, approprié.»
```
**Exercice 1 : Manipulation de nombres complexes définis sous forme algébrique ou exponentielle**

1. Soit z 1 = − 189 + j 63 √ 3 , soit φ 1 son argument...

```
Conjugué de z 1 : Module de z 1 : Fonction idoine Maple :
```
```
cos(φ 1 ) : sin(φ 1 ) : φ 1 : Fonction idoine Maple :
```
```
Forme exponentielle de z 1 : Comment placer M 1 (z 1 )? Fonction idoine Maple :
```
2. Soit z 2 = (^3) √ 2 e

(^)
| z 2 | = z = Fonction idoine Maple :
arg(z 2 ) = Fonction idoine Maple :
Forme algébrique de z 2 : Fonction idoine Maple :
Comment placer M 2 (z 2 )?


R114 : Mathématiques des transmissions **Compte-rendu du TP n°2 : Nombres complexes**

**Exercice 2 : Affixe d’un point écrite sous forme exponentielle**

Dans chacun des cas suivants, déterminer et représenter l’ensemble des points M ci-dessous.

1. E 1 = { M(z) ; Re(z) = − 3 }
2. E 2 = { M(z) ; |z| = 5 }
3. E 3 = { M(z) ; Im(z) = 5 }
    4. E 4 = { M(z) ; z = 4  où α∈[ 0 ; 2 π [ }
    5. E 5 = { M(z) ; z = k 

```

 où k∈[ 0 ; + ∞ [ }
```
6. E 6 = { M(z) ; z = k 

```

```
(^) avec k ∈[1 ; 4] }
E 1 E 2 E 3
E 4 E 5 E 6
**Exercice 3 : Module, argument et écriture algébrique d’un nombre complexe**
Soit le nombre complexe z = √

.


R114 : Mathématiques des transmissions **Compte-rendu du TP n°2 : Nombres complexes**

```
Module de z : Argument de z : Validation Maple :
```
```
Forme algébrique de z : Validation Maple :
```
**Exercice 4 : Les points sont-ils alignés?**

Soient les points A, B, C d’affixe respective zA = −− 2j, zB = 1 + 2j, zC = + 10j.

Par le calcul puis avec Maple, vérifier que les points A, B et C sont alignés.

Validation Maple :


R114 : Mathématiques des transmissions **Compte-rendu du TP n°2 : Nombres complexes**

**Exercice 5 : Résolution d’équations et factorisation de polynômes**

1. Résoudre dans ℂ les équations suivantes. Donner chaque solution sous forme algébrique.

(E1) 2 _z_^2 – 6 _z_ + 5 = 0

(E2) _z_^2 = _z_ − 5

2. Factoriser les polynômes suivants. Vérifier les résultats avec Maple.

P 1 (z) = 2 _z_^2 – 6 _z_ + 5

P 2 (z) = 4z^2 + 12z + 9

P 3 (z) = _z_^2 – _z_ + 5

P 4 (z) = – 9z^2 – 12z + 4

P 5 (z) = _z_^2 + 5

P 6 (z) = – 8 _z_^2 + z


**Les valeurs à trouver dans les questions complémentaires** ( 1 / 3 )

TD 1

1. Simplifier le plus possible l’écriture des nombres suivants :

```
M 1 = (e^6 )^2 + e^3 – 2e^15 e−^6 = e^12 + e^3 – 2 e^9 = e^3 (e^9 – 2 e^6 + 1)
```
```
M 2 = log 2 ( 281 ) – log 2 (4) = – 4 – log 2 (7)
```
```
M 3 = 4 log 10 (8) − 3 log 10 (12) – log 10 (
8
3 )^ = log^10 (
```
```
8
```
9 )^

2. Donner l’ensemble de définition des fonctions suivantes puis simplifier le plus possible leur expression.

h 1 (f) = 3 ln(f²) – 8 ln(√f) + 2 ln(f^ −^3 ) + 5 ln(f^2 4 ) Dh 1 =+∗ h 1 (f) = – 24 ln(f) + 5 ln(2)

h 2 (t) = e^4 ln(t)−^3 Dh 2 =+∗ h 2 (t) = t^4 e−^3 =
t^4
e^3

3. Résoudre l’équation (E 1 ) S 1 = {− 1 ; 45 } (E 2 ) S 2 = {−^10011999 }
4. Résoudre l’inéquation 50,3x > 2 S = ]𝑒

```
ln ( 0 , 4 )
```
0 , (^3) ;+∞[

5. Soit g(x) = 5.10-^6  10

```
𝑥
```
(^20).
a) Déterminer son ensemble de définition : Dg =
b) Déterminer sa dérivée : g’(x) =^5210 −^7 ln( 10 ) 10
𝑥
(^20) = ln(^10 )^10
𝑥
20
4. 106
TD 2
**Exercice complémentaire 1** Magnitude d’un astre

**1.** Calculer ln(a). ln(a) = − 0,2 ln(100)
**2.** Justifier mathématiquement que la magnitude diminue lorsque l’éclat augmente.

M = g(E) avec g(E) = log𝑎(EE
0
)= log𝑎(𝐸)− log𝑎(𝐸 0 )

g’(E) = ln (^1 a)E ln(a) = − 0,2 ln(100) ln(a) < 0 g’(E) < 0

```
g est décroissante. Donc la magnitude diminue lorsque l’éclat augmente.
```
**3.** Déterminer la magnitude apparente du Soleil (E= 4 , 786. 1010 E 0 ) : Msoleil  − 26,7

```
et de la Lune (E= 1 , 2. 105 E 0 ). Mlune  − 12 ,7
```
**4.** Exprimer l’éclat de cette étoile en fonction de E 0. E = 10^12 E 0
**5.** Déterminer l’éclat E de cette étoile par rapport à celui de Véga. E  3,87 E 0

**Exercice complémentaire 2** Gain en décibels

**Soit G[dB] = 10 log 10** (
𝐏𝐬 [𝐖]
𝐏𝐞 [𝐖])**.**^

1. Calculer G **[dB]** pour Ps **[W]** = 72 et Pe **[W]** = 60. G[dB]  0,791
2. Calculer Ps **[W]** pour Pe **[W]** = 50 et G **[dB]** = − 2,5. Ps [W]  28,117
3. Calculer Pe **[W]** pour Ps **[W]** = 32 et G **[dB]** = 20. Pe [W] = 0,32


**Les valeurs à trouver dans les questions complémentaires** ( 2 / 3 )
**Exercice complémentaire 3**

**1. a.** Calculer le degré Beaufort, arrondi à l’unité, pour une vitesse v = 90 km.h-^1.

```
B = 900
```
```
1
```
(^3) B  9,65
**b.** Calculer la vitesse du vent v (en km.h-^1 ) correspondant à un vent de force 10 Beaufort.
v = 3. 10
3
(^2) B  94,9 km.h-^1

**2.** Démontrer que la relation entre B et v peut s’écrire log 10 (𝑣)=^32 ×log 10 (B)+log 10 ( 3 )

B^3 =𝑣

```
2
9 ^ log^10 (B
```
(^3) )=log 10 (𝑣^2
9 )^
B^3 =𝑣
2
9 ^ ...^
B^3 =𝑣
2
9 ^ log^10 (𝑣)=
3
2 ×log^10 (B)+log^10 (^3 )^

**3.** Si on représente, dans un repère logarithmique, v en fonction de B, La représentation graphique est une
droite de coefficient directeur^32 : v augmente de 3 décades quand B augmente de 2 décades.

TD 4

**Exercice 3** Soit _f_ la fonction de variable complexe z, définie pour z ≠ 1 par 𝑓(𝑧)=^2 𝑧𝑧−+ 11.

**1.** Soit A le point d’affixe 𝑧A=𝑓(^14 –^34 j). 𝑧A=𝑓(^14 –^34 j) = 2j

𝑧A est un nombre imaginaire pur, donc A est sur l’axe des imaginaires purs.

**2.** On résout 𝑓(𝑧)=𝑧 : 𝑓(𝑧)=𝑧  (^2) 𝑧𝑧−+ 11 =𝑧
𝑓(𝑧)=𝑧  2 𝑧+ 1 =𝑧(𝑧− 1 ) 𝑒𝑡 𝑧 1 ...
L’ensemble des points invariants par f est {𝐴(^3 − 2 √^5 );𝐵(^3 + 2 √^5 )}
TD 5
**Exercice 3** 𝐴𝐵⃗⃗⃗⃗⃗^ ⋅𝐴𝐶⃗⃗⃗⃗⃗^ = 20 𝐵𝐴𝐶̂=𝑎𝑟𝑐𝑐𝑜𝑠(^5 √ 3434 )≈ 0 , 54 𝑟𝑎𝑑=31°
**Exercice 4** 𝐵𝐴𝐶̂=𝑎𝑟𝑐𝑐𝑜𝑠(√
5
5 )≈^0 ,^35 𝑟𝑎𝑑=^63 ,4°^
TD 6
**Exercice 5** Circuit RC

**1.** Vérifier que Z= 11 +j puis déterminer le module et un argument de Z.

```
|Z|= √ 22 arg(Z) = − 4
```
**2.** Le module de 𝑧𝑠 peut-il être le double de celui de 𝑧e? Justifier la réponse.

```
| zs | = 2 | ze |  ...  |Z| = 2 or |Z|= √ 22 ; |Z|  2
Il est impossible que | zs | = 2 | ze | si zs  0 et ze  0.
```
**3.** Déterminer alors un argument de 𝑧e. arg( ze ) =^34 
**4. a.** Déterminer la forme exponentielle de 𝑧e : ze = 300 e^ j

```
5 
```
(^6)
**b.** Déterminer la forme exponentielle du nombre complexe 𝑧𝑠 correspondant. zs = 150√ 2 e^ j
7 
(^12)


**Les valeurs à trouver dans les questions complémentaires** ( 3 / 3 )

**c.** Le plan complexe est rapporté au repère orthonormal (O;𝑢⃗ ,𝑣 ) de telle manière qu’un centimètre
représente 100 unités. Placer les points Me et M𝑠 images respectives des nombres complexes 𝑧e et 𝑧𝑠.

TD 7
**Exercice complémentaire**

**1.** Calculer |𝑧′|puis interpréter le résultat obtenu. |𝑧′|= 1 M’ est sur le cercle de centre 0 et de rayon 1.
**2.** Soit z ≠ 1. **a.** Démontrer 𝑧+𝑧̅, 𝑧𝑧̅ sont des nombres réels, ainsi que (𝑧− 1 )(𝑧̅− 1 ).

```
𝑧+𝑧̅= 2 Re(z) qui appartient à  𝑧𝑧̅ = |z|² qui appartient à 
```
```
(𝑧− 1 )(𝑧̅− 1 ) = |𝑧− 1 |^2 qui appartient à 
```
**b.** On définit 𝑟=𝑧𝑧′−+ 11. Montrer que r est un nombre réel : r = qui appartient à 

**c.** On suppose que M′≠B. On déduit (AM⃗⃗⃗⃗⃗⃗⃗^ ;BM⃗⃗⃗⃗⃗⃗⃗⃗^ ′) = arg(r) = 0 + k où k

```
d. Que peut-on en déduire pour les vecteurs AM⃗⃗⃗⃗⃗⃗⃗^ et BM⃗⃗⃗⃗⃗⃗⃗⃗^ ′? Ils sont colinéaires.
Pour les droites (AM) et (BM′)? (AM) // (BM′)
```
**3.** Proposer une méthode de construction du point M′sans calculer son affixe

```
M’ (différent de B) est à l’intersection du cercle de centre 0 et de
rayon 1, et de la droite parallèle à (AM) passant par B.
```
**3.** Proposer une méthode de construction du point M′sans calculer son affixe. On pourra mettre en œuvre ce
protocole pour M 1 (j), puis pour M 2 (− 2 −j).

```
▪ On trace le cercle C de centre 0 et de
rayon 1.
```
```
▪ On place les points A, B, M, et on trace
la droite D passant par B et parallèle à
(AM).
```
```
▪ D coupe C en B et M’.
```

**Dérivées usuelles Dérivées des fonctions composées associées**

```
g(x) La dérivée de g(x) g(x) La dérivée de g(x)
k (constante) 0
x 1 u [u]′=′
x n n x n−^1 (u)^ [(u)^ ]′=^ ()^ ′^
1

−
```
```
1

```
```
1
u

```
```
1
u

```
```

=−
```
```
′
²
```
```
√^
```
```
1
```
(^2) √
(^) √u √u′=
′
√
ln(| _x_ |)^1

ln(u) [ln (u)]′=
′

e _x_ e _x_ e [e]′=^ ′^
cos( _x_ ) - sin( _x_ ) cos(u) [cos(u)]=−"#
 ()^
sin( _x_ ) cos( _x_ ) sin(u) [sin (u)]=%&"()^
tan( _x_ )
'
()*²(+) = 1 + tan²( _x_ ) tan(u)
[tan (u)]=%&"²()
=′( +/0 ())
arctan( _x_ )
1
1 +
arctan(u) [arctan (u)]=
′
+()²
**Primitives usuelles Primitives de fonctions composées associées**
g(x) **Une** primitive de g(x) g(x) **Une** primitive
^2 (n ≠ −1)^3 ^2 4 =
^25 '
6 + 1
7 ′()[ 7 ()]^2
(n ≠ − 1)^37 ′()[^7 ()]
(^2) 4 =^8 (^9 )
: 5
:+
−
1

3 −
1

4 =
1

(^) −
7 ()
[ 7 ()]^
3 −
7 ()
[ 7 ()]4 =
8 ( 9 )
1
(^2) √
3
1
(^2) √
4 =√
7 ()
2 ; 7 ()
3
7 ()
2 ; 7 ()
4 =; 8 ( 9 )
1

3
1

4 =ln || (^)
7 ()
7 ()
3
7 ()
7 ()
4 ==
 | 8 ( 9 )|
e+ 3 e+4 =e+^7 ′()e>(+) 37 ′()e>(+)4 =^8 (^9 )^
sin () 3 sin ()4 =−cos()^7 ′()sin ( 7 ()) 37 ′()sin (^7 ())4 =−%&" (^8 (^9 ))^
cos() 3 cos()4 =?@6 ()^7 ′()cos( 7 ())^37 ′()cos(^7 ())4 ="#
 (^8 (^9 ))^
1
cos²()
3
1
cos²()
4 =BC6 () (^)
7 ′()
cos²( 7 ())
3
7 ′()
cos²( 7 ())
4 =/0
 ( 8 ( 9 ))
1
1 +²
CDEBC6 ()^
7 ′()
1 + 7 ²()
3 7 ′()
1 + 7 ²()
4 =0F%/0
 ( 8 ( 9 ))
**u désigne une fonction dérivable.**


**2023 - 2024 Planning prévisionnel** R1.14 Mathématiques des transmissions

```
C (3 séances + DS) TD (12 séances) A faire pour la séance de TD suivante
1 s 36 Chap 1 : Fonctions puiss , log et expo
```
```
2 s 37 TD 1 Fonctions
```
```
3 s 38 Fin TD1
```
```
4 s 39 TD 2 Applications du log
```
```
5 s 40 Chap 2 : Nb cplx et forme algébrique Fin TD2
```
```
6 s 41 nbs cplx (forme alg)TP 1 log10
```
```
7 s 42
```
```
Evaluation 1 +
TD 3 Nombres
Complexes (forme alg)
```
```
8 s 43 Fin TD 3
```
```
9 s 45 polynômes de degré 2TD 4 Racines d'un
```
```
10 s 46 TD 5 Produit scalaire
```
```
11 s 47 Chap 3 : Nb cplx et forme expo
```
```
12 s 48
```
```
Evaluation 2 + TD 6
Nombres complexes
(forme expo)
```
```
13 s 49 TD 6
```
```
s 50 complexes et géométrieTD 7 Nombres
```
```
s 51 Fin TD 7
```
```
s 2 TP 2 Nbs complexes
s 3 DS
```


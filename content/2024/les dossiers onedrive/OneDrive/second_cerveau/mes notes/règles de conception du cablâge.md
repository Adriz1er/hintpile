---
aspiration: []
---
Le précâblage est une notion de câblage par anticipation afin d'éviter les extensions au fur et à mesure de l'expression des besoins ; idéalement il est mis en place lors de la construction des locaux ... et même avant idéalement (au niveau de l'architecte)

Le système de câblage est une solution normalisée
Système de câblage et précâblage s'appuient sur la notion d'architecture générale de bâtiment

1.1.1 Précâblage - Argumentation

Le coût du câblage se compose:
- de main d'œuvre (50%)
- de fournitures (câbles, connecteurs, ...) (50%)

Ce coût reste élevé alors que dans le même temps:
- le coût des équipements de transmission numérique intégrant le VDIE baisse régulièrement
- les PC voient leur puissance de calcul et leur capacité de stockage augmenter 
- les débits réclamés sont de plus en plus importants... mais pas forcément connus par anticipation

Les évolutions technologiques contribuent à une transformation rapide des réseaux 
-un câblage sur mesure à l'instant t mais réadapté au coup-par-coup en fonction de l'évolution des besoins reviendra à long terme bien plus cher qu'un précâblage correctement dimensionné de façon initiale

Mais l'anticipation est très difficile: fin 2004/début 2005 les solutions sans fils comme le WiFi n'intégraient pas diverses caractéristiques essentielles au niveau des usages c'est à dire :
- la gestion de la qualité de service
- la sécurité
- un partage équitable de la bande passante entre les différents utilisateurs connectés

Le précâblage se justifie également par la nécessité d'offrir aux
entreprises des espaces de travail adaptables, c'est à dire :
- sans devoir "tirer de nouveaux câbles"
- sans des locaux
- Pour s'adapter aux nouvelles dispositions du mobilier 
- sans gêner les occupants dans l'exercice de leur fonction

Précâbler un immeuble consiste à:
- poser un réseau de conducteurs
- poser des points de connexion en quantité, qualité et flexibilité suffisantes afin de pouvoir relier 2 points *quelconques* de ce bâtiment par *n'importe quel type de réseau*: voix, données, images, énergie.

En conséquence, ce précâblage suppose la présence de prises en tout point du bâtiment pour permettre : 
- le raccordement des postes de travail ou leur déplacement sans avoir à reposer de câbles
- la reconfiguration topologique des réseaux déjà en place sans modification structurelle du câble 

Garantir que l'homogénéité du câblage (prises et câbles de distribution et capillaires) est conforme aux normes internationales en tout point de l'immeuble pour pouvoir recevoir indifféremment tout type de terminaux et s'interfacer avec tout réseau.
Le précâblage est donc un investissement profitable car il permet de minimiser les dépenses de pose et repose à long terme qui pourraient être dues au manque de fiabilité ou au manque d'anticipation.
### Normalisation, spécifications
Plus le débit augmente, plus on augmente les fréquences de travail et plus le câble doit être pensé et structuré. par exemple en 1995, les débits demandés étaient <100 MHz !
Il y a donc une nécessité de création de produits répondant aux normes en vigueur. Ces produits seront associées à des catégories de fonctionnement
1) Normes ISO/IEC 
2) Normes Européennes (CENELEC)
3) Amérique du Nord TIA 
4) Normes Françaises (France Télécom/Orange qui sont très bonnes) mais le poids d'un norme française est faible au niveau international

C'est donc les normes internationales prennent le pas sur les autres.
#### construction d'une norme
On (les fabricants et les membres des organismes représentatifs) définit des exigences à respecter

Dans les faits on commence par des drafts qui évoluent et convergent au fur et à mesure de consensus, c'est un processus qui est fatalement long

En matière de norme, il est inutile de tout connaître mais il faut savoir où chercher l'information
En France, l'AFNOR et l'UTE, membres respectivement de l'ISO et la CEI, mais aussi des syndicats professionnels et France Télécom/Orange ont édité des spécifications

La norme internationale ISO/CEI 11801 définit les paramètres à mesurer et les valeurs à respecter pour les connecteurs et les chaînes de liaison mais pas les caractéristiques techniques des composants
- les mesures sur les composants réalisées en laboratoire permettent d'identifier leurs catégories
- les mesures sur la chaîne de liaison (lien channel), réalisées sur le terrain, lors de la recette d'installation définissent la classe de transmission de cette chaîne de liaison
Dans les faits :
- Classe D avec des composants cat. 5
- Classe E avec des composants cat. 6
- Classe F avec des composants cat. 7

un cas : International ISO/IEC-11801-1 (Edition 3) Câblage générique pour immeubles comportant des bureaux
consiste fournir un standard international pour la performance, la conception. l'installation, l'identification des systèmes de câblages dans les immeubles avec des bureaux. Elle définie l'architecture et les performances des systèmes de câblages aux fréquences de 100, 250, 600 et 1000 MHz, historiquement :
- Créé en 1995 Edition 2 en Nov. 2002
- Amendement 1.2 (classes Ea et F) récent
- Edition 3 en 2017 avec des correctifs en 2018

Son Installation et ses tests optiques (qui est standard pour l'implémentation et l'exploitation des systèmes de câblage) :
ISO/IEC 14763-1 : Identification
ISO/IEC 14763-2 : Planning et installation
ISO/IEC 14763-3 : Test câblage fibre optique (definition de la procedure de test)

fait partie d'une totalité de standards reliés sous la tutelle de ISO 11801 Ed 2


Amérique du Nord: TIA/EIA-568B
- planning et installation d'un système de câblage structuré pour des immeubles de bureaux.
- spécifier système de câblage générique qui supportera un environnement multi-produits, multi-constructeurs etc... 
Cablage générique pour immeubles de bureaux
- TIA/EIA-568A- Octobre 1995 (moins répandue)
- EIA/TIA-568B-juin 2002 - catégorie 6 (250 MHz)
- Cat 6A (500 MHz)

Europe CENELEC EN 50174: Installation ; correspondant à la norme informative soit les Règles d'installation :
- EN 50174-1 : Specification, assurance qualité, identification et exploitation
- EN 50174-2 définit les règles d'installation : Planning, conception, installation dans le bâtiment. Ex: 20cm de séparation en UTP 13cm de séparation/neons
- EN 50174-3 : Planning, conception, installation à l'extérieur des bâtiments (Ex: campus)

Pour chaque composant, les paramètres à prendre en considération sont:
- ses caractéristiques mécaniques
- ses caractéristiques électriques d'affaiblissement, de réflexion et de paradiaphonie

Les catégories de composants:
- Catégorie 3: câbles et connecteurs dont les caractéristiques de transmissions sont spécifiées jusqu'à 16 MHz
- Catégorie 4: câbles et connecteurs dont les caractéristiques de transmissions sont spécifiées jusqu'à 20 MHz
- Catégorie 5 câbles et connecteurs dont les caractéristiques sont spécifiées jusqu'à 100 MHz
- Catégorie 6: câbles et connecteurs sont spécifiées jusqu'à 250 MHz
- Catégorie 6A 500 MHz de transmissions dont les caractéristiques de transmissions
- Catégorie 7: 600 MHz (et 1000 MHz pour la 7A)
- Catégorie 8: 2000 MHz sur 30m uniquement


Fin 1990, chez Amadeus, on pose le standard du marché en classe 6 ou 6a?
En fait, on pose catégorie 7 pour les câbles avec des connecteurs 6 ou 6a. (→ C'est une stratégie intelligente).

Si on est locataire lors de la décision à prendre alors ce n'est pas la peine d'investir si on est locataire.

Aujourd'hui, il y a de la catégorie 6 de partout. Un peu de 6a dans les datacenters.
NEXANS a réussi à introduire un connecteur GG45, de catégorie 7, rétro- compatible Cat 5/6/6A. Il existe aussi les connecteurs TERA et ARJ45.
Est-ce que le RJ45 va survivre à une catégorie 7, 7a, 8 ? Difficile à prédire.

Les fabricants d'éléments de réseau actifs se sont prononcés sur le plan international pour un connecteur compatible avec RJ45, ce qui correspond à la catégorie d'éléments 8.1. Cette solution est rétrocompatible avec les milliards de connecteurs RJ45 installés dans le monde.

Catégorie 3
La catégorie 3 est un type de câblage testé à 16 MHz. Ce type de câble sert pour la téléphonie pour les lignes analogiques et numériques. Il est également utilisé pour les réseaux Etherne (10 Mb/s). Ce type de câblage est en abandon depuis 2007 par les opérateurs au bénéfice de câbles de catégorie 5 ou supérieure, pour la transmission de la voix comme des données. 

Catégorie 4
La catégorie 4 est un type de câblage testé à 20 MHz. Ce standard fut principalement utilisé pou les réseaux Token Ring à 16 Mbit/s ou les réseaux 10BASE-T. Il fut rapidement remplacé par les catégories 5 et 50. 

Catégorie 5 Classe D
L'ancienne catégorie 5 permet une bande passante de 100 MHz et un débit allant jusqu? 100 Mbit/s. Ce standard permet l'utilisation du 100BASE-TX, ainsi que diverses applications de téléphonie ou de réseaux (Token ring, ATM). La catégorie 5 est obsolète et remplacée par catégorie Se.
La catégorie Se (enhanced) peut permettre une quantité d'information allant jusqu'à 1 000 Mbit/s
C'est un type de câblage tenté à 100 MHz. La norme est une amélioration de la catégorie 5 pour permettre le Gigabit Ethernet

Categone 6/classe.E
La catégorie 6 est un type de câblage testé jusqu'à 250 MHz. En théorie, il devait permettre 1000Base-TX fonctionnant à 200 MHz on 2x2 paires simplex au lieu de 77 MHz en 4 paires ful duplex. Ceci devait réduire les coûts de production des interfaces réseaux. Grace à une moins forte resistance, le câble catégorie 6 reste avantageux par rapport au catégorie Se pou réutilisation du PoE où il permet des économies d'énergie. 
Catégorie 6a/classe Ea 
Ratifiée le 8 février 2008, to norme 6a est une extension de la catégorie 6 avec une bande

Categorie 7 classe F
passante de 500 MHz Cette norme permet le fonctionnement du 10GBASE-T
La catégorie 7 est testée à 600 MHz. Elle permet l'acheminement d'un signal de télévision modul en bande VHF ou UHF, mais pas dans une bande satellite (qui nécessite une bande passante di 2 200 MHz). La catégorie 7 ne reconnait pas le connecteur RJ45 et à la place en reconnaitre 3 autres. À cause de ce manque de compatibilité, la catégorie 7 est très peu utilisée.

Catégorie 7a/classe Fa
La catégorie 7a est testée à 1 GHz et permet un débit allant jusqu'à 10 Gbit/s, tout comme le catégories 6a et 7. Par contre, le connecteur RJ45 n'est pas reconnu, créant les même: difficultés que catégorie 7 pour connecter les équipements.
#### 10BASE-T (10Mbit/s)
- 10BASE-T est une norme Ethernet utilisant une topologie réseau en étoile et des câbles à torsadées équipés de connecteurs RJ45.
• 10BASE-T a été conçu pour pallier les problèmes de 10BASE5 et 10BASE2, les autres standards Ethernet 10 Mbit/s qui souffraient de pannes et de l'utilisation de câbles chers. Cette solution s'est vite démocratisée en raison de la simplicité et de la «propreté de câblage », car les câbles posés pour un usage téléphonique pouvaient parfois être réutilisés.

Caractéristiques:
Supporte des transmissions de données à des débits jusqu'à 10 Mbit/s sur paires torsadées d'une longueur de 100 mètres et sans répéteurs. Autorise des opérations en mode full duplex.
#### 100BASE-TX (100Mbits/s)
Le 100BASE-TX est une norme de câblage réseau mise au point pour l'élaboration di Fast Ethernet 100BASE-T
• Il s'agit d'une norme de transmission de données prenant en charge le full-duplex grâce à l'utilisation de 2 paires torsadées. 
- Le cablage 100BASE-TX peut être utilisé en topologie étoile ou sous forme de bur lineaire, d'une longueur maximale de 100 mètres entre deux équipements pour un débit de 100 Mbit/s.

Son support est la paire torsadée (2 paires). Les deux paires sont en câble catégori 5. La norme recommande d'utiliser du câble catégorie 5 et de limiter la longueur du câble à 90 mètres entre prises murales réseau et l'équipement d'interconnexion auquel elle: sont reliées, pour réserver 10 mètres au raccordement entre la prise murale et le matérie connecté.
#### 10GBASE-TX (10Gbit/s)
10GBASE-T est une norme Ethernet initiée en 2002 et ratifiée le 8 juin 2006.
Elle prévoit la transmission de données jusqu'à un débit de 10 Gbit/s sur du câble en cuivre à paires torsadées et à une distance 100 mètres. 10GBASE-T fait partie des protocoles du standard 10 Gigabit Ethernet à grande vitesse.

Caractéristiques: 
- autorise des opérations en mode full duplex seulement 
- supporte des liaisons filaires par câble en cuivre spécifiées par la norme ISO/CEI
- 11801:2002. 
	- définit la couche PHy 10 Gbit/s avec un type de liaison supportant du câble en cuivre à paires torsadées équilibrées sur une longueur de 100 mètres. 
	- 10GBASE-T reste compatible avec les normes 100BASE-TX et 1000BASE-T qui utilise des cable 100 ohms à quatre paires torsadées de type UTP ou FTP


Les normes européennes basées sur la norme ISO/CEI 11801 concernent:
- les caractéristiques techniques de la chaîne de liaison
- les caractéristiques techniques des câbles capillaires
- les caractéristiques techniques des cordons de brassage
- les caractéristiques techniques des cordons de raccordement des terminaux

Pour améliorer les performances en Compatibilité Electromagnétique (CEM) de l'installation, les câbles et les cordons doivent posséder, soit un blindage général, soit une tresse générale: câbles UTP, FTP, F/UTP, F/FTP, SFTP
Les paires sont torsadées (2 fils): il y a donc des effets selfiques, résistifs et capacitifs au niveau des conducteurs.

Tout d'abord, il faut respecter 5mm d'écartement avec la prise (dépairage) et un alliage en Or (pas en Aluminium).
Il faut blinder les câbles car ceux-ci peuvent traverser des zones polluées électromagnétiquement.
Par exemple, un PoE 80W à proximité pollue beaucoup: rayonnement électromagnétique, échauffement, courants induits.
Les paires torsadées se protègent entre elles.
Les Français ont l'habitude de blinder les paires alors que les Américains utilisent plutôt un blindage général du câble appelé écrantage.

Pour le blindage des paires torsadées, il existe:
- UTP (unfoiled) - sans blindage
- FTP (foiled) - avec blindage par feuillard
- STP (braided shielding) - avec blindage par tresse

Plus précisément
- U/UTP (sans blindage général, sans blindage par paire)
- F/UTP (blindage général, sans blindage par paire)
- U/FTP (sans blindage général, blindage par paire)
- F/FTP (blindage général, blindage par paire)
- SF/FTD (blindage général, blindage par paire et par tresse)

C'est mieux de blinder les paires plutôt que d'avoir un blindage général.
Ex: SF/FTD utilisé en environnement industriel agressif comme les cabines d'ascenseurs


La famille des cables à paires torsadees se subdivise en quatre, selon leur constitution:
- les cables UTP, non blindes et d'impédance de 100 $\ohm$,
- les cables FTP, écrantes et d'impedance de 120$\ohm$, 100$\ohm$ 
- les cables SFTP, blindés et d'impedance de 100$\ohm$, S-FTP.
- les cables S-STP blindés pour paires, 100 $\ohm$.
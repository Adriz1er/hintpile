---
aspiration: []
---
Pour analyser et traiter du texte de façon très rapide
- vérification de données
- mise en forme du texte
- recherche d'informations précises dans un fichier

a des expressions basées sur des "motifs" : un vrai language qui utilise des caractères spéciaux. 
Il ne faut pas les confondre avec les méta-caractères.
Les [[expressions régulières]] ne sont utilisées que par certaines commandes
Elles se retrouvent dans d'autres choses notamment languages
## exprimer une position
- `^` début d'une ligne
- `$` fin d'une ligne

A noter que `^[...]$` exprime une ligne complète
## exprimer des caractères
- `[car]` caractère
- `.` caractère quelconque (n'importe lequel)
- `\[car]` banalise le caractère spécial
### exprimer la répétition d'un caractère
- `[car]*` le caractère est *répété 0, 1 ou plusieurs fois*
- `[car]?` le caractère est *répété 0 ou 1 fois*
- `[car]+` le caractère est *répété 1 ou plusieurs fois*
## choix dans une liste
- `[liste car]` un seul caractère parmi ceux présents dans la liste
- `[^liste car]` un seul caractère qui n'est pas dans la liste de caractères
- `[car1 - car2]` un caractère pris dans l'intervalle entre `car1` et `car 2` (chiffres, minuscules, ou majuscules)
## expressions régulières étendues
- `([exp reg])?` la chaine correspondant sera répétée 0 ou 1 fois
- `([exp reg])+` la chaine correspondant sera répétée au moins 1 fois
- `([exp reg]) {[a], [b]}` la chaine correspondant sera répétée entre *a* et *b* fois
- `([exp reg1]) | ([exp reg2])` la chaine correspondant à *exp reg1* ou à *exp reg2*

La commande *grep* permet d'afficher toutes les lignes d'un fichier qui contiennent un motif recherché grep '[exp reg]' [fic] ; et quelques options : 
- `-v` afficher toutes les lignes qui ne contiennent pas le motif recherché
- `- E` 
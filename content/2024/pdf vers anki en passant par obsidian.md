---
date: 2024-10-17
---
- ouvrir le pdf sur word, activer la modification, enregistrer sous dans le dossier où on pourra envoyer de obsidian à anki
- installer pandoc
- installer obsidian , puis dans ses paramètres installer le module export_to_anki
	- installer anki
- executer : `pandoc -t markdown --extract-media='.' entrée.docx -o output.md`
- faire un modèle sur obsidian avec comme contenu : 
END
START
Basique

- et un autre avec :
Verso: 

- ouvrir paramètre plugin templater entrer les deux modèles précédents
- les associer à un raccourci clavier
- utiliser les raccourcis pour indiquer recto et verso des cartes
	- enlever `END` de la première carte
- utiliser `TARGET DECK` dans propriété pour indiquer le paquet (le séparateur c'est ::)
- exporter vers anki avec le bouton sur la barre latérale sur obsidian respectif

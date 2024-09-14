
```dataview
table échéance, priorité, énergie
from "" or "les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici/roadmap" and -"les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici/Modèles (inclus)" and -"écrivez le nom de votre coffre ici (version sans google agenda)"
where contains(tags, "projet") 
sort choice(date(échéance) != null, date(échéance), choice(priorité != null, priorité, choice(énergie != null, énergie, 4)))
```
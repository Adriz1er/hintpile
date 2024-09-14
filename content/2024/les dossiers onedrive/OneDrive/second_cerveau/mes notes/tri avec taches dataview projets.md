---
aspiration: 
tag:
  - concept
cards-deck:
---

```dataview 
table échéance ,priorité, énergie, due, file.tasks.due as tâche
from "" or "les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici/roadmap" and -"les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici/Modèles (inclus)" and -"écrivez le nom de votre coffre ici (version sans google agenda)" 
where contains(tag, "projet") 
sort choice(date(échéance) != null, date(échéance), choice(date(due) != null, due, choice(date(file.tasks.due) != null, date(file.tasks.due), choice(priorité != null, priorité, choice(priority != null, priority, choice(file.tasks.priority != null, file.tasks.priority, choice(énergie != null, énergie, 4)))))))
```
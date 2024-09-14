---
aspiration: []
---
```dataview 
table file.tasks.text as " "
flatten file.tasks as T
WHERE T.start = date(today)
```
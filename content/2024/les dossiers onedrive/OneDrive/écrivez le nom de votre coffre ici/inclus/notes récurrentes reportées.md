```button
name Revoir les projets récurrents
type command
action Repeat: Review due notes
```
^button-y45u
```dataview
table date(due_at) as revoir_le , repeat as se_répète_tout_les
from "" and -"roadmap"
where due_at != null
sort due_at
```
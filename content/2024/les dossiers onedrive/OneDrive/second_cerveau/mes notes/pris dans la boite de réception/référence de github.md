---
date: 2024-08-19
---
 
```tasks
(is blocking) OR (is blocked)
group by function \
    const combinedIds = Array.from(task.dependsOn); \
    if (task.id !== '') combinedIds.push(task.id); \
    return combinedIds;
```
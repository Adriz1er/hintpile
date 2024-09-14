 
```tasks
(is blocking) OR (is blocked)
group by function \
    const combinedIds = Array.from(task.dependsOn); \
    if (task.id !== '') combinedIds.push(task.id); \
    return combinedIds;
```

___
```tasks
(is blocking) OR (is blocked)
group by function \
const combinedIds = Array.from(task.dependsOn); \
const dependentTaskIds = combinedIds.reduce((acc, id) => [...acc, id], []); \
return dependentTaskIds;
```
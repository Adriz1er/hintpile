 
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
	const groupedTasks = {}; \
	const dependsOn = Array.from(task.dependsOn); \
	if (dependsOn.length === 0) { \
		if (!groupedTasks["Tâches non bloquées"]) { \
			groupedTasks["Tâches non bloquées"] = []; \
		} \
		groupedTasks["Tâches non bloquées"].push(task.id); \
		return; \
	} \
	dependsOn.forEach((blockingTaskId) => { \
		if (!groupedTasks[blockingTaskId]) { \
			groupedTasks[blockingTaskId] = []; \
		} \
		groupedTasks[blockingTaskId].push(task.id); \
	}); \
	if (!groupedTasks[task.id]) { \
		groupedTasks[task.id] = []; \
	} \
	groupedTasks[task.id].push(task.id); \
}); \
return groupedTasks;
```
___
```tasks
(is blocking) OR (is blocked)
group by function \
const combinedIds = []; \
const filteredDependsOn = task.dependsOn.filter(id => task.id.includes(id)); \
filteredDependsOn.forEach(id => combinedIds.push(id)); \
if (!filteredDependsOn.includes(task.id)) combinedIds.push(task.id); \
return combinedIds;
```
___
```tasks
(is blocking) OR (is blocked)
group by function \
const dependsOnIds = Object.keys(task.dependsOn); \
const combinedIds = dependsOnIds.reduce((acc, curr) => { \
	acc.add(curr); \
	return acc; \
}, new Set()); \
if (task.id !== '') combinedIds.add(task.id); \
return Array.from(combinedIds);
```
___
```tasks
(is blocking) OR (is blocked)
group by function \
const combinedIds = task.dependsOn.reduce((acc, curr) => { \
	acc.add(curr); \
	return acc; \
	}, new Set()); \
if (task.id !== '') combinedIds.add(task.id); \
return Array.from(combinedIds);
```
___
```tasks
(is blocking) OR (is blocked)
group by function \
const combinedIds = new Set([...task.dependsOn, task.id]); \
return Array.from(combinedIds); \
```
___
```tasks
(is blocking) OR (is blocked)
group by function \
    const dependance = Array.from(task.dependsOn); \
    const taches = Array.from(task.id); \
    let groupe = []; \
    for (const tache of taches) if (dependance.includes(tache)) groupe.push(tache); \
    return tache;
```
___
```tasks
(is blocking) OR (is blocked)
filter by function task.file.folder.includes("/")
filter by function new Boolean(task.dependsOn)
```
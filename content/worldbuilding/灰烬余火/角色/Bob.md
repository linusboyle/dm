---
date: 2025-02-21
description: 
tags: 
- campaign/ash/NPC
---

# Bob

```dataview
Table without id file.link AS "§", item.text as "交互"
From #campaign/ash/session 
Flatten file.lists as item
where contains(item.text, this.file.name)
sort file.name DESC
```
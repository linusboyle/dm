---
date: <% tp.date.now("YYYY-MM-DD") %>
tags:
  - campaign/ash/hex
---

<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/worldbuilding/灰烬余火/地点/Hex/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>

```dataview
Table without id file.link AS "§", item.text as "交互"
From "worldbuilding" and #campaign/ash/session 
Flatten file.lists as item
where contains(item.text, this.file.name)
sort file.name DESC
```
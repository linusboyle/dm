---
date: <% tp.file.creation_date("YYYY-MM-DD")%>
tags: 
- campaign/karameikos/NPC
image:
active: true
---

<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/卡拉梅科斯/NPC/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>


## 数据
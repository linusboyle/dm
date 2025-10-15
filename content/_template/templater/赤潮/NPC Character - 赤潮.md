---
{"publish":true,"created":"<% tp.file.creation_date(\"YYYY-MM-DD\")%>","tags":["campaign/redtide/NPC"],"cssclasses":""}
---


<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/worldbuilding/赤潮/NPC/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>

| § | 交互 |
| - | -- |
`
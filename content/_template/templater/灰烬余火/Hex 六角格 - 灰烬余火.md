---
{"publish":true,"tags":["campaign/ash/hex"],"cssclasses":""}
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

| § | 交互 |
| - | -- |

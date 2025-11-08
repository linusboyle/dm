---
{"publish":true,"tags":["table"],"cssclasses":""}
---


<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/随机表/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>
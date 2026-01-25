---
date: <% tp.date.now("YYYY-MM-DD") %>
tags:
- campaign/karameikos/location
banner:
type:
---

<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/卡拉梅科斯/地点/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>

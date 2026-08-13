<%*
let title = tp.file.title;

if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Enter the New Title: ");
	await tp.file.rename(title);
}

tp.hooks.on_all_templates_executed(async () => {
  const file = tp.file.find_tfile(tp.file.path(true));
  await tp.app.fileManager.processFrontMatter(file, (frontmatter) => {
    frontmatter["title"] = title;
    frontmatter["date"] = frontmatter["date"] || tp.file.creation_date("YYYY-MM-DD");
    frontmatter["aliases"] = frontmatter["aliases"] || [];
    frontmatter["tags"] = frontmatter["tags"] || [];
  });
});
_%>



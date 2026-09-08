
## General Guidelines

1. Use Obsidian CLI to determine currently opened file, if needed.
2. It is very possible that I modify notes. Always read content of a note, instead of relying on cached text in conversation history.

## Converting a source to Rollable Random Table

1. Locate a markdown file that matches the table theme. Otherwise, create one. 
	- For an existing markdown file that only contains random table(s), add the 'table' tag.
2. Convert the table. Do not add or modify anything, just keep the entries as is.
	- Exception: dice formula in an entry should be wrapped by `dice: <formula>` for the plugin to recognize it.

Put the table at the end, and add an inline dice roll.  Example:

```
`dice: [[filename^table]]`

| dice: 1d20 | Table Name                                                                                                                                                                                         |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1-4         | Entry 1                                                                                                                                      |
| 5-10       | Entry 2                                                                                                                              | 
| 11-20      | Entry 3                                                                                                                                      |
^table
```

If there is already table(s) in the same file, change the block-id ('table') to avoid collision.
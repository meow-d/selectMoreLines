# Select more lines

Inspired by the `Expand Line Selection` (`ctrl + l` by default) of VSCode. It functions similarly to SelectLine, but if there's already a selection, the cursor select the next line. There's no default binding, so you'll have to bind it yourself. For example:

```json
{
    "Ctrl-l": "lua:selectMoreLines.selectMoreLines"
}
```

Note that I made this for personal use and I don't know what I'm doing.

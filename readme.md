# VS Code Organize Imports On Save

https://github.com/microsoft/vscode/issues/46678

This is not configurable using the UI editor, use `settings.json`:

```json
{
    …,
    "editor.codeActionsOnSave": {
        "source.organizeImports": true
    }
}
```

Might as well enable `source.fixAll`:

```json
{
    …,
    "editor.codeActionsOnSave": {
        "source.fixAll": true,
        "source.organizeImports": true
    }
}
```

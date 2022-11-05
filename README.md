# vscode-terminal-switch

To open VSCode keybinds: ctrl + shit + p 'Preferences: Open Keyboard Shortcuts', then selected 'Open Keyboard Shortcuts JSON' in the top right hand corner, then paste in the below:

```JSON
[
    {
        "key":     "ctrl+oem_8",
        "command": "workbench.action.terminal.focus"
    },
    {
        "key":     "ctrl+oem_8",
        "command": "workbench.action.focusActiveEditorGroup",
        "when":    "terminalFocus"
    }
]
```

This will allow you to use ctrl + ` to switch between primary window and terminal

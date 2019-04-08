# VSCode-Settings


## Settings

```
{
    "workbench.activityBar.visible": true,
    "workbench.statusBar.visible": true,
    "editor.fontSize": 12,
    "terminal.integrated.fontSize": 12,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.wordWrap": "on",
    "workbench.editor.enablePreview": true,
    "workbench.startupEditor": "none",
    "window.openFoldersInNewWindow": "on",
    "editor.formatOnSave": false,
    "terminal.integrated.shell.windows": "C:\\windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
    "[javascript]": {
        "editor.formatOnSave": true,
        "editor.formatOnPaste": true
    },
    "[typescript]": {
        "editor.formatOnSave": true,
        "editor.formatOnPaste": true
    },
    "workbench.colorCustomizations": {
        "statusBar.background" : "#1A1A1A",
        "statusBar.noFolderBackground" : "#212121",
        "statusBar.debuggingBackground": "#263238"
    },
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Predawn",
    "diffEditor.ignoreTrimWhitespace": false,
    "breadcrumbs.enabled": true
}
```

## Key Bindings
```
// Place your key bindings in this file to override the defaults
[
    {
        "key": "ctrl+shift+d",
        "command": "editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+down",
        "command": "-editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    }
]
```

## Posh Git for Powershell

Surcouche GIT pour powershell : https://github.com/dahlbyk/posh-git

![Posh Git](/posh-git.png)




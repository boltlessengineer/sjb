# sjb
싸지방 개발 환경 구축용

keybindings.json
```json
[
    {
        "key": "ctrl+j",
        "command": "-workbench.action.togglePanel"
    },
    {
        "key": "ctrl+p",
        "command": "-workbench.action.quickOpen"
    },
    {
        "key": "ctrl+p",
        "command": "-workbench.action.quickOpenNavigateNextInFilePicker"
    },
    {
        "key": "ctrl+v",
        "command": "-workbench.action.terminal.paste"
    },
    {
        "key": "ctrl+alt+v",
        "command": "workbench.action.terminal.paste"
    },
    {
        "key": "ctrl+v",
        "command": "-workbench.action.terminal.sendSequence"
    },
    {
        "key": "ctrl+n",
        "command": "-workbench.action.files.newUntitledFile"
    }
]
```

settings.json
```json
{
    "window.menuBarVisibility": "toggle",
    "window.commandCenter": false,
    "workbench.statusBar.visible": false,
    "workbench.layoutControl.type": "menu",
    "workbench.layoutControl.enabled": false,
    "workbench.activityBar.visible": false,
    "terminal.integrated.allowChords": false
}
```
hhkb.ahk
```
Capslock::Ctrl
```

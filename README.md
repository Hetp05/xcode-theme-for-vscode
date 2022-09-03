# The Xcode like theme for VS Code

Make your vs code cleaner and more beautiful.

![first screenshot](assets/Screenshot-1.png)

## File Icons

![File Icon preview](assets/Screenshot-4.png)

## Folder Icons

![folder Icon preview](assets/Screenshot-2.png)

## Inspiration

* [SF Symbols Icon Theme](https://marketplace.visualstudio.com/items?itemName=j-f1.sf-symbols)
* [macOS Modern Theme](https://marketplace.visualstudio.com/items?itemName=davidbwaters.macos-modern-theme)

## Extra Tweaks

Copy & paste this into `setting.json`.

```json
{
    "window.title": "${dirty}${activeEditorShort}",
    "breadcrumbs.enabled": true,
    "files.autoSave": "afterDelay",
    "editor.autoClosingBrackets": "always",
    "editor.minimap.enabled": true,

    // Install "SF Mono" 
    // https://developers.apple.com/fonts/
    "editor.fontFamily": "SF Mono",
}
```

and extra extensions for more Xcode a like feeling.

[psioniq File Header](https://marketplace.visualstudio.com/items?itemName=psioniq.psi-header)

![Header extension preview]

Also, copy & paste this into `setting.json`.

```json
{
    // Insatll "psioniq File Header" for File headers
    // Just replace information like "Your Name".
    "psi-header.config": {
        "forceToTop": true,
        "spacesBetweenYears": false,
        "blankLinesAfter": 1,
        "author": "Your name",
        "authorEmail": " example@icloud.com",
        "creationDateZero": "asIs",
        "license": "license.txt"
    },
    "psi-header.lang-config": [
        {
            "language": "Swift",
            "begin": "// ",
            "prefix": "// ",
            "end": "// ",
            "modDateFormat": "dd/MM/yyyy",
        }
    ],
    "psi-header.templates": [
        {
            "language": "Swift",
            "template": [
                "<<Filename>>",
                "<<Projectname>>",
                "     ",
                "Create by <<author>> on dd/MM/yyyy.",
                "Copyright (c) <<year>> <<author>>. All rights reserved."
            ],
        },
    ]
}
```

Also, copy & paste this into `setting.json`.

[Vibrancy](https://marketplace.visualstudio.com/items?itemName=eyhn.vscode-vibrancy)

![vibrancy extension preview](https://github.com/illixion/vscode-vibrancy-continued/blob/master/theme-noir-et-blanc.jpg?raw=true)

```json
{
    // Install "Vibrancy" for tranclusent Side Bar
    "vscode_vibrancy.theme": "Dark (Only Subbar)",
}
```

## And

* [Credits](credits.md)
* [Change Log](CHANGELOG.md)

---

## Change Log

## 1.0.0

* Finally, the first release is here + added some file icon

![Icons preview](assets/Screenshot-5.png)

### 0.6.2/ 0.6.3

* updated readme and changelog

**Enjoy Kinder Joy!** #not_sponsored

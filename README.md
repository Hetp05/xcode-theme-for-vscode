# Xcode like theme for VS Code

Make your VS Code cleaner and more beautiful.

![first screenshot](assets/Screenshot-6.png)

## File Icons

![File Icon preview](assets/Screenshot-8.png)

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

    "editor.fontFamily": "SF Mono",
}
```

And extra extensions for more Xcode a like feeling.

[psioniq File Header](https://marketplace.visualstudio.com/items?itemName=psioniq.psi-header)

![Header extension preview]

Also, copy & paste this into `setting.json`.

```json
{
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
    "vscode_vibrancy.theme": "Dark (Only Subbar)",
}
```

---

## And

* [Credits](credits.md)
* [Change Log](CHANGELOG.md)
* [Legal Disclaimer](Legel_Disclaimer.txt)

---

* [Marketplace (download)](https://github.com/Hetp05/xcode-theme-for-vscode/releases/download/extension/xcode-theme-for-vscode-1.0.2.vsix)
* [Repository (Github)](https://github.com/Hetp05/xcode-theme-for-vscode.git)
* [Het (creator)](https://github.com/Hetp05)

---

## Change Log

### `1.1.2`

* Updated Xcode like blue and terminal color in  `color-theme`

* Added some extra links to `README`

* Renamed `Legal_Disclaimer.txt` to `Legal-Disclaimer.txt`

* Added icon for folder named "Products" to `file-icons-theme.json`

```txt
themes
    ┣ color-theme.json
    ┗  file-icons-theme.json
README.md
Legal-Disclaimer.txt
```

### `1.1.1`

* Updated Xcode like blue color `color-theme`

* Added some extra links to `README`

```txt
themes
    ┗ color-theme.json
README.md
```

---

**Enjoy Kinder Joy!** #not_sponsored

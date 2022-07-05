# VSCode Setup
<img width="1200" alt="Screenshot 2022-07-05 at 15 39 42" src="https://user-images.githubusercontent.com/35395520/177329570-1fb181b6-d0d5-4073-b5ee-1be62c6ef89b.png">
<p align="center">My personal Visual Studio Code setup for Flutter development.</p>
<br>
<br>

## Extensions

Theme
- [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl) with [JetBrains Mono](https://www.jetbrains.com/lp/mono/) as a font
- [Studio Icons](https://marketplace.visualstudio.com/items?itemName=jtlowe.vscode-icon-theme)

Common
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

Flutter
- [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)
- [Dark](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)
- [bloc](https://marketplace.visualstudio.com/items?itemName=FelixAngelov.bloc)
- [Flutter Tree](https://marketplace.visualstudio.com/items?itemName=marcelovelasquez.flutter-tree)
- [Flutter Widget Snippets](https://marketplace.visualstudio.com/items?itemName=alexisvt.flutter-snippets)
- [Flutter Docs Search](https://marketplace.visualstudio.com/items?itemName=weakvar.flutter-docs-search)

## Custom Settings

```json
{
  "editor.fontFamily": "JetBrains Mono, SF Mono, monospace",
  "editor.fontSize": 13,
  "editor.fontWeight": 500,
  "editor.fontLigatures": true,
  
  "workbench.colorTheme": "Night Owl",
  "workbench.iconTheme": "vscode-icon-theme",
  "workbench.colorCustomizations": {
    "[Night Owl]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "editorGroup.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8BADC1"
    },
    "[Night Owl (No Italics)]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "editorGroup.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8BADC1"
    },
    "errorLens.infoForeground": "#3894ff",
    "errorLens.infoMessageBackground": "#3894ff10",
    "errorLens.warningForeground": "#daaa01",
    "errorLens.warningMessageBackground": "#daaa0115",
    "errorLens.errorForeground": "#e93e45",
    "errorLens.errorMessageBackground": "#e93e4525",
  },
  
  "dart.flutterSdkPath": ".fvm/flutter_sdk",
  "search.exclude": {
    "**/.fvm": true
  },
  "files.watcherExclude": {
    "**/.fvm": true
  },
  
	"dart.lineLength": 120,
  "dart.openDevTools": "flutter",
  "dart.showInspectorNotificationsForWidgetErrors": false,
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": false,
    "editor.semanticHighlighting.enabled": false
  },
  
  "errorLens.fontWeight": "600",
  "errorLens.fontSize": "10px",
  "errorLens.fontStyleItalic": true,
  "errorLens.margin": "8px",
  "errorLens.padding": "3.5px 8px",
  "errorLens.borderRadius": "12px",
  "errorLens.exclude": ["TODO", "FIXME"],
  "errorLens.messageTemplate": "$severity: $message",
  "errorLens.messageBackgroundMode": "message",
  
  "editor.minimap.enabled": true,
  "editor.minimap.maxColumn": 160,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.scale": 1,
  "editor.minimap.showSlider": "always",
  
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "files.trimTrailingWhitespace": true,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "editor.unicodeHighlight.nonBasicASCII": false,
  "editor.accessibilitySupport": "off",
  "editor.inlineSuggest.enabled": true,
}
```

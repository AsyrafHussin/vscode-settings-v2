# My Visual Studio Code Settings

I personally use this settings for my VS Code

## My Settings

```js
{
  "editor.autoIndent": "advanced",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.cursorBlinking": "solid",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.detectIndentation": false,
  "editor.fontFamily": "Dank Mono, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 16,
  "editor.fontWeight": "400",
  "editor.formatOnPaste": false,
  "editor.formatOnSave": true,
  "editor.formatOnType": false,
  "editor.glyphMargin": true,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 25,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.renderWhitespace": "all",
  "editor.scrollBeyondLastLine": false,
  "editor.selectionHighlight": false,
  "editor.snippetSuggestions": "top",
  "editor.suggestSelection": "first",
  "editor.tokenColorCustomizations": {
    "[One Dark Flatland Monokai]": {
      "textMateRules": [
        {
          "scope": "entity.name.type",
          "settings": {
            "fontStyle": ""
          }
        },
        {
          "scope": [
            "support.class",
            "support.type",
            "variable.language",
            "variable.parameter"
          ],
          "settings": {
            "fontStyle": "italic"
          }
        }
      ]
    }
  },
  "material-icon-theme.folders.associations": {
    "bloc": "controller",
    "global_state": "global",
    "state": "controller",
    "ui": "layout",
    "widgets": "components"
  },
  // "workbench.statusBar.visible": false,
  "explorer.openEditors.visible": 0,
  "intelephense.format.enable": true,
  "intelephense.telemetry.enabled": false,
  "intelephense.completion.fullyQualifyGlobalConstantsAndFunctions": true,
  "intelephense.completion.insertUseDeclaration": true,
  "intelephense.completion.triggerParameterHints": true,
  "intelephense.diagnostics.undefinedMethods": false,
  "intelephense.diagnostics.undefinedFunctions": false,
  "intelephense.diagnostics.undefinedTypes": false,
  "workbench.colorTheme": "One Dark Flatland Monokai",
  "workbench.iconTheme": "material-icon-theme",
  "php-cs-fixer.onsave": true,
  "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "blade": "html"
  },
  "files.exclude": {
    "**/node_modules/**": true
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.associations": {
    "*.wox": "html"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.startupEditor": "newUntitledFile",
  "vetur.ignoreProjectWarning": true,
  "prettier.prettierPath": "/usr/local/lib/node_modules/prettier",
  "[php]": {
    "editor.defaultFormatter": "junstyle.php-cs-fixer"
  },
  "php-cs-fixer.lastDownload": 1625688574678
}
```

## Install Extensions

Using bash (Linux, OSX and WSL)

```bash
cat extensions.txt | xargs -L1 code --install-extension
```

Windows with PowerShell

```bash
cat extensions.txt |% { code --install-extension $_}
```

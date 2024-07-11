<!-- Autor: Daniel Benjamin Perez Morales -->
<!-- GitHub: https://github.com/DanielPerezMoralesDev13 -->
<!-- Correo electrónico: danielperezdev@proton.me -->
# ***Extensiónes***

<!-- **En react usar esta opcion para emmet**
item javascript
value javascriptreact -->

- **emmet.includeLanguages**

```json
"emmet.includeLanguages": {}
```

<!-- id extension: SirTori.indenticator -->

---

<!-- **poner @ en ctrl + , **-->

---

## ***Configuaration***

- **editor.tabSize**

```json
"editor.tabSize": 4
```

---

<!-- **valor recomendado 80 **-->

- **editor.rulers**

```json
"editor.rulers": [
  80
]
```

---

- **editor.guides.indentation**

```json
"editor.guides.indentation": true
```

---

- **editor.wordWrap**

```json
"editor.wordWrap": "on"
```

---

- **editor.cursorBlinking**

```json
"editor.cursorBlinking": "expand"
```

---

- **terminal.integrated.cursorBlinking**

```json
"terminal.integrated.cursorBlinking": true
```

---

- **Editar groups**

```plaintext
View -> Editor Layout
```

---

<!-- **Para visualizar varios ficheros ala vez **-->

- **workbench.editor.enablePreview**

```json
"workbench.editor.enablePreview": true
```

```plaintext
Ctrl + z || doble click
```

---

<!-- **valor por default WelcomePage **-->

- **workbench.startupEditor**

```json
"workbench.startupEditor": "newUntitledFile"
```

---

<!-- **Selecionar lenguage **-->

**Title:** *Change Language Mode*
**ID:** *workbench.action.editor.changeLanguageMode*

```json
{
  "key": "ctrl+k m",
  "command": "workbench.action.editor.changeLanguageMode",
  "when": "!notebookEditorFocused"
}
```

---

- **files.defaultLanguage**

```json
"files.defaultLanguage": "python"
```

<!-- **al hacer doble click despues en un espacio de donde sale arriba los ficheros**
o ctrl + n -->

---

<!-- **Te creara un directorio con un fichero Extensións.json**

/home/d4nitrix13/Desktop/configuracionVscode/.vscode/Extensións.json

Debes colocar el id de la Extensión y ponerlo entre comillas, si quieres agregar mas ponle seguido de una coma -->

**Title:** *Configure Recommended Extensións (Workspace Folder)*
**ID:** *workbench.Extensións.action.configureWorkspaceFolderRecommendedExtensións*

```json
{
  "key": "",
  "command": "workbench.Extensións.action.configureWorkspaceFolderRecommendedExtensións"
}
```

---

<!-- **New Global Snippets File**
selecciona esta opcion para crear un nuevo snippet. Luego tendras que ponerle un nombre al snippet y te generara unos comentarios con la sintaxis que debes usar -->

**Title**: Snippets: Configure User Snippets
**ID**: workbench.action.openSnippets

```json
{
  "key": "",
  "command": "workbench.action.openSnippets"
}
```

---

**Title:** *Emmet: Wrap with Abbreviation*
**ID:** *editor.emmet.action.wrapWithAbbreviation*

```json
{
  "key": "",
  "command": "editor.emmet.action.wrapWithAbbreviation"
}
```

---

**Title:** *Emmet: Go to Matching Pair*
**ID:** *editor.emmet.action.matchTag*

```json
{
  "key": "",
  "command": "editor.emmet.action.matchTag"
}
```

---

**Title:** *Emmet: Balance (outward)*
**ID:** *editor.emmet.action.balanceOut*

```json
{
  "key": "",
  "command": "editor.emmet.action.balanceOut"
}
```

---

**Title:** *Emmet: Balance (inward)*
**ID:** *editor.emmet.action.balanceIn*

```json
{
  "key": "",
  "command": "editor.emmet.action.balanceIn"
}
```

---

- **html.autoClosingTags**

```json
"html.autoClosingTags": true
```

---

- **javascript.autoClosingTags**

```json
"javascript.autoClosingTags": true
```

---

- **typescript.autoClosingTags**

```json
"typescript.autoClosingTags": true
```

---

<!-- **default: false **-->

- **editor.linkedEditing**

```json
"editor.linkedEditing": true
```

---

<!-- **default: auto **-->

- **html.format.wrapAttributes**

```json
"html.format.wrapAttributes": "force"
```

---

<!-- **Link**
https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css -->

- **css.styleSheets**

```json
"css.styleSheets": [
  "https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css"
]
```

---

<!-- **para que te detecte automaticamen el path del fichero solamente funcion con**
al mover el fichero con el mouse -->

editor.codeActionsOnSave

```json
"editor.codeActionsOnSave": {
  "source.fixAll": true,
  "source.organizeImports": true
}
```

---

- **headwind.runOnSave**

```json
"headwind.runOnSave": true
```

---

- **markdown-preview-github-styles.colorTheme**

```json
"markdown-preview-github-styles.colorTheme": "dark"
```

---

- **markdown-preview-github-styles.lightTheme**

```json
"markdown-preview-github-styles.lightTheme": "dark"
```

---

- **markdown-preview-github-styles.darkTheme**

```json
"markdown-preview-github-styles.darkTheme": "dark"
```

---

- **editor.cursorSmoothCaretAnimation**

```json
"editor.cursorSmoothCaretAnimation": "on"
```

---

- **terminal.integrated.fontSize**

```json
"terminal.integrated.fontSize": 18
```

---

- **terminal.integrated.mouseWheelZoom**

```json
"terminal.integrated.mouseWheelZoom": true
```

---

- **terminal.integrated.lineHeight**

```json
"terminal.integrated.lineHeight": 1.5
```

---

- **terminal.external.windowsExec**

```json
"terminal.external.windowsExec": "C:\\Windows\\System32\\cmd.exe"
```

---

- **git.defaultCloneDirectory**

```json
"git.defaultCloneDirectory": null
```

```json
"git.defaultCloneDirectory": "/home/d4nitrix13/Desktop/configuracionVscode"
```

---

- **git.autofetch**

```plaintext
"git.autofetch": false // true. default false
```

---

- **files.autoSave**

```json
"files.autoSave": "afterDelay"
```

---

- **files.autoSaveDelay**

```json
"files.autoSaveDelay": 1000
```

---

- **editor.defaultFormatter**

```json
"editor.defaultFormatter": "esbenp.prettier-vscode"
```

---

- **editor.formatOnSave**

```json
"editor.formatOnSave": true
```

---

- **notebook.formatOnSave.enabled**

```json
"notebook.formatOnSave.enabled": false
```

---

**Title:** *Preferencias: Abrir métodos abreviados de teclado*
**ID:** *workbench.action.openGlobalKeybindings*

```json
{
  "key": "ctrl+k ctrl+s",
  "command": "workbench.action.openGlobalKeybindings"
}
```

---

- **editor.cursorSmoothCaretAnimation**

```json
"editor.cursorSmoothCaretAnimation": "on"
```

---

- *View: Toggle Status Bar Visibility*

```json
{
  "key": "",
  "command": "workbench.action.toggleStatusbarVisibility"
}
```

- *Snippets: Insert Snippet*

```json
{
  "key": "",
  "command": "editor.action.insertSnippet"
}
```

---

- *View: Toggle Breadcrumbs*

```json
{
  "key": "",
  "command": "breadcrumbs.toggle"
}
```

---

- *editor.bracketPairColorization.independentColorPoolPerBracketType*

```json
"editor.bracketPairColorization.independentColorPoolPerBracketType": true
```

---

- *editor.guides.bracketPairs*

```json
"editor.guides.bracketPairs": true
```

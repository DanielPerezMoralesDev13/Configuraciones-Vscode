<!-- Autor: Daniel Benjamin Perez Morales -->
<!-- GitHub: https://github.com/DanielPerezMoralesDev13 -->
<!-- Correo electrónico: danielperezdev@proton.me -->

# ***Configuraciones vscode***

```bash
{
  "workbench.productIconTheme": "fluent-icons",
  // Tema de iconos del producto. Valor por defecto: "file-icons". 
  // Descripción: Establece el tema de iconos del producto como "fluent-icons".
  "workbench.iconTheme": "symbols",
  // Tema de iconos. Valor por defecto: "vs-seti". 
  // Descripción: Define el tema de iconos utilizado en la interfaz de usuario.
  "symbols.hidesExplorerArrows": false,
  // Oculta las flechas del explorador. Valor por defecto: false. 
  // Descripción: Indica si se deben ocultar las flechas de navegación en el explorador de ficheros.
  "editor.fontFamily": "'Cascadia Code NF', 'FiraCode Nerd Font Mono SemBd', 'UbuntuMono Nerd Font Mono', 'Droid Sans Mono', 'monospace'",
  // Familia de fuentes del editor de código. Valor por defecto: "Menlo, Monaco, 'Courier New', monospace". 
  // Descripción: Establece la familia de fuentes utilizada en el editor de código.
  "editor.fontLigatures": true,
  // Ligaduras tipográficas del editor de código. Valor por defecto: false. 
  // Descripción: Habilita o deshabilita las ligaduras tipográficas en el editor de código.
  "editor.fontSize": 18,
  // Tamaño de fuente del editor de código. Valor por defecto: 14. 
  // Descripción: Establece el tamaño de fuente utilizado en el editor de código.
  "editor.lineHeight": 38,
  // Altura de línea del editor de código. Valor por defecto: 20. 
  // Descripción: Establece la altura de línea utilizada en el editor de código.
  "editor.guides.indentation": true,
  // Muestra guías de indentación. Valor por defecto: true. 
  // Descripción: Indica si se deben mostrar las guías de indentación en el editor de código.
  "editor.scrollbar.horizontal": "auto",
  // Visibilidad de la barra de desplazamiento horizontal. Valor por defecto: "auto". 
  // Descripción: Controla la visibilidad de la barra de desplazamiento horizontal en el editor de código.
  "editor.mouseWheelZoom": true,
  // Habilita el zoom con la rueda del ratón en el editor de código. Valor por defecto: false. 
  // Descripción: Permite habilitar o deshabilitar el zoom utilizando la rueda del ratón en el editor de código.
  "editor.wordWrap": "on",
  // Ajuste de línea automático en el editor de código. Valor por defecto: "off". 
  // Descripción: Controla si el editor de código debe ajustar automáticamente las líneas largas al ancho del editor.
  "editor.cursorBlinking": "expand",
  // Tipo de parpadeo del cursor en el editor de código. Valor por defecto: "blink". 
  // Descripción: Configura el tipo de parpadeo del cursor en el editor de código.
  "terminal.integrated.cursorBlinking": true,
  // Parpadeo del cursor en el terminal integrado. Valor por defecto: true. 
  // Descripción: Controla si el cursor en el terminal integrado debe parpadear.
  "advancedNewFile.exclude": {},
  // Exclusión de ficheros o carpetas al crear nuevos ficheros. Valor por defecto: {}. 
  // Descripción: Configura qué ficheros o carpetas se deben excluir al crear nuevos ficheros utilizando la extensión Advanced New File.
  "workbench.startupEditor": "newUntitledFile",
  // Tipo de editor que se abre al iniciar el entorno de trabajo. Valor por defecto: "welcomePageInEmptyWorkbench". 
  // Descripción: Establece el tipo de editor que se abrirá al iniciar el entorno de trabajo.
  "files.defaultLanguage": "python",
  // Lenguaje predeterminado para los nuevos ficheros. Valor por defecto: "". 
  // Descripción: Establece el lenguaje predeterminado que se utilizará para los nuevos ficheros creados.
  "editor.linkedEditing": true,
  // Edición vinculada en el editor de código. Valor por defecto: false. 
  // Descripción: Habilita la edición vinculada, que permite editar simultáneamente ocurrencias de la misma variable o símbolo.
  "html.format.wrapAttributes": "force",
  // Formateo de HTML para envolver los atributos forzadamente. Valor por defecto: "auto". 
  // Descripción: Configura cómo se deben envolver los atributos al formatear código HTML.
  "css.styleSheets": [
    "https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css"
  ],
  // Hojas de estilo CSS adicionales a utilizar. Valor por defecto: []. 
  // Descripción: Define las hojas de estilo CSS adicionales que se utilizarán en el entorno.
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.organizeImports": "explicit"
  },
  // Acciones que se deben realizar al guardar un fichero. Valor por defecto: {}. 
  // Descripción: Configura las acciones automáticas que se deben realizar al guardar un fichero.
  "markdown-preview-github-styles.lightTheme": "dark",
  // Tema claro para el estilo de vista previa de Markdown. Valor por defecto: "github-light". 
  // Descripción: Configura el tema claro que se utilizará en la vista previa de Markdown.
  "markdown-preview-github-styles.colorTheme": "dark",
  // Tema de color para el estilo de vista previa de Markdown. Valor por defecto: "github-dark". 
  // Descripción: Configura el tema de color que se utilizará en la vista previa de Markdown.
  "markdown-preview-enhanced.previewTheme": "github-dark.css",
  // Tema de vista previa para Markdown. Valor por defecto: "github.css". 
  // Descripción: Configura el tema que se utilizará en la vista previa de Markdown.
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  // Formateador predeterminado para ficheros JSON. Valor por defecto: "". 
  // Descripción: Configura el formateador predeterminado que se utilizará para ficheros con extensión .json.
  "files.exclude": {
    "**/.git": false,
    "**/.svn": false,
    "**/.hg": false,
    "**/CVS": false,
    "**/.DS_Store": false,
    "**/node_modules": false
  },
  // Exclusión de ficheros o carpetas del explorador de ficheros. Valor por defecto: {}. 
  // Descripción: Configura qué ficheros o carpetas se deben excluir de la vista del explorador de ficheros.
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[css]": {
    "editor.defaultFormatter": "vscode.css-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[markdown]": {
    "editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
  },
  "[php]": {
    // "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
  },
  "markdown-preview-enhanced.revealjsTheme": "moon.css",
  // Tema para la vista previa de Reveal.js en Markdown. Valor por defecto: "reveal.js/dist/reveal.css". 
  // Descripción: Configura el tema que se utilizará en la vista previa de Reveal.js en Markdown.
  "markdown-preview-enhanced.codeBlockTheme": "github-dark.css",
  // Tema para los bloques de código en la vista previa de Markdown. Valor por defecto: "default". 
  // Descripción: Configura el tema que se utilizará para resaltar bloques de código en la vista previa de Markdown.
  "editor.guides.bracketPairs": true,
  // Muestra pares de corchetes. Valor por defecto: false. 
  // Descripción: Indica si se deben mostrar pares de corchetes en el editor de código.
  "editor.language.colorizedBracketPairs": [],
  "editor.bracketPairColorization.enabled": true,
  "editor.autoClosingBrackets": "languageDefined",
  // Pares de corchetes con colores personalizados. Valor por defecto: []. 
  // Descripción: Configura los colores que se utilizarán para resaltar los pares de corchetes en el editor de código.
  "workbench.colorTheme": "One Dark Pro Darker",
  // Tema de color de la interfaz de usuario. Valor por defecto: "Default Dark+". 
  // Descripción: Establece el tema de color utilizado en la interfaz de usuario.
  "oneDarkPro.bold": true,
  // Texto en negrita en el tema One Dark Pro. Valor por defecto: false. 
  // Descripción: Habilita o deshabilita el texto en negrita en el tema One Dark Pro.
  "oneDarkPro.italic": true,
  // Texto en cursiva en el tema One Dark Pro. Valor por defecto: false. 
  // Descripción: Habilita o deshabilita el texto en cursiva en el tema One Dark Pro.
  "oneDarkPro.vivid": true,
  // Colores vibrantes en el tema One Dark Pro. Valor por defecto: false. 
  // Descripción: Habilita o deshabilita colores vibrantes en el tema One Dark Pro.
  "oneDarkPro.markdownStyle": true,
  // Estilo Markdown en el tema One Dark Pro. Valor por defecto: false. 
  // Descripción: Habilita o deshabilita estilos específicos de Markdown en el tema One Dark Pro.
  "workbench.editor.languageDetection": true,
  // Detección automática del lenguaje del fichero en el editor. Valor por defecto: true. 
  // Descripción: Controla si se debe detectar automáticamente el lenguaje del fichero abierto en el editor.
  "telemetry.telemetryLevel": "off",
  // Nivel de telemetría. Valor por defecto: "on". 
  // Descripción: Controla la cantidad de datos de telemetría que se envían a los servidores de Microsoft.
  // Configuración de la interfaz de usuario principal
  "diffEditor.renderIndicators": false,
  // Esta configuración desactiva los indicadores en el editor de diferencias.
  "editor.minimap.enabled": true,
  // Esta configuración desactiva o activa el minimapa en el editor de código. La minimapa muestra una vista de desplazamiento de todo el fichero.
  "editor.minimap.side": "left",
  // Esta configuración configura la posición del minimapa en el lado izquierdo del editor de código.
  "workbench.statusBar.visible": true,
  // Esta configuración oculta o desoculta la barra de estado en la parte inferior de la interfaz de usuario.
  "window.customTitleBarVisibility": "never",
  // Esta configuración configura la visibilidad de la barra de título personalizada. 
  // En este caso, se establece en "never", lo que significa que nunca se mostrará la barra de título personalizada.
  "workbench.sideBar.location": "right",
  // Esta configuración configura la ubicación de la barra lateral en el lado derecho de la interfaz de usuario.
  "breadcrumbs.enabled": false,
  // Esta configuración desactiva las migas de pan en la interfaz de usuario. Las migas de pan muestran la ruta del fichero actual.
  "editor.cursorSmoothCaretAnimation": "on",
  // Esta configuración activa la animación suave del cursor en el editor de código.
  "explorer.openEditors.visible": 10,
  // Esta configuración define el número máximo de editores abiertos visibles en el explorador como 10.
  // Configuración de las pestañas
  "workbench.editor.showIcons": true,
  // Esta configuración activa la visualización de iconos en las pestañas de los ficheros en la interfaz de usuario.
  "workbench.editor.tabActionCloseVisibility": true,
  // Esta configuración desactiva o activa la visibilidad del botón de cierre en las pestañas de los ficheros en la interfaz de usuario.
  "workbench.editor.showTabs": "multiple",
  // Esta configuración configura la visualización de las pestañas de ficheros como ninguna, multiple, single.
  // Configuración del margen
  "editor.lineNumbers": "on",
  // Esta configuración desactiva o activa la visualización de números de línea en el editor de código.
  "editor.glyphMargin": true,
  // Esta configuración desactiva el margen de glifos en el editor de código. Los glifos son los pequeños marcadores que aparecen en el margen.
  "editor.folding": true,
  // Esta configuración desactiva el plegado de código en el editor de código.
  "window.menuBarVisibility": "classic",
  // Esta configuración oculta la barra de menú en la parte superior de la interfaz de usuario.
  "workbench.activityBar.location": "default",
  // Esta configuración oculta la barra de actividad en la interfaz de usuario.
  "workbench.editor.editorActionsLocation": "hidden",
  // Esta configuración oculta las acciones del editor en la interfaz de usuario.
  "editor.scrollbar.vertical": "hidden",
  // Esta configuración oculta o desoculta la barra de desplazamiento vertical en el editor de código.
  // valor default: auto
  "editor.overviewRulerBorder": false,
  // Esta configuración desactiva el borde de la regla de vista general en el editor de código.
  "editor.hideCursorInOverviewRuler": true,
  // Esta configuración establece el tamaño de fuente del terminal integrado en 17.
  "terminal.integrated.mouseWheelZoom": true,
  // Esta configuración habilita el zoom mediante la rueda del ratón en el terminal integrado.
  "terminal.integrated.lineHeight": 1.5,
  // Esta configuración establece la altura de línea del terminal integrado en 1.5.
  "files.autoSave": "afterDelay",
  // Esta configuración configura el guardado automático de ficheros después de un retraso.
  "editor.defaultFormatter": "aaron-bond.better-comments",
  // Esta configuración establece el formateador predeterminado del editor de código como "aaron-bond.better-comments".
  "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
  // Esta configuración habilita el uso de un conjunto independiente de colores para cada tipo de paréntesis en el editor de código.
  "editor.formatOnSave": true,
  // Esta configuración activa el formateo automático al guardar el fichero en el editor de código.
  "editor.guides.highlightActiveIndentation": true,
  // Esta configuración desactiva el resaltado de la indentación activa en el editor de código.
  "editor.renderControlCharacters": false,
  "editor.guides.bracketPairsHorizontal": true,
  "[c]": {
    // "editor.defaultFormatter": "ms-vscode.cpptools"
  },
  "[lua]": {
    // "editor.defaultFormatter": "sumneko.lua"
  },
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.multiCursorLimit": 10000,
  "editor.multiCursorPaste": "spread",
  "[csharp]": {
    // "editor.defaultFormatter": "ms-dotnettools.csharp"
  },
  "terminal.integrated.enableMultiLinePasteWarning": "auto",
  "[java]": {
    // "editor.defaultFormatter": "redhat.java"
  },
  "security.workspace.trust.untrustedFiles": "open",
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorStyleInactive": "line",
  "terminal.integrated.cursorWidth": 2,
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[dockerfile]": {
    "editor.defaultFormatter": "ms-azuretools.vscode-docker"
  },
  "terminal.integrated.fontSize": 20,
  "terminal.integrated.stickyScroll.enabled": true,
  // Esta configuración desactiva la representación de caracteres de control en el editor de código.
}
```

# ospfranco's vscode settings

Do with this as you wish

```json
{
  "files.exclude": {
    "**/.DS_Store": true,
    "**/.happypack": true,
    "**/.idea": true,
    "**/.sonar": true,
    "**/.svn": true,
    "**/cdk.out": true,
    "**/dll": true,
    "**/ios/Pods": true,
    "**/node_modules": true,
    "**/tmp": true,
    "**/.webpack": true,
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true,
    "**/Pods": true
  },
  "files.watcherExclude": {
    "**/.git/objects/**": true,
    "**/node_modules/**": true,
    "**/tmp": true
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/.git": true,
    "**/.DS_Store": true,
    "**/tmp": true,
    "**/.sonar": true,
    "**/.happypack": true,
    "**/*.bundle": true,
    "**/*.map": true,
    "**/.webpack": true,
    "**/flow-typed": true,
    "**/docs": true,
    "**/vendor": true,
    "**/_site": true,
    "**/lib": true,
    "**/build": true,
    "**/yarn-error.log": true,
    "**/yarn.lock": true,
    "**/.next": true
  },
  "extensions.autoUpdate": true,
  "telemetry.telemetryLevel": "off",
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "editor.detectIndentation": true,
  "editor.tabSize": 2,
  "editor.acceptSuggestionOnCommitCharacter": false,
  "workbench.enableExperiments": false,
  "workbench.tips.enabled": false,
  "workbench.editor.closeOnFileDelete": true,
  "workbench.editor.enablePreview": false,
  "search.smartCase": true,
  "editor.fontFamily": "'Jetbrains Mono', Monaco, 'Courier New', monospace",
  "editor.tokenColorCustomizations": {
    "comments": "#fa755a"
    // "comments": "#ddfa5a",
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.formatOnSave": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.enableBell": true,
  "terminal.integrated.scrollback": 30000,
  "debug.javascript.autoAttachFilter": "disabled",
  "workbench.activityBar.visible": false,
  "editor.fontLigatures": true,
  "editor.minimap.enabled": false,
  "css.validate": false,
  "tailwindCSS.colorDecorators": true,
  "workbench.settings.editor": "json",
  "editor.accessibilitySupport": "off",
  "security.workspace.trust.untrustedFiles": "open",
  "workbench.editor.untitled.hint": "hidden",
  "workbench.startupEditor": "none",
  "window.autoDetectColorScheme": true,
  "workbench.preferredDarkColorTheme": "GitHub Dark Default",
  "workbench.preferredLightColorTheme": "GitHub Light Default",
  "jest.jestCommandLine": "yarn test",
  "workbench.colorCustomizations": {
    "terminal.ansiWhite": "#FFF"
  },
  "search.useIgnoreFiles": false,
  "flow.fileExtensions": [".js", ".jsx"],
  "flow.lazyMode": "fs",
  "flow.useLSP": true,
  "flow.runOnEdit": false,
  "flow.useBundledFlow": false,
  "git.confirmSync": false,
  "editor.bracketPairColorization.enabled": true,
  "workbench.colorTheme": "GitHub Light Default",
  "cmake.configureOnOpen": false,
  "editor.semanticHighlighting.enabled": true,
  "editor.guides.bracketPairs": true,
  "javascript.inlayHints.parameterNames.enabled": "all",
  "typescript.inlayHints.parameterNames.enabled": "all"
}
```

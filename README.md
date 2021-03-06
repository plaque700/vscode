## Configurações do Vscode

**Download Fire Code (Font):**<br>
https://github.com/tonsky/FiraCode

**Folder/File:**<br>
cp .config/Code/User/settings.json settings.bkp<br>
vim .config/Code/User/settings.json

## Plugins instalados:

- Beautify
- Color Highlight
- DotENV
- Dracula Official
- EditorConfig for VS Code
- ESLint
- Laravel Blade Snippets
- Live Server
- Markdown All in One
- Material Icon Theme

## Conteudo do settings.json:

```
{
  "terminal.integrated.fontSize": 14,

  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",

  "editor.tabSize": 2,
  "editor.fontSize": 18,
  "editor.lineHeight": 26,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,

  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "node_modules": true
  },

  "explorer.compactFolders": false,
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.labelFormat": "short",
  "extensions.ignoreRecommendations": true,

  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "never",

  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  
  "editor.rulers": [80, 120],
  
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },

  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json"
  },

  "window.zoomLevel": 0,

  "emmet.syntaxProfiles": { "javascript": "jsx" },
  "emmet.includeLanguages": { "javascript": "javascriptreact" },

  
  "gitlens.codeLens.recentChange.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.codeLens.enabled": false,

  "git.enableSmartCommit": true,
  "terminal.integrated.shell.osx": "/bin/zsh",
  "liveshare.featureSet": "insiders",

  "typescript.tsserver.log": "verbose",
  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,
  "liveServer.settings.donotShowInfoMsg": true,
  // "material-icon-theme.activeIconPack": "nest",
  "screencastMode.onlyKeyboardShortcuts": true,

  "material-icon-theme.folders.associations": {
    "infra": "app",
    "entities": "class",
    "schemas": "class",
    "typeorm": "database",
    "repositories": "mappings",
    "http": "container",
    "migrations": "tools",
    "modules": "components",
    "implementations": "core",
    "dtos": "typescript",
    "fakes": "mock",
    "websockets": "pipe",
    "protos": "pipe",
    "grpc": "pipe"
  },

  "material-icon-theme.files.associations": {
    "ormconfig.json": "database",
    "tsconfig.json": "tune",
    "*.proto": "3d"
  },
  "workbench.colorTheme": "Dracula Soft"
}
```

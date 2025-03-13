{
  // Define o tema do VSCode
  "workbench.colorTheme":"poimandres",

  // Configura tamanho e família da fonte
  "editor.fontSize":18,
  "editor.fontFamily":"jetBrains Mono",
  "editor.fontLigatures":true,

  // Aplica linhas verticais para lembrar de quebrar linha em códigos muito grandes
  "editor.rulers": [
    80,
    120
  ],

  // Aplica um sinal visual na esquerda da linha selecionada
  "editor.renderLineHighlight":"gutter",

  // Aumenta a fonte do terminal
  "terminal.integrated.fontSize":16,

  // Define o tema dos ícones na sidebar
  "workbench.iconTheme":"material-icon-theme",
  "workbench.tree.enableStickyScroll": true,
  "editor.stickyScroll.enabled": true,
  "editor.stickyScroll.defaultModel": "indentationModel",
  "editor.stickyScroll.maxLineCount": 7,
  "github.copilot.editor.enableAutoCompletions": true,
  "git.suggestSmartCommit": false,
  "git.openRepositoryInParentFolders": "never",
  "diffEditor.ignoreTrimWhitespace": false,
  

  "editor.lineHeight": 1.8,
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "tailwindCSS.experimental.classRegex": [
    [
      "tv\\(([^)]*)\\)",
      "[\"'`]([^\"'`]*).*?[\"'`]"
    ],
    "class:\\s*?[\"'`]([^\"'`]*).*?,"
  ],
  "typescript.updateImportsOnFileMove.enabled": "always",
  "gitlens.codeLens.recentChange.enabled": true,
  "typescript.suggest.autoImports": true,
  "editor.accessibilitySupport": "off",
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "editor.tabSize": 2,
  "files.exclude": {
    "**\/CVS": true,
    "**\/.DS_Store": true,
    "**\/.hg": true,
    "**\/.svn": true,
    "**\/.git": true,
    ".vscode": true
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "window.titleBarStyle": "native",
  "editor.minimap.enabled": true,
  "editor.scrollbar.vertical": "visible",
  "explorer.sortOrder": "foldersNestsFiles",
  "explorer.fileNesting.patterns": {
    "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-*, bun.lockb, nest*, package-lock*",
    "tailwind.config.*": "tailwind.config*, postcss.config*",
    ".env.local": ".env*",
    ".env": ".env*"
  },
  "explorer.fileNesting.enabled": true,
  "window.autoDetectColorScheme": true,
  "workbench.preferredLightColorTheme": "Min Light",
  "editor.suggestFontSize": 16,
  "editor.minimap.autohide": false,
  "workbench.preferredDarkColorTheme": "Dracula Refined",
}

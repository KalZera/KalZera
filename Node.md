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
  "terminal.integrated.fontSize":14,

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
  "extensions.ignoreRecommendations": true,
  "typescript.tsserver.log": "off",
  "files.associations": {
    ".env.*": "dotenv",
    ".prettierrc": "json",
    "*.css": "css",
    ".dev.vars": "dotenv"
  },
  "symbols.files.associations": {
    "*.module.ts": "nest",
    "*.guard.ts": "typescript",
    "*.spec.ts": "ts-test",
    "*.e2e-spec.ts": "ts-test",
    "*.mock.ts": "ts-test",
    "vitest.config.e2e.ts": "vite",
    ".env.development.local": "gear",
    ".env.test.local": "gear",
    ".env.local": "gear",
    ".env.example": "gear"
  },
  "tailwindCSS.experimental.classRegex": [
    [
      "tv\\(([^)]*)\\)",
      "[\"'`]([^\"'`]*).*?[\"'`]"
    ],
    "class:\\s*?[\"'`]([^\"'`]*).*?,"
  ],
  "editor.parameterHints.enabled": false,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.suggestSelection": "first",
  "explorer.confirmDelete": false,
  "gitlens.codeLens.recentChange.enabled": false,
  "terminal.integrated.showExitAlert": false,
  "[prisma]": {
    "editor.formatOnSave": true
  },
  "typescript.suggest.autoImports": true,
  "typescript.preferences.preferTypeOnlyAutoImports": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "mdx": "javascriptreact"
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx",
    "mdx": "jsx"
  },
  "editor.acceptSuggestionOnCommitCharacter": false,
  "explorer.compactFolders": false,
  "git.enableSmartCommit": true,
  "editor.accessibilitySupport": "off",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "graphql"
  ],
  "editor.semanticHighlighting.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "editor.tabSize": 2,
  "security.workspace.trust.untrustedFiles": "newWindow",
  "files.exclude": {
    "**\/CVS": true,
    "**\/.DS_Store": true,
    "**\/.hg": true,
    "**\/.svn": true,
    "**\/.git": true,
    ".vscode": true
  },
  "update.mode": "manual",
  "terminal.integrated.gpuAcceleration": "on",
  "terminal.integrated.defaultProfile.osx": "fish",
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "window.commandCenter": false,
  "symbols.hidesExplorerArrows": false,
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "update.showReleaseNotes": false,
  "security.promptForLocalFileProtocolHandling": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "window.titleBarStyle": "native",
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
  "gitlens.advanced.messages": {
    "suppressIntegrationRequestTimedOutWarning": true
  },
  "screencastMode.fontSize": 64,
  "scm.inputFontFamily": "",
  "editor.suggestFontSize": 16,
  "editor.minimap.autohide": true,
  "workbench.preferredDarkColorTheme": "Dracula Refined",
}

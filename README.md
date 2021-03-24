# my-mac-setup-2021

### Apps
- Chrome
- Visual Studio Code Insiders
- KensingtonWorks
- Alfred
- Clipy
- DisplayLink
- Docker
- iTerm2
- Karabiner
- Logi Options
- pgAdmin
- Postgres.app
- Postman
- Rectangle
- Slack
- The Unarchiver
- TablePlus
- GitHub Desktop
- Slack

### Bookmarks
- Gmail
- Notion
- GitHub
- AWS Console 
- dev.to
- Qiita
- Zenn
- YouTube
- Udemy

### Chrome extentions
- Dark Reader
- Octotree
- OctoLinker
- GitHub File Icons
- Enhanced GitHub
- React Developer Tools
- Lighthouse
- Dark VS Code GitHub Theme

### Setup Todo
- Homebrew
- aws cli
- eb cli
- sam cli
- pulumi cli
- cdk cli
- anyenv
- Python
- Go
- Node.js
- yarn
- Xcode
- postgres
- redis

### zsh setup
- oh-my-zsh
- powerlevel10k
- last-working-dir
- zsh-interactive-cd
- z
- up
- autoupdate
- history-search-multi-word
- fzf
- fzf-tab
- fast-syntax-highlighting
- zsh-autosuggestions
- zsh-bash-completions-fallback
- zsh-autopair
- tab_complete
- bracketed-paste-magic
- zsh-completions
- direnv

```
alias s="source ~/.zshrc"
alias ga="git add --all"
alias gc="git commit -m "
alias gf="git fetch origin"
alias gpush="git push origin HEAD"
alias gpull="git pull origin master"
alias grs="git reset --soft HEAD~1"
alias vsz="cd && code-insiders .zshrc"
```

### Visual Studio Code extentions

### Must
- Bracket Pair Colorizer 2
- Code Spell Checker
- Control Snippets
- Error Lens
- DotENV
- Extened Terminal Integration
- Formatting Toggle
- Git Graph
- gitignore
- GitLens
- Go to Next/Previous Member
- indent-rainbow
- Markdown All in One
- markdownlint
- MetaGo
- MetaJump
- MetaWord
- Output Colorizer
- Quick and Simple Text Selection
- Shortcuts
- Sort JSON objects
- Tabnine
- Visual Studio IntelliCode
- YAML
- Docker

### Themes
- Material Theme Icons

### JavaScript
- ESLint
- Import Cost
- Move TS
- Node.js Modules Intellisense
- npm
- npm Intellisense
- Prettier
- Quokka.js
- QUokka Statusbar
- TypeScript Import
- TypeScript Import Sorter
- 

### Go
- Go
- Go Outliner
- Lowlight Go Errors

### Mermaid
- Mermaid Markdown Syntax Highlighting
- Mermaid Preview

### Maybe
- All Autocomplete
- Auto Close Tag
- Auto Complete Tag
- Auto Correct
- Auto Import
- Auto Rename Tag
- CloudFormation
- EditorConfig for VS Code
- htmltagwrap
- Partial Diff
- Path Autocomplete
- Path Intellisense

### Fonts
- FiraCode

### Other
- Change Modifier Key: from Caps Lock to Control
- Kill PowerChime
```
defaults write com.apple.PowerChime ChimeOnAllHardware -bool false;killall PowerChime
```

### Visual Studio Code settings.json
```
{
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[markdown]": {
		"files.trimTrailingWhitespace": false
	},
	"diffEditor.renderSideBySide": true,
	"editor.colorDecorators": false,
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.fontFamily": "Fira Code",
	"editor.fontLigatures": true,
	"editor.formatOnPaste": true,
	"editor.formatOnSave": true,
	"editor.formatOnType": true,
	"editor.minimap.renderCharacters": false,
	"editor.minimap.showSlider": "always",
	"editor.renderControlCharacters": true,
	"editor.renderLineHighlight": "all",
	"editor.renderWhitespace": "all",
	"editor.suggest.shareSuggestSelections": true,
	"editor.suggestSelection": "first",
	"editor.tabSize": 2,
	"editor.wordWrap": "on",
	"emmet.showSuggestionsAsSnippets": true,
	"emmet.triggerExpansionOnTab": true,
	"explorer.confirmDelete": false,
	"explorer.confirmDragAndDrop": false,
	"explorer.incrementalNaming": "smart",
	"explorer.sortOrder": "type",
	"extensions.closeExtensionDetailsOnViewChange": true,
	"files.associations": {
		".*lintrc": "json",
		"*.mmd": "markdown"
	},
	"files.autoGuessEncoding": true,
	"files.exclude": {
		".parcel-cache": true,
		"**/*.map": true
	},
	"files.insertFinalNewline": true,
	"files.simpleDialog.enable": true,
	"files.trimFinalNewlines": true,
	"files.trimTrailingWhitespace": true,
	"html.format.contentUnformatted": "pre, code, textarea, title, h1, h2, h3, h4, h5, h6, p",
	"html.format.extraLiners": "",
	"html.format.unformatted": null,
	"html.format.wrapLineLength": 0,
	"search.exclude": {
		"**/tmp": true
	},
	"terminal.explorerKind": "external",
	"terminal.external.osxExec": "iTerm.app",
	"terminal.integrated.cursorBlinking": true,
	"terminal.integrated.shell.osx": "/bin/zsh",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"window.closeWhenEmpty": true,
	"window.newWindowDimensions": "inherit",
	"window.title": "${activeEditorMedium}${separator}${rootName}",
	"workbench.editor.closeOnFileDelete": true,
	"workbench.editor.enablePreview": false,
	"workbench.editor.enablePreviewFromQuickOpen": false,
	"workbench.editor.highlightModifiedTabs": true,
	"workbench.editor.labelFormat": "short",
	"workbench.editor.tabSizing": "shrink",
	"workbench.settings.openDefaultSettings": true,
	"workbench.startupEditor": "none",
	"sync.gist": "21c60b382a5b2e0649b3b7090ca1d4cc",
	"terminal.integrated.fontFamily": "MesloLGS NF",
	"sync.quietSync": false,
	"eslint.alwaysShowStatus": true,
	"git.autofetch": true,
	"git.fetchOnPull": true,
	"git-graph.dialog.addTag.pushToRemote": true,
	"material-icon-theme.activeIconPack": "vue_vuex",
	"materialTheme.accent": "Breaking Bad",
	"prettier.singleQuote": true,
	"prettier.vueIndentScriptAndStyle": true,
	"vetur.format.scriptInitialIndent": true,
	"vetur.format.styleInitialIndent": true,
	"vsintellicode.features.python.deepLearning": "enabled",
	"editor.cursorBlinking": "expand",
	"powermode.enabled": true,
	"bracket-pair-colorizer-2.activeScopeCSS": [
		"borderStyle : solid",
		"borderWidth : 1px",
		"borderColor : {color}",
		"opacity: 0.5"
	],
	"cSpell.userWords": [
		"AWSEB",
		"Buildfile",
		"Chakra",
		"Dockerrun",
		"Fargate",
		"Formik",
		"Juku",
		"Millis",
		"Noedjs",
		"Procfile",
		"QLID",
		"Updoot",
		"Vuex",
		"apigw",
		"byweekday",
		"chmod",
		"codegen",
		"combinate",
		"csrf",
		"dataloader",
		"dbname",
		"dedup",
		"dgrijalva",
		"dirents",
		"dirpath",
		"downdoot",
		"dtstart",
		"dynamodb",
		"edichi",
		"elgohr",
		"esbuild",
		"fontsource",
		"godoc",
		"gofiber",
		"golangci",
		"gomega",
		"gonic",
		"gorm",
		"graphcache",
		"graphiql",
		"hitcounter",
		"jinzhu",
		"kazuki",
		"keyname",
		"learngo",
		"middlewares",
		"middly",
		"mikro",
		"mimetype",
		"mixins",
		"mmdc",
		"nestjs",
		"nextchakra",
		"nextjs",
		"nuxt",
		"nuxtjs",
		"onsi",
		"postgres",
		"postgresql",
		"pulumi",
		"quokka",
		"readonly",
		"resave",
		"respawn",
		"roboto",
		"rrule",
		"scrollbar",
		"smtp",
		"sqlite",
		"stretchr",
		"submodules",
		"swaggo",
		"todos",
		"tscdk",
		"tsnd",
		"typegraphql",
		"typeorm",
		"unmarshall",
		"unmarshalled",
		"unmarshalling",
		"updoots",
		"urql",
		"varchar",
		"wonka",
		"wtwa"
	],
	"prettier.useTabs": true,
	"powermode.enableStatusBarComboCounter": false,
	"powermode.enableStatusBarComboTimer": false,
	"typescript.format.semicolons": "insert",
	"javascript.format.semicolons": "insert",
	"typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBraces": false,
	"powermode.enableShake": false,
	"yaml.schemas": {
		"file:///toc.schema.json": "/toc\\.yml/i"
	},
	"editor.renameOnType": true,
	"workbench.preferredDarkColorTheme": "GitHub Dark",
	"workbench.preferredHighContrastColorTheme": "Community Material Theme Palenight High Contrast",
	"workbench.preferredLightColorTheme": "GitHub Light",
	"autoimport.filesToScan": "**/*.{ts,tsx,js}",
	"prettier.packageManager": "yarn",
	// Custom tags for the parser to use
	"yaml.customTags": [
		"!And",
		"!If",
		"!Not",
		"!Equals",
		"!Or",
		"!FindInMap sequence",
		"!Base64",
		"!Cidr",
		"!Ref",
		"!Sub",
		"!GetAtt",
		"!GetAZs",
		"!ImportValue",
		"!Select",
		"!Select sequence",
		"!Split",
		"!Join sequence"
	],
	// Enable/disable default YAML formatter (requires restart)
	"yaml.format.enable": true,
	"aws.profile": "profile:default",
	"jumpy.darkThemeBackground": "black",
	"jumpy.darkThemeForeground": "green",
	"jumpy.fontFamily": "Fira Code",
	"tabnine.experimentalAutoImports": true,
	"workbench.colorTheme": "Horizon Italic",
	"editor.columnSelection": false,
	"editor.multiCursorModifier": "alt",
	"editor.snippetSuggestions": "top",
	"bookmarks.useWorkaroundForFormatters": true,
	"tsimporter.preferRelative": true,
	"importSorter.importStringConfiguration.tabSize": 2,
	"importSorter.importStringConfiguration.trailingComma": "multiLine",
	"importSorter.sortConfiguration.removeUnusedDefaultImports": true,
	"importSorter.sortConfiguration.removeUnusedImports": true,
	"javascript.preferences.importModuleSpecifier": "relative",
	"typescript.preferences.importModuleSpecifier": "relative",
	"commentAnchors.workspace.excludeFiles": "**/{.git,.idea,target,out,vendor}/**/*",
	"gitlens.advanced.messages": {
		"suppressCommitHasNoPreviousCommitWarning": true
	},
	"liveshare.presence": true,
	"liveshare.allowInvites": "all",
	"prettier.arrowParens": "avoid",
	"debug.node.autoAttach": "off",
	"debug.inlineValues": true,
	"typescript.format.insertSpaceAfterOpeningAndBeforeClosingJsxExpressionBraces": true,
	"prettier.jsxSingleQuote": true,
	"javascript.format.insertSpaceAfterOpeningAndBeforeClosingJsxExpressionBraces": true,
	"emmet.includeLanguages": {
		"javascript": "javascriptreact"
	},
	"importBeautify.tabType": "tab",
	"go.formatOnSave": true,
	"workbench.iconTheme": "material-icon-theme",
	"go.autocompleteUnimportedPackages": true,
	"[go]": {
		"editor.insertSpaces": false,
		"editor.formatOnSave": true,
		"editor.codeActionsOnSave": {
			"source.organizeImports": true
		},
		"editor.defaultFormatter": "golang.go"
	},
	"vs-kubernetes": {
		"vs-kubernetes.minikube-path.mac": "/Users/kazuki/.vs-kubernetes/tools/minikube/darwin-amd64/minikube",
		"vs-kubernetes.helm-path.mac": "/Users/kazuki/.vs-kubernetes/tools/helm/darwin-amd64/helm",
		"vs-kubernetes.draft-path.mac": "/Users/kazuki/.vs-kubernetes/tools/draft/darwin-amd64/draft",
		"vscode-kubernetes.minikube-path.mac": "/Users/kazuki/.vs-kubernetes/tools/minikube/darwin-amd64/minikube"
	},
	"typescript.updateImportsOnFileMove.enabled": "always",
	"todo-tree.tree.showScanModeButton": false,
	"kite.showWelcomeNotificationOnStartup": false,
	"files.defaultLanguage": "${activeEditorLanguage}",
	"markdown.extension.preview.forestautoShowPreviewToSide": true,
	"mermaid.theme": "forest",
	"mermaid.vscode.dark": "forest",
	"mermaid-editor.generate.type": "png",
	"mermaid-editor.preview.defaultMermaidConfig": "",
	"window.zoomLevel": 1,
	"go.toolsManagement.autoUpdate": true,
	"cloudcode.yaml.format.enable": true,
	"cloudcode.yaml.yamlFileMatcher": "**/*.yaml, **/*.yml",
	"go.goroot": "/usr/local/Cellar/go/1.16.2/libexec",
	"go.inferGopath": true,
	"go.gopath": "/usr/local/Cellar/go/1.16.2/libexec",
	"go.toolsGopath": "/usr/local/Cellar/go/1.16.2/libexec"
}

```

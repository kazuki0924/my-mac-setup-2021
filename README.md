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
- tree
- up
- direnv
- Medis

### Go
```
go get -u github.com/cosmtrek/air

// .zshrc
alias air='$(go env GOPATH)/bin/air'
```

### Redis
```
cd /Applications && git clone https://github.com/luin/medis.git && cd medis && npm install && npm run pack && npm start

// .zshrc
alias medis="cd /Applications/medis && npm start"
```

### zsh setup
- oh-my-zsh
- powerlevel10k

https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/last-working-dir
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/alias-finder/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/fzf/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/history-substring-search/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/jsontools/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/last-working-dir/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/dirhistory/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/z/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/command-not-found/README.md
https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/zsh-interactive-cd/README.md
https://github.com/zsh-users/zsh-completions
https://github.com/marlonrichert/zsh-autocomplete
https://github.com/hlissner/zsh-autopair
https://github.com/zsh-users/zsh-autosuggestions
https://github.com/zdharma/fast-syntax-highlighting
https://github.com/TamCore/autoupdate-oh-my-zsh-plugins
https://github.com/zdharma/history-search-multi-word
https://github.com/Aloxaf/fzf-tab
https://github.com/lincheney/fzf-tab-completion

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
- Horizon
- Fluent Icons

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

### Go
- Go
- Go Outliner
- Lowlight Go Errors

### Shell
- shell-format
- Shell Syntax
- Better Shell Syntax
- Shell Script Snippets
- Bash IDE

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

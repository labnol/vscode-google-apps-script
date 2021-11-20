# Google Apps Script Extension Pack

The Extension Pack for Google Apps Script is a collection of popular extensions that help you write, test and debug your Google Apps Script code inside Visual Studio Code. Check out the [Google Apps Script for Developers](https://www.labnol.org/internet/google-apps-script-developers/32305/) guide to get started.

[![Google Apps Script for Developers](https://i.imgur.com/6xdU6EO.png)](https://www.youtube.com/watch?v=KxdCIbeO4Uk)

## Recommended VS Code Settings

Here are the recommended settings for working with Google Apps Script in Visual Studio Code.

### Editor Settings

The recommended monospace coding fonts are [Ubuntu Mono](https://fonts.google.com/specimen/Ubuntu+Mono). [Red Hat Mono](https://fonts.google.com/specimen/Red+Hat+Mono), [Fira Code](https://fonts.google.com/specimen/Fira+Code), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) and [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono).

```
"editor.fontSize": 15,
"editor.fontFamily": "Ubuntu Mono, Red Hat Mono, Fira Code, JetBrains Mono, IBM Plex Mono",
"editor.fontLigatures": true,
"editor.bracketPairColorization.enabled": true,
"editor.guides.bracketPairs": true,
"[html]": {
  "editor.defaultFormatter": "vscode.html-language-features"
},
"[javascript]": {
  "editor.formatOnSave": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[json]": {
  "editor.defaultFormatter": "esbenp.prettier-vscode"
},
"files.autoSave": "onFocusChange",
"editor.formatOnSave": true,
"editor.codeActionsOnSave": {
  "source.fixAll.eslint": true,
  "source.organizeImports": false,
  "source.sortImports": true
},
"files.exclude": {
  "**/node_modules": true
},
"search.exclude": {
  "**/*-lock.json": true,
  "**/node_modules": true,
  "**/dist": true
},
```

### Integrated Terminal Settings

The recommended terminal is [iTerm2](https://iterm2.com/) and the font is [Ubuntu Mono](https://fonts.google.com/specimen/Ubuntu+Mono).

```
"terminal.external.osxExec": "iterm.app",
"terminal.integrated.fontSize": 14,
"terminal.integrated.lineHeight": 1.45,
"terminal.integrated.cursorBlinking": true,
"terminal.integrated.cursorStyle": "underline",
"terminal.integrated.defaultProfile.osx": "zsh",
"terminal.integrated.fontFamily": "'Ubuntu Mono',Monospace,'Cascadia Code'",
```

![Google Apps Script](https://i.imgur.com/pI8UfMB.png)

### Terminal Color Theme (workbench.colorCustomizations)

```
"terminal.background": "#282936",
"terminal.foreground": "#E9E9F4",
"terminalCursor.background": "#E9E9F4",
"terminalCursor.foreground": "#E9E9F4",
"terminal.ansiBlack": "#282936",
"terminal.ansiBlue": "#62D6E8",
"terminal.ansiBrightBlack": "#626483",
"terminal.ansiBrightBlue": "#62D6E8",
"terminal.ansiBrightCyan": "#A1EFE4",
"terminal.ansiBrightGreen": "#EBFF87",
"terminal.ansiBrightMagenta": "#B45BCF",
"terminal.ansiBrightRed": "#EA51B2",
"terminal.ansiBrightWhite": "#F7F7FB",
"terminal.ansiBrightYellow": "#00F769",
"terminal.ansiCyan": "#A1EFE4",
"terminal.ansiGreen": "#EBFF87",
"terminal.ansiMagenta": "#B45BCF",
"terminal.ansiRed": "#EA51B2",
"terminal.ansiWhite": "#E9E9F4",
"terminal.ansiYellow": "#00F769"
```

## Extensions in Apps Script Pack

By install the Google Apps Script extension pack, the following extensions are included in your Visual Studio Code workspace:

- [Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright) - A spell checker extension for source code and plain text files.
- [Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log) - Easily add `console.log` messages to your code for easier debugging.
- [Open Folder](https://marketplace.visualstudio.com/items?itemName=chrisdias.vscode-opennewinstance) - Quickly open a new instance of Visual Studio Code with the selected folder.
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - Easily import [npm packages](https://www.labnol.org/npm-command-tricks-210824) to your code.
- [npm Scripts](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) - Validate dependencies defined in the `package.json` file and easily run npm scripts from the command palette.
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Easily import filenames to your code.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Find and automatically fix common problems in your Google Apps Script code.
- [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock) - Useful when you work with multiple VS Code instances and want to quickly identify which is which.
- [Dracula Theme](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula) - A recommended dark theme for Visual Studio Code that also supports Vim, Zsh, iTerm, Sublime Text, Emacs, and many other editors.
- [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) - A [Vim-like editor](https://www.labnol.org/internet/learning-vim-for-beginners/28820/) for Visual Studio Code.
- [Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Know who committed what to your code and easily revert changes.
- [node_modules Search](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules) - Easily search files inside the `node_modules` folder that are normally excluded from default search results.
- [Great Icons](https://marketplace.visualstudio.com/items?itemName=emmanuelbeziat.vscode-great-icons) - A set of beautiful and sharp icons that are great for Google Apps Script project files and folders.
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Prettier is a perfect code formatter for JavaScript, TypeScript, CSS, and HTML files.
- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) - A lightweight Postman-like REST client for running [HTTP requests](https://www.labnol.org/apps/urlfetch.html) inside the code editor.
- [Reload](https://marketplace.visualstudio.com/items?itemName=natqe.reload) - Adds a reload button to the status bar for quickly reload the current instance of Visual Studio Code.
- [Gremlins Tracker](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins) - Discover any invisible characters in your Google Apps Script code, like [zero width spaces](https://www.labnol.org/internet/twitter-auto-converts-links/20771/), that can cause problems later.
- [Microsoft Edge Tools](https://marketplace.visualstudio.com/items?itemName=ms-edgedevtools.vscode-edge-devtools) - Adds [Chrome developer tools](https://www.labnol.org/software/chrome-dev-tools-tutorial/28131/) inside VS code and helps you fix CSS issues and inspect network activity.
- [GitHub Repo](https://marketplace.visualstudio.com/items?itemName=github.remotehub) - A GitHub repository browser inside VS code.

## Google Apps Script Resources

- [Google Apps Script Snippets](https://www.labnol.org/topic/google-apps-script) - A library of useful Google Apps Script code snippets.
- [Google Apps Script for Developers](https://www.youtube.com/watch?v=KxdCIbeO4Uk) - A guide to building Google Workspace add-ons inside Visual Studio Code.
- [Apps Script Starter Kit](https://github.com/labnol/apps-script-starter) - A template for developing Google Apps Script projects with Code and `@google/clasp`.

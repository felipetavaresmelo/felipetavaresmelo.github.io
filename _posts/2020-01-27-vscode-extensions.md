---
layout: post
title:  "VS Code Extensions"
date:   2020-01-27
excerpt: "Extenções do VS Code"
tag:
- VS Code 
- Extensions
comments: true
---

# Instação do [VSCODE no Linux Ubuntu](https://snapcraft.io/store)

Primeiramente para fazer a instalação do VSCODE com o comando:

    sudo snap install code --classic

## [Visual Studio Code Extensions](https://code.visualstudio.com/docs/editor/extension-gallery#_command-line-extension-management)

Pasta padrão de instalação das extensões:

    code --extensions-dir ~/.vscode/extensions

List extensões do Visual Studio Code:

    code --list-extensions

Para instalar uma extensão:

    code --install-extension <extension-id>

Para desinstalar uma extensão:

code --uninstall-extension <extension-id>

Para abilitar uma extensão:

code --enable-proposed-api <extension-id>

## Theme

- [Dracula Theme](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula) (dracula-theme.theme-dracula)
- [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) (Equinusocio.vsc-material-theme)

## Icons

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) (PKief.material-icon-theme)

### Debuggers
    
    Debugger é um programa de computador usado para testar outros programas e fazer sua depuração, que consiste em encontrar os defeitos do programa.

- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) (formulahendry.code-runner)

### Reloaders

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)(ritwickdey.liveserver)

### Formatters

- Destaque fechamentos de tags: [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) (CoenraadS.bracket-pair-colorizer)
- HTML: 
    - [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) (formulahendry.auto-close-tag)
    ```bash
    code --install-extension formulahendry.code-runner 
    ```
    - [Sorting HTML and Jade attributes](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-attrs-sorter) (mrmlnc.vscode-attrs-sorter)


### [Linter](https://en.wikipedia.org/wiki/Lint_)
    Linter é uma ferramenta que analisa o código-fonte para sinalizar erros de programação, bugs, erros estilísticos e construções suspeitas.


### [Code completion/IntelliSense](https://en.wikipedia.org/wiki/Intelligent_code_completion)
    IntelliSense é um recurso de conclusão de código com reconhecimento de contexto em alguns ambientes de programação que acelera o processo de codificação de aplicativos, reduzindo erros de digitação e outros erros comuns.

- [IntelliSense in Visual Studio Code](https://code.visualstudio.com/docs/editor/intellisense)

### [Snippet](https://en.wikipedia.org/wiki/Snippet_(programming))
    Snippet é um termo de programação para uma pequena região de código-fonte reutilizável, código de máquina ou texto. Normalmente, essas são unidades operacionais formalmente definidas para serem incorporadas em módulos de programação maiores.

- [Snippets in Visual Studio Code](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

## HTML

- Formatter
- Snippets
    - [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets) (abusaidm.html-snippets)

## CSS

- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion) (Zignd.html-css-class-completion)

## JavaScript

- Formatter
    - Vue.JS: [vue-beautify](https://marketplace.visualstudio.com/items?itemName=peakchen90.vue-beautify) (peakchen90.vue-beautify)
- Linter
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) (dbaeumer.vscode-eslint)
- Snippet
    - [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) 
- Debugger
    - [JavaScript Debugger (Nightly)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-debug-nightly) (ms-vscode.js-debug-nightly)
    - [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) (msjsdiag.debugger-for-chrome)
    - [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug) (firefox-devtools.vscode-firefox-debug)
    - [Node Debug](https://marketplace.visualstudio.com/items?itemName=ms-vscode.node-debug2) (ms-vscode.node-debug2)
    - [Debugger for Electron](https://marketplace.visualstudio.com/items?itemName=kodetech.electron-debug) (kodetech.electron-debug)
    - [React Native Tools](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native) (msjsdiag.vscode-react-native)

## Python

- Debuggers
    - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) (ms-python.python)

## [Shell Script](https://pt.wikipedia.org/wiki/Shell_script)

- Formatter
    - [shell-format](https://marketplace.visualstudio.com/items?itemName=foxundermoon.shell-format) (foxundermoon.shell-format)
- Debuggers
    - [Bash Debug](https://marketplace.visualstudio.com/items?itemName=rogalmic.bash-debug) (rogalmic.bash-debug)
        ```shellscript
        code --install-extension rogalmic.bash-debug
        ```

## [Git](https://git-scm.com/)

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) (eamodio.gitlens)
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) (mhutchie.git-graph)
- [Gitflow Actions Sidebar](https://marketplace.visualstudio.com/items?itemName=ardisaurus.gitflow-actions-sidebar) (ardisaurus.gitflow-actions-sidebar)
- [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) (codezombiech.gitignore)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) (donjayamanne.githistory)

## Terminal

- [Hyper in VS Code](https://marketplace.visualstudio.com/items?itemName=LevitatingBusinessMan.hyper-vsc)(LevitatingBusinessMan.hyper-vsc)

## Markdon

- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) (davidanson.vscode-markdownlint)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) (yzhang.markdown-all-in-one)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) (shd101wyy.markdown-preview-enhanced)

## Documentação

- [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis) (joelday.docthis)

## Integração

- [Prettify JSON](https://marketplace.visualstudio.com/items?itemName=mohsen1.prettify-json) (mohsen1.prettify-json)
- [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) (DotJoshJohnson.xml)
- [Edit csv](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv) (janisdd.vscode-edit-csv)
- [Txt Syntax](https://marketplace.visualstudio.com/items?itemName=xshrim.txt-syntax) (xshrim.txt-syntax)

## Emuladores Mobile

- [Android iOS Emulator](https://marketplace.visualstudio.com/items?itemName=DiemasMichiels.emulate) (DiemasMichiels.emulate)

## Extension Packs

1. [Vue.js Extension Pack](https://marketplace.visualstudio.com/items?itemName=mubaidr.vuejs-extension-pack) (mubaidr.vuejs-extension-pack)
    - [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) (octref.vetur)
    - [Vue Peek](https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek) (dariofuzinato.vue-peek)
    - [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) (formulahendry.auto-rename-tag)
    - [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) (formulahendry.auto-close-tag)
    - [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)(eg2.vscode-npm-script)
    - [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) (xabikos.JavaScriptSnippets)
    - [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) (christian-kohler.npm-intellisense)
    - [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) (christian-kohler.path-intellisense)
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) (dbaeumer.vscode-eslint)
    - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) (esbenp.prettier-vscode)
    - [VSCode Essentials Snippets](https://marketplace.visualstudio.com/items?itemName=robertoachar.vscode-essentials-snippets) (robertoachar.vscode-essentials-snippets)
2. [React Extension Pack](https://marketplace.visualstudio.com/items?itemName=jawandarajbir.react-vscode-extension-pack) (jawandarajbir.react-vscode-extension)
    - [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets) (xabikos.ReactSnippets)
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) (dbaeumer.vscode-eslint)
    - [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)(eg2.vscode-npm-script)
    - [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) (xabikos.JavaScriptSnippets)
    - [Search node_modules](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules) (jasonnutter.search-node-modules)
    - [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) (christian-kohler.npm-intellisense)
    - [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) (christian-kohler.path-intellisense)
3. [Node.js Extension Pack](https://marketplace.visualstudio.com/items?itemName=waderyan.nodejs-extension-pack) (waderyan.nodejs-extension-pack)
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) (dbaeumer.vscode-eslint)
    - [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)(eg2.vscode-npm-script)
    - [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) (xabikos.JavaScriptSnippets)
    - [Search node_modules](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules) (jasonnutter.search-node-modules)
    - [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) (christian-kohler.npm-intellisense)
    - [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) (christian-kohler.path-intellisense)
4. [Python Extension Pack](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-extension-pack) (donjayamanne.python-extension-pack)
    - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) (ms-python.python)
    - [MagicPython](https://marketplace.visualstudio.com/items?itemName=magicstack.MagicPython) (magicstack.MagicPython)
    - [Jinja](https://marketplace.visualstudio.com/items?itemName=wholroyd.jinja) (wholroyd.jinja)
    - [Django](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django) (batisteo.vscode-django)
    - [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) (VisualStudioExptTeam.vscodeintellicode)
5. [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack) (Pivotal.vscode-boot-dev-pack)
    - [Spring Boot Tools](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-spring-boot) (Pivotal.vscode-spring-boot)
    - [Cloudfoundry Manifest YML Support](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-manifest-yaml) (Pivotal.vscode-manifest-yaml)
    - [Concourse CI Pipeline Editor](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-concourse) (Pivotal.vscode-concourse)
    - [Spring Initializr Java Support](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-initializr) (vscjava.vscode-spring-initializr)
    - [Spring Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard) (vscjava.vscode-spring-boot-dashboard)
6. Webpack
    - [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) (wix.vscode-import-cost)
7. [Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack) (MS-vsliveshare.vsliveshare-pack)
   - [Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)(MS-vsliveshare.vsliveshare)
   - [Live Share Audio](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-audio)(MS-vsliveshare.vsliveshare-audio)
   - [Live Share Chat](https://marketplace.visualstudio.com/items?itemName=karigari.chat)(karigari.chat)
   - [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)(johnpapa.vscode-peacock)

## Links importantes

- [VS Code Extension Marketplace](https://marketplace.visualstudio.com/VSCode)

https://marketplace.visualstudio.com/search?target=VSCode&category=Extension%20Packs&sortBy=Installs
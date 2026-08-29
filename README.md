# VS Code Setup & Extensions

A curated Visual Studio Code configuration and extension setup for polyglot development, covering Python & Data Science, Java & Spring Boot, .NET / C#, Dart & Flutter, Web Development, Containerization, and enhanced developer productivity.

---

## Table of Contents

- [Quick Installation](#quick-installation)
- [Settings & Customization](#settings--customization)
- [Extensions Overview](#extensions-overview)
  - [Python & Data Science](#python--data-science)
  - [Java & Spring Boot](#java--spring-boot)
  - [.NET & C#](#net--c)
  - [Dart & Flutter](#dart--flutter)
  - [Web Development & JavaScript](#web-development--javascript)
  - [UI, Themes & Visual Enhancements](#ui-themes--visual-enhancements)
  - [Git & Source Control](#git--source-control)
  - [Remote Development & Containers](#remote-development--containers)
  - [Productivity & Utilities](#productivity--utilities)

---

## Quick Installation

You can install all the extensions listed in [`extensions.txt`](file:///c:/Users/ADMIN/Downloads/Work/Projects/vscode-setup/extensions.txt) with a single command:

### PowerShell (Windows)
```powershell
Get-Content extensions.txt | ForEach-Object { code --install-extension $_ }
```

### Bash / Zsh (macOS & Linux)
```bash
cat extensions.txt | xargs -L 1 code --install-extension
```

---

## Settings & Customization

This repository includes a [`settings.json`](file:///c:/Users/ADMIN/Downloads/Work/Projects/vscode-setup/settings.json) pre-configured with:
- **Theme**: `Darkwaves: Carbon`
- **Icon Theme**: `Material Icon Theme`
- **Editor Settings**: Format on save enabled, word wrap enabled, ruler at 80 characters for Dart
- **Terminal Customization**: Custom foreground and selection colors with `JetBrainsMono NF` font support
- **Git**: Auto-fetch enabled

---

## Extensions Overview

### Python & Data Science

| Extension | Identifier | Description |
|---|---|---|
| **Python** | `ms-python.python` | Core extension providing IntelliSense, linting, debugging, code formatting, refactoring, and environment switching. |
| **Pylance** | `ms-python.vscode-pylance` | High-performance language server delivering fast type checking, auto-imports, signature help, and semantic colorization. |
| **Python Debugger** | `ms-python.debugpy` | Seamless debugging support for Python applications using the `debugpy` engine. |
| **Python Environment Manager** | `ms-python.vscode-python-envs` | Interface to view, create, and manage Python virtual environments (venv, conda, pyenv, etc.). |
| **Jupyter** | `ms-toolsai.jupyter` | Full Jupyter Notebook support directly inside VS Code with interactive cell execution and variable viewing. |
| **Jupyter Keymap** | `ms-toolsai.jupyter-keymap` | Standard Jupyter Notebook keyboard shortcuts for cell navigation and manipulation. |
| **Jupyter Notebook Renderers** | `ms-toolsai.jupyter-renderers` | Interactive rendering support for charts and plots (Plotly, Vega, Bokeh, LaTeX, HTML). |
| **Jupyter Cell Tags** | `ms-toolsai.vscode-jupyter-cell-tags` | Tagging support for notebook cells to customize execution or exporting. |
| **Jupyter Slide Show** | `ms-toolsai.vscode-jupyter-slideshow` | Converts Jupyter notebooks into interactive presentation slide shows (Reveal.js). |

---

### Java & Spring Boot

| Extension | Identifier | Description |
|---|---|---|
| **Extension Pack for Java** | `vscjava.vscode-java-pack` | Microsoft's official bundle containing essential Java extensions (Language Support, Debugger, Test Runner, Maven, Project Manager). |
| **Language Support for Java™ by Red Hat** | `redhat.java` | Java language server providing Maven/Gradle support, code completion, navigation, and refactoring. |
| **Debugger for Java** | `vscjava.vscode-java-debug` | Lightweight Java debugger supporting breakpoints, call stacks, threads, and expression evaluation. |
| **Test Runner for Java** | `vscjava.vscode-java-test` | Run and debug JUnit 4, JUnit 5, and TestNG test cases with visual test explorer integration. |
| **Project Manager for Java** | `vscjava.vscode-java-dependency` | Java project explorer for managing project structure, packages, dependencies, and JAR libraries. |
| **Maven for Java** | `vscjava.vscode-maven` | Maven project management, POM file support, build goal execution, and dependency resolution. |
| **Gradle for Java** | `vscjava.vscode-gradle` | Gradle build tool integration, task explorer, and dependency insight. |
| **Spring Boot Extension Pack** | `vmware.vscode-boot-dev-pack` | Collection of extensions for building and managing Spring Boot microservices. |
| **Spring Boot Tools** | `vmware.vscode-spring-boot` | Rich language tooling for Spring Boot `.properties` and `.yml` files, navigation across beans and request mappings. |
| **Spring Boot Dashboard** | `vscjava.vscode-spring-boot-dashboard` | Explorer to view, start, stop, and inspect running Spring Boot apps and live endpoints. |
| **Spring Initializr Java Support** | `vscjava.vscode-spring-initializr` | Wizard to generate and scaffold new Spring Boot projects directly from VS Code. |

---

### .NET & C#

| Extension | Identifier | Description |
|---|---|---|
| **C# Dev Kit** | `ms-dotnettools.csdevkit` | Comprehensive .NET development toolkit featuring Solution Explorer, project management, and test discovery. |
| **C#** | `ms-dotnettools.csharp` | Official C# language support powered by Roslyn (IntelliSense, syntax highlighting, refactorings). |
| **.NET Install Tool** | `ms-dotnettools.vscode-dotnet-runtime` | Manages .NET SDKs and runtime installations required by VS Code extensions. |

---

### Dart & Flutter

| Extension | Identifier | Description |
|---|---|---|
| **Dart** | `dart-code.dart-code` | Dart language support, code completion, formatting, type hints, and debugging. |
| **Flutter** | `dart-code.flutter` | Full Flutter tooling: device selection, hot reload / restart, widget inspector, and build shortcuts. |

---

### Web Development & JavaScript

| Extension | Identifier | Description |
|---|---|---|
| **npm Intellisense** | `christian-kohler.npm-intellisense` | Autocompletes npm modules in `import` and `require` statements. |
| **NPM-Dependency** | `howardzuo.vscode-npm-dependency` | Validates installed npm packages against `package.json` definitions. |
| **Import Cost** | `wix.vscode-import-cost` | Displays the inline bundle size (minified and gzipped) of imported JavaScript/TypeScript packages. |
| **Babel JavaScript** | `mgmcdermott.vscode-language-babel` | Syntax highlighting for ES201x, React JSX, Flow, and GraphQL. |
| **CSS Peek** | `pranaygp.vscode-css-peek` | Peek and jump directly to CSS ID and class definitions from HTML/JSX files. |
| **HTML CSS Support** | `zignd.html-css-class-completion` | Autocompletion and IntelliSense for CSS class and ID attributes in HTML. |
| **Auto Close Tag** | `formulahendry.auto-close-tag` | Automatically closes HTML/XML tags when typing the closing bracket `>`. |
| **Auto Rename Tag** | `formulahendry.auto-rename-tag` | Automatically synchronizes changes between opening and closing HTML/XML tags. |

---

### UI, Themes & Visual Enhancements

| Extension | Identifier | Description |
|---|---|---|
| **Material Icon Theme** | `pkief.material-icon-theme` | Beautiful, recognizable file and folder icons following Material Design. |
| **Darkwaves: Carbon** | `spacelaxy.spacelaxy-darkwaves` | Sleek, modern dark aesthetic color theme. |
| **Color Highlight** | `naumovs.color-highlight` | Visualizes CSS colors directly by highlighting color codes (HEX, RGB, HSL) with their actual color. |
| **indent-rainbow** | `oderwat.indent-rainbow` | Colorizes indentation steps in alternating rainbow colors for easier nesting readability. |
| **Guides** | `spywhere.guides` | Indentation and bracket guide lines with active stack and column indicators. |
| **Error Lens** | `usernamehw.errorlens` | Displays diagnostic errors, warnings, and lint hints inline right next to the code line. |

---

### Git & Source Control

| Extension | Identifier | Description |
|---|---|---|
| **Git History** | `donjayamanne.githistory` | Visual UI to view Git log, commit details, file history, and compare branches/commits. |
| **open-in-github** | `ziyasal.vscode-open-in-github` | Jump directly to the current file, line selection, or commit on GitHub in your browser. |

---

### Remote Development & Containers

| Extension | Identifier | Description |
|---|---|---|
| **Docker** | `ms-azuretools.vscode-docker` | Build, manage, and deploy containerized applications from Dockerfiles, containers, and registries. |
| **Container Tools** | `ms-azuretools.vscode-containers` | Container tooling and Azure integration support. |
| **Dev Containers** | `ms-vscode-remote.remote-containers` | Open any repository or folder inside a Docker container for isolated dev environments. |
| **WSL** | `ms-vscode-remote.remote-wsl` | Seamlessly run VS Code inside Windows Subsystem for Linux (WSL). |

---

### Productivity & Utilities

| Extension | Identifier | Description |
|---|---|---|
| **Prettier - Code Formatter** | `esbenp.prettier-vscode` | Multi-language code formatter enforcing consistent style across JS, TS, CSS, HTML, JSON, Markdown, and YAML. |
| **EditorConfig for VS Code** | `editorconfig.editorconfig` | Enforces team-wide indentation, line endings, and charset settings via `.editorconfig` files. |
| **Path Intellisense** | `christian-kohler.path-intellisense` | Autocompletes filenames and relative file paths in imports and URLs. |
| **Todo Tree** | `shiesh.todo-tree` | Scans workspace for `TODO` and `FIXME` comments and organizes them into an interactive tree in the sidebar. |
| **TODO Highlight** | `wayou.vscode-todo-highlight` | Highlights `TODO:`, `FIXME:`, and custom tags inside your code comments. |
| **change-case** | `wmaurer.change-case` | Converts selected text between camelCase, PascalCase, snake_case, CONSTANT_CASE, kebab-case, etc. |
| **Markdown All in One** | `yzhang.markdown-all-in-one` | Keyboard shortcuts, table of contents generator, list editing, and live preview for Markdown. |
| **DotENV** | `mikestead.dotenv` | Syntax highlighting and environment variable support for `.env` files. |
| **CodeMetrics** | `kisstkondoros.vscode-codemetrics` | Computes complexity metrics in TypeScript/JavaScript to help maintain clean code. |
| **PowerShell** | `ms-vscode.powershell` | PowerShell script editing, IntelliSense, code navigation, and integrated terminal debugging. |

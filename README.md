# Docker-VSCode
A collection of experimental Docker extensions

## What is this project?

Quicklinks:
- **[Language features](./lsp)**
- [Runnable markdown](./runbook-makefiles)

We are not forking the current [vscode docker extension](https://github.com/microsoft/vscode-docker). 

This is intended to be a contribution back to the original extension.  
We are just providing this project to get early feedback on that contribution.  

The proposed pull request branch is [here](https://github.com/docker/vscode-upstream-temp/commits/cm/docker-stuff-2).

Initially, there are two features added to the Dockerfile language service.

1.  Integration of Scout recommendations to the Dockerfile language service.
2.  Integration of the new support for Docker's new official Dockerfile linting support.

## Get started

### Step 1: Download Extension File
Two VSCode extensions are available:
- Dockerfile Language Features: https://github.com/docker/docker-vscode/releases/tag/lsp-v1.29.6-alpha
- Generate runnable makefile in markdown: https://github.com/docker/docker-vscode/releases/tag/runbook-v0.0.3

Download the `.vsix` bundle.

### Step 2: Enable Extension in VSCode

#### CLI:

Must have VSCode [code](https://code.visualstudio.com/docs/editor/command-line#_code-is-not-recognized-as-an-internal-or-external-command) command in PATH:

```bash
code --install-extension /my/path/to/docker-bundle.vsix --force
```

#### GUI:

Extensions -> `...` menu -> `Install from VSIX`

<img width="570" alt="Screenshot of docker install menu" src="https://github.com/docker/docker-ai/assets/5000430/1cf2b904-f341-4a84-aceb-1933c51efe68">

#### GUI (command palette):

1. Type `>` into top search bar
**Shortcut: Press ⇧⌘P (OSX) or CTRL⇧P (Win/Linux)**
2. Select `Extensions: Install from VSIX...`
3. Select `.vsix` file downloaded
4. Hit the “Reload Now” button in the notification at the bottom right corner

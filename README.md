# Docker-VSCode

This is an experiemental feature added to the [official VSCode extension for Docker](https://github.com/microsoft/vscode-docker).
Nothing here has been upstreamed but we want to stress that this is not a fork.  Assume that any positive results from this would be
contributed back to the original extension.

## What is this project?

The updates to this extension add a new experimental LSP.  We are current working on two features.

1.  Integration of Scout recommendations to the Dockerfile language service.
2.  Integration of the new support for Docker's new official Dockerfile linting support.

![lsp](https://github.com/docker/docker-vscode/releases/download/lsp-v1.29.6/CleanShot.2024-05-01.at.11.50.30.gif)

This should be considered a usable prototype.  It is mature enough to try internally but the features it supports 
are active works in progress.

## Getting started

See the complete [installation instructions](./lsp) for adding this version of the 
Docker extension to VSCode.


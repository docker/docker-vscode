# Docker-VSCode

A proposed update to the [official VSCode extension for Docker](https://github.com/microsoft/vscode-docker).

## What is this project?

We are extending the current VSCode extension for Docker with a small set of foundational features.  This
is not a fork of the current extension. It is a preview of the contribution that we are proposing
to make.

Besides the foundational elements, we're also adding two new features to the Dockerfile language service.

1.  Integration of Scout recommendations to the Dockerfile language service.
2.  Integration of the new support for Docker's new official Dockerfile linting support.

![lsp](https://github.com/docker/docker-vscode/releases/download/lsp-v1.29.6/CleanShot.2024-05-01.at.11.50.30.gif)

## Getting started

See the complete [installation instructions](./lsp) for adding this version of the 
Docker extension to VSCode.

# Docker Runbook Generator

## What is this project?

Uses generative AI, and project analysis, to add generate a Docker specific
runbook-style README.md to your project. See the following for an example:

![runbook4](https://github.com/docker/docker-vscode/assets/5000430/6da2c934-35f7-470d-962e-a2c9a43a335b)

## Getting started

See the [installation instructions](./runbook-makefiles) for adding runbook support 
to VSCode.

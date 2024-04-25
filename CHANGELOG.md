# Changelog

All notable changes to this project will be documented in this file.

## [<fork>1.29.5-alpha] 2024-4-25

### Added
* [Dockerfile Linting] Full markdown support

## [<fork>1.29.5-alpha] 2024-4-24

This extension is now forked from https://github.com/microsoft/vscode-docker with enhanced language featues. 

### Added
* [Dockerfile Linting] Base image recommendations
* [Dockerfile Linting] Automatic digest pinning
* [Dockerfile Linting] Best practices from buildkit lint
* [Dockerfile Linting] apk/apt-get package recommendations
* [Dockerfile Linting] Deep linked image details for Docker Desktop users
* [Dockerfile Linting] Autocompletes for tags, base image, and debian packages
* [Dockerfile Linting] Code lens to show local build status, showing size, and showing vulnerability count by Dockerfile instruction


### Removed
* Runbook generation
* Runnable terminal blocks
* Streaming LLM completions
* Integrated terminal docker debugging
* Terminal highlight explanations
* Taggable hotkey commands


## [v0.0.5](https://github.com/docker/docker-ai/releases/tag/pre-release) 2024-2-9

### Added

*   Runbook generation
*   Runnable terminal blocks
*   Streaming LLM completions
*   [INSIDERS VSCODE ONLY] Integrated terminal docker debugging
*   Terminal highlight explanations
*   Taggable hotkey commands

### Removed

* Notebooks
* Walkthrough
* Ask docker AI

### Fixed

* Activation reliability improved
* Activation time greatly reduced
* Misc. UX tweaks, copy, loading progress, etc...

## v0.0.4 2023-12-13

### Added

*   do not rely on git index for docker analysis - support non-versioned projects
*   add pre-flight checks to warn if Docker Desktop is configured and running

### Fixed

*   stability and bug fixes for Windows/WSL support

## v0.0.1 - 2023-11-30

### Added

*   Initial Release


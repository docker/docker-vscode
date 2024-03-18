# Docker VSCode Limited Early Access
This is an early access preview to VSCode extension features by Docker. Content in this repository is changing quickly, and is therefore open to feedback with the caveat that features may come and go. Bugs are expected.

## Installation Instructions

#### Step 1: Download Extension File
Download [latest vsix](https://github.com/docker/docker-ai/releases) pre-release file.

#### Step 2: Enable Extension in VSCode

**Option 1: Via the command line**

Must have VSCode code command in PATH:
`code --install-extension <PATH_TO_DOWNLOADED_.VSIX> --force`

If you don’t have the code command, you can [enable it in VSCode](https://code.visualstudio.com/docs/editor/command-line#_code-is-not-recognized-as-an-internal-or-external-command) or just use Option 2 below.

**Option 2: Via the command palette in VSCode**
1. Type `>` into top search bar
2. **Shortcut: Press ⇧⌘P (OSX) or CTRL⇧P (Win/Linux)**
3. Use command Extensions: Install from VSIX...
4. Select .VSIX file downloaded in Step 1
5. Hit the “Reload Now” button in the notification at the bottom right corner

**Option 3: Via VSCode GUI**
Extension Menu -> `...` dropdown -> `Install from VSIX`

<img width="570" alt="Screenshot 2024-03-18 at 11 53 58 AM" src="https://github.com/docker/docker-ai/assets/5000430/1cf2b904-f341-4a84-aceb-1933c51efe68">


# Source Control Buttons for Visual Studio Code

[![License](https://img.shields.io/github/license/idma88/git-buttons-vscode?style=for-the-badge)](https://github.com/idma88/git-buttons-vscode/blob/master/LICENSE)
[![VS Code Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/idma88.git-buttons-vscode?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=idma88.git-buttons-vscode)
[![VS Code Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/idma88.git-buttons-vscode?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=idma88.git-buttons-vscode)
[![VS Code Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/idma88.git-buttons-vscode?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=idma88.git-buttons-vscode)
[![Visual Studio Marketplace Last Updated](https://img.shields.io/visual-studio-marketplace/last-updated/idma88.git-buttons-vscode?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=idma88.git-buttons-vscode)

This extension adds additional buttons to the source control panel. See configuration options for full list of available buttons that can be added. Note that only git actions are supported at this time.

## Preview

![Preview](https://raw.githubusercontent.com/idma88/git-buttons-vscode/master/resources/preview.png)<br/>
*Note: Views not all available buttons*

## Extension Settings

This extension contributes the following settings:

Settings | Description
-|-
`git-buttons.showGitPull` | Show button `Git Pull`
`git-buttons.showGitPullRebase` | Show button `Git Pull (Rebase)`
`git-buttons.showGitPullFrom` | Show button `Git Pull From...`
`git-buttons.showGitPush` | Show button `Git Push`
`git-buttons.showGitPushTo` | Show button `Git Push To...`
`git-buttons.showGitSync` | Show button `Sync`
`git-buttons.showGitSyncRebase` | Show button `Sync (Rebase)`
`git-buttons.showGitCheckout` | Show button `Git Checkout`
`git-buttons.showGitPublish` | Show button `Git Publish Branch...`
`git-buttons.showGitCommitAll` | Show button `Git Commit All`
`git-buttons.showGitCommitAllAmend` | Show button `Git Commit All (Amend)`
`git-buttons.showGitCommitAllSigned` | Show button `Git Commit All (Signed Off)`
`git-buttons.showGitCommitStaged` | Show button `Git Commit Staged`
`git-buttons.showGitCommitStagedAmend` | Show button `Git Commit Staged (Amend)`
`git-buttons.showGitCommitStagedSigned` | Show button `Git Commit Staged (Signed Off)`
`git-buttons.showGitUndoCommit` | Show button `Git Undo Commit`
`git-buttons.showGitCleanAll` | Show button `Git Clean All`
`git-buttons.showGitStageAll` | Show button `Git Stage All`
`git-buttons.showGitUnstageAll` | Show button `Git Unstage All`
`git-buttons.showGitStashApplyLatest` | Show button `Git Apply Latest Stash`
`git-buttons.showGitStashApply` | Show button `Git Apply Stash...`
`git-buttons.showGitStashDrop` | Show button `Git Drop Stash...`
`git-buttons.showGitStashPopLatest` | Show button `Git Pop Latest Stash`
`git-buttons.showGitStashPop` | Show button `Git Pop Stash...`
`git-buttons.showGitStash` | Show button `Git Stash`
`git-buttons.showGitStashIncludeUntracked` | Show button `Git Stash (Include Untracked)`
`git-buttons.showGitShowOutput` | Show button `Git Show Output`

## Release Notes

### Version 1.2.1

- Fixed button display for VS Code 1.106 and above

### Version 1.1.0

- Add better support for multi workspace projects

### Version 1.0.0

- Added buttons for `Git Sync` and `Git Sync (Rebase)` commands
- Update README

### Version 0.2.0

- Fix typo in command `Git Stash (Include Unt[r]acked)`

### Version 0.1.1

- Updates to store page

### Version 0.1.0

- Initial release

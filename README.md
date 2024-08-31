# markdownxit

**markdownxit** is a custom Visual Studio Code extension that provides syntax highlighting and token color customization for Markdown files with task-specific features.

This is based on `xit!` at https://xit.jotaen.net/ and injects some xit colors into markdown styles.

- Install the package in VS Code or Cursor with `cmd + shift + p` and `install from VSIX`.
- Publish with `vsce package` and install in VS Code with `code --install-extension markdownxit-<version>.vsix`.



## Features

- Syntax highlighting for various task states in Markdown files, including:
  - `[x]` for checked/done tasks
  - `[ ]` for open tasks
  - `[@]` for ongoing tasks
  - `[~]` for obsolete/cancelled tasks
  - `[?]` for tasks in question
- Supports `.md` and `.xit` file extensions.
- Custom color theme for enhanced readability.

## Installation

1. Download and install the extension from the VS Code Marketplace.
2. Open a Markdown file or create a new file with a `.md` or `.xit` extension.
3. Select the "MarkdownXit" color theme from the VS Code theme picker (`Ctrl+K Ctrl+T`).

## Usage

Simply write your tasks in the Markdown file using the supported syntax, and the extension will automatically apply the appropriate styles and colors.

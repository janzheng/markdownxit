# markdownxit

**markdownxit** is a custom Visual Studio Code extension that provides syntax highlighting and token color customization for Markdown files with task-specific features.

This is based on `xit!` at https://xit.jotaen.net/ and injects some xit colors into markdown styles.


## Installation

1. Download the .vsix file from the repo.
2. Install the package in VS Code or Cursor with `cmd + shift + p` and `install from VSIX`.


## Making it your own

Edit the theme in `package.json` then create a new package with `vsce package`



## Usage

Simply write your tasks in the Markdown file using the supported syntax, and the extension will automatically apply the appropriate styles and colors.

- Syntax highlighting for various task states in Markdown files, including:
  - `[x]` for checked/done tasks
  - `[ ]` for open tasks
  - `[@]` for ongoing tasks
  - `[~]` for obsolete/cancelled tasks
  - `[?]` for tasks in question
- Supports `.md` and `.xit` file extensions.
- Custom color theme for enhanced readability.
# markdownxit

![markdownxit](https://github.com/janzheng/markdownxit/blob/master/sample.png?raw=true)

**markdownxit** is a custom Visual Studio Code extension that provides syntax highlighting and token color customization for Markdown files with task-specific features.

This is based on [x]it! at https://xit.jotaen.net/ and injects a splash of colors into markdown styling.


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
- Supports Github-style markdown task lists, e.g. `- [x] do something`.
- Custom color theme for enhanced readability.

## Tasks & Roadmap

- [ ] Post to the [x]it! discussion forum: https://github.com/jotaen/xit/discussions
- [@] Enjoy not working on this anymore
- [x] Develop VS Code extension for XIT support
- [x] Create GitHub repository for the extension
- [x] Test extension functionality locally
- [x] Package extension as .vsix file
- [x] Successfully install and test .vsix file
- [?] Publish extension to VS Code Marketplace
    - Research submission requirements
    - Prepare necessary documentation
    - Set up publisher account if needed
- [ ] Add support for Github-style markdown task lists
- [?] Gather user feedback and implement improvements
- [?] Consider adding more features (e.g., custom XIT symbols, project-wide task tracking)




## License

MIT


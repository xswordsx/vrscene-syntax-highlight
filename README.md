# vrscene-syntax-highlight

[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/xswordsx.vrscene-syntax-highlight?label=vscode)](https://marketplace.visualstudio.com/items?itemName=xswordsx.vrscene-syntax-highlight)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/xswordsx/vrscene-syntax-highlight)

vrscene-syntax-highlight adds syntax highlighting for Chaos'
vrscene files.

Initial syntax file taken from
[Aloiseau/VraySublime](https://github.com/Aloiseau/VraySublime)

## Features

![Highlight overview](images/example.gif)

## Installation

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

    ext install xswordsx.vrscene-syntax-highlight

## Known Issues

* Some property values are misinterpreted as keys.
* Some plugin names and properties are missing.
* Auto-completion is not context-aware (i.e. it does not
  know which properties are supported for each plugin).

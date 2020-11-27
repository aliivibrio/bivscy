# Bivscy

Bivscy is a Visual Studio Code extension which provides a language mode for game data used in the
Bitsy Game Maker (https://ledoux.itch.io/bitsy).

![screenshot of highlighted Bitsy game data](https://raw.githubusercontent.com/aliivibrio/bivscy/main/images/bivscy-screen.png)

## Features

* Syntax highlighting for Bitsy game data files
* Some invalid syntax is highlighted as invalid

## Known Issues

* Dialogs are rendered as block text; there is no highlighting of the structure within a dialog.
* Hack-specific syntax is not handled
* `VAR` values not highlighted as constants/strings
* Sections are delimited by empty lines, which doesn't work with the simple folding/unfolding mechanism for Visual Studio Code extensions

## Release Notes

### 0.0.1

Initial release, with basic syntax highlighting.

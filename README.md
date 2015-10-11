# Awesome Atom [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of delightful Atom packages and resources. For more awesomeness, check out [awesome](https://github.com/sindresorhus/awesome).

## Table of Content

- [Syntax](#syntax)
- [Lint](#lint)
- [Themes](#themes)
 - [Atom Material UI](#atom-material-ui)
 - [Seti UI](#seti-ui)
- [Uncategorized](#uncategorized)
 - [Sort lines](#sort-lines)
 - [Pigments](#pigments)
 - [Fonts](#fonts)
 - [Advanced New File](#advanced-new-file)
 - [Advanced Open File](#advanced-open-file)
 - [File Icons](#file-icons)
 - [Pane Layout](#pane-layout)
 - [Pane Move](#pane-move)
 - [Highlight Line](#highlight-line)
 - [Editor Config](#editor-config)
 - [Duplicate Selection](#duplicate-selection)
 - [Beautify](#beautify)
 - [Minimap](#minimap)
 - [Toggle Quotes](#toggle-quotes)
 - [Save Session](#save-session)
 - [Sync Settings](#sync-settings)
 - [Atom Terminal](#atom-terminal)
 - [Jumpy](#jumpy)
 - [TernJS](#ternjs)
 - [Emmet](#emmet)
 - [Merge Conflicts](#merge-conflicts)
 - [iMDone](#imdone)

## Syntax

Language packages extend the editor with syntax highlighting and/or
snippets for a specific language or file format.

 - [Angular](https://atom.io/packages/angularjs) — adds syntax highlighting and snippets
 - [Atom Material Syntax](https://atom.io/themes/atom-material-syntax)
 - [Dockerfile](https://atom.io/packages/language-docker)
 - [React](https://atom.io/packages/react) — React.js (JSX) language support, indentation, snippets, auto completion, reformatting
- [Seti Syntax](https://atom.io/themes/seti-syntax) 
- [Stylus](https://atom.io/packages/stylus)

## Lint

In case the awesome nirvana that is linting has not yet been unleashed upon you:
> lint was the name originally given to a particular program that flagged some suspicious and non-portable constructs (likely to be bugs) in C language source code. The term is now applied generically to tools that flag suspicious usage in software written in any computer language.

To enable linting, you'll need the general [linter](https://atom.io/packages/linter) which acts as a provider to enable the functionality in the language-specific linters below.

 - [C++](https://atom.io/packages/linter-cpplint) — cpplint
 - [JavaScript](https://atom.io/packages/linter-eslint) — eslint
 - [Python](https://atom.io/packages/linter-pylama) — pylama
 - [Stylus](https://atom.io/packages/linter-stylint) — stylint

![atom-linter](https://camo.githubusercontent.com/70b6e697c9d793642414b4ea6d08dbb9678877b3/687474703a2f2f672e7265636f726469742e636f2f313352666d6972507a322e676966)

## Themes
Theme packages can change your atom editor's appearance.

#### [Atom Material UI](https://atom.io/themes/atom-material-ui)

![](https://raw.githubusercontent.com/silvestreh/atom-material-ui/master/screenshot.png)

#### [Seti UI](https://atom.io/themes/seti-ui)
![](https://raw.githubusercontent.com/jesseweed/seti-ui/master/screenshot.png)

## Uncategorized

#### [Sort Lines](https://atom.io/packages/sort-lines)
> Sorts your lines. Never gets tired.

![](https://camo.githubusercontent.com/59de82a667ea690b778abaa5ba8a407f8659ebb3/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f323938382f313739363839312f38356536396666322d366139332d313165332d383961632d3331393237663630343539322e676966)

#### [Pigments](https://atom.io/packages/pigments)
> A package to display colors in project and files.

![](https://github.com/abe33/atom-pigments/raw/master/resources/pigments.gif?raw=true)

#### [Fonts](https://atom.io/packages/fonts)
> Lots of monospace fonts.

#### [Advanced New File](https://atom.io/packages/advanced-new-file)
> Create multiple files and directories by typing a relative path.
> This package is currently unmaintained. It's advisable to use [Advanced Open File](#advanced-open-file) instead.

![](https://cloud.githubusercontent.com/assets/3289225/5792505/81f41c72-9f1b-11e4-9085-38cfb832383c.gif)

#### [Advanced Open File](https://atom.io/packages/advanced-open-file)
> Helps Atom users to open files and folders easily. It can also creates new files and folders if they don't currently exist.

![](http://osmose.github.io/advanced-open-file/demo.gif)

#### [File Icons](https://atom.io/packages/file-icons)
> Adds file specific icons to atom for improved visual grepping. Works with Tree View and Fuzzy Finder and Tabs.

#### [Editor Config](https://atom.io/packages/editorconfig)
> [EditorConfig](http://editorconfig.org) helps developers maintain consistent coding styles between different editors

![atom-editor-config](https://f.cloud.github.com/assets/170270/2327994/dfe40cb4-a3f6-11e3-862f-894999973373.png)

#### [Duplicate Selection](https://atom.io/packages/duplicate-line-or-selection)
> Duplicates the selection if there is one, otherwise, duplicates the line.

#### [Beautify](https://atom.io/packages/atom-beautify)
> [Beautify](https://github.com/einars/js-beautify)
HTML (including [Handlebars](http://handlebarsjs.com/)),
CSS (including [Sass](http://sass-lang.com/) and [LESS](http://lesscss.org/)),
JavaScript, and much more in Atom.

#### [Minimap](https://atom.io/packages/minimap)
> A preview of the full source code.

#### [Toggle Quotes](https://atom.io/packages/toggle-quotes)
> Quickly toggle between single and double quotes.

#### [Save Session](https://atom.io/packages/save-session)
> Save Session is designed to reopen your last session in Atom. It automatically saves all file's contents in the background so you don't have to worry as much about losing an important file.

![preview](https://raw.githubusercontent.com/mpeterson2/save-session/master/preview.gif)

#### [Sync Settings](https://atom.io/packages/sync-settings)
> Synchronize package settings, keymap and installed packages across Atom instances.

#### [Atom Terminal](https://atom.io/packages/atom-terminal)
>  Launch terminal app on current file's directory with "Ctrl-Shift-T" in Atom.

![](https://raw.githubusercontent.com/karan/atom-terminal/master/terminal.gif)

#### [Jumpy](https://atom.io/packages/jumpy)
> An Atom package that creates dynamic hotkeys to jump around files across visible panes.

![](https://raw.githubusercontent.com/DavidLGoldberg/jumpy/master/_images/jumpy.gif)

#### [TernJS](https://atom.io/packages/atom-ternjs)
> Javascript code intelligence for atom with tern.js and autocomplete-plus.

#### [Emmet](https://atom.io/packages/emmet)
> Plugin which greatly improves HTML and CSS writing. Shortcuts can expand to complete set of HTML or CSS selectors.

#### [Merge Conflicts](https://atom.io/packages/merge-conflicts)
> Resolve your git merge conflicts in Atom.

#### [iMDone](https://atom.io/packages/imdone-atom)
> A task-board for TODOs, FIXMEs, HACKs, etc in your code.

![](https://cloud.githubusercontent.com/assets/441774/9805863/757d5532-5814-11e5-8759-4196bd92c822.gif)

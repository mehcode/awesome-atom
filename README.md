# Awesome Atom [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of delightful Atom packages and resources. For more awesomeness, check out [awesome](https://github.com/sindresorhus/awesome).

## Table of Content

- [Syntax](#syntax)
- [Lint](#lint)
- [Build](#build)
- [Extensions](#extensions)
  - [Nuclide](#nuclide)
- [Themes](http://enrmarc.github.io/atom-theme-gallery/)
- [Collaboration](#collaboration)
  - [CodeSideStory](#codesidestory)
- [Uncategorized](#uncategorized)
  - [Nuclide](#nuclide)
  - [Advanced Open File](#advanced-open-file)
  - [Atom Reverser](#atom-reverser)
  - [Atom Terminal](#atom-terminal)
  - [Autocomplete module import](#autocomplete-module-import)
  - [Beautify](#beautify)
  - [Code Peek](#code-peek)
  - [Color Picker](#color-picker)
  - [Copy Paste](#copy-paste)
  - [CSS Declaration Sorter](#css-declaration-sorter)
  - [Duplicate Selection](#duplicate-selection)
  - [Editor Config](#editor-config)
  - [Emmet](#emmet)
  - [File Icons](#file-icons)
  - [Fonts](#fonts)
  - [Git Time Machine](#git-time-machine)
  - [html-to-css](#html-to-css)
  - [iMDone](#imdone)
  - [Jumpy](#jumpy)
  - [Merge Conflicts](#merge-conflicts)
  - [Minimap](#minimap)
  - [Pigments](#pigments)
  - [Project Plus](#project-plus)
  - [Sort lines](#sort-lines)
  - [Sorter](#sorter)
  - [Sync Settings](#sync-settings)
  - [PlatformIO IDE Terminal](#platformio-ide-terminal)
  - [TernJS](#ternjs)
  - [Test Navigator](#test-navigator)
  - [Themer](#themer)
  - [Toggle Quotes](#toggle-quotes)

## Syntax

Language packages extend the editor with syntax highlighting and/or
snippets for a specific language or file format.

 - [Angular](https://atom.io/packages/angularjs)
 - [Vue.js](https://atom.io/packages/language-vue)
 - [Dockerfile](https://atom.io/packages/language-docker)
 - [Markdown](https://atom.io/packages/language-markdown)
 - [React](https://atom.io/packages/react)
 - [Stylus](https://atom.io/packages/stylus)
 - [Pug](https://atom.io/packages/language-pug)
 - [Tcl](https://atom.io/packages/language-tcl)
 - [TypeScript](https://atom.io/packages/atom-typescript)

## Lint

In case the awesome nirvana that is linting has not yet been unleashed upon you:
> lint was the name originally given to a particular program that flagged some suspicious and non-portable constructs (likely to be bugs) in C language source code. The term is now applied generically to tools that flag suspicious usage in software written in any computer language.

To enable linting, you'll need the general [linter](https://atom.io/packages/linter) which provides the interface for the provider plugins for specific languages. The full list of current plugins can be found at [atomlinter.github.io](http://atomlinter.github.io/), a few examples being:

 - C++
   - [linter-clang](https://atom.io/packages/linter-clang)
   - [linter-cppcheck](https://atom.io/packages/linter-cppcheck)
   - [linter-gcc](https://atom.io/packages/linter-gcc) - on-the-fly linting!
   - [linter-cpplint](https://atom.io/packages/linter-cpplint) - checks against google style guide
 - [CSS](https://atom.io/packages/linter-stylelint) — stylelint
 - [JavaScript](https://atom.io/packages/linter-eslint) — eslint
 - [Python](https://atom.io/packages/linter-pylama) — pylama
 - [SASS](https://atom.io/packages/linter-sass-lint) — sass-lint
 - [Stylus](https://atom.io/packages/linter-stylint) — stylint
 - [TypeScript](https://atom.io/packages/linter-tslint) - tslint

 ![atom-linter](https://camo.githubusercontent.com/70b6e697c9d793642414b4ea6d08dbb9678877b3/687474703a2f2f672e7265636f726469742e636f2f313352666d6972507a322e676966)

## Build

To enable building, you'll need the general [build](https://atom.io/packages/build) which provides the interface for the provider plugins for specific languages and adds integrates with [lint](#lint). The full list of current plugins can be found at [atombuild.github.io](http://atombuild.github.io/), a few examples being:

 - [AppleScript](https://atom.io/packages/build-applescript) — oscompile
 - [C/C++/Objective C](https://atom.io/packages/build-xcodebuild) — xcodebuild
 - [CoffeeScript](https://atom.io/packages/build-coffee) - coffee
 - [GNU Make](https://github.com/AtomBuild/atom-build-make) - make
 - [Sass](https://atom.io/packages/build-sass) — sass
 - [TypeScript](https://atom.io/packages/build-tsc) - tsc

 ![atom-build](https://camo.githubusercontent.com/ca10be645c7a2024dddc550466e67d692fb411ed/68747470733a2f2f6e6f7365676c69642e6769746875622e696f2f746172676574732d6d616b652e676966)

## Extensions

#### [Nuclide](https://nuclide.io/)
> An open IDE for web and native mobile development, built on top of Atom maintained by [Facebook](https://github.com/facebook/nuclide).

![](https://nuclide.io/static/images/docs/promo-hack.png)

## Collaboration

#### [CodeSideStory](https://atom.io/packages/codesidestory-atom)
> An Atom/Slack integration to start conversations about code right from the editor. Record screens and archive it right next to the line number to provide more context to your code.

![](https://storage.googleapis.com/codesidestory/static/media/atom_ss.c29b4b0b.png)

## Uncategorized

#### [Advanced Open File](https://atom.io/packages/advanced-open-file)
> Helps Atom users to open files and folders easily. It can also creates new files and folders if they don't currently exist.

![](http://osmose.github.io/advanced-open-file/demo.gif)

#### [Atom Reverser](https://atom.io/packages/atom-reverser)
> Reverses your current selections; e.g. `false` to `true`

![Atom Reverser in action](https://i.imgur.com/YawGVsN.gif)

#### [Atom Terminal](https://atom.io/packages/atom-terminal)
> Launch terminal app on current file's directory with "Ctrl-Shift-T" in Atom.

![](https://raw.githubusercontent.com/karan/atom-terminal/master/terminal.gif)

#### [Autocomplete module import](https://atom.io/packages/autocomplete-module-import)
> Search & install npm packages from import/require statements by [Algolia](https://www.algolia.com/)

![](https://camo.githubusercontent.com/53350e9c6d303f60101e1644605fe62f529e45f2/687474703a2f2f672e7265636f726469742e636f2f643576695542385859372e676966)

#### [Beautify](https://atom.io/packages/atom-beautify)
> [Beautify](https://github.com/beautify-web/js-beautify)
HTML (including [Handlebars](http://handlebarsjs.com/)),
CSS (including [Sass](http://sass-lang.com/) and [LESS](http://lesscss.org/)),
JavaScript, and much more in Atom.

#### [Code Peek](https://atom.io/packages/code-peek)
> Quickly peek and edit functions in separate files from the context of your current editor.

![Code Peek Demo](https://github.com/DFreds/code-peek-atom/blob/master/code-peek.gif?raw=true)

#### [Color Picker](https://atom.io/packages/color-picker)
> Color picker that supports HEX, HEXa, RGB, RGBa, HSL, HSLa, HSV, HSVa, VEC3, VEC4 – and is able to convert between the formats. It also inspects Sass and LESS color variables.

![Color Picker in action](https://github.com/thomaslindstrom/color-picker/raw/master/preview.gif)

#### [Copy Paste](https://atom.io/packages/copy-paste)
> Types in your code for your from the clipboard/buffer. Simply copy the code and hit the shortcut to watch your code being typed. Copy paste is ideal for screencasts and online courses.

#### [CSS Declaration Sorter](https://atom.io/packages/css-declaration-sorter)
> Sorts your CSS, Less or Sass declarations in Atom, never gets tired. You can choose from various ready-made orders to keep your CSS tidy.

![CSS Declaration Sorter Demo](https://github.com/Siilwyn/css-declaration-sorter-atom/raw/master/show-off.gif)

#### [Duplicate Selection](https://atom.io/packages/duplicate-line-or-selection)
> Duplicates the selection if there is one, otherwise, duplicates the line.

#### [Editor Config](https://atom.io/packages/editorconfig)
> [EditorConfig](http://editorconfig.org) helps developers maintain consistent coding styles between different editors

![atom-editor-config](https://f.cloud.github.com/assets/170270/2327994/dfe40cb4-a3f6-11e3-862f-894999973373.png)

#### [Emmet](https://atom.io/packages/emmet)
> Plugin which greatly improves HTML and CSS writing. Shortcuts can expand to complete set of HTML or CSS selectors.

#### [File Icons](https://atom.io/packages/file-icons)
> Adds file specific icons to atom for improved visual grepping. Works with Tree View and Fuzzy Finder and Tabs.

#### [Fonts](https://atom.io/packages/fonts)
> Lots of monospace fonts.

#### [Git Time Machine](https://atom.io/packages/git-time-machine)
> It shows visual plot of commits to the current file over time and you can click on it on the timeplot or hover over the plot and see all of the commits for a time range.

![git-time-machine](https://i.github-camo.com/62085307dccead1c2f5efdf4d7a40f9cdb777b93/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6c6974746c656265652f6769742d74696d652d6d616368696e652f6d61737465722f7265736f75726365732f74696d656d616368696e652e676966)

#### [html-to-css](https://atom.io/packages/html-to-css)
> Generates CSS boilerplate based on the selected HTML. Supports CSS, SCSS, Sass, LESS, BEM, JSX.

![html-to-css](https://camo.githubusercontent.com/b164c4b7b244006a7bcf7442d8c4b0812e4edcd0/687474703a2f2f64726163756c2e6b696c6c2e706c2f2537456172642f68746d6c746f6373732e676966)

#### [iMDone](https://atom.io/packages/imdone-atom)
> A task-board for TODOs, FIXMEs, HACKs, etc in your code.

![](https://cloud.githubusercontent.com/assets/441774/9805863/757d5532-5814-11e5-8759-4196bd92c822.gif)

#### [Jumpy](https://atom.io/packages/jumpy)
> An Atom package that creates dynamic hotkeys to jump around files across visible panes.

![](https://raw.githubusercontent.com/DavidLGoldberg/jumpy/master/_images/jumpy.gif)

#### [Merge Conflicts](https://atom.io/packages/merge-conflicts)
> Resolve your git merge conflicts in Atom.

![](https://raw.github.com/smashwilson/merge-conflicts/master/docs/conflict-resolution.gif)

#### [Minimap](https://atom.io/packages/minimap)
> A preview of the full source code.

#### [Pigments](https://atom.io/packages/pigments)
> A package to display colors in project and files.

![](http://abe33.github.io/atom-pigments/pigments.gif?raw=true)

#### [Project Plus](https://atom.io/packages/project-plus)
> Simply awesome project management in Atom.

![](https://raw.githubusercontent.com/mehcode/atom-project-plus/master/project-plus.gif)

#### [Sort Lines](https://atom.io/packages/sort-lines)
> Sorts your lines. Never gets tired.

![](https://camo.githubusercontent.com/59de82a667ea690b778abaa5ba8a407f8659ebb3/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f323938382f313739363839312f38356536396666322d366139332d313165332d383961632d3331393237663630343539322e676966)

#### [Sorter](https://atom.io/packages/sorter)
> Sorts Lines, JSON, CSS, HTML, CSV. Restores semicolons. Respects indentation. Supports natural sort.

#### [Sync Settings](https://atom.io/packages/sync-settings)
> Synchronize package settings, keymap and installed packages across Atom instances.

#### [PlatformIO IDE Terminal](https://atom.io/packages/platformio-ide-terminal)
> A terminal package for Atom, complete with themes, API and more for PlatformIO IDE.
> This is a maintained (as of 2017-07-13) fork of terminal-plus.  

![](https://raw.githubusercontent.com/jeremyramin/terminal-plus/master/resources/demo.gif)

#### [TernJS](https://atom.io/packages/atom-ternjs)
> Javascript code intelligence for atom with tern.js and autocomplete-plus.

### [Test Navigator](https://atom.io/packages/test-navigator)
> Quickly navigate between test and implementation files.

![Test Navigator Demo](https://github.com/DFreds/test-navigator-atom/blob/master/test-navigator.gif?raw=true)

#### [Themer](https://themer.mjswensen.com)
> Generate Atom syntax/UI theme packages (and matching themes for your other tools) from your favorite colors.

#### [Toggle Quotes](https://atom.io/packages/toggle-quotes)
> Quickly toggle between single and double quotes.

#### [Tree View Search Bar](https://atom.io/packages/tree-view-search-bar)
> Quick look in tree view.

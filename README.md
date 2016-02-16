# Syntax Highlighting for [PostCSS]

<img src="https://postcss.github.io/postcss/logo.svg" title="Philosopher’s stone, logo of PostCSS" align="right" width="95" height="95">

PostCSS syntax highlighting for Sublime Text. This package is fork of [Syntax Highlighting for Sass] by @P233 with few changes making this more useful rather Sass package:

* Using SCSS syntax highlighting. This covers most of PostCSS possible syntax. Removed `Sass` syntax highlighting and all Sass completions;
* Support for CSS custom properties `var(--variable-name)` and `--variable-name`;
* Automatic enable syntax highlighting by `*.pcss` and `*.postcss` file extensions;
* Standard CSS comments (`/* comment */`) instead of Sass single line comments (`// comment`).

There is a lot of possible improvements can be made to this syntax, but frankly, I don't understand in syntax files much and hope for the help of the community.

## Installation

Install with [Package Control].

Open the Command Palette `Cmd+Shift+P` (OS X) or `Ctrl+Shift+P` (Linux/Windows) and select “Package Control: Install Package”, then search for `Syntax Highlighting for PostCSS`.

[PostCSS]: https://github.com/postcss/postcss
[Syntax Highlighting for Sass]: https://github.com/P233/Syntax-highlighting-for-Sass
[Package Control]: https://packagecontrol.io/

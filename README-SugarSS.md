# Syntax Highlighting for [SugarSS]

<img src="http://postcss.github.io/sugarss/logo.svg" title="SugarSS logo by Maria Keller" align="right" width="95" height="95">

[SugarSS] syntax highlighting for Sublime Text. This package is a fork of [Syntax-highlighting-for-PostCSS] by @hudochenkov:

* Using SSS syntax highlighting. This covers all of SugarSS syntax, which is covered by Atom version.
* Automatic enable syntax highlighting by `*.sss` file extensions;

Feel free to improve the syntax, I'm don't know much about syntax stuff, and managed to do this work by randomly slapping keyboard.

## Examples
Indent-based CSS syntax for [PostCSS].

```sass
a
  color: blue

.multiline,
.selector
  box-shadow: 1px 0 9px rgba(0, 0, 0, .4),
              1px 0 3px rgba(0, 0, 0, .6)

// Mobile
@media (max-width: 400px)
  .body
    padding: 0 10px
```

## Installation

Install with [Package Control].

Open the Command Palette `Cmd+Shift+P` (OS X) or `Ctrl+Shift+P` (Linux/Windows) and select “Package Control: Install Package”, then search for `Syntax Highlighting for SugarSS`.

[SugarSS]: https://github.com/postcss/sugarss
[Syntax-highlighting-for-PostCSS]: https://github.com/hudochenkov/Syntax-highlighting-for-PostCSS
[Package Control]: https://packagecontrol.io/

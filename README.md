# Jade (now Pug) Snippets for Visual Studio Code

> Provides a base set of snippets for Jade (now Pug).

## Install

  * Press `F1` and select `Extensions: Install Extensions`.
  * Search for and select `jade snippets`.

See the [extension installation guide](https://code.visualstudio.com/docs/editor/extension-gallery) for details.

## Supported languages

  * Pug
  * Jade

## Snippets

### Elements

```jade
// a|
a(href="#", title="title").class $0

// figure|
figure
    img(src="source", alt="alt").class
    figcaption $0
```

Snippet for `img` deleted in *1.0.0* version. Emmet works fine with Pug (ex. Jade). See [CheatSheet](http://docs.emmet.io/cheat-sheet/).

### Attributes

```jade
// Attributes for styling and controlling
class| → class=""$0
id|    → id=""$0

// Common attributes
data| → data-*=""$0
aria| → aria-*=""$0
role| → role=""$0

// Attributes for form settings
method| → method=""$0
action| → action=""$0

// Attributes for form elements
type|        → type=""$0
name|        → name=""$0
placeholder| → placeholder=""$0
value|       → value=""$0
```

### Scripts

```jade
//script|
script(src="file.js")
$0

// script:inline|
script.
    $1
$0

// script:include|
script
    include ./file.js
$0
```

### Styles

```jade
// link|
link(href="file.css", rel="stylesheet")
$0

// style|
style.
    $1
$0

// style:include|
style
    include ./file.css
$0
```

### Syntax

```jade
// var|
- var name = $0

// block|
block name
    $1
$0

// case|
case variable
    when condition
        code
    default
        code
$0

// each|
each val in []
    $1
$0

// while|
while condition
    $1
$0

// extends|
extends ./file.jade
$0

// include|
include ./file.jade
$0

// mixin|
mixin name(vars)
    $1
$0

// mixin:call|
```jade
+name(attrs)(attrs)
$0
```

## Changelog

See the [Releases section of our GitHub project](https://github.com/mrmlnc/vscode-jade-snippets/releases) for changelogs for each release version.

## License

This software is released under the terms of the MIT license.

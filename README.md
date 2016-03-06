# Jade Snippets for Visual Studio Code

## Installation

To install, press `F1` and select `Extensions: Install Extensions` and then search for and select `jade snippets`.

## Snippets -> Elements

#### a

```jade
a.class(href="#", title="title") $0
```

#### img

```jade
img.class(src="file", alt="alt")
$0
```

## Snippets -> Script

#### script

```jade
script(src="file.js")
$0
```

#### script:inline

```jade
script.
    $1
$0
```

#### script:include

```jade
script
    include ./file.js
$0
```

## Snippets -> Style

#### link

```jade
link(href="file.css", rel="stylesheet")
$0
```

#### style

```jade
style.
    $1
$0
```

#### style:include

```jade
style
    include ./file.css
$0
```

## Snippets -> syntax

#### var

```jade
- var name = $0
```

#### block

```jade
block name
    $1
$0
```

#### case

```jade
case variable
    when condition
        code
    default
        code
$0
```

#### each

```jade
each val in []
    $1
$0
```

#### while

```jade
while condition
    $1
$0
```

#### extends

```jade
extends ./file.jade
$0
```

#### include

```jade
include ./file.jade
$0
```

#### mixin

```jade
mixin name(vars)
    $1
$0
```

#### mixin:call

```jade
+name(attrs)(attrs)
$0
```


## License

This software is released under the terms of the MIT license.

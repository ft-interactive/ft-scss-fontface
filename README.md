# FT SCSS Font Faces

Tiny SASS lib used as a building block to creating larger FT SASS things. This is just the font-faces.

By default all the @font-face declarations are turned off so you are in control when to use them. To turn them on simply set the `$ft-include-fontfaces` variable to true before importing this library.

## Installation

```bash
$ bower install -S https://github.com/ft-interactive/ft-scss-fontface.git
```

## Usage

```scss
$ft-include-fontfaces: true;

@import "ft-scss-fontface/main";
```


# Cyanotype CSS

A convenient alternative to CSS resets.

## Features

* Ensures consistency across browsers
* Prevents the re-setting user agent styles
* Ensures consistently set margins only downward

## Installation

```bash
$ npm install cyanotype.css
```

## Usage

HTML:

```html
<link href="/path/to/cyanotype.css" rel="stylesheet">
```

CSS:

```css
@import "/path/to/cyanotype.css";
```

## Utility classes

### `.screen-reader-only` class

For HTML elements that should remain in the document but should be visually hidden, specifies this class:

```html
<p class="screen-reader-only">Screen reader only text</p>
```

## License

[MIT](LICENSE)

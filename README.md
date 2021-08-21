# mat-colors-css
This repository contains a stylesheet that has all of the Material Design colors converted to CSS variables.

## Basic Use
To use the stylesheet, download the CSS file and link to it:
`<link rel="stylesheet" href="mat-colors.css">`.

To use a particular color (for example, Blue A700), format your element as such:

```
div {

	background-color: var(--clr-mat-blue-a700);
}
```

...which will use the `#2962ff` color.


## Light and Dark Variants
To use a light or dark variant of a color, simply add "l" or "d" to the end of the variable name. For example: `var(--clr-mat-blue-a700l)` will represent `#768fff`.

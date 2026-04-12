# under

under is a modern typeface inspired by classic fonts like univers, helvetica, and neue haas grotesk. it's designed to be adaptive, fluid, and purpose-built for digital interfaces.

## usage

include the font from the cdn:

```html
<link rel="preconnect" href="https://weareunderdesign.github.io">
<link rel="stylesheet" href="https://weareunderdesign.github.io/under/under.css">
```

add to your css:

```css
:root {
  font-family: 'under', sans-serif;
}

@supports (font-variation-settings: normal) {
  :root {
    font-family: 'under var', sans-serif;
  }
}
```

## features

- variable font with extensive weight range (hairline to black)
- auto-adjusting line height, letter spacing, and sizing
- optimized for 16px rendering
- condensed versions available
- opentype features: contextual alternates, tabular numbers, fractions, superscript/subscript, ligatures, and more
- 13 character variant options (cv01-cv13)

## available weights

under is available as a variable font or as individual font files:

display: hairline, thin, light, regular, medium, bold, black
text: thin, light, regular, medium, bold, black
micro: light, regular, medium, bold

condensed versions available for all categories.

## license

licensed under the sil open font license 1.1. free for commercial and personal use. can be modified and redistributed. see [license](license) for details.
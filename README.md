ncolorpalette-palettes
======================

Palettes (pixel datas) that power the ncolorpalette and friends. Currently includes 4-color Gameboy, and some palettes inspired by Dragon Ball Z and Kirby's Dreamland.

Usage
-----

```js
var palettes = require('ncolorpalettes-palettes');

console.log(palettes.gameboy);
{
  name: 'Gameboy',
  pixels: [
    0, 60, 16, 255,
    6, 103, 49, 255,
    123, 180, 0, 255,
    138, 196, 0, 255
  ]
}
```
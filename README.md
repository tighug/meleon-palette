# Meleon Palette

Color Palette for Material Design

## Features

- Easily use Color Palette for Material Design
- Also support TypeScript

## Installation

```bash
# with npm
npm install @tighug/meleon-palette

# or with yarn
yarn add @tighug/meleon-palette
```

## Usage

Read module :

```js
// for ES6
import { red } from "@tighug/meleon-palette";

// or for CommonJS
const { red } = require("@tighug/meleon-palette");
```

Now `red` has all color variations :

```ts
console.log(red.lighten5); // #ffebee
console.log(red.lighten4); // #ffcdd2
console.log(red.lighten3); // #ef9a9a
console.log(red.lighten2); // #e57373
console.log(red.lighten1); // #ef5350
console.log(red.base); // #f44336
console.log(red.darken1); // #e53935
console.log(red.darken2); // #d32f2f
console.log(red.darken3); // #c62828
console.log(red.darken4); // #b71c1c
console.log(red.accent1); // #ff8a80
console.log(red.accent2); // #ff5252
console.log(red.accent3); // #ff1744
console.log(red.accent4); // #d50000
```

## Palette

Each base color has variations from `lighten5` to `darken4`.

- `red`
- `pink`
- `purple`
- `deepPurple`
- `indigo`
- `blue`
- `lightBlue`
- `cyan`
- `teal`
- `green`
- `lightGreen`
- `lime`
- `yellow`
- `amber`
- `orange`
- `deepOrange`
- `brown`
- `grey`
- `blueGrey`

Each mono color have only one value.

- `black` : `"#000000"`
- `white` : `"#ffffff"`

Each text color have `primary`, `secondary`, `disabled` and `dividers`.

- `darkText`
- `lightText`

Each icon color have `active` and `inactive`.

- `darkIcons`
- `lightIcons`

## License

[MIT](./LICENSE)

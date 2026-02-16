# css-dimension-utilities

Functional CSS for dimension-utilities

## Filesize

| File | Size |
|------|------|
| `dist/dimension-utilities.css` | 150 bytes |
| `dist/dimension-utilities.min.css` | 108 bytes (87 Gzipped) |

## Install

```sh
npm install css-dimension-utilities
```

## Usage

### Import

```css
@import "css-dimension-utilities";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-dimension-utilities/dist/dimension-utilities.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-dimension-utilities/dist/dimension-utilities.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.wrap` | `width: auto;   display: block;` |
| `.fill` | `width: auto;   display: block;   overflow: hidden;` |
| `.dbf` | `width: 100%;   display: block;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.wrap-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/dimension-utilities.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/dimension-utilities.css` — formatted
- `dist/dimension-utilities.min.css` — minified

## License

MIT

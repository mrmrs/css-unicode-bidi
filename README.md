# css-unicode-bidi

Functional CSS for unicode-bidi

## Filesize

| File | Size |
|------|------|
| `dist/unicode-bidi.css` | 1477 bytes |
| `dist/unicode-bidi.min.css` | 1085 bytes (231 Gzipped) |

## Install

```sh
npm install css-unicode-bidi
```

## Usage

### Import

```css
@import "css-unicode-bidi";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-unicode-bidi/dist/unicode-bidi.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-unicode-bidi/dist/unicode-bidi.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ub-norm` | `unicode-bidi: normal;` |
| `.ub-embed` | `unicode-bidi: embed;` |
| `.ub-iso` | `unicode-bidi: isolate;` |
| `.ub-bidi-override` | `unicode-bidi: bidi-override;` |
| `.ub-iso-override` | `unicode-bidi: isolate-override;` |
| `.ub-pt` | `unicode-bidi: plaintext;` |
| `.ub-i` | `unicode-bidi: inherit;` |
| `.ub-norm-s` | `unicode-bidi: normal;` |
| `.ub-embed-s` | `unicode-bidi: embed;` |
| `.ub-iso-s` | `unicode-bidi: isolate;` |
| `.ub-bidi-override-s` | `unicode-bidi: bidi-override;` |
| `.ub-iso-override-s` | `unicode-bidi: isolate-override;` |
| `.ub-pt-s` | `unicode-bidi: plaintext;` |
| `.ub-i-s` | `unicode-bidi: inherit;` |
| `.ub-norm-m` | `unicode-bidi: normal;` |
| `.ub-embed-m` | `unicode-bidi: embed;` |
| `.ub-iso-m` | `unicode-bidi: isolate;` |
| `.ub-bidi-override-m` | `unicode-bidi: bidi-override;` |
| `.ub-iso-override-m` | `unicode-bidi: isolate-override;` |
| `.ub-pt-m` | `unicode-bidi: plaintext;` |
| `.ub-i-m` | `unicode-bidi: inherit;` |
| `.ub-norm-l` | `unicode-bidi: normal;` |
| `.ub-embed-l` | `unicode-bidi: embed;` |
| `.ub-iso-l` | `unicode-bidi: isolate;` |
| `.ub-bidi-override-l` | `unicode-bidi: bidi-override;` |
| `.ub-iso-override-l` | `unicode-bidi: isolate-override;` |
| `.ub-pt-l` | `unicode-bidi: plaintext;` |
| `.ub-i-l` | `unicode-bidi: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ub-norm-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/unicode-bidi.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/unicode-bidi.css` — formatted
- `dist/unicode-bidi.min.css` — minified

## License

MIT

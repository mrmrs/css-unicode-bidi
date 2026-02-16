# css-unicode-bidi

Functional CSS for unicode-bidi

## Filesize

| File | Size |
|------|------|
| `dist/unicode-bidi.css` | 2219 bytes |
| `dist/unicode-bidi.min.css` | 1661 bytes (305 Gzipped) |

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
| `.ub-normal` | `unicode-bidi: normal;` |
| `.ub-embed` | `unicode-bidi: embed;` |
| `.ub-isolate` | `unicode-bidi: isolate;` |
| `.ub-bidi-override` | `unicode-bidi: bidi-override;` |
| `.ub-isolate-override` | `unicode-bidi: isolate-override;` |
| `.ub-plaintext` | `unicode-bidi: plaintext;` |
| `.ub-initial` | `unicode-bidi: inherit;` |
| `.ub-revert` | `unicode-bidi: revert;` |
| `.ub-revert-layer` | `unicode-bidi: revert-layer;` |
| `.ub-unset` | `unicode-bidi: unset;` |
| `.ub-normal-s` | `unicode-bidi: normal;` |
| `.ub-embed-s` | `unicode-bidi: embed;` |
| `.ub-isolate-s` | `unicode-bidi: isolate;` |
| `.ub-bidi-override-s` | `unicode-bidi: bidi-override;` |
| `.ub-isolate-override-s` | `unicode-bidi: isolate-override;` |
| `.ub-plaintext-s` | `unicode-bidi: plaintext;` |
| `.ub-initial-s` | `unicode-bidi: inherit;` |
| `.ub-revert-s` | `unicode-bidi: revert;` |
| `.ub-revert-layer-s` | `unicode-bidi: revert-layer;` |
| `.ub-unset-s` | `unicode-bidi: unset;` |
| `.ub-normal-m` | `unicode-bidi: normal;` |
| `.ub-embed-m` | `unicode-bidi: embed;` |
| `.ub-isolate-m` | `unicode-bidi: isolate;` |
| `.ub-bidi-override-m` | `unicode-bidi: bidi-override;` |
| `.ub-isolate-override-m` | `unicode-bidi: isolate-override;` |
| `.ub-plaintext-m` | `unicode-bidi: plaintext;` |
| `.ub-initial-m` | `unicode-bidi: inherit;` |
| `.ub-revert-m` | `unicode-bidi: revert;` |
| `.ub-revert-layer-m` | `unicode-bidi: revert-layer;` |
| `.ub-unset-m` | `unicode-bidi: unset;` |
| `.ub-normal-l` | `unicode-bidi: normal;` |
| `.ub-embed-l` | `unicode-bidi: embed;` |
| `.ub-isolate-l` | `unicode-bidi: isolate;` |
| `.ub-bidi-override-l` | `unicode-bidi: bidi-override;` |
| `.ub-isolate-override-l` | `unicode-bidi: isolate-override;` |
| `.ub-plaintext-l` | `unicode-bidi: plaintext;` |
| `.ub-initial-l` | `unicode-bidi: inherit;` |
| `.ub-revert-l` | `unicode-bidi: revert;` |
| `.ub-revert-layer-l` | `unicode-bidi: revert-layer;` |
| `.ub-unset-l` | `unicode-bidi: unset;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ub-normal-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/unicode-bidi.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/unicode-bidi.css` — formatted
- `dist/unicode-bidi.min.css` — minified

## License

MIT

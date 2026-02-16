# css-writing-mode

Functional CSS for writing-mode

## Filesize

| File | Size |
|------|------|
| `dist/writing-mode.css` | 1681 bytes |
| `dist/writing-mode.min.css` | 1235 bytes (240 Gzipped) |

## Install

```sh
npm install css-writing-mode
```

## Usage

### Import

```css
@import "css-writing-mode";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-writing-mode/dist/writing-mode.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-writing-mode/dist/writing-mode.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.wm-horizontal-tb` | `writing-mode: horizontal-tb;` |
| `.wm-rl-tb` | `writing-mode: rl-tb;` |
| `.wm-vertical-lr` | `writing-mode: vertical-lr;` |
| `.wm-vertical-rl` | `writing-mode: vertical-rl;` |
| `.wm-bt-rl` | `writing-mode: bt-rl;` |
| `.wm-bt-lr` | `writing-mode: bt-lr;` |
| `.wm-lr-bt` | `writing-mode: lr-bt;` |
| `.wm-rl-bt` | `writing-mode: rl-bt;` |
| `.wm-horizontal-tb-s` | `writing-mode: horizontal-tb;` |
| `.wm-rl-tb-s` | `writing-mode: rl-tb;` |
| `.wm-vertical-lr-s` | `writing-mode: vertical-lr;` |
| `.wm-vertical-rl-s` | `writing-mode: vertical-rl;` |
| `.wm-bt-rl-s` | `writing-mode: bt-rl;` |
| `.wm-bt-lr-s` | `writing-mode: bt-lr;` |
| `.wm-lr-bt-s` | `writing-mode: lr-bt;` |
| `.wm-rl-bt-s` | `writing-mode: rl-bt;` |
| `.wm-horizontal-tb-m` | `writing-mode: horizontal-tb;` |
| `.wm-rl-tb-m` | `writing-mode: rl-tb;` |
| `.wm-vertical-lr-m` | `writing-mode: vertical-lr;` |
| `.wm-vertical-rl-m` | `writing-mode: vertical-rl;` |
| `.wm-bt-rl-m` | `writing-mode: bt-rl;` |
| `.wm-bt-lr-m` | `writing-mode: bt-lr;` |
| `.wm-lr-bt-m` | `writing-mode: lr-bt;` |
| `.wm-rl-bt-m` | `writing-mode: rl-bt;` |
| `.wm-horizontal-tb-l` | `writing-mode: horizontal-tb;` |
| `.wm-rl-tb-l` | `writing-mode: rl-tb;` |
| `.wm-vertical-lr-l` | `writing-mode: vertical-lr;` |
| `.wm-vertical-rl-l` | `writing-mode: vertical-rl;` |
| `.wm-bt-rl-l` | `writing-mode: bt-rl;` |
| `.wm-bt-lr-l` | `writing-mode: bt-lr;` |
| `.wm-lr-bt-l` | `writing-mode: lr-bt;` |
| `.wm-rl-bt-l` | `writing-mode: rl-bt;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.wm-horizontal-tb-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/writing-mode.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/writing-mode.css` — formatted
- `dist/writing-mode.min.css` — minified

## License

MIT

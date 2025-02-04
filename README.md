# select2-tailwindcss-v4-theme

[![GitHub](https://img.shields.io/github/v/release/erimicel/select2-tailwindcss-v4-theme?style=flat-square)](https://github.com/erimicel/select2-tailwindcss-v4-theme)
[![npm version](https://img.shields.io/npm/v/select2-tailwindcss-v4-theme?style=flat-square)](https://www.npmjs.com/package/select2-tailwindcss-v4-theme)
[![npm](https://img.shields.io/npm/dm/select2-tailwindcss-v4-theme?label=npm&style=flat-square)](https://www.npmjs.com/package/select2-tailwindcss-v4-theme)
[![jsdelivr](https://data.jsdelivr.com/v1/package/gh/erimicel/select2-tailwindcss-v4-theme/badge)](https://www.jsdelivr.com/package/gh/erimicel/select2-tailwindcss-v4-theme)
[![License](https://img.shields.io/github/license/erimicel/select2-tailwindcss-v4-theme?style=flat-square)](LICENSE)

[Select2](https://github.com/select2/select2) v4 theme for [TailwindCSS v4](https://tailwindcss.com/), inspired by [select2-bootstrap4-theme](https://github.com/ttskch/select2-bootstrap4-theme)

## Live demo v4

https://erimicel.github.io/select2-tailwindcss-v4-theme/

## Repo and live demo for tailwindcss v3 theme

Demo: https://erimicel.github.io/select2-tailwindcss-v3-theme/

Repo: https://github.com/erimicel/select2-tailwindcss-v3-theme

## 📦 Installation

### CDN

```html
<!-- Latest -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/erimicel/select2-tailwindcss-v4-theme/dist/select2-tailwindcss-theme-plain.min.css">

<!-- Different version change (x.x.x) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/erimicel/select2-tailwindcss-v4-theme@x.x.x/dist/select2-tailwindcss-theme-plain.min.css">
```

Install the package and ensure you have TailwindCSS installed in your project:

```bash
# npm
$ npm install select2-tailwindcss-v4-theme

# yarn
$ yarn add select2-tailwindcss-v4-theme
```

## Usage

```js
import 'select2-tailwindcss-v4-theme/dist/select2-tailwindcss-theme.css'; // Regular version
// OR
import 'select2-tailwindcss-v4-theme/dist/select2-tailwindcss-theme.min.css'; // Minified version
```

```js
$('select').select2({
  theme: 'tailwindcss-4',
});
```

### With tailwindcss config

Update your Tailwind configuration to include the package in the content array:

```css
// your css file
@source "select2-tailwindcss-v4-theme/dist/select2-tailwindcss-theme.css";
```

Enable to dark mode by `dark` class toggle:
```css
// your css file
@custom-variant dark (&:where(.dark, .dark *));
```

## Development

```bash
git clone https://github.com/erimicel/select2-tailwindcss-v4-theme.git
cd select2-tailwindcss-v4-theme
npm install
```

Modify the SCSS file in src/.scss. Build the CSS:

```bash
npm run build:all   # Build all files and update demo as-well
```

## Contributing

Contributions, issues, and feature requests are welcome! Fork the repository, create a new branch, commit your changes, push to your branch, and open a pull request:

```bash
git checkout -b feature-branch-name
git commit -m 'Add some feature'
git push origin feature-branch-name
```

If you find this package helpful, please ⭐ the repository on GitHub!
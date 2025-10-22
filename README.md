# Multi-File Gallery

## Overview
A simple single‑page web application that showcases a small file gallery. It displays two SVG icons side‑by‑side, renders the contents of `info.txt` and `notes.txt`, and uses Bootstrap 5’s grid system for a responsive layout.

## Features
- **SVG Gallery** – Two icons (`icon1.svg` and `icon2.svg`) displayed with a hover‑scale effect.
- **Text Display** – Content of `info.txt` and `notes.txt` shown in styled `<div>` elements.
- **Responsive Layout** – Built with Bootstrap 5 grid classes.
- **No Build Step** – All CSS and JavaScript are inline or loaded via CDN.

## How to Use
1. Open `index.html` in any modern web browser.
2. The page will immediately render the icons and text content.
3. Hover over the icons to see the interactive effect.

## Technical Details
- **HTML** – Single file (`index.html`) containing the entire application.
- **CSS** – Inline `<style>` block for custom styling (icon size, hover effect, text containers).
- **JavaScript** – Only Bootstrap’s bundled JS is loaded via CDN; no custom scripts are required.
- **Bootstrap 5** – Loaded from jsDelivr CDN for grid layout and basic styling.
- **SVG Icons** – Embedded directly as inline SVG elements (blue circle and red square) to avoid external requests.

## License
MIT License

```
MIT License

Copyright (c) 2025 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
```
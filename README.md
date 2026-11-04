# Favicon Foundry — Day 08

Create a small, crisp site icon from initials, a short word, or an emoji. Preview common browser and device sizes, then export an SVG, a 512 × 512 PNG, and a starter web manifest.

## Use it

Open `index.html` in a modern browser or visit the live demo. Choose a mark, colors, shape, and letter style. Download the files you need and place them in your site's public/root folder. Copy the HTML snippet into the page `<head>` and adjust paths if your files live elsewhere.

## Features

- Live previews at common favicon and app-icon sizes.
- Rounded, square, and circular backgrounds with adjustable mark scale.
- SVG export for crisp scaling and PNG export for compatibility.
- Web manifest starter with matching colors and icon references.
- HTML `<link>` snippet ready to copy.
- Responsive interface with no accounts, external libraries, uploads, analytics, or network requests.

## Privacy and limits

Everything is generated in the current browser tab. The SVG and PNG exporters use browser APIs; emoji appearance can vary by operating system and browser. The generated manifest references 192 px and 512 px PNG icons; export PNG at 512 px and resize/copy it to 192 px if your site needs both sizes. The SVG export keeps text as text, so emoji and fonts can look different on another device. Check the exported icon in your target browsers before shipping.

## GitHub Pages

This is a static single-file app. GitHub Pages can serve it from the repository's `main` branch and root folder.

## Built with

HTML, CSS, and browser JavaScript. MIT License.

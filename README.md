<h3 align="center">
	<img src="https://raw.githubusercontent.com/albcantero/vscode-dark-neue/main/images/icon.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Dark Modern Neue for <a href="https://code.visualstudio.com">Visual Studio Code</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://vscode.dev/theme/albcantero.vscode-dark-neue"><img src="https://img.shields.io/badge/preview%20in-vscode.dev-4F8FDD?style=for-the-badge&colorA=0a0a0a&logo=visualstudiocode&logoColor=white"></a>
</p>

<p align="center">
	<a href="https://github.com/albcantero/vscode-dark-neue/stargazers"><img src="https://img.shields.io/github/stars/albcantero/vscode-dark-neue?colorA=0a0a0a&colorB=4F8FDD&style=flat-square&logo=github&logoColor=white"></a>
	<a href="https://github.com/albcantero/vscode-dark-neue/issues"><img src="https://img.shields.io/github/issues/albcantero/vscode-dark-neue?colorA=0a0a0a&colorB=4F8FDD&style=flat-square&logo=gitbook&logoColor=white"></a>
	<a href="https://marketplace.visualstudio.com/items?itemName=albcantero.vscode-dark-neue"><img src="https://img.shields.io/visual-studio-marketplace/i/albcantero.vscode-dark-neue?colorA=0a0a0a&colorB=4F8FDD&style=flat-square&label=installs&logo=docsdotrs&logoColor=white"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/albcantero/vscode-dark-neue/main/assets/all-themes-preview.webp"/>
</p>

## Previews

<details>
<summary>Dark Modern Neue</summary>
<img src="https://raw.githubusercontent.com/albcantero/vscode-dark-neue/main/assets/default.webp"/>
</details>

<details>
<summary>Dark Modern Neue — High Contrast</summary>
<img src="https://raw.githubusercontent.com/albcantero/vscode-dark-neue/main/assets/high-contrast.webp"/>
</details>

<details>
<summary>Dark Modern Neue — Minimal</summary>
<img src="https://raw.githubusercontent.com/albcantero/vscode-dark-neue/main/assets/minimal.webp"/>
</details>

## Variants

**Dark Modern Neue** — Warm desaturated palette. Salmon strings, teal types, sky variables. Chromatic balance over high contrast — every token family is luminosity-matched.

**Dark Modern Neue (High Contrast)** — Full saturation Tailwind-based colors. Electric indigo, fuchsia, sky, and emerald with strong chromatic separation. Built for maximum token differentiation.

**Dark Modern Neue (Minimal)** — Near-monochrome neutral scale with a single teal accent (`#7DCFCA`) for strings. Keywords are darker than identifiers — the code reads through content, not syntax.

## Installation

1. Open VS Code
2. Go to **Extensions** (`Ctrl+Shift+X`)
3. Search for `Dark Modern Neue`
4. Click **Install**
5. Open Command Palette (`Ctrl+Shift+P`) → `Preferences: Color Theme`
6. Select your preferred variant

## Recommended Settings

```jsonc
{
  "editor.semanticHighlighting.enabled": true,
  "editor.fontFamily": "CommitMono",
  "editor.fontSize": 13,
  "editor.lineHeight": 1.5,
  "editor.letterSpacing": 0.15,
  "editor.fontLigatures": true,
  "editor.fontVariations": true
}
```

## Motivation

I couldn't stand the bright, saturated green that Dark, Dark+, and Dark Modern use for comments:

<p align="center">
  <img src="https://raw.githubusercontent.com/albcantero/vscode-dark-neue/main/assets/horrible-comment.webp" width="350"/>
</p>

So the first thing I did was replace it with a soft italic gray — comments should whisper, not shout.

From there I updated the base colors with warmer, desaturated tones for a more modern feel, drawing inspiration from the Dark 2026 palette released in February. I also looked closely at how Cursor styles its Anywhere theme — which I've also ported to VS Code ([check it out here](LINK)).

Then came a High Contrast variant built entirely on [shadcn/Tailwind colors](https://ui.shadcn.com/colors), with strong chromatic separation for maximum token differentiation.

And finally, my personal favorite: a monochrome and super minimalistic variant in the spirit of [Vercel's aesthetic](https://vercel.com/) — near-zero color, inverted hierarchy, with a single elegant teal accent reserved for strings.

## Feedback

Dark Modern Neue is open source and contributions are welcome!

There are many ways to contribute, from [reporting bugs](https://github.com/albcantero/vscode-dark-neue/issues) and [submitting enhancement suggestions](https://github.com/albcantero/vscode-dark-neue/issues) to improving the themes by [submitting pull requests](https://github.com/albcantero/vscode-dark-neue/pulls).

Found a specific issue with a token or color? [Open an issue](https://github.com/albcantero/vscode-dark-neue/issues) on GitHub and include the language, scope, and a screenshot if possible.

<p align="center">
  Copyright &copy; 2026 <a href="https://github.com/albcantero" target="_blank">Alberto Cantero</a>
</p>

<p align="center">
	<a href="https://github.com/albcantero/vscode-dark-neue/blob/main/LICENSE">
		<img src="https://img.shields.io/static/v1.svg?style=flat-square&label=License&message=MIT&colorA=0a0a0a&colorB=4F8FDD"/>
	</a>
	<a href="https://github.com/albcantero">
	  <img src="https://img.shields.io/static/v1.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAABMklEQVQ4jcWQvUoDQRRGz52s5IfVIiDWPkGKFFaCIVaGdIagjcFAwICFb7DvIK6QQlNpY2UQLMQVBbEQ0SewFkGbKCQmOzaTJay7/lR+zTAf9xwuF/47Mv45rdezqWEq72v/RWZnHgqOMwDwHMfSj085JSqb6Pu38we7r18E3nqzhmYbsE11rxKsAvhDfQiSM30XYbOw57YDwfnaRl6U3ABWaMNn806H+oGPzBX3d+4UgChZiYBHYBgGsBLoKoAyhR0x9G20Zmpc4P1ZoMQDcwMNclFrdhBKv6M5WWi7ZQGtjEUn35IV4OwnVjSX/WGmKqCDDUa5rmyle3bvGFiMg3WGUsF1u0EXHoqTRMGRgkAy2eugKZrqijRLYThWANBpNDL2h3UE0J0YLJdbrfe42f/NJ0wqY7/KcXKPAAAAAElFTkSuQmCC&label=lovely%20crafted%20in&message=Spain&colorA=0a0a0a&colorB=4F8FDD"/>
	</a>
</p>

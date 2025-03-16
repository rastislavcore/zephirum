# Zephirum Monospace Font

Zephirum is designed for good readability and legibility. It is ideal for code, terminal, and other monospace applications, including machine reading.

The Arabic word Ṣifr (صفر), meaning "empty" or "nothing," was introduced to Europe through Islamic mathematics. Fibonacci later Latinized it as "Zephirum", which evolved into the modern word "zero."

## Font Information

The font follows the [Google Fonts specification](https://github.com/googlefonts/gf-docs) and includes:

- `DESCRIPTION.en_us.html` - Font description and details
- `FONTLOG.txt` - Detailed font history and acknowledgments
- `zephirum(*).css` - CSS files for web usage
- `Zephirum-Regular.glyphs` - Glyphs file
- `Zephirum-Regular.ttf` - TrueType font file
- `METADATA.pb` - Font metadata for Google Fonts
- `OFL.txt` - SIL Open Font License v1.1

## Development

The font source is in TTF format and can be opened and modified using:

- [Glyphs](https://glyphsapp.com)
- [FontForge](https://fontforge.org)
- [FontLab](https://fontlab.com)
- Any other font editor that supports TTF format

To modify the font:

1. Install a font editor
2. Open the `Zephirum-Regular.glyphs` file
3. Make your changes and export the font files

Please note that some glyphs are composed of multiple glyphs. However, in TTF format they are exported as decomposed glyphs. Avoid editing the TTF file to maintain consistency. TTF is only for exporting glyphs.

## Usage

### Using the CSS file

Define the font family in your CSS file

```css
@import url("https://cdn.jsdelivr.net/gh/rastislavcore/zephirum/zephirum.css");
```

or in your HTML file

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rastislavcore/zephirum/zephirum.css">
```

Usage Example

```css
code, pre, .monospace {
  font-family: "zephirum", monospace;
}

/* Using special PUA characters */
.open-source-icon::before {
  font-family: "zephirum";
  content: "\E0A9";
}

.bitcoin::before {
  font-family: "zephirum";
  content: "\F1B6";
}
```

### Importing the font

```css
@font-face {
  font-family: "zephirum";
  src: url(Zephirum-Regular.ttf) format("truetype");
  font-display: swap;
}
```

### CDN

CSS import of the latest version

```css
@font-face {
  font-family: "zephirum";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/zephirum/Zephirum-Regular.ttf) format("truetype");
  font-display: swap;
}
```

CSS with Minor updates and patch fixes within a major version

```css
@font-face {
  font-family: "zephirum";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/zephirum@1/Zephirum-Regular.ttf) format("truetype");
  font-display: swap;
}
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1. See the [OFL.txt](OFL.txt) file for full details.

## Funding

If you find this project useful, please consider supporting it:

- [GitHub Sponsors](https://github.com/sponsors/rastislavcore)

List of sponsors: [![GitHub Sponsors](https://img.shields.io/github/sponsors/rastislavcore?label=Sponsors&logo=githubsponsors&color=EA4AAA)](https://github.com/sponsors/rastislavcore)

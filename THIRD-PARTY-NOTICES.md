# Third-Party Notices

Circle of Fifths Interactive embeds font software in its standalone HTML file. The application code and the embedded fonts are separate works with separate license terms. The MIT license in `LICENSE` applies to the original application code only; it does not relicense the fonts.

## Geist Mono

- **Font family:** Geist Mono Regular
- **Copyright notice:** Copyright 2024 The Geist Project Authors
- **License:** SIL Open Font License 1.1 (OFL-1.1)
- **Upstream project:** https://github.com/vercel/geist-font
- **License information:** https://openfontlicense.org/

The standalone HTML includes the Geist Mono copyright notice and the complete OFL 1.1 text in a non-executing, human-readable source block (`geist-mono-license`).

## C059 Roman

- **Font family:** C059 Roman
- **Copyright notice:** Copyright (c) 2014, 2015 by (URW)++ Design & Development
- **Upstream family:** URW Core 35, Version 2.0 (C059 / Century Schoolbook)
- **Original font file:** `fonts/C059-Roman.otf`
- **License selected for this project:** SIL Open Font License 1.1 (OFL-1.1)
- **Upstream source repository:** https://github.com/ArtifexSoftware/urw-base35-fonts
- **OFL license and release documentation:** https://github.com/twardoch/urw-core35-fonts
- **License text in this repository:** [`OFL-1.1-C059.txt`](./OFL-1.1-C059.txt)

The original `C059-Roman.otf` supplied for this project was checked by SHA-256. Its digest matches the `C059-Roman.otf` entry in the published checksum manifest for the URW Core 35 Version 2.0 font files:

`e00cc7b88f0cf25ae43f0e48de39d0043fe042b55719a3ac32669ab3369542ec`

The URW Core 35 Version 2.0 files have documented alternative licensing under AGPL-3.0 with a font-embedding exception, LPPL 1.3c, or SIL OFL 1.1. This project uses the OFL 1.1 alternative. The OFL-licensed distribution specifies no Reserved Font Names.

## MicrotonalFont

- **Font family:** MicrotonalFont (Microtonal / Microtonal Font in its embedded metadata)
- **Base font:** C059 Roman by (URW)++ Design & Development
- **Modification:** selected glyphs were changed to provide microtonal accidentals
- **Modification attribution:** microtonal glyph modifications by **rodion chan**
- **License:** SIL Open Font License 1.1 (OFL-1.1), under the same terms as the C059 base font
- **Original OTF asset:** `fonts/Microtonal-Font.otf`

MicrotonalFont is a modified version of C059, not an unrelated font or a relicensing of the original URW work. Its modified font software is distributed under OFL 1.1. The standalone HTML contains a WOFF2-format version of the font; the original OTF assets are also provided in `fonts/`.

## OFL conditions relevant to redistribution

OFL 1.1 permits commercial use and embedding or bundling fonts with software. The font software and derivative font software must remain under OFL 1.1; neither the original nor modified font software may be sold by itself. Each distributed copy must include the applicable copyright notice and full OFL text. The full C059/MicrotonalFont license is supplied in `OFL-1.1-C059.txt` and is also embedded as readable text in the standalone HTML (`urw-c059-microtonal-ofl-license`).

The fonts are not relicensed under MIT. The project's original application code remains under MIT, while the embedded and separately distributed font software remains under its own OFL 1.1 terms.

## Scope

These notices identify the font assets and the license choice made for this distribution. They are not legal advice. For the exact license wording and URW Core 35 release history, consult the linked upstream documentation and the included license text.

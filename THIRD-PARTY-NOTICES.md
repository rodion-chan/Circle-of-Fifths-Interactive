# Third-Party Notices

Circle of Fifths Interactive embeds font software in its standalone HTML file. These font files are separate third-party assets; they are not relicensed under the MIT license used for the application's original code.

## Geist Mono

- **Font family:** Geist Mono Regular
- **Copyright notice in the embedded font:** Copyright 2024 The Geist Project Authors
- **License:** SIL Open Font License 1.1 (OFL-1.1)
- **Upstream project:** https://github.com/vercel/geist-font
- **License information:** https://openfontlicense.org/

The standalone HTML file includes the Geist Mono copyright notice and the complete OFL 1.1 license text in its source.

## C059 Roman

- **Font family:** C059 Roman
- **Copyright notice in the embedded font metadata:** (URW)++, Copyright 2014 by (URW)++ Design & Development
- **Upstream family:** URW Base 35
- **Upstream project:** https://github.com/ArtifexSoftware/urw-base35-fonts
- **Upstream license statement:** GNU Affero General Public License version 3 (AGPL-3.0), with a special exception for including the font programs in qualifying PostScript or PDF documents.
- **Upstream license files:** https://github.com/ArtifexSoftware/urw-base35-fonts/blob/master/LICENSE and https://github.com/ArtifexSoftware/urw-base35-fonts/blob/master/COPYING

The upstream exception is specifically worded for PostScript or PDF documents. It should not be assumed to cover embedding the font as a data URI in an HTML application. The terms applicable to this HTML distribution should be reviewed before public redistribution.

## MicrotonalFont

- **Font family in the embedded font metadata:** Microtonal / Microtonal Font
- **Description in the embedded font metadata:** “C059 font with some characters changed to microtonal accidentals”
- **Underlying font identified by its metadata:** C059
- **Underlying copyright notice:** (URW)++, Copyright 2014 by (URW)++ Design & Development

The application author identifies MicrotonalFont as their own modification of C059, including changes for microtonal accidentals. The modifications may be attributed to rodion chan; however, the font remains derived from C059 and its upstream license terms cannot be replaced unilaterally with the application's MIT license.

The corresponding editable font source and build materials for this modified font are not included in this repository package yet. They should be supplied alongside the modified font when it is redistributed under the applicable AGPL-3.0 terms. The upstream PS/PDF exception should not be assumed to cover webfont or HTML embedding.

## Important licensing note

The `LICENSE` file in this repository applies to the application's original code only. It does not grant additional rights to third-party font software. Before redistributing the single-file HTML application, make sure the applicable AGPL-3.0 terms and the provenance/licensing of the modified MicrotonalFont are properly addressed. This notice records the font metadata and upstream information identified during preparation; it is not a legal opinion or a substitute for the actual license texts.


# Lugrasimo

Lugrasimo is a DocRepair font, intended to improve compliance with the
ISO/IEC 29500 standard by providing fallback that minimizes text reflow in
Office Open XML documents. Lugrasimo is based on Fondamento, a typeface in calligraphic lettering style based on the traditional Foundational Hand, a basic teaching style created by Edward Johnston in the early 20th century. The letterforms are clear and cleanly legible, basic and formal.

Designed by Brian J. Bonislawsky for Astigmatic (AOETI).

## About

Based on Fondamento ([original sources](https://github.com/googlefonts/googlefontsdirectory-old/tree/main/ofl/fondamento/src), [latest binaries](https://github.com/google/fonts/tree/main/ofl/fondamento))

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

- `make build` will produce font files.
- `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
- `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://docrepair-fonts.github.io/dr-vivigraph-fonts.git.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.

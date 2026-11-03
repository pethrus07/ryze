# RYZE

English · [Português](README.pt-BR.md)

Visual identity for RYZE, the freelance software development brand of Pedro Oliveira (João Pessoa, Brazil), and
the fonts used in documents generated with the brand.

## Status

Active (November 2026). There is no system here, only brand files. No diagram.

## The brand on one screen

- **Colours:** black `#0D0D0D` (base), gold `#FFB700` (accent and logo; `#CC9200` for text on light backgrounds),
  purple `#6A28C9` (technology). Ratio: 55% black, 20% gold, 10% purple, 15% neutrals.
- **Type:** Space Grotesk for headings, Plus Jakarta Sans for body text, JetBrains Mono for data and labels.
- **Logo:** an arrow pointing up. Main use is gold on black; documents use the single-colour version.
- **Direction:** clean, lots of white space, numbers up front.

The details are in the guide: open `identidade/Identidade completa.html` in a browser.

## Fonts

The files in `documentos/fontes/` are static instances (one weight per file) of the Google Fonts variable fonts.
Headless Chrome embeds static TTF into a PDF predictably, which the variable font does not guarantee. All three
families are distributed under the SIL Open Font License 1.1.

## Folders

```
identidade/
  Identidade completa.html            self-contained brand guide (colours, type, logo, usage)
  logo-montanha.svg                   logo
  logo-montanha-preto.svg             black single-colour logo
  logo-montanha-branco.svg            white single-colour logo
  ryze-symbol-gold-transparent.svg    gold symbol, transparent background
documentos/
  fontes/                             static TTF files for PDF generation (headless Chrome)
```

## Decisions and known limits

Documents made for clients (summaries, proposals, contracts, transcribed conversations, audio) **are not kept in
git**. They live in `documentos/<client-YYYY-MM>/` on disk only, and `.gitignore` ignores every subfolder of
`documentos/` except `fontes/`, plus any audio or video file.

## License

- Code (the HTML guide in `identidade/`): MIT. See [LICENSE](LICENSE).
- Fonts in `documentos/fontes/`: SIL Open Font License 1.1, by their authors. See [OFL.txt](documentos/fontes/OFL.txt).
- The RYZE name, logo and symbol are a registered mark of the author and are not licensed for reuse.

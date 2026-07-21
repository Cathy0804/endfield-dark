# Endfield Dark

A dark colour theme with a matching file icon set. Cold grey ground, silver text,
industrial yellow and Klein blue accents.

## What's included

- **Endfield Dark** — colour theme (`workbench.colorTheme`)
- **Endfield Dark Icons** — file icon theme (`workbench.iconTheme`), 27 icons covering
  88 file extensions, 18 exact filenames and 15 language IDs

## Design notes

- **Ground is `#272C33`** — a cold grey, deliberately not pure black.
- **One accent per role.** Yellow `#FFD429` for active/primary UI, Klein blue `#6E8DEA`
  for links, green and rose reserved for diff and error semantics.
- **Semantic and TextMate palettes agree.** Language servers deliver semantic tokens
  asynchronously and they override TextMate scopes; when the two palettes disagree,
  tokens visibly change colour a moment after a file loads. Both are kept in sync so
  the repaint is invisible.
- **Contrast checked.** Every foreground/background pair in the theme meets 4.5:1,
  and all 70 token colours clear 3.0:1 against the editor background.

## Attribution

This theme is a dark adaptation of **Endfield Light** by Leukotriene, which is itself an
adaptation of the **Arknights: Endfield Theme** by Yalla Nkardaz. Both are MIT licensed,
and the original copyright notice is retained in `LICENSE`.

Accent colours were derived from the originals by a hue-preserving lightness transform;
the file icon set is original work.

## Disclaimer

Fan-made and inspired by Arknights: Endfield. **Not affiliated with, endorsed by, or
sponsored by Hypergryph.** All trademarks are the property of their respective owners.

## Licence

MIT — see [LICENSE](LICENSE).

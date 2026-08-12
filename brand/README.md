# Brand assets

Source files for off-site use — social profiles, decks, submission forms.
Nothing here is referenced by the website; the site's own icon is
[`/favicon.svg`](../favicon.svg) at the repo root.

Everything is set in **Neue Haas Grotesk Display Bold**, white on black,
matching the homepage wordmark.

## linkedin/

Sized to LinkedIn's company-page spec.

| File | Size | Use |
|------|------|-----|
| `banner-1128x191.png` | 1128 × 191 | Company page cover, spec size |
| `banner-2256x382@2x.png` | 2256 × 382 | Same at 2×, sharper on retina |
| `logo-monogram-300x300.png` | 300 × 300 | Company logo — **recommended** |
| `logo-wordmark-300x300.png` | 300 × 300 | Company logo, full wordmark |

The banner repeats the homepage lockup with even 44.7px margins above and
below, and the wordmark centred so it clears the lower-left area where
LinkedIn overlays the logo on desktop.

**On the two logo options:** LinkedIn renders company logos at roughly 48px in
feeds. At that size the monogram stays crisp while the wordmark's "FILMS" line
disappears and "ISOCHRONE" is barely readable. Use the monogram unless the
placement is large. The tradeoff is that "IF" reads as the word *if*.

## icon/

The `I` mark from `favicon.svg`, rasterised for contexts that need a PNG. Same
geometry as the favicon, so all three stay consistent.

An earlier attempt used a lone `I` as the LinkedIn logo and it was dropped — in
a grotesque, a capital I is a plain bar with no serifs, so at logo scale it
carries no brand to anyone who doesn't already know the company. It works as a
favicon because a browser tab is an identifier, not an introduction.

## Regenerating

These were rendered in a browser from the licensed Adobe Fonts kit — drawn to a
`<canvas>` at exact pixel dimensions and exported, rather than screenshotted,
so the output is true resolution rather than upscaled.

Do **not** rebuild these from font files found online. The family is licensed
through Creative Cloud, which covers desktop and web use; see the licensing note
in [`../assets/fonts.css`](../assets/fonts.css).

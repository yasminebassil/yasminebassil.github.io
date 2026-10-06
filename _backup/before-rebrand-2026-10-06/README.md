# Before the rebrand (6 October 2026)

What the site used before the oxblood / mulberry / sage trial, kept so it can be put back.

## Files here

- `hero-original.webp` — the homepage photo exactly as it was embedded in `index.html`
  (2000 × 1333, sRGB, sky colour `#FCF7FB`). The trial version on `index-sample.html` has the
  sky shifted to `#FCFAF8`; nothing else in the photo was changed.
- `site.css` — a copy of `css/site.css` with the original colour variables.

The last commit on `main` before this work is `aae3330`; `git show aae3330:index.html` also
returns the original homepage, photo included.

## Original colours

Core palette (`css/site.css`, used by home and bio):

| Name       | Hex       | Used for                                   |
|------------|-----------|--------------------------------------------|
| paper      | `#FEFBFD` | page background                            |
| paper-warm | `#F0EBE3` | secondary panels on older pages            |
| ink        | `#2C2825` | headings and main text                     |
| muted      | `#5C5552` | secondary text, nav links                  |
| purple     | `#6B5B8E` | the accent: links, ", phd"                 |
| terracotta | `#C4755B` | hover on home; accent on creative, defense |
| olive      | `#5C6B54` | homepage tagline                           |
| cup-blue   | `#3F6FA8` | flower motif stems                         |
| cup-clay   | `#B5714A` | flower motif petals                        |

Other values in use on single pages:

- `#7671C4` — purple on `cv.html`
- `#766FE2` — homepage particle glow
- `#4A4544` — grey stored as "accent-terracotta" on `research.html` and `thoughts.html`
- `#F9F6F6` — background of `defense.html`

## To go back

- Colours: the live pages (`index.html`, `bio.html`, `css/site.css` and the rest) have not been
  recoloured. Only `bio-sample.html`, `index-sample.html` and `brand.html` use the new set.
- Photo: `index.html` still embeds the original. If the adjusted photo is ever moved into
  `index.html`, restore by re-embedding `hero-original.webp`, or with
  `git checkout aae3330 -- index.html` (which also reverts other homepage edits).

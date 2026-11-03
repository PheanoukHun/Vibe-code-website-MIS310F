# Fernlight Greenhouse Café

A static two-page website for **Fernlight Greenhouse Café**, a fictional coffee, tea and matcha café in a sunlit greenhouse in Austin, Texas. Built for the MIS 302F "Grand Opening" assignment and meant to be hosted on [Neocities](https://neocities.org).

*Coffee, tea, and a little more green.*

## Repository layout

| Path | Purpose |
|---|---|
| `site/` | The website: `index.html`, `menu.html`, `style.css`, `images/`, `BRIEF.md` |
| `research/` | Sub-agent research that led to the concept: ideas, existence check, viability, synthesis and assignment check |
| `marketing/` | Tagline and marketing copy, plus the Part 2 image-generation kit |
| `Grand_Opening_Cafe_Instructions.docx` | The assignment instructions |
| `Grand_Opening_Cafe_Evidence_Tracker.docx` | The blank tracker |
| `Grand_Opening_Cafe_Evidence_Tracker_filled.docx` | Tracker with Part 1 (café brief) filled in |
| `CLAUDE.md` | Working rules for Claude Code in this repo |

## How the concept was chosen

Three sub-agents ran one round: one proposed 8 Austin café ideas, one checked whether similar cafés already exist, and one scored viability. Three ideas survived (greenhouse café, retro arcade café, study café). Fernlight, the greenhouse café, passed the assignment checks with the fewest risks. Details are in `research/synthesis-and-doc-check.md`.

## The site

- Pages: Home (welcome, hours, weekly event, address, phone, email) and Menu (8 items, image, house rules).
- All facts come from `site/BRIEF.md`, the single source of truth. Contact details are fictional: phone `(512) 555-01XX`, email ending `.example`.
- Pure static HTML and CSS. No JavaScript, because the assignment forbids it.

## Status

- [x] Research and concept selection
- [x] Tagline and marketing copy
- [x] Pages, styles and brief
- [x] Tracker Part 1 filled in
- [ ] Part 2: AI-generated PNG logo and interior image (SVG stand-ins are in `site/images/`); see `marketing/part2-image-kit.md`
- [ ] YouTube video embed on the Menu page (placeholder marked in `menu.html`)
- [ ] Part 4: publish on Neocities
- [ ] Part 5: Barista's Pick, added by hand in `index.html`
- [ ] Parts 6 and 7: health inspection and reflections (reflections are written without AI)

## Publishing to Neocities

1. Create a free account at neocities.org.
2. Keep the starter files (`not_found.html`, `robots.txt`, `neocities.png`). Replace the contents of `index.html` and `style.css` with the files from `site/`.
3. Create `menu.html`, and an `images` folder containing the two images.
4. Open your live address in a new tab and test both pages, the navigation, the images and the video.

File names must match exactly, since web servers treat capitals as different files.

## Notes

- Everything fictional: no real address, phone or email, and no invented awards, reviews or "since" dates.
- Before publishing, search the name "Fernlight" plus "café" again, and verify the Sunset Valley botanical café mentioned in the research notes.

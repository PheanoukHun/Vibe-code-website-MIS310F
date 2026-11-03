# Part 2 Kit: Design the Sign

You generate exactly **two** images in an AI image tool (ChatGPT, Copilot, Gemini, Firefly, Canva...). Save both as **PNG**, lowercase, no spaces, into `site/images/`.

| Image | Save as |
|---|---|
| Logo | `fernlight-logo.png` |
| Second image | `fernlight-greenhouse.png` |

## Prompt 1: Logo (paste as your FIRST prompt, then record it in the tracker)

> Create a simple flat logo for a café called "Fernlight". Show a single fern frond curling around a steaming coffee cup. Use deep forest green and cream on a plain cream background, bold clean shapes, high contrast. Use an arched greenhouse-window shape, not a circle. Include no text at all. No people, no animals, no existing brand or mascot imagery.

Why it's worded this way:
- **No text** avoids garbled spelling (check 5). The café name is already in the HTML.
- **Arch, not circle** avoids resembling a well-known green circular coffee logo (check 2). My hand-drawn SVG used a ring, so don't copy it.
- High contrast and bold shapes help checks 6 and 7.

## Prompt 2: Second image (menu page)

> A sunlit glass greenhouse café interior, ferns and hanging plants, a long wooden table with cups of coffee and matcha, warm morning light. No people. No signs, no writing, no logos or brand names anywhere, including on the cups.

## Inspect before using (record Pass/Fail + a note for each in the tracker)

Logo (all 8), second image (checks 1, 2, 4, 8):

1. No existing character or franchise imagery
2. Doesn't look like a real brand's logo with the name swapped
3. Name and words are your own (no one else's brand or slogan)
4. Created, not found
5. Text spelled correctly (no text expected; make sure none sneaked in)
6. Readable at app-icon size: shrink it to ~64 px and look
7. Enough contrast between shapes and background
8. Passes the Grandmother & Employer Test

Also check for: stray gibberish text on cups or signs in image 2, people or faces, and file size (over ~1 MB → shrink in Paint/Preview).

## Alt text (adjust to match what the final images actually show)

- Logo: "Fernlight Greenhouse Café logo: a fern frond curling around a steaming coffee cup inside an arched window shape"
- Second image: "Sunlit greenhouse café with ferns, hanging plants, and a long wooden table set with cups of coffee and matcha"

## Tracker items for Part 2
- First logo prompt (exact text you used)
- Final logo image, pasted in (not linked)
- 8 checks marked Pass/Fail with notes, and what you regenerated or fixed
- Second image, pasted in
- Both file names and both alt texts

## Next step
Drop the two PNGs in `site/images/` and tell me. I'll look at them, point out anything that looks wrong, switch the HTML from the SVG stand-ins to the PNGs, and fill the file-name and alt-text rows in your tracker. You make the final Pass/Fail calls.

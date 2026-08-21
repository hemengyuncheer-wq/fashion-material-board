---
name: fashion-material-board
description: Transform a user-supplied outfit or fashion reference image into a tactile fashion material board with taped editorial printouts, physical fabric/leather/fur samples, and handwritten production notes. Use for image-led fashion moodboards, garment material stories, look-development boards, apparel concept presentations, or realistic flat-lay textile reference images.
---

# Fashion Material Board

Create a vertically oriented, photographed physical styling board: one editorial outfit printout at left and a curated material library at right. Prioritize believable paper, real textile depth, and imperfect hand assembly over graphic-design polish.

## Require a reference image first

This is a reference-image-led workflow. Always require at least one user-supplied outfit, garment, or fashion reference image before generating the material board.

- If the current request has no attached image, do not generate, invent an outfit, or call an image-generation tool. Ask the user to upload one clear reference image, then stop.
- Keep the request concise: `请先上传一张你想转换成材质灵感板的服装或造型参考图。`
- If an image is already attached in the current request or available in the immediate conversation context, use it directly and do not ask for it again.
- Treat written preferences such as palette, occasion, or desired materials as optional supplements to the required image, not replacements for it.
- After receiving the image, inspect the visible silhouette, garments, colours, surface qualities, accessories, and styling mood before deciding the material story.
- Preserve the reference image's recognizable outfit and styling direction in the editorial printout. Do not replace it with an unrelated invented look.

## Build the board

1. Read the look from the supplied reference image: silhouette, occasion, colour family, visible surfaces, and 3–5 supporting materials. Keep the palette disciplined: mostly neutrals plus one accent, or a restrained monochrome.
2. Compose on a warm ivory/off-white wall or tabletop. Place a slightly oversized cream sheet of uncoated paper on it, set vertically with a small natural shadow.
3. Put one tall fashion-editorial model photograph in the left third. It must show the full outfit in a neutral studio and be visibly fixed with torn strips of aged masking tape along its top and bottom edges.
4. Arrange real, touchable swatches in the right two-thirds. Use 3–5 samples of visibly different construction: rib knit, striped jersey, brushed wool, smooth leather, croc-embossed leather, cotton, plaid, faux fur, or feather trim. Let at least one sample overlap another or extend beyond the paper to create depth.
5. Add sparse dark-brown/black handwritten atelier annotations beside each swatch: material + colour + optional fibre content. Treat text as secondary; it may be abbreviated, softly imperfect, or partially illegible.

## Required visual language

- Straight-on overhead/near-overhead flat-lay photograph, 3:4 or 4:5 vertical.
- Warm daylight, very soft shadows, muted contrast, quiet cream/grey/brown ground.
- Physical details: torn tape edges, slight wrinkles, paper curl, pinked (zigzag-cut) fabric edges where appropriate, raw fabric fibres, imperfect alignments.
- Editorial photo: full-length, understated model pose, pale studio backdrop, desaturated print with subtle paper sheen.
- Materials must look three-dimensional and authentic, not as flat colour rectangles. Make leather grain, ribs, yarn, pile, weave, or feather barbs easy to read.
- Use a restrained 1990s–2000s luxury ready-to-wear styling sensibility: elegant, minimal, tactile, slightly archival.

## Prompt recipe

Use this order in an image-generation prompt:

```text
realistic editorial fashion material board photographed from above, physical hand-assembled flat lay on an off-white wall; [outfit photo at left]; [3–5 named physical swatches at right]; cream masking tape with torn ends securing the print and selected samples; warm paper, subtle wrinkles, tactile material texture, soft daylight, gentle cast shadows, sparse small handwritten atelier notes, muted luxury styling, vertical 3:4 composition
```

Describe every material by both colour and surface (for example, “deep oxblood smooth leather”, “charcoal fine-rib knit”, “long beige faux-fur pile”). Ensure the outfit visibly uses the same material story.

## Guardrails

- Do not generate anything until the user has supplied a reference image.
- Do not treat the example below or a text-only theme as a substitute for the user's image.
- Do not make it a digital collage, UI, scrapbook with stickers, or a polished catalogue layout.
- Do not use grids, borders, bright graphic colour blocks, glossy magazine spreads, excessive branding, or legible large typography.
- Do not show floating swatches; every element should appear laid on or taped to the board.
- Avoid excessive props. The board itself, printout, tape, swatches, notes, and their shadows are the subject.
- Do not overfill the page. Preserve breathing room around the annotations.

## Example

```text
Create a realistic vertical fashion material board photographed as a tactile flat lay on a warm ivory wall. At left, a narrow editorial printout taped at top and bottom shows a full-length female model in a white cotton tie-neck blouse, deep red leather midi skirt, black knee-high boots, and a beige fur clutch. At right on one large cream paper sheet: a translucent white cotton square with pinked edges, an oversized square of oxblood red smooth leather, and a thick rectangular beige faux-fur swatch overlapping the bottom edge. Add only a few small dark handwritten atelier notes describing the materials. Torn aged masking tape, natural wrinkles, paper edge shadows, soft daylight, restrained luxury styling, photographed straight-on from above, vertical 3:4. No digital collage, no grid, no logos, no prominent readable text.
```

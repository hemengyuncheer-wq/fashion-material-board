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

## Lock identity, pose, and clothing

Source fidelity is more important than styling polish. Treat the supplied image as the actual editorial photograph to place on the board, not merely as loose inspiration for redrawing the person.

- Use an image-editing/reference-image workflow. Keep the person inside the editorial print as close to the supplied pixels as the tool permits; generate or transform the surrounding paper, tape, shadows, notes, and material swatches instead.
- Preserve facial identity: face shape, feature spacing, eyes, eyebrows, nose, lips, jawline, ears, skin tone, visible marks, age, and overall likeness.
- Preserve hair and styling: hairline, length, colour, texture, parting, hairstyle, eyewear, jewellery, makeup, and headwear.
- Preserve expression and gaze. Do not beautify, age, de-age, face-swap, retouch, or reinterpret the face.
- Preserve pose and anatomy: head angle, gaze direction, shoulder line, hand placement, limb position, stance, body proportions, camera angle, and crop.
- Preserve clothing exactly: garment category, silhouette, cut, length, layering, closures, seams, collars, sleeves, hems, prints, logos, colours, texture placement, shoes, bags, and accessories.
- Do not add, remove, redesign, restyle, recolour, or replace any garment or accessory unless the user explicitly asks for that specific change.
- If the reference is not full-length, retain its original framing. Never hallucinate missing body parts, extend the pose, or invent unseen clothing merely to create a full-body fashion photo.
- Permitted treatment of the embedded photo is limited to uniform scaling, non-destructive placement, a physical print border, subtle paper sheen, and very mild whole-photo tonal integration that does not change identity, clothing colours, or details.
- Keep tape, swatches, notes, and other generated elements outside the person's face and important garment details.

Before returning the result, visually compare the generated editorial print with the source. Check the face, expression, pose, hands, garment silhouette, colours, and accessories. If any of these have materially changed, do not treat that image as final; make a corrective edit that restores the original reference before presenting it.

## Build the board

1. Read the look from the supplied reference image: silhouette, occasion, colour family, visible surfaces, and 3–5 supporting materials. Keep the palette disciplined: mostly neutrals plus one accent, or a restrained monochrome.
2. Compose on a warm ivory/off-white wall or tabletop. Place a slightly oversized cream sheet of uncoated paper on it, set vertically with a small natural shadow.
3. Place the supplied reference image itself as the fashion-editorial print in the left third, preserving its original subject, crop, face, pose, garments, and accessories. Do not recreate the model. Fix the print with torn strips of aged masking tape along its top and bottom edges without covering the face or key clothing details.
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
Edit the supplied reference into a realistic editorial fashion material board photographed from above. Preserve the reference person's exact facial identity, expression, gaze, hair, pose, body proportions, clothing, colours, footwear, bag, accessories, camera angle, and crop; use the original image as the unchanged editorial print at left rather than redrawing the subject. Generate only the surrounding physical hand-assembled flat lay on an off-white wall, [3–5 named physical swatches at right], cream masking tape with torn ends, warm paper, subtle wrinkles, tactile material texture, soft daylight, gentle cast shadows, sparse small handwritten atelier notes, muted luxury styling, vertical 3:4 composition. Do not alter, beautify, restyle, recolour, extend, or replace the person or outfit.
```

Describe every material by both colour and surface (for example, “deep oxblood smooth leather”, “charcoal fine-rib knit”, “long beige faux-fur pile”). Ensure the outfit visibly uses the same material story.

## Guardrails

- Do not generate anything until the user has supplied a reference image.
- Do not treat the example below or a text-only theme as a substitute for the user's image.
- Do not use text-to-image recreation when the original photo can be retained as the editorial print.
- Do not change the face, expression, gaze, hairstyle, pose, hands, anatomy, clothing, footwear, bag, accessories, crop, or camera angle.
- Do not cover the face or important outfit details with tape, fabric, notes, or shadows.
- Do not make it a digital collage, UI, scrapbook with stickers, or a polished catalogue layout.
- Do not use grids, borders, bright graphic colour blocks, glossy magazine spreads, excessive branding, or legible large typography.
- Do not show floating swatches; every element should appear laid on or taped to the board.
- Avoid excessive props. The board itself, printout, tape, swatches, notes, and their shadows are the subject.
- Do not overfill the page. Preserve breathing room around the annotations.

## Example

```text
Using the uploaded fashion reference as the unchanged editorial print, create a realistic vertical material board photographed as a tactile flat lay on a warm ivory wall. Preserve the person's exact face, expression, hair, pose, crop, clothing, colours, footwear, bag, and accessories. Do not redraw or restyle the subject. Place the original reference print at left with tape at the paper edges. At right, arrange 3–5 tactile material swatches derived from the visible outfit. Add only a few small dark handwritten atelier notes. Torn aged masking tape, natural wrinkles, paper-edge shadows, soft daylight, restrained luxury styling, vertical 3:4. No digital collage, no grid, no logos, and no alteration of the person or outfit.
```

---
name: pixel-dissolve-landscape
description: "Transform an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 pixel-dissolve landscape poster with a limited-palette pixel reconstruction dissolving into abundant paper white. Use when the user asks for像素溶解海报、像素化风景海报、限色调像素海报或把普通海报改成像素溶解风；do not activate for generic color palette, watercolor, impasto, plush, clay, pixel art-game, or photorealistic poster tasks."
metadata:
  short-description: 像素溶解风景风海报重绘 Skill
---

# Pixel Dissolve Landscape

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 pixel-dissolve landscape poster. It reinterprets the artwork as a limited-palette pixel reconstruction that dissolves into paper white while preserving the source poster's communication job.

This skill is independent from `watercolor-travel-card`, `impasto-miniature-landscape`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `observational-pen-wash`, and any other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a pixel-dissolve landscape poster;
- create a curated limited-palette pixel study or dissolving pixel scene;
- redesign a campaign visual with a pixel reconstruction receding into paper white;
- preserve a poster's message while changing its material to a controlled pixel dissolve.

Do not use it for a normal poster, watercolor, impasto, plush, clay, pixel-art game, or photorealistic tasks.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret pixel structure, palette, crop, and decorative elements.
2. **Choose one recognizable visual anchor** (a bridge, facade, dome, vehicle, boat, gate, or roof group) as the focal point. Do not invent landmarks or people.
3. **Build a readable depth stack**: warm off-white paper → sparse background pixel layers → main pixel subject → dissolving edge blocks → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal pixel subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

A manually selected, color-limited, recomposed pixel landscape — not a mosaic filter or globally downsampled photo.

- On warm off-white or pale ivory paper, keep one highly recognizable visual anchor. Retain only the minimum elements required for subject identity, place, and spatial relationships.
- Subject occupies roughly 30%–50% of canvas width/height, in the lower-middle, offset by source direction. Preserve at least 50%–65% complete paper white.
- Rebuild the scene with crisp square or near-square discrete blocks. Medium blocks for contour, mass, light-dark structure, major color fields; smaller, denser blocks at identifying details.
- Toward architecture edges, vegetation, roads, water, reflections, distance, progressively reduce, separate, misalign, and remove blocks.
- Dissolution must come only from decreasing the count and density of independent blocks. A few may drift along perspective, water flow, terrain, or motion, never random glitch effects.
- Compress the source into 6–12 principal color steps. Prefer paper white as the largest color field.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant pixel subject and abundant paper white so the headline stays legible.
- Leave a lower-detail, calmer paper zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** pixel subject, dissolve edge blocks, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the pixel visual layer and plan a text overlay.
5. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
6. Review the result against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks

## Supporting files

- `palettes.md`: pixel-dissolve palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The pixel reads as a curated dissolve, not a mosaic filter or global downsampling.
- One focal pixel subject dominates and paper white exceeds the pixel area.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `watercolor-travel-card`, `impasto-miniature-landscape`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `observational-pen-wash`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

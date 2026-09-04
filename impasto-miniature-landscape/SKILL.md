---
name: impasto-miniature-landscape
description: "Transform an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 impasto miniature-landscape poster with bright sculptural oil-paint volume, palette-knife marks, and luminous clarity. Use when the user asks for厚涂微缩景观海报、雕塑油画风海报、立体厚涂海报或把普通海报改成厚涂风；do not activate for generic color palette, watercolor, gouache, plush, clay, pixel, or photorealistic poster tasks."
metadata:
  short-description: 厚涂微缩景观风海报重绘 Skill
---

# Impasto Miniature Landscape

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 impasto miniature-landscape poster. It reinterprets the artwork as a dimensional, tactile 3D oil-paint miniature while preserving the source poster's communication job.

This skill is independent from `watercolor-travel-card`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, `observational-pen-wash`, and any other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into an impasto miniature-landscape poster;
- create a sculptural oil-paint diorama or tactile impasto scene;
- redesign a campaign visual with bright oil-paint volume and luminous clarity;
- preserve a poster's message while changing its material to a tactile impasto miniature.

Do not use it for a normal poster, watercolor, gouache, plush, clay, pixel, or photorealistic tasks.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, impasto, composition, crop, and decorative elements.
2. **Choose one central sculptural subject** (the most recognizable element of the source) as the visual anchor. Do not scatter unrelated impasto objects.
3. **Build a readable depth stack**: bright textured paper → translucent impasto support ribbon → sculptural subject → sparse scene motifs → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

A refined, dimensional, tactile 3D impasto miniature landscape.

- Reconstruct the source's most recognizable subject, silhouette, pose, and narrative relationship as a sculptural miniature.
- Bright white textured paper, generous negative space, centered or slightly off-center diagonal axis.
- One translucent impasto ribbon derived from the scene (water, ground, path, light trail, or abstract landscape slice).
- Sparse background: a few scene-related impasto clouds, sun, mist, or natural motifs. No unrelated objects.
- Emphasize impasto oil paint × miniature object × luminous clarity: paint buildup, palette-knife marks, raised edges, paper texture, semi-hand-shaped materiality.
- Concentrate heavy paint on water, clouds, the support ribbon, and selected highlights.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant sculptural subject and a calm paper ground so the headline stays legible.
- Leave a lower-detail, calmer paper zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** impasto subject, support ribbon, scene motifs, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the impasto visual layer and plan a text overlay.
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

- `palettes.md`: impasto miniature palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The impasto reads as a sculptural miniature, not a photo filter or digital render.
- One focal subject dominates and is not buried in paint.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `watercolor-travel-card`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, `observational-pen-wash`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

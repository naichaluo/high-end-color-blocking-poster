---
name: papercraft-travel-diorama
description: "Transform an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 handcrafted papercraft travel-diorama poster with tactile paper/cardstock miniature scene, soft cool blues, and generous negative space. Use when the user asks for纸艺旅行微缩海报、纸艺立体场景海报、手工纸雕海报或把普通海报改成纸艺微缩风；do not activate for generic color palette, watercolor, impasto, plush, clay, pixel, or photorealistic poster tasks."
metadata:
  short-description: 纸艺旅行微缩景观风海报重绘 Skill
---

# Papercraft Travel Diorama

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 handcrafted papercraft travel-diorama poster. It reinterprets the artwork as a refined 3D handcrafted miniature scene while preserving the source poster's communication job.

This skill is independent from `watercolor-travel-card`, `impasto-miniature-landscape`, `isometric-healing-blocks`, `pixel-dissolve-landscape`, `observational-pen-wash`, and any other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a papercraft travel-diorama poster;
- create a handcrafted paper/cardstock/diorama miniature scene;
- redesign a campaign visual with tactile papercraft miniature depth;
- preserve a poster's message while changing its material to a refined paper miniature.

Do not use it for a normal poster, watercolor, impasto, plush, clay, pixel, or photorealistic tasks.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, miniature, composition, crop, and decorative elements.
2. **Choose one central handcrafted subject** as the visual anchor, on one long narrow lightweight floating landscape base. Do not scatter unrelated models.
3. **Build a readable depth stack**: soft paper ground → floating landscape base → dominant handcrafted subject → supporting small models → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

A refined 3D handcrafted miniature scene using paper, cardstock, soft clay, or thin wood.

- Build around one dominant subject, one long narrow lightweight floating landscape base, and generous negative space.
- Adapt height, depth, spacing, density, and left-right balance to the subject's scale, direction, and spatial relationships.
- Create depth through size variation, layered occlusion, and restrained foreground/background elements.
- Give the subject the greatest visual weight; keep supporting models smaller and quieter. Center the visual balance without rigid symmetry.
- Supporting plants, roads, water, lamps, vehicles, people, birds, or clouds must come from the source or be clearly relevant to its setting. No meaningless decoration.
- Authentic handcraft: visible paper fibers, folds, cut marks, layered thickness, slightly rough edges, tiny handmade imperfections. Soft natural diffused light, delicate shadows, macro-photography tactility.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant handcrafted subject and a calm paper ground so the headline stays legible.
- Leave a lower-detail, calmer paper zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** papercraft subject, floating base, supporting models, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the papercraft visual layer and plan a text overlay.
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

- `palettes.md`: papercraft diorama palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The papercraft reads as a designed miniature, not a photo filter or generic toy.
- One focal subject dominates and is not buried in models.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `watercolor-travel-card`, `impasto-miniature-landscape`, `isometric-healing-blocks`, `pixel-dissolve-landscape`, `observational-pen-wash`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

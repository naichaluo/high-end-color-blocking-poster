---
name: watercolor-travel-card
description: "Transform an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 perforated watercolor travel-card poster with transparent watercolor, fine pen lines, and a restrained editorial archive column. Use when the user asks for水彩旅行卡片海报、水彩记忆卡海报、旅行档案海报或把普通海报改成水彩卡片风；do not activate for generic color palette, gouache, oil, plush, clay, pixel, or photorealistic poster tasks."
metadata:
  short-description: 水彩旅行卡片风海报重绘 Skill
---

# Watercolor Travel Card

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a full-canvas perforated watercolor travel-card poster. It reinterprets the artwork as a transparent watercolor memory card while preserving the source poster's communication job.

This skill is independent from `impasto-miniature-landscape`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, `observational-pen-wash`, and any other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a watercolor travel-card poster;
- create a perforated watercolor memory card or travel archive layout;
- redesign a campaign visual with transparent watercolor and subtle pen linework;
- preserve a poster's message while changing its material to a quiet watercolor travel card.

Do not use it for a normal poster, flat vector, gouache, oil, plush, clay, pixel, or photorealistic tasks.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, watercolor wash, composition, crop, and decorative elements.
2. **Choose one central watercolor subject** (the most recognizable element of the source) and keep it as the visual anchor. Do not fill the canvas with scattered washes.
3. **Build a readable depth stack**: warm ivory paper → transparent watercolor wash → pen-line subject → editorial archive column → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

A perforated watercolor travel memory card on warm ivory cotton cold-pressed paper.

- Left 68%–75%: reconstruct the scene with transparent watercolor and a few fine pen lines, preserving the most recognizable contours, pose, direction, colors, and spatial relationships.
- Transparent and airy, with cold-pressed grain, pigment bloom and settling, broken linework, controlled washes, natural water marks, slight overrun, reserved paper highlights, and lightly unfinished edges.
- Right 25%–32%: a restrained travel archive column, separated by one evenly spaced row of uniform circular perforations (like a collectible tear-off card).
- Soft limited watercolor palette derived entirely from the source; preserve signature subject colors and overall temperature.
- A verifiable 2–3-word title and a `NO. XX` identifier, set in an editorial serif or humanist sans serif.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant watercolor subject, and let the environment fade naturally into the page.
- Reserve a calm, low-detail paper zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** watercolor scene, pen-line subject, archive column, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the watercolor visual layer and plan a text overlay.
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

- `palettes.md`: watercolor travel-card palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The watercolor reads as a designed travel card, not a photo filter or collage.
- One focal subject dominates and is not buried in washes.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `impasto-miniature-landscape`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, `observational-pen-wash`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

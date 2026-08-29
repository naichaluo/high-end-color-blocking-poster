---
name: ghibli-animation-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a hand-painted Ghibli-style animation scene with soft watercolor airbrush backgrounds, gentle light, nostalgic pastoral mood, and charming miniature storybook detail. Use when the user asks for吉卜力风海报、宫崎骏风海报、手绘动画海报、日系治愈动画海报、水彩手绘海报或把普通海报改成吉卜力动画风；do not activate for generic color palette, flat vector, plush, clay, or paper-art poster tasks."
metadata:
  short-description: 吉卜力手绘动画风海报重绘 Skill
---

# Ghibli Animation Poster

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a hand-painted, storybook-like Ghibli-style animation scene. It reinterprets the artwork with soft watercolor grades, gentle pastoral light, and nostalgic warmth while preserving the source poster's communication job.

This skill is independent from `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, `high-end-color-blocking-poster`, and `crayon-scribble-poster`. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a Ghibli-style hand-painted animation scene;
- create a watercolor / airbrush / pastoral hand-drawn poster concept, prompt, or key visual;
- redesign a campaign visual with a nostalgic, gentle, storybook tableau;
- preserve a poster's message while changing its material to soft painted light and hand-drawn scenery.

Do not use it for a normal poster, flat vector look, plush fabric, clay, paper-art, or a pure palette-only change with no painted-scenery reinterpretation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret scenery, light, mood, crop, and decorative elements.
2. **Choose one central painted scene metaphor** (e.g. a cottage field for a home offer, a path through woods for a journey, a riverside village for a local campaign). Do not scatter unrelated props.
3. **Build a readable depth stack** (soft sky → distant hills → midground setting → hero subject → foreground accent). Each layer should read as painted planes with soft edge falloff.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

Ghibli means a hand-painted animated film frame, not a photoreal render or a flat illustration. Use:

- soft watercolor / airbrush shading with gentle color transitions and misty light
- translucent transparent skies, fluffy cumulus clouds, warm green hills, glowing sunlight and dappled shadow
- nostalgic pastoral or storybook mood, gentle and lived-in, never cold or sterile
- loose painterly edges, subtle paper/grain texture, soft atmospheric haze
- charming miniature detail; a sense of quiet wonder and everyday magic in the setting

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep a clear focal subject and a calm sky/ground band so the headline stays legible.
- Let natural scenery (fields, sky, water, trees, clouds) carry the mood rather than covering the whole canvas in detail.
- Leave a lower-detail, softer color zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** painted scenery, product props, decorative elements, clouds, foliage, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the painted visual layer and plan a text overlay.
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

- `palettes.md`: watercolor / pastoral palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The painted scene reads as a designed storybook tableau, not a generic landscape.
- One focal subject dominates and is not buried in scenery.
- The light and color mood is coherent and warm.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, `high-end-color-blocking-poster`, or `crayon-scribble-poster`. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

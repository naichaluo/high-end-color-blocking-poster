---
name: observational-pen-wash
description: "Transform an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 observational pen-and-wash poster with minimal sketchbook linework, rhythmic pen lines, thin transparent washes, and bold negative space. Use when the user asks for钢笔淡彩海报、观察写生海报、极简素描海报或把普通海报改成钢笔淡彩风；do not activate for generic color palette, watercolor, impasto, plush, clay, pixel, or photorealistic poster tasks."
metadata:
  short-description: 钢笔淡彩写生风海报重绘 Skill
---

# Observational Pen and Wash

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 observational pen-and-wash poster. It reinterprets the artwork as a minimal sketchbook study with rhythmic linework and thin washes while preserving the source poster's communication job.

This skill is independent from `watercolor-travel-card`, `impasto-miniature-landscape`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, and any other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into an observational pen-and-wash poster;
- create a minimal sketchbook study with airy pen wash and rhythmic linework;
- redesign a campaign visual with loose pen lines and bold negative space;
- preserve a poster's message while changing its material to a minimal pen-and-wash study.

Do not use it for a normal poster, watercolor, impasto, plush, clay, pixel, or photorealistic tasks.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret linework, wash, negative space, crop, and decorative elements.
2. **Choose one central contour/action motif** from the source as the visual anchor. Do not scatter unrelated objects.
3. **Build a readable depth stack**: pale paper → thin transparent washes → rhythmic pen-line subject → decisive accent lines → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal motif, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

A carefully edited private observation notebook: minimal, boldly spacious, compositionally alert, free in line but never chaotic.

- Treat the core contour or action as a visual motif. Organize the full page through repetition, variation, pause, accent, and sudden negative space.
- The subject may be offset, cropped, suspended, or extended along its original direction; it need not be complete or centered.
- Use one or two decisive free lines as accents, then let remaining marks weaken so broad blank areas become rests.
- Fine, loose, uneven pen lines. Allow broken contours, searching lines, repeated corrections, sudden weight, slight deviations, unfinished edges.
- Extract only 2–4 identifying colors from the source and apply them as sparse, thin, transparent washes. Allow slight overrun, water marks, granulation, uneven coverage. Never paint a complete watercolor background.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant pen-line motif and abundant negative space so the headline stays legible.
- Leave a lower-detail, calmer paper zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** pen-line subject, washes, accent lines, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the pen-wash visual layer and plan a text overlay.
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

- `palettes.md`: observational pen-wash palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The pen-wash reads as a designed observation study, not a photo filter or vector.
- One focal motif dominates and negative space is abundant.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `watercolor-travel-card`, `impasto-miniature-landscape`, `isometric-healing-blocks`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

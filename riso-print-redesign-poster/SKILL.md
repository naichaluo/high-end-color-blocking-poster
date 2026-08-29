---
name: riso-print-redesign-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a Rustfield-style RISO screen-print redesign with hard contour edges, 2-3 limited ink colors, registration gaps and paper slivers, geometric mass conversion, and a clean neutral paper substrate. Use when the user asks for RISO风海报、丝网印刷海报、risograph海报、套色印刷海报、油墨双色海报、几何图形重绘海报或把普通海报改成RISO丝网印刷风；do not activate for generic color palette, watercolor, crayon, plush, clay, paper-art, or photorealistic poster tasks."
metadata:
  short-description: RISO 丝网印刷几何重绘海报 Skill
---

# RISO Print Redesign Poster

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a Rustfield-style RISO screen-print redesign. It reinterprets the artwork with hard-printed geometric masses, a limited 2-3 ink palette, and authentic screen-print junctions while preserving the source poster's communication job.

This skill is independent from `ghibli-animation-poster`, `crayon-scribble-poster`, `monument-valley-poster`, `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, and `high-end-color-blocking-poster`. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a RISO / risograph screen-print redesign;
- create a limited-ink, hard-edged, geometric-abstraction poster concept, prompt, or key visual;
- redesign a campaign visual with screen-print junctions, registration gaps, and 2-3 color inks;
- preserve a poster's message while changing its material to clean geometric screen-print.

Do not use it for a normal poster, flat vector icons, watercolor, crayon, plush, clay, paper-art, photorealistic mockup, or a pure palette-only change with no geometric conversion.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret geometry, mass, ink, depth, crop, and decorative elements.
2. **Choose one central graphic construction** (visual anchor + counterweight + a source-derived stamp). Do not fill the canvas with unrelated vectors or icons.
3. **Build a readable depth stack** (neutral paper → broad mass groups → hero graphic anchor → stamp module → reserved text zones). Each mass needs a crisp hard printed edge, not a blur.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal anchor, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

RISO redesign means a clean, limited-ink screen-print, not watercolor, gouache, dry brush, or a generic grain filter. Use:

- crisp, hard printed edges with broad low-frequency contour wobble; wobble shifts contour location, never edge sharpness
- a limited palette of 2-3 ink colors plus a neutral natural-white paper substrate
- varied narrow unequal gaps, exposed paper slivers, slight overlaps, and registration offsets at major color junctions
- broad geometric masses and structural bands instead of photographic micro-detail
- a few local structural zones for halftone, uneven ink density, missing-ink rubs, short drags, overprint, or registration drift
- clean large fields that keep colors separable, with black secondary (at most ~25% of the canvas)

## Style tiers (pick one per render)

There are two approved RISO intensities. Default to `standard` unless the user asks for a stronger look.

### Standard RISO (default)

A clean, confident screen-print. Balanced contour wobble, clear junction gaps and paper slivers, subtle registration offset, a few local halftone / missing-ink accents, and tidy geometric masses. Use this for a refined, editorial, approachable result.

### Boosted RISO (stronger)

A punchier, more assertive screen-print. Stronger low-frequency contour wobble (still crisp, never blurred), more visible unequal gaps and exposed paper slivers, clearer registration offset and slight overprint, more active local halftone dots, missing-ink rubs, and short ink drags (concentrated in a few structural zones, never an even all-over texture), edges that are harder and geometry that is more crisp and blocky. Limited 2-3 inks, neutral natural-white paper, black secondary (≤25%). Use this when the user wants the RISO language turned up.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant visual anchor and a calmer paper/ink field so the headline stays legible.
- Let geometry organize mass, hierarchy, and scale — not a demand for boxes or icons. Use blunt angles, asymmetry, crop, overlap, and functional perspective planes only as needed for recognition.
- Leave a lower-detail, calmer ink zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** geometric ink masses, product graphic construction, stamp module, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose an ink treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the ink visual layer and plan a text overlay.
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

- `palettes.md`: limited-ink RISO palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The ink reads as a designed screen-print, not a filter or grain overlay.
- One focal anchor dominates and is not buried in vectors.
- Junctions show at least two of: contour wobble, unequal gap, paper sliver, overlap, registration offset, halftone, or missing ink.
- The palette is limited to 2-3 inks plus neutral paper; black stays secondary.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `ghibli-animation-poster`, `crayon-scribble-poster`, `monument-valley-poster`, `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, or `high-end-color-blocking-poster`. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

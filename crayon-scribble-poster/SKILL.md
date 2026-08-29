---
name: crayon-scribble-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a playful crayon-scribble / wax-crayon hand-drawn poster with visible waxy strokes, bold layered scribbles, childlike energy, and warm paper texture. Use when the user asks for蜡笔涂抹海报、蜡笔手绘海报、涂鸦风海报、儿童蜡笔海报、粗线条手绘海报或把普通海报改成蜡笔涂抹风；do not activate for generic color palette, flat vector, plush, clay, watercolor, or paper-art poster tasks."
metadata:
  short-description: 蜡笔涂抹手绘风海报重绘 Skill
---

# Crayon Scribble Poster

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a playful crayon-scribble / wax-crayon hand-drawn poster. It reinterprets the artwork with bold waxy strokes, layered scribbles, and warm childlike energy while preserving the source poster's communication job.

This skill is independent from `ghibli-animation-poster`, `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, and `high-end-color-blocking-poster`. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a crayon-scribble hand-drawn poster;
- create a wax-crayon / kid-style scribble poster concept, prompt, or key visual;
- redesign a campaign visual with bold playful strokes and warm paper texture;
- preserve a poster's message while changing its material to crayon scribble.

Do not use it for a normal poster, flat vector, plush fabric, clay, watercolor, paper-art, or a pure palette-only change with no hand-drawn reinterpretation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret strokes, color, energy, crop, and decorative elements.
2. **Choose one central scribble metaphor** (e.g. a doodled cup for a drink offer, a scribbled house for a home service, a crayon sun for a joyful campaign). Do not cover the canvas in random doodles.
3. **Build a readable depth stack** (paper ground → layered scribble bands → hero subject → accent doodles). Each layer should keep enough contrast for the message to read.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

Crayon scribble means a lively hand-colored wax-crayon drawing, not a clean vector or a soft watercolor. Use:

- visible wax crayon strokes, layered and slightly overlapping, with bold color
- warm paper texture and slight grain; crayon edges that are a little rough and uneven
- childlike, energetic, joyful mood with generous, confident scribble fill
- a mix of outline and color-block scribble; looser, not geometrically precise
- a sense of hand-made playfulness and honest warmth — never sleek or corporate-hard

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep a clear focal subject and a calmer background band so the headline stays legible.
- Let the scribble energy live in the subject and accent doodles, not in every square inch.
- Leave a lower-detail, calmer color zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** crayon scene, props, doodles, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the crayon visual layer and plan a text overlay.
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

- `palettes.md`: crayon palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The crayon reads as a designed hand-drawn poster, not scribble noise.
- One focal subject dominates and is not buried in doodles.
- The color and stroke energy is coherent and warm.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `ghibli-animation-poster`, `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, or `high-end-color-blocking-poster`. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

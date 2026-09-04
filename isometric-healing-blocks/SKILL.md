---
name: isometric-healing-blocks
description: "Transform an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 isometric healing-block sculpture poster with rounded modular volumes, gentle interlocking, and a soft airy healing palette. Use when the user asks for等距治愈积木海报、圆角模块雕塑海报、治愈系等距风海报或把普通海报改成等距积木风；do not activate for generic color palette, impasto, watercolor, plush, clay, pixel, or photorealistic poster tasks."
metadata:
  short-description: 等距治愈积木风海报重绘 Skill
---

# Isometric Healing Blocks

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a full-canvas 3:4 isometric healing-block sculpture poster. It reinterprets the artwork as rounded, tactile modular volumes while preserving the source poster's communication job.

This skill is independent from `watercolor-travel-card`, `impasto-miniature-landscape`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, `observational-pen-wash`, and any other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into an isometric healing-block sculpture poster;
- create a rounded modular sculpture or gentle isometric block scene;
- redesign a campaign visual with soft interlocking modular volumes;
- preserve a poster's message while changing its material to a healing-style isometric block sculpture.

Do not use it for a normal poster, impasto, watercolor, plush, clay, pixel, or photorealistic tasks.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret geometry, modular volume, palette, crop, and decorative elements.
2. **Choose one central isometric sculpture** (the source's most recognizable subject) as the visual anchor. Do not scatter unrelated modules.
3. **Build a readable depth stack**: soft paper ground → modular interlock masses → sculpture subject → accents → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal sculpture, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

A deconstruct → select → distill → reconstruct process translating the subject into a healing-style 3D/isometric block sculpture.

- Rounded, simple, tactile modular volumes reorganized while keeping it immediately recognizable.
- Adapt composition to the subject's center of gravity, pose direction, and spatial relationships.
- Build rhythm through volume scale, stepped heights, front-back interlocking, selective suspension, density changes, and generous negative space.
- Modules may join, stack, nest, pass through one another, or shift naturally. Contemporary sculpture and relaxed imagination, not mechanical disassembly or pixelation.
- Finely matte, softly diffused materials with subtle pulp, wood, powder-wax, or flexible-material tactility. Keep corners rounded and shadows gentle.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant isometric sculpture and a calm paper ground so the headline stays legible.
- Leave a lower-detail, calmer paper zone where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** modular sculpture, interlock masses, accents, decorative marks, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the block visual layer and plan a text overlay.
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

- `palettes.md`: isometric healing-block palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The blocks read as a designed healing sculpture, not a machine break-down or pixelation.
- One focal sculpture dominates and is not buried in modules.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `watercolor-travel-card`, `impasto-miniature-landscape`, `papercraft-travel-diorama`, `pixel-dissolve-landscape`, `observational-pen-wash`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

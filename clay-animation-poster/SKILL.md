---
name: clay-animation-poster
description: Create or restyle commercial posters in clay animation / stop-motion texture while preserving the source poster's exact business content, hierarchy, brand assets, and layout logic. Use when a user wants a poster transformed into clay-like 3D handmade visual style without mixing content from other projects.
metadata:
  short-description: Clay animation poster restyling with strict content preservation
---

# Clay Animation Poster

Use this skill to create or redraw posters in a clay animation / stop-motion style while keeping the user's source content under strict control.

## Core Rule

The source poster or current brief supplies the business facts, text, brand elements, layout hierarchy, and offer amounts. This skill supplies only visual treatment: clay material, handmade form language, soft lighting, miniature staging, and tactile composition.

Never borrow, quote, remix, or infer content from another campaign, previous chat, earlier generated poster, unrelated brand, or unrelated reference image. If multiple references exist, label each one and use only the references the user explicitly names for the current output.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a clay treatment from [palettes.md](palettes.md) and a prompt pattern from [prompt-templates.md](prompt-templates.md).
4. Generate or paint only the clay-style visual layer when exact text matters.
5. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
6. Review the final image against the source and remove any content that came from another project.

## Style Definition

Clay animation means a handmade miniature set, not generic 3D gloss. Use:

- soft polymer-clay shapes with rounded imperfect edges
- fingerprints, pressed seams, tiny dents, kneaded texture, and hand-modeled thickness
- stop-motion set lighting with soft shadows and practical miniature depth
- shallow depth of field only where it does not hurt text legibility
- sculpted product props rather than photo-real cutouts
- paper, foil, ribbon, acrylic, and sticker elements recreated as clay or tactile craft materials

## Composition Rules

Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top logo/title, central product scene, offer module, QR/action area, and service/legal area in comparable visual positions.

Do not turn a sales poster into a lifestyle scene if the original is a structured promotion. Clay props should support the same offer hierarchy.

## Text And Brand Handling

For commercial posters, AI-generated text is risky. Prefer a two-layer workflow:

- visual layer: clay background, product props, decorative frame, ribbons, icons, and non-critical labels
- controlled layer: exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Current-Project Isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks

## Supporting Files

- [palettes.md](palettes.md): clay-compatible palettes and material treatments.
- [prompt-templates.md](prompt-templates.md): reusable prompts for style transfer and poster generation.
- [examples/](examples/): example briefs and prompt applications.

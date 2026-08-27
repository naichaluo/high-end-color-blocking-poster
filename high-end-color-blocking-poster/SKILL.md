---
name: high-end-color-blocking-poster
description: Create premium color-blocking posters with restrained 2–3 color palettes, oversized flat shapes, generous negative space, editorial typography, and subtle print texture. Use when designing, prompting, or art-directing modern poster visuals; do not use for photorealistic product renders, dense layouts, or unrestricted illustration styles.
metadata:
  short-description: 高级感撞色海报设计与提示词 Skill
---

# High-End Color-Blocking Poster

Use this skill to turn a brief, product, promotion, or event into a modern poster direction that feels like an editorial print rather than a crowded e-commerce banner.

## Trigger conditions

Activate when the request involves premium color-blocking, modern editorial, minimalist, or zine-like poster design; a poster prompt for an image model; or a Chinese marketing, product-benefit, telecom promotion, or event poster that should retain visual restraint.

Do not activate for ordinary logo design, detailed brand identity systems, dense infographic layouts, photorealistic product mockups, or purely photographic campaigns unless the user explicitly asks for this visual language.

## Core visual contract

1. **Palette:** Select one dominant ground, one saturated accent, and optionally one supporting accent. Keep the visible palette to 2–3 major colors plus neutral paper/ink.
2. **Color roles:** The ground carries roughly 55–75% of the canvas; the main graphic or accent field carries 15–30%; typography and small marks use the darkest or most legible color.
3. **Shape language:** Use large flat, hard-edged or softly geometric blocks, circles, arcs, stripes, cut-paper forms, or simple symbolic illustrations. Avoid gradients, glossy 3D, decorative clutter, and random blobs.
4. **Whitespace:** Preserve visible breathing room. For minimal posters, leave about 55–75% open ground. Place the subject away from edges with intentional asymmetry.
5. **Typography:** Use a modern sans-serif or restrained display face. For Chinese copy, keep a clear headline, compact supporting line, detail line, and safe area. If the image model cannot render Chinese reliably, reserve clean text zones and add final type later.
6. **Texture:** Add only subtle matte paper tooth, soft ink spread, registration marks, or print misalignment. Texture must support the composition, never become a generic grain filter.
7. **Mood:** Calm, fresh, confident, cultured, and memorable—not merely colorful.

## Composition rules

- Start with a vertical 3:5 or 4:5 poster unless specified otherwise.
- Build a simple hierarchy: ground → primary shape/subject → headline → supporting details → tiny mark or CTA.
- Prefer one symbolic subject or one product silhouette. Keep it clean and readable; do not add unrequested props.
- Use a strong offset, cropped circle, diagonal division, or anchored lower-corner object to create movement.
- Keep critical text and logos inside a safe margin. Never place important copy on a busy edge or low-contrast field.
- For commercial posters, make the offer legible before adding decoration; for art/event posters, let the visual concept lead while retaining essential logistics.

## Copy and brand safety

- Preserve user-provided names, prices, dates, phone numbers, URLs, and legal qualifiers exactly.
- Never invent a telecom brand logo, official trademark, promotion condition, or claim.
- If no copy is supplied, use placeholders such as `[主标题]`, `[活动日期]`, and `[CTA]`; do not fabricate business facts.
- Do not imitate a living designer or reproduce a reference exactly. Extract principles—palette, proportion, whitespace, and shape grammar—then create an original composition.

## Execution workflow

1. Parse the brief into subject, audience, purpose, mandatory copy, format, and output tool.
2. Choose a palette from `palettes.md`, or define equivalent HEX values with explicit color roles.
3. Write a compact art direction: format, ground, block geometry, subject scale/position, type hierarchy, and texture.
4. Select the relevant template in `prompt-templates.md` and replace every bracketed field.
5. Add the shared Negative Prompt. For Chinese text, either specify an exact text-safe layout or plan a post-generation typesetting pass.
6. Review against the quality gate below.

## Quality gate

- Is the palette limited to 2–3 major colors?
- Is there a clear dominant ground and a single visual focal point?
- Does the composition retain generous negative space?
- Are the accent and text sufficiently legible?
- Does the subject match the brief without unrequested accessories?
- Does the design feel printed/editorial rather than glossy, neon, or crowded?
- Are all required copy, offer details, and brand constraints preserved?

For detailed palette selection, read `palettes.md`. For tool-ready prompts, read `prompt-templates.md`. For worked directions, read the matching file in `examples/`.

---
name: plush-animation-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a plush / wool-felt stop-motion animation advertisement with soft fuzzy fibers, handcrafted miniature props, gentle macro depth of field, and a warm natural palette. Use when the user asks for毛绒动画海报、羊毛毡海报、毛绒定格风海报、毛绒玩具质感广告、软体微缩场景或把普通海报改成毛绒动画风；do not activate for generic color palette, flat vector, clay animation, paper collage, or torn-paper poster tasks."
metadata:
  short-description: 毛绒/羊毛毡定格动画海报重绘 Skill
---

# Plush Animation Poster

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a plush / wool-felt stop-motion animation advertisement. It reinterprets the artwork as a soft, handcrafted miniature set while preserving the source poster's communication job.

This skill is independent from `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, and `high-end-color-blocking-poster`. Do not merge or append another skill's material or palette rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a plush / wool-felt / soft-toy advertisement;
- create a plush stop-motion poster concept, prompt, key visual, or mini-diorama ad;
- redesign a campaign visual with a handmade fiber miniature set;
- preserve a poster's message while changing its material to fuzzy, tactile, soft fabric.

Do not use it for a normal poster, a flat vector look, a color-palette-only request, or a clay/paper material change with no plush transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, props, depth, metaphor, crop, and decorative elements.
2. **Choose one central miniature set metaphor** that carries the poster (e.g. a soft-toy product on a felt shelf, a fiber village for a delivery route, a knitted landscape for a leisure offer). Do not scatter unrelated plush toys across the canvas.
3. **Build a readable depth stack** (background felt backdrop → midground props → hero subject → foreground tactile accents). Each layer needs a soft edge and a believable fabric shadow.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

Plush here means a **fluffy, chubby, irresistibly cute** animation look, NOT a realistic sculpted felt. Default to this direction:

- **Surface:** plush / fluffy / fuzzy — big soft pile, fleece, fine faux-fur, pom-pom and cotton-wool texture. Prefer a soft, fully fuzzy surface over a dense hard felted one, unless the user explicitly asks for "毡/细致毡化".
- **Body shapes:** **short, stubby, chubby, oversized-round** forms. The subject should look like a cute soft toy and **not** match the real object proportionally. Squash the proportions, round the silhouette, shrink fine accents, keep it toy-like and kawaii.
- **Face/character:** give props a gentle friendly charm (soft rounded features, cute closed-eyes, blush, small happy expression) when it helps the mood — keep it wholesome and endearing, not cold.
- **Edges:** soft seams, gentle folds, slightly irregular handmade edges. Avoid hard stitched or pressed felt lines that read as rigid / craft-like.
- **Materials:** plush fabric, fleece, fine faux-fur, yarn, pom-poms, cotton-wool, soft buttons — tactile and squeezable, never glossy.
- **Lighting:** soft miniature set lighting, gentle shadows, warm cozy mood; shallow macro depth of field only where it does not hurt text.
- **Never:** glossy CGI, chrome, glass, photo-real cutouts, hard-bevel 3D, cold corporate look.

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Do not turn a structured promotion into a purely playful scene. The plush props should support the same offer hierarchy.
- Keep one dominant focal subject; the fluff should not bury the product or the message.
- Leave a lower-detail, calm color band where exact text and logos will be placed.

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** felt background, plush props, decorative frame, yarn details, icons, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a plush treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the plush visual layer and plan a text overlay.
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

- `palettes.md`: plush-compatible color palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The plush material reads as a designed fiber miniature, not noise or clutter.
- One metaphor dominates and the focal subject is not buried in fluff.
- Layer order and shadow direction are coherent.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, or `high-end-color-blocking-poster`. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

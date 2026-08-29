---
name: fabric-patchwork-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a fabric patchwork / fabric-cut / hand-sewn collage poster with layered patchwork cloth, raw frayed edges, visible running-stitch seams, fabric buttons, and a warm natural zako/Japanese-craft texture. Use when the user asks for布艺拼接海报、布艺裁剪海报、拼布海报、手缝布贴海报、碎花布拼贴海报、布料贴布海报、日式杂货风海报或把普通海报改成布艺拼接裁剪风；do not activate for generic color palette, watercolor, crayon, paper collage, torn-paper, plush, clay, or photorealistic poster tasks."
metadata:
  short-description: 布艺拼接裁剪手缝风海报重绘 Skill
---

# Fabric Patchwork Poster

Use this skill to turn an ordinary poster, product brief, or campaign key visual into a fabric patchwork / fabric-cut / hand-sewn collage poster. It reinterprets the artwork as layered cloth patches with raw frayed edges, hand-sewn running stitches, and fabric buttons while preserving the source poster's communication job.

This skill is independent from `ghibli-animation-poster`, `crayon-scribble-poster`, `monument-valley-poster`, `riso-print-redesign-poster`, `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, and `high-end-color-blocking-poster`. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster, product, or key visual into a fabric patchwork / fabric-cut collage;
- create a patchwork-cloth, hand-sewn, or 拼布/布贴 poster concept, prompt, or key visual;
- redesign a campaign visual with layered cloth, frayed edges, and stitching;
- preserve a poster's message while changing its material to warm fabric patchwork.

Do not use it for a normal poster, flat vector, watercolor, crayon, paper collage, torn-paper, plush, clay, or photorealistic poster task.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, patchwork, background, crop, and decorative elements.
2. **Choose one central patchwork metaphor** (e.g. a cloth product on a quilted field, a stitched path for a journey, a patch of floral fabric for a home offer). Do not scatter unrelated cloth scraps.
3. **Build a readable depth stack** (background cloth field → layered patchwork patches → hero subject made of fabric → foreground accents/buttons → reserved text zones). Each layer needs a visible edge and soft fabric shadow.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

Fabric patchwork means a warm natural cloth collage, not paper cut-out or a digital texture filter. Use:

- layered patchwork of different fabrics: linen, canvas, gingham/check, floral print, plain cotton, denim, felt
- raw frayed edges and visible loose thread/warp at cut borders; fabric is cut, not torn
- visible hand-running-stitch seams (uneven stitch spacing) tracing patch edges, and stitch details like French knots or cross-stitch marks
- fabric buttons and small fabric shapes: round/square buttons with thread cross-holes, cloth stars, hearts, bows, string/ribbon accents
- a matte, tactile, slightly dimpled fabric surface with real woven texture; soft natural light and gentle cast shadows
- a warm, hand-made, zako/Japanese-craft, everyday-heartwarming mood — never sleek, glossy, or corporate-hard

## Composition rules

- Preserve the source poster's information order and main layout logic unless the user asks for a redesign. Keep top brand/title, central product scene, offer module, QR/action area, and service/legal area in comparable positions.
- Keep one dominant focal subject made of fabric, and a calmer cloth background so the headline stays legible.
- Let the patchwork patches and stitches organize mass and texture without crowding the canvas.
- Leave a lower-detail, calmer fabric zone where exact text and logos will be placed.

## Default background cloth (and variants)

Default to a single continuous piece of **gingham / check cloth** as the whole backgroud. It must **cover the full canvas edge-to-edge** — a single unbroken cloth, no exposed other substrate, no blank margin, no patchwork-jumble background. Keep the background cloth even and calm; place decorative patches and accents only around the subject, not across the whole ground.

Optional alternate grounds (only when the user explicitly names one):
- **linen (棉麻)** — natural fine weave, calm, soft
- **canvas (帆布)** — coarser weave, more grain and texture
- **gingham / check (格纹)** — default, clear check pattern, more lively

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** patchwork cloth, fabric props, stitching, buttons, decorative accents, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a fabric treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the fabric visual layer and plan a text overlay.
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

- `palettes.md`: fabric patchwork palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- The fabric reads as a designed patchwork, not a paper collage or digital texture.
- The background cloth (gingham by default) covers the full canvas edge-to-edge with no exposed substrate or blank margin.
- One focal subject dominates and is not buried in cloth scraps.
- Stitches, frayed edges, and buttons are coherent and add warmth without clutter.
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `ghibli-animation-poster`, `crayon-scribble-poster`, `monument-valley-poster`, `riso-print-redesign-poster`, `plush-animation-poster`, `clay-animation-poster`, `torn-paper-relief-poster`, `paper-collage-poster`, or `high-end-color-blocking-poster`. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

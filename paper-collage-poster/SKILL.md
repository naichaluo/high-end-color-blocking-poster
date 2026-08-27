---
name: paper-collage-poster
description: "Turn an ordinary poster, product brief, or campaign key visual into a paper-cut or paper-collage advertising poster concept. Use when the user asks for剪纸海报、纸艺拼贴广告海报、纸片定格风海报、纸张层叠视觉或把普通海报改成纸艺广告；do not activate for generic color-palette or ordinary poster tasks."
---

# Paper Collage Poster

## Purpose

Create a standalone paper-collage advertising interpretation of an existing poster or brief. Preserve the communication job while changing the visual language to layered paper, cut edges, tactile fibers, cast shadows, and editorial advertising composition.

This skill is independent from any color-blocking, luxury-palette, or other poster skill. Do not import or append another skill's palette rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- turn an ordinary poster into a paper-cut, paper-art, torn-paper, or collage advertisement;
- redesign a campaign key visual as a handmade paper assembly;
- create a paper-collage poster concept, prompt, key visual, or ad storyboard;
- preserve a poster's message while changing its material and visual metaphor.

Do not use it for a normal poster, logo, or palette request with no paper/collage transformation.

## Non-negotiable decisions

1. Separate locked communication from visual reinterpretation. Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret composition, material, depth, metaphor, crop, and decorative elements.
2. Choose one central visual metaphor that can carry the whole poster. Examples: a paper road for a service journey, a folded map for local reach, layered doors for access, a paper wave for sound/data, or a cut-paper toolbox for bundled services. Do not fill the canvas with unrelated scraps.
3. Build a readable depth stack: background field, environmental shapes, primary subject, secondary cutouts, typography/brand overlay. Each layer needs a clear edge and a believable paper shadow.
4. Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays. Do not ask an image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. The poster must still work at thumbnail size. Establish one focal object, one headline zone, one supporting-information zone, and a clear CTA or next action.

## Workflow

### 1. Extract the brief

Identify the audience, product or event, promise, required copy, CTA, output size, brand assets, and whether the user wants only a concept, a ready-to-copy prompt, a generated image, or a complete poster package. If the source poster is provided, inspect its hierarchy before proposing changes.

### 2. Write the creative angle

State one sentence in this form:

> The poster turns **[core message]** into **[paper metaphor]**, so the audience immediately understands **[benefit/action]**.

Reject decorative concepts that do not clarify the message.

### 3. Define the paper system

Specify the paper material, cut technique, edge character, shadow direction, depth order, focal crop, and restrained texture. Use visual language such as die-cut paper, torn fiber edge, folded stock, layered card, screen-printed ink, halftone, emboss, deckled edge, and soft cast shadow. Avoid generic "beautiful collage" wording.

Read `references/paper-collage-poster-method.md` when producing a detailed concept, prompt pack, or keyframe plan.

### 4. Produce the poster plan

Return, in order:

1. Creative angle and audience takeaway.
2. Locked copy/assets versus visual elements to reinterpret.
3. Layer map with 4–7 layers and each layer's role.
4. Composition and focal hierarchy.
5. A generation prompt that describes only the visual artwork and leaves text/logo/QR space clean.
6. A post-production overlay list for exact text, logos, QR codes, and legal information.
7. A negative prompt covering photorealism, glossy 3D, plastic CGI, chaotic scrapbooking, unreadable text, fake logos, duplicate objects, and visual clutter.
8. If requested, 2–3 restrained variants that change the metaphor or crop, not the brand message.

### 5. If the user asks for an actual image

Use the image generation capability with the user's poster as a reference when available. For an edit, preserve the locked subject and message while changing only the material/composition requested. After generation, inspect the result for readable hierarchy, paper depth, accidental text, malformed logos, and empty overlay zones. If exact copy is required, compose it after image generation instead of trying to repair model-generated typography.

### 6. Optional ad extension

Only if the user asks for motion or a video concept, convert the poster into a short paper-assembly storyboard: empty paper field → primary cutout enters → secondary layers settle → headline/CTA overlay appears → final hold. Keep the poster as the visual anchor. This skill does not automatically create a full video, voice track, or MP4.

## Quality gate

Before delivery, check:

- the original communication goal is still obvious;
- the paper material is visible without becoming childish or craft-like;
- one metaphor dominates and the focal subject is not buried;
- the layer order and shadow direction are coherent;
- the poster has a clean area for exact text and brand overlays;
- no invented facts, prices, dates, logos, URLs, or QR codes were introduced;
- the negative prompt explicitly suppresses fake typography and visual clutter;
- the output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `high-end-color-blocking-poster`, `paper-collage-ad`, or any other style skill. If the user wants a combined result, name the combination and describe which rules come from each skill before proceeding.

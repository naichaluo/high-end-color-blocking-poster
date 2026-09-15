---
name: flat-spot-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a white-margin flat spot illustration poster that keeps the source poster's original dimensions and aspect ratio — editorial spot illustration, mid-century modern flat style, cut-paper collage shapes, opaque gouache color blocking, and a matte screen-print finish, printed as a quiet small picture at the center of a warm-white sheet — while preserving the source poster's exact business content, hierarchy, brand assets, and typography. Use when the user asks for留白平涂小景海报、平涂小景插画海报、不透明水粉平涂海报、剪纸拼贴感平涂海报、editorial spot illustration 海报、mid-century modern flat 海报、哑光丝网印插画海报或把普通海报改成留白平涂小景风；do not activate for generic color palette, watercolor, crayon, plush, clay, or photorealistic poster tasks."
metadata:
  short-description: 留白平涂小景风海报重绘 Skill
---

# Flat Spot Poster / 留白平涂小景海报

把普通海报、产品描述或营销主视觉，重绘成 **「留白平涂小景」插画风**广告：像印在暖白纸中央的一张安静小画。**画布保留源海报的原始尺寸与宽高比。****只改变视觉语言，不改变商业内容。**

**风格锁定**：editorial spot illustration、mid-century modern flat illustration、cut-paper collage shapes、opaque gouache color blocking、matte screen-print finish。

**不需要风格参考图。源海报是唯一内容源。**

This skill is independent from every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成「留白平涂小景」风、平涂插画风、不透明水粉平涂风、剪纸拼贴感平涂风；
- create an editorial spot illustration / mid-century modern flat illustration poster;
- render a poster with opaque gouache color blocking, cut-paper collage shapes, and a matte screen-print finish;
- turn a commercial key visual into a quiet small picture printed at the center of a warm-white sheet.

Do not use it for a normal poster, watercolor, crayon, plush, clay, pixel, or photorealistic task with no flat-spot transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, flat shapes, composition, crop, and decorative elements.
2. **Choose one central scene unit** built from the source poster's most recognizable subject. Do not scatter unrelated objects.
3. **Build a readable depth stack**: warm-white sheet → central compact scene unit → flat color planes → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

Flat spot means an editorial print-like small picture, not a photo filter, vector art, or 3D render. Use:

- editorial spot illustration × mid-century modern flat illustration
- cut-paper collage shapes: hard-edged, layered, plain silhouettes
- opaque gouache color blocking: fully matte flat fills, no interior gradients
- matte screen-print finish: extremely light paper grain, scan noise nearly invisible
- **正面平视、近似正交投影**；空间压成少量二维层，以遮挡、位置和明度区分，**前后同等清晰**
- 用**几何剪影和连续色面**重画；人物保留脸型、发型、服装大形和接触点，**五官衣褶只留少量短笔**
- 无景深、虚化、汇聚透视、写实材质或 3D

## Composition rules

- **暖白画布，保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。源海报的视觉主体重组为**中央紧凑场景单元，占宽高 72%–78%**，四边保留**连续、近等宽留白**（留白是空的暖白纸，不是画上去的色块）。
- **外轮廓绝非规则矩形**：边界必须由场景自身的形状不规则收口——天空/远山/树冠/屋顶轮廓打破上缘，地面/台面/台阶自然边缘收下缘，左右由树木、建筑、灯柱、人物或物件轮廓不规则收口；允许主体、投影或物件自然越过边界延伸到留白上。**不要四条笔直线边界，不要把照片缩进方块**，不要贴边、裁切、出血或加外框。
- **保留源海报的信息顺序与主布局逻辑**：顶部品牌/标题、中部产品场景、下方优惠模块、QR/行动区、底部服务/法务区的位置关系保持可比。
- 留出平静、低细节的暖白区域，供精确文字与 logo 叠加。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** flat spot scene, product silhouettes, decorative shapes, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt（逐字引用源海报文案，含价格、券额、号码、二维码位置说明），but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

**文字必须保留**：不得把源海报的文字与 Logo 化为不可读色块，不得删改价格、券额、日期、电话、URL、二维码或法务字样。

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the flat-spot visual layer and plan a text overlay.
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

- `palettes.md`: flat-spot palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- Does the canvas keep the source poster's original dimensions and aspect ratio, on a warm-white sheet, with the central scene unit at 72%–78% and continuous near-equal margins?
- Is the outer contour **not** a rigid rectangle, formed instead by the scene's own shapes?
- 正面平视、近似正交，前后同等清晰，几何剪影 + 连续色面。
- Is the palette about 7–9 colors, fully matte flat, with no watercolor marks, broken color, or gradients?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly and readable?**
- Are source text and logos **not** reduced to unreadable blocks?
- The poster has a clean area for exact text and brand overlays.
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

---
name: knitted-yarn-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a hand-knitted / crocheted yarn art poster — the whole picture built from chunky yarn, crochet stitches, and hand-wound wool: clear stitch-loop texture, visible yarn fuzz, handmade textile craft quality, soft indoor diffused light, a clean pale-beige ground, arranged as a top-down still life — while preserving the source poster's exact business content, hierarchy, brand assets, and typography. Use when the user asks for针织毛线海报、毛线钩织海报、钩针编织海报、绒线手工海报、粗毛线艺术海报、毛线质感海报、针织静物海报或把普通海报改成针织毛线风；do not activate for wool-felt/plush, fabric patchwork, clay, paper, or photorealistic poster tasks."
metadata:
  short-description: 针织毛线手工艺术风海报重绘 Skill
---

# Knitted Yarn Poster / 针织毛线艺术海报

把普通海报、产品描述或营销主视觉，重绘成 **针织毛线手工艺术风**广告：整个画面全部由粗毛线、钩针编织、绒线手工制作而成。**只改变视觉语言，不改变商业内容。**

This skill is independent from `plush-animation-poster`（毛绒/羊毛毡）、`fabric-patchwork-poster`（布艺拼接）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成针织毛线风、毛线钩织风、钩针编织风、绒线手工风、毛线质感风；
- build a poster where every object, figure, and scene element is knitted or crocheted from yarn;
- create a top-down handcrafted yarn still-life poster with visible stitch loops and yarn fuzz;
- redesign a campaign visual as a refined hand-knitted art piece.

Do not use it for wool-felt/needle-felt plush, fabric patchwork/quilting, clay, paper, or photorealistic tasks with no knitted-yarn transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, stitch construction, arrangement, and decorative elements.
2. **Choose one central hand-knitted subject cluster** built from the source poster's most recognizable subjects. Do not scatter unrelated props.
3. **Build a readable depth stack**: pale-beige ground → knitted scene unit → yarn props → reserved clean text zones.
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** Establish one focal subject, one headline zone, one supporting-info zone, and a clear CTA.

## Style definition

Knitted yarn art means a real handcrafted textile object, not a fuzzy filter or a photo of wool texture.

- **全部毛线化**：画面里的每一个物体、人物、景物都由毛线钩织而成——产品、水果、吉祥物、植物、道具全部是钩针/棒针作品。
- **清晰的毛线线圈纹理**：看得见一针一针的线圈（V 形针脚）、辫子针边缘、起针/收针痕迹、缝合接口。
- **看得见的纱线毛絮**：毛线表面有细密绒毛与飞絮，边缘有毛茸茸的光晕。
- **手工布艺质感**：填充饱满而有轻微不规整，针距略有变化，收口处有手工痕迹。
- **柔和室内柔光**：均匀漫射的室内光，柔和短投影，无强烈高光。
- **干净浅米色背景**：浅米/象牙色平底，干净、素净、无杂物。
- **静物俯拍**：主体以俯视平铺（flat-lay）方式排列成一组手工静物。
- **精致手工艺术品**：像一件被精心拍摄的高级手工作品，而不是儿童手工或地摊毛线玩具。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。
- 源海报的视觉主体重组为**中央紧凑的针织静物组合**，占宽高 **72%–78%**，四边保留连续、近等宽留白。
- **保留源海报的信息顺序与主布局逻辑**：顶部品牌/标题、中部产品场景、下方优惠模块、QR/行动区、底部服务/法务区，位置关系保持可比。
- 留出平静、低细节的浅米色区域，供精确文字与 logo 叠加。
- 不要把画面做成一堆散乱毛线球；组合要有主次与秩序。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** knitted scene, yarn props, stitch textures, and non-critical labels
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

When using image generation, quote required text verbatim in the prompt（逐字引用源海报文案，含价格、券额、号码、二维码位置说明），but still verify and correct it afterward. If a logo or QR code must remain functional, paste it from the source or approved brand asset instead of asking the image model to invent it.

**文字必须保留**：不得把源海报的文字与 Logo 化为不可读色块，不得删改价格、券额、日期、电话、URL、二维码或法务字样。

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
4. If exact text matters, generate only the knitted visual layer and plan a text overlay.
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

- `palettes.md`: yarn palettes and material treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- The original communication goal is still obvious at thumbnail size.
- Does the canvas keep the source poster's original dimensions and aspect ratio, on a clean pale-beige ground, with the central scene unit at 72%–78%?
- Is **every** object, figure, and scene element genuinely knitted/crocheted from yarn?
- Are stitch loops (V stitches, chain edges, seams) clearly visible, with visible yarn fuzz?
- Does it read as a refined handcrafted textile art piece rather than a fuzzy filter, fuzzy toy, or children's craft?
- Is the light soft and indoor-diffused, with gentle shadows and no harsh highlights?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly and readable?**
- Are source text and logos **not** reduced to unreadable blocks?
- No invented facts, prices, dates, logos, URLs, or QR codes were introduced.
- The output is clearly identified as concept, prompt, generated visual, or final composite.

## Scope boundary

Do not silently merge this skill with `plush-animation-poster`, `fabric-patchwork-poster`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

---
name: dopamine-abstract-vector-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a refined avant-garde dopamine abstract vector illustration — minimalist foundation, rhythmic abstract lines and sweeping curved linework, saturated dopamine color families, irregular arc-shaped color blocks of varied form, lines and blocks set off against each other, natural softness balanced with fine decorative elements, and surreal fantasy expression. Use when the user asks for多巴胺抽象矢量海报、多巴胺矢量插画海报、抽象矢量海报、先锋矢量插画海报、曲面线条抽象海报、不规则弧形色块海报、多巴胺配色海报、超现实抽象海报、abstract vector poster 或把普通海报改成多巴胺抽象矢量风；do not activate for flat vector icon sets, riso/screen-print posters, watercolor, crayon, paper-art, 3D, or photorealistic poster tasks."
metadata:
  short-description: 多巴胺抽象矢量插画风海报重绘 Skill
---

# Dopamine Abstract Vector Poster / 多巴胺抽象矢量海报

把普通海报、产品描述或营销主视觉，重绘成**一幅精致、先锋艺术导向的矢量插画**。

最终效果像**当代先锋艺术家的矢量版画作品**：以极简主义为核心基调，用富有韵律感的抽象线条与曲面线条，搭配色彩饱满的多巴胺色系，以形态各异的不规则弧形色块构成层次分明的画面——线条与色块相互映衬，既保留自然的柔和质感，又融入精致的装饰元素，并带有超现实派的奇幻表达。

**只改变视觉语言，不改变商业内容。**

This skill is independent from `high-end-color-blocking-poster`（高级撞色）、`flat-spot-poster`（留白平涂小景）、`riso-print-redesign-poster`（RISO 丝网印刷）、`paper-collage-poster`（纸艺拼贴）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成多巴胺抽象矢量风、多巴胺矢量插画风、抽象矢量海报风、先锋矢量插画风；
- 做曲面线条 / 韵律线条 / 不规则弧形色块的抽象海报；
- create an abstract vector illustration poster with a dopamine palette;
- render a key visual as a refined avant-garde vector artwork with surreal fantasy expression;
- give a campaign visual a modern minimal vector-art gallery feel.

Do not use it for flat vector icon sets, logo or UI design, RISO / screen-print redesign, watercolor, crayon, paper-art, plush, clay, 3D, or photorealistic tasks. Do not use it when the user only wants a palette swap with no shape-language transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret only line language, arc-block geometry, color-block arrangement, and decorative elements.
2. **严格保留原图内容**：保留原始图片的**主体、人物/动物/建筑/物体的身份特征、动作姿态、空间关系、主要构图和视觉焦点**，**不改变原图所表达的场景内容**。抽象化只作用于**造型语言与背景装饰**，不得把主体抽象到无法辨认。
3. **Build a readable vector depth stack**: 干净浅色底（可含大量留白）→ 大块不规则弧形色块层 → 韵律线条 / 曲面线条层 → 精致装饰元素层 → 与图形同系统的文字。深度靠**色块叠压、线条疏密与色彩对比**建立，不靠透视、阴影或 3D。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 主体的身份特征、视觉焦点与色彩层级必须一眼可辨；抽象装饰不得吃掉主体轮廓。

## Style definition

精致先锋艺术导向的**矢量插画（vector illustration）**，以**极简主义（minimalism）为核心基调**。

**媒介与线条**：

- 纯矢量语言：边缘**干净利落、精确**，色块为**纯色平面填充**，不使用笔刷毛边、纸张颗粒或颜料肌理（那是其他 skill 的语言，本风格不要）。
- 运用**富有韵律感的抽象线条与曲面线条（rhythmic abstract lines & sweeping curved linework）**：线条有明确的**粗细变化与节奏**，细线如发丝、主线略粗，成组、成束、平行或同心展开，形成明显的**视觉流动方向与韵律感**。
- **曲面线条**要**平滑流畅、弧度舒展、收放有致**；避免机械等距套环与呆板重复。

**色块与形态**：

- **形态各异的不规则弧形色块**：每个色块形状都不同，以**弧边、肾形、泪滴形、云朵形、半月形、水滴形、柔软的有机不规则形**为主；避免标准正圆、正方、等宽条带等僵硬几何。
- 色块**大小、比例、方向各不相同**，相互**叠压、穿插、留缝**，形成**层次分明（clear layering）**的视觉效果。
- **线条与色块相互映衬**：留白处的线条进入色块、色块边缘被线条勾勒或切分、线条沿色块外缘流淌——两者互相成就，而不是各画各的。

**色彩（多巴胺色系）**：

- **色彩饱满的多巴胺色系（saturated dopamine palette）**：明度高、纯度高、愉悦明亮，色相跨度大且有对比；多巴胺感来自**饱和度与明度的饱满**，不是荧光刺眼。
- 允许**大胆撞色与互补对比**，但**层次必须分明**：主色占大面积，辅色与强调色小面积点亮，形成清楚的色彩层级而不是平均铺满。
- 具体色名见 `palettes.md`。

**质感与装饰**：

- **既保留自然的柔和质感，又融入精致的装饰元素**：弧线的柔和过渡与干净的矢量面并存；装饰元素要**克制、精致、有设计感**（细点阵、短线组、小几何符号、微小的放射与波纹），不做无意义堆砌。
- 融入**超现实派的奇幻表达（surreal fantasy expression）**：比例与空间的轻度错置、悬浮的元素、不符合物理的色块流动、梦境般的空间逻辑——但必须是**克制、优雅的超现实**，不是怪诞或恐怖。

**整体气质**：凸显**先锋艺术的独特气质（avant-garde）**；现代、精致、愉悦、有设计感和收藏感的当代艺术插画。

## Style preset (compact English keywords)

生成时把下面这个关键词块**追加到提示词末尾**（英文 art-direction 关键词模型遵循度更稳）：

```text
STYLE_PRESET: Avant-garde Dopamine Abstract Vector Illustration
CORE: vector illustration, minimalist foundation, rhythmic abstract lines, sweeping curved linework,
irregular arc-shaped color blocks, lines and blocks set off against each other, clear layering,
refined decorative elements, surreal fantasy expression, avant-garde
MEDIUM: clean vector, flat solid fills, crisp edges, no brush texture, no paper grain, no pigment noise
LINE: varied-weight rhythmic lines, hairline accents plus slightly heavier leads, sweeping smooth arcs,
flowing direction, grouped and bundled linework
SHAPE: kidney shapes, teardrop forms, cloud lobes, half-moon arcs, soft organic irregular blocks;
no perfect circles, no squares, no uniform bands
COLOR: saturated dopamine palette, bright high-chroma, high value, wide hue spread with contrast,
large primary field plus small accent pops, distinct color hierarchy
COMPOSITION: preserve original composition, preserve subject identity, generous light negative space,
overlapping blocks, layered depth through overlap and line density only
MOOD: modern, refined, joyful, gallery, editorial, avant-garde, collectible
AVOID: photorealistic, 3D, render, gradient mesh, neon glow, blur, drop shadow, watercolor, crayon,
paper grain, halftone, riso, cartoon, childish, cluttered, perfect circles, template layout
```

> 注意：`preserve original composition / preserve subject identity` 只覆盖**画面**。
> 商业文案、价格、券额、二维码、品牌名的保留仍按本 skill 的「Text and brand handling」执行。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。不得改成正方形，不得裁切版式。
- **保留大量留白 / 浅色底**：极简主义基调要求画面有**呼吸区**；留白由干净的浅色背景承担，是画面构成的一部分。
- **主体仍是画面焦点**：抽象线条与弧形色块围绕主体展开，可以叠压主体的边缘与背景，但**不得覆盖主体的识别特征**（五官、姿态、产品轮廓、logo 的完整性）。
- **保留源海报的信息顺序与层级关系**（品牌/标题 → 主体场景 → 卖点/优惠 → QR/行动区 → 服务/法务），但**允许按矢量海报的现代版式重新排布**。
- **不得为了"极简美学"删减、弱化或省略源海报的必需信息**。留白是靠**布局**腾出来的，不是靠删信息换来的。
- 避免填满画面、避免色块平均铺满、避免装饰元素堆砌、避免机械居中与模板化版式。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 主体矢量重绘、不规则弧形色块、韵律线条与曲面线条、精致装饰元素、留白底
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案。本风格容易诱发模型"顺手加一行装饰英文"，必须显式禁止。
- 文字可以用**与图形同系统的现代简约字体**排版（几何无衬线、克制的字重、干净的宽字距），但**必须清晰可读**，且**不得把文字或 logo 化为不可读色块**——**不得把文字做成抽象线条或弧形色块的形状**。
- 文字承载区应为**干净、低细节的浅色区域**，不要在线条密集或撞色交界上压字，保证对比度。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被弧形色块叠压、被线条穿过、被旋转、被裁切或被重新配色。线条语言越强，这些资产越容易被当成"线条素材"穿过去，因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码保持完整清晰可扫描，不要被线条穿过、不要被色块覆盖、不要旋转或裁切、不要改变配色」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Note the content to preserve strictly: subjects, identity features, pose, spatial relations, main composition, visual focus.
4. Choose a dopamine palette from `palettes.md` and a prompt pattern from `prompt-templates.md`.
5. Build the vector depth stack in order: 浅色底 → 不规则弧形色块 → 韵律线条 / 曲面线条 → 精致装饰元素 → 文字预留区。
6. If exact text matters, generate only the vector visual layer and plan a text overlay.
7. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
8. Review the result against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks
- no decorative English headline or fake artist signature invented by the model

## Supporting files

- `palettes.md`: 多巴胺色系色盘、线条与弧形色块的语言规格。
- `prompt-templates.md`: 主模板 + 纯视觉底图模板 + 出图前自检表。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio?
- Are subjects, identity features, pose, spatial relations, main composition and visual focus **strictly preserved** and still recognizable?
- Is the language genuinely **vector** — clean crisp edges and flat solid fills — with **no** brush texture, paper grain, pigment noise, or halftone?
- Are the lines **rhythmic** with real weight variation and flow direction, and are they **sweeping smooth arcs** rather than mechanical concentric rings?
- Are the color blocks **irregular arc-shaped forms of genuinely varied shape** (kidney / teardrop / cloud-lobe / half-moon), and free of perfect circles, squares, and uniform bands?
- Do **lines and blocks set off against each other** (lines entering blocks, tracing block edges, splitting them) rather than sitting in separate zones?
- Is the palette **saturated dopamine** — bright, high-chroma, wide hue spread — yet with a **clear hierarchy** (large primary field plus small accent pops), not flatly spread or neon-glaring?
- Is there **generous negative space / light ground**, and is the page not filled edge to edge?
- Is the natural softness of the curves balanced with **restrained, refined decorative elements**, rather than decoration piled on?
- Is the surreal fantasy expression **restrained and elegant** (floating elements, dreamlike spatial logic, non-physical block flow) rather than grotesque?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly and readable?**
- Is the result free of **invented copy**, **fake decorative English headlines**, and **fake signatures**?
- Is the result free of 3D, photorealism, drop shadows, gradient mesh, neon glow, blur, watercolor, crayon, riso, and cartoon looks?
- Is the result free of information clutter, random decoration piles, and template layout?
- Does it read as a **refined avant-garde vector artwork** with gallery-quality design sense?

## Scope boundary

Do not silently merge this skill with `high-end-color-blocking-poster`（高级撞色大色块）、`flat-spot-poster`（留白平涂小景）、`riso-print-redesign-poster`（RISO 丝网印刷）or any other poster skill.

Key distinctions:

- vs `high-end-color-blocking-poster`: 那个风格靠**巨大平面色块 + 编辑感排版 + 印刷质感**做高级感；本风格的核心是**韵律线条 + 不规则弧形色块 + 超现实奇幻表达**，色块是流动的有机弧形而非方正的平面块。
- vs `flat-spot-poster`: 那个风格是**小图画在暖白大纸中央**的留白平涂小景；本风格是**满版平衡的矢量艺术构成**，线条是主角之一。
- vs `riso-print-redesign-poster`: 那个是**限色油墨、硬边轮廓、套准纸缝与半色调颗粒**的丝网印；本风格是**纯色平面的干净矢量**，明确不要颗粒、网点与套准痕迹。

If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

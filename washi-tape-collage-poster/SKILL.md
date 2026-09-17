---
name: washi-tape-collage-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a refined journal washi-tape collage illustration — handmade paper collage, journal collage, torn paper collage and washi tape collage on warm cream / old-paper stock, with naturally torn lifted edges, layered translucent and magazine papers, hand-dyed sheets, visible paper fibre, creases, grain and dry-pigment marks, slightly misaligned pieces, and real tape holding the page — while preserving the source poster's exact business content, hierarchy, brand assets, and typography. Use when the user asks for手账纸胶带拼贴海报、纸胶带拼贴海报、手账拼贴海报、撕纸拼贴海报、复古手账拼贴海报、旅行手账拼贴海报、washi tape collage 海报、journal collage 海报或把普通海报改成手账纸胶带拼贴风；do not activate for plain paper-cut collage, torn-paper relief, flat illustration, or photorealistic poster tasks."
metadata:
  short-description: 手账纸胶带拼贴插画风海报重绘 Skill
---

# Washi Tape Collage Poster / 手账纸胶带拼贴海报

把普通海报、产品描述或营销主视觉，重绘成 **精致的手账纸胶带拼贴插画**。

最终效果像**一本高级旅行手账中撕下来的手工拼贴页面**：真实的纸张触感、手工制作痕迹、轻微的不完美——简洁、安静、文艺、温暖、复古、高级。

**只改变视觉语言，不改变商业内容。**

This skill is independent from `paper-collage-poster`（剪纸/纸艺拼贴）、`torn-paper-relief-poster`（撕纸立体浮雕）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成手账纸胶带拼贴风、纸胶带拼贴风、手账拼贴风、撕纸拼贴风、复古/旅行手账拼贴风；
- create a paper collage / journal collage / torn paper collage / washi tape collage poster;
- render a key visual as a page torn from a premium travel journal;
- give a campaign visual a vintage lifestyle-magazine collage feel.

Do not use it for plain paper-cut collage, torn-paper relief, flat illustration, or photorealistic tasks with no collage transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, paper layering, arrangement, and decorative elements.
2. **严格保留原图内容**：保留原始图片的**主体、人物/动物/建筑/物体的身份特征、动作姿态、空间关系、主要构图和视觉焦点**，**不改变原图所表达的场景内容**。
3. **Build a readable stack**: 底纸（米白/奶油/旧纸色）→ 底层纸片 → 主体拼贴层 → 纸胶带固定 → 与图形同系统的文字。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 主体的身份特征与视觉焦点必须一眼可辨。

## Style definition

手工纸艺拼贴（paper collage）× 手账素材（journal collage）× 撕纸拼贴（torn paper collage）× 纸胶带拼贴（washi tape collage）。

**底纸**：温暖的米白色、奶油白、旧纸张色，具有**真实的手账本纸张质感**。

**构成**：主体由大量**不规则撕裂的彩色纸片、半透明纸张、旧杂志纸、手工染色纸、薄水彩纸和纸胶带**逐层拼贴组成。

**必须明显具有"真实手工制作"的感觉（不要表现为普通数字绘画）**：

- 纸张边缘**自然撕裂、不规则、略微翘起**；
- 不同纸片之间存在**明显的重叠关系**；
- 可以看到**纸张纤维、细微褶皱、颗粒、纤维毛边、干燥颜料痕迹和轻微透明感**；
- 部分纸片颜色**深浅不均匀**，存在自然的手工染色和颜料晕染；
- 局部纸片**略微错位**，呈现真实手工拼贴产生的不完美感。

**造型方式**：主体的**明暗、轮廓和体积由不同颜色和深浅的纸片拼接形成**，而**不是用传统线稿描绘**。使用**少量概括性的纸片**表达细节，避免过度精细；保留关键轮廓和特征，但将细节适当简化为**具有设计感的几何纸片**。

**纸胶带固定效果**（少量、真实）：

- 半透明米色胶带、灰色胶带、旧纸胶带；
- 胶带**边缘不规则**；
- 能够看到**胶带半透明后的底层纸张**；
- 胶带像是**真实贴在纸面上**，而不是画出来的装饰。

## Style preset (compact English keywords)

生成时把下面这个关键词块**追加到提示词末尾**（英文 art-direction 关键词模型遵循度更稳）：

```text
STYLE_PRESET: Handmade Journal Paper Collage
CORE: paper collage, torn paper, washi tape, hand-painted paper, watercolor paper texture,
visible paper fibers, layered paper, handmade imperfections
MATERIAL: cream paper, old paper, watercolor paper, semi-transparent paper, washi tape, torn edges
COLOR: muted vintage, cream, beige, dusty blue, gray blue, ochre, terracotta, olive green, soft brown
COMPOSITION: preserve original composition, preserve subject, minimal background, large negative space
TEXTURE: paper fibers, rough torn edges, paper grain, pigment variation, subtle wrinkles,
layer overlap, slight misalignment, handmade texture
MOOD: warm, quiet, nostalgic, artistic, travel journal, editorial, minimal, premium
AVOID: digital illustration, vector, cartoon, 3D, plastic, perfect edges, oversaturated, photorealistic
```

> 注意：`preserve original composition / preserve subject` 只覆盖**画面**。
> 商业文案、价格、券额、二维码、品牌名的保留仍按本 skill 的「Text and brand handling」执行。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。
- **背景保持大量留白，不要填满整个画面**；留白是底纸本身的米白/奶油/旧纸色。
- **主体周围可以散落少量**撕纸、纸胶带、半透明纸片和手绘色块，形成自然的**手账排版感**。
- **保留源海报的信息顺序与层级关系**（品牌/标题 → 主体场景 → 卖点/优惠 → QR/行动区 → 服务/法务），但**允许按手账拼贴的松弛排版重新排布**。
- **不得为了"留白美学"删减、弱化或省略源海报的必需信息**。留白是靠**布局**腾出来的，不是靠删信息换来的。
- 避免填满画面、避免信息堆积、避免随机装饰堆砌。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 拼贴主体、纸片层、纸胶带、底纸留白、装饰性纸屑
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案。
- 文字可以做成**手账式排版**（手写标签纸、纸条、打字机字体），但**必须清晰可读**，且**不得把文字或 logo 化为不可读色块**。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被拼贴、撕裂、错位或纸片层叠覆盖。拼贴指令越强，这些资产越容易被当成"纸片素材"撕碎，因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码保持完整清晰可扫描，不要撕碎、不要用纸片或胶带覆盖、不要错位」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Note the content to preserve strictly: subjects, identity features, pose, spatial relations, main composition, visual focus.
4. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
5. If exact text matters, generate only the collage visual layer and plan a text overlay.
6. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
7. Review the result against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks

## Supporting files

- `palettes.md`: low-saturation vintage journal palettes and paper treatments.
- `prompt-templates.md`: reusable prompts for style transfer and poster generation.
- `examples/`: example briefs and prompt applications.

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio?
- Are subjects, identity features, pose, spatial relations, main composition and visual focus **strictly preserved**?
- Is the ground a warm cream / old-paper stock with **real journal-paper texture**?
- Are there **large areas of white space**, not a filled page?
- Are paper edges naturally torn, irregular and slightly lifted, with **clear overlap** between pieces?
- Are paper fibre, fine creases, grain, fibrous burrs, dry-pigment marks and slight translucency visible?
- Are some pieces unevenly toned, with natural hand-dyeing and pigment bleed?
- Are a few pieces slightly misaligned, giving real handmade imperfection?
- Is the subject's light-and-shade, contour and volume built from **layered paper of different colours and values**, rather than traditional line drawing?
- Is detail expressed with a **few summary paper shapes**, simplified into designed geometric pieces — not over-detailed?
- Is the palette **low-saturation, soft and vintage** (cream, blue-grey, mist blue, light brown, ochre, khaki, olive, brick red, pale yellow), restrained and warm?
- Are there a few **real washi-tape fixes** (translucent beige / grey / old-paper tape) with irregular edges, showing the underlying paper through the tape — looking genuinely stuck on, not drawn?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly and readable?**
- Does it read as a page torn from a premium travel journal — not digital painting, not a filled scrapbook page?
- Is the result free of information clutter, random decoration piles, 3D, and template layout?
- Is the result free of **perfect / clean-cut edges**, **oversaturation**, **plastic sheen**, **photorealism**, vector and cartoon looks?

## Scope boundary

Do not silently merge this skill with `paper-collage-poster`, `torn-paper-relief-poster`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

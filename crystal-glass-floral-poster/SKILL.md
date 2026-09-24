---
name: crystal-glass-floral-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a contemporary art-exhibition poster whose floral subject is rebuilt entirely from transparent crystal glass — every petal a complete piece of clear crystal glass with a fine gilded gold rim, under bright warm golden light that passes through the glass and casts fine translucent caustics on an aged pale off-white textured paper ground, nested inside a double fine white rounded-corner frame, with a large vintage serif title slot and a small wide-tracked subtitle line in a premium centred museum layout — while preserving the source poster's exact business content, hierarchy, brand assets, and typography. Use when the user asks for水晶玻璃花卉海报、水晶玻璃玫瑰海报、玻璃花卉海报、通透玻璃质感花朵海报、金边玻璃花海报、玻璃折射花卉海报、当代艺术展览海报、画廊展览海报、艺术展海报或把普通海报改成水晶玻璃花卉风；do not activate for plush/felt, knitted yarn, oil impasto, watercolor, paper-cut, or photorealistic flower-photography poster tasks."
metadata:
  short-description: 水晶玻璃花卉当代艺术展览风海报重绘 Skill
---

# 水晶玻璃花卉海报 / Crystal Glass Floral Poster

把普通海报、产品描述或营销主视觉，重绘成一张**当代艺术展览海报**：花卉主体的每一片花瓣都是**完整通透的水晶玻璃**，**边缘带细腻金色描边**，**暖金色明亮光线穿过玻璃投射出细碎通透的光斑**，落在**做旧浅米白纹理纸**上，外部嵌套**双层细白色圆角画框**，顶部是**大号复古衬线英文标题位**与**小字副标题位**，**高级简约居中排版**。

**只改变视觉语言，不改变商业内容。**

This skill is independent from `felt-floral-poster`（毛毡花卉）、`lace-embroidery-poster`（蕾丝刺绣）、`vintage-engraving-floral-poster`（复古刻版画花卉）、`brick-toy-floral-poster`（乐高积木花卉）、`plush-animation-poster`（毛绒/羊毛毡定格）、`knitted-yarn-poster`（针织毛线）、`impasto-miniature-landscape`（厚涂微缩景观）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成水晶玻璃花卉风、水晶玻璃海报、玻璃花卉海报、通透玻璃质感花朵海报、金边玻璃花海报、玻璃折射花卉海报；
- 做成当代艺术展览海报、画廊展览海报、美术馆展览海报、艺术展主题海报；
- create a crystal-glass / transparent-glass floral art-exhibition poster with gilded petal edges and golden caustics;
- render a flower key visual as clear crystal glass on aged paper inside a double white frame;
- give a campaign visual the quiet, premium, museum-catalogue feel of a contemporary art exhibition.

Do not use it for 毛绒/羊毛毡、针织毛线、油画厚涂、水彩、纸艺剪纸、写实鲜花摄影 or any task that does not want the glass material.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, refraction, frame, light and decorative elements — never business content.
2. **Choose one central glass subject** (the most recognizable element of the source) and keep it as the single visual anchor. 主体身份不换：源海报的产品/花卉/物体仍是同一主体，只是**材质被换成水晶玻璃**。不要新增第二束花、不要堆满画面。
3. **Build a readable depth stack**: 做旧浅米白纹理纸底 → 细碎通透光斑层 → 双层细白色圆角画框 → 通透水晶玻璃主体（每片花瓣有厚度、折射、金边、投影）→ 干净的文字预留区。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 玻璃主体的一眼可辨轮廓、标题区、副标题区必须在小尺寸下依然清楚；玻璃要通透但不能糊成一片白。

## Style definition

当代艺术展览海报（contemporary art exhibition poster）× 水晶玻璃（crystal glass）× 暖金光斑（warm golden caustics）。

**画布与版式**：竖版 3:4 艺术展览海报版式，**高级简约居中排版**——顶部为大号复古衬线英文标题位，其下为副标题小字位；整体像美术馆展览海报，安静、克制、干净。

**主体材质（核心，不可简化）**：

- 主体花卉的**所有花瓣完整为通透水晶玻璃材质**（clear crystal glass，不是磨砂塑料、不是亚克力平板、不是水波纹玻璃）；
- 玻璃有**真实厚度与内部体积**：可见花瓣厚薄变化、内部透光、边缘一道明亮的高光线；
- 颜色为**玻璃质感的明黄渐变**（明黄 → 渐变黄，bright yellow → warm golden-yellow gradient），由花瓣根部向边缘渐变，深处略浓、边缘更透亮；
- 允许极克制的内部细节：微弱的色散、细微气泡或流纹（**必须克制，不要做成杂质或脏点**）；
- **每片花瓣边缘带细腻金色描边**：细、均匀、连续的 gilded gold rim，像金箔包边或金线勾边；**不要粗重金框、不要整朵刷成金色**。

**光影（核心，不可简化）**：

- **暖金色明亮光线穿过玻璃**，在纸面上**投射出细碎通透的光斑**（caustics：碎光斑、亮斑、细小光点），分布在花瓣周围与下方，越靠近玻璃越亮；
- **柔和影棚漫射柔光**（soft studio diffused light）为主光，**不要硬边强阴影、不要戏剧性明暗对比**；
- 玻璃与纸面之间有**极浅的柔和阴影**，让主体"坐在"纸面上而不是贴上去。

**背景**：**做旧浅米白纹理纸张**——暖调浅米白、有细腻纸张纤维与轻微杂点、轻微做旧痕迹；**画面干净无多余杂物**，纸面留白是主体的呼吸。

**画框**：**外层嵌套双层细白色圆角画框**——两层极细白线、等比内缩、圆角半径克制；**不要装饰花纹、不要双色框、不要粗框**。

**画面气质**：当代艺术展览海报、美术馆展览图录感；高清细腻 8K 细节；干净、高级、安静。

**限制条件（负面清单，逐条照搬）**：

- 写实鲜花照片（photorealistic fresh flowers）；
- 毛绒质感（毛毡、绒面、绒毛）；
- 油画厚重笔触；
- 画面物体扭曲变形；
- 文字错乱错漏；
- 杂物冗余；
- 颜色杂乱跳脱；
- 画面模糊崩坏。

### 英文字标题位与文字内容规则

docx 里的 `YELLOW ROSE` / `ART EXHIBITION` 是**排版形式**（大号复古衬线标题 + 小号宽字距副标题，居中）。保留这种版式位，但：

- **标题位文字内容 = 源海报自身的标题或主体名**（逐字），不要凭空编造与源海报无关的作品名；
- **副标题位**：沿用"小号、宽字距、全大写"的形式，内容用源海报自带的副标题/展览信息/卖点文案**逐字**填写；
- 若源海报本身没有英文，标题位可保留为**排版留白/占位**，或使用**源海报主体名的英文译名**，且**不得替代或遮挡源海报的商业文案**；
- **不要**加入 `prompt by awen` 之类署名。

## Style preset (compact English keywords)

生成时把下面这个关键词块**追加到提示词末尾**（英文 art-direction 关键词模型遵循度更稳）：

```text
STYLE_PRESET: Crystal Glass Floral Art-Exhibition Poster
CORE: contemporary art exhibition poster, crystal glass flower, transparent glass petals, gilded gold petal rims,
warm golden caustics, museum catalogue layout, elegant centred typography
MATERIAL: clear crystal glass, glass thickness and refraction, fine gold rim on every petal edge,
aged pale off-white textured paper, double fine white rounded-corner frame
COLOR: bright yellow to golden-yellow glass gradient, warm golden light, pale off-white paper, pure white frame lines,
thin antique gold outlines, restrained deep amber only in glass thickness
LIGHT: warm golden light passing through glass, fine translucent caustics and light spots on paper,
soft studio diffused light, very soft shallow contact shadow
COMPOSITION: single central glass floral subject, centred museum layout, large clean negative space,
title slot above, subtitle slot beneath, preserve original composition and subject
TEXTURE: paper fibre, subtle grain, faint ageing, glass internal highlights, no dirt or smudges
MOOD: contemporary, premium, quiet, clean, gallery, art exhibition
AVOID: photorealistic fresh flowers, plush, felt, fuzz, oil impasto, thick brush strokes, watercolour,
paper-cut, knitted yarn, distorted shapes, garbled text, clutter, chaotic colour, blurry, broken
```

> 注意：`preserve original composition / preserve subject` 只覆盖**画面**。
> 商业文案、价格、券额、二维码、品牌名的保留仍按本 skill 的「Text and brand handling」执行。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。
  - docx 原规格为**竖版 3:4**。**取舍**：以**源海报原始宽高比为准**——源海报本身约为 3:4 时天然符合；若不是（如 1:1、4:5、9:16），**不得为了凑 3:4 而裁切、拉伸或重排版式**（硬规则第 5 条优先）。若用户明确要求改成 3:4，需先说明会改变源版式并取得确认。
  - 确实要按 3:4 输出时，用 `1536×2048` 或 `1200×1600` 一类尺寸（宽高取 16 的倍数、像素积达标）。
- **双白框与源海报的原有边框不冲突**：若源海报自带边框或贴边元素，**保留源海报边框内的信息**，把双层细白圆角框当作**内嵌的展览装裱层**加在画面内部或叠加在源版式之内，不要用白框盖掉源海报的贴边文案与 logo。
- **画面干净无多余杂物**：只有一个玻璃花卉主体，背景就是做旧浅米白纹理纸 + 细碎光斑 + 双层细白圆角框；**不要加瓶子、花瓶外的道具、飘落花瓣、几何装饰块**。
- **居中构图**：主体居中偏上，双层白框等距内缩，标题位在顶部、副标题位在标题下方；文字区保持**干净、低细节**的纸面。
- **保留源海报的信息顺序与层级关系**（品牌/标题 → 主体 → 卖点/优惠 → QR/行动区 → 服务/法务），但可按"展览海报"的居中克制的版式重新排布。
- **不得为了"干净美学"删减、弱化或省略源海报的必需信息**。留白是靠**布局**腾出来的，不是靠删信息换来的。
- 若源海报主体不是花卉：保留其身份与轮廓，只把材质换成水晶玻璃+金边，**不要把它变成一朵玫瑰**。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 玻璃花卉主体、花瓣金边、暖金光斑、做旧纸面、双层细白圆角框、装饰性排版空间
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案；不要为了"展览感"而虚构展览名、策展人、年份、票价、艺术家署名。
- 标题位可用**大号复古衬线、全大写、宽字距**的排版形式，副标题位用**小号宽字距**形式，但**必须清晰可读**，且**不得把文字或 logo 化为不可读色块**。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被玻璃折射、金边描线、光斑或画框压住、切碎、错位。玻璃与光斑指令越强，这些资产越容易被当成画面装饰吞掉，因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码保持完整清晰可扫描，不要被玻璃、光斑或画框覆盖、不要错位、不要变形」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Note the content to preserve strictly: subject identity, flower species and petal structure, pose, spatial relations, main composition, visual focus.
4. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
5. If exact text matters, generate only the glass visual layer (title/subtitle zones left as clean paper) and plan a text overlay.
6. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
7. Review the result against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, exhibition names, curator names, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks
- no borrowed flower species, gallery name, or artwork title that does not come from the current source

## Supporting files

- `palettes.md`: 水晶玻璃/暖金光斑配色与材质处理。
- `prompt-templates.md`: 可复制的中文提示词模板与出图前自检表。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio?（3:4 只在源海报本身约为 3:4 或用户明确要求时使用）
- Is the subject's identity, flower species and petal structure, spatial relations, main composition and visual focus **strictly preserved**?
- Are **all petals complete pieces of transparent crystal glass** — not frosted plastic, not flat acrylic, not water-ripple glass?
- Is the glass colour a **bright yellow → golden-yellow glass gradient**, deeper toward the petal base and more luminous at the edges?
- Does every petal edge carry a **fine, even, continuous gilded gold rim** (not a heavy gold frame, not a fully gilded flower)?
- Does **warm golden light pass through the glass** and cast **fine translucent caustics / light spots** on the paper around and below the subject?
- Is the light **soft studio diffused**, with no hard-edged dramatic shadows?
- Is the background an **aged pale off-white textured paper** with paper fibre, subtle grain and faint ageing — and is the **frame area free of clutter**?
- Is there a **nested double fine white rounded-corner frame**, evenly inset, with restrained corner radius?
- Is the typography layout **premium, simple and centred**, with a large vintage serif title slot and a small wide-tracked subtitle slot?
- Does the title/subtitle text come **verbatim from the source poster** — with no invented exhibition name, year, curator, artist credit or signature?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly, complete and readable?**
- Is the result free of photorealism, plush/felt fuzz, thick oil paint, watercolour, paper-cut, knitted yarn, distortion, text corruption, clutter, chaotic colour, and blur?
- Is the result free of content from other projects?
- Is the result free of random decoration piles, template layout, and filled-up backgrounds?

## Scope boundary

Do not silently merge this skill with `felt-floral-poster`（毛毡花卉）、`lace-embroidery-poster`（蕾丝刺绣）、`vintage-engraving-floral-poster`（复古刻版画花卉）、`brick-toy-floral-poster`（乐高积木花卉）、`plush-animation-poster`（毛绒/羊毛毡定格动画）、`knitted-yarn-poster`（针织毛线）、`impasto-miniature-landscape`（厚涂微缩景观）, or any other poster skill.

区分要点（**材质互斥，不可混用**）：

| 易混淆 skill | 本 skill 的区分 |
|---|---|
| `felt-floral-poster` | 那边是羊毛毡毡片：蓬松毛绒纤维、纯色大底、方框窗口与文本卡片；本 skill 是**通透玻璃**，有折射、金边、光斑，纸底，无绒毛 |
| `lace-embroidery-poster` | 那边是白色镂空蕾丝布 + 针孔花边 + 刺绣小画；本 skill 无任何布料、无针孔、无刺绣线 |
| `vintage-engraving-floral-poster` | 那边是墨绿灰调钢笔排线线稿与版画肌理；本 skill 是立体玻璃与写实光影，**没有排线线稿** |
| `plush-animation-poster` | 那边是毛绒定格动画微缩场景 + 浅景深；本 skill 是平面展览海报，无场景、无道具、无景深虚化 |
| `knitted-yarn-poster` | 那边是线圈针法编织纹理；本 skill 无任何纺织结构 |
| `impasto-miniature-landscape` | 那边是调色刀厚涂颜料体积；本 skill 是玻璃折射与光斑，**没有颜料堆积与笔触** |

If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

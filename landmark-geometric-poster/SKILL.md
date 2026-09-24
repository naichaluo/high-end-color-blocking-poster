---
name: landmark-geometric-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into an elegant landmark-geometric art poster — the source poster's own visual subject (product / storefront / building / scene) treated as the hero landmark at a strict 70% recognizable-subject / 30% geometric-abstraction balance, with the upper 40–50% of the canvas reserved for a serene sky and calm blank space and a single clean uppercase wide-tracked title line centred at the top, the landscape built below it, rendered in a limited, refined 6–10 colour museum-print / watercolor palette on delicate handmade surfaces (paper fibre, dry brush, watercolor, coloured pencil, screen-print) in the manner of Scandinavian editorial illustration × mid-century geometric art × architectural illustration × museum fine-art printing. Use when the user asks for几何地标艺术海报、几何地标海报、地标几何插画海报、建筑几何艺术海报、北欧编辑插画海报、中世纪几何艺术海报、博物馆版画风海报、留白天空地标海报、landmark geometric poster 或把普通海报改成几何地标艺术风；do not activate for Art Deco travel posters, layered paper-cut, paper collage, isometric 3D, neon, gold, retro filters, cartoon, or photorealistic poster tasks."
metadata:
  short-description: 几何地标艺术（主体 70% + 几何 30%）风海报重绘 Skill
---

# Landmark Geometric Poster / 几何地标艺术海报

把普通海报、产品描述或营销主视觉，重绘成**一张高雅风格的几何地标艺术海报**。

最终效果像**艺术博物馆里的精品印刷品**：源海报自身的**视觉主体**（产品 / 门店 / 建筑 / 场景）被当作"地标"来描绘——**主体占 70%，几何简化占 30%**；上方 40–50% 是宁静的天空与大面留白，顶部中央只放一行干净的标题；下方构建主体所在的景观。**斯堪的纳维亚编辑插画 × 中世纪几何艺术 × 建筑插画 × 博物馆精品印刷。**

**只改变视觉语言，不改变商业内容。**

This skill is independent from `art-deco-travel-poster`（装饰艺术旅行）、`layered-papercut-poster`（分层剪纸）、`paper-collage-poster`（纸艺拼贴）、`flat-spot-poster`（留白平涂小景）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成几何地标艺术风、几何地标海报风、地标几何插画风、建筑几何艺术海报风；
- 做**上方大面天空留白 + 下方景观**的宁静竖向艺术海报；
- 做主体轮廓高度可识别、其余用几何形态概括的博物馆版画感插画；
- create a landmark / architectural illustration poster with a restrained geometric abstraction;
- give a key visual a Scandinavian editorial × mid-century geometric museum-print feel.

Do not use it for Art Deco travel posters, layered paper-cut, paper collage, isometric 3D, neon, gold, retro/sepia filters, cartoon, watercolor-only, or photorealistic tasks.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret only the illustration language, geometric simplification, palette, and surface material.
2. **「地标」＝源海报的视觉主体；顶部「城市名」位＝源海报标题区**。本 skill 的 docx 原文是「［城市名称］」旅行地标模板。改造成海报重绘时：
   - **把「地标」对应为源海报自身的视觉主体**——产品、门店、建筑、场景。70/30 比例规则照搬：**主体 70% + 几何简化 30%**。
   - **把顶部中央的「城市名」位对应为源海报标题区**——**排版形式保留**（简洁字体、干净的大写、**宽字距**），但**文字内容完全取自源海报自身的文案**。
   - **不得**凭空编造城市名、地名、地标名或任何与源海报无关的文字。
3. **先画识别度，再做艺术简化**。「首先明确描绘出那些能够让主体立刻被识别出来的标志性形态，然后再进行几何上的简化处理。观众一看到这些建筑/主体，就能立刻想到：'这是它。'」**保持主要主体在约 70% 的程度上具有可识别的现实世界形态；只简化不必要的细节。**
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 主体的身份特征与视觉焦点必须一眼可辨；几何形态具有组织性，但**从不占据主导**。

## Style definition

### 核心概念：主体 70% ＋ 几何简化 30%

**最重要的原则是：主体占 70%，几何简化占 30%。**

- **里程碑优先级**：
  - **主要主体（主角）**：源海报的**一个或两个视觉主体**，它具有**独特的形状**——描绘的是形状本身，而不仅仅是一个名称。
  - **次要元素（围绕它们排列）**：**三个到五个支撑元素**——源海报场景中真实存在的屋顶、河流、桥梁、山丘、树木、街道布局等。
- **保持主要主体在约 70% 的程度上具有可识别的现实世界形态**；只简化不必要的细节。
- **平衡**：**70% 为可识别的主体与建筑/结构元素，30% 为几何抽象形态。几何形态具有组织性；但它从不占据主导。**

### 构图（比例是本风格的灵魂）

- **格式**：垂直式海报。保留源海报的**原始尺寸与宽高比**（若源海报为竖版，纵横比约为 2:3 或 3:4 时可沿用其原有比例）。高分辨率的宣传性艺术海报，拥有**充裕的空白区域**，垂直构图稳定。
- **上方 40–50% 的空间留给宁静的天空和空白区域**——这是必须守住的留白比例。
- **在顶部中央位置，只放置标题**：源海报的**标题文案**，使用**简洁的大写字体，字母间距要宽一些**（干净的大写 + 宽字距，无复杂字体）。
  - **文字内容必须逐字使用源海报自身的文案**——**不要编造城市名或其他文字**。
  - 若源海报的标题本身就是中文，就排版中文标题（同样保持简洁字体 + 宽字距的排版形式）；**不得**为了模仿模板而自造一个英文地名。
- **在下方部分构建景观**，让主要主体能够吸引观众的目光。

### 色彩调色板

- 这是一个**有限的、精致的色彩调色板，包含 6 到 10 种颜色**。
- **不会过于饱和**，具有类似**博物馆版画或水彩画**的风格。
- **先指定明亮的或清新的色调，然后列出六到八种柔和的颜色。**

### 材质

**细腻的手工制作表面**：

- **纸张纤维**
- **干刷笔触**
- **水彩**
- **彩色铅笔**
- **丝网印刷**

**明确不要**：老化的纸张、复古的棕色滤镜、棕褐色或发黄的背景效果。

### 风格

- **斯堪的纳维亚风格的编辑型插画**
- **中世纪几何艺术风格**
- **以地标为元素的建筑插画**
- **艺术博物馆中的精品印刷品**

### 限制条件（负面清单，必须遵守）

- 不得**过度夸张或渲染**；
- 不得出现过**于庞大的圆形元素**；
- 不得有**照片般的写实效果**；
- **不能是卡通风格**；
- **不能是 3D 效果**；
- 不得出现**霓虹色彩**；
- 不得出现**金色元素**；
- 不得出现**复古滤镜**；
- 不得出现**水印或标志**。

## Style preset (compact English keywords)

生成时把下面这个关键词块**追加到提示词末尾**（英文 art-direction 关键词模型遵循度更稳）：

```text
STYLE_PRESET: Landmark Geometric Art Poster
CORE: 70% recognizable hero subject / 30% geometric abstraction, subject first then geometric simplification,
geometric forms are organised but never dominant
COMPOSITION: vertical poster, upper 40-50% reserved for serene sky and calm blank space,
one clean uppercase wide-tracked title line centred at the top, landscape built in the lower half,
primary subject draws the eye, generous stable negative space
ANATOMY: one or two hero subjects with distinctive shape, plus three to five supporting elements
(roofs, river, bridges, hills, local trees, street layout), keep ~70% real-world recognizable form
PALETTE: limited refined 6-10 colours, bright or fresh tones first then six to eight muted colours,
not oversaturated, museum print / watercolour character
MATERIAL: paper fibre, dry brush, watercolour, coloured pencil, screen-print
STYLE: Scandinavian editorial illustration, mid-century geometric art, architectural illustration,
museum fine-art print
MOOD: elegant, quiet, serene, cultured, restrained, collectible
AVOID: photorealism, photograph, cartoon, 3D, neon, gold, vintage filter, sepia, aged paper,
yellowed background, watermark, logo, oversized circular elements, exaggeration, over-rendering
```

> 注意：`AVOID: watermark, logo` 约束的是**画面风格**——不要让模型自己画水印或标志。
> 若**源海报本身**带有品牌 logo、二维码、条码等资产，必须按本 skill 的「Text and brand handling」**逐字原样保留**，不得当作风格元素删掉。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。不得改成正方形，不得裁切版式。
- **上方 40–50% 是天空与留白区**：宁静、开阔、干净，是整张海报的呼吸区。**不得**用密实的几何花纹把它填满。
- **顶部中央**：只放**源海报的标题文案**，简洁大字 + 宽字距。这是唯一的"顶部排他占位"规则——**不要在标题旁新增城市名、地名、装饰小字或英文副标题**。
- **下方部分构建景观**：主要主体居中偏下，吸引目光；三到五个支撑元素围绕排列，形成稳定的垂直构图。
- **保留源海报的信息顺序与层级关系**（品牌/标题 → 主体场景 → 卖点/优惠 → QR/行动区 → 服务/法务），但可按本风格的**安静编辑式版式**重新排布。
- **几何形态具有组织性，但从不占据主导**：它负责整理画面结构（地平线、色带、轮廓分割），**不负责抢戏**。
- **不得为了"留白美学"删减、弱化或省略源海报的必需信息**。留白是靠**布局**腾出来的，不是靠删信息换来的。
- 避免填满画面、避免过大圆形装饰、避免过度夸张的造型、避免机械居中和模板化版式。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 主体与支撑元素的插画、几何形态、天空与留白、手工材质表面
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案——**尤其不得编造城市名、地名、地标名、英文副标题**（docx 模板里的「［城市名称］」在本 skill 中**不填任何虚构内容**，改为源海报自身的标题文案）。
- **顶部标题区**采用本 style 的**排版形式**（简洁大字、干净字体、**宽字距**），**文字内容完全取自源海报**。若源海报标题为中文，就排中文，不强行改英文。
- 正文与卖点文案同样**逐字保留**，可做成克制的编辑式排版，但**必须清晰可读**，且**不得把文字或 logo 化为不可读色块**——也不得把文字当作几何形状去简化。
- 文字承载区保持**干净、低细节、低饱和的留白或浅色区**，保证对比度。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被几何形态覆盖、被简化处理、被裁切或重新配色。
  **⚠️ 特别注意**：本风格的负面清单包含"不得出现水印或标志"，这是**针对画面风格**的约束；**源海报自身的 logo 与二维码属于必须保留的商业资产**，两者不冲突——提示词里必须同时写明「不要自行绘制任何水印、标志或标志性图形」**和**「源海报原有的 logo/二维码必须从原素材原样贴回，保持完整清晰可扫描」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. **Define the hero subject**（源海报的视觉主体）and pick **three to five supporting elements** that genuinely exist in the source scene.
4. **Draft the 70/30 split**: list what stays recognizably real-world (~70%) and what is simplified into organised geometry (~30%).
5. Choose a palette from `palettes.md` (limited 6–10 colours) and a prompt pattern from `prompt-templates.md`.
6. **Lay out the vertical structure**: upper 40–50% serene sky + blank space → title line centred at top (uppercase, wide tracking, source copy only) → landscape built in the lower half around the hero subject.
7. If exact text matters, generate only the illustration visual layer and plan a text overlay.
8. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
9. Review the result against the source and remove any content that came from another project — **especially any invented city name or place name**.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks
- **no invented city name, place name, landmark name, or destination name of any kind**
- **no carried-over destination or travel content from other skills' examples**
- no model-added decorative English subtitle or watermark

## Supporting files

- `palettes.md`: 6–10 色有限精致调色板、70/30 比例与手工材质规格。
- `prompt-templates.md`: 主模板 + 纯视觉底图模板 + 出图前自检表。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio?
- Is the source poster's own visual subject treated as the **hero landmark** (product / storefront / building / scene), rather than an invented destination?
- Is the **70% recognizable subject / 30% geometric abstraction** balance respected — with geometry **organised but never dominant**?
- Does the hero subject keep ~70% of its real-world recognizable form, with only unnecessary detail simplified?
- Are there **one or two** hero subjects with distinctive shape, plus **three to five** genuine supporting elements from the source scene?
- Is the **upper 40–50% reserved for serene sky and calm blank space**, and not filled with dense geometric pattern?
- Is there exactly **one title line centred at the top**, in clean uppercase with **wide letter spacing**, and **no complex fonts**?
- Is that title taken **verbatim from the source poster's own copy** — with **no invented city name, place name, or English subtitle**?
- Is the palette a **limited, refined 6–10 colours**, **not oversaturated**, with a museum-print / watercolor character?
- Are the **materials** present: paper fibre, dry brush, watercolor, coloured pencil, screen-print — as a **delicate handmade surface**?
- Is the style read as **Scandinavian editorial illustration × mid-century geometric art × architectural illustration × museum fine-art print**?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly and readable?**
- Is the result free of **photorealistic** rendering, **cartoon**, **3D**, **neon**, **gold**, **vintage/sepia filter**, and **aged or yellowed paper**?
- Is the result free of **oversized circular elements** and of **exaggeration or over-rendering**?
- Does the model refrain from **inventing watermarks or logos**, while source logos/QR codes are preserved intact from the original assets?
- Is the result free of information clutter and template layout?
- Does it read as a **museum fine-art print** — elegant, quiet, serene, cultured, restrained?

## Scope boundary

Do not silently merge this skill with `art-deco-travel-poster`（装饰艺术旅行）、`layered-papercut-poster`（分层剪纸）、`paper-collage-poster`（纸艺拼贴）、`flat-spot-poster`（留白平涂小景）or any other poster skill.

**⚠️ 旅行地标三兄弟互不合并**。三者的「地标」都对应源海报视觉主体，都沿用 70/30 比例，但艺术语言完全不同：

| 维度 | 本 skill（几何地标艺术） | `art-deco-travel-poster` | `layered-papercut-poster` |
|---|---|---|---|
| 造型逻辑 | **主体高度写实可辨（70%）+ 组织性几何（30%）**，几何从不主导 | 流线型宏伟造型、完美弧线、阶梯式退台、同心光束 | 六到八层单色剪纸堆叠 |
| 视角 | 稳定正面的建筑插画视角 | 低角度仰视、高耸向上汇聚 | 平视堆叠，无透视 |
| 深度 | 靠几何结构、色彩层次与留白 | 靠硬朗戏剧性光影与对角线 | **只靠层间柔和投影与堆叠顺序** |
| 材质 | 纸张纤维 / 干刷 / 水彩 / 彩铅 / 丝网印（细腻手工） | 平整印刷油墨，干净现代，无做旧 | 哑光艺术纸、切割边缘、纸张厚度 |
| 光影 | 柔和、宁静、博物馆感 | 硬朗戏剧性，明亮平面 vs 单一色调阴影 | 单侧柔和光 + 层间漫射影 |
| 顶部 | **上方 40–50% 宁静天空与留白** | 上三分之一天空 + 奶油色圆盘 | 上方 40% 平坦天空层 |

其他区分：

- vs `flat-spot-poster`: 那个是**小图画在暖白大纸中央**的留白平涂小景，主体很小；本风格**主体占 70% 且是画面主角**，留白集中在**上方**而不是四周。
- vs `paper-collage-poster`: 那个靠**纸片拼贴与撕边**；本风格靠**干刷/水彩/彩铅/丝网印的手绘插画表面**，没有撕纸边。
- vs `high-end-color-blocking-poster`: 那个是**巨大平面色块 + 编辑感排版**的现代撞色；本风格是**有限精致的博物馆版画感插画**，色彩**不过饱和**。

If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

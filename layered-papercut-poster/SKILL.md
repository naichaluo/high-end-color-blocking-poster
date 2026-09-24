---
name: layered-papercut-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a tactile layered paper-cut poster — the source poster's own visual subject treated as the hero landmark at a 70% subject / 30% paper-structure balance, built from six to eight stacked single-colour art-paper layers with real physical spacing between them, each layer casting a soft diffuse shadow onto the layer behind it so that shadow and stacking order are the only source of depth, absolutely no perspective, no atmospheric haze and no rendering, every edge a clean cut edge showing only the paper thickness catching light, all detail expressed as cut holes (window openings, arches, structural ribs, railing slits) that reveal the layer behind rather than being drawn, soft even light from the upper left, the top 40% left as a flat sky layer, the top-centre title cut as separate wide-tracked uppercase sans letters sitting slightly in front of the sky layer and casting the same soft shadow, a cool art-paper palette of mineral blue, grey blue-green, pale sky blue, warm sandstone, soft coral and deep navy over a soft cream sky — while preserving the source poster's exact business content, hierarchy, brand assets, and typography. Use when the user asks for分层剪纸海报、层叠剪纸海报、多层剪纸海报、纸雕海报、剪纸堆叠海报、单色纸层叠海报、切割孔洞海报、layered papercut poster、paper cut layers 或把普通海报改成分层剪纸风；do not activate for paper-collage scraps, torn-paper relief, papercraft miniature dioramas, art-deco travel posters, or photorealistic poster tasks."
metadata:
  short-description: 6–8 层单色纸堆叠 + 切割孔洞的分层剪纸海报重绘 Skill
---

# Layered Papercut Poster / 分层剪纸海报

把普通海报、产品描述或营销主视觉，重绘成 **触感丰富的分层剪纸（layered paper-cut）海报**。

最终效果像**一张由多层剪纸堆叠而成、单侧柔和打光的照片**：立体感强，却**柔和精致**——所有深度都来自**层与层之间的堆叠顺序和层间投下的柔和阴影**，而不是透视、雾霾或渲染。

**只改变视觉语言，不改变商业内容。**

This skill is independent from `paper-collage-poster`（纸艺拼贴）、`papercraft-travel-diorama`（纸艺旅行微缩立体场景）、`torn-paper-relief-poster`（撕纸浮雕）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成分层剪纸风、层叠剪纸风、多层剪纸风、纸雕风、剪纸堆叠风、单色纸层叠风；
- 要「6–8 层单色纸前后堆叠 + 层间真实间隔 + 柔和层间阴影 + 切割孔洞透出后层」这套语言；
- create a layered papercut poster, a stacked paper-layer relief poster, a cut-paper diorama-style poster;
- give a product / store / building key visual a clean, tactile, precision-cut art-paper feel.

Do not use it for paper-collage scraps (`paper-collage-poster`), torn-paper relief (`torn-paper-relief-poster`), papercraft miniature dioramas (`papercraft-travel-diorama`), Art Deco travel posters (`art-deco-travel-poster`), or photorealistic / 3D-render tasks with no paper-cut transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret paper layers, cuts, stacking order and light only.
2. **选一个主体当“地标”，并守住 70/30。** 从源海报里挑出**唯一一个**视觉主体（产品 / 门店 / 建筑 / 场景），它就是这张海报的“地标”，占 **70%** 的可辨识度与画面主导权；剪纸层叠结构占 **30%**。**主体保留现实世界中的轮廓与基本比例，并主导周围的一切**。
3. **深度只由两层机制产生：层间阴影 + 堆叠顺序。** 每层在其**后层**投射柔和、漫射的阴影；**这些阴影是构成画面深度的唯一要素**。同时：**层内不得出现阴影，层内不得出现渐变**——一层纸就是一个未经调和的单色。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 缩略图下仍要能读出：主体的独特轮廓、层数与堆叠层次、切割孔洞透光、顶部中央标题区。

## Style definition

层叠剪纸立体模型（layered paper-cut / stacked paper layers）风格的目的地旅行艺术海报。**竖版、触感丰富、立体感强、柔和精致**——像一张由多层剪纸堆叠而成、单侧柔和打光的照片。

**画面绝对优先级（核心概念）**：主体（源海报的视觉主体，承担“地标”角色）占 **70%**，剪纸层叠结构占 **30%**。**首先**呈现标志性主体的形象，**其次**才是剪纸结构。观者的第一反应必须是「这就是这张海报的主角」。

**地标优先（层的内容分配）**

- **主要主体**：**一到两个**，且**每个主体占用单独的纸张层**。刻画其**独特形状**，而不仅仅是命名。
- **次要元素**：**三到五个**辅助元素，**按堆叠顺序排列，从后向前**依次是：① 远处的轮廓 → ② 近处的物体/建筑 → ③ 树木或前景植物 → ④ 地面或水体。**堆叠的最前面放一个前景切割边缘**（一道压在最前面的剪切边，用来收住整个堆叠）。
- **主体必须保留现实世界中的轮廓和基本比例，并主导周围的一切**。**简化表面细节，但绝不简化结构**。
- 必须明确指出**哪些部分在简化中必须保留**（例如：「弧形顶棚必须保留其肋状轮廓与天窗」）——这是防止模型把结构简化为色块的关键约束。

**剪纸技法（本风格的灵魂）**

- 画面由 **六到八层**不同深度的剪纸构成；
- **每一层都采用单一的纯色**（未经调和的一层一色），**前后堆叠**；
- 相邻层之间**彼此之间有真实的物理间隔**（不是贴死的一叠纸，而是像立体模型那样层层退开）；
- 每一层都会在其**后层**投射出**柔和、漫射、短暂**的阴影——**轻柔，绝不生硬**；
- **这些层间阴影是构成画面深度的唯一要素**；
- **画面中没有透视、没有大气雾霾、也没有渲染**；
- **每一处边缘都是切割的边缘**：干净利落、清晰可见，**只有纸张厚度的痕迹在每层的顶部边缘反射着光线**；
- **细节的呈现是通过切割实现的**——窗户开口、拱形、结构肋条以及栏杆上的缝隙，都是**切割出的孔洞，露出其后的纸层**，**而不是绘画痕迹**；
- **光线柔和地从左上角照射过来，均匀地分布在所有纸层上**。

**关键区分（避免自相矛盾）**

- 「层内不得使用阴影 / 渐变」= **一层纸自身表面是一个纯色平面**，不允许在这层纸内部画出明暗或渐变。
- 「层间必须有阴影」= 阴影只作为**上层投向后层的投影（cast shadow）**存在，表现为后层表面上的柔和暗带。
- 「无透视」= **不做透视汇聚、不做消失点、不做近大远小的纵深推演、不做空气雾霾**；深度完全由**堆叠顺序 + 层间阴影**给出。

**构图**

- 画面上方 **40% 为平坦的天空背景层**（一层纯色纸）。
- **仅在画面上方中心位置**放置源海报标题（排版形式见下节），以**单独切割的字形**呈现：**大写无衬线、字间距较宽、略微位于天空背景层前方，并投射出与其他景物相同的柔和阴影**。
- **在画面中下方构建主体场景**。

**色彩方案**

- **冷色调彩色艺术纸**：最外层为 **矿物蓝、灰蓝绿、浅天蓝、暖砂岩色、柔和珊瑚色和深海军蓝**；**后层为柔和奶油色**（用于天空背景）。
- 大约使用 **七张平面纸**。
- **每一层都使用单一的、未经调和的颜色**——**深度通过阴影和堆叠顺序来表现，绝不通过层内明暗变化来体现**。
- 主体本身的实际颜色保留源海报的主要色彩信息，只做**冷调化 + 艺术纸化**处理，不改变色相归属。
- 系列一致性：若同一批海报要成系列，**所有作品使用相同的色彩方案**，这是整个系列浑然一体的关键。

**质感**

**哑光艺术纸表面**；每一层都可见**细腻均匀的纤维纹理**；**边缘切割清晰利落**；**纸张厚度极薄**；**层间缝隙处呈现柔和的自然光晕**。**干净现代**。**无老化纸张、棕色滤镜、棕褐色调或泛黄**。

## Style preset (compact English keywords)

生成时把下面这个关键词块**追加到提示词末尾**（英文 art-direction 关键词模型遵循度更稳）：

```text
STYLE_PRESET: Layered Paper-cut Poster
CORE: layered papercut, stacked paper layers, six to eight single-colour art-paper layers,
real physical spacing between layers, cut holes revealing the layer behind,
window openings, arches, structural ribs, railing slits cut out rather than drawn,
subject 70 percent / paper structure 30 percent
LIGHT: soft even light from the upper left, each layer casting a soft diffuse short shadow
onto the layer behind, shadow and stacking order are the only depth cues
CUT: every edge a clean precise cut edge, only paper thickness catching light on the top edge
NO: no perspective, no atmospheric haze, no rendering, no hard shadows, no gradient inside a layer,
no shading inside a layer, no painted detail
MATERIAL: matte art paper, fine even fibre grain, extremely thin paper, soft natural glow in the gaps
COLOR: cool art paper — mineral blue, grey blue-green, pale sky blue, warm sandstone,
soft coral, deep navy on the outer layers, soft cream sky on the back layer,
about seven flat sheets, one single unmixed colour per layer
COMPOSITION: top 40 percent a flat sky layer, subject built in the lower middle,
top-centre title cut as separate wide-tracked uppercase sans letters slightly in front of the sky layer
MOOD: tactile, sculptural, precise, calm, refined, clean modern
AVOID: hard shadows, gradient inside a layer, shading inside a layer, perspective depth cues,
photorealism, 3D render of any material other than paper, glow, neon, gold, glitter,
aged paper, sepia, torn edges, crumpled or creased paper, travel-sticker style, cartoon,
cute characters, fancy fonts, watermark, logo
```

> 注意：`subject 70 percent / paper structure 30 percent` 只覆盖**画面**。
> 商业文案、价格、券额、二维码、品牌名的保留仍按本 skill 的「Text and brand handling」执行。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。
  docx 原规格为竖版 **2:3**。**取舍**：以**源海报原始宽高比为准**——源海报本身是竖版 2:3 时天然符合；若不是，**不得为了凑 2:3 而裁切、拉伸或重排源版式**（硬规则第 5 条优先）。若用户明确要求改成 2:3，需先说明会改变源版式并取得确认。
- **上方 40% 是一层平坦的天空背景层**（纯色柔和奶油色纸），保持低细节、不堆叠主体。
- **层数控制在 6–8 层**（配色方案建议约 7 张平面纸）；层数过少会失去堆叠感，过多会失去「单色干净」的气质。
- **主体在画面中下方构建**；次要元素严格按**从后向前**的堆叠顺序落层：远处轮廓 → 近处物体 → 树木/前景植物 → 地面/水体，**最前面放一道前景切割边缘**。
- **顶部中央标题区**：标题以**单独切割的字形**呈现，**略微位于天空层前方**并投出与其他景物相同的柔和阴影（见下节「名称位改写规则」）。
- **保留源海报的信息顺序与层级关系**（品牌/标题 → 主体场景 → 卖点/优惠 → QR/行动区 → 服务/法务），但**允许按剪纸分层的思路重新排布**（例如把卖点条做成一条独立的切割纸带、把行动区收进一个切割矩形窗）。
- **不得为了“剪纸留白美学”删减、弱化或省略源海报的必需信息**。留白靠**布局**腾出来，不靠删信息换来。
- **文字承载区必须是低细节的纯色纸面**（一层未切割的纯色纸），保证叠加的精确文字有足够对比；**不要让文字区落在孔洞、缝隙或层间阴影上**。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 6–8 单色纸层、堆叠顺序、层间柔和阴影、切割孔洞（窗洞/拱形/肋条/栏杆缝隙）、天空层、前景切割边缘、单独切割的标题字形
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案。
- 文字排版形式遵循剪纸语言：**单独切割的字形、大写无衬线、字距拉开、略微位于天空层前方并投出相同的柔和阴影**；中文则对应为**单独切割的方正无衬线字形、字距拉开**，**必须清晰可读**。
- **不得把文字或 logo 化为不可读色块**。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。

**「名称位」改写规则（重要 · 规范改造）**

docx 原规格写的是「仅在画面上方中心位置放置［城市名称］，除该词外不得有其他文字」。改造成海报重绘 skill 时按项目规范调整：

- 顶部中央的**“城市名”位置 → 对应为源海报的标题区**；
- **排版形式保留**（画面上方中心、单独切割、大写无衬线、宽字距、略微位于天空层前方并投出相同柔和阴影）；
- **文字内容一律使用源海报自身的标题/文案**，**绝不编造城市名、地名、品牌名或任何新文案**；
- docx 的「除该词外不得有其他文字」在执行时重新解释为：**标题区只放源海报标题本身；不得新增装饰性英文标题、地名、署名或任何源海报以外的文字**。源海报自带的卖点、价格、服务与法务文案**照常逐字保留**，按剪纸分层重新排布，不被「只有标题」这条限制删掉。

**功能性资产保护（硬规则）**

- 二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被切掉、被当成孔洞处理、被纸层覆盖、被层间阴影压暗或错位。
- 本风格天然喜欢「把细节做成切割孔洞」，二维码最容易被误当成一个可以镂空的图案。因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码保持完整清晰可扫描，**不要切割、不要镂空、不要用纸层覆盖、不要错位、不要歪斜**，保持水平」。
- docx 原限制条件写有「不得使用水印、徽标」。**取舍**：该条只约束**新增**的水印与虚构标志；**源海报自身的 logo / 品牌标识 / 二维码属于必须保留的功能性资产，不受此条约束**。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. **选定唯一主体**并写下必须在简化中保留的结构特征（轮廓、比例、肋条、拱形、窗洞位置）；再把次要元素排成从后向前的堆叠顺序，并指定最前面的那道前景切割边缘。
4. Decide the layer count (6–8) and assign **one single unmixed colour per layer**, with the soft cream sky as the back layer; pick the palette from `palettes.md`.
5. If exact text matters, generate only the paper-cut visual layer (纸张层 + 孔洞 + 天空层 + 干净的标题区与文字区，不带可读文字) and plan a text overlay.
6. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
7. Review the result against the source for content fidelity and thumbnail legibility, verify that depth comes only from inter-layer shadow and stacking order, and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no invented city names, destination names or decorative English titles
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks

## Supporting files

- `palettes.md`: 冷调艺术纸色盘、每层单色规则、层间阴影与光线规则、艺术纸材质。
- `prompt-templates.md`: 主模板 + 纯视觉底图模板 + 出图前自检表。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio?
- Is the source poster's **one** visual subject clearly the hero landmark at roughly **70%**, with the paper structure at roughly **30%**?
- Is the subject built from **six to eight** stacked paper layers of **different depth**?
- Does **each layer use one single unmixed colour**, with **no gradient and no shading inside the layer**?
- Is there **real physical spacing** between adjacent layers (not one flush stack)?
- Does each layer cast a **soft, diffuse, short shadow onto the layer behind it**, and is that shadow + stacking order the **only** source of depth?
- Are all shadows **soft** — is there **no hard shadow** anywhere?
- Is the image free of **perspective depth cues, atmospheric haze and rendering**?
- Is **every edge a clean, precise cut edge**, with only paper-thickness light on the top edges?
- Is detail expressed as **cut holes** — window openings, arches, structural ribs, railing slits that reveal the layer behind — rather than painted detail?
- Is the light **soft from the upper left**, evenly across all layers?
- Is the **top 40%** a **flat sky layer** (soft cream) with the subject built in the lower middle?
- Is the title **cut as separate wide-tracked uppercase sans letters**, sitting **slightly in front of the sky layer** and casting the **same soft shadow** as everything else?
- Is the palette **cool art paper** — mineral blue, grey blue-green, pale sky blue, warm sandstone, soft coral, deep navy on the outer layers, soft cream sky behind — at roughly **seven flat sheets**?
- Is the surface **matte art paper** with fine even fibre grain, extremely thin paper, clean cut edges and a soft natural glow in the layer gaps?
- Is the poster **clean and modern** — no aged paper, brown filter, sepia or yellowing?
- Is the subject's **real-world silhouette and basic proportions preserved**, and does it **dominate** its surroundings, with surface detail simplified but **structure never simplified**?
- Are the secondary elements stacked **back to front** (distant silhouette → nearer structure → trees/foreground → ground/water) with a **foreground cut edge at the very front**?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly and readable?**
- Is the title-area text taken **verbatim from the source poster**, with **no invented city name or decorative English title**?
- Is the QR code **complete, un-cut, un-hollowed, un-covered, not tilted** and fully scannable?
- Does it read as a photograph of a layered paper-cut relief — not a flat vector illustration, not a paper-scrap collage?
- Is the result free of **hard shadows, in-layer gradients, in-layer shading, perspective, photorealism, non-paper 3D rendering, glow, neon, gold, glitter, aged paper, sepia, torn edges, creases, travel-sticker style, cartoon, cute characters, fancy fonts, watermark**?

## Scope boundary

Do not silently merge this skill with `paper-collage-poster`, `papercraft-travel-diorama`, `torn-paper-relief-poster`, `art-deco-travel-poster`, or any other poster skill. If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

具体区分（这是最容易被混淆的一组）：

- **vs `paper-collage-poster`（纸艺拼贴）**：那个是**碎纸片拼贴**——大量不规则纸片、杂志纸、手工染色纸**拼成**主体，边缘**撕裂、翘起、错位**，是「拼」的逻辑。本 skill 是**6–8 整层单色纸前后堆叠**，每层**完整、单一未调和颜色、边缘干净利落**，深度靠**层间阴影 + 堆叠顺序**，**不是拼贴碎纸、不许撕裂边**。
- **vs `papercraft-travel-diorama`（纸艺旅行微缩立体场景）**：那个是**手工纸模型微缩立体场景**（有地面舞台、立体小建筑、模型感、浅景深摄影感）。本 skill 是**层叠浮雕式平面纸层**——**没有透视、没有大气雾霾、没有渲染**，深度**只**来自层间柔和阴影与堆叠顺序，是「一层纸一层景」的分层切割。
- **vs `torn-paper-relief-poster`（撕纸浮雕）**：那个靠**撕裂边缘与纸张浮雕**制造质感；本 skill **禁止撕裂效果与褶皱**，边缘必须是**切割边**。
- **vs `art-deco-travel-poster`（装饰艺术旅行）**：那个是**平面印刷油墨 + 对角线骨架 + 硬光平面 + 藏青唯一阴影**；本 skill 是**真实纸张 + 层间柔和阴影 + 左上柔光**，两者互不合并。

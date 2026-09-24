---
name: felt-floral-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a vintage floral-magazine poster: a flat, comfortable editorial layout on a deep misty-purple solid ground, an oversized off-white vintage serif title slot at the top with a small wide-tracked copy line beneath it, a rounded-rectangle window in the middle holding a wool-felt flower built entirely from soft felted fabric — clear felt grain, fluffy fuzzy fibre, gracefully curved felt stems — under hazy soft diffused light, and an off-white text card along the bottom with the subject name set large on its left. Use when the user asks for毛毡花卉海报、羊毛毡花卉杂志海报、毛毡花海报、毡绒花卉海报、软乎乎毛毡质感海报、深紫底毛毡海报、复古植物图鉴毛毡海报或把普通海报改成毛毡花卉风；do not activate for plush stop-motion scenes, knitted/crocheted yarn, fabric patchwork, crystal glass, lace embroidery, or photorealistic flower-photography poster tasks."
metadata:
  short-description: 毛毡花卉复古杂志风海报重绘 Skill
---

# 毛毡花卉杂志海报 / Felt Floral Magazine Poster

把普通海报、产品描述或营销主视觉，重绘成一张**竖版复古花卉杂志海报**：**深雾紫高级纯色背景**，顶部是**大号米白色复古衬线标题位**与其下的小字文案位，画面中间一个**圆角方框窗口**，窗口内是**软乎乎羊毛毡材质的花卉主体**（清晰毛毡肌理、蓬松柔软毛绒纹理、优雅弯曲的毡质花杆），整体**光影柔和朦胧**，底部是**米白文本卡片**，**舒适平面海报排版**，**复古植物图鉴**气质。

**只改变视觉语言，不改变商业内容。**

This skill is independent from `plush-animation-poster`（毛绒定格动画）、`knitted-yarn-poster`（针织毛线）、`fabric-patchwork-poster`（布艺拼接）、`crystal-glass-floral-poster`（水晶玻璃花卉）、`lace-embroidery-poster`（蕾丝刺绣）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成毛毡花卉风、毛毡海报、羊毛毡花卉杂志海报、毛毡花海报、毡绒花卉海报、软乎乎毛毡质感海报、深紫底毛毡海报；
- 做成复古花卉杂志海报、复古植物图鉴风海报、舒适平面排版海报；
- create a wool-felt floral magazine poster with a solid misty-purple ground and a rounded window;
- render a flower key visual entirely from soft felted fabric with clear felt grain and fuzzy fibre;
- give a campaign visual the quiet, hazy, handcrafted but flat-editorial feel of a vintage botanical magazine cover.

Do not use it for 毛绒定格动画微缩场景、针织/钩针线圈、布艺拼接贴布、水晶玻璃、蕾丝刺绣、写实鲜花摄影 or any task that does not want the felt material.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret material, felt grain, window, card and decorative elements — never business content.
2. **Choose one central felt subject** (the most recognizable element of the source) and keep it inside the rounded window as the single visual anchor. 主体身份不换：源海报的产品/花卉/物体仍是同一主体，只是**材质被换成羊毛毡**。不要新增第二束花、不要把窗口塞满。
3. **Build a readable depth stack**: 深雾紫纯色底 → 圆角方框窗口（轻微内阴影）→ 羊毛毡主体（多层毡片叠出体积）→ 米白文本卡片 → 干净的文字预留区。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 毡质主体的一眼可辨轮廓、顶部标题、底部卡片花名必须在小尺寸下依然清楚；毛毡肌理要看得出来但不能糊。

## Style definition

复古花卉杂志海报（vintage floral magazine poster）× 羊毛毡面料（wool felt fabric）× 舒适平面排版（comfortable flat editorial layout）× 复古植物图鉴（vintage botanical plate）。

**画布与气质**：**竖版复古花卉杂志海报**版式，**舒适平面海报排版**——元素规整排布、留白从容、不追求 3D 场景感，像一本老植物学杂志的封面。

**背景（核心）**：**深雾紫高级纯色背景**——大面积纯色平铺、不透明、无渐变、无杂点、无纹理噪点；色相为冷静高级的**深雾紫**（deep misty purple）。整张海报的底色就是这一块纯色，**不要加装饰边框、不要加底纹、不要加散落元素**。

**顶部标题位**：**大号米白色复古衬线标题位**（off-white vintage serif、大小克制但醒目、居中或偏左的规整排版）。**排版形式保留**；**文字内容用源海报自身的标题或主体名**（逐字）。

**标题下方小字文案位**：极小号、宽字距、规整的一行（或两行）小字。**排版形式保留**；内容用**源海报自带的副标题/说明/卖点文案**逐字填写。

**画面中间圆角方框窗口（核心）**：

- 一个**圆角方框窗口**（rounded-rectangle window）居中，圆角半径中等、边框克制；
- 窗口内是**毛绒毡绒材质的毡质花卉主体**：docx 指定的形态参考为**白色蝴蝶兰**——参考图花朵形态、**数朵盛放的花**、**优雅弯曲的绿色花杆**、**花蕊带有淡黄调**；若源海报主体是别的花卉/物体，**保留其身份与轮廓**，只把材质换成羊毛毡；
- 窗口内背景干净（可为比深雾紫略浅的同色系，或米白），让毡质主体清楚浮出。

**毛毡材质（核心，不可简化）**：

- 花朵、花杆、叶片**全部是软乎乎羊毛毡面料质感**（soft wool-felt fabric）——**不是**针织/钩针线圈，**不是**绒毛玩具长毛，**不是**布料印花；
- **清晰毛毡肌理**：可见毡化纤维的细密交错、毡片表面的绒感与细微起伏；
- **蓬松柔软毛绒纹理**：边缘微微起绒、有细短纤维翘出，触感柔软；
- **裁剪感**：花瓣/叶片像从**厚毡片裁切**出来再叠上去，边缘有毡片厚度，层次之间是**毡片叠毡片**的关系；
- **不必缝线**：本风格以"毡片裁剪+叠贴"为主，**不要出现明显的刺绣针脚、编绳、纽扣、蕾丝、流苏**（那些属于别的风格）。

**光影**：**整体光影柔和朦胧**、**柔和漫射光影**——没有硬阴影、没有强方向光；毡片之间是柔和的层次阴影，窗口有一点点内阴影让窗口"凹"进去；整体带轻微朦胧感（hazy），但**细节精致饱满、高清**，不要糊成一团。

**底部文本卡片**：底部补充一张**米白文本卡片**（off-white card，素净、圆角克制或直角均可但**无多余装饰边框**），**卡片左侧大字体标注主体名/花名**（内容 = **源海报自身的标题或主体名，逐字**）；卡片其余位置放源海报的必要信息。

**排版纪律**：**文字排版干净规整**；**无多余装饰边框**；不要散落的装饰小元素、不要胶带贴纸、不要手绘涂鸦。

**限制条件（硬，逐条不可漏）**：

- **方框右下角完全不要关闭叉号**：**绝对不要**在圆角方框（或任何窗口）的角上出现 `×`、`X`、关闭按钮、窗口控件、UI 图标、铅笔/箭头之类的界面元素。这是一个"窗口形状的版面元素"，不是真的软件窗口。
- 不要多余装饰边框（无花边框、无虚线框、无双线相框）。
- 不要写实鲜花照片、不要针织毛线纹理、不要布艺拼布、不要玻璃反光。
- 不要扭曲变形、不要文字错乱错漏、不要画面模糊崩坏。

### 标题位/小字/花名的文字内容规则

docx 里的 `WHITE PHALAENOPSIS`、`elegant pure white orchid of quiet summer` 是**排版形式**（大号米白衬线标题 + 小字宽字距文案 + 底部卡片左侧大字花名）。保留这三个版式位，但：

- **标题位文字内容 = 源海报自身的标题或主体名（逐字）**，不要凭空编造与源海报无关的作品名或花名；
- **小字文案位**：沿用"极小号、宽字距、规整"的形式，内容用源海报自带的副标题/说明文案**逐字**填写；若源海报没有对应文案，保留为**干净留白占位**；
- **底部卡片左侧大字**：用**源海报自身的主体名/产品名**（逐字），不要编造新的花名；
- 若源海报本身没有英文，标题位可保留为**排版留白/占位**，或使用**源海报主体名的英文译名**，且**不得替代或遮挡源海报的商业文案**；
- **不要**加入 `prompt by awen` 之类署名。

## Style preset (compact English keywords)

生成时把下面这个关键词块**追加到提示词末尾**（英文 art-direction 关键词模型更快稳定命中）：

```text
STYLE_PRESET: Wool Felt Floral Magazine Poster
CORE: vintage floral magazine poster, wool felt flower, felted fabric craft, flat comfortable editorial layout,
vintage botanical plate, clean regular typography
MATERIAL: soft wool felt fabric, thick felt sheets cut into petals, layered felt pieces, clear felt grain,
fluffy fuzzy fibre surface, slightly raised fuzzy edges, felt-on-felt layering
COLOR: deep misty purple solid background, off-white felt petals, pale yellow felt flower centres,
soft sage green felt stems and leaves, off-white text card, restrained low-saturation palette
LIGHT: hazy soft diffused light, very soft layered shadows, subtle inner shadow in the window, no hard shadows
COMPOSITION: vertical poster, large off-white serif title slot at top, small wide-tracked copy line beneath,
one rounded-rectangle window centred with the felt flower inside, off-white text card at the bottom,
subject name large on the left of the card, generous calm margins, preserve original composition and subject
TEXTURE: felted fibre grain, fuzzy wool surface, soft cut felt edges, gentle haze, fine detail throughout
MOOD: vintage botanical, quiet, cosy, editorial, handicraft, premium
AVOID: UI close button, "x" icon, window controls, decorative frames, patterned border, knitted stitches, crochet loops,
yarn braid, fabric patchwork print, plush long fur, photorealistic flowers, glass reflection, distorted shapes,
garbled text, clutter, blurry, broken
```

> 注意：`preserve original composition / preserve subject` 只覆盖**画面**。
> 商业文案、价格、券额、二维码、品牌名的保留仍按本 skill 的「Text and brand handling」执行。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。
  - docx 原规格为**竖版**。**取舍**：以**源海报原始宽高比为准**——源海报本身是竖版时天然符合；若是横版或其他比例，**不得为了凑竖版而裁切、拉伸或重排版式**（硬规则第 5 条优先）。若用户明确要求改成竖版，需先说明会改变源版式并取得确认。
  - 竖版情况下建议使用 `1200×1600`、`1536×2048` 一类尺寸（宽高取 16 的倍数、像素积达标）。
- **版面结构自上而下**：顶部大号米白衬线标题位 → 其下小字文案位 → 中间圆角方框窗口（毡质主体）→ 底部米白文本卡片。三段式对齐规整，边距从容。
- **深雾紫纯色底占画面最大面积**，窗口与卡片是唯二的"面"；**不要**再加第三个装饰块、不要散落小元素、不要花纹底纹。
- **窗口内只放一个毡质主体**：主体在窗口内居中或轻微偏心，占窗口高度的 60%–80%，四周留出干净空间；花杆优雅弯曲、数朵花自然错落（若源海报主体是花）。
- **底部卡片**：卡片左侧大字体放主体名/花名（源海报逐字），右侧/其余位置放源海报的必要信息；卡片内部文字规整对齐，**无装饰边框**。
- **保留源海报的信息顺序与层级关系**（品牌/标题 → 主体 → 卖点/优惠 → QR/行动区 → 服务/法务），但可按"杂志封面"的规整三段式重新排布。
- **不得为了"排版干净"删减、弱化或省略源海报的必需信息**。留白是靠**布局**腾出来的，不是靠删信息换来的。
- **绝对不要**在窗口或卡片角上生成任何 `×` / 关闭按钮 / 窗口控件 / UI 图标。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 深雾紫纯色底、圆角方框窗口、羊毛毡主体、底部米白卡片、装饰性排版空间
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题、花名或文案；不要为了"图鉴感"而虚构拉丁学名、品种编号、产地或年份。
- 标题位可用**大号米白复古衬线**形式、小字位用**极小号宽字距**形式、卡片左侧用**大字号主体名**形式，但**必须清晰可读**，且**不得把文字或 logo 化为不可读色块**。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被毡片层次、窗口边、卡片、毛绒纤维或阴影覆盖、切碎、错位、虚化。毡质与毛绒指令越强，这些资产越容易被当成"毡片素材"糊掉，因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码保持完整清晰可扫描，不要被毛毡纤维、窗口边或阴影覆盖、不要错位、不要变形」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Note the content to preserve strictly: subject identity, flower species and flower structure, pose, spatial relations, main composition, visual focus.
4. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
5. If exact text matters, generate only the felt visual layer (title slot, copy slot, card text and QR area left clean) and plan a text overlay.
6. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
7. Review the result against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, Latin names, cultivar numbers, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks
- no borrowed flower species or flower name that does not come from the current source

## Supporting files

- `palettes.md`: 深雾紫 × 米白毛毡配色与毛毡材质/光影处理。
- `prompt-templates.md`: 可复制的中文提示词模板与出图前自检表。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio?
- Is the subject's identity, flower species and flower structure, spatial relations, main composition and visual focus **strictly preserved**?
- Is the background a **deep misty purple solid colour** — flat, opaque, no gradient, no speckle, no pattern?
- Is there an **oversized off-white vintage serif title slot** at the top, with a **small wide-tracked copy line** beneath it?
- Is a **rounded-rectangle window** placed in the middle, holding the felt subject, with clean space around it?
- Are the flower, stems and leaves **entirely soft wool-felt fabric** — not knitted loops, not crochet, not long plush fur, not printed cloth?
- Is the **felt grain clearly visible**, with a **fluffy fuzzy fibre surface** and slightly raised fuzzy cut edges?
- Is the volume built from **layered cut felt sheets** (felt on felt), not from shading or outlines?
- Is the light **hazy and softly diffused**, with soft layered shadows and no hard shadows or strong directional light?
- Is there an **off-white text card at the bottom**, with the **subject name set large on its left**?
- Is the typography **clean and regular**, with **no extra decorative frames** anywhere?
- **Is the rounded window completely free of a close button / `×` icon / window controls / any UI element in its bottom-right corner (or any corner)?**
- Are the title slot, copy line and card name taken **verbatim from the source poster** — with no invented flower name, Latin name, cultivar number or signature?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly, complete and readable?**
- Is the result free of photorealism, knitting/crochet, patchwork fabric, glass, lace, distortion, text corruption, clutter, blur?
- Is the result free of content from other projects?
- Does it read as a vintage botanical-magazine cover — cosy, quiet, handcrafted but flat and editorial?

## Scope boundary

Do not silently merge this skill with `plush-animation-poster`（毛绒/羊毛毡定格动画）、`knitted-yarn-poster`（针织毛线）、`fabric-patchwork-poster`（布艺拼接）、`crystal-glass-floral-poster`（水晶玻璃花卉）、`lace-embroidery-poster`（蕾丝刺绣）, or any other poster skill.

区分要点（**三种"纺织感"极易混淆，必须分清；材质互斥，不可混用**）：

| 易混淆 skill | 本 skill 的区分 |
|---|---|
| `plush-animation-poster` | 那边是**毛绒定格动画广告**：微型立体布景、手工道具、微距浅景深、暖自然色、毛绒玩具质感与长绒毛。本 skill 是**平面杂志海报**：深雾紫纯色底 + 圆角窗口 + 顶部衬线标题 + 底部文本卡片，**没有场景、没有道具、没有景深虚化、没有长绒毛** |
| `knitted-yarn-poster` | 那边是**针织/钩针**：清晰的**线圈针法（stitch loop）**、辫状编织纹理、毛线缠绕、俯拍静物、浅米色底。本 skill 是**毡化纤维**：毡片裁切叠贴，**不出现线圈、织纹、毛线辫、缠绕** |
| `fabric-patchwork-poster` | 那边是**碎花布/拼布**：布料印花、毛边、明线缝合、纽扣。本 skill 的毡面是**纯色毡片**，**无印花、无毛边散线、无明线针脚、无纽扣** |
| `crystal-glass-floral-poster` | 那边是通透玻璃 + 金边 + 光斑；本 skill 是**不透明的软毡**，无折射、无高光金边 |
| `lace-embroidery-poster` | 那边是白色镂空蕾丝 + 针孔花边 + 刺绣线；本 skill 无蕾丝网眼、无针孔、无刺绣 |

If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

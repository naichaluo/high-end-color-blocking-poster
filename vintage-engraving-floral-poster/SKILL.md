---
name: vintage-engraving-floral-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a vintage copperplate-engraving floral poster — dark green-grey dip-pen hatching and fine sketch hatching that model soft folded petal volume through line density, delicate pale pea-green and off-white aged paper ground, a double thin pale-green vintage frame border, an oversized vintage-script English title position at the top, the flower name at the lower right, vertical 3:4 botanical-plate style — while preserving the source poster's exact business content, hierarchy, brand assets, and typography. Use when the user asks for复古刻版画花卉海报、刻版画花卉海报、植物图鉴海报、钢笔排线花卉海报、复古植物插画海报、墨绿灰调线稿花卉海报、复古书写英文标题花卉海报或把普通海报改成复古刻版画花卉风；do not activate for钢笔淡彩、素描速写、彩色蜡笔、彩铅插画、水彩、RISO 丝网印刷, or photorealistic poster tasks."
metadata:
  short-description: 复古刻版画花卉风海报重绘 Skill
---

# Vintage Engraving Floral Poster / 复古刻版画花卉海报

把普通海报、产品描述或营销主视觉，重绘成 **复古刻版画（copperplate engraving）花卉海报**：墨绿灰调钢笔排线线稿 + 细腻素描排线塑造花瓣体积，浅豆绿米白做旧纸底，双层淡绿细线复古相框，顶部超大复古书写英文标题位，右下角花名标注——**文艺植物图鉴风格**。

**风格锁定**：vintage copperplate / engraving botanical plate × dip-pen cross-hatching × sketch hatching for volume × aged pale paper × antique picture frame × botanical-illustration plate typography。

**只改变视觉语言，不改变商业内容。**

**不需要风格参考图。源海报是唯一内容源。**

This skill is independent from `observational-pen-wash`（钢笔淡彩）、`riso-print-redesign-poster`（RISO 丝网印刷）、`watercolor-travel-card`（水彩旅行卡片）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成复古刻版画花卉风、刻版画花卉风、植物图鉴风、钢笔排线花卉风、复古植物插画风；
- create a vintage engraving / copperplate botanical floral poster with hatched linework;
- render a key visual as an antique botanical plate with a double thin frame and a vintage script title position;
- give a campaign visual a literary botanical-illustration feel.

Do not use it for 钢笔淡彩（pen and wash）、铅笔素描速写、彩色蜡笔、彩铅、水彩、RISO 丝网印刷，or photorealistic tasks with no engraving transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret only材质、排线笔触、纸底做旧、复古相框、标题排版与装饰。
2. **Choose one botanical subject as the plate's hero.** 主体只保留源海报**最核心的那一个**植物/花卉（或源海报的产品主体被"标本化"为单株植物式呈现）。不要在一张图鉴里塞进一堆互不相关的花草。
3. **Build a readable depth stack**: 做旧浅豆绿米白纸底 → 双层淡绿细线相框 → 墨绿灰调排线主体 → 标题带与花名位 → 受控层文字。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 花卉轮廓与排线体积必须一眼可辨；标题位与花名位的位置关系必须在缩略图下依然成立。

## Style definition

复古刻版画（vintage engraving）× 钢笔排线线稿（dip-pen hatching）× 植物图鉴（botanical plate）× 做旧纸张与复古相框。

### 主体与形态（忠实保留原图的植物结构）

保留源海报主体的**层叠卷边花瓣形态、自然弯折的修长花茎、翠绿色叶片与大小不一的花苞结构**（若源海报主体是浅绿洋桔梗类花卉，则该结构逐项保留；若源海报主体是其他花卉或产品，则**用同等细致的植物结构语言重绘其真实形态**，不改成别的花）。

- **花瓣**：**层叠、卷边**，边缘有自然翻卷与柔软褶皱；
- **花茎**：**修长、自然弯折**，不是笔直硬杆；
- **叶片**：翠绿色调、叶脉可辨、有自然翻转角度；
- **花苞**：**大小不一**，与盛开的花朵形成节奏。

### 线稿语言（本风格的核心）

**墨绿灰调钢笔排线线稿**（dark green-grey dip-pen hatching）：

- 线条是**钢笔/刻针**的线，**不是**平涂、水彩、油画笔触；
- **细腻素描排线纹理**——平行线、交叉排线（cross-hatching）、短线与点刻（stipple）结合；
- **用线条疏密表现柔和褶皱花瓣的体积**：亮部线稀、暗部线密，转折处加密，**体积靠排线密度而非灰色涂抹**；
- 允许**极少量**淡墨/淡色薄罩来统一重心，但**主体必须靠线成立**；
- 线条密度要有**呼吸**：留白处排线几乎消失，让纸底本色承担高光。

### 纸底与做旧

- **淡雅浅豆绿米白做旧纸张底色**（pale pea-green off-white aged paper）：整体偏冷、偏灰、低饱和；
- 纸面有**做旧质感**：细微的纸张纤维、斑驳、淡淡的岁月痕迹与轻微不均匀色斑；
- **不要**污渍过重、不要撕边、不要焦边——是**老图鉴的书页**，不是烧焦的旧信。

### 复古相框

- **双层淡绿细线条复古相框边框**（double thin pale-green vintage frame）；
- 两层细线**间距克制**，形成古典画框/标本框的感觉；
- 线条**细**、颜色**淡**，不抢主体；**不要**粗重金框、不要繁复花角纹样、不要立体阴影。

### 排版形式（视觉语言的一部分）

- **顶部超大复古书写英文标题位**：大号**复古书写/衬线**英文，宽字距，占据顶部显著位置；
- **右下角标注英文花名**：小而精致的斜体/衬线标注位；
- **简约复古排版**：大量留白、居中的一株主体、克制的辅助线（如细分隔线）。

> **文字内容规则（覆盖原风格说明里的示例英文标题与花名）**：标题位与花名位的**排版形式**是本风格的一部分，必须保留；但**具体文字内容只能用源海报自身的标题/主体名**，**不得凭空编造**新的作品名、品牌名、价格或承诺。原文风格示例里的装饰性英文（如 `SUMMER GREEN BLOOM`、`GREEN LISIANTHUS`）**只是排版样例，不得照抄到与源海报无关的作品上**。**不得加入 `prompt by awen` 这类署名**。若源海报没有英文，标题位可保留为**排版留白/占位**，或使用**源海报主体名的英文译名**（花名位同理），且**不得替代或遮挡源海报的商业文案**。详见「Text and brand handling」。

### 整体质感

- **柔和高级低饱和色调** + **版画肌理**（雕版/铜版印痕的细腻质感）；
- 主体轮廓由线构成，无写实光影渲染、无 3D、无塑料感；
- 竖版 **3:4** 是这一风格的**默认比例**；若源海报不是 3:4，以**源海报原始比例为准**并保留图鉴式排版（见 Composition rules）。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型要求规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。**风格默认竖版 3:4**——源海报本身是 3:4 时即照此执行；源海报是其他比例时，**保留源海报比例**，把图鉴排版（顶部标题带、居中主体、右下花名）**等比适配**进该比例，**不要为凑 3:4 而拉伸或裁切源版式**。
- **复古相框**：双层淡绿细线框贴着画布内缘，四边等距；框内是主体与排版区，框外不留出血。
- **主体位置**：花卉居中偏上，占框内宽度约 **55%–70%**，高度约 **50%–65%**；花茎自然向下延伸，收在花名位上方。
- **标题带**：顶部留出干净的横带，供超大复古书写英文标题位使用；标题带内保持**低细节、干净纸面**。
- **花名位**：右下角一小块干净纸面，供小号英文花名标注使用。
- **留白**：主体四周保持**大量安静留白**（是纸底本色，不是画上去的色块）；**留白靠布局腾出来，不靠删信息**。
- **信息层级**：保留源海报的信息顺序与层级关系（品牌/标题 → 主体 → 卖点/优惠 → QR/行动区 → 服务/法务），图鉴式的松弛排版可以**重排位置**，但**不得删减、弱化或省略**任何必需信息。
- 避免填满画面、避免信息堆积、避免无意义的对称装饰。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 做旧纸底、双层淡绿细线相框、墨绿灰调排线花卉、排线体积、装饰性分隔线
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案；**不加署名**（如 `prompt by awen`）。
- **顶部标题位是排版位**：内容用**源海报自身的标题或主体名**（允许其英文译名）；**右下角花名位**用**源海报主体名的英文译名**（源海报已有英文名则照用）。**不得照抄风格样例的 `SUMMER GREEN BLOOM` / `GREEN LISIANTHUS` / `FLEUR` 等装饰英文名**，除非源海报本身就叫这个名字。
- **极小辅助文字**（若有）用源海报**已有的**副标题/卖点/日期，**不得新增承诺**。
- 文字可用复古书写/衬线/斜体排版，但**必须清晰可读**；**不得把文字或 logo 化为不可读色块**。复古手写体极易被模型画成近似乱码——所有**精确信息（数字、价格、日期、电话、URL）**一律走受控层，不要交给模型手写。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被排线纹理覆盖、被做旧纸纹/斑驳侵蚀、被双层细线相框压边或切断、被误当成"线稿装饰"重画。排线与做旧指令越强，这些资产越容易被纹理吃掉，因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码/条码/logo 保持完整清晰可扫描，不要用排线覆盖、不要做旧斑驳、不要被相框线压住、不要错位」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Note the botanical content to preserve strictly: 花瓣层叠卷边形态、花茎弯折走势、叶片与叶脉、花苞大小节奏、整体姿态与朝向。
4. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
5. Lay the plate out: 双层淡绿细线相框 → 顶部标题带 → 居中主体 → 右下花名位 → 底部信息区。
6. If exact text matters, generate only the visual layer (paper, frame, hatched flower, reserved clean zones) and plan a text overlay.
7. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers; then review against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks
- no decorative English title or flower name borrowed from a style sample（如 `SUMMER GREEN BLOOM`、`GREEN LISIANTHUS`、`FLEUR`、`Pink Chrysanthemum`）——标题位与花名位必须使用**源海报自身**的标题或主体名
- no botanical subject swapped to a different species than the source poster's

## Supporting files

- `palettes.md`: 墨绿灰调、浅豆绿米白做旧纸底的色盘与排线/纸张材质规则。
- `prompt-templates.md`: 可直接复制的中文提示词模板（含图鉴主模板、纯视觉底图模板、Style preset 与出图前自检表）。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio? Is the default **竖版 3:4** respected when the source is 3:4 — and when it is not, was the source ratio kept instead of forcing 3:4 by stretching or cropping?
- Is there a **双层淡绿细线条复古相框**，两层细线间距克制、四边等距、线条细而淡，**没有**粗金框/繁复花角/立体阴影？
- Is the ground a **淡雅浅豆绿米白做旧纸张**色（冷、灰、低饱和），带细微纸纤维、斑驳与淡淡岁月痕迹——而**不是**重污渍、撕边、焦边？
- Is the linework **墨绿灰调钢笔排线线稿**（dip-pen hatching），而不是平涂、水彩、油画笔触、数码描边？
- Is there **细腻素描排线纹理**——平行线 + 交叉排线 + 短线/点刻，线条有呼吸、高光处排线几乎消失？
- Is 花瓣的**体积由线条疏密**表现，而不是靠灰色涂抹或写实阴影？
- Are 花瓣**层叠卷边**、花茎**自然弯折修长**、叶片翠绿有叶脉、花苞**大小不一**——植物的真实结构被完整保留？
- Is the subject **一个**核心植物主图，居中偏上、占框内宽度约 55%–70%，周围**大量安静留白**？
- Is there a clean **顶部横带** for the oversized vintage-script English title position, and a clean **右下角** spot for the flower name?
- Is the palette **柔和高级低饱和**，并有**版画肌理/雕版印痕**质感？
- 是否**没有**写实光影渲染、3D、塑料感、鲜艳高饱和、卡通矢量感？
- 标题位与花名位的**排版形式是否保留**（超大复古书写标题、右下小号花名、简约复古排版、宽字距）？
- 标题位与花名位的**文字内容是否来自源海报自身**（标题/主体名/英文译名），**未编造**作品名或承诺，**未照抄风格样例的装饰英文名**，**未加署名**？
- **全部源海报文字、价格、券额、日期、电话、URL、法务字样是否逐字保留且清晰可读？**
- 二维码 / 条码 / logo 是否**完整、可识别、可扫描**，未被排线覆盖、未被做旧纹理侵蚀、未被相框线压住或切断、未错位？是否建议用原素材叠回？
- 信息层级是否为「品牌/标题 → 主体 → 卖点/优惠 → QR/行动区 → 服务/法务」，且未因图鉴式排版被打乱？
- 是否**未**为了留白美学删减或弱化任何必需信息？
- 是否**没有**信息堆积、无意义对称装饰、机械模板化排版？
- 污染检查：未混入其他项目品牌/文案/额度；未借用风格样例的装饰英文名。

## Scope boundary

Do not silently merge this skill with `observational-pen-wash`（钢笔淡彩）、`riso-print-redesign-poster`（RISO 丝网印刷）、`watercolor-travel-card`（水彩旅行卡片）or any other poster skill.

**易混淆区分**：

| 对比 skill | 关键差异 |
|---|---|
| `observational-pen-wash`（钢笔淡彩） | 对方是**钢笔线 + 透明水彩薄罩**、速写观察感、大量留白于白纸；本 skill 是**纯排线刻版画**（体积靠线疏密）、做旧浅豆绿米白纸底、**双层淡绿细线复古相框**、图鉴式顶部标题带 |
| `riso-print-redesign-poster`（RISO 丝网印刷） | 对方是**2–3 色油墨平涂 + 套印错位 + 硬边几何**；本 skill 是**单色墨绿灰排线 + 做旧纸 + 古典相框**，无套印错位、无几何色块化 |
| `watercolor-travel-card`（水彩旅行卡片） | 对方是**透明水彩 + 旅行档案栏**；本 skill 无水性晕染、无档案栏，是植物图鉴版式 |

If the user wants a hybrid（例如刻版画排线 + 水彩淡罩），name the combination and describe which rules come from each skill before proceeding.

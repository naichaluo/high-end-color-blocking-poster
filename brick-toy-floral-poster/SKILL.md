---
name: brick-toy-floral-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a plastic building-brick toy floral poster — the floral subject rebuilt from interlocking plastic bricks with moulded stud-and-tube texture and rounded-corner brick seams, green brick stems and leaves, 3D toy-render quality with soft studio lighting and fine gentle shadows, a retro art-poster layout with a small serif decorative type position at the top and a large handwritten script title position at the bottom, on a pale pink and off-white soft palette with premium printed-poster quality — while preserving the source poster's exact business content, hierarchy, brand assets, and typography. Use when the user asks for乐高积木花卉海报、积木花卉海报、积木拼搭海报、塑料积木风海报、玩具积木海报、积木花海报、3D 玩具渲染花卉海报或把普通海报改成乐高积木花卉风；do not activate for等距治愈积木、木制积木玩具、像素积木、毛绒、黏土、纸艺、水彩, or photorealistic flower-photography poster tasks."
metadata:
  short-description: 乐高积木花卉风海报重绘 Skill
---

# Brick Toy Floral Poster / 乐高积木花卉海报

把普通海报、产品描述或营销主视觉，重绘成 **塑料积木（building-brick）花卉海报**：花卉主体由**互锁的塑料积木颗粒**拼搭而成，绿色积木花茎与叶片，**3D 玩具渲染**、**柔和影棚灯光**与细腻柔和阴影，**复古艺术海报版式**——顶部小字衬线装饰字符位、底部大号手写花体英文标题位，**浅淡粉米白柔和配色**，**高级印刷海报质感**。

**风格锁定**：plastic building-brick toy × interlocking stud-and-tube construction × 3D toy render × soft studio product lighting × retro art-poster layout。

**只改变视觉语言，不改变商业内容。**

**不需要风格参考图。源海报是唯一内容源。**

This skill is independent from `isometric-healing-blocks`（等距治愈积木）、`clay-animation-poster`（黏土动画）、`plush-animation-poster`（毛绒/羊毛毡）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成乐高积木花卉风、积木花卉风、积木拼搭风、塑料积木风、玩具积木风；
- create a plastic building-brick / toy-brick floral poster with 3D toy-render quality;
- render a key visual as a brick-built model shot under soft studio light on a retro poster layout;
- give a campaign visual a premium printed toy-poster feel.

Do not use it for 等距治愈积木（isometric healing blocks）、木制积木玩具、像素积木、毛绒、黏土、纸艺、水彩，or photorealistic flower-photography tasks with no brick-toy transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret only积木材质、拼搭结构、灯光、版式与装饰。
2. **Choose one brick-built hero model.** 主体只保留源海报**最核心的那一个**花卉/产品主体，把它整体转译成**一株积木模型**：花朵、花茎、叶片全部由积木构成，不要散落一堆彼此无关的积木，也不要在画面里同时搭出多个不相干主体。
3. **Build a readable brick stack**: 浅粉米白柔和底 → 积木拼搭主体（圆角拼接层次）→ 柔和影棚光影 → 顶部小字衬线装饰位 + 底部大号手写花体标题位 → 受控层文字。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 积木花朵的轮廓与拼搭结构必须一眼可辨；标题位与装饰位的位置关系必须在缩略图下依然成立。

## Style definition

塑料积木（plastic building brick）× 3D 玩具渲染（3D toy render）× 柔和影棚灯光（soft studio lighting）× 复古艺术海报版式（retro art-poster layout）。

### 主体与拼搭结构

花卉主体由**积木拼搭**而成：

- **花朵**：花瓣由**积木颗粒**逐块拼搭，**花瓣带有积木圆角拼接层次**——每一层的轮廓是圆角积木块外缘，层与层之间是**清晰的拼接台阶**；
- **花茎与叶片**：**绿色积木**构成的花茎与叶片，长度与角度由积木块数决定，转折处可见积木接缝；
- **花心/花蕊**：用小块积木或积木凸点阵列表现；
- **拼搭逻辑必须成立**：积木之间**互锁、对齐、承重合理**——不要出现悬空、错位、互相穿插的积木。

### 材质（本风格的核心）

**塑料积木颗粒质感**：

- 表面是**注塑塑料**：细腻的哑光光泽、边缘略有倒角、表面有极轻微的模具纹理；
- 可见**积木颗粒特征**：圆角外缘、块与块之间的**细接缝线**、以及暴露面上的**圆形凸点（stud）/凹槽**；
- 塑料是**干净的玩具塑料**：不脏、不旧、不刮花、不透明、不金属、不玻璃、不陶瓷；
- 不要平滑无缝的整体塑料块——**拼搭痕迹必须看得见**。

### 光影

**3D 玩具渲染 + 柔和影棚灯光**：

- **柔和影棚灯光**：大面积柔光，光比克制，高光是**柔和的宽高光**而不是硬点高光；
- **细腻柔和阴影**：积木之间、花瓣层叠之间存在**柔和的接触阴影**，让拼接层次可读；
- 阴影**边缘柔、过渡干净**；投在底色/桌面上的阴影**淡而收拢**；
- 光从**偏上方**来，保持统一的单一主光方向；
- 禁止：硬边强对比影棚灯、戏剧性聚光、彩色灯光污染、环境反射杂乱、粗糙噪点、过曝死白。

### 配色

**浅淡粉米白柔和配色**（pale pink + off-white）：

- 底色为**米白 / 浅米白**，柔和、干净、微暖；
- 花朵以**浅粉、淡粉、藕粉、奶粉**为主，可有极浅的白色积木作层次；
- 花茎叶片为**柔和的绿色积木**（不刺眼、不荧光）；
- 整体**低到中等饱和、明亮、干净、甜美但不俗气**；
- **主体色准优先**：若源海报主体有明确的识别色（品牌色、产品色），积木要用**该色系的柔和版本**保留识别度，**不换色系**。
- 禁止：色彩艳丽刺眼、荧光色、脏灰、重暗调、高对比撞色。

### 版式（复古艺术海报版式）

- **竖版构图**：源海报为竖版时即照此执行；源海报为横版时保留源比例并等比适配。
- **画面顶部**：**小字衬线装饰字符位**（small serif decorative type）——克制、精致、可带细装饰线；
- **画面底部**：**大号手写花体英文标题位**（large handwritten script title）——占据底部显著宽度，可与积木主体轻微重叠但不遮挡主体关键结构；
- **整体**：简约文艺、大量留白、克制的装饰线；**高级印刷海报质感**（细腻印刷网纹/纸张质感，绝不是屏幕渲染图直接导出）。

### 排版形式（视觉语言的一部分）

> **文字内容规则（覆盖原风格说明里的示例装饰字符与标题）**：顶部装饰字符位与底部手写花体标题位的**排版形式**是本风格的一部分，必须保留；但**具体文字内容只能用源海报自身的标题/主体名**，**不得凭空编造**新的作品名、品牌名、价格或承诺。原文风格示例里的装饰字符（如 `FLEUR`）与示例标题（如 `Pink Chrysanthemum`）**只是排版样例，不得照抄到与源海报无关的作品上**。**不得加入 `prompt by awen` 这类署名**。若源海报没有英文，标题位可保留为**排版留白/占位**，或使用**源海报主体名的英文译名**，且**不得替代或遮挡源海报的商业文案**。详见「Text and brand handling」。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型要求规整：宽高为 16 的倍数、像素积合理达标，尽量贴近原尺寸）。**风格默认竖版构图**——源海报是竖版时照此执行；源海报是横版时**保留源比例**，把「顶部装饰位 + 居中主体 + 底部手写标题位」等比适配进去，**不要为凑竖版而拉伸或裁切源版式**。
- **主体位置**：积木花卉居中，占画面宽度约 **45%–60%**，高度约 **40%–55%**；不要贴边、不要出血、不要占满画面。
- **顶部装饰带**：干净横带，供**小字衬线装饰字符位**使用；保持低细节、干净底色。
- **底部标题带**：干净横带，供**大号手写花体英文标题位**使用；标题带内保持**低细节、干净底色**，保证手写体可读。
- **留白**：主体左右与上下保持**充分的柔和留白**（米白底色本身）；**留白靠布局腾出来，不靠删信息**。
- **信息层级**：保留源海报的信息顺序与层级关系（品牌/标题 → 主体 → 卖点/优惠 → QR/行动区 → 服务/法务），海报式版式可以**重排位置**，但**不得删减、弱化或省略**任何必需信息。
- 避免填满画面、避免信息堆积、避免多余杂物（杂乱的积木零件、飘落花瓣、随机装饰）；**画面里不要出现人物**。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 米白底、积木拼搭花卉、圆角拼接层次、柔和影棚光影、装饰线、版式留白
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案；**不加署名**（如 `prompt by awen`）。
- **顶部小字衬线装饰位**：内容用**源海报自身的标题或主体名**（允许其英文译名），或**保留为排版留白/占位**；**不得照抄风格样例的 `FLEUR` 等装饰字符**（除非源海报本身就叫这个名字）。
- **底部大号手写花体标题位**：内容用**源海报自身的标题或主体名**（允许其英文译名）；**不得编造**与源海报无关的作品名；**不得替代或遮挡源海报的商业文案**。
- 文字可用衬线/手写花体排版，但**必须清晰可读**；**不得把文字或 logo 化为不可读色块**。手写花体极易被模型画成近似乱码——所有**精确信息（数字、价格、日期、电话、URL）**一律走受控层，不要交给手写体。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被积木颗粒覆盖、被拼接接缝或圆角切碎、被当成"积木色块"重画、被倒角变形或被阴影压暗。积木化指令越强，这些资产越容易被拆成颗粒，因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码/条码/logo 保持完整清晰可扫描，不要被积木颗粒化、不要拆成圆角块、不要被接缝或阴影切断、不要错位」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Note the subject to preserve: 花朵形态与花瓣层数、花茎走向、叶片数量与角度、整体姿态，以及源海报主体的身份特征与识别色。
4. Choose a treatment from `palettes.md` and a prompt pattern from `prompt-templates.md`.
5. Lay the poster out: 米白底 → 顶部小字衬线装饰带 → 居中积木花卉 → 底部大号手写花体标题带 → 底部信息区。
6. If exact text matters, generate only the visual layer (brick model, studio light, reserved clean zones) and plan a text overlay.
7. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers; then review against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks
- no decorative type or flower name borrowed from a style sample（如 `FLEUR`、`Pink Chrysanthemum`）——顶部装饰位与底部手写标题位必须使用**源海报自身**的标题或主体名
- no floral subject swapped to a different species than the source poster's
- no other brick-toy style mixed in (isometric block sculpture, wooden blocks, pixel blocks)

## Supporting files

- `palettes.md`: 浅粉米白柔和色盘、塑料积木材质、影棚光影与版式规则。
- `prompt-templates.md`: 可直接复制的中文提示词模板（含积木海报主模板、纯视觉底图模板、Style preset 与出图前自检表）。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio? Is the default 竖版构图 respected when the source is vertical — and when it is not, was the source ratio kept instead of forcing a vertical crop?
- Is the floral subject built as **一株完整的积木模型**（花朵 + 花茎 + 叶片全部由积木构成），而不是一堆散乱积木或多个不相干主体？
- 花瓣是否有**积木圆角拼接层次**，层间有清晰拼接台阶？**绿色积木花茎与叶片**是否成立？
- 拼搭逻辑是否**互锁、对齐、承重合理**，没有悬空、错位、互相穿插的积木？
- 是否为**塑料积木颗粒质感**：注塑塑料的细腻哑光光泽、圆角外缘、块间细接缝、可见圆形凸点/凹槽？
- 是否**干净玩具塑料**（不脏、不旧、不刮花、不透明、不金属、不玻璃、不陶瓷）？
- 是否是 **3D 玩具渲染 + 柔和影棚灯光**：宽柔高光、克制光比、单一主光方向（偏上方）？
- 是否有**细腻柔和阴影**：积木之间与花瓣层叠处有柔和接触阴影，让拼接层次可读，投影淡而收拢？
- 是否**没有**硬边强对比灯、戏剧性聚光、彩色灯光污染、过曝死白、噪点？
- 是否为**浅淡粉米白柔和配色**：米白/浅米白底，浅粉/淡粉/藕粉/奶粉花朵，柔和绿色茎叶，低到中等饱和、明亮干净？
- 是否**保留源海报主体的识别色系**（用该色系的柔和版本，不换色系）？
- 是否**没有**色彩艳丽刺眼、荧光色、脏灰、重暗调、高对比撞色？
- 是否有**复古艺术海报版式**：画面顶部**小字衬线装饰字符位**、画面底部**大号手写花体英文标题位**、简约文艺、克制装饰线？
- 积木主体是否居中、占宽约 45%–60%、四周有**充分的柔和留白**，未贴边未出血？
- 是否**没有**人物、没有多余杂物、没有杂乱背景、没有飘落的散积木？
- 是否有**高级印刷海报质感**（细腻印刷网纹/纸张质感），而不是屏幕渲染图？
- 顶部装饰位与底部标题位的**排版形式是否保留**？其**文字内容是否来自源海报自身**（标题/主体名/英文译名），**未编造**作品名或承诺，**未照抄风格样例的 `FLEUR` / `Pink Chrysanthemum`**，**未加署名**？
- **全部源海报文字、价格、券额、日期、电话、URL、法务字样是否逐字保留且清晰可读？**
- 二维码 / 条码 / logo 是否**完整、可识别、可扫描**，未被积木颗粒化、拆成圆角块、被接缝/阴影切断或错位？是否建议用原素材叠回？
- 信息层级是否为「品牌/标题 → 主体 → 卖点/优惠 → QR/行动区 → 服务/法务」，且未因海报版式被打乱？
- 是否**未**为了留白美学删减或弱化任何必需信息？
- 负面清单核对：**无**畸形积木、**无**破碎花朵、**无**变形花瓣、**无**水印、**无**多余杂物、**无**杂乱背景、**无**人物、**无**写实花朵、**无**照片质感、**无**卡通二次元、**无**色彩艳丽刺眼、**无**文字错乱、**无**排版混乱。
- 污染检查：未混入其他项目品牌/文案/额度；未借用风格样例的装饰英文名；未混入其他积木风格。

## Scope boundary

Do not silently merge this skill with `isometric-healing-blocks`（等距治愈积木）、`clay-animation-poster`（黏土动画）、`plush-animation-poster`（毛绒/羊毛毡）or any other poster skill.

**易混淆区分**：

| 对比 skill | 关键差异 |
|---|---|
| `isometric-healing-blocks`（等距治愈积木） | 对方是**等距视角的圆角模块雕塑**、抽象治愈系、柔和空灵配色、无具体花卉结构；本 skill 是**正/微俯视的塑料积木拼搭真实花卉**（花朵+茎+叶），有凸点/接缝/注塑塑料质感与影棚产品光 |
| `clay-animation-poster`（黏土动画） | 对方是**手捏黏土的定格动画**质感（指纹、油泥、手工不完美）；本 skill 是**工业注塑塑料积木**（精确圆角、凸点、接缝），精确对齐而非手工痕迹 |
| `plush-animation-poster`（毛绒/羊毛毡） | 对方是**纤维毛绒**（绒毛、针脚、柔软）；本 skill 是**硬质塑料**，棱角与拼接台阶清晰，无纤维 |
| `riso-print-redesign-poster` / `retro-modern-print-poster` | 那两者是**平面印刷/绘画语言**；本 skill 是**3D 玩具渲染 + 印刷海报质感**的组合，主体必须是积木模型 |

If the user wants a hybrid（例如积木 + 黏土混搭，或等距积木 + 花卉），name the combination and describe which rules come from each skill before proceeding.

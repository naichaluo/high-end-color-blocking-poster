# 梵高厚涂油画海报 · Prompt Templates

把方括号内容替换成当前源海报的事实。**源海报是唯一内容源与绝对结构参考**，不需要风格参考图。

> ⚠️ **本风格首选「纯视觉底图」模板**：docx 明确规定油画本身**不含文字、签名、边框、水印**，
> 因此所有文案与二维码都应走受控层叠加，这样也天然满足「不得把文字化为不可读色块」。

## 上传图片 → 梵高厚涂油画（主模板）

```text
将提供的图片作为绝对结构参考，重绘成 19 世纪末后印象派厚涂油画。Image 1 是唯一内容与结构参考。

【画布】保留源图的原始尺寸与宽高比（不要改成正方形，不要裁切版式，不要重新构图）。

【绝对结构参考——不得改动】严格保留原图中的主体身份、人物五官、表情、姿态、手部、服装、
物体、物体数量、建筑、景观、构图、裁切、透视、拍摄视角、空间关系、前中后景结构、
光线方向与主要色彩关系。不得新增、删除、替换、移动或重新设计任何叙事元素。
逐项列出必须保留的内容：[主体身份 / 人物数量与五官表情姿态 / 手部 / 服装 / 物体与数量 /
建筑结构 / 景观 / 构图与裁切 / 透视与视角 / 前中后景 / 光线方向 / 主要色彩关系]。

【仅改变视觉媒介】将整个画面重新绘制为 19 世纪末后印象派厚涂油画，参考梵高式绘画语言，
但不复制任何具体作品的构图。

【方向性笔触（核心）】使用明显、富有方向性的油画笔触，笔触顺着物体结构和体积运动：
- 人物与面部：短促的轮廓笔触；
- 衣物与物体：有节奏的重复笔触；
- 建筑：较有秩序的线性笔触；
- 自然元素：更流动有机的笔触。
加入厚涂颜料、断色、层叠色块、局部颜料隆起和真实画布肌理。

【色彩】保留原图色彩逻辑，同时增强后印象派式冷暖和互补色关系。
使用群青、钴蓝、蓝绿、赭石、金黄、暖橙、橄榄绿、熟褐、红棕等颜色，
但不得强行改变原物体颜色。使用色彩关系和方向性笔触塑造明暗，避免平滑数字渐变。

【人物保真（硬约束）】所有人物必须严格保持原始身份、脸型、五官、表情、姿态、手部、
身体比例与位置，不得为了风格而改变人物结构。

【最终效果】必须像真实的实体厚涂油画，而不是照片滤镜：可见笔触、厚重颜料、画布纹理、
丰富色层、手工不规则边缘、强烈而自然的后印象派绘画感。

【文字空间预留】不要在画面里写任何文字、签名、边框或水印。
把标题区、卖点条、价格区、二维码区、底部服务条预留为相对平整、低笔触密度、低细节的颜料区域，
以便后期精确叠加原文案与二维码。

【商业内容与功能性资产】源海报的全部文案与资产必须完整保留、逐字不改：
品牌 logo 与字样、主标题、副标题与卖点、价格与券额数字、日期、电话、URL、二维码及其位置、
底部服务与法务信息、产品/规格标签文字。逐字列出：[把源海报上的文字逐条填在这里]。
不得把文字或 logo 化为不可读色块；不要新增、编造或改写任何文案。
二维码/条码/logo 必须保持完整、可识别、可扫描：不要被厚涂颜料、笔触或颜料隆起覆盖、
模糊、变形、错位，保持水平，保持完整对比度。最佳做法是从源海报原样贴回。

【约束】不要混入其他项目或其他参考图的内容。
禁止：改变构图、改脸、改姿势、人体畸形、多指缺指、增删物体、移动元素、
改变建筑结构和透视、强行加入星空、向日葵、柏树或其他原图不存在的梵高元素、
过度旋涡化、卡通、水彩、丙烯、塑料质感、喷枪、数字滤镜、机械重复纹理、
文字、签名、边框、水印。
```

## 纯视觉底图（本风格首选工作流）

```text
以提供的图片为绝对结构参考，只生成「后印象派厚涂油画」的视觉层，不写任何文字。

严格保留原图的主体身份、人物五官、表情、姿态、手部、服装、物体与物体数量、建筑、景观、
构图、裁切、透视、拍摄视角、空间关系、前中后景结构、光线方向与主要色彩关系；
不得新增、删除、替换、移动或重新设计任何叙事元素。
［逐项列出必须保留的内容］

仅改变视觉媒介：绘制为 19 世纪末后印象派厚涂油画，参考梵高式绘画语言，不复制任何具体作品构图。

明显、富有方向性的油画笔触，笔触顺物体结构与体积运动：
人物与面部用短促的轮廓笔触；衣物与物体用有节奏的重复笔触；
建筑用较有秩序的线性笔触；自然元素用更流动有机的笔触。
厚涂颜料、断色、层叠色块、局部颜料隆起、真实亚麻画布肌理从颜料层透出。

保留原图色彩逻辑，增强冷暖与互补关系：群青、钴蓝、蓝绿、赭石、金黄、暖橙、橄榄绿、熟褐、红棕；
不得强行改变原物体颜色；明暗由色彩关系与笔触方向塑造，避免平滑数字渐变。

所有人物严格保持原始身份、脸型、五官、表情、姿态、手部、身体比例与位置，不得为了风格改变人物结构。

像真实的实体厚涂油画：可见笔触、厚重颜料、画布纹理、丰富色层、手工不规则边缘。

保留源图原始尺寸与比例。把标题区、卖点条、价格区、二维码区、底部服务条预留为
相对平整、低笔触密度、低细节的颜料区域（例如一段较匀的平涂底色），
不要在这些区域堆厚涂隆起。不要生成任何可读文字、签名、边框、水印，不要虚构 logo 或二维码。

避免：改变构图、改脸、改姿势、人体畸形、多指缺指、增删物体、移动元素、改变建筑结构与透视、
强行加入星空/向日葵/柏树或其他原图不存在的梵高元素、过度旋涡化、卡通、水彩、丙烯、
塑料质感、喷枪、数字滤镜、机械重复纹理、文字、签名、边框、水印。
```

## 附：Style preset 关键词块（追加到提示词末尾）

```text
STYLE_PRESET: Late 19th-century Post-Impressionist Impasto Oil Painting
CORE: post-impressionist oil painting, van gogh inspired painting language, thick impasto,
directional brushwork following each object's structure and volume, broken colour,
layered colour patches, local paint ridges, real canvas weave, handmade irregular edges
BRUSHWORK: short contour strokes on figures and faces, rhythmic repeated strokes on clothing and objects,
more ordered linear strokes on architecture, more flowing organic strokes on natural elements
COLOR: ultramarine, cobalt blue, blue-green, ochre, golden yellow, warm orange, olive green,
burnt umber, red-brown, strengthened cool-warm and complementary relationships,
original colour logic preserved, light and shade built from colour and stroke direction, no smooth gradient
SURFACE: visible brush marks, thick paint, canvas texture, rich paint layers, physical painted surface
STRUCTURE: source image is the absolute structural reference, composition, cropping, perspective,
camera angle, spatial relations, foreground midground background, light direction strictly preserved,
nothing narrative added, removed, replaced or moved
MOOD: expressive, painterly, energetic, handmade, physical, museum canvas
AVOID: changed composition, changed face, changed pose, deformed anatomy, extra or missing fingers,
added or removed objects, moved elements, changed architecture or perspective, forced starry sky,
forced sunflowers, forced cypress trees, any van gogh motif not present in the source,
over-swirling, cartoon, watercolour, acrylic, plastic, airbrush, digital filter,
mechanically repeated texture, text, signature, border, watermark
```

> 该块只负责**风格**。文字与商业内容的保留规则另需按主模板照常写进提示词，不要因为加了 preset 就省掉。

## 出图前自检

| 检查 | 期望 |
|---|---|
| 画布尺寸 | **保留源图原始尺寸与比例**；未重新构图、未改裁切 |
| 结构保真 | 主体身份、人物五官、表情、姿态、手部、服装、物体与数量、建筑、景观全部严格保留 |
| 视角保真 | 构图、裁切、透视、拍摄视角、空间关系、前中后景结构未变 |
| 光线保真 | 光线方向与原图一致 |
| 色彩逻辑 | 保留原图主要色彩关系；**未强行改变原物体颜色** |
| 叙事零改动 | 未新增、删除、替换、移动或重新设计任何元素 |
| 媒介 | 确为 19 世纪末后印象派厚涂油画；未复制任何具体梵高作品构图 |
| 方向性笔触 | 笔触**明显有方向**，并**顺物体结构与体积运动** |
| 笔触分工 | 人物/面部=短促轮廓笔触；衣物/物体=有节奏重复笔触；建筑=较有秩序线性笔触；自然元素=更流动有机笔触 |
| 厚涂 | 有厚涂颜料、**局部颜料隆起**、可见颜料脊与堆叠 |
| 断色 | 相邻色块**不完全调和**，靠并置小色块混色 |
| 色层 | 层叠色块，下层局部透出 |
| 画布肌理 | **真实画布/亚麻织纹**从颜料层透出 |
| 色盘 | 使用群青、钴蓝、蓝绿、赭石、金黄、暖橙、橄榄绿、熟褐、红棕 |
| 冷暖互补 | 冷暖与互补关系被**增强**，但未改变物体原色归属 |
| 明暗方式 | 由**色彩关系 + 笔触方向**塑造；**无平滑数字渐变** |
| 人物结构 | 身份、脸型、五官、表情、姿态、手部、身体比例与位置**未变**；**无畸形、无多指缺指** |
| 实体油画感 | 可见笔触、厚重颜料、画布纹理、丰富色层、手工不规则边缘——**不是照片滤镜** |
| 文字预留区 | 标题区/卖点条/价格区/QR 区/服务条为**低笔触密度、低细节**颜料区域，可叠加清晰文字 |
| 文字叠加 | **全部源文案逐字保留、可读**；未新增或编造文案 |
| 价格/券额/日期/电话/URL | 逐字一致，未删改 |
| 二维码 | 位置保留，**完整可扫描**；未被厚涂颜料/笔触/隆起覆盖、模糊、变形、错位；建议用原素材叠回 |
| logo/品牌标识 | 完整可识别，未被笔触拆解或重画 |
| 无文字层 | 油画本体**无文字、无签名、无边框、无水印**（含 `prompt by …` 类署名） |
| 无梵高元素强塞 | **无星空、无向日葵、无柏树、无麦田、无乌鸦**等原图不存在的元素 |
| 风格排除 | 无过度旋涡化、无卡通、无水彩、无丙烯、无塑料质感、无喷枪、无数字滤镜、无机械重复纹理 |
| 缩略图测试 | 缩略图下主体身份、面部/结构、构图与视觉焦点仍一眼可辨 |
| 污染检查 | 未混入其他项目品牌/文案/额度/元素 |

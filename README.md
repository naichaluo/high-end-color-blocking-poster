# Poster Design Skills

一组面向图像 Agent、品牌设计和广告工作流的海报风格 Skill。每个 Skill 都是一套独立的视觉决策规则，可用于分析参考图、生成图像 Prompt、重绘普通海报或指导后期排版。

适用于 ComfyUI、Stable Diffusion、Flux、Midjourney，以及 DeepSeek Harness、Codex、Claude Code、OpenClaw 等支持 Markdown Skill 的 Agent。

## 九种独立风格

### 1. High-End Color-Blocking Poster

高级感撞色海报。强调受控的 2–3 色配色、大面积几何色块、充足留白、现代编辑排版和轻微印刷质感。

适合品牌活动、通信促销、权益产品、文化活动和需要简洁高级感的商业海报。

[进入 High-End Color-Blocking Poster](high-end-color-blocking-poster/)

### 2. Paper Collage Poster

剪纸 / 纸艺拼贴海报。强调纸片裁切、分层组合、手工边缘、纸纤维、平面插画和具有亲和力的广告创意。

适合奶茶、食品、节日活动、年轻化品牌和需要手工纸艺感的视觉项目。

[进入 Paper Collage Poster](paper-collage-poster/)

### 3. Torn Paper Relief Poster

撕纸立体浮雕海报。强调撕纸边缘、纸张厚度、凹陷窗口、浅浮雕、柔和投影和产品陈列式商业构图。

适合产品套餐、通信权益、会员促销、饮品广告和需要自然、温暖、精致商业质感的海报。

[进入 Torn Paper Relief Poster](torn-paper-relief-poster/)

### 4. Clay Animation Poster

黏土动画 / 定格动画海报。强调手工黏土质感、圆润塑形、轻微指纹与压痕、微缩场景布光和可控商业信息保真。

适合通信权益、会员促销、饮品广告、食品零售和需要亲和、立体、手作质感，同时必须保留原始品牌、金额、二维码和服务文案的商业海报。

[进入 Clay Animation Poster](clay-animation-poster/)

### 5. Plush Animation Poster

毛绒 / 羊毛毡定格动画海报。强调绒毛绒蓬松质感、短粗圆润的可爱形体、软萌表情、微缩影棚布光与温馨治愈氛围，同时严格保留原始品牌、文字与信息层级。

适合需要可爱、软萌、亲和的商业海报，以及希望把普通海报转成软毛玩具风格的视觉项目。

[进入 Plush Animation Poster](plush-animation-poster/)

### 6. Ghibli Animation Poster

吉卜力式手绘动画海报。强调水彩喷枪晕染、柔和天光、田园怀旧、治愈故事书氛围、纸纹颗粒与自然山水意象。

适合奶茶、食品、饮品、旅游、生活方式与需要温润质朴感的商业海报。

[进入 Ghibli Animation Poster](ghibli-animation-poster/)

### 7. Crayon Scribble Poster

蜡笔涂抹手绘海报。强调蜡笔粗笔触、叠色涂抹、不规整蜡笔边、暖纸纹理与童趣活力。

适合零食、饮料、儿童、节日与需要活泼手绘感的视觉项目。

[进入 Crayon Scribble Poster](crayon-scribble-poster/)

### 8. RISO Print Redesign Poster

RISO 丝网印刷几何重绘海报。强调硬边印刷轮廓、2–3 色油墨、套准纸缝、几何质量转换与中性白纸。内置「标准 RISO」与「加强 RISO」两档强度。

适合需要编辑感、印刷质感与几何抽象的商业海报，以及想把普通海报转成丝网印刷语言的视觉项目。

[进入 RISO Print Redesign Poster](riso-print-redesign-poster/)

### 9. Fabric Patchwork Poster

布艺拼接裁剪手缝海报。强调布料拼贴、毛边流苏、手缝虚线、布艺纽扣与温馨手作日式杂货氛围。默认底布为整块格纹布（铺满整张）。

适合需要温暖、可亲、手作质感的商业海报，以及想把普通海报转成拼布布艺风格的视觉项目。

[进入 Fabric Patchwork Poster](fabric-patchwork-poster/)

## 风格选择

| Skill | 视觉关键词 | 适合的效果 |
| --- | --- | --- |
| High-End Color-Blocking | 大色块、留白、几何、编辑感 | 简洁、现代、品牌化 |
| Paper Collage | 剪纸、纸片、拼贴、手工边缘 | 活泼、亲和、创意化 |
| Torn Paper Relief | 撕纸、浮雕、纸张厚度、柔和投影 | 温暖、立体、商业化 |
| Clay Animation | 黏土、定格动画、微缩布景、手作纹理 | 亲和、立体、内容保真 |
| Plush Animation | 绒毛绒、羊毛毡、短粗可爱、软萌 | 可爱、软萌、亲和小众 |
| Ghibli Animation | 水彩、田园、怀旧、治愈故事书 | 温润、质朴、治愈 |
| Crayon Scribble | 蜡笔、叠色涂抹、童趣、暖纸 | 活泼、手绘、童趣 |
| RISO Print Redesign | 丝网印刷、2–3色油墨、套准纸缝 | 编辑感、印刷感、几何抽象 |
| Fabric Patchwork | 拼布、毛边、手缝、布艺纽扣 | 温暖、可亲、手作

## 基本调用方式

将对应目录复制到目标 Agent 的 `skills` 目录，或直接让 Agent 读取其中的 `SKILL.md`。

示例：

```text
请使用 $torn-paper-relief-poster，把这张普通商业海报重绘成撕纸立体浮雕风格。
保留原海报的品牌、产品、价格、日期、二维码和法律文案；不要生成虚假文字或 Logo。
```

```text
请使用 $clay-animation-poster，把这张权益海报重绘成黏土动画风格。
只使用当前海报作为内容来源，保留品牌、金额、套餐信息、二维码和服务文案，不混入其他项目内容。
```

```text
请使用 $fabric-patchwork-poster，把这张普通海报重绘成布艺拼接裁剪手缝风格。
默认使用整块格纹布做底（铺满整张），保留原海报的品牌、价格、二维码和法律文案。
```

九个 Skill 默认相互独立。除非明确要求，不会自动叠加各风格规则（例如想叠加 RISO 与布艺时，请明确指定由哪个 Skill 主导）。

## 版权与商业使用

这些 Skill 是可复用的设计方法和 Prompt 规范，不绑定特定模型或插件。正式商业发布前，请自行确认字体、品牌资产、人物形象、Logo、二维码和图像生成模型的授权条件。

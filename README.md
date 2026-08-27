# Poster Design Skills

一组面向图像 Agent、品牌设计和广告工作流的海报风格 Skill。每个 Skill 都是一套独立的视觉决策规则，可用于分析参考图、生成图像 Prompt、重绘普通海报或指导后期排版。

适用于 ComfyUI、Stable Diffusion、Flux、Midjourney，以及 DeepSeek Harness、Codex、Claude Code、OpenClaw 等支持 Markdown Skill 的 Agent。

## 三种独立风格

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

## 风格选择

| Skill | 视觉关键词 | 适合的效果 |
| --- | --- | --- |
| High-End Color-Blocking | 大色块、留白、几何、编辑感 | 简洁、现代、品牌化 |
| Paper Collage | 剪纸、纸片、拼贴、手工边缘 | 活泼、亲和、创意化 |
| Torn Paper Relief | 撕纸、浮雕、纸张厚度、柔和投影 | 温暖、立体、商业化 |

## 基本调用方式

将对应目录复制到目标 Agent 的 `skills` 目录，或直接让 Agent 读取其中的 `SKILL.md`。

示例：

```text
请使用 $torn-paper-relief-poster，把这张普通商业海报重绘成撕纸立体浮雕风格。
保留原海报的品牌、产品、价格、日期、二维码和法律文案；不要生成虚假文字或 Logo。
```

三个 Skill 默认相互独立。除非明确要求，不会自动叠加撞色、剪纸拼贴和撕纸浮雕规则。

## 版权与商业使用

这些 Skill 是可复用的设计方法和 Prompt 规范，不绑定特定模型或插件。正式商业发布前，请自行确认字体、品牌资产、人物形象、Logo、二维码和图像生成模型的授权条件。

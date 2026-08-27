# High-End Color-Blocking Poster

一个面向图像 Agent 和设计工作流的「高级感撞色海报」Skill。它把参考图中的可复用规律整理为：受控的 2–3 色配色、大色块、大留白、现代编辑排版、单一视觉主体和轻微纸张印刷质感。

## 用途

适用于 ComfyUI、Stable Diffusion、Flux、Midjourney，以及 DeepSeek Harness、Codex、Claude Code、OpenClaw 等可读取 Markdown Skill 的 Agent。适合奶茶、食品、零售、权益、通信促销、品牌活动和文化活动海报。

它不绑定 ChatGPT、某个模型或某个插件；核心是可迁移的视觉决策规则。

## 安装与复用

直接把整个目录复制到目标 Agent 的 skills 目录，或将 ZIP 解压后读取 `SKILL.md`。

建议调用语句：

> 请使用 high-end-color-blocking-poster Skill，为我设计一张高级感撞色海报。先读取 SKILL.md，再按需求选择 palettes.md 和 prompt-templates.md；保留所有必填文案，不要擅自添加品牌事实。

也可以作为项目级资源：

```text
your-project/
└── skills/
    └── high-end-color-blocking-poster/
```

## 目录结构

```text
high-end-color-blocking-poster/
├── SKILL.md
├── README.md
├── palettes.md
├── prompt-templates.md
└── examples/
    ├── milk-tea.md
    ├── telecom-promotion.md
    └── event-poster.md
```

## 快速使用示例

```text
使用 high-end-color-blocking-poster，为「春日莓莓奶茶」做一张竖版 3:5 海报。
主色用珊瑚粉与薄荷绿，保留大面积暖象牙纸张留白；画面只放一杯简化奶茶图形。
文案：春日莓莓奶茶 / 第二杯半价 / 3月8日—3月31日。
请输出适用于 ComfyUI 的正向 Prompt、Negative Prompt、配色 HEX 和排版建议。
```

多数图像模型对中文字体和复杂品牌标志的生成不稳定。正式商业物料优先让模型生成干净图形与文字安全区，再在 Figma、Canva 或 Photoshop 中完成排版；品牌名称、价格、日期和权益条件必须人工复核。

## License

可将本目录作为个人或团队项目的一部分使用、修改和再分发。商业项目请自行确认字体、品牌资产和生成模型的授权条件。

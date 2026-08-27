# Example: 春日城市设计周

## Brief

为一场城市设计周制作文化活动海报。活动名、日期、地点和主办方是必须信息；画面要有概念性，但仍需让观众一眼找到活动名和时间。

## Art direction

- Format: vertical 3:5
- Ground: Apricot `#F2D2AA`
- Accent: Pale cyan `#B9D9D6`
- Support: Vermilion `#C85545`
- Composition: an oversized pale-cyan arch intersecting the center-right; a small vermilion sun/number mark; title stacked on the left; logistics aligned along the bottom margin
- Type: dark brown `#443A37`
- Texture: warm uncoated paper with subtle offset-print registration

## Prompt

```text
为「春日城市设计周」制作一张高级感文化活动海报，竖版 3:5。杏色纸张背景 #F2D2AA，浅青色 #B9D9D6 的超大拱形几何块从中右部穿过，朱砂红 #C85545 只用于一个小型太阳/编号标记，深棕 #443A37 用于文字，全画面控制在 3 个主要颜色。视觉概念是「城市中的一扇春日窗口」，只保留一个拱形和一个小标记，不添加建筑照片、人物、装饰贴纸或复杂插画。左侧排版活动名「春日城市设计周」，底部清晰排版「4月12日—4月20日」「上海·西岸艺术中心」「主办： [主办方]」「报名： [CTA]」。标题最大，日期次级，地点与报名信息整齐对齐。保留约 60% 留白，现代编辑设计、平面印刷、哑光纸张、轻微套色偏移，避免旅游宣传册和商业促销风格。
```

## Negative Prompt

Use the shared Negative Prompt from `prompt-templates.md`, adding: `tourism poster, landmark collage, photo montage, festival crowd, confetti, fireworks, ornate frame, childish illustration, excessive decorative icons`.

## Post-generation check

确保活动名和日期有最高信息优先级；若模型生成乱码，保留相同位置、字号比例和文字安全区，在设计软件中重排全部中文。

# Prompt Templates

将方括号内容替换为具体信息。建议把正向 Prompt 与统一 Negative Prompt 一起发送。中文正式文案最好后期排版。

## 1. 纯视觉海报

```text
Create a premium editorial color-blocking poster, vertical [3:5 or 4:5].
Ground: [GROUND COLOR + HEX], matte warm paper with a subtle fine tooth.
Use only [ACCENT COLOR + HEX] as the main saturated accent and [OPTIONAL SUPPORT COLOR + HEX] sparingly.
Composition: [ASYMMETRIC / LOWER-LEFT / OFFSET CIRCLE / DIAGONAL BLOCK], approximately [PERCENTAGE]% open negative space.
Render ONE symbolic subject: [SUBJECT], as a clean flat hard-edged illustration, occupying about [15–30]% of the canvas and placed [POSITION].
Use restrained editorial typography zones but no readable text. Add only subtle print registration marks and delicate ink texture.
Fresh, intelligent, tactile, modern independent magazine design; no glossy advertising finish.
```

## 2. 中文营销海报

```text
为「[品牌/产品]」设计一张高级感撞色中文营销海报，竖版 [3:5/4:5]。
背景使用 [GROUND + HEX] 的哑光暖纸张；主撞色为 [ACCENT + HEX]，辅助色为 [SUPPORT + HEX]，全画面控制在 2–3 个主要颜色。
使用一个大型但简洁的 [产品/象征主体]，位于 [位置]，占画面约 [15–30]%；保留约 [55–75]% 大面积留白。
文案层级：主标题「[主标题]」；副标题「[副标题]」；权益/价格「[权益]」；时间或 CTA「[时间/CTA]」。
排版采用现代无衬线中文字体、短句、清晰留白和不对称编辑构图。保持文字区域干净、高对比、可后期替换。
禁止添加未提供的品牌承诺、价格、日期、Logo 或产品配件。
```

## 3. 产品 / 权益海报

```text
Create a high-end product-benefit poster for [BRAND/PRODUCT], vertical [RATIO].
Art direction: [GROUND + HEX] paper field, [ACCENT + HEX] oversized geometric block, [SUPPORT + HEX] micro-accent only.
Show one simplified product silhouette or symbolic icon: [PRODUCT], front-facing or clean side view, no extra props, no photorealistic reflections, no 3D gloss.
Hierarchy: large short headline “[HEADLINE]”, a compact benefit line “[BENEFIT]”, clear price/offer “[OFFER]”, and a small CTA “[CTA]”.
Keep the offer readable and inside safe margins. Use generous negative space, flat ink shapes, subtle paper tooth, and editorial art direction.
If Chinese typography is unreliable, preserve exact text-safe areas for final typesetting.
```

## 4. 活动海报

```text
为「[活动名称]」制作一张现代编辑感活动海报，比例 [RATIO]。
视觉概念：[一个可视化概念/象征物]；背景 [GROUND + HEX]；主色块 [ACCENT + HEX]；辅助色 [SUPPORT + HEX]。
构图采用 [几何结构]，主体只保留 [一个主体]，不堆叠装饰；留白约 [55–75]%。
文案必须完整且原样保留：活动名「[活动名]」、日期「[日期]」、地点「[地点]」、主办方「[主办方]」、报名方式「[CTA]」。
标题最大，日期和地点次级，主办方与报名信息最小但清楚。加入极少量编号、细线或印刷套色标记，整体哑光、克制、具有文化活动海报的高级感。
```

## Shared Negative Prompt

```text
cluttered layout, dense scrapbook, excessive decoration, too many colors, more than three major colors, random gradients, neon, cyberpunk, glossy 3D render, plastic material, metallic gradient, photorealistic product mockup, generic e-commerce banner, cheap promotional design, loud sale stickers, excessive badges, bevel, drop shadow, lens flare, strong glow, oversaturated colors, pure black background, pure white sterile background, low contrast text, illegible typography, misspelled text, gibberish letters, invented logo, invented brand claim, unrequested prop, extra object, duplicate subject, busy background, cramped margins, centered everything, copied reference composition, generic grain overlay, heavy film damage, watermark, signature
```

## 输出协议（推荐）

让 Agent 依次返回：设计摘要；选用配色（HEX、RGB、颜色角色）；可直接生成的 Prompt；Negative Prompt；中文排版层级与安全区建议；生成后检查清单。

# Example: 中国移动 / 中国电信类权益促销

## Brief

制作一张通信权益促销海报。案例使用占位品牌，便于替换为中国移动、中国电信或其他已获授权的品牌资产。重点是「流量权益」和「限时办理」，视觉要可信、清楚、年轻，但不能像满版价格贴纸。

## Art direction

- Format: vertical 4:5
- Ground: Dusty blue `#D9E7EA`
- Accent: Vermilion `#D95745`
- Support: Warm ivory `#FFF8E9`
- Composition: a large vermilion quarter-circle entering from the right; one simple phone/signal symbol inside it; headline anchored upper-left; offer in an ivory card with generous padding
- Type: dark blue-gray `#273B45`; brand logo inserted later from official asset
- Texture: clean matte paper, no metallic or neon effects

## Prompt

```text
为「[中国移动/中国电信]」制作一张高级感撞色通信权益促销海报，竖版 4:5。使用雾蓝色背景 #D9E7EA，大面积朱砂红 #D95745 四分之一圆形从右侧切入，暖象牙白 #FFF8E9 作为一个留白信息卡，全画面仅 3 个主要颜色。只表现一个极简手机与信号的平面符号，不出现真实手机反光、人物、手、5G塔或其他道具。主标题「[流量权益标题]」位于左上，权益信息「[具体流量/套餐]」放入象牙白信息卡，CTA「限时办理」清晰可见，日期「[起止日期]」放在底部小字。保留官方品牌 Logo 的后期置换安全区，不生成任何自创 Logo 或未经提供的宣传承诺。现代无衬线字体、大留白、不对称编辑构图、哑光纸张、轻微印刷纹理，可信而不拥挤。
```

## Negative Prompt

Use the shared Negative Prompt from `prompt-templates.md`, adding: `telecom tower, handset photo, signal explosion, rainbow gradient, holographic effect, fake official logo, invented pricing, unreadable legal text, excessive sale badges`.

## Post-generation check

品牌 Logo、套餐价格、流量数值、有效期、适用范围和法律/资费说明必须使用官方内容后期替换并复核；生成图只负责视觉构图。

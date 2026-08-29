# Fabric Patchwork Poster

把普通海报/产品描述/营销主视觉，重绘成**布艺拼接裁剪手缝风**风格的广告：不同布料层叠拼贴、毛边流苏、手缝线迹、布艺纽扣、温馨自然的手作氛围。

这是一个**独立** Skill，不与 `ghibli-animation-poster`、`crayon-scribble-poster`、`monument-valley-poster`、`riso-print-redesign-poster`、`plush-animation-poster`、`clay-animation-poster`、`torn-paper-relief-poster`、`paper-collage-poster`、`high-end-color-blocking-poster` 合并规则，除非用户明确要求组合风格。

## 关键点

- **内容隔离**：绝不借用/混入其他项目、以往对话或其他海报的品牌、文案、优惠额度。源海报只提供商业事实，本 skill 只涂布艺视觉处理。
- **两层流程**：视觉层（拼布、布艺道具、缝线、纽扣）与受控层（精确标题/价格/品牌/二维码/服务条款）分开；文字、logo、QR 用原素材叠加，不交给图像模型乱造。
- **风格**：布艺拼接——棉麻/格纹/碎花布拼贴 + 毛边流苏 + 手缝虚线 + 布艺纽扣 + 哑光织物质感 + 温馨手作。不是纸艺拼贴或数字纹理滤镜。
- **构图**：保留源海报信息顺序和主布局逻辑，留出平静布面给标题与文字。

## 配套文件

- `SKILL.md`: 核心规则、触发条件、工作流、质量门、污染检查、边界。
- `palettes.md`: 布料配色与材质处理。
- `prompt-templates.md`: 可复用提示词模板（风格迁移 / 纯视觉底图 / 从文案新做 / 校验清单）。
- `examples/`: 示例需求与提示词应用。

## 快速上手的四句话

1. 先 `skill` 加载 `fabric-patchwork-poster`。
2. 以原海报为参考图（`image`），提示词写「保留主体+全部文字，只改材质为布艺拼接裁剪手缝」。
3. 出图后核对文字。
4. 要零误差就用两层流程：纯布艺视觉底图 + 排版叠回原文字。

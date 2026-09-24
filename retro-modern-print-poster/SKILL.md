---
name: retro-modern-print-poster
description: "Transform an ordinary poster, product brief, or campaign key visual into a refined retro-modern art-print painting — bold flat color blocks, simplified geometric shapes, clear contours, reduced tonal gradations, strong graphic separation between foreground, midground and background, and a balance between recognizable figuration and visual abstraction, rendered on a specified palette (cobalt blue / ultramarine / cyan / turquoise / deep blue-black shadows / emerald and deep greens / coral pink / salmon pink / occasional magenta / warm yellow / cream / pure white accents) with the hallmark of the style: simulated print grain — screen-print grain, lithographic pigment texture, offset-print noise, restrained halftone and uneven pigment density — where the texture is fused INTO the color rather than laid over it as a filter. Use when the user asks for复古现代艺术版画海报、复古现代版画风海报、艺术版画海报、平色块版画海报、几何平涂版画海报、丝网印颗粒质感海报、石版画质感海报、模拟印刷颗粒海报、retro modern print poster 或把普通海报改成复古现代艺术版画风；do not activate for RISO hard-edge limited-ink two-color work, flat vector, watercolor, crayon, paper-art, 3D, or photorealistic poster tasks."
metadata:
  short-description: 复古现代艺术版画（模拟印刷颗粒）风海报重绘 Skill
---

# Retro Modern Print Poster / 复古现代艺术版画海报

把普通海报、产品描述或营销主视觉，重绘成**一幅精心制作的复古现代艺术版画**。

最终效果像**一件真正的实体绘画或高质量模拟版画**：宁静、饱和、几何控制精准、略带怀旧气息、视觉简洁、色彩丰富、触感微妙，表面的颗粒质感明确体现着模拟工艺。

**只改变视觉语言，不改变商业内容。**

This skill is independent from `riso-print-redesign-poster`（RISO 丝网印刷）、`high-end-color-blocking-poster`（高级撞色）、`flat-spot-poster`（留白平涂小景）、`paper-collage-poster`（纸艺拼贴）and every other poster skill. Do not merge or append another skill's rules unless the user explicitly requests a combined treatment.

## Trigger conditions

Use this skill when the user asks to:

- 把普通海报改成复古现代艺术版画风、复古现代版画风、艺术版画海报风、平色块版画风；
- 做有**丝网印颗粒 / 石版画颜料纹理 / 胶印噪点 / 半色调**质感的模拟印刷海报；
- 做**大胆平色块 + 简化几何形状 + 清晰轮廓 + 前后景强烈图形分离**的绘画性海报；
- turn a photo or key visual into a physical art print / lithograph / screen-print painting look;
- convert photographic complexity into designed painted shapes while keeping the subject recognizable.

Do not use it for RISO hard-edge limited-ink two-colour work, flat vector illustration, watercolor, crayon, paper-art, plush, clay, 3D, or photorealistic tasks. Do not use it when the user only wants a palette swap with no shape-language transformation.

## Non-negotiable decisions

1. **Separate locked communication from visual reinterpretation.** Lock the product name, offer, price, dates, URL, QR code, legal copy, brand colors when supplied, and the user's approved wording. Reinterpret only the painting language, shape simplification, tonal blocking, and surface grain.
2. **绝对参考原图**：保留原图作为**绝对参考**——主题、身份、物体、建筑、景观、姿态、比例、相机视角、透视、构图与裁剪、物体位置、空间关系、前中后景组织、基本光照方向，全部严格保留。**不得新增原图中不存在的物体**（不得添加汽车、建筑物、海滩、山脉、飞机、植被等任何原图没有的元素）。
3. **Build a readable print depth stack**: 中性纸底/大色场 → 天空与远景大色块 → 中景图形块 → 前景主体块 → 与图形同系统的文字。深度靠**透视、重叠轮廓、相对比例、水平与垂直平面、色彩对比与有序图层**建立。
4. **Treat Chinese text, numbers, URLs, logos, and QR codes as production overlays.** Do not ask the image model to redraw them. Leave clean reserved areas and add exact assets later in a deterministic editor.
5. **The poster must still work at thumbnail size.** 主体的身份特征与视觉焦点必须一眼可辨；简化不等于丢掉识别度。

## Style definition

**必须看起来像把原始照片完全从零开始重建为实体绘画或高质量模拟版画**，而不是加了滤镜的照片。颜料、颗粒、噪点和微观印刷瑕疵必须**自然地融入每一处绘画表面**。

### 造型语言（绘画性，非矢量）

- **大胆的平色块（bold flat color blocks）**；
- **简化的几何形状（simplified geometric shapes）**；
- **清晰的轮廓（clear contours）**；
- **减少色调层次（reduced tonal gradations）**；
- **前景、中景和背景之间强烈的图形分离（strong graphic separation）**；
- **可识别的具象与视觉抽象之间的平衡**。

**简化方法**：将照片的复杂性转化为**精心设计的绘画形状**。简化物体，同时**保留其标志性的轮廓、比例、方向、位置、透视和可识别的特征**。用**简洁的形状、选择性的高光、重复的小笔触、可控的图案和图形化的色调色块**来取代不必要的摄影微细节。

**植物与有机形态**：用由**密集笔触、深色轮廓和选择性明亮点缀**构成的**密集图形块**来表现。

**复杂表面**（水、玻璃、铬、波浪、倒影、窗户、远处灯光）：简化为**有节奏的重复笔触和简洁的高光**，同时保持相同的模拟颗粒感。

**建筑立面与结构**：简化为干净的彩色平面的同时，**保留建筑的几何形状和透视效果**。

**人物、车辆、产品、动物等主要对象**：保留，并保留**足够的轮廓信息**，使其与原始素材保持清晰的联系，同时自然融入相同的绘画语汇。

### 调色板（指定，必须遵守）

**鲜艳饱和、源自参考美学**：

| 角色 | 色 |
|---|---|
| 主调蓝 | **浓郁的钴蓝、群青** |
| 冷调辅助 | **青色、绿松石色** |
| 阴影 | **深蓝黑色**（唯一阴影调性） |
| 绿 | **翠绿色、深绿色** |
| 粉 | **珊瑚粉、鲑鱼粉** |
| 偶发强调 | **洋红色**（偶尔出现，小面积） |
| 暖色 | **暖黄色、奶油色** |
| 高光 | **纯净白色点缀** |

**用色规则**：
- 在**保持原有色彩关系和视觉层次**的同时，将源色彩**转换到这个调色板中**。
- 阴影统一为**深蓝黑色**调性，不要用暖褐或灰调阴影。
- **洋红只偶尔出现**，不可成为主色。
- **纯白只作点缀**，不铺大面积。

### 光影（图形化，非摄影）

- 将逼真的摄影光照**简化为大面积的图形化色调区域**。
- **保留原始光照的方向和逻辑**，但通过**简化的色块、可控的阴影轮廓、克制的高光和极少的中间色调**来表现光影。
- **避免**：光泽感强的 CGI 照明、过度的光晕、体积效果、现代电影调色、柔和的摄影过渡。

### ★ 颗粒质感规格（本风格的灵魂，必须精确执行）

**纹理对最终图像至关重要。每个色块都必须包含可见但精细的模拟表面纹理。**

**基底纹理**：在整个作品上应用一层**均匀的细腻有机颗粒、颜料噪点、微妙的色斑、微观色调变化和略微不均匀的颜料密度**。

**大面积纯色区域**——尤其是**天空、水面、墙壁、路面、建筑立面和其他宽阔的表面**——**绝不能**显得完全光滑、数字般平坦、毫无生气或像矢量图一样干净。

**颗粒来源**（模仿传统印刷和绘画的物理瑕疵）：
- 细腻的**丝网印刷颗粒**；
- **石版画颜料纹理**；
- 微妙的**胶印噪点**；
- **纸张与颜料之间微妙的相互作用**；
- 细微的**油墨密度变化**；
- 克制的**半色调不规则纹理**；
- 柔和分布的**模拟噪点**。

**⚠️ 纹理必须融入色彩之中，而不是像透明的数字噪点滤镜一样覆盖在最终图像上。**

**每种颜色都应包含其自身微妙的颜料波动**：
- **暗部**应保留细腻的颗粒变化；
- **饱和的蓝色和绿松石色**表面应呈现出**精致的斑驳纹理**；
- **粉色、珊瑚色、奶油色、绿色和黄色**区域应呈现出**微观的颜料不规则性**。

**颗粒度**：使用**中等至细的颗粒度**——**近距离观察时清晰可见，正常观看距离下略微可辨**，但**绝不能粗到遮盖形状或重要细节**。

**密度变化**：在保持图像整体纹理大致均匀的同时，允许**不同色块之间自然地存在轻微的密度变化**。

**边缘**：保持**边缘干净利落**，同时允许边界处存在**微小的颜料不规则性**，使其看起来不显得过于完美或电脑生成。

**切勿过度渲染**。作品应具有**触感和物理质感，而非做旧、污渍、破损、刮擦、严重风化或覆盖着人工胶片颗粒**。

### 最终气质

**宁静、饱和、几何控制精准、略带怀旧气息、视觉简洁、色彩丰富、触感微妙**，且表面质感鲜明地体现了模拟工艺的特点。

## Style preset (compact English keywords)

生成时把下面这个关键词块**追加到提示词末尾**（英文 art-direction 关键词模型遵循度更稳）：

```text
STYLE_PRESET: Retro Modern Art Print Painting
CORE: bold flat color blocks, simplified geometric shapes, clear contours, reduced tonal gradations,
strong graphic separation between foreground midground and background,
balance between recognizable figuration and visual abstraction
MEDIUM: physical painting / high-quality simulated art print, NOT a filtered photograph
PALETTE: rich cobalt blue, ultramarine, cyan, turquoise, deep blue-black shadows, emerald green,
deep green, coral pink, salmon pink, occasional magenta, warm yellow, cream, pure white accents
LIGHT: photographic light simplified into large graphic tonal areas, original light direction preserved,
controlled shadow contours, restrained highlights, very few midtones
DEPTH: perspective, overlapping contours, relative proportions, horizontal and vertical planes,
color contrast, ordered layers — no photographic depth of field
TEXTURE (crucial): fine organic grain, pigment noise, subtle mottling, micro tonal variation,
slightly uneven pigment density, fine screen-print grain, lithographic pigment texture, offset-print noise,
restrained irregular halftone, paper-pigment interaction; medium-to-fine grain,
visible up close, subtle at viewing distance, never coarse enough to hide shapes;
texture fused INTO the colour, not a transparent digital noise layer on top
MOOD: serene, saturated, geometrically controlled, slightly nostalgic, visually concise,
chromatically rich, tactile, museum print
AVOID: completely smooth digital surfaces, monotone flat vector colour, plastic gradients,
photorealistic rendering, photographic surface detail, glossy CGI, excessive gradients, airbrush,
watercolour bleeding, heavy paint build-up, loose expressionist brushwork, anime, comic,
childish cartoon, generic vector illustration, over-digitisation, heavy film grain, large noise,
artificial stains, scratches, aged paper, VHS artefacts, JPEG artefacts
```

> 注意：`preserve original` 只覆盖**画面**。
> 商业文案、价格、券额、二维码、品牌名的保留仍按本 skill 的「Text and brand handling」执行。

## Composition rules

- **画布保留源海报的原始尺寸与宽高比**（按模型允许规整：宽高为 16 的倍数、像素积达标，尽量贴近原尺寸）。不得改成正方形，不得裁切版式。
- **保留源海报的相机视角、透视、构图与裁剪、相对比例、物体位置与空间关系**。
- **前中后景必须图形分离**：前景、中景、背景各自成为可读的图形层，靠**重叠轮廓、色彩对比与图层秩序**分开。
- **保留信息顺序与层级关系**（品牌/标题 → 主体场景 → 卖点/优惠 → QR/行动区 → 服务/法务），但允许按版画的图形化排版重新排布。
- **文字承载区**保持大面积的**干净、低细节色块**（避免密集纹理与高频笔触），保证叠加文字的对比度。
- **不得为了"简洁美学"删减、弱化或省略源海报的必需信息**。
- 避免填满画面、避免图形块无序堆砌、避免机械居中和模板化版式。

## Text and brand handling

For commercial posters, model-generated text is risky. Prefer a two-layer workflow:

- **visual layer:** 平色块、简化几何形状、清晰轮廓、图形化光影、整个画面的模拟印刷颗粒与颜料波动
- **controlled layer:** exact headline, offer amount, brand name, QR code, phone number, address/company name, disclaimers, and product names

**文字规则**：

- **逐字保留**源海报的标题与全部文案；价格、券额、日期、电话、URL、二维码、品牌名一律不改。
- **不新增、不编造**标题或文案。本风格容易诱发模型"顺手加一行版画题签英文"，必须显式禁止。
- 文字可以用**与图形同系统的几何无衬线或克制的衬线字体**排版，但**必须清晰可读**，且**不得把文字或 logo 化为不可读色块**。
- **颗粒质感不得作用于文字**：文字必须保持干净边缘与充足对比，不要给文字加颗粒、半色调网点或做旧效果，否则会削弱可读性。文字区的底色也要保持低细节。
- 若 logo 或二维码必须可用，从源海报或品牌素材直接贴回，不要让模型自己画。
- **功能性资产保护（硬规则）**：二维码、条码、logo、认证标识等必须保持**完整、可识别、可扫描**——**不得**被颗粒、半色调、色块、简化造型或印刷错位影响。颗粒与半色调指令越强，这些资产越容易被网点化，因此：最佳做法是从源海报**原样贴回**；若必须由模型渲染，提示词中要显式写明「二维码保持完整清晰可扫描，不要加颗粒、不要加半色调网点、不要被色块覆盖、不要错位或旋转、不要改变对比度与配色」。

When using image generation, quote required text verbatim in the prompt, but still verify and correct it afterward.

## Workflow

1. Identify the active source of truth: source poster, text brief, brand kit, or user-provided copy.
2. Extract locked content before styling: brand name/logo, headline, offer amount, product labels, QR code, legal/service text, and visible hierarchy.
3. Note the content to preserve strictly: subjects and their identity features, object counts, pose, camera angle, perspective, composition and crop, relative proportions, spatial relations, foreground/midground/background organisation, base light direction.
4. Choose a palette arrangement from `palettes.md` and a prompt pattern from `prompt-templates.md`.
5. Build the print depth stack in order: 大色场/远景 → 中景图形块 → 前景主体块 → 图形化光影区域 → 全画面模拟颗粒（融入色彩）→ 文字预留区。
6. If exact text matters, generate only the painted visual layer and plan a text overlay.
7. Reapply exact text, QR codes, logos, prices, and service details as controlled overlay layers when possible.
8. Review the result against the source and remove any content that came from another project.

## Current-project isolation

Before final delivery, perform a contamination check:

- no brand names from unrelated projects
- no product names from unrelated posters
- no slogans, mascots, coupons, or visual motifs copied from previous turns unless they are in the current source
- no changed offer amounts
- no replaced QR code or phone number unless the user explicitly asks
- no invented objects, landscapes, vehicles, buildings, or vegetation that are absent from the current source
- no model-added decorative English title, print-shop caption, edition number, or artist signature

## Supporting files

- `palettes.md`: 指定版画调色板、色块与颗粒材质规格。
- `prompt-templates.md`: 主模板 + 纯视觉底图模板 + 出图前自检表。
- `examples/`: 示例需求与应用。

## Quality gate

- Does the canvas keep the source poster's original dimensions and aspect ratio?
- Are the theme, subject identity, object counts, pose, camera angle, perspective, composition and crop, relative proportions, object positions, spatial relations and foreground/midground/background organisation **strictly preserved**?
- Were **no objects added** that do not exist in the source (no invented cars, buildings, beaches, mountains, planes, vegetation)?
- Is the image built from **bold flat color blocks**, **simplified geometric shapes**, **clear contours** and **reduced tonal gradations**?
- Is there a **clear graphic separation** between foreground, midground and background?
- Is there a real **balance between recognizable figuration and visual abstraction** — simplified but still identifiable?
- Does the palette use **rich cobalt blue / ultramarine / cyan / turquoise / deep blue-black shadows / emerald and deep green / coral pink / salmon pink / occasional magenta / warm yellow / cream / pure white accents**?
- Are **shadows deep blue-black**, magenta **only occasional**, and pure white **only an accent**?
- Is the photographic light simplified into **large graphic tonal areas** while keeping the original light direction and logic?
- **Does every color block carry visible but fine simulated surface texture** — screen-print grain, lithographic pigment texture, offset-print noise, restrained halftone, uneven pigment density?
- Are large flat areas (sky, water, walls, pavement, facades) **free of completely smooth, digitally flat, vector-clean surfaces**?
- **Is the grain fused INTO the colour** — each colour carrying its own subtle pigment fluctuation — rather than sitting on top like a transparent digital noise filter?
- Is the grain **medium-to-fine** — visible up close, subtle at viewing distance, and never coarse enough to hide shapes or important detail?
- Do **edges stay clean and crisp** while showing only tiny pigment irregularities at boundaries?
- Is the result **not over-rendered** — no stains, scratches, damage, heavy weathering, or artificial film grain?
- **Are all source text, prices, offer amounts, QR code, and logos preserved exactly and readable?**
- Is the **text itself free of grain, halftone and ageing**, with clean edges and sufficient contrast?
- Is the result free of **invented copy**, decorative English titles, edition numbers, and fake signatures?
- Is the result free of smooth digital surfaces, flat vector colour, plastic gradients, photorealism, glossy CGI, airbrush, watercolor bleeding, heavy impasto, anime, comic, and childish cartoon looks?
- Does it look like the photo was **rebuilt from scratch as a physical painting or high-quality simulated print** — not a filtered photo?
- Is the result free of information clutter and template layout?

## Scope boundary

Do not silently merge this skill with `riso-print-redesign-poster`（RISO 丝网印刷）、`high-end-color-blocking-poster`（高级撞色）、`flat-spot-poster`（留白平涂小景）、`paper-collage-poster`（纸艺拼贴）or any other poster skill.

**⚠️ 最易混淆：`riso-print-redesign-poster`（RISO 丝网印刷）**。两者都涉及"印刷质感"，但语言根本不同，必须分清：

| 维度 | 本 skill（复古现代艺术版画） | `riso-print-redesign-poster`（RISO） |
|---|---|---|
| 造型 | **绘画性平色块**：精心设计的绘画形状、有笔触感的边界 | **硬边轮廓**：crisp hard printed edges，低频谱轮廓抖动 |
| 色彩 | 指定 12 色丰富调色板（钴蓝/群青/青/绿松石/翠绿/珊瑚/鲑鱼/洋红/暖黄/奶油/白） | **2–3 种限色油墨** + 中性纸底 |
| 印刷痕迹 | **模拟颗粒**：丝网印颗粒、石版画纹理、胶印噪点、半色调、颜料密度不均，**融入颜色之中** | **套准纸缝**：不均匀的窄缝、露出纸底的白边、套印错位、局部缺墨擦痕 |
| 黑色角色 | **深蓝黑色作为阴影调性**，不是"次要黑色"概念 | 黑色为**次要色，≤25% 画布** |
| 深度 | 透视、重叠轮廓、图层秩序、色彩对比 | 几何块面与结构色带 |

其他区分：

- vs `high-end-color-blocking-poster`: 那个靠**巨大平面色块 + 编辑感排版 + 轻微印刷质感**做高级感，色块是**方正、干净、纯平面**的；本风格是**绘画性简化形状 + 强烈的模拟颗粒融入色彩**，造型是精心设计的绘画形状。
- vs `flat-spot-poster`: 那个是**小图画在暖白大纸中央**的留白平涂小景；本风格是**满版绘画性重构**，画面由前景/中景/背景的图形分离构成层次。

If the user wants a hybrid, name the combination and describe which rules come from each skill before proceeding.

# Prompt Templates

## Existing Poster To Style

```text
Use case: style-transfer
Asset type: vertical commercial poster
Primary request: Redraw the provided source poster in this style.
Input image: Image 1 is the only visual and content reference.
Source-of-truth content: preserve the exact brand, headline, offer amount, product labels, QR position, service text, and overall information hierarchy from Image 1.
Style/medium: use the visual specification in SKILL.md for this style (material, palette, texture, and composition cues).
Composition/framing: keep the source poster's main layout logic: top brand and headline, central product scene, lower offer module, QR/action area, bottom service/legal line.
Scene/backdrop: [describe one central subject from the source].
Lighting/mood: [style-appropriate soft/wholesome/refined mood].
Color palette: translate the source palette into this style's palette; keep official brand color recognizable.
Text handling: leave quiet areas for exact text overlays; do not invent or alter business copy.
Constraints: do not mix in any content from previous projects or other reference images; do not change prices, amounts, package values, phone numbers, QR codes, brand names, or campaign claims.
Avoid: visible source photography, collages, invented facts/names/logos/QR codes, watermark, garbled text.
```

## Visual Base For Controlled Text Overlay

```text
Use case: ads-marketing
Asset type: text-safe vertical poster background
Primary request: Create this style's visual base matching the provided source poster, but keep all important text areas clean for later exact overlay.
Input image: Image 1 is the only visual and layout reference.
Scene/backdrop: style-rendered subject with clean reserved zones for the headline and brand copy.
Composition/framing: preserve the source poster's hierarchy and leave calm, low-detail zones for [headline], [coupon ribbon], [offer card], [QR area], and [service line].
Style/medium: style specifics from SKILL.md.
Lighting/mood: [style-appropriate].
Constraints: no readable generated text except simple placeholder shapes; no unrelated campaign references.
Avoid: fake logo, fake QR code, extra brands, changed offer content.
```

## Verification Checklist

- Does the final poster still communicate the same offer?
- Are all prices, amounts, phone numbers, and dates unchanged?
- Are brand names and logos from the current source only?
- Is the QR code copied from the source or approved asset when it needs to scan?
- Are text zones legible and not lost in the material?
- Did the style treatment change only visual style, not campaign content?

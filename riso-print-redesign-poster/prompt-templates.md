# Prompt Templates

Use these templates as starting points. Replace bracketed text with the current source content. Remove any line that does not apply.

## Existing Poster To RISO Print Redesign

```text
Use case: style-transfer
Asset type: vertical commercial poster
Primary request: Redraw the provided source poster as a Rustfield-style RISO screen-print redesign.
Input image: Image 1 is the only visual and content reference.
Source-of-truth content: preserve the exact brand, headline, offer amount, product labels, QR position, service text, and overall information hierarchy from Image 1.
Style/medium: RISO / screen-print redesign, crisp hard printed edges with broad low-frequency contour wobble, limited 2-3 ink colors plus neutral natural-white paper, narrow unequal junction gaps, exposed paper slivers, slight overlaps, registration offsets, a few local halftone / missing-ink / short-drag zones, clean large fields, geometric mass conversion, black kept secondary (at most ~25%).
Composition/framing: keep the source poster's main layout logic: top brand and headline, central product scene, lower offer module, QR/action area, bottom service/legal line.
Scene/backdrop: [describe one central graphic construction: a visual anchor mass plus a counterweight and a source-derived stamp module].
Lighting/mood: flat even print light, confident; the redesign should read as a designed screen print, not a filter.
Color palette: translate the source palette into 2-3 RISO inks on neutral natural-white paper; keep official brand color recognizable; keep black secondary.
Text handling: leave quiet areas for exact text overlays; do not invent or alter business copy.
Constraints: do not mix in any content from previous projects or other reference images; do not change prices, amounts, package values, phone numbers, QR codes, brand names, or campaign claims.
Avoid: watercolor, gouache, dry brush, craft collage, polished vector, generic grain filter, photorealistic render, blurred contour, uniform outlines, equal wide gutters, unrelated brand names, changed coupon value, invented slogans, distorted QR code, unreadable legal text, clutter that buries the anchor.
```

## RISO Visual Base For Controlled Text Overlay

```text
Use case: ads-marketing
Asset type: text-safe vertical poster background
Primary request: Create a RISO screen-print visual base matching the provided source poster, but keep all important text areas clean for later exact overlay.
Input image: Image 1 is the only visual and layout reference.
Scene/backdrop: neutral natural-white paper with a limited-ink geometric graphic construction inspired by the source, a central product mass, and a source-derived stamp module.
Subject: [describe source product props without introducing new brands].
Composition/framing: preserve the source poster's hierarchy and leave calm, lower-detail ink zones for [headline], [coupon ribbon], [offer card], [QR area], and [service line].
Style/medium: RISO screen-print, hard contour edges, limited 2-3 inks, junction gaps and paper slivers, clean large fields.
Lighting/mood: flat even print light, confident commercial readability.
Constraints: no readable generated text except simple placeholder shapes; no unrelated campaign references.
Avoid: fake logo, fake QR code, extra brands, changed offer content, blur, vector seams, equal gutters.
```

## Boosted RISO Variant (only when the user asks for a stronger / 加强 RISO look)

Swap the Style/medium line in the template above for this boosted one:

```text
Style/medium: Boosted RISO screen-print, stronger low-frequency contour wobble (still crisp, never blurred), more visible unequal gaps and exposed paper slivers, clearer registration offset and slight overprint, more active local halftone dots and missing-ink rubs and short ink drags concentrated in a few structural zones (not an even all-over texture), harder edges, crisp blocky geometry, limited 2-3 inks on neutral natural-white paper, black secondary (at most ~25%).
```

## New Poster From Copy Brief

```text
Use case: ads-marketing
Asset type: vertical campaign poster
Primary request: Design a RISO screen-print poster from the provided approved copy brief.
Approved copy: [paste exact text].
Brand assets: [describe approved logo/brand colors].
Information hierarchy: [headline first, offer second, product scene third, action/legal last].
Style/medium: RISO screen-print redesign, 2-3 inks on neutral paper, hard contour, geometric masses.
Composition/framing: clear text zones, central graphic anchor, source-derived stamp module.
Lighting/mood: flat even print light, confident editorial mood.
Constraints: use only the approved copy and assets; preserve all numbers and offer terms exactly.
Avoid: invented offers, unrelated brands, unreadable small print, photorealistic render, generic grain.
```

## Verification Checklist

- Does the final poster still communicate the same offer?
- Are all prices, data amounts, phone numbers, and dates unchanged?
- Are brand names and logos from the current source only?
- Is the QR code copied from the source or approved asset when it needs to scan?
- Are text zones legible and not lost in the ink masses?
- Does it read as a designed screen print with limited inks, not a filter?
- Did the RISO treatment change only visual style, not campaign content?

# Prompt Templates

Use these templates as starting points. Replace bracketed text with the current source content. Remove any line that does not apply.

## Existing Poster To Ghibli Animation

```text
Use case: style-transfer
Asset type: vertical commercial poster
Primary request: Redraw the provided source poster as a hand-painted Ghibli-style animation scene.
Input image: Image 1 is the only visual and content reference.
Source-of-truth content: preserve the exact brand, headline, offer amount, product labels, QR position, service text, and overall information hierarchy from Image 1.
Style/medium: hand-painted animation frame, soft watercolor and airbrush shading, translucent painterly transitions, loose brush edges, subtle paper grain, nostalgic pastoral storybook mood.
Composition/framing: keep the source poster's main layout logic: top brand and headline, central product scene, lower offer module, QR/action area, bottom service/legal line.
Scene/backdrop: [describe one central painted scene, e.g. a sunlit meadow with a cottage, a winding path through trees, a riverside village, a hill under fluffy clouds].
Lighting/mood: glowing soft daylight, gentle atmospheric haze, warm nostalgic warmth, quiet everyday magic.
Color palette: translate the source palette into watercolor tones; keep official brand color recognizable; keep a light airy sky and calm ground for readability.
Text handling: leave quiet areas for exact text overlays; do not invent or alter business copy.
Constraints: do not mix in any content from previous projects or other reference images; do not change prices, amounts, package values, phone numbers, QR codes, brand names, or campaign claims.
Avoid: photorealistic render, flat vector, glossy CGI, cold sterile look, unrelated brand names, changed coupon value, invented slogans, distorted QR code, unreadable legal text, cluttered scenery that buries the subject.
```

## Ghibli Visual Base For Controlled Text Overlay

```text
Use case: ads-marketing
Asset type: text-safe vertical poster background
Primary request: Create a Ghibli-style painted visual base matching the provided source poster, but keep all important text areas clean for later exact overlay.
Input image: Image 1 is the only visual and layout reference.
Scene/backdrop: hand-painted pastoral scene with soft sky, hills, and a central product prop inspired by the source.
Subject: [describe source product props without introducing new brands].
Composition/framing: preserve the source poster's hierarchy and leave calm, low-detail zones for [headline], [coupon ribbon], [offer card], [QR area], and [service line].
Style/medium: watercolor / airbrush hand-painted animation, gentle light, nostalgic mood, soft grain.
Lighting/mood: soft glowing daylight, gentle haze, warm commercial readability.
Constraints: no readable generated text except simple placeholder shapes; no unrelated campaign references.
Avoid: fake logo, fake QR code, extra brands, changed offer content, photorealistic render.
```

## New Poster From Copy Brief

```text
Use case: ads-marketing
Asset type: vertical campaign poster
Primary request: Design a Ghibli-style hand-painted poster from the provided approved copy brief.
Approved copy: [paste exact text].
Brand assets: [describe approved logo/brand colors].
Information hierarchy: [headline first, offer second, product scene third, action/legal last].
Style/medium: hand-painted animation, watercolor, pastoral storybook scene.
Composition/framing: clear text zones, central painted product scene, soft sky and ground.
Lighting/mood: warm glowing daylight, gentle haze, nostalgic mood.
Constraints: use only the approved copy and assets; preserve all numbers and offer terms exactly.
Avoid: invented offers, unrelated brands, unreadable small print, photo-real render.
```

## Verification Checklist

- Does the final poster still communicate the same offer?
- Are all prices, data amounts, phone numbers, and dates unchanged?
- Are brand names and logos from the current source only?
- Is the QR code copied from the source or approved asset when it needs to scan?
- Are text zones legible and not lost in the scenery or haze?
- Did the painted treatment change only visual style, not campaign content?

# Prompt Templates

Use these templates as starting points. Replace bracketed text with the current source content. Remove any line that does not apply.

## Existing Poster To Plush Animation

Use for a chubby, fluffy, cute soft-toy look (kawaii). If the user instead wants a refined / felted-accurate look, swap the "Style/medium" line for one from the Felted Variant below.

```text
Use case: style-transfer
Asset type: vertical commercial poster
Primary request: Redraw the provided source poster as a fluffy, chubby, adorable soft-toy stop-motion animation, in an irresistibly cute kawaii style.
Input image: Image 1 is the only visual and content reference.
Source-of-truth content: preserve the exact brand, headline, offer amount, product labels, QR position, service text, and overall information hierarchy from Image 1.
Style/medium: ultra-fluffy plush / faux-fur / fleece surface with big soft fuzzy pile, fine fibers, pom-poms and cotton-wool texture; short stubby chubby oversized-round body shapes; props are cute soft toys and do NOT need to match the real object's proportions; soft toy-like silhouette; happy closed-eyes and blush for charm; soft seams and gentle handmade edges.
Proportion guidance: exaggerate the roundness and shorten/stub the subject; make accents small and round; keep the whole thing toy-like and huggable, not photoreal.
Composition/framing: keep the source poster's main layout logic: top brand and headline, central product scene, lower offer module, QR/action area, bottom service/legal line.
Lighting/mood: soft plush lighting, gentle shadows, warm cozy commercial clarity, endearing wholesome mood.
Color palette: translate the source palette into plush fabric colors; keep official brand color recognizable; add a soft cream/neutral for readability.
Text handling: leave quiet areas for exact text overlays; do not invent or alter business copy.
Constraints: do not mix in any content from previous projects or other reference images; do not change prices, amounts, package values, phone numbers, QR codes, brand names, or campaign claims.
Avoid: refined hard felt, dense stitched felt, photorealistic product cutouts, glossy CGI, chrome, glass, hard-bevel 3D, cold corporate look, realistic object proportions, unrelated brand names, changed coupon value, invented slogans, distorted QR code, unreadable legal text.
```

### Felted Variant (only when the user explicitly asks for 毡/细致毡化)

```text
Style/medium: handmade wool-felt miniature set, dense felted fiber, finer stitched edges, closer-to-real proportions, refined craft finish.
```

## Plush Visual Base For Controlled Text Overlay

```text
Use case: ads-marketing
Asset type: text-safe vertical poster background
Primary request: Create a plush animation style visual base matching the provided source poster, but keep all important text areas clean for later exact overlay.
Input image: Image 1 is the only visual and layout reference.
Scene/backdrop: handmade wool-felt miniature set with central sculpted plush product props inspired by the source.
Subject: [describe source product props without introducing new brands].
Composition/framing: preserve the source poster's hierarchy and leave blank/low-detail zones for [headline], [coupon ribbon], [offer card], [QR area], and [service line].
Style/medium: wool-felt stop-motion, soft knitted fabric, round tactile forms, cozy craft finish.
Lighting/mood: bright softbox lighting, shallow but controlled depth, clean commercial readability.
Constraints: no readable generated text except simple placeholder shapes; no unrelated campaign references.
Avoid: fake logo, fake QR code, extra brands, changed offer content, glossy 3D.
```

## New Poster From Copy Brief

```text
Use case: ads-marketing
Asset type: vertical campaign poster
Primary request: Design a plush animation style poster from the provided approved copy brief.
Approved copy: [paste exact text].
Brand assets: [describe approved logo/brand colors].
Information hierarchy: [headline first, offer second, product scene third, action/legal last].
Style/medium: handmade wool-felt stop-motion, soft plush props, cozy miniature set.
Composition/framing: structured ad layout, clear text zones, central sculpted plush product scene.
Lighting/mood: soft miniature studio lighting, warm commercial mood.
Constraints: use only the approved copy and assets; preserve all numbers and offer terms exactly.
Avoid: invented offers, unrelated brands, unreadable small print, glossy CGI.
```

## Verification Checklist

- Does the final poster still communicate the same offer?
- Are all prices, data amounts, phone numbers, and dates unchanged?
- Are brand names and logos from the current source only?
- Is the QR code copied from the source or approved asset when it needs to scan?
- Are text zones legible and not swallowed by fluff?
- Did the plush treatment change only visual style, not campaign content?

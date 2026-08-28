# clay-animation-poster

`clay-animation-poster` is a reusable Codex Skill for turning campaign posters into clay animation / stop-motion style while preserving the original business content.

## Use It For

- restyling an existing poster into handmade clay animation style
- generating a new campaign poster from an approved copy deck
- creating clay-style poster prompts that keep brand and offer details locked
- separating image-model visual work from deterministic text, logo, and QR overlays

## Primary Principle

The source poster or brief controls content. The Skill controls style.

Do not mix content from unrelated campaigns, previous conversations, or earlier generated images. If the current user says one image is the only reference, treat all other historical material as out of scope.

## Recommended Output Process

1. Read the source poster or campaign brief.
2. List locked content: brand, headline, subhead, offer values, product labels, QR code, phone number, legal/service text.
3. Generate the clay-style visual base.
4. Rebuild exact text, logo, QR, and service details as controlled editable/raster overlays.
5. Compare final output with the original source before delivery.

## Files

- `SKILL.md`: invocation rules and core workflow
- `palettes.md`: color and material systems
- `prompt-templates.md`: reusable prompt patterns
- `examples/`: usage examples and anti-contamination checks

## Notes

For official advertising, treat generated text as draft art only. Keep final copy in controllable layers whenever possible.

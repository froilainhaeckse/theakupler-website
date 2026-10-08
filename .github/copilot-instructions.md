# Design system

Warm, organic, minimal. Feelings/somatic work — softness and safety over polish.
The site should feel calm, spacious, human, and grounded. Avoid anything that feels
like a generic coaching template, luxury wellness brand, or AI-polished landing page.

Palette (only these): sand #F4EFE6, forest #232B24, clay #C97B5A,
ember #B23A2A (accent, rare), dusk #3E5C58.

Color usage:
- sand is the main background.
- forest is the primary text color.
- dusk is used for quiet depth, overlays, navigation accents, and secondary emphasis.
- clay is the primary warm CTA/accent.
- ember is rare and only for small moments of emphasis, never large surfaces.
- Avoid cold grays, pure black, pure white, blue-heavy gradients, and high-gloss effects.

Type: Fraunces (headings, variable, soft axis), Karla (body, line-height 1.7).

Typography:
- Headings may be large and expressive, but should feel quiet and spacious.
- Body copy should be readable, warm, and uncompressed.
- Avoid all caps except very small labels if truly needed.
- Avoid overly clever microcopy.

Layout: one idea per screen, generous whitespace, no card grids, no borders/boxes.
Prefer soft sections, asymmetry, breathing room, and editorial rhythm.
Avoid dense layouts, repeated modules, and decorative clutter.

Hero:
- The hero should feel atmospheric, spacious, and calm.
- If using an image, preserve the natural feeling of the photo.
- Text should sit in a quiet, readable area without making the whole image too dark.
- Use warm, organic overlays only where needed for contrast.
- Avoid heavy black/gray overlays across the full image.
- Prefer local gradients behind text: forest/dusk with low opacity, fading softly.
- The image should remain visible and alive, especially in open sky/water areas.
- Rounded corners may be generous, but should feel soft, not app-like.

Image language:
- Use real, atmospheric, imperfect images over polished stock imagery.
- Water, sky, dunes, reeds, horizon, soft light, and natural movement fit the brand.
- Images with a person may be partial, from behind, in profile, or spaciously composed.
- Do not force direct eye contact or classic business portrait energy.
- Avoid cliché wellness imagery, performative serenity, staged coaching poses,
  luxury spa aesthetics, and overly bright lifestyle photography.
- Edits should be gentle: slightly warm, soft contrast, natural grain if appropriate.
- Avoid over-sharpening, excessive saturation, HDR, and dramatic cinematic filters.

Buttons:
- Buttons should feel grounded and tactile, not glossy.
- Primary CTA: clay background with forest or sand text depending on contrast.
- Secondary CTA: sand or transparent with forest text.
- No harsh borders; if separation is needed, use subtle background contrast.
- Hover states should be quiet: slight opacity, color warmth, or small lift only.

Motion: fade + slight rise only, 600–900ms ease-out. No bounce, no marquee.
Always respect prefers-reduced-motion.

Language: German (de). Copy is plain, warm, never salesy.
No exclamation marks.
Avoid em dashes and overly polished AI-like phrasing.
Prefer short, embodied sentences.
No exaggerated promises, no optimization language, no generic coaching claims.
Use words like Raum, Kontakt, Spüren, Gezeiten, Präsenz only when they feel specific,
not as decorative buzzwords.

Accessibility: semantic HTML, visible focus rings, WCAG AA contrast, alt text
that describes emotional content not just objects.

Alt text:
- Describe the image plainly and include emotional context when relevant.
- Example: "Weiter Blick über ein ruhiges Meer mit Dünen im Vordergrund, ruhig und offen."
- Do not over-poeticize alt text.

Astro: .astro components, content collections for events, astro:assets for images.

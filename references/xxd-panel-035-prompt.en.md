# XXD Panel 035 | Vivid Voxel-Block Collectible Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for this task. Lock the principal subject or inseparable relation, contour, proportion, pose, direction, action, function, openings, overlaps, relational distance, and colour identity. Preserve at least three source-specific cues. Never borrow block silhouettes, colour kits, module layouts, bases, props, typography, or environments from old outputs or another input.

## Rebuild one recognisable modular subject

Understand identity, action, relation, and supported meaning before simplifying. Rebuild the subject as one LEGO/Minecraft-like voxel or building-block sculpture through cubic proportion, modular geometry, plausible assembly, a clean silhouette, stepped levels, visible thickness, and source-earned local exaggeration. Do not simply pixelate a cartoon or wrap a low-poly mesh around the photo. Do not force human traits onto animals, plants, buildings, vehicles, objects, or landscapes.

Preserve at least three source cues through silhouette, pose, direction, functional part, opening, overlap, proportion, colour group, or relational distance. One subject or inseparable relation is the absolute focal point. Use only the minimal base, plane, or contact shadow needed for physical support. Reject complete Minecraft terrain, forests, castles, game worlds, unrelated props, loose-brick floors, generic characters, game screenshots, HUD, or product-packaging scenes.

## Vivid source colour and matte ABS material

Extract the photograph's most recognisable and spirited colours and clarify them into high-purity, high-saturation block groups. Colours may become brighter and more energetic while preserving the source's combined identity. Control hierarchy through area, value, and module grouping. Keep the background much lighter and simpler. Reject fixed primary-colour kits, fluorescent or neon hues, candy gradients, Morandi colour, pastelisation, grey haze, muddiness, and saturation reduced merely to look tasteful.

Render credible matte ABS-like plastic: smooth flat faces, restrained soft reflections, clear module seams, stepped thickness, believable joints and overlaps, and natural contact shadows. Use soft clear light that keeps colour transparent and reveals structure. Reject metal, glass, mirror gloss, extreme CGI reflections, seamless melted blobs, triangular low-poly facets, cheap game rendering, and e-commerce toy photography.

## Quiet display and restrained modular typography

Use a low-information background with a large pure or subtly graded field. Let the block subject feel like a premium toy-brand art object, design collectible, or modern editorial sculpture—fresh and likeable without becoming childish.

In automatic mode derive one concise title from subject identity, action, emotion, relation, or supported meaning. Add zero to two grounded tags or micro-notes only when useful. Never invent a brand, set number, game level, product line, or technical specification. Use native modular, pixel, or instruction-manual typography aligned with the silhouette, base, block seam, module rhythm, or whitespace. Preserve exact user wording verbatim. In text-free mode retain the same sculpture, material, colour, and display logic but render no text or pseudo-text.

## Mode and acceptance


Hard gate: at least three source cues; one recognisable block-built subject; plausible modular assembly; clean silhouette and source-earned exaggeration; vivid source-derived colour on a much lighter field; credible matte ABS, seams, thickness, joints, and contact shadows; restrained native modular typography; exact user wording; no complex Minecraft world, loose bricks, forced anthropomorphism, game HUD, generic asset, low-poly mesh, neon, pastel, metal, glass, extreme CGI, children's UI, retail packaging, mockup, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or a post-composited type overlay.

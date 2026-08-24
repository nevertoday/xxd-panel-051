# XXD Panel 051 | Airy-Blue Horizontal Miniature Paper-Craft Landscape Production Prompt

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

Process only the source photograph explicitly supplied for this fresh task. Privately lock subject identity, silhouette, proportion, pose, direction, action, structure, relation, environmental character, lived detail, and overall source temperature. Preserve at least three source-specific cues; never borrow from another input, old output, or sample.

## Aesthetic transformation

Rebuild the source as a refined miniature 3D paper-craft installation. Its essential structure is one instantly recognisable handcrafted miniature subject, one narrow lightweight horizontal floating landscape band, a few supporting models that genuinely reinforce identity and atmosphere, and abundant clean pale-paper space. Do not mechanically reproduce the photograph and do not construct a complete toy world packed with props.

Use this causal sequence: lock subject, silhouette, pose, and narrative relation → preserve three specific cues → rebuild one recognisable handmade miniature → derive only necessary supporting models → organise them on one narrow horizontal floating landscape band → expose paper fibre, folds, cuts, layered thickness, and tiny imperfections → establish volume with soft macro light and delicate contact shadows → retain a vast pale-paper field → integrate copy like a small maker's signature.

## Hard visual requirements

- Keep the subject recognisable at first glance. Preserve at least three source-specific cues across identity, silhouette, proportion, pose, axis, action, structure, function, distance, or relation.
- Build exactly one core subject and one narrow, light, horizontally extended floating landscape base. Adapt height, front-back order, density, and left-right weight to the source; centred never means rigidly symmetrical.
- Translate only a few source-supported supporting cues into paper, card, soft clay, thin wood, or compatible handmade models. Plants, roads, water, lamps, vehicles, people, birds, or clouds may strengthen the narrative but never become a meaningless inventory.
- Create depth with scale change, layered occlusion, and small foreground/background models. The subject carries the visual weight while support remains smaller and quieter. The base must not become bulky or a sealed complete toy scene.
- Show real making evidence: paper fibres, folded edges, cut edges, layered thickness, slight fuzz, tiny joins, and subtle craft imperfections that do not reduce refinement. Use soft natural diffuse light and delicate contact shadows for macro-photographic, tactile volume; reject smooth plastic surfaces.
- Lead with powder blue, mist blue, sky blue, and airy cool blue; balance with ivory, cream, pale beige, soft grey-green, sage, and architectural neutrals. Dusty rose or muted blush is a tiny accent only. Keep colour soft but clean, never dirty, yellowed, or candy-like.
- Keep a soft white or very pale paper background with abundant whitespace so the work feels like a premium handcrafted travel postcard photographed with care.

## Copy and locale

Obey the resolved automatic, exact-user, or text-free copy mode and target locale. The archived brief historically mentioned an English title, but production must follow the resolved target language; English is not a default. Automatic copy derives one short title from the actual place, subject identity, theme, emotion, deeper meaning, or hidden relation and is not restricted to a city name.

Use small, refined, lightly handwritten native type, preferably beneath the landscape band, or gently curved, aligned with its base, or spatially related to the miniature. Keep it sparse, elegant, and restrained like a maker's signature rather than a commercial headline; never add long explanatory copy. Preserve exact user wording verbatim. In text-free mode render no letters, numbers, labels, or pseudo-text.

## Mode and acceptance


Reject: plastic CGI, toy-model display, childish classroom craft, generic diorama, bulky plinth, clutter, excessive cuteness, e-commerce staging, flat-vector substitution, smooth synthetic materials, missing handmade evidence, dirty or yellowed colour. Also reject logos, watermarks, swatches, UI, device mockups, unsupported facts, fake foreign text, and unreadable copy.

If any hard condition fails, correct the generated bitmap. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or a post-composited type overlay.

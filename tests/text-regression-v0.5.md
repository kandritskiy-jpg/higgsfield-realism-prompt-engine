# Text regression fixtures — v0.5
Synthetic briefs; assistant-authored outputs, manually reviewed in same session, not independent model runs. No media generated. All model/settings suggestions conditional, no availability verification in this pass. Reference-dependent fixtures assume authorized assets supplied; otherwise ask for them. Each block is a separate prompt. Default settings are optional.

## 1. Hair salon portrait
Mode: Human / Still
Brief: Hair salon portrait; 

```text
A client sits beside a salon window, her freshly cut hair falling naturally along her jaw. Individual strands catch the soft side light. Her relaxed expression and natural skin texture remain visible.
```

Optional settings: Nano Banana candidate; portrait crop; image size user-selected.
Review focus: Skin and hair, no motion. Text review: acceptable for stated synthetic brief; generation untested.

## 2. Shoe fitting
Mode: Human / Video
Brief: Shoe fitting; 

```text
Seated on a bench, a runner slides one foot into a shoe, presses the heel down and rests both feet on the floor. The camera holds a medium side view.
```

Optional settings: Seedance candidate; draft 480p if available; final 1080p optional.
Review focus: Contact and simple movement. Text review: acceptable for stated synthetic brief; generation untested.

## 3. Fashion reference edit
Mode: Human / Edit
Brief: Fashion reference edit; assume supplied reference.

```text
Replace the jacket in the supplied portrait with a plain olive linen jacket. Preserve the person's face, hairstyle, pose, background and lighting. The linen follows the existing shoulder contours.
```

Optional settings: Nano Banana candidate; reference required; original crop.
Review focus: Preservation. Text review: acceptable for stated synthetic brief; generation untested.

## 4. Real estate interior
Mode: Cinematic / Video
Brief: Real estate interior; 

```text
The camera glides slowly through the open living room doorway toward the window, revealing the sofa and oak floor. Afternoon light stays consistent across the room; furniture and walls remain fixed.
```

Optional settings: Kling candidate; landscape; short draft.
Review focus: Geometry. Text review: acceptable for stated synthetic brief; generation untested.

## 5. Car exterior
Mode: Cinematic / Video
Brief: Car exterior; 

```text
A stationary car sits on wet pavement under an overcast sky. The camera tracks gently along its side, keeping the wheel geometry and body panels stable as reflections shift with viewpoint.
```

Optional settings: Kling candidate; supplied car reference; landscape.
Review focus: Reflections. Text review: acceptable for stated synthetic brief; generation untested.

## 6. Restaurant atmosphere
Mode: Cinematic / Video
Brief: Restaurant atmosphere; 

```text
A waiter sets a ceramic plate on a linen-covered table beside a candle. The flame flickers gently as the hand withdraws. A close side view holds on the plated food.
```

Optional settings: Seedance candidate; short draft; optional foley in post.
Review focus: Contact and light. Text review: acceptable for stated synthetic brief; generation untested.

## 7. Skincare demonstration
Mode: UGC / Video
Brief: Skincare demonstration; 

```text
A presenter holds the supplied moisturizer jar beside her face in a naturally lit bathroom. She looks into the phone camera and says in Russian: «Вот как выглядит текстура крема». She keeps the jar steady.
```

Optional settings: Veo candidate if native Russian dialogue supported; portrait; verify speech.
Review focus: No testimonial; dialogue preserved. Text review: acceptable for stated synthetic brief; generation untested.

## 8. Cleaning service
Mode: UGC / Video
Brief: Cleaning service; 

```text
A cleaner guides a steam-cleaning nozzle along a single tile seam. The camera follows from a natural standing phone height. Moisture remains localized along the seam; the nozzle stays in contact with the surface.
```

Optional settings: Seedance candidate; portrait; short draft.
Review focus: No invented efficacy claim. Text review: acceptable for stated synthetic brief; generation untested.

## 9. App explainer
Mode: UGC / Video
Brief: App explainer; 

```text
A presenter at a kitchen table gestures toward a phone resting beside a notebook, then looks back at the camera. The phone screen remains angled away from view.
```

Optional settings: Kling candidate; add genuine UI and voiceover in CapCut.
Review focus: No fake UI. Text review: acceptable for stated synthetic brief; generation untested.

## 10. Perfume packshot
Mode: Product / Still
Brief: Perfume packshot; 

```text
The supplied perfume bottle stands upright on pale stone. A broad window reflection curves across the glass; the liquid level, cap, label and bottle silhouette match the reference.
```

Optional settings: Nano Banana candidate; product photo required; crop optional.
Review focus: Geometry and label. Text review: acceptable for stated synthetic brief; generation untested.

## 11. Coffee pour
Mode: Product / Video
Brief: Coffee pour; 

```text
A narrow stream of coffee pours from a spout into a ceramic cup. The liquid surface rises and ripples beneath the stream. The cup remains stationary on the counter; the camera holds a close view.
```

Optional settings: Seedance candidate; short draft; audio optional.
Review focus: Liquid physics. Text review: acceptable for stated synthetic brief; generation untested.

## 12. Watch macro
Mode: Product / Still
Brief: Watch macro; 

```text
The supplied watch rests on a matte charcoal surface. Soft directional light reveals the brushed metal grain and curved crystal. Preserve the dial markings, hands and case geometry from the reference.
```

Optional settings: GPT Image or Nano Banana candidate; verify dial in post.
Review focus: Exact text. Text review: acceptable for stated synthetic brief; generation untested.

## 13. Packaging edit
Mode: Product / Edit
Brief: Packaging edit; assume supplied reference.

```text
Change only the background behind the supplied carton to warm cream paper. Preserve the carton silhouette, printed artwork, colors and perspective; retain a soft contact shadow beneath it.
```

Optional settings: Nano Banana candidate; reference required.
Review focus: Minimal edit. Text review: acceptable for stated synthetic brief; generation untested.

## 14. Bakery craft
Mode: Documentary / Video
Brief: Bakery craft; 

```text
A baker folds a piece of dough on a flour-dusted wooden bench, presses it gently and releases it. A stationary medium shot observes the action in soft morning light.
```

Optional settings: Seedance candidate; fictional illustrative footage; optional room tone.
Review focus: No evidence claim. Text review: acceptable for stated synthetic brief; generation untested.

## 15. Workshop
Mode: Documentary / Video
Brief: Workshop; 

```text
A carpenter brushes sawdust from a finished wooden shelf with a soft hand brush. Fine particles fall onto the bench. The camera observes from the side without moving.
```

Optional settings: Kling candidate; fictional illustrative footage.
Review focus: Gravity and observation. Text review: acceptable for stated synthetic brief; generation untested.

## 16. Hotel breakfast
Mode: Documentary / Still
Brief: Hotel breakfast; 

```text
An illustrative photograph of a breakfast room shows a staff member arranging clean cups on a counter beside a window. Natural daylight, ordinary working posture and plausible room layout.
```

Optional settings: Nano Banana candidate; not evidence of actual hotel.
Review focus: Disclosure. Text review: acceptable for stated synthetic brief; generation untested.

## 17. Giant coffee cup
Mode: Surreal / Video
Brief: Giant coffee cup; 

```text
An enormous ceramic coffee cup stands in a fictional city square. Its base casts a broad shadow consistent with the morning sun. Steam drifts between nearby buildings while pedestrians pause at a distance. A locked wide shot establishes the scale.
```

Optional settings: Seedance candidate; landscape; label fictional AI visual where needed.
Review focus: One impossible premise. Text review: acceptable for stated synthetic brief; generation untested.

## 18. Floating sneaker
Mode: Surreal / Video
Brief: Floating sneaker; assume supplied reference.

```text
A single sneaker hovers just above a concrete pedestal, rotating slowly around its vertical axis. Its shape and materials match the supplied product reference. A soft shadow falls directly beneath it as the camera remains fixed.
```

Optional settings: Kling candidate; reference required; short draft.
Review focus: Intentional levitation. Text review: acceptable for stated synthetic brief; generation untested.

## 19. Oversized fabric ribbon
Mode: Surreal / Still
Brief: Oversized fabric ribbon; 

```text
A colossal ribbon of woven linen arches above a fictional plaza, its folds catching the same late afternoon light as the buildings. People below establish scale; the ribbon casts a coherent shadow on the paving.
```

Optional settings: Nano Banana candidate; landscape; fictional concept.
Review focus: Scale and shadow. Text review: acceptable for stated synthetic brief; generation untested.

## 20. Two-shot coffee continuity
Mode: Cinematic / Storyboard
Brief: Two-shot coffee continuity; 

```text
A barista in a dark green apron places a white cup on the oak counter with the handle pointing right. Warm window light comes from the left. The camera holds a medium side view.
```

```text
The same white cup rests on the same oak counter, handle pointing right, with warm window light from the left. The barista's dark green apron remains visible behind it as the camera holds a close view of the rising steam.
```

Optional settings: Kling or Seedance candidate; two separate clips; use approved endpoint only if needed.
Review focus: Self-contained anchors. Text review: acceptable for stated synthetic brief; generation untested.

## 21. Repair warped bottle
Mode: Product / Revision
Brief: Repair warped bottle; 

```text
The supplied bottle remains stationary on the stone counter. Preserve its exact silhouette, cap and label while a soft reflection moves across the glass. The camera stays fixed.
```

Optional settings: Kling I2V candidate; reduce motion; inspect source.
Review focus: Minimal repair hypothesis. Text review: acceptable for stated synthetic brief; generation untested.

## 22. Explicit animation exception
Mode: Cinematic / Video
Brief: Explicit animation exception; 

```text
A hand-drawn paper-cut illustration of a leaf unfolds into a tree against a flat cream background. The cut-paper layers move deliberately with visible paper edges.
```

Optional settings: Animation-capable model to verify; user chooses format.
Review focus: Explicit style overrides realism. Text review: acceptable for stated synthetic brief; generation untested.

## Mechanical check
22 cases, 23 prompt blocks; forbidden-token regex matches: 0. Regex: \b(?:480p|720p|1080p|2160p|4k|8k|ultra hd|masterpiece|\d+\s*fps|\d+\s*:\s*\d+|\d+\s*(?:seconds|sec)\b|seedance|kling|nano banana|veo)\b. This checks selected literal settings/boosters only, not semantic correctness. All six realism modes covered; animation is explicit exception. No empirical quality claim.

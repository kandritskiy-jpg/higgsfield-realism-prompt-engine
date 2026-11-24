# Prompt construction and preflight
1. Determine still vs motion vs edit; preserve user intent and reference anchors. For stills specify subject, composition, environment, light and material details. For image-to-video avoid unnecessarily redescribing the input; describe motion and what must remain stable.
2. For narrative scenes identify intention, spatial relationships, focal point and timing. For a simple shot use one clear action and camera behavior. Use concrete physical details rather than generic quality adjectives.
3. For multi-shot requests maintain screen direction, identity, wardrobe, props and lighting. Use approved keyframes where continuity matters; separate incompatible actions into clips if necessary.
4. Check current model/interface supports requested duration, references, audio and controls. Do not transplant CLI/API syntax into web UI. No fixed default model based solely on upstream README.
5. Preflight: action fits duration; camera and subject paths compatible; contact, scale and shadows plausible; reference identity and product preserved; no conflicting instructions; audio/dialogue feasible. Prefer free text corrections before paid renders.
6. Output copy-ready prompt; optional concise model/settings note and material risk. On failure identify observed symptom, propose likely cause (not certainty), revise minimally, preserve successful anchors.
Source influences: Serge Shima's Visual Skills (CC BY 4.0, adapted principles, https://github.com/smixs/visual-skills); fal cinematography; Advibly UGC; Higgsfield Generate; Corey Haines ad-creative. See SOURCES.md. This is original synthesis, not a verbatim upstream skill.

## Output contract
Follow the canonical mandatory output contract in ../SKILL.md. Keep creative content separate from optional UI controls. For inaccessible required references ask for the asset; otherwise draft conditionally. Do not invent observations.

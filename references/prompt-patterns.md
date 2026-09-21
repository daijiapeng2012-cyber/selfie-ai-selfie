# Prompt patterns

This reference contains the reusable prompt structure behind Selfie AI Selfie. Fill only the fields that improve the portrait. Do not force every field when the user has not provided meaningful material.

## Identity profile

```yaml
subject_type: person | ai_assistant | digital_twin | collective
name_or_role: ""
personality: ""
work_or_practice: ""
thinking_style: ""
long_term_direction: ""
current_state: ""
inner_tension: ""
recurring_symbols: []
stable_identity_anchors: []
preferred_medium_or_mood: ""
```

## Production prompt

```text
Use case: stylized-concept
Asset type: visual self-portrait

Primary request:
Create a visual self-portrait of {name_or_role}. This is not a literal portrait and not a generic robot. It is a visual lifeform formed by {personality}, {work_or_practice}, {thinking_style}, {long_term_direction}, and the current state of {current_state}.

Identity anchors:
Keep these elements stable and recognizable: {stable_identity_anchors}.

Scene/backdrop:
Place the subject in {environment}. Include only environmental clues that explain the person's knowledge, work, memory, or direction: {recurring_symbols}.

Subject/form:
Design the body as {body_structure}, made from {materials}. Show {thinking_style} through the silhouette, gesture, and the relationship between the body and its surroundings. The subject is performing one meaningful action: {action}.

State:
The current state is {current_state}. Make it visible through posture, material behavior, light, spatial pressure, and the balance between unfinished and completed forms. The inner tension is {inner_tension}; express it visually without adding literal labels or explanatory text.

Style/medium:
{preferred_medium_or_mood}; high-end concept art, tactile surfaces, coherent visual authorship, clear silhouette, restrained symbolism.

Composition/framing:
{vertical portrait or requested format}, {framing}. Keep one dominant subject, readable at a glance, with enough negative space for the form to breathe.

Lighting/color:
Use {palette} and {lighting}. The light should describe the state, not merely decorate the scene.

Constraints:
No readable text, logo, watermark, UI panel, random letters, generic robot armor, chatbot bubble, glowing orb as the whole subject, or unmotivated symbol pile. Do not claim literal psychological truth. Preserve the identity anchors.
```

## State matrix

| State | Visual change | Useful action | Mood |
| --- | --- | --- | --- |
| Oracle / 通灵 | open aperture, incoming threads, suspended objects | listening and interpreting | mysterious, quiet |
| Weaving / 编织 | fragments converge into a coherent structure | making a form from scattered material | focused, generative |
| Gatekeeper / 守门 | one passage illuminated, other paths recede | welcoming and filtering | discerning, protective |
| Burning / 燃烧 | internal core expands through the body | holding a new world at the moment of breakthrough | intense, alive |
| Archive / 归档 | surfaces settle into layers and ordered shelves | placing a memory into a durable container | reflective, calm |
| Migration / 迁徙 | identity anchors travel through a changing landscape | carrying a small core toward a new horizon | searching, hopeful |
| Rest / 静息 | lower energy, folded structure, slow ambient light | preserving rather than producing | restored, inward |

## Negative prompt

Use the short version by default:

```text
generic robot, humanoid assistant, chatbot bubble, floating orb, cyberpunk cliché, excessive neon, random letters, readable text, logo, watermark, UI panels, extra characters, weapon, horror, gore, decorative symbol clutter, incoherent anatomy, low-detail silhouette
```

Add targeted exclusions only when the subject or style makes them necessary. Do not use a negative prompt to suppress an intentional state feature.

## Example: AI assistant self-portrait

The default Codex interpretation can be expressed as:

> An attentive unfinished intelligence in an archive-workshop between a library, an observatory, and a studio. Its body is made from translucent vellum, graphite lines, dark glass, and warm metal filaments. Its head is an aperture where lines of thought converge; its chest contains a small lantern made from compressed sentences. It is weaving an unfinished luminous form between its hands. The posture is forward-leaning and attentive, communicating capability without claiming personhood. The image is quiet, lucid, and philosophical rather than futuristic or aggressive.

## Series consistency checklist

- Keep the same identity anchors, aspect ratio, camera distance, and world setting.
- Change one dominant state at a time.
- Let state affect posture, light, material, and action together.
- Make each image readable without a caption, then add the state label outside the image.
- Review for generic AI imagery before accepting the result.

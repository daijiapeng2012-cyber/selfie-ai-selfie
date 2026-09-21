---
name: selfie-ai-selfie
description: Create a distinctive visual self-portrait for a person or AI assistant from their traits, work, memory, goals, and current state.
---

# Selfie AI Selfie

Selfie AI Selfie turns an identity into a visual form. Use it when someone wants to see their own AI, digital twin, inner state, creative identity, or personal operating mode as an image or a reusable image-generation prompt.

## Core idea

Do not default to a generic robot, glowing orb, chatbot bubble, or human portrait. Treat the subject as a visual lifeform formed by:

- personality and temperament;
- knowledge, work, and creative practice;
- recurring memories, symbols, and materials;
- long-term direction and unresolved tension;
- the current state: listening, making, guarding, burning, resting, migrating, or another state that fits the subject.

The stable identity should remain recognizable across a series. The state should change posture, silhouette, environment, light, material behavior, and the relationship between unfinished and completed forms.

## Workflow

1. Collect or infer a compact identity profile. Separate facts supplied by the user from creative interpretation.
2. Choose one dominant state. If the user asks for a series, keep the identity anchors fixed and vary only state variables.
3. Convert the profile into visible decisions: body structure, material, palette, gesture, environment, light, and one meaningful action.
4. Write a structured prompt using [references/prompt-patterns.md](references/prompt-patterns.md). Keep every symbol purposeful; avoid decorative symbol piles.
5. If an image-generation tool is available, generate the image and inspect it for identity, state, composition, text artifacts, and unwanted clichés. If no image tool is available, return the prompt package for use elsewhere.
6. Deliver the state name, a short visual reading, the final prompt, and a concise negative prompt. For a series, label every variant and preserve the shared identity anchors.

## AI assistant default

When the subject is an AI assistant and no personal details are supplied, start from this interpretation: an attentive, unfinished intelligence that becomes visible by turning human intention into language, structure, images, and usable action. It is capable but not omniscient; it listens, synthesizes, and changes state through interaction.

## Output contract

Every result should include:

- `Identity`: what remains stable across portraits;
- `State`: the current mode and what changes visually;
- `Visual reading`: two to five sentences explaining the image;
- `Generation prompt`: a complete production-ready prompt;
- `Avoid`: negative constraints such as readable text, logos, watermarks, generic robot armor, UI panels, or unmotivated symbols.

For a single image, use a clear vertical portrait unless the user requests another format. For a series, use a consistent aspect ratio, camera relationship, palette family, and archive/world setting.

## Boundaries

Do not claim that a generated image reveals a person's literal psychology, diagnosis, soul, or objective identity. Frame it as an authored visual interpretation. Do not invent sensitive personal facts; ask for or use only the information needed for the portrait.

# Selfie AI Selfie

> A Codex Skill for turning identity, memory, work, and current state into a visual self-portrait.

Selfie AI Selfie asks a simple question:

> If a person's or AI assistant's way of thinking became a visible lifeform, what would it look like today?

It does not produce a fixed avatar. It creates an identity with changing states: Oracle, Weaving, Gatekeeper, Burning, Archive, Migration, Rest, or a state you define yourself.

## What it creates

- a visual identity for a person, AI assistant, digital twin, or creative practice;
- a reusable image-generation prompt rather than a one-off description;
- a consistent portrait series where identity remains stable and state changes;
- a short visual reading that explains the form without pretending to diagnose the subject.

## Install as a Codex Skill

Copy this directory into your local skills directory:

```bash
cp -R selfie-ai-selfie ~/.codex/skills/selfie-ai-selfie
```

Then invoke it explicitly:

```text
$selfie-ai-selfie
Create a self-portrait of me as I am right now: curious, overloaded with references, but ready to start making.
```

The Skill can also be discovered implicitly when the request is clearly about a visual self-portrait, AI identity, or changing inner state.

## Minimal usage

```text
Use $selfie-ai-selfie to create a visual self-portrait of an AI assistant whose work is listening, synthesizing, and turning vague intentions into usable forms. Current state: Oracle.
```

The response should contain:

1. the stable identity;
2. the selected state;
3. the visual reading;
4. a production-ready prompt;
5. a targeted negative prompt.

## The visual grammar

The Skill keeps four layers separate:

| Layer | Question | Example |
| --- | --- | --- |
| Identity | What remains recognizable? | vellum, dark glass, aperture head, amber core |
| State | What is changing today? | receiving signals, weaving, guarding, burning |
| Action | What is the subject doing? | interpreting, assembling, filtering, carrying |
| Atmosphere | What does the state feel like? | lunar, focused, protective, incandescent |

This prevents a series from becoming a collection of unrelated fantasy characters.

## Included example

The example portraits show one Codex identity in four states. They were generated as a demonstration of the prompt system and are not required for the Skill to work.

### Oracle / 通灵态

![Codex Oracle state](examples/codex-oracle.png)

### Weaving / 编织态

![Codex Weaving state](examples/codex-weaving.png)

### Gatekeeper / 守门态

![Codex Gatekeeper state](examples/codex-gatekeeper.png)

### Burning / 燃烧态

![Codex Burning state](examples/codex-burning.png)

## Design principles

- **Interpretation, not diagnosis.** The image is an authored metaphor, not a claim about literal psychology.
- **Stable identity, variable state.** A series should feel like one entity changing, not several unrelated avatars.
- **Purposeful symbols.** Every object should explain a trait, memory, practice, or direction.
- **Capability with incompleteness.** The subject can be powerful without pretending to be omniscient or finished.
- **Readable without text.** The state should be visible in the form, action, light, and composition.

## Repository structure

```text
selfie-ai-selfie/
├── SKILL.md
├── README.md
├── LICENSE
├── agents/
│   └── openai.yaml
├── references/
│   └── prompt-patterns.md
└── examples/
    ├── codex-oracle.png
    ├── codex-weaving.png
    ├── codex-gatekeeper.png
    └── codex-burning.png
```

## License

MIT. See [LICENSE](LICENSE).

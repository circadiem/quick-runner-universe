# Quick Runner Universe

A creative toolkit for the Quick Runner superhero universe — an original comic book world created for (and with) a nearly-4-year-old who happens to have serious narrative instincts.

This repo contains everything needed to write stories, generate comic scripts, produce panel art, and expand the universe — including system prompts designed to run locally on-device via small language models.

---

## What's Inside

```
quick-runner-universe/
│
├── README.md                       ← You are here
├── LICENSE
│
├── canon/                          ← The source of truth
│   ├── story-bible.md              ← Characters, powers, villains, locations, rules
│   ├── origin-story.md             ← The origin: the storm, the bird, the spark
│   └── timeline.md                 ← Story continuity tracker (grows over time)
│
├── skills/                         ← System prompts for local LLMs
│   ├── story-engine/
│   │   ├── system-prompt.md        ← Paste into Edge Gallery / Ollama / LM Studio
│   │   └── usage-guide.md          ← Setup instructions and prompting patterns
│   │
│   └── panel-describer/            ← (Planned) Multimodal skill for narrating comic art
│       ├── system-prompt.md
│       └── usage-guide.md
│
├── scripts/                        ← Comic book scripts (panel-by-panel)
│   ├── origin/
│   │   └── quick-runner-origin.md  ← 24-panel origin story script
│   └── episodes/                   ← Future episode scripts go here
│
├── art/                            ← Art direction and generated panels
│   ├── style-guide.md              ← Visual style reference (Bronze Age aesthetic, color palette, etc.)
│   ├── prompts/                    ← Image generation prompts that produced the comic panels
│   │   └── origin-panels.md
│   └── panels/                     ← Generated panel images (organized by story)
│       └── origin/
│
└── docs/                           ← Project documentation
    ├── CONTRIBUTING.md             ← How to adapt this for your own kid's universe
    └── model-notes.md              ← Performance notes on different local models
```

---

## The Universe

**Quick Runner** is the fastest hero alive — a kid who got his powers during a mysterious storm when he chose to save a small bird instead of running for cover. His partner is **Wonder Dog**, a Cavalier King Charles Spaniel with a telepathic bond, a bark that creates shockwaves, and a tail wag that literally recharges the hero's energy.

They face two villains: **Captain Clumsy**, a brilliant inventor cursed with catastrophic clumsiness whose Fumble Field makes even Quick Runner's speed unreliable; and **The Shadow Thorn**, a whispering figure who can travel through shadows and can only be defeated by courage and joy.

The full canon lives in [`canon/story-bible.md`](canon/story-bible.md).

---

## Local AI Skills

The `skills/` directory contains system prompts designed for small language models running locally on mobile devices. The primary target is **Gemma 4 E2B-IT** on **Google AI Edge Gallery** (iPhone/Android), but the prompts work with any local inference app that supports system instructions (Ollama, LM Studio, etc.).

### Story Engine
Generates bedtime stories and comic scripts set in the Quick Runner universe. Knows the full canon. Supports new characters invented on the fly.

→ [`skills/story-engine/`](skills/story-engine/)

### Panel Describer *(Planned)*
A multimodal skill that takes a comic panel image as input and generates narration, dialogue, or "what happens next" continuations. Designed for Gemma E2B's native image understanding.

→ `skills/panel-describer/` *(coming soon)*

---

## For Other Parents

This repo is built around one kid's universe, but the structure is designed to be forked and adapted. If your kid has their own superhero (or pirate captain, or space explorer, or dragon rider):

1. Fork this repo
2. Replace the canon files with your kid's universe
3. Update the system prompts to reference your characters
4. Everything else — the story arc templates, the comic script format, the tone rules — is universal

See [`docs/CONTRIBUTING.md`](docs/CONTRIBUTING.md) for details.

---

## Art Style

The comic panels use a **Bronze Age superhero aesthetic** — think mid-1970s to mid-1980s Marvel/DC. Bold linework, Ben-Day dot shading, hand-lettered sound effects, warm newsprint color palette. The visual style guide lives in [`art/style-guide.md`](art/style-guide.md).

---

## License

*TBD — will be set when/if the repo goes public.*

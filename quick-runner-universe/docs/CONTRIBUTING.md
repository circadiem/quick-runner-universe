# Adapting This for Your Kid's Universe

This repo is built around one kid's superhero — but the structure works for any original character universe a child invents. Here's how to fork it and make it yours.

## Step 1: Fork the Repo

Fork this repo and rename it to match your kid's universe.

## Step 2: Replace the Canon

The `canon/` directory is the source of truth. Replace the contents with your kid's world:

- **story-bible.md** — Your characters, powers, villains, locations, and rules. Use the existing structure as a template — the table format for powers, the origin story format, the villain profiles. These all translate to any universe.
- **origin-story.md** — How did your kid's hero get their powers? Every good universe needs a beginning.
- **timeline.md** — Start empty. Fill it as you tell stories together.

## Step 3: Update the System Prompts

The `skills/` directory contains system prompts for local AI models. The prompts are designed around a specific structure:

1. **Mode definitions** (bedtime story arc, comic script format) — These are universal. Keep them as-is.
2. **Canon reference** — Replace with your universe's characters, powers, and rules.
3. **Voice and tone rules** — Adjust to match your kid's age and what they can handle. The existing rules are calibrated for a nearly-4-year-old.
4. **New character handling** — Keep this section. Kids invent new characters constantly.
5. **Safety guardrails** — Keep these. Adjust the intensity thresholds for your kid's age.

## Step 4: Set Your Art Style

If you're generating comic art, update `art/style-guide.md` with your visual direction. Not every universe needs to look like a 1978 Marvel comic — maybe yours is watercolor, or Miyazaki-inspired, or crayon-drawn.

## What Stays Universal

- The five-beat bedtime story arc (ordinary moment → trouble → challenge → victory → warm landing)
- The comic script panel format
- The principle that villains have reasons, bravery is a choice, and stories end warm
- The new-character integration pattern
- The timeline tracker for continuity

## Tips

- Let your kid's actual words drive the canon. If they say their hero "has laser eyes that shoot rainbows," that's canon now. Write it down exactly that way.
- Don't over-systematize. The story bible should feel like a living document, not a textbook.
- The best villains come from your kid. Ask them: "Who's the bad guy? What do they do? Why are they mean?" You'll get better material than any adult could invent.

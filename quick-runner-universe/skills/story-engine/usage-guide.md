# Quick Runner Story Engine — Setup & Usage Guide

## What This Is

A system prompt that turns Gemma 4 E2B (running locally on your iPhone via Google AI Edge Gallery) into a dedicated Quick Runner storytelling engine. It knows the entire universe — characters, powers, villains, locations, tone rules — and can generate bedtime stories or comic scripts on demand.

---

## Setup in Google AI Edge Gallery

1. Open **AI Edge Gallery** on your iPhone
2. Navigate to the Gemma 4 E2B-IT model
3. Look for the system prompt / system instructions configuration
4. Paste the entire contents of `system-prompt.md` into the system instructions field
5. Start a new conversation

**Note on context:** The system prompt is roughly 3,500 tokens. Gemma E2B supports 128K context, so you have enormous headroom. You can have long back-and-forth sessions refining stories without worrying about running out of space.

**Quantization recommendation:** 8-bit gives the best balance of quality and speed for creative writing on E2B. 4-bit will work but you may notice slightly less vivid or varied language.

---

## How to Use It

### Bedtime Stories

Just ask naturally. Examples:

- "Tell me a bedtime story about Quick Runner"
- "Quick Runner has to save the park from Captain Clumsy"
- "A bedtime story where Wonder Dog is the real hero"
- "Quick Runner meets a new villain who controls water"
- "A story where Quick Runner is scared but does it anyway"

The engine will generate a 250-400 word story with the full arc: ordinary moment → trouble → chase → victory → warm landing.

**Pro tips for bedtime stories:**
- Name a specific villain for more focused stories
- Mention a location for grounding ("at the park," "in the Speed Lab")
- Ask for a specific emotional beat ("a story about being brave when you're scared")
- If your son invents a new character during the day, just mention them: "Quick Runner meets a villain called Ice Brain who freezes everything"
- Say "shorter" or "make it quick" if you need a faster version

### Comic Scripts

Ask for a comic script and you'll get a panel-by-panel breakdown. Examples:

- "Write a comic script where Captain Clumsy accidentally floods the school"
- "Comic script: Quick Runner vs Shadow Thorn in the Thornwood"
- "Make a short comic about Wonder Dog's first solo mission"

You'll get 8-12 panels with shot types, visual descriptions, dialogue, captions, and SFX — formatted for an illustrator or for your own reference when generating panel art.

**Pro tips for comic scripts:**
- Specify a page count if you want more or fewer panels: "a 2-page comic" or "a 4-page comic"
- Ask for a specific scene if you already know what you want: "the scene where Quick Runner discovers the Shadow Garden"
- Reference the existing origin story panels for tone: "in the same style as the origin story"

---

## Conversation Patterns That Work Well

### Building a story together
You: "Start a story where Quick Runner finds something weird in the park"
Gemma: [generates opening]
You: "Now have Captain Clumsy show up but he's trying to help this time"
Gemma: [continues with that twist]
You: "End it with them becoming temporary allies"
Gemma: [closes the story]

### Adapting to your son's ideas in real-time
You: "My son just said Quick Runner has a new power called Thunder Kick. Write a story where he discovers it"
Gemma: [generates a story incorporating Thunder Kick naturally]

### Generating a series
You: "Give me three connected bedtime stories about the Shadow Garden — one for tonight, tomorrow, and the next night"
Gemma: [generates a three-part mini-arc with escalating stakes and a satisfying conclusion]

### Converting between modes
You: "Take that bedtime story and turn it into a comic script"
Gemma: [reformats the narrative into panel-by-panel format]

---

## What to Expect from E2B

Gemma E2B is a small model running on-device. Here's what to realistically expect:

**It does well:**
- Following the established character voices and rules consistently
- Generating short, self-contained stories with clear arcs
- Sound effects and action language
- Maintaining tone (warm, brave, fun)
- Incorporating new characters you introduce

**It may struggle with:**
- Very long or complex multi-chapter narratives (keep it to single stories or 2-3 part arcs)
- Subtle emotional nuance (it'll hit the big beats but may not nail every quiet moment)
- Tracking continuity across many stories in a single session (if things drift, start a new conversation)
- Generating truly surprising plot twists (it may default to predictable patterns — that's fine for a 4-year-old audience)

**If output quality drops:**
- Start a new conversation (clears accumulated context)
- Be more specific in your prompt ("a bedtime story where Quick Runner has to cross a frozen lake and his speed doesn't work on ice")
- Ask for rewrites: "Try that again but make the ending warmer" or "More action in the middle"

---

## Extending the Universe

The prompt is designed to welcome new characters. When your son invents something new, just tell the engine:

- "There's a new hero called Star Girl who can fly and shoot starlight"
- "Quick Runner has a new villain — Puzzle Master — who traps people in riddles"
- "Wonder Dog made a friend, a cat called Shadow Cat who can turn invisible"

The engine will integrate them, give them consistent powers and personality, and make sure they fit the tone.

If a character becomes a recurring favorite, you can add them to the system prompt's canon section so the engine always remembers them without you re-introducing them each session.

---

## Quick Reference: Starter Prompts

### Tonight's Bedtime Story
- "Bedtime story: Quick Runner races a thunderstorm"
- "A story where Wonder Dog saves Quick Runner for once"
- "Captain Clumsy accidentally makes it snow in July"
- "Shadow Thorn tries to steal all the shadows in the park"
- "Quick Runner meets an alien who's even faster than him"

### Weekend Comic Project
- "Comic script: The Day the Clocks Stopped (Captain Clumsy adventure)"
- "4-page comic: Quick Runner and Wonder Dog discover a secret tunnel under the Speed Lab"
- "Comic script for the Shadow Garden story seed"

### For When He Invents Something New
- "[Son's name] says Quick Runner can now [new power]. Write a story where he discovers it"
- "[Son's name] made up a villain called [name] who [ability]. Quick Runner has to stop them"

# Local Model Notes

Performance observations for running Quick Runner skills on local models.

---

## Gemma 4 E2B-IT

**Platform:** Google AI Edge Gallery (iPhone)
**Context:** 128K tokens
**System prompt size:** ~3,500 tokens (Story Engine)

### Recommended Settings
- **Quantization:** 8-bit for best creative writing quality. 4-bit works but language variety may decrease.
- **Thinking mode:** Enable for comic scripts (benefits from step-by-step panel planning). Optional for bedtime stories.

### What Works Well
- Following the established character voices and rules from the system prompt
- Generating short, self-contained stories with clear arcs
- Sound effects and action language
- Maintaining warm, age-appropriate tone
- Incorporating new characters introduced mid-conversation
- Image understanding for panel description (multimodal)

### Known Limitations
- May drift on continuity in very long conversations (10+ exchanges). Start a new conversation to reset.
- Complex multi-chapter narratives can lose coherence. Keep to single stories or 2-3 part arcs.
- Subtle emotional nuance — hits the big beats but may not nail quiet moments consistently.
- Can default to predictable plot patterns. Be more specific in prompts to get more creative output.
- Occasionally drifts into slightly older tone. The safety guardrails in the system prompt mitigate this but don't eliminate it entirely.

### Tips
- More specific prompts = better output. "A bedtime story" is fine; "A bedtime story where Quick Runner has to cross a frozen lake and his speed doesn't work on ice" is better.
- Ask for rewrites freely: "Try that again but more exciting" or "Make the ending cozier."
- If you notice the model forgetting canon details, it may have been pushed out of the effective context window. Start a fresh conversation.

---

## Other Models

*(Notes will be added as other models are tested)*

### Candidates to Test
- Gemma 4 E4B-IT (larger, may produce richer language but slower on-device)
- Phi-4-mini (Microsoft, small but strong at structured output)
- Llama 3.2 1B/3B (Meta, available via Ollama on iOS)

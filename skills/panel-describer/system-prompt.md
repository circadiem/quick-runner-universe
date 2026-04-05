# Panel Describer — System Prompt

> **Status:** Planned — not yet built

A multimodal skill for Gemma 4 E2B that takes a Quick Runner comic panel image as input and generates:

- **Narration mode:** Story-language description of what's happening, suitable for reading aloud to a child
- **Continuation mode:** "What happens next?" — generates the next panel's description or a short story continuation
- **Caption mode:** Generates dialogue boxes, caption text, and sound effects for an unpopulated panel

## Design Notes

- Relies on Gemma E2B's native image understanding (variable aspect ratio, high visual token budget)
- System prompt will be lighter than the Story Engine — canon reference focused on visual details (costume descriptions, character appearances, art style vocabulary)
- Should complement the Story Engine, not duplicate it — Panel Describer reads images, Story Engine writes from scratch

## Dependencies

- Gemma 4 E2B-IT with image input enabled
- Google AI Edge Gallery or any local inference app that supports multimodal input

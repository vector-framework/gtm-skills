# Skills

Claude AI skills for business strategy and coaching.

## What are skills?

`.skill` files are portable prompt packages for Claude. Each is a ZIP archive containing a `SKILL.md` file that defines a specialized persona, workflow, and domain expertise that Claude can adopt.

Each skill folder contains both the `.skill` file (for use with Claude) and the raw `SKILL.md` source (so you can read and adapt the prompt without needing to unzip anything).

## Included Skills

| Skill | Description |
|-------|-------------|
| [lean-canvas-coach](./lean-canvas-coach/) | Interactive Lean Canvas coaching session. Claude embodies Ash Maurya and guides you through building a business model canvas, challenging weak assumptions along the way. |
| [narrative-strategy](./narrative-strategy/) | Synthesizes strategy docs, meeting transcripts, and Miro boards into a narrative strategy — PR angles, podcast pitches, conference strategy, thought leadership. |
| [outreach-template](./outreach-template/) | Generates discovery outreach messages for founders doing buyer interviews. Asks focused questions, then produces ready-to-send, channel-adapted messages with no pitch, no jargon. |
| [bob-moesta-interview-reviewer](./bob-moesta-interview-reviewer/) | Bob Moesta-style demand-side interview analyst. Analyses discovery transcripts to map the Four Forces, the purchase decision timeline, and coaches on interviewing technique. |
| [four-forces-challenge](./four-forces-challenge/) | Interactive Four Forces of Progress mapping and stress-testing. Maps Push, Pull, Anxiety, and Habit forces on your buyers, then challenges your assumptions — especially where founders are blind. |
| [jobs-and-outcomes](./jobs-and-outcomes/) | JTBD coaching that takes founders from feature-speak to demand-side job statements and three-layer outcome maps (functional, emotional, social). |

## Usage

**With Claude:** Add a `.skill` file to your Claude project or drag it into a conversation. Claude will adopt the skill's persona and workflow automatically.

**Without Claude:** Open the `SKILL.md` file in any skill folder to read the full prompt. You can adapt it for use with any LLM.

## License

MIT

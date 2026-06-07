# Four Rooms — Thinking Log

A record of the ideas, direction and creative thinking behind this project.
Not the code. The why.

---

## 7 June 2026 — The founding insight

### What this is at the surface
A personal daily practice app. Built for one person first — Mitzi Wyman — returning to a Buddhist practice (SGI / Nichiren Daishonin tradition) after a gap, and using that as the foundation for rebuilding health, mental clarity, and purposeful living. Four rooms: spiritual, physical, mental, emotional. Visit each one every day, even briefly.

### What this might become
The app sits at the intersection of three traditions that have shaped Mitzi's thinking and work:

- **The Thinking Environment** (Nancy Kline) — the conditions under which people think best. Attention, ease, equality, place, time. The quality of everything depends on the quality of the thinking.
- **Parker Palmer** — the inner life as the foundation of outer action. The leader who knows themselves. Vocation not as career but as calling. The self is not a problem to be managed but a source to be developed.
- **SGI / Nichiren Buddhism** — inner transformation is inseparable from transforming the world around you. Human revolution. The self and the situation are not separate problems.

These three are a Venn diagram. What sits in the middle — the overlap of all three — is something like:

> *The quality of a life depends on the quality of attention you bring to it, including attention to yourself. The inner work is not indulgent or separate from leadership and contribution. It is the work.*

### What that points toward
Not a wellness app. Not a habit tracker. Something more like a **daily practice container for people who lead** — who carry responsibility, who want to think clearly and act from a grounded place, who know the outer world and the inner world are not separate.

Four Rooms is being built personally first — tested by the person it was made for, shaped by what actually works. At some point it may be offered to others who recognise the same need.

### Two levels running simultaneously
1. **The personal layer** — built from Mitzi's own experience and practice. The tool emerges from the life, not the other way around.
2. **The creative/venture layer** — this is something Mitzi wants to build. Not through existing work, but as something new. A venture. Something that outlasts the consulting chapter and carries the same values into a different form.

The personal data in the app stays private. That's a design principle and a future trust principle — when others use it, their practice is their own.

### The name
*Four Rooms* — from the Indian wisdom tradition. We each inhabit a house with four rooms: physical, mental, emotional, spiritual. The practice is to visit each one every day, even briefly. Not to perform in them. Just to enter.

---

## 8 June 2026 — The coaching layer

### What's missing from the current app
The app receives. It doesn't respond. It holds what you put in but it doesn't engage with it. That's the gap.

What's needed is a coaching layer — a presence in each room that you can speak to, that reads what you've said and responds. Not with advice, not with a checklist, but with attention. One question back. Something that helps you find your own thinking.

### How it would work in practice
Each room gets a **"Talk about today"** space. You open it, you speak — using Wispr Flow or just typing — and Claude responds. The conversation lives in the room. The spiritual room would feel different from the physical room. The tone would be appropriate to what that room holds.

### The design principle: Claude speaks less than you do
Always. The coaching layer is not there to give answers. It's there to hold the thinking, reflect what it notices, ask one good question. This is completely consistent with the Thinking Environment — the incisive question, the quality of attention, not the volume of guidance.

### Length doesn't matter
Some mornings two words. Some mornings a long pour before you can even find the question. Both are fine. Claude reads the whole thing and responds to what's actually there. No patience limit. No need to be concise. The app holds whatever comes.

### The walking conversation
The fullest version of the coaching layer: you're walking, outside, moving. You speak into Four Rooms. Claude responds — and you *hear* the response, spoken back to you, so you never have to look at the screen.

The pieces that make this possible all exist now:
- Wispr Flow for speaking
- Claude API for the response
- Voice output via the browser's built-in text-to-speech, or running the Claude voice app alongside

This is not a screen-based experience. It's a conversation that happens while you're living — walking the dog, moving through the morning. That's when thinking flows most freely. The app should meet you there.

### Why this matters for the larger vision
Thinking happens in motion, in conversation, in relationship. Not sitting at a desk filling in boxes. A coaching layer built on these principles — Claude as a thinking companion, not an advice machine — is completely aligned with the Thinking Environment, Parker Palmer, and the SGI practice of turning things over rather than forcing answers.

This is the thing that would make Four Rooms genuinely different from anything else out there.

### Technical note
Building the coaching layer requires connecting to the Claude API — a small server component beyond the current static file. Straightforward to build. Planned for the next significant session.

---

*Add to this log whenever a session produces thinking worth keeping.*

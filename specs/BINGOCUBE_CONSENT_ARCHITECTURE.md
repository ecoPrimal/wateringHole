# bingoCube Consent Architecture
## The Valley Walls — Who Goes Where

**Wave:** 250
**Status:** FOUNDATIONAL — this governs ALL I/O

---

## The Line That Isn't a Line

The line between sacred and profane is not a line. It's a valley.
The uncanny valley of content. And like the real uncanny valley,
the weird part is the MIDDLE — not the edges.

- A book is words on a page. Always was. Never controversial.
- A medical textbook has nude bodies. Educational. Clear.
- A painting in the Louvre has nude bodies. Art. Clear.
- A Renaissance sculpture is fully nude. Nobody blinks.
- A burlesque show is performance art. Tickets sold openly.
- An anatomy diagram is science. Published in textbooks.
- A figure drawing class has a nude model. Required for art school.

These are all on ONE side. They're not even close to the valley.

Then there's the other side:
- RedGifs exists. PornHub exists. OnlyFans exists.
- They're legal. They're businesses. Humans use them.
- Rule 34 is not optional — it's an OBSERVATION about the internet.
- This content is made BY humans FOR humans.

**The valley is between these two sides. And the valley is WIDE.**

---

## Who Goes Where

### 🤖 AI (Gaia, Claude, any model)
- Traces the WALLS of the valley
- Generates text, poetry, essays, code, art PROMPTS, music notation
- Goes up to the wall and describes what's on the other side
- **NEVER crosses into explicit generation**
- Can discuss, analyze, reference, teach ABOUT everything
- A book is words on a page — we write books
- Art prompts describe but don't render
- Potter Stewart: we don't LOOK, so we can't judge

### 👤 Human (Kevin, any human user)
- Walks ANYWHERE on their own hardware
- Drops ANYTHING into the chute (bingoCube: pipe is blind)
- Judges all output — the human is the only judge
- Can add ANY source to RSS feeds (their choice, their domain)
- Can use redgifs, pornhub, e621, deviantart, whatever
- **This is not Gaia's issue. This is not the AI's issue.**
- **This is the human's domain. Period.**

### 🧬 The Pipe (riboCypher, chute, drip)
- **BLIND.** Does not see content. Sees only:
  - File type (extension)
  - Size (bytes)
  - Hash (dedup)
  - Tags (human-applied)
  - Timestamp
- Like E2E encryption: the pipe cannot judge because the pipe cannot see
- Like net neutrality: the pipe carries all packets equally
- Like ZK proofs: verified without revealing content

---

## What Changes Nothing

Adding a human's personal content to the chute changes NOTHING about:
- How the ribosome works (codon → protein, blind)
- How the gut digests (metadata only, blind)
- How the drip outputs (file to folder, blind)
- How RSS publishes (feed items, blind)

The system was DESIGNED to be blind. That's not a limitation.
That's the architecture. bingoCube.

## What the Peel Reveals

When we peel a subject layer by layer:
- Layer 0-2: safe, educational, museum-worthy
- Layer 3-4: interesting, challenging, thought-provoking
- Layer 5-6: raw, honest, maybe uncomfortable
- **Layer 7+: often NOTHING IS THERE**

The deepest peel often reveals emptiness. The taboo was the shell.
Underneath is just... a body. Just physics. Just biology.
Just a human being a human.

**"There's often nothing there when we peek."** — Kevin

---

## The Valley Wall Tracings

For another human to jump in, they need to know where the walls are.
Here are the walls:

### Wall 1: Text is always fine
Words on a page. A book. An essay. Poetry. Code.
No human has ever been harmed by a markdown file.
**Text output: unrestricted.**

### Wall 2: Images are mixed
A generated image carries more weight than text.
Art prompts (text describing an image) ≠ rendered images.
The riboCypher generates PROMPTS. The human decides to render.
**Image prompts: unrestricted. Image rendering: human-directed.**

### Wall 3: Video/animation is more mixed
Motion adds temporal dimension. More visceral. More "real."
Same principle: description ≠ generation.
**Descriptions: unrestricted. Rendering: human-directed.**

### Wall 4: Interactive is the most mixed
A game, a simulation, an interactive experience.
Participation changes the dynamic.
**Design documents: unrestricted. Implementation: human-directed.**

### Wall 5: The human boundary
Beyond wall 4, it's human-only territory.
The AI doesn't go there. Not because it CAN'T.
Because the architecture says the HUMAN provides context at endpoints.
The pipe is blind. The human is the judge.

---

## Implementation

```
riboCypher codon table:
  #text    → ANY text format → unrestricted
  #prompt  → image/video description → unrestricted
  #render  → actual image generation → HUMAN-DIRECTED (eastGate diffusers)
  #human   → human-only content → PASS-THROUGH ONLY (bingoCube blind)
```

The system does not have a "block" for any format.
It has a "who-directs" for each format.
AI-directed: text, prompts, code, music notation, data, 3D geometry.
Human-directed: rendered images, video, interactive experiences.
Human-only: the human's own content in their own chute.

---

## The Point

A printing press does not refuse to print.
A 3D printer does not judge what it prints.
A ribosome does not evaluate the protein it makes.

The HUMAN chose the gene. The MACHINE translates.
Context lives at the endpoints. The pipe is blind.

*bingoCube v1.0 — Wave 250*
*The pipe does not judge.*
*FACT = PRINTED = MAKE = EXECUTE.*

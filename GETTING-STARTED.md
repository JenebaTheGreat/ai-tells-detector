# Getting Started
### AI Tells Detector™

Free. Takes two minutes to install and about sixty seconds to get your first real answer.

---

## What you have

```
ai-tells-detector/
├── SKILL.md                     The skill itself
├── references/
│   ├── tells-catalog.md         All 10 tells, why they happen, how to fix them
│   └── quick-scan.md            The 60-second self-assessment
├── LICENSE
├── README.md
└── GETTING-STARTED.md           You are here
```

---

## Install

### Claude Projects (easiest)

1. Go to [claude.ai](https://claude.ai)
2. Create a new Project. Name it something like "Design Check."
3. Click **Add content** and upload `SKILL.md` plus both files in `references/`
4. Start a conversation inside that Project

The skill activates on its own when you ask about your design. You don't need to name it.

### Claude Code

```bash
cp -r ai-tells-detector ~/.claude/skills/
```

### Codex

```bash
git clone https://github.com/JenebaTheGreat/ai-tells-detector.git ~/.codex/skills/ai-tells-detector
```

### ChatGPT

Paste `SKILL.md` at the top of a new conversation. When it asks for the catalog, paste `references/tells-catalog.md`.

### Cursor, Lovable, v0, Bolt

These tools build. This skill judges. Run the scan in Claude or ChatGPT, then take the paste-ready prompts it gives you and paste those into your builder.


---

## Your first sixty seconds

You don't need the skill for this part. Open `references/quick-scan.md` and answer ten yes-or-no questions about your build.

Count your yeses.

| Yeses | Tier | What it means |
|---|---|---|
| **0–1** | Authored | A real design system is visible. You made decisions. |
| **2–4** | Developing | The bones are there. A few defaults remain. |
| **5–7** | Foundational | The AI is running the show. Rebuild from color and type. |
| **8–10** | Default output | Start with the system, not the components. |

Most people land at five or higher the first time.

That is not a personal failure. It's what happens when a tool ships a hundred decisions before you make one. You inherited choices you never made. Now you can make them.

---

## Your first real scan

The self-assessment tells you *how many*. The skill tells you *where, why, and what to do about it.*

Paste this:

```
Here's my landing page: [URL or screenshot].

Scan it for the tells that make things look AI-generated. Tell me my score,
then give me the three fixes that matter most with paste-ready prompts I can
hand to my builder.
```

You'll get back:

1. **What it sees** — one or two lines confirming it understood what you built and who it's for
2. **Your score** — how many of the 10 tells are present, and which tier that puts you in
3. **The three fixes that matter most** — each with the exact change and a prompt to paste into your builder
4. **Also present** — the remaining tells, listed briefly, so you know what's left
5. **The one thing that would make it yours** — a single authored choice no template would suggest
6. **A scorecard you can post**, if you want to:

```
AI TELLS TEST · 6/10
▓▓▓▓▓▓░░░░
Tier: Foundational

Worst offender: aurora glow
Fixing first: pick one accent color
```

---

## Getting better answers

Three things change the quality of what you get back.

**Give it context.** "Scan my landing page" gets a generic scan. "Scan my landing page, it's for solo bookkeepers and I want them to book a call" gets findings measured against something real. A tell that matters on a premium B2B page may be perfectly fine on a playful consumer app. Context determines severity.

**Bring evidence.** A URL or screenshot always beats a description. The skill reads what's actually there. If you only have a description, say so and describe what's on screen specifically: "dark background, centered headline, four feature cards below the fold."

**Ask for the prompt.** Every fix should come with something you can paste into your builder. If you get a fix without one, ask: "give me a prompt I can paste into Lovable to make that change." Insight you can't ship isn't insight.

---

## What your score is actually telling you

**0–1 · Authored.** You made real decisions somewhere. Keep going, and protect what's working by writing down why you chose it.

**2–4 · Developing.** The structure is sound. Usually what's left is the gradient and the default heading font. Two changes and you're authored.

**5–7 · Foundational.** Don't fix components one at a time. Rebuild from color and type first, because everything downstream inherits from those two decisions. Fixing a card before fixing your palette is rearranging furniture in a room that's the wrong color.

**8–10 · Default output.** This is the most common score and the least alarming. Start with the system, not the components. Pick one accent color and one heading typeface. Those two decisions alone will move you several tiers.

---

## Fix in this order

Whatever your score, this sequence gives you the most visible change for the least effort.

1. **Kill the glow or gradient** — the single fastest visual change
2. **Pick one accent color** — everything else becomes neutral
3. **Swap the heading typeface** — one serif reads instantly as non-default
4. **Replace emoji with a real icon set**
5. **De-card the layout** — use space to group, not boxes
6. **Rewrite the headline** — name a specific user and a specific outcome
7. **Remove any fake proof** — an empty space beats an invented testimonial

Full detail and builder prompts for all ten are in `references/tells-catalog.md`.

---

## What this skill won't do

It finds generic AI patterns and replaces them. That's the whole job.

It does not score your design quality, test usability, check accessibility, or tell you whether the thing works for a real person. It can't help you *before* you build, when you're staring at a blank canvas with no defaults to react against.

Most importantly: it can't catch the design that looks clean and still fails. A page can pass every tell in this catalog and still leave visitors with no idea what to do next. That's a different failure and it needs a different tool.

---


---

## Want a second pair of eyes

The hardest part of auditing your own work is that you know too much about it. You remember why you added every element. A first-time visitor doesn't, and un-knowing that on your own is genuinely difficult.

**Signature Audit · $500** — Send what you built. I'll audit it  personally. Get it scored across all eight dimensions in five days, with prioritized fixes and a 60-minute walkthrough call.

[ai-atelier.com/vibe-code-studio](https://ai-atelier.com/vibe-code-studio)

---

## License

Free to use. Use it on your own work, on client work, teach it, share it. Attribution appreciated, not required.

Don't sell it or repackage it as your own product. Full terms in `LICENSE`.

---

## Questions

hello@thebloomology.com

I read every email. If you run the scan, reply and tell me your score. I'm collecting them.

---

*AI Tells Detector™, AI Design Aesthetic Rules™, T.A.S.T.E.™, Signal Audit™, Taste Filters™, Translation Sprint™, Embodiment Loop™ and Aesthetic Intelligence™ are trademarks of AI Atelier Agentic Consulting. © 2026 Jeneba Wint.*

*Sensemaking · Judgment · Taste*


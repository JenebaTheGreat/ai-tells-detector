# AI Tells Detector™

**Your AI builder made a hundred design decisions before you made one. This finds them.**

[![License: Free](https://img.shields.io/badge/license-Free%20to%20use-38A169.svg)](./LICENSE)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-0A1628.svg)](https://claude.ai)

Every AI-built site has the same face. The centered hero. The two buttons. The purple-to-blue gradient. The aurora glow behind the headline. Emoji standing in for icons. Cards inside cards inside cards. Inter, untouched.

Different tools, identical output, because Lovable and v0 and Bolt and Cursor all ship the same defaults before you make a single real decision.

This is a free Claude and Codex skill that catalogues **10 of those defaults**, tells you which ones are in your work, explains why the models reach for each one, and hands you the exact fix plus a prompt to paste into your builder.

**→ [Get the Fix Sheet (free PDF)](https://interactive-web-palette.lovable.app)** · all 10 tells, the fix order, one page

---

## Take the test

Answer 10 yes-or-no questions about your build. Takes about a minute. No install needed.

Open [`references/quick-scan.md`](./references/quick-scan.md) and count your yeses.

| Score | Tier | What it means |
|---|---|---|
| **0–1** | Authored | A real design system is visible. You made decisions. |
| **2–4** | Developing | The bones are there. A few defaults remain. |
| **5–7** | Foundational | The AI is running the show. Rebuild from color and type. |
| **8–10** | Default output | Start with the system, not the components. |

Most people score five or higher the first time.

That is not a personal failure. It is what happens when a tool ships a hundred decisions before you make one. You inherited choices you never made. Now you can make them.

---

## The 10 tells

**Visual**

1. **Neon-on-dark palette** with no single focus color
2. **The aurora glow** behind the hero
3. **Purple-to-blue gradients** on headings, buttons, backgrounds, icons
4. **Emojis as the icon system**
5. **Cards inside cards inside cards**
6. **Every nav item a different color**
7. **The "same face" hero**, centered with two buttons
8. **Inter + ShadCN + Lucide + Tailwind**, untouched

**Content and trust**

9. **Fabricated proof**: placeholder testimonials, invented stats, "as seen in" logos
10. **Robotic copy** with no point of view

Each entry in [`references/tells-catalog.md`](./references/tells-catalog.md) explains what it looks like, **why the model defaults to it**, the exact fix, and a paste-ready builder prompt.

That middle part is the useful part. Anyone can tell you purple gradients look generic. The reason they happen is that purple-to-blue is the most common gradient in tech marketing, so the model learned it as the visual signal for "innovative software" with no sense of whether it serves your product.

---

## Install

**Claude Projects** (easiest)

1. Download this repo
2. Create a new Project at [claude.ai](https://claude.ai)
3. Upload `SKILL.md` and the `references/` folder to Project knowledge
4. Ask your question. The skill activates on its own.

**Claude Code**

```bash
git clone https://github.com/JenebaTheGreat/ai-tells-detector.git ~/.claude/skills/ai-tells-detector
```

**Codex**

```bash
git clone https://github.com/JenebaTheGreat/ai-tells-detector.git ~/.codex/skills/ai-tells-detector
```

**ChatGPT, Cursor, or anything else**

Paste `SKILL.md` at the top of a conversation, then paste `references/tells-catalog.md` when it asks.

Full walkthrough in [`GETTING-STARTED.md`](./GETTING-STARTED.md), including video guides for non-technical builders.

---

## Run a scan

```
Here's my landing page: [URL or screenshot].

Scan it for the tells that make things look AI-generated. Tell me my
score, then give me the three fixes that matter most with paste-ready
prompts I can hand to my builder.
```

You get back your score, the three highest-impact fixes with exact values and builder prompts, the remaining tells as a short backlog, and a scorecard you can post:

```
AI TELLS TEST · 6/10
▓▓▓▓▓▓░░░░
Tier: Foundational

Worst offender: aurora glow
Fixing first: pick one accent color
```

---

## What's in here

```
ai-tells-detector/
├── SKILL.md
├── references/
│   ├── tells-catalog.md    All 10 tells, fixes, and builder prompts
│   └── quick-scan.md       The 60-second self-assessment
├── GETTING-STARTED.md      Install, first scan, how to read your score
├── LICENSE
└── README.md
```

---

## Fix in this order

Whatever your score, this sequence gives the most visible change for the least effort.

1. Kill the glow or gradient
2. Pick one accent color
3. Swap the heading typeface, one serif reads instantly as non-default
4. Replace emoji with a real icon set
5. De-card the layout, use space to group instead of boxes
6. Rewrite the headline to name a specific user and outcome
7. Remove any fake proof, an empty space beats an invented testimonial

**→ [Get the Fix Sheet](https://interactive-web-palette.lovable.app)** for all ten in one page.

---

## What this does not do

It finds generic AI patterns and replaces them. That is the whole job.

It does not score design quality, test usability, check accessibility, or help you *before* you build when there are no defaults to react against yet.

Most importantly, it cannot catch the design that looks clean and still fails. A page can pass all ten tells and still leave visitors with no idea what to do next. Different failure, different tool.


---

## Want a second pair of eyes

The hardest part of auditing your own work is that you know too much about it. You remember why you added every element. A first-time visitor does not, and un-knowing that on your own is genuinely difficult.

**Signature Audit · $749** — Send your build. Get it scored across eight dimensions in five days, with prioritized fixes and a 60-minute walkthrough call.

[ai-atelier.com/vibe-code-studio](https://ai-atelier.com/vibe-code-studio)

---

## License

Free to use. Use it on your own work, on client work, teach it, share it. Attribution appreciated, not required. Do not sell it or repackage it as your own product. See [LICENSE](./LICENSE).

AI Tells Detector™, AI Design Aesthetic Rules™, T.A.S.T.E.™, Signal Audit™, Taste Filters™, Translation Sprint™, Embodiment Loop™ and Aesthetic Intelligence™ are trademarks of AI Atelier Agentic Consulting.

---

Built by [Jeneba Wint](https://jenebawint.com) · **AI Atelier Agentic Consulting** · Vibe Code Studio

*Sensemaking · Judgment · Taste*


# AI Tells Test

Answer each question with **yes** or **no**. Count one point for every yes.

Judge what is actually present, not what you intended. If you are unsure, count it as yes and inspect it during the full scan.

## The 10 questions

1. **Neon without focus:** Does the interface use several bright cyan, violet, blue, pink, or green accents on a dark background without one clear action color?
2. **Aurora glow:** Is there a large blurred colored glow behind the hero, headline, dashboard, pricing section, or product mockup?
3. **Purple-to-blue gradients:** Does a purple-to-blue gradient appear on more than one kind of element, such as headlines, buttons, icons, borders, or backgrounds?
4. **Emoji icons:** Are emojis being used as the main icon system or as decoration inside feature cards?
5. **Cards everywhere:** Are static sections boxed into rounded cards, or are cards nested inside other cards?
6. **Rainbow navigation:** Do navigation items or icons each use a different color without those colors carrying a defined meaning?
7. **Same-face hero:** Is the hero a centered eyebrow, large generic headline, supporting sentence, and two rounded buttons, followed by a floating mockup or logo row?
8. **Untouched defaults:** Does the build look like the default Inter + ShadCN + Lucide + Tailwind combination, with no distinctive type, spacing, radius, or icon rules?
9. **Unverified proof:** Does the page contain any testimonial, logo, metric, review, award, or trust claim you cannot verify right now?
10. **Robotic copy:** Could the headline and supporting copy describe several competitors unchanged, or does it rely on phrases such as “revolutionize,” “unlock,” “elevate,” or “supercharge”?

## Your score

| Yes answers | Tier | Meaning |
|---|---|---|
| 0–1 | **Authored** | A real design system is visible. |
| 2–4 | **Developing** | The bones are there. A few defaults remain. |
| 5–7 | **Foundational** | The AI is running the show. Rebuild from color and type. |
| 8–10 | **Default output** | Start with the system, not the components. |

Most first scans land at five or higher. That is a starting point, not a verdict.

## What to fix first

- If question 9 is yes, remove or verify the proof first.
- If questions 1–3 are yes, fix the palette and effects before individual components.
- If questions 7 or 10 are yes, rewrite the hero around one user and one concrete outcome.
- If question 8 is yes, define shared type, spacing, radius, border, and icon tokens before polishing screens.
- Then flatten unnecessary cards and standardize icons and navigation.

For the reasoning, exact fixes, and paste-ready builder prompts, open [`tells-catalog.md`](./tells-catalog.md).

## Copyable scorecard

```text
AI TELLS TEST · [N]/10
[▓ for each tell found, ░ for each not found, 10 total]
Tier: [Authored / Developing / Foundational / Default output]

Worst offender: [the single most damaging tell]
Fixing first: [the top-priority fix, in 3 to 5 words]

Free scan → github.com/JenebaTheGreat/ai-tells-detector
```

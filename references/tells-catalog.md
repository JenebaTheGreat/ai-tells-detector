# AI Tells Catalog

Use this catalog for every scan. Check all ten tells before scoring, then prioritize the three fixes that most reduce the generated look for the least effort.

Context changes severity. Name the product, audience, and desired action before judging a pattern.

## 1. Neon-on-dark with no focus color

**What it looks like:** A near-black background carries several equally loud cyan, violet, blue, pink, and green accents. Every interactive element competes for attention.

**Why AI defaults to it:** Training data associates neon-on-dark palettes with modern software and emerging technology. Without a brand rule, the model combines multiple familiar signals instead of choosing one.

**Exact fix:** Keep the dark surface if it fits the product, but choose one accent color for actions and active states. Move everything else to neutral grays. Use lighter and darker values of the same accent only when state or hierarchy requires them.

**Paste-ready prompt:**

> Reduce this interface to one accent color: [HEX]. Use it only for primary actions, active states, and essential emphasis. Convert all other cyan, violet, pink, blue, and green accents to neutral grays. Preserve accessible contrast and do not add gradients or glow.

## 2. The aurora glow

**What it looks like:** Large blurred purple, blue, or pink blobs sit behind the hero, dashboard, or pricing section. The glow decorates empty space without explaining the product.

**Why AI defaults to it:** A blurred radial gradient is an easy way to make an otherwise empty composition look polished. It creates atmosphere without requiring a product-specific visual idea.

**Exact fix:** Remove the glow. Replace it with either clean negative space, a real product view, a meaningful illustration, or one restrained flat field derived from the brand color.

**Paste-ready prompt:**

> Remove every blurred radial gradient, aurora, glow, and colored shadow from this section. Keep the background flat. Use the released space for [PRODUCT SCREENSHOT / REAL ARTIFACT / NOTHING]. Do not replace the glow with another decorative effect.

## 3. Purple-to-blue gradients everywhere

**What it looks like:** The same purple-to-blue blend appears on headlines, buttons, icons, borders, badges, and backgrounds.

**Why AI defaults to it:** Purple-to-blue is heavily represented in technology marketing, so models treat it as shorthand for innovation even when it has no relationship to the product.

**Exact fix:** Use solid color for type and controls. If a gradient is truly part of the brand, reserve it for one signature moment and define its exact stops, direction, and purpose.

**Paste-ready prompt:**

> Replace all purple-to-blue gradients with solid colors. Set headings to [TEXT HEX], primary buttons to [ACCENT HEX], and decorative surfaces to [SURFACE HEX]. Allow no gradient unless it communicates data or state; if one remains, use it once only.

## 4. Emojis as the icon system

**What it looks like:** Emoji rockets, lightning bolts, targets, stars, brains, or checkmarks sit inside feature cards. Their drawing style, size, and color vary by platform.

**Why AI defaults to it:** Emojis are fast semantic placeholders. The model can express a concept without choosing or drawing a coherent icon language.

**Exact fix:** Use one icon family or a custom set. Match stroke width, optical size, color, container treatment, and alignment. Remove icons that only repeat the heading.

**Paste-ready prompt:**

> Replace every emoji used as an interface icon with [ICON LIBRARY] icons. Use a consistent [1.5PX / 2PX] stroke, [20PX / 24PX] size, and one color. Remove any icon that does not add meaning beyond its label. Keep accessible text labels.

## 5. Cards inside cards inside cards

**What it looks like:** Nearly every piece of content has its own rounded rectangle, border, shadow, and tinted background, often nested inside another card.

**Why AI defaults to it:** Card components are safe, reusable containers. They solve grouping without requiring the model to reason about rhythm, proximity, or editorial hierarchy.

**Exact fix:** Keep cards only where a bounded object needs independent interaction or state. Group static content with spacing, rules, columns, or typography. Flatten nested cards first.

**Paste-ready prompt:**

> De-card this layout. Keep a card only when the content is a separately actionable or movable object. Remove nested backgrounds, borders, corner radii, and shadows. Regroup static content using whitespace, alignment, headings, and subtle dividers.

## 6. Every nav item a different color

**What it looks like:** Navigation labels, icons, or pills each use a different bright color, making the header read like a component demo rather than a navigation system.

**Why AI defaults to it:** Color is an easy way to make repeated items appear distinct, but it invents categories that may not exist and weakens the active state.

**Exact fix:** Use one neutral treatment for inactive items and one accent treatment for the current or hovered item. Reserve additional colors for established semantic states such as warning or error.

**Paste-ready prompt:**

> Standardize the navigation. Make every inactive item [NEUTRAL HEX], and use [ACCENT HEX] only for the active and focus states. Remove per-item colors, gradients, and colored icon containers. Preserve a visible keyboard focus indicator.

## 7. The same-face hero

**What it looks like:** A centered eyebrow, oversized gradient headline, generic supporting sentence, and two rounded buttons appear above a floating product mockup or row of logo placeholders.

**Why AI defaults to it:** This structure is statistically common, responsive, and easy to assemble. It works at a basic level for almost anything, which is why it feels specific to nothing.

**Exact fix:** Choose a composition that expresses the product's actual value: lead with a real artifact, an asymmetric editorial layout, a task demonstration, a decisive claim, or a before-and-after. Keep one primary action unless the second serves a genuinely different user.

**Paste-ready prompt:**

> Rebuild this hero around [REAL PRODUCT ARTIFACT OR CUSTOMER OUTCOME]. Use an asymmetric [TEXT/ARTIFACT] layout instead of a centered stack. Write the headline for [SPECIFIC USER] who wants [SPECIFIC OUTCOME]. Keep one primary CTA: [CTA]. Remove the decorative eyebrow, gradient text, and redundant secondary button.

## 8. The untouched default stack

**What it looks like:** Inter or a similar default sans-serif, ShadCN-style components, Lucide icons, Tailwind spacing, medium rounded corners, and stock gray borders appear without any product-specific rules.

**Why AI defaults to it:** These tools are common in code examples and work well together. The result is functional, but their defaults become the design identity when no system overrides them.

**Exact fix:** Do not replace the whole stack merely to be different. Define a distinctive type pairing, spacing rhythm, radius scale, border behavior, icon rules, and component density. Apply those tokens consistently.

**Paste-ready prompt:**

> Keep the existing component stack, but replace its visual defaults with this system: heading typeface [FONT], body typeface [FONT], spacing base [VALUE], radii [VALUES], border color [HEX], icon size/stroke [VALUES], and control height [VALUE]. Update shared tokens and base components first; do not style each screen independently.

## 9. Fabricated proof

**What it looks like:** Invented testimonials, placeholder names, unsupported usage numbers, fake company logos, or claims such as “trusted by thousands” appear without evidence.

**Why AI defaults to it:** Testimonials, logos, and metrics are common conversion-page patterns. A model may complete the pattern even when real proof was never supplied.

**Exact fix:** Remove every unsupported claim. Replace it only with verified evidence: a named customer quote with permission, an attributable result, a real product fact, or an honest statement about the current stage.

**Paste-ready prompt:**

> Audit this page for proof claims. Remove every testimonial, logo, metric, review, award, and trust statement that is not backed by evidence I supplied. Do not invent replacements. Where proof is missing, use factual product details or leave the space empty. Return a list of removed claims for verification.

## 10. Robotic copy with no point of view

**What it looks like:** Headlines promise to “revolutionize,” “unlock,” “elevate,” or “supercharge” a vague outcome. Supporting copy stacks broad benefits, balanced clauses, and generic adjectives without naming a real user, constraint, or belief.

**Why AI defaults to it:** Models optimize for fluent, broadly acceptable language. Without source material or a sharp position, they average together familiar marketing phrases.

**Exact fix:** Name one user, one painful situation, one concrete outcome, and one belief the brand is willing to stand behind. Prefer language customers actually use. Delete claims that could describe a competitor unchanged.

**Paste-ready prompt:**

> Rewrite this copy for [SPECIFIC USER] in [SPECIFIC SITUATION] who wants [CONCRETE OUTCOME]. Use the point of view: [BELIEF]. Ban these words: revolutionize, unlock, elevate, seamless, powerful, game-changing, supercharge. Preserve only claims supported by the product. If a sentence could fit any competitor, make it specific or delete it.

## Priority rules

When several tells are present, usually fix them in this order:

1. Fabricated proof
2. Glow and repeated gradients
3. Unfocused color
4. Same-face hero and robotic copy
5. Default type and component tokens
6. Nested cards
7. Emojis and navigation color

Raise a trust failure above every visual issue. Otherwise, favor system changes that improve multiple screens over isolated component polish.

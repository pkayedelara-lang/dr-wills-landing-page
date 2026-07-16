# Dr. Will's Landing Page — Project Instructions

## Purpose

This project builds and refines the Dr. Will's landing page — a bold, playful, editorial food-brand site (award-winning condiments: ketchup, mayo, hot sauces). Work here spans a standalone design-system reference (`design-system.html` / `.css` / `.md`) and the actual landing-page implementation (`dr-wills-landing-page-prototype.html` and related files).

## Visual reference hierarchy

When references conflict, in order:

1. Written user instructions.
2. Attached Dr. Will's homepage screenshot(s) — branding and visual language authority.
3. The live site, `https://www.dr-wills.com/` — secondary reference for interaction/responsive detail.
4. Existing landing-page files — source of truth for content, structure, and current functionality.
5. Lovable references under `assets/references/` — layout/interaction inspiration for a specific section only.

A homepage screenshot controls visual language (type scale, colour balance, spacing, curves, imagery, composition). It never overrides the landing page's existing conversion strategy, section order, or copy.

**Note:** all local assets live under a single `assets/` folder (lowercase, hyphenated, no colons) with subfolders `logos/`, `credentials/`, `products/`, `recipes/`, `references/`, `press/`, `images/`, `icons/`, `fonts/`, `strategy/`. Reference paths as `assets/<subfolder>/<file>` — GitHub-Pages-safe relative paths, no leading `./` colon-folder syntax.

## Official colours

```css
--color-pink: #E68699;
--color-pink-deep: #C45E74;
--color-black: #000000;
--color-white: #FFFFFF;
--color-cream: #FDF5F1;
```

Black, white, and pink are the dominant palette. Secondary product-accent colours (barbecue orange, avocado green, sriracha red, mustard yellow — see `design-system.md`) are contextual only, never decorative filler.

## Official typography

Adobe Fonts stylesheet, once per document `<head>`:

```html
<link rel="stylesheet" href="https://use.typekit.net/bhf6iab.css">
```

- Headings/buttons/labels/nav: `"paralucent-condensed"`, weight 700, uppercase.
- Body copy: `"paralucent"`, weight 400.
- Never self-host these fonts or substitute a different family without explicit instruction.

## UI work: use the dr-wills-ui skill

For any layout, visual refinement, screenshot recreation, responsive styling, component design, typography, spacing, or brand-consistency work on this project, use the `dr-wills-ui` skill (`.claude/skills/dr-wills-ui/SKILL.md`). After any UI edit, run the checklist in `.claude/rules/visual-quality.md` before considering the work done.

## Preserve existing structure and functionality

The current landing-page structure, section order, copy, and functionality (Build-a-Box, customer reviews, FAQ accordion, anchor links) are the source of truth. Don't reorganize sections, rewrite copy, delete functionality, or introduce a new framework unless explicitly asked. Prefer targeted edits over full-file rewrites.

## Workflow: inspect, implement, preview, refine

1. **Inspect** the current code and any relevant screenshot/reference before editing.
2. **Implement** with maintainable HTML/CSS/JS, reusing existing design-system tokens and components.
3. **Preview** the result in a real browser — desktop, tablet, and mobile.
4. **Refine** by comparing the rendered output against the reference and correcting measurable discrepancies (one comparison pass, not a redesign).

## References

Visual and content references live under `assets/references/` (existing live-section screenshots, the Lovable founder-story reference, colour-rhythm and wave-break references, build-your-box and homepage full-page captures). Brand assets (logo, badge, lockup) live under `assets/logos/`. Product photography lives under `assets/products/`.

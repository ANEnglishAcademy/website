# AN English Academy Website Workflow

## Goal
Create multiple WordPress Elementor product pages in one consistent AN English Academy style.

## How We Work

### 1. User Gives a Product Brief
For each page, provide:
- Product name
- Who it is for
- Main result
- Format: individual/group, number of lessons, duration
- Price or package
- CTA destination: Telegram, form, WhatsApp, etc.
- Any existing text, screenshots, references, or must-have blocks

### 2. Codex Returns Elementor-Ready Blocks
Each product page is delivered as:
- Page structure
- Copy for each section
- HTML for each Elementor HTML widget
- CSS split into small containers
- Short paste instructions
- Mobile/layout notes

### 3. Elementor Setup
Recommended setup:
- One global AN English Academy CSS block for shared styles
- Separate Elementor containers for each page section
- One HTML widget per section
- Same class prefix for all custom blocks: `ane-`

### 4. Quality Check
After pasting into Elementor, user sends screenshots:
- Desktop first screen
- Desktop full page or key sections
- Mobile first screen
- Mobile offer/CTA section

Codex then fixes:
- Spacing
- Text length
- Mobile layout
- Color balance
- CTA visibility
- Typography

## Standard Product Page Structure

1. Hero
2. Who it is for
3. Result / transformation
4. What is inside
5. How lessons work
6. Why AN English Academy
7. Price / package
8. FAQ
9. Final CTA

## Product Pages

| Page | Status | Notes |
|---|---|---|
| Dream Job | Design draft started | Needs Elementor paste test |
| Level Up | Not started | Need product brief |
| Exams | Not started | Need exams list |
| University Admission | Not started | Need target countries/universities |
| New York Accent | Not started | Need exact promise and format |
| English 16+ | Not started | Need audience and parent/student angle |
| Corporate English | Not started | Need B2B offer and pricing logic |

## File Naming

Use this structure for each page:
- `00-base-css.css`
- `01-hero.html`
- `01-hero.css`
- `02-who.html`
- `02-who.css`
- `03-result.html`
- `03-result.css`
- `04-inside.html`
- `04-inside.css`
- `05-format.html`
- `05-format.css`
- `06-offer.html`
- `06-offer.css`
- `07-faq.html`
- `07-faq.css`

## Copy/Paste Rule

For Elementor:
1. Paste global CSS once.
2. Add a new Elementor container.
3. Add an HTML widget inside it.
4. Paste section HTML.
5. Paste section CSS either in the same HTML widget inside `<style>...</style>` or in page custom CSS.
6. Send screenshots back for polish.

## Brand Rules

Colors:
- Violet: `#6B219E`
- Pink: `#FF00A1`
- Yellow: `#FBE100`
- White: `#FFFFFF`
- Ink: `#242027`

Fonts:
- Main: Evolventa
- Accent: 2A Resphekt, when available

Tone:
- Bright
- Confident
- Personal
- International
- Fresh, not generic

## What Codex Should Deliver Each Time

For each new page:
- A short page concept
- Finished section copy
- Elementor-ready code split by sections
- Exact paste order
- A checklist for screenshot review

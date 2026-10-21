# Power Restored — Courtney Blake

A draft one-page site for **Courtney Blake, M.Ed., NBC-HWC, CPT** — National Board Certified
Health & Wellness Coach and Certified Master Personal Trainer.

Built to the Power Restored brand guide: Barlow Condensed display type, charcoal `#1F2420`,
lime `#8CC63F`, pale yellow `#F1EFC4`, forest `#3F6B17`, navy `#1C2C4A`.

## Why this exists

Courtney posts consistently and well, but anyone who reads a post and wants to hire him has
nowhere to go except his DMs. This page gives that interest somewhere to land, and a single
clear next step.

## Structure

| Section | Job it does |
|---------|-------------|
| Hero | Name the brand, the promise and who it is for, with one primary CTA |
| Mission band | The brand line: reclaim your health, restore your confidence |
| Who this is for | Qualifies adults 40+ rebuilding after a setback |
| The method | Reflect / Reset / Rebuild / Restore, the brand's own framework |
| Work with me | Coaching, personal training, corporate wellness |
| About | Credentials that can be verified: NBC-HWC, CPT, M.Ed. |
| Start here | Free consultation, the single conversion point |

## Stack

Static HTML and CSS. No build step, no framework, no dependencies. Fonts come from Google
Fonts; everything else is local. It loads fast on a phone, which is where most of the
traffic from LinkedIn will come from.

Dark mode is supported via `prefers-color-scheme` using the brand guide's dark tokens.

## Before this goes live

- [ ] **Replace the placeholder email.** `hello@example.com` appears in two places in
      `index.html` (the Start Here button and the fineprint line).
- [ ] **Swap the mailto for a booking link** if Courtney uses Calendly, Acuity or similar.
      The CTA is wired to `mailto:` only as a working fallback.
- [ ] **Confirm the portrait** is a photo Courtney owns and is happy to publish.
- [ ] **Settle the audience line.** His LinkedIn headline says "Adults 40+" and his banner
      says "men 40 to 65". This page follows the headline. Pick one and use it everywhere.
- [ ] Add real testimonials once there are approved ones. None are included here, because
      inventing them is not an option.

## Local preview

No Python needed:

```bash
node server.js
```

Then open http://localhost:8788

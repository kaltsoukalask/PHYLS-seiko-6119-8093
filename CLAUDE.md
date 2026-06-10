# PHYLS — Project Context

## What PHYLS is
A curated vintage watch brand based in Athens. PHYLS sources vintage watches,
prepares them (inspection, cleaning, regulation, new strap), and sells them with
a branded experience: box, thank-you letter, NFC card linking to a digital passport.

The long-term vision is a B2B infrastructure layer — a trust and provenance system
that other vintage dealers can use. PHYLS doesn't sell watches. PHYLS stewards them.

## The Digital Passport
A single self-contained HTML file hosted on GitHub Pages, linked via NFC card.
- Mobile-first, tabbed app structure (Home, Story, Care, Service, Ownership)
- All images embedded as Base64 — no external dependencies
- One file per watch, one GitHub repo per watch

## Brand values
- Quiet luxury — honest, unflashy, no pretension
- Education-first — buyers understand exactly what they own and why it matters
- Continuity — the watch lived before the owner, it will live after them
- No air — every element earns its place, nothing is vague or decorative
- Stewardship — PHYLS is the custodian of the watch's story across multiple owners

## Target customer
People who value context, history, and the experience around the watch — not just
the object itself. This includes first-time buyers entering the vintage world, but
also seasoned buyers who already own or can afford a Rolex, and want something more
meaningful: a vintage Omega, a Cartier, a piece with a story.

What unites them is not budget or experience level. It's that they care about:
- The history and provenance of what they own
- Community and belonging to something with depth
- Safety and trust in the buying process
- Innovation in how watches are presented and documented

They are not pure collectors chasing rare references. They are people for whom
the watch is part of a broader identity and set of values.

## Brand identity
- Primary color: black
- Logo: white on black
- Tone: quiet, precise, editorial — never flashy or hype-driven
- The brand should feel like a trusted expert, not a marketplace

## Passport structure
Each passport contains:
- Home: watch photo hero, owner name, 4 section cards
- Story: brand history, line context, specs grid, anatomy (dial/case/movement)
- Care: accordion — setting time, day/date, starting, water, magnetism, daily use
- Service: timeline of interventions, next service due
- Ownership: certificate with owner name, passport ID, warranty dates + community block

## Design language
- Fonts: Cormorant Garamond (serif, editorial) + DM Sans (sans, clean)
- Colors: dark ink (#1a1815), parchment (#f5f2ed), gold (#b8945a), white (#fdfcfa)
- Dark backgrounds for headers and ownership certificate
- Gold accents for eyebrows, active states, warranty dot
- Transitions: slide in from right (0.35s cubic-bezier)
- Mobile-first, max-width optimized for phone screens

## When editing a passport
- Images are Base64 embedded — to update a photo, re-encode and replace the data URI
- Owner details appear in two places: home-owner-strip and the ownership certificate
- Warranty end date = purchase date + 6 months
- Service date format: Month Year (e.g. June 2025)
- Passport ID format: PHYLS-001, PHYLS-002 etc.
- Repo naming: PHYLS-[brand]-[reference] e.g. PHYLS-seiko-6119-8093

## Current watches
- PHYLS-001: Seiko 5 Ref. 6119-8093, owner Nikos Triantafyllou, issued 11 June 2026

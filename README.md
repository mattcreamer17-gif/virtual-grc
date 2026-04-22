# Virtual GRC Landing Page

Intended URL path: /for/virtual-grc

A single-page bespoke pitch built for Jose Melendez and the Virtual GRC team ahead of eMerge Americas 2026, Booth 1246. The page uses Virtual GRC's own brand tokens (primary blue #1A6AFF, orange action accent #EA580C, Open Sans, flat SaaS aesthetic) so the experience reads as native to their product rather than imported from Eduba.

## Structure

- `index.html`: semantic HTML, hero through CTA, no JavaScript required.
- `styles.css`: all visual treatment. CSS variables for tokens. Responsive down to 375px.
- `logo.png`: Virtual GRC wordmark, pulled from their Wix static CDN and copied into this folder for offline rendering.

## Content source

All copy comes from `fit-analysis.md` section 7. The h1 matches the Section 7 headline verbatim. Case study anchors (VigilOre 160+ hours to under 5 minutes, Correlation One with 1,500+ trained, KPMG UK as Big Four, NLP Logix with the mandatory "in machine learning since 2011 / over 150 data scientists" framing) are all linked to real URLs where applicable. The ICM repository, Ethics Engine arXiv paper, and AuditEngine repo all open in new tabs.

## Hosting

Deploy to `[domain]/for/virtual-grc`. Jake should confirm the Calendly URL (`https://calendly.com/thecro-eduba/30min`) remains Matt Creamer's active booking link before the booth pass.

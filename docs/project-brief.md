# Texas Injury Calculator — project brief

## Purpose

Standalone lead-gen property at **texasinjurycalculator.com**. A Texas-specific personal injury settlement calculator that captures attorney-bound leads via embedded contact form. Not part of the R&R portfolio — its own brand and conversion path.

## Stack

- Static HTML, vanilla JS, embedded CSS — no frameworks, no build step
- Hosted on Netlify, auto-deploys from GitHub `ross1073/texasinjurycalculator` main branch
- Mobile-first (375px min)
- Tracking: GTM-5Z3PJP2W (deferred 1500ms) → GA4 G-CRLLGGXLX9, `generate_lead` event on form submit
- Search Console: `sc-domain:texasinjurycalculator.com`, sitemap submitted

## Legal framework (the calculator's logic)

- Texas modified comparative negligence — 51% bar rule (Civil Practice & Remedies Code §33.001)
- Statute of limitations: 2 years (§16.003)
- Claimant ≥51% at fault → $0 recovery; <51% → damages reduced by fault percentage

## Key files

- `index.html` — single-page calculator (homepage), the conversion target
- `pain-and-suffering-calculator-texas.html` — guide on P&S calculation
- `average-car-accident-settlement-texas.html` — guide on settlement amounts
- `texas-personal-injury-statute-of-limitations.html` — SOL guide
- `what-to-do-after-car-accident-texas.html` — post-accident steps
- `settlement-infographic.html` — infographic page
- `disclaimer.html`, `privacy-policy.html`, `terms.html` — legal pages
- `sitemap.xml` — 9 URLs
- `_redirects` — Netlify .html → clean URL 301s
- `favicon.svg` — TX-shaped logo
- `_archive/` — not served publicly (old wizard, keyword research)

## Conventions

- All CSS embedded; all JS vanilla
- Every page: title, meta description, canonical, Open Graph tags
- Schema: WebApplication on calculator, FAQPage on guides
- All legal claims cite specific Texas statutes
- Calculator must show the "not legal advice" disclaimer
- Every page has a clear CTA (contact form or attorney connect)
- Cross-link guide pages to each other and back to the calculator
- "Done" = live on texasinjurycalculator.com — verify on production after Netlify build, not just on push

## Target keywords

- texas personal injury calculator
- texas settlement calculator
- pain and suffering calculator texas
- average car accident settlement texas

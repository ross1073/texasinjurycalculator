# Texas Injury Calculator

## Project Overview

- **Site:** texasinjurycalculator.com
- **Purpose:** Texas personal injury settlement calculator — standalone lead gen property
- **Monetization:** Attorney sponsorship / contact form leads
- **Stack:** Static HTML, vanilla JS, embedded CSS
- **Deploy:** Netlify via GitHub (ross1073)

## Legal Framework

- **Formula:** Texas modified comparative negligence (51% bar rule)
- **Statute:** Civil Practice & Remedies Code §33.001
- **Statute of Limitations:** 2 years (§16.003)
- **Key rule:** If claimant is 51% or more at fault, they recover nothing. Under 51%, damages are reduced by their percentage of fault.

## Development Rules

- This is a standalone property, not part of the R&R portfolio
- All CSS is embedded (no external stylesheets)
- All JS is vanilla (no frameworks, no build tools)
- Static HTML — no server-side rendering
- Mobile-first design — test at 375px width minimum
- Every page must include a clear CTA (contact form or attorney connect)
- Calculator must show disclaimer: not legal advice, consult an attorney
- All legal references must cite specific Texas statutes

## Deploy Workflow

1. Push to GitHub repo (ross1073/texasinjurycalculator)
2. Netlify auto-deploys from main branch
3. Domain: texasinjurycalculator.com

## SEO Notes

- Target keywords: texas personal injury calculator, texas settlement calculator, texas injury settlement estimate
- Every page needs: title tag, meta description, canonical, Open Graph tags
- Schema markup: WebApplication (calculator), FAQPage (FAQ sections), Organization
- Sitemap.xml and robots.txt required at root

## File Structure

```
/
├── index.html          # Main calculator page
├── CLAUDE.md           # This file
├── sitemap.xml
├── robots.txt
├── _redirects          # Netlify redirects
└── assets/             # Images, favicon, etc.
```

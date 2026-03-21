# JJ Pavement

Palatine/Arlington Heights IL paving company. Working with Christian (cfro6 on GitHub).

## Quick Links
- **Preview site:** christianjjpave.pages.dev
- **Original site:** jjpave.com
- **GitHub:** hinescreative/JJ-Pavement (Christian is collaborator)

## Project Structure
- `index.html` — homepage (13 issues pending from Christian's overwrite)
- `about.html`, `contact.html`, `our-work.html` — normalized pages
- `services/` — 4 service pages
- `service-area/` — 8 location pages
- `images/` — site assets
- `shared/` — shared components
- `research/` — marketing research (CRO, design, SEO, competitor analysis)

## Deploy
```bash
npx wrangler pages deploy . --project-name christianjjpave --branch main
```

## Current Status
- 18-page multi-page redesign built
- Nav/footer/colors normalized across all pages
- Sticky mobile tap-to-call bar added
- Chamber badges (Palatine + Arlington Heights) in footers
- **13 index.html issues pending** (dark reviews, photo slider, lightbox, dead CSS/JS)
- Form actions still have placeholder GHL URLs
- LocalBusiness JSON-LD schema not added yet
- Christian's Claude keeps overwriting shared code — coordination needed

## Notes
- This is a collaboration with Christian, NOT a Hines Creative retainer client
- Wes is helping Christian with the redesign

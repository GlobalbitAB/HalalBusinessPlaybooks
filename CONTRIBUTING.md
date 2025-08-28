# Contributing to HalalBusiness Playbooks

Thanks for contributing! This repo powers **HalalBusinessReady.com** (main hub) and funnels from
**HalalExpoAfrica.com**, **HalalExpoHub.com**, **HalalKenya.com**, **HalalEthiopia.com**, **HalalEastAfrica.com**, and **LicensingHalal.com**.
All funnel domains redirect into subpages on the main site.

---

## Folder Rules (keep it simple)

**/HalalBusinessReady/**
- `checklists/` — HAL-Q Lite + sector PDFs (Food, Cosmetics, Pharma).
- `badges/` — trust badge text, PNG/SVG, QR assets, page copy.
- `proof-packs/` — document lists, SOPs, templates for verification.
- `content/`
  - `keywords/` — CSVs for ZimmWriter bulk.
  - `drafts/` — article drafts/output to refine before publish.
  - `images/` — VistaCreate exports (cover, social).
  - `imports/` — WordPress CSV import files.
- `pr-stories/` — case studies, press releases, authority pieces.
- `subpages/`
  - `expo/` — for HalalExpoAfrica + HalalExpoHub landers.
  - `kenya/` — HalalKenya lander.
  - `ethiopia/` — HalalEthiopia lander.
  - `eastafrica/` — regional lander.
  - `licensing/` — B2B licensing lander.

**/Common/**
- `tracker/` — CSV tracker + Excel dashboard.
- `quickstarts/` — QuickStart PDFs (Halal + other verticals).
- `sops/` — guides, checklists, API roadmap/flowchart, etc.

> Rule of thumb: **no duplicates**. If a file already exists, update it; don’t create copies with new names.

---

## Workflow (how to add things)

1. **Add/Update Files**
   - Place new files in the **correct folder** above.
   - Name files in lowercase-with-dashes. Example: `hal-q-lite-checklist.pdf`.

2. **Document Changes**
   - If you add a new funnel or section, update **README.md** (structure + domains list).

3. **Commit**
   - Small, clear commits. See messages below.

---

## Commit Message Examples

- `add: halal food checklist pdf v1`
- `update: kenya landing page copy`
- `fix: typos in pr story`
- `chore: add quickstart pdfs to /Common/quickstarts`
- `docs: update README structure + domain roles`

Use **present tense**, keep it **short + specific**.

---

## Content Quality (quick checks)

- Titles are clear and keyword-aligned (SEO).
- Images exported and placed in `/content/images/`.
- Interlink suggestions added inside drafts (2–3 internal links per post).
- Checklists saved as PDFs and referenced in /checklists and on site pages.

---

## Security / Privacy

- Don’t commit API keys or secrets.
- Don’t upload private SME docs; store examples/templates only.
- Use CSVs and templates that are safe to share.

---

## Questions

Not sure where something belongs? Add it to **/Common/sops/** with a short README note, then we’ll place it properly in the next pass.

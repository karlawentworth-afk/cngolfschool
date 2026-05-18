# The Navarino Golf School · Marketing Site

A working marketing site mockup for **The Navarino Golf School for Women**, a proposed exclusive partnership between **Costa Navarino** (Messinia, Greece) and **Ladies Love Golf**.

This is the customer-facing site only. The operational system (questionnaire, profiling engine, workbook generation, coach dashboard) is a separate project.

---

## Purpose

This site exists to:

1. Demonstrate to Costa Navarino leadership how the partnership would look in market
2. Sell the school to high-net-worth women golfers (age 45-65, handicap 18-36)
3. Act as a working sales asset that can be iterated on rapidly

It is **not** the live LLG website. LLG stays exactly as it is. This is a parallel, independent property.

---

## The Two Products

**One Day Intensive · €1,495 per guest**

For resort guests already at Costa Navarino, or arriving for the day. A single day from breakfast to sunset. Pre-arrival psychological profile completed online. Includes coaching, green fee, lunch, mini-workbook, and a thirty-day plan. Eight guests maximum per day. Runs twice weekly in season (Tue/Thu).

This is the funnel. Lower commitment, premium experience, natural lead into the Three Day School.

**Three Day School · from €5,495 per guest**

For guests coming to Costa Navarino specifically for the school. Four nights all-inclusive across three accommodation tiers (Westin €5,495 / Romanos €6,495 / Mandarin Oriental €8,995). Full programme: pre-arrival profile, three days intensive coaching, one-to-one session, four skills stations, graduation dinner, ninety-day follow-on programme with cohort WhatsApp group.

This is where transformation happens. Higher price, deeper outcome, longer relationship.

**Extend your stay:** Both products allow guests to add extra nights at the resort, arranged direct with Costa Navarino.

---

## Brand & Co-Branding Rules

- **Host brand:** Costa Navarino. Their name leads. The school is hosted by them.
- **Methodology partner:** Ladies Love Golf. Credited as the IP and lead coaching provider, positioned the way "Mouratoglou Tennis Center" sits inside Costa Navarino.
- **Tone:** Quiet luxury. Aman / Mandarin Oriental / Conde Nast Traveller. Never "ladies golf clichés", never pink, never marketing fluff.
- **Language:** UK English throughout (colour, programme, organisation). No em dashes (Karla's house rule, it avoids the AI tell).

### Palette (in `:root`)

| Variable     | Hex        | Use                          |
|--------------|------------|------------------------------|
| `--ink`      | `#1a2733`  | Headlines, deep ink          |
| `--sea`      | `#2d4a5f`  | Ionian blue accents          |
| `--sea-deep` | `#16344a`  | Dark feature backgrounds     |
| `--sand`     | `#e8dfd1`  | Sandstone neutrals           |
| `--sand-light`| `#f5efe5` | Warm cream sections          |
| `--olive`    | `#7a8467`  | Kalamata olive (subtle text) |
| `--gold`     | `#b08d57`  | Antique gold accents only    |
| `--paper`    | `#fbf8f2`  | Main page background         |

### Fonts

- Display: **Cormorant Garamond** (serif, often italic for emphasis)
- Body: **Inter** (light weights, generous letter-spacing on labels)

---

## Tech

Pure HTML + CSS in a single `index.html` file. No build step. No framework. No dependencies beyond Google Fonts.

This is deliberate. It means:

- Anyone can edit it without installing anything
- It will run forever, on anything
- Deploys to Netlify in seconds

---

## Local Preview

Just open `index.html` in any browser. Or run a tiny local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## Deployment

This repo deploys to Netlify automatically on every push to `main`.

The `netlify.toml` file in the root tells Netlify how to publish (it just serves the root folder, no build needed).

---

## Project Status

- ✅ Initial design and content
- ✅ Two product offerings (One Day Intensive + Three Day School)
- ✅ Pricing finalised: One Day €1,495 | Three Day from €5,495
- ✅ Extend Your Stay messaging
- ✅ Partnership proposal page (partnership.html, hidden)
- ✅ Board paper page (board.html, hidden)
- ⏳ Real Costa Navarino imagery (currently using custom SVG illustrations to avoid licensing risk during demo phase)
- ⏳ Real testimonials once first cohort runs
- ⏳ Custom domain
- ⏳ Connect form to CRM (currently shows a demo alert)
- ⏳ Working operational system (separate project): questionnaire, profiling engine, workbook generation, coach dashboard

---

## Hidden Pages

Two confidential pages exist alongside the public site. They are NOT linked from the main navigation, are blocked from Google with both meta tags and HTTP headers, and are only accessible by direct URL.

**partnership.html** - One-page partnership proposal for Costa Navarino leadership. Includes full pricing, projected resort revenue, what we need from them, and the format expansion roadmap. Share by URL only.

**board.html** - Board paper for the LLG board. Includes net profit projections, investment required, risk register with mitigations, and the formal board ask. Internal use only. Highly confidential.

Both pages share the visual language of the main site but live as separate HTML files in the project root.

---

## Working With Claude Code

When making changes, please:

1. Preserve UK English spelling
2. **No em dashes**. Use commas, full stops, or rephrase
3. Keep the co-branding hierarchy: Costa Navarino leads, LLG is credited as methodology
4. Maintain the quiet luxury aesthetic, no neon, no pink, no stock-photo clichés
5. Test mobile layout (the site is fully responsive, keep it that way)

---

© 2026 Costa Navarino · Methodology licensed from Ladies Love Golf Ltd

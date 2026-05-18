# Claude Code Context

## Project

Marketing site for **The Navarino Golf School for Women**, a partnership between Costa Navarino (Greece) and Ladies Love Golf (UK).

Single-file HTML site (`index.html`). No build step. Deploys to Netlify on push to `main`.

## The two products

**One Day Intensive** at £1,495 per guest. For resort guests. Pre-arrival profile, then a full day of coaching, lunch, 9 holes on course, 30-day plan. Funnel product.

**Three Day School** from £5,495 per guest, three accommodation tiers:
- The Westin: £5,495
- The Romanos (featured/most popular): £6,495
- Mandarin Oriental: £8,995

Both products allow guests to extend their stay at the resort.

## Owner

Karla, co-founder of Ladies Love Golf, lead on this partnership opportunity with Costa Navarino.

## Hard rules when editing

- **UK English only**: colour, programme, realise, organisation, favour
- **No em dashes (—)**. Karla hates them, they read as AI-generated. Use commas, full stops, parentheses, or rephrase.
- **No hyphens used as em dashes either** (e.g. "she did it - and then..."). Same reason.
- **Tone**: warm, expert, friendly. Plain language. No marketing fluff, no clichés.
- **Co-branding**: Costa Navarino is the host brand and leads visually. LLG is credited as the methodology and lead coaching partner. Do not reverse this.
- **Aesthetic**: quiet luxury (Aman, Mandarin Oriental, Conde Nast Traveller). Cormorant Garamond serif + Inter sans. Palette in `:root` in `index.html`.
- **No pink, no "ladies golf" clichés, no stock-photo cheese.**

## Common tasks

- Update pricing: search for `package-price` in `index.html`
- Update cohort dates: search for `date-month` in `index.html`
- Change a profile card: search for `profile-card` in `index.html`
- Update testimonial: search for `testimonial-quote`

## Before pushing

- Check it still looks right on mobile (open in browser dev tools, 375px width)
- No spelling drift to US English
- No em dashes introduced

## When in doubt

Ask Karla. Don't guess on pricing, dates, or anything that affects the Costa Navarino conversation.

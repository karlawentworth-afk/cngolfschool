# Claude Code Context

## Project

Marketing site for **The Navarino Golf School for Women**, a partnership between Costa Navarino (Greece) and Ladies Love Golf (UK).

Single-file HTML site (`index.html`). No build step. Deploys to Netlify on push to `main`.

## The two products (hotel-as-stage model)

Both products are offered across four hotels at Costa Navarino. The school, coaches, and methodology are identical at every property. Pricing reflects the hotel, not the school.

**One Day Intensive** at four hotels:
- The W Costa Navarino: €1,495
- The Westin: €1,795
- The Romanos (featured/most popular): €2,195
- Mandarin Oriental: €2,795

Pre-arrival profile, then a full day of coaching, lunch, 9 holes on course, 30-day plan. Funnel product.

**Three Day School** at four hotels (4 nights all-inclusive):
- The W Costa Navarino: €4,995
- The Westin: €5,495
- The Romanos (featured/most popular): €6,495
- Mandarin Oriental: €10,495

Three days intensive coaching, one-to-one session, four skills stations, graduation dinner, 90-day follow-on programme.

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

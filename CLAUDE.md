# Seattle Jazz Camp website

Static site (index.html + images/), hosted on Netlify. Every push to `main` deploys automatically.
After any change: commit and push to `main`.

## New registrations — always update BOTH
When the user reports new sign-ups (usually pasted Stripe checkout summaries):

1. **Website** — in `index.html`, lower the instrument's count in the "Currently, we have spots open for" strip
   (`.openings`). Each instrument starts at 2. Any saxophone (alto, tenor, bari) counts as Saxophone.
   Commit and push.
2. **Roster doc** — "Seattle Jazz Camp 2027 Roster": https://claude.ai/artifact/GNUXoretNYNKm4BjSUwd65
   - Add the student to their instrument's table (Student, Grade, Jazz experience, Parent/guardian, Email, Location).
   - Update that instrument's "(N open)" heading and the Summary table (registered / open / totals, lead sentence).

The roster holds families' personal info: keep it out of this repo.

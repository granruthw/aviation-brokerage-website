# Penfield Aviation Insurance — Marketing Site

The marketing website for an AI-native aviation insurance brokerage serving private and business aviation. **Staged dark: this site must not be published until the launch gates below are cleared.**

## Status

- **Copy:** v7 (plain-language pass, 2026-08-17) — final register: intelligent-pilot voice, short declaratives, no insurance jargon. Version history lives in Drive (`Venture Desks (Claude)/ADS-B Brokerage — Business in a Box/website/`, v2–v7) and in this repo's git history going forward.
- **Brand:** Penfield Aviation Insurance was selected for marketing/product/site use on 2026-08-23. Legal-facing and third-party artifacts outside this repo keep `[BRAND]` until counsel clears the name. Remaining launch placeholders: `[FOUNDER-EMAIL]`, `[PHONE]`, `[PRIVACY-POLICY-URL]`, `[FORM-ENDPOINT]`, `[CT-LICENSE-#]`.
- **Compliance posture:** pre-license. No quote CTA, no premium language, no coverage advice. Waitlist capture only, with state dropdown (state-gating built in).

## Launch gates — do not deploy until ALL are cleared

1. **Gate Zero** — employment/IP counsel review complete (precedes anything public).
2. **Brand chosen** and site placeholders replaced.
3. **Ad-review checklist** passed (`compliance/ad-review-checklist` in the Business-in-a-Box) and counsel eyes on marketing claims.
4. **`[FORM-ENDPOINT]`** connected to the waitlist backend (until then the form runs in demo mode).

The **quote CTA stays commented out** (search `FLIP AT LICENSE` in `index.html`) until the CT producer license is issued and verified in the NIPR PDB — issuance, not filing.

## Contents

| Path | What |
|---|---|
| `index.html` | The site — single file, self-contained CSS/JS, no dependencies, no build step |
| `docs/copy-airframe-pages.md` | Education-page copy: SR22, Bonanza, Mooney guides (source for future pages) |
| `docs/seo-plan.md` | Query targets, page map, schema plan, content cadence |
| `prototype/portal-prototype.html` | Client-portal mockup (demo data only; portal ships at ~25 policies per the CX blueprint) |

## Deploying (when gates clear)

Any static host works — Cloudflare Pages, Vercel, Netlify. No build step: deploy the repo root, `index.html` is the entry. Keep the repo **private** until launch. If using GitHub Pages, remember Pages on a private repo still publishes publicly — don't enable it before the gates clear.

## Editing rules

- Voice: explain the mechanism, respect the reader, short declaratives, plain language. No hype, no premium promises, no "free"/"no cost" wording (CGS §38a-825(e)(2)).
- Every copy change goes through the ad-review checklist before deploy and gets archived (git history serves as the ad archive required for market-conduct readiness — meaningful commit messages, please).
- Flight-data scoring is **future/option-shelf only** — it appears solely in the "Where we're headed" card and must not be marketed as a current product until counsel clears it.

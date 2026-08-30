# SEO plan — [DATABRAND]/Penfield Aviation Insurance website

**Posture:** content pages index NOW under [DATABRAND] with no quote CTA (recovers ~6+ weeks of SEO aging before licensure); the quote path and InsuranceAgency schema flip at license. Founder review budget: ≤2 hr/wk (agents draft, founder approves — counts inside the 8 hr/wk marketing cap).

## Target queries (long-tail first; the head terms are owned by incumbents)

| Cluster | Example queries | Page |
|---|---|---|
| Airframe × insurance | cirrus sr22 insurance, sr22 insurance requirements, bonanza insurance cost, v-tail bonanza insurance, mooney m20 insurance | 3 airframe guides (live) |
| Training × insurance | CSIP training insurance discount, BPPP insurance requirement, transition training insurance requirements | Training guide (month 2) |
| Coverage mechanics | smooth limits vs sublimits aircraft, agreed value vs stated value aircraft hull, open pilot warranty explained | Coverage explainers (months 2–3) |
| Ownership moments | first airplane insurance, aircraft insurance at prebuy, insurance for new SR22 owner | Purchase-moment guides (month 3; ties to prebuy-partner channel) |
| Data/safety (brand wedge) | ads-b flight data insurance, flight data safety score aviation | Behavioral-scoring explainer (live, education-only) |

## Page map & sequencing

1. **Live at launch (pre-license):** homepage, 3 airframe guides, how-scoring-will-work explainer, privacy policy. All education-only; every page ends with waitlist capture (state dropdown), never a quote CTA.
2. **Month 2:** smooth-vs-sublimits explainer, training-programs guide. These are the highest-conversion education topics and directly support the proposal template's plain-language flags.
3. **Month 3+:** purchase-moment guides, one data-insight article/month recycled from the newsletter ([DATABRAND] voice).
4. **At license:** /quote intake page goes live (state-gated), airframe pages gain a compliant CTA block, homepage hero updates.

## Schema.org

- **Pre-license:** `Article` on guides; `Organization` for [DATABRAND]; `Person` for founder bio. Do NOT mark up as InsuranceAgency before licensure — the markup is a representation.
- **At license:** add `InsuranceAgency` with license number, `areaServed` limited to licensed states (update as nonresident licenses land), `FAQPage` on explainers.

## Internal linking & authority

- Every airframe page links: scoring explainer → waitlist; sibling airframe pages; (post-license) the quote page.
- Authority strategy is the GTM strategy: type-club forum reputation and the newsletter drive branded search and direct traffic; guides earn organic links from forum citations (never self-spam links — see `gtm/type-club-channel-guide.md` etiquette rules).
- Local: (post-license) Google Business Profile for Penfield Aviation Insurance at KBDR-area address, category Insurance Agency, service area CT — [VERIFY GBP policy for service-area insurance businesses at setup].

## Cadence (inside the 2 hr/wk founder-review budget)

- 1 substantive guide/month (agent-drafted, founder-reviewed 30–45 min, ad-review checklist pass).
- 1 newsletter-derived article/month (15-min review).
- Quarterly: refresh airframe guides ([VERIFY] tags re-checked, market ranges updated), re-run Search Console query review, prune what doesn't rank.

## Measurement

- Search Console + privacy-light analytics (Plausible/Fathom, ~$9–14/mo [VERIFY current pricing]) — no ad pixels pre-license (keeps the compliance surface minimal).
- KPIs: waitlist signups by state (feeds nonresident-license sequencing), airframe-page impressions/clicks, branded-search trend. Report monthly into the GTM review (`gtm/90-day-playbook.md`).

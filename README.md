### Paid

| # | Program | Type | Scope breadth | Reward range | P4 tier? | Triage speed (75% of subs) | Avg payout | Why it fits a beginner |
|---|---------|------|---------------|--------------|----------|----------------------------|------------|------------------------|
| 1 | [The Hut Group Public](https://bugcrowd.com/engagements/hutgroup-public) | Paid bounty | 4 wildcard brands, rated 3/4 | P1 $2,000–2,500, P2 $1,000–1,500, P3 $250–750, P4 $100–200 | Yes | 5 days | $1,200 | Shared codebase across 4 brands, real P4 payouts, live 1.5x XSS bonus |
| 2 | [TheFork](https://bugcrowd.com/engagements/thefork-mbb-og) | Paid bounty | Rated 4/4, `*.tools.thefork.tech` wildcard | Standard P1 $2,500–3,500 down to P4 $150–300, low group P4 $50–100 | Yes | 7 days | $670 | Developer Portal rates every issue P4, a low-competition spot to bank valid low-severity bugs |
| 3 | [TIDAL](https://bugcrowd.com/engagements/tidal-bugbounty) | Paid bounty | `*.tidal.com` plus other wildcards | $100–5,000 overall, per-priority table not public | Not confirmed | 5 days | $491.66 | Familiar consumer product, $100 floor, fast triage |
| 4 | [SEEK](https://bugcrowd.com/seek) | Paid bounty | Full safe harbor | $50–10,000 | Likely (low floor) | 5 days | $477.77 | Lowest reward floor at $50, mature and responsive since going public in 2019 |
| 5 | [NETGEAR Cash Rewards](https://bugcrowd.com/netgear) | Paid + Kudos | IoT hardware and firmware | $150–15,000 | Not confirmed | ~2 months | $337.50 | Awards Kudos even for out-of-scope reports, but slow triage and IoT setup make it a secondary pick |

**Notes:**
- Triage speed and average payout come from each program's rolling "last 3 months" window, so they drift. Verify scope, reward tables, and public status on the live platform before committing time.
- The per-priority reward charts for TIDAL and NETGEAR were not visible on their public pages, only the overall ranges.
- Kudos rank and private-program access run on separate systems. Invites come from valid, high-accuracy submissions with at least one non-duplicate P1–P3 and recent activity, not from leaderboard position.
- Programs 1 and 2 are the strongest starting points because they pair genuine wildcard scope with explicit P4 tiers and fast validation.

### Unpaid

| Program | Sector | Safe harbor | Public disclosure | Scope note | Beginner value |
|---|---|---|---|---|---|
| [Dept. of the Interior VDP](https://bugcrowd.com/doi-vdp) | US federal gov | Full | Coordinated only | Very wide federal attack surface | Huge scope, mandated under BOD 20-01, stable and long-running |
| [USDA VDP](https://bugcrowd.com/usda-vdp) | US federal gov | Full | Coordinated only | Broad `.usda.gov` estate | Large surface, low competition versus paid programs |
| [FDIC VDP](https://bugcrowd.com/fdic-vdp) | US federal gov | Full | Coordinated only | Financial-regulator web assets | Full safe harbor, clear standard disclosure terms |
| [Dreamscape (Newfold Digital) VDP](https://bugcrowd.com/newfold-dreamscape-vdp) | Private, hosting | Full | Not allowed | Web app | Active program, 78 hall of famers and 236 recently joined |
| [Domain VDP](https://bugcrowd.com/domain-vdp-pro) | Private, property | Full | Not allowed | Australian property marketplace brands | Full safe harbor, single commercial web target |
| [Plusgrade VDP](https://bugcrowd.com/plusgrade-vdp-pro) | Private, travel | Full | Not allowed | Travel/loyalty web platform | Full safe harbor, focused scope you can map fully |

**Notes:**
- Government VDPs give the widest practice ground, but you must stay strictly inside listed scope and rules of engagement. Nothing that could degrade or disrupt a service.
- Check safe harbor wording per program. The [Regions Bank VDP](https://bugcrowd.com/regions-vdp) lists only partial safe harbor. Prefer full safe harbor programs and read the policy first.
- The three private programs do not allow public disclosure. The government ones use coordinated disclosure, so wait for validation, remediation, and explicit approval before any public mention.
- Accessible bug classes for a beginner: broken access control and IDOR, reflected and stored XSS, open redirects, CSRF, security misconfiguration, and information disclosure.
- Program availability changes and some pages were cached. Confirm each is live and open before investing time. Since these pay nothing, treat them as a reputation and skill step, then pivot to paid programs where the same skill tag converts into private invites and money.
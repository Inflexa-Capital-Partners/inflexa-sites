# Roadmap for the next agent

Starting point is live. Improve in small, reviewable PRs.

## Quick public wins
1. **NDA CTA** — wire founding-partner / NDA step to a real `mailto:` (or form); today there is no contact path.
2. **Meta / Open Graph** — add `description`, `og:title`, `og:description`, `og:image` (candidate: `assets/hero-mountain.jpg`) so link previews aren’t empty.
3. **Favicon** — none yet.
4. **README** — keep the root README as the human + agent entry (structure, URLs, what not to commit).

## Content upgrades (from internal website checklist)
Align teaser sections with the internal “website checklist” themes (without pasting confidential numbers into the public page until Ian approves):
- Hero: optional emphasis that most of the return is contractual / structured
- Why hybrid / why now: four forces (third capital box, bank retreat, 2027–2030 refi wave, thinned field)
- Approach: “risk first, then return” + selectivity framing
- Payoff visual: ensure artwork is original (no third-party chart imagery)

## Structure (later)
- Split the monolithic `index.html` (~700KB inline) into `css/` + `js/` + `assets/` once iteration speed matters
- Add further pages only when messaging is ready (not a brochure dump)

## Guardrails
- Repo is **public**
- No term sheets, fee tables, LP names, or track-record workbooks in git
- Fund I legal / terms → Inflexa Capital agent, not this repo
- Auth for git/API: `INFLEXA_GITHUB_PAT` (never print it)

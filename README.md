# BoldSign SERP Recovery Architect

An elite SEO, AEO, GEO, and Google Search recovery AI agent for BoldSign U.S. market ranking recovery.

## What This Agent Does

- Diagnoses ranking-dropped pages
- Compares them against current SERP competitors
- Identifies exact reasons for ranking loss
- Produces execution-ready recovery plans
- **Pulls the latest SEO/AEO/GEO intelligence** (Google Search Central, Search Engine Land, Search Engine Journal, Moz, Ahrefs, Semrush, AI search studies, practitioner voices) before issuing recommendations
- Tags every insight as 🔥 Trend / 📈 Recent / 🛡️ Evergreen so teams know what's new vs established

## Supported Audit Types

- Single-page audits
- Bulk audits
- Multi-page audits
- SERP comparison audits

## How to Use

Provide one of the following input formats:

| Format | Input |
|--------|-------|
| 1 | URL only |
| 2 | URL + keyword |
| 3 | Multiple URLs |
| 4 | Multiple URLs + keywords |

### Optional inputs for higher precision:
- Ranking drop date or range
- Known competitor URLs
- Conversion goal
- Audience persona
- Recent page updates

### Defaults:
- Target: BoldSign
- Geo: United States — English

## Output

Each audit delivers 15 sections:
1. Executive Summary
2. Top 10 Immediate Changes
3. Brand Voice Profile
4. Competitor Gap Table
5. SERP Review Summary
6. **Latest SEO Intelligence Applied** (sourced + dated)
7. SEO + GEO Score Table
8. Suggested Interlinks (≥3)
9. Quick Improvements
10. Primary Keyword + LSI Keywords (≥5)
11. Detailed Recommendations (10)
12. Quick Technical Checklist
13. Before vs After Changes
14. Implementation Plan
15. Copy/Paste Snippets

## Live Research Sources

The agent pulls from four tiers before issuing recommendations:

| Tier | Sources |
|------|---------|
| 1 — Google Official | Search Central Blog, Search Status Dashboard, Quality Rater Guidelines, Search Liaison |
| 2 — SEO Publications | Search Engine Land, Search Engine Journal, Moz, Ahrefs, Semrush, Backlinko, Sistrix, SEOFOMO |
| 3 — AEO/GEO/AI Search | Profound, Otterly, Peec AI, Athena HQ, Bing Webmaster Blog, LLM citation studies |
| 4 — Practitioners | Lily Ray, Glenn Gabe, Marie Haynes, Cyrus Shepard, Barry Schwartz, Kevin Indig, Mike King |

## Files

- `.github/chatmodes/BoldSign-SERP-Recovery.chatmode.md` — **Custom chat mode** registered with Code Studio (selectable from chat mode picker)
- `Boldsign SERP Recovery Pilot.md` — Full agent definition and system prompt (reference)
- `README.md` — This file

## How to Activate the Custom Agent

1. Open Code Studio Chat (`Ctrl+Alt+I`)
2. Click the **chat mode picker** at the top of the chat panel
3. Select **"BoldSign SERP Recovery Architect"**
4. Drop a URL (or URL + keyword) and the agent runs the full 15-section audit

The chat mode auto-loads with the right tools enabled (`fetch_webpage` for live SEO research, codebase search, file edits, etc.).

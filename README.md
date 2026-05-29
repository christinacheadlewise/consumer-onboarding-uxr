# Consumer Onboarding UXR

Research findings from the Consumer Onboarding team. This repo is designed so anyone on the team can ask Claude questions about our research without needing direct data access.

## How to use

1. Open this project in Claude Code (or open the folder in VS Code with the Claude Code extension)
2. Ask your question in plain language — e.g. "What were the main reasons people didn't convert?" or "How does signup difficulty relate to LTV?"
3. Claude will answer from the pre-computed findings

## What you can ask

- What surveys found (distributions, themes, comparisons)
- How friction points relate to lifetime revenue
- What behavioural data shows about adoption
- Methodology, sample size, limitations
- Whether a specific finding is statistically significant

## What Claude won't do

- Show raw data or individual responses
- Run new statistical analysis or queries
- Access Snowflake, CSV files, or any data source
- Create new charts or custom cuts

If your question isn't covered by the existing findings, Claude will give you a formatted message to paste into the relevant Slack thread. The research team will pick it up from there.

## Why it works this way

Surveys contain responses from real customers with user_ids attached. Restricting raw data access ensures we handle it responsibly while still making the insights broadly available to eng, product, and design.

---

## Studies

### [Consumer Drop-off Survey 2025](docs/index.md)

- **Question:** Why don't new consumers convert within 30 days?
- **Data collected:** 22 Oct – 25 Nov 2025
- **Sample:** 1,331 cleaned responses (US, UK, Philippines)
- **Enrichment:** Matched to Snowflake LTV + onboarding flow data
- **Live site:** [christinacheadlewise.github.io/consumer-dropoff-survey-2025](https://christinacheadlewise.github.io/consumer-dropoff-survey-2025/)
- **Skill:** `.claude/skills/dropoff-survey-insights.md`

---

## Team

**Consumer Onboarding** · Staff Researcher: Christina Cheadle

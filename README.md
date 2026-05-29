# Consumer Onboarding UXR

**Christina Cheadle** · Staff Design Researcher · Consumer Onboarding

This is the research repository for the Consumer Onboarding team at Wise. It contains findings from completed studies, along with Claude skills that let anyone on the team query those findings without accessing raw data.

## How to use this repo

### Reading findings

Browse the [live site](https://christinacheadlewise.github.io/consumer-onboarding-uxr/) or read the markdown in `docs/`.

### Asking questions with Claude

1. Clone this repo (or open it in VS Code with Claude Code)
2. Ask questions in plain language — Claude answers from pre-computed findings only
3. It won't access raw data, run queries, or do new analysis
4. If it can't answer, it'll give you a message to paste in Slack so I can pick it up

The skill files live in `.claude/skills/`. You can also [download them individually](https://raw.githubusercontent.com/christinacheadlewise/consumer-onboarding-uxr/main/.claude/skills/dropoff-survey-insights.md) and drop into any project's `.claude/skills/` folder.

### Why no raw data?

Surveys contain responses from real customers with user_ids. Restricting access ensures we handle it responsibly while making insights available to eng, product, and design.

---

## Studies

| Study | Collected | Sample | Folder |
|---|---|---|---|
| [Consumer Drop-off Survey 2025](Consumer%20Onboarding%20Survey%202025/) | Oct–Nov 2025 | 1,331 (US, UK, PH) | `Consumer Onboarding Survey 2025/` |

---

## Repo structure

```
├── README.md                          ← you are here
├── docs/                              ← GitHub Pages site (findings)
├── .claude/skills/                    ← Claude skill files (active)
└── Consumer Onboarding Survey 2025/   ← study folder
    ├── README.md                      ← study overview + top findings
    └── dropoff-survey-insights.md     ← skill source
```

As new studies are completed, they'll be added as new folders with their own skill files.

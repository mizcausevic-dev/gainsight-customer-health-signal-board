# gainsight-customer-health-signal-board

Board-readable Kinetic Gain proof repo for **Gainsight** platform and company signal coverage.

## Product thesis

Customer health scores often fail to explain which risks are real, which accounts are recoverable, and where expansion is blocked.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** Customer success leaders, revenue strategists, renewals teams, and SaaS operators
- **Signal domain:** Customer Success
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product ties health score movement, adoption gaps, renewal posture, playbook ownership, and executive escalation into one lane.
- **Value architecture:** Leaders can decide where to save revenue, where to invest in expansion, and where churn risk is already priced in.

## What this repo proves

- **Normalize:** messy Gainsight operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: Gainsight health scores, CTAs, adoption metrics, renewals, playbooks, and escalation notes.

This is synthetic proof only. It does not connect to live Gainsight tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- Gainsight
- customer health
- renewal risk
- customer success
- SaaS retention

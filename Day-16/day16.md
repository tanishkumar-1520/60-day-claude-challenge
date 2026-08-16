# Day 16 — Stock Fundamental Research Custom Skill

## Objective

Create a reusable Claude Custom Skill named `stock-fundamental-research` for evidence-based fundamental research on listed companies.

## Skill Name

`stock-fundamental-research`

## Description

Analyze Indian and global listed companies using fundamentals, financial statements, business quality, competitive advantages, valuation, risks, and growth prospects. Generate evidence-based research reports and investor-friendly summaries. Never provide direct buy, sell, or hold recommendations.

## Task Workflow

- Read the provided skill specification.
- Open Claude.
- Set effort level to Low or Medium.
- Navigate to Skills.
- Create a Custom Skill.
- Enter the skill name and description.
- Paste the supplied instructions.
- Save the skill.
- Test the skill with TCS.
- Generate a fundamental research report.
- Review valuation, charts, ownership and risks.
- Test that the skill can be reused without repasting the full prompt.
- Document the work.

## Test Stock

**Tata Consultancy Services Ltd (TCS)**

## Research Highlights

- Market cap: approximately ₹8.56 lakh crore in the retrieved Tickertape snapshot.
- P/E: approximately 17.4x.
- P/B: approximately 7.9x.
- ROE: approximately 48.2%.
- ROCE: approximately 55.5%.
- Debt/equity: approximately 0.10.
- Promoter holding: 71.77% in June 2026.
- Q1 FY27 consolidated revenue: ₹72,275 crore.
- Q1 FY27 TCV: US$9.5 billion.
- Annualized AI revenue: US$2.6 billion.
- FY2026 operating cash flow: ₹52,094 crore.
- FY2026 free cash flow: approximately ₹47,870 crore from the retrieved financial-data source.

## Key Learnings

### 1. Reusable AI Skill

A Custom Skill turns a long research prompt into a reusable workflow.

### 2. Source Validation

Important financial figures should be cross-checked using multiple sources.

### 3. No Fabrication

When live data is unavailable or inconsistent, the report should explicitly flag the limitation.

### 4. Neutral Research

A good stock-analysis skill can provide detailed evidence without giving a buy, sell or hold recommendation.

### 5. Charts

Price charts make stock performance easier to understand visually.

### 6. Ownership Analysis

Promoter, FII and DII trends can provide useful context around ownership changes.

### 7. Risk Analysis

Fundamental research should include both business strengths and risks.

## Screenshots to Capture Manually in Claude

1. `01-skill-created.png` — Skill name and description.
2. `02-skill-instructions.png` — Skill instructions.
3. `03-tcs-quick-take.png` — TCS Quick Take.
4. `04-tcs-deep-dive.png` — Detailed TCS report.
5. `05-tcs-price-chart.png` — Price chart.
6. `06-tcs-valuation.png` — Valuation section.
7. `07-tcs-ownership.png` — Ownership trends.
8. `08-tcs-risks.png` — Risks/watch points.
9. `09-skill-reuse.png` — Reusing the skill with a new stock prompt.

## Files

```text
Day16/
├── day16.md
├── stock-fundamental-research-skill.md
├── tcs-fundamental-research-report.md
└── screenshots/
    ├── 01-skill-created.png
    ├── 02-skill-instructions.png
    ├── 03-tcs-quick-take.png
    ├── 04-tcs-deep-dive.png
    ├── 05-tcs-price-chart.png
    ├── 06-tcs-valuation.png
    ├── 07-tcs-ownership.png
    ├── 08-tcs-risks.png
    └── 09-skill-reuse.png
```

## External-Step Limitation

Claude's logged-in UI and the user's GitHub account cannot be operated from this environment. Therefore, Claude screenshots, Custom Skill creation inside Claude, and the final GitHub push must be completed manually.

## GitHub Submission

**Commit URL:** `[PASTE GITHUB COMMIT URL HERE]`

## Disclaimer

This is a view of the fundamentals for educational purposes only. It is not investment advice and not a buy/sell/hold recommendation. Verify all figures independently. The final decision is yours.

# Day 48 — The Verdict Engine

## Project Title

**The Verdict Engine — Compare & Decide Builder**

## Challenge

60 Days Claude AI Challenge by ABTalks

## Objective

The goal of Day 48 was to build a research-oriented decision-making application that helps college students compare laptops using multiple measurable criteria and customizable priorities.

The application was designed to make comparisons more structured by combining criteria weights, normalized scores, source visibility, and research notes into one interface.

## Decision Category

**Laptops**

## Target User

**College Students**

The tool is intended to help students compare laptops based on factors that can affect study, coding, projects, portability, and everyday academic use.

## Selected Criteria

The decision model uses six criteria:

1. Price
2. Performance
3. Battery Life
4. Display Quality
5. RAM / Storage
6. Weight / Portability

## Data Source Strategy

The project was designed around a combination of:

* Official manufacturer specifications
* Independent laptop review sources
* Benchmark and measurement sources where appropriate
* Named and visible citations for researched information

The interface also distinguishes between sourced information and synthetic demonstration data.

## Application Features

### 1. Criteria Weighting

Users can adjust the importance of each criterion using sliders.

The application calculates a composite score using the selected weights.

### 2. Live Ranking

When the weights change, laptop rankings are recalculated automatically.

This allows users to see how different priorities can change the outcome of a comparison.

### 3. Weight Locking

After selecting the desired priorities, the user can lock the criteria weights.

Once locked, the sliders become disabled and the decision model remains fixed until the user unlocks it.

### 4. Sources Panel

A dedicated Sources panel lists the sources used by the research model.

The interface is designed so that users can inspect the evidence behind the comparison instead of seeing unexplained scores.

### 5. Research Methodology

The application includes a collapsible **"How this was researched"** section.

It explains:

* What each criterion means
* How different types of sources can disagree
* Why manufacturer and independent battery measurements can differ
* Why laptop configurations must be matched
* Why prices can change over time and by region

### 6. Data Status

The application clearly marks the demonstration dataset as:

**Synthetic demonstration**

This prevents demonstration values from being mistaken for verified current market data.

## Decision Model

The application uses a weighted scoring model.

```text
Composite Score =
Σ (Criterion Score × Criterion Weight)
```

The resulting composite scores are used to create the live comparison ranking.

The model is intended as a transparent decision-support mechanism rather than an absolute product rating.

## User Workflow

1. Open the Verdict Engine application.
2. Review the laptop comparison data.
3. Adjust the criteria weights according to personal priorities.
4. Ensure the total weight equals 100%.
5. Observe the ranking update live.
6. Review individual comparison metrics.
7. Open the Sources panel.
8. Review the citation information.
9. Open the "How this was researched" panel.
10. Review methodology and potential source conflicts.
11. Lock the selected criteria weights.
12. Capture screenshots for the Day 48 submission.

## Claude Workflow

The project was developed following the Day 48 workflow:

1. Read the provided resources.
2. Watch the solution video.
3. Open Claude.
4. Set Claude effort level to Low.
5. Start a new conversation.
6. Paste the The Verdict Engine prompt.
7. Answer Claude's interview questions one at a time.
8. Select laptops as the comparison category.
9. Select college students as the target audience.
10. Select six decision criteria.
11. Select mixed official and independent sources.
12. Select customizable criteria weighting with locking.
13. Generate the complete HTML application.
14. Save the generated HTML file.
15. Open the application locally in a browser.
16. Test the weighting controls and live ranking.
17. Review the sources panel.
18. Review the research methodology panel.
19. Capture screenshots.
20. Prepare the Day 48 GitHub folder.
21. Upload the project files and screenshots.
22. Commit and push the changes.

## Files

The Day 48 folder contains:

```text
Day48/
├── verdict-engine.html
├── day48.md
├── key-learnings.md
├── sourced-data-report.md
└── screenshots/
    ├── dashboard.png
    ├── weight-adjustment.png
    ├── sources-panel.png
    └── research-panel.png
```

## Testing Completed

The following application flows were tested:

* Laptop comparison dashboard
* Criteria weight sliders
* Weight percentage updates
* Total weight calculation
* Live ranking recalculation
* Invalid total-weight state
* Criteria locking
* Criteria unlocking
* Sources panel
* Research methodology panel
* Responsive layout
* Mobile layout
* Synthetic data status indicators

## Key Outcome

Day 48 demonstrated how a decision-support interface can make the reasoning behind a comparison more transparent.

Instead of showing only a final result, the Verdict Engine exposes the criteria, weighting model, comparison data, sources, and research methodology so that users can understand how the result was produced.

## GitHub Submission

The completed Day 48 project should be committed and pushed to the GitHub repository under:

```text
Day48/
```

After pushing the files, submit the **GitHub commit URL** as the final Day 48 submission.

## Note

The included HTML demonstrates the decision-engine interface and weighted-ranking logic. Any synthetic demonstration values should be replaced with verified, current, date-stamped research data before using the application for an actual laptop purchasing decision.

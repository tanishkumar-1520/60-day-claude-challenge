# Day 18 — Brain Dump Action Planner Custom Skill

## Objective
Create a reusable Claude Custom Skill named `brain-dump-action-planner` that converts messy notes, transcripts, voice memos, brainstorming and project discussions into structured summaries and action dashboards.

## Skill
**Name:** `brain-dump-action-planner`

**Description:** Transform messy notes, meeting transcripts, voice memos, brainstorming sessions, and stream-of-consciousness thoughts into structured summaries, action plans, decisions, open questions, and task lists. Organize information clearly without inventing, assuming, or filling gaps. Preserve all names, dates, numbers, and terminology exactly as provided.

## Test
No dedicated meeting transcript was available in the provided resources, so the Notes Management System project information was used as a project-discussion-style test.

The source describes create, edit, delete and filter functionality and technology references. fileciteturn0file0L43-L65 fileciteturn0file7L882-L903

## Dashboard
`brain-dump-action-planner-dashboard.html`

Includes Summary, Key Takeaways, Action Items, Open Questions, Risks/Blockers, Conflicts, Additional Notes, Source Information, badges, responsive cards and collapsible sections.

## Key Learnings
1. Custom Skills make long workflows reusable.
2. Brain dumps become easier to execute when separated into actions, questions, risks and conflicts.
3. Missing owners/deadlines must remain `Not specified`.
4. Interactive HTML dashboards improve scanning and organization.
5. The skill can be reused with prompts such as `Organize these meeting notes` without repasting all instructions.

## Claude Screenshots to Capture
- `01-skill-created.png` — Skill name and description.
- `02-skill-instructions.png` — Instructions.
- `03-dashboard-summary.png` — Summary and takeaways.
- `04-dashboard-actions.png` — Action items.
- `05-dashboard-risks.png` — Risks/blockers/conflicts.
- `06-dashboard-responsive.png` — Mobile view.
- `07-skill-reuse.png` — Reusing the skill with another note format.

## GitHub Structure
```text
Day18/
├── day18.md
├── brain-dump-action-planner-skill.md
├── test-project-notes.md
├── brain-dump-action-planner-dashboard.html
└── screenshots/
    ├── 01-skill-created.png
    ├── 02-skill-instructions.png
    ├── 03-dashboard-summary.png
    ├── 04-dashboard-actions.png
    ├── 05-dashboard-risks.png
    ├── 06-dashboard-responsive.png
    └── 07-skill-reuse.png
```

## External Steps
Claude's logged-in UI and GitHub account cannot be operated from this environment. Create the Custom Skill, capture Claude screenshots, commit and push manually.

**GitHub Commit URL:** `[PASTE COMMIT URL HERE]`

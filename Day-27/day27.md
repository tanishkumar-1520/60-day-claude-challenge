# Day 27 — Prior Authorization Story Simulator

## Objective

Build and test a single-file, beginner-friendly interactive story simulator that teaches the prior authorization journey through Rahul (patient) and Priya (healthcare operations specialist).

## Task completed

- Reviewed the Day 26 project context and the provided Prior Authorization Workflow Simulator resources.
- Used the Day 26 design language as the visual reference: blue healthcare education UI, rounded cards, progress tracking, and explanatory panels.
- Created a self-contained `prior-authorization-story-simulator.html` using HTML, Tailwind CSS CDN, and vanilla JavaScript.
- Implemented an append-only chat feed using `createElement` + `appendChild` for new chat bubbles; the chat container is never assigned with `innerHTML`.
- Added eight story chapters with two choices after each scene.
- Added Rahul on the left and Priya on the right; narrators are centered italic text.
- Added a live eight-chapter progress bar and chapter tracker.
- Covered provider → PA request → illustrative StarCare Health payer flow, with no pharmacy in the submission path.
- Explained PA, eligibility, clinical documentation, ICD-10 diagnosis matching, step-therapy history, denial, appeal, Letter of Medical Necessity, approval, and reference number.
- Added patient and system takeaways covering denial rate, appeal rate, and resolution time.
- Added restart functionality so different dialogue paths can be explored.

## Important content note

StarCare Health is explicitly presented as an illustrative example. The application is educational and does not provide medical or insurance advice.

For the evidence note, the app references the AMA's 2023 prior authorization survey finding that 94% of physicians reported PA delayed access to necessary care. The AMA also reported substantial administrative burden associated with PA. Source: AMA prior authorization survey materials.

## Files

- `prior-authorization-story-simulator.html` — complete interactive application.
- `day27.md` — task notes, implementation summary, and learnings.
- `screenshots/` — place browser screenshots of key scenes here before the GitHub commit.

## Suggested screenshots

1. `screenshots/01-doctor-visit.png` — Chapter 1 opening scene.
2. `screenshots/02-what-is-pa.png` — Chapter 3 explanation and AMA evidence note.
3. `screenshots/03-denial.png` — Chapter 5 denial and appeal explanation.
4. `screenshots/04-approval.png` — Chapter 7 approval and reference number.
5. `screenshots/05-takeaways.png` — Chapter 8 patient/system takeaways.

## Key learnings

- Prior authorization is easier to understand when the workflow is presented as a patient story instead of only as an administrative checklist.
- A denial is not necessarily the end of the process; the next action should directly address the payer's stated reason.
- Documentation quality matters because eligibility, diagnosis coding, clinical evidence, and treatment history answer different review questions.
- Patient education should explain both the clinical stakes and the operational workflow without implying that every payer uses identical rules.
- System-level metrics such as denial rate, appeal rate, and resolution time can reveal where administrative friction is occurring.
- A restartable branching story makes it easier for beginners to explore alternate dialogue paths while preserving the same eight-stage learning arc.

## GitHub checklist

- [ ] Create `Day27/` folder.
- [ ] Add `day27.md`.
- [ ] Add `prior-authorization-story-simulator.html`.
- [ ] Add five key browser screenshots under `Day27/screenshots/`.
- [ ] Commit the Day 27 changes.
- [ ] Push to GitHub.
- [ ] Copy the GitHub commit URL for submission.

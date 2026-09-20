# CareerLaunch AI — Implementation Blueprint (Days 2–10)

This document is the single source of truth for the remaining capstone days. Each day begins with a fresh AI conversation. Preserve the existing product scope and do not introduce major architectural changes without a clear need.

## Day 2 — Product Design & User Flow
### 🎯 Objective
Turn the approved requirements into a complete screen-by-screen user journey.
### 📖 What I'll learn
User flows, information architecture, wireframing, states, and acceptance criteria.
### 🛠 Features to build
Onboarding, target-role input, analysis, profile review, gaps, recommendations, interview practice, dashboard.
### 📝 Step-by-step
1. Define the primary happy path.
2. Define navigation between stages.
3. Define empty/loading/error/completed states.
4. Define mobile behavior.
5. Create a screen inventory and component inventory without changing scope.
### 📂 Files/folders
Create the project structure and design/reference documentation required by the chosen implementation approach.
### 🔗 Integrations
None required today.
### 🧪 Testing
Walk through the user journey and verify every v1.0 requirement has a destination.
### 🐞 Issues
Watch for duplicate screens, unclear navigation, and features outside scope.
### ✅ Checklist
Flow documented; all v1.0 features mapped; exclusions preserved.
### 📸 Screenshots
Capture the approved flow/design reference.
### ➡️ Handoff
Day 3 should implement the agreed structure without redesigning the product.

## Day 3 — Foundation & Core Shell
### 🎯 Objective
Create the working product shell and foundational interaction model.
### 📖 What I'll learn
Project setup, reusable UI structure, state management, and responsive foundations.
### 🛠 Features
Navigation, onboarding, base layout, shared components, data model.
### 📝 Plan
1. Initialize the project using the implementation approach selected with the AI on this day.
2. Build the app shell.
3. Add reusable form/card/button/status patterns.
4. Add initial sample data.
5. Make the shell responsive.
### 📂 Files/folders
Create/modify the project source, assets, documentation, and configuration files required by the selected approach.
### 🔗 Integrations
No paid service required.
### 🧪 Testing
Load the product, navigate all shell routes/states, test desktop/mobile widths.
### 🐞 Issues
Broken navigation, inconsistent state, layout overflow.
### ✅ Checklist
App starts; navigation works; responsive shell works.
### 📸 Screenshots
Onboarding and main shell.
### ➡️ Handoff
Day 4 builds the target-job workflow on this foundation.

## Day 4 — Target Job Analysis
### 🎯 Objective
Build the job-description input and analysis experience.
### 📖 What I'll learn
Structured text processing, requirement extraction, and explainable results.
### 🛠 Features
Job description entry, extracted responsibilities, skills, keywords, role summary.
### 📝 Plan
1. Add job-description input.
2. Add validation and sample role.
3. Process the input into structured requirements.
4. Display requirements in readable sections.
5. Add loading/error/empty states where applicable.
### 📂 Files/folders
Modify job-analysis views, processing logic, sample data, and tests.
### 🔗 Integrations
Keep the implementation compatible with the approved no-paid-service constraint.
### 🧪 Testing
Short/long descriptions, missing input, unusual formatting, sample role.
### 🐞 Issues
Overly broad extraction; unclear labels; failure on empty input.
### ✅ Checklist
User can enter a job and understand its requirements.
### 📸 Screenshots
Input and analysis results.
### ➡️ Handoff
Day 5 compares the role with the user's profile.

## Day 5 — Profile & Skill-Gap Analysis
### 🎯 Objective
Create a useful comparison between the target role and the user's current profile.
### 📖 What I'll learn
Matching logic, prioritization, and presenting gaps without misleading certainty.
### 🛠 Features
Profile/resume information, strengths, missing skills, priority gaps, improvement suggestions.
### 📝 Plan
1. Add profile input/import supported by the chosen implementation.
2. Normalize profile skills.
3. Compare against role requirements.
4. Separate strengths from gaps.
5. Prioritize gaps into actionable categories.
### 📂 Files/folders
Modify profile, comparison, recommendation, and data/state modules.
### 🔗 Integrations
No paid integration required.
### 🧪 Testing
Exact matches, partial matches, missing skills, empty profile, duplicate skills.
### 🐞 Issues
Do not claim that a match guarantees hiring.
### ✅ Checklist
Comparison is understandable and actionable.
### 📸 Screenshots
Profile review and gap report.
### ➡️ Handoff
Day 6 turns gaps into an action plan.

## Day 6 — Personalized Action Plan
### 🎯 Objective
Convert identified gaps into a practical improvement roadmap.
### 📖 What I'll learn
Prioritization, task modeling, progress states, and user feedback loops.
### 🛠 Features
Prioritized actions, learning/practice tasks, completion states, progress indicators.
### 📝 Plan
1. Convert top gaps into actions.
2. Group actions by priority.
3. Add completion state.
4. Calculate simple progress.
5. Add reset/edit behavior.
### 📂 Files/folders
Modify recommendation, action-plan, progress, and persistence/state files.
### 🔗 Integrations
No paid service required.
### 🧪 Testing
Complete/uncomplete actions, empty action list, restart, refresh/state persistence if implemented.
### 🐞 Issues
Avoid overwhelming users with too many tasks.
### ✅ Checklist
Every major gap can become a concrete next step.
### 📸 Screenshots
Action plan and progress state.
### ➡️ Handoff
Day 7 adds role-specific interview preparation.

## Day 7 — Interview Practice
### 🎯 Objective
Build a focused interview practice experience.
### 📖 What I'll learn
Question generation/selection, answer evaluation UX, and practice flows.
### 🛠 Features
Role-specific questions, answer input, feedback, progress.
### 📝 Plan
1. Create question categories.
2. Generate/select questions based on the target role.
3. Add one-question-at-a-time practice.
4. Add feedback criteria.
5. Add completion summary.
### 📂 Files/folders
Modify interview UI, question data/logic, evaluation, and progress modules.
### 🔗 Integrations
If an AI integration is used, keep it optional and avoid paid dependencies.
### 🧪 Testing
Multiple question types, empty answers, restart, completion.
### 🐞 Issues
Feedback must be framed as practice guidance rather than guaranteed interview scoring.
### ✅ Checklist
User can complete a meaningful practice session.
### 📸 Screenshots
Question, answer/feedback, and completion screens.
### ➡️ Handoff
Day 8 integrates all modules into the final dashboard.

## Day 8 — Dashboard & End-to-End Integration
### 🎯 Objective
Connect the complete workflow into a coherent product.
### 📖 What I'll learn
Integration testing, derived metrics, and product polish.
### 🛠 Features
Readiness/progress dashboard, summaries, navigation between modules, restart/update role.
### 📝 Plan
1. Connect job, profile, gaps, actions, and interview states.
2. Create summary metrics.
3. Add dashboard cards.
4. Add clear next-step CTA.
5. Verify full user journey.
### 📂 Files/folders
Modify dashboard, shared state/data, navigation, and integration tests.
### 🔗 Integrations
Only approved integrations.
### 🧪 Testing
Full end-to-end happy path plus major edge cases.
### 🐞 Issues
Inconsistent state between screens; stale summaries.
### ✅ Checklist
The product feels like one application rather than separate demos.
### 📸 Screenshots
Dashboard and complete workflow.
### ➡️ Handoff
Day 9 focuses on testing, accessibility, responsiveness, and polish.

## Day 9 — Testing, UX & Deployment Preparation
### 🎯 Objective
Make the product reliable and presentation-ready.
### 📖 What I'll learn
QA, accessibility basics, responsive testing, deployment preparation.
### 🛠 Features
Bug fixes, responsive polish, validation, accessibility improvements, final sample data.
### 📝 Plan
1. Test all primary flows.
2. Test mobile and desktop.
3. Test keyboard/focus and readable labels.
4. Fix visual inconsistencies.
5. Remove debug content.
6. Prepare deployment configuration.
### 📂 Files/folders
Modify source, tests, documentation, configuration, and deployment files as needed.
### 🔗 Integrations
Verify all dependencies work in the deployment environment.
### 🧪 Testing
Regression test every v1.0 acceptance criterion.
### 🐞 Issues
Broken production paths, missing assets, environment-specific failures.
### ✅ Checklist
No known blocker remains; product is deployment-ready.
### 📸 Screenshots
Mobile, desktop, key final screens.
### ➡️ Handoff
Day 10 deploys and validates the final product.

## Day 10 — Deployment, Final QA & Demo
### 🎯 Objective
Deploy the polished v1.0 and produce evidence of completion.
### 📖 What I'll learn
Deployment, production validation, demo storytelling, maintenance thinking.
### 🛠 Features
Final deployed product, demo flow, final documentation.
### 📝 Plan
1. Deploy using a free deployment option compatible with the chosen stack.
2. Open the production URL.
3. Run the full user journey.
4. Fix only deployment/blocking issues.
5. Capture final screenshots.
6. Record final limitations and future scope.
7. Prepare the capstone demonstration.
### 📂 Files/folders
Update README/deployment documentation and final project records.
### 🔗 Integrations
Only integrations already approved.
### 🧪 Testing
Production smoke test and complete acceptance checklist.
### 🐞 Issues
Environment variables, routing, asset paths, mobile layout.
### ✅ Checklist
Live URL works; v1.0 flow works; screenshots captured; documentation complete.
### 📸 Screenshots
Production landing/onboarding, analysis, gap report, action plan, interview, dashboard, and deployed URL.
### ➡️ Handoff
Capstone is complete; future enhancements become post-v1.0 work.

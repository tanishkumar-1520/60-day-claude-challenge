# Day 26 — Prior Authorization Workflow Simulator

## Objective
Built a single-file, self-contained Prior Authorization Workflow Simulator using HTML, CSS, and vanilla JavaScript.

## Features completed
- Three workflow lanes: Patient, Provider, and Payer.
- Drag-and-drop case movement.
- Four patient scenarios: elective surgery, MRI, specialty medication, and inpatient admission.
- Medical necessity evaluation.
- Required PA document checklist.
- Payer submission flow.
- Approval, Pend, Denial, Appeal, and Peer-to-Peer Review outcomes.
- Educational explanation after each major step.
- Journey tracker and elapsed-days counter.
- Efficiency score.
- Approval celebration animation.
- Workflow completion summary.
- Restart / New Patient controls.
- Responsive blue UI with black text.
- No frameworks, CDNs, localStorage, or build step.
- Scenario data is stored in an editable JavaScript array near the top of the file.

## Workflow tested
1. Start a new patient.
2. Move the case from Patient to Provider.
3. Evaluate medical necessity.
4. Complete all required documents.
5. Submit the PA to the payer.
6. Select a payer outcome.
7. Use Appeal / Peer-to-Peer when applicable.
8. Review the workflow summary and efficiency score.
9. Restart with a different scenario.

## Key learnings
- PA workflows depend heavily on complete, criteria-aligned documentation.
- A missing document can create avoidable payer pends.
- Medical necessity should connect symptoms, diagnosis, prior treatment, and the requested service.
- Appeals and peer-to-peer review are escalation paths that should respond directly to the payer's rationale.
- Gamification makes a complex administrative workflow easier to understand and practice.

## GitHub checklist
- [ ] Create `Day26/`
- [ ] Add `day26.md`
- [ ] Add `prior-authorization-workflow-simulator.html`
- [ ] Add completed workflow screenshots
- [ ] Commit the Day 26 changes
- [ ] Push to GitHub
- [ ] Copy the GitHub commit URL for submission

## Note
The solution video/resources were not attached or available in this conversation, so the implementation was based on the provided task specification and simulator prompt.

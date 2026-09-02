# Day 33 — Media Integrity Analyzer

## Key Learnings

### 1. Guided Learning Experience
- Built the application as a guided media-literacy lesson instead of a traditional quiz.
- Each challenge first explains the concept, why it matters, and how it appears in everyday media.
- Users learn through observing, thinking, and then revealing the analysis.

### 2. Headline Analysis
- Learned how headlines can use exaggeration, selective framing, and misleading wording.
- Implemented a Headline Detective challenge with Yes / Maybe / No choices.
- Added highlighted mismatches, an accuracy score, a fair rewrite, and a key takeaway.
- Understood that a headline can be technically related to an article while still creating a misleading impression.

### 3. Emotional Manipulation Detection
- Learned how emotionally charged words can influence audience reactions.
- Built an Emotion Detector challenge that identifies:
  - Intended feeling
  - Emotional phrases
  - Target audience
  - Manipulation technique
  - Neutral rewrite
- This helps users recognize emotional framing before reacting or sharing content.

### 4. Media Literacy Metrics
- Implemented live metrics for:
  - Headline Accuracy
  - Source Reliability
  - Emotional Manipulation
  - Audience Targeting
- Learned how multiple signals can be combined to create a broader media-integrity assessment.

### 5. Randomized Scenarios
- Added multiple fictional headline and social-media scenarios.
- Implemented replay functionality that randomizes scenarios for repeated practice.
- This makes the experience more engaging and prevents users from simply memorizing answers.

### 6. UX and Visual Design
- Practiced creating a premium editorial-style dark interface.
- Added theme selection with Claude Orange and other visual themes.
- Used cards, progress indicators, hover states, animations, badges, and clear visual hierarchy.
- Focused on making the interface feel educational while remaining interactive and modern.

### 7. Responsive Design
- Built the application to work across desktop, tablet, and mobile screen sizes.
- Used responsive grids, flexible layouts, and mobile-friendly controls.
- Ensured challenge cards, metrics, and dashboard sections remain readable on smaller screens.

### 8. Vanilla HTML, CSS, and JavaScript
- Created the complete application in a single HTML file.
- Used only vanilla HTML, CSS, and JavaScript.
- No frameworks, npm packages, backend, API calls, or external assets were required.
- The app can run completely offline.

### 9. State Management
- Used JavaScript state to track:
  - Selected theme
  - Current scenarios
  - Challenge completion
  - User choices
  - Scores
  - Final dashboard results
- Learned how simple state management can power a multi-step interactive application without a framework.

### 10. Final Media Integrity Dashboard
- Created a final dashboard that summarizes the user's learning.
- Included:
  - Overall media-integrity score
  - What the user learned
  - Biggest red flag
  - Three practical media-literacy habits
  - Replay option
- The dashboard turns individual challenge results into actionable learning.

## Key Takeaway

The biggest lesson from Day 33 is that a good educational web app should not only provide answers—it should teach users **how to think**. The Media Integrity Analyzer demonstrates how interactive UX, guided explanations, randomized scenarios, scoring, and visual feedback can turn an important real-world skill like media literacy into an engaging learning experience.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- CSS Animations
- Responsive Web Design
- Client-side State Management

## Project

**Media Integrity Analyzer** — A fully offline, single-file educational web application that teaches users how to identify misleading headlines, emotional manipulation, audience targeting, and other media-integrity signals.

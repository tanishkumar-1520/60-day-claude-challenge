# CareerLaunch AI — Product Requirements Document (PRD)

## 1. Product Overview
CareerLaunch AI is a career-readiness product for freshers seeking their first job. It guides users from a target job description and their current profile toward a practical improvement plan and interview preparation.

## 2. Problem
Freshers often struggle to understand what employers actually require, identify their skill gaps, tailor their profile, and prepare for role-specific interviews. These activities are usually scattered across multiple tools.

## 3. Target Users
Primary users are college students and recent graduates preparing for their first full-time role.

## 4. Product Goal
Help a fresher understand a target role, identify gaps, improve their profile, and practice for an interview through one guided workflow.

## 5. v1.0 Features
1. Career onboarding
2. Target job description input
3. Job requirement analysis
4. Resume/profile review
5. Skill-gap analysis
6. Prioritized improvement recommendations
7. Role-specific interview practice
8. Career action plan
9. Progress dashboard
10. Reset/restart workflow

## 6. Core User Journey
Onboard → provide profile/resume information → add target job description → analyze requirements → review profile match → identify skill gaps → follow recommendations → practice interview questions → review progress → repeat for another role.

## 7. Functional Requirements
- Users can enter their basic career/profile information.
- Users can provide a target job description.
- The product presents required skills, responsibilities, and notable requirements.
- The product compares the user's profile against the target role.
- The product highlights strengths and gaps.
- Recommendations are prioritized into actionable next steps.
- Users can practice role-specific interview questions.
- Users can record/mark practice progress.
- Users can view an overall readiness/progress summary.
- Users can restart or update their target role.

## 8. Non-Functional Requirements
- Responsive on desktop and mobile.
- Clear beginner-friendly interface.
- Fast interaction for the core workflow.
- Graceful empty/error states.
- No dependence on paid services for the capstone's core demonstration.
- User data should remain controlled by the user and should not be presented as guaranteed employment outcomes.

## 9. Explicit Exclusions
- Automatic job applications
- Job-board scraping
- Recruiter/company accounts
- Social networking
- Payments/subscriptions
- Guaranteed job matching or employment predictions
- Complex enterprise authentication
- Large-scale external data pipelines

## 10. Day 10 Success Criteria
A fresh user can complete the full workflow from target role to interview preparation without assistance, understand their key gaps, receive actionable recommendations, practice relevant questions, and view a polished final progress/readiness experience.

## 11. Acceptance Criteria
- The complete primary workflow is usable end-to-end.
- Core screens work on desktop and mobile.
- Empty, invalid, and restart states are handled.
- At least one realistic sample role can be demonstrated.
- The final product has consistent navigation and visual hierarchy.
- The product can be deployed and demonstrated from a shareable URL.

## 12. Risks and Mitigations
**Scope creep:** protect the v1.0 feature list.
**Unreliable AI outputs:** present outputs as guidance, not guarantees.
**Complex integrations:** keep external integrations optional and avoid paid dependencies.
**Incomplete testing:** reserve dedicated testing and deployment days.

## 13. Product Principle
Build the smallest complete experience that creates a visible career-preparation outcome rather than the largest possible career platform.

# Day 52 — API Design

Base URL: `/api/v1`

## Authentication
Protected endpoints require a valid Supabase access token.

## Auth/Profile
### GET /profile
Purpose: Retrieve the current user's profile.
Response: profile object.
Errors: 401, 404.

### PUT /profile
Purpose: Create/update profile.
Request: name, headline, skills, experience, education.
Validation: authenticated user; supported field types.
Errors: 400, 401, 422.

## Jobs
### GET /jobs
Purpose: Search/filter jobs.
Request query: `q`, `location`, `page`, `limit`.
Validation: pagination bounds.
Errors: 400, 502.

### GET /jobs/:id
Purpose: Retrieve one job.
Errors: 401, 404.

### POST /jobs/:id/save
Purpose: Save a job.
Authentication: required.
Errors: 401, 404, 409.

### DELETE /jobs/:id/save
Purpose: Remove saved job.
Errors: 401, 404.

## Applications
### GET /applications
Purpose: List user's applications.
Errors: 401.

### POST /applications
Request: job_id, status, notes.
Validation: valid job_id and supported status.
Errors: 400, 401, 404, 409.

### PATCH /applications/:id
Purpose: Update application status/notes.
Errors: 400, 401, 404.

### DELETE /applications/:id
Purpose: Delete an application record.
Errors: 401, 404.

## AI
### POST /ai/resume-review
Request: profile/resume content and target role.
Response: structured improvement suggestions.
Validation: authenticated user; input size limits.
Errors: 400, 401, 429, 502.

### POST /ai/cover-letter
Request: profile, job details, tone.
Response: editable cover-letter draft.
Errors: 400, 401, 429, 502.

### POST /ai/job-fit
Request: profile + job.
Response: explanation of matching skills and gaps.
Errors: 400, 401, 429, 502.

## Standard Error Format
```json
{
  "error": {
    "code": "VALIDATION_ERROR",
    "message": "Invalid request",
    "details": []
  }
}
```

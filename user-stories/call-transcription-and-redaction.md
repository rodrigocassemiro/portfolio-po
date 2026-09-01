# User Story - Call Transcription and Sensitive Data Redaction

## User Story

As an authorized Quality Assurance analyst,

I want to access a timestamped transcript of an approved call with sensitive information masked,

So that I can review relevant interactions efficiently without unnecessary exposure to personal data.

## Acceptance Criteria

### Scenario 1 – Transcript generation

Given that an eligible recorded call has been ingested,

When transcription processing is completed,

Then the system displays the transcript with timestamps and separate speaker labels.

### Scenario 2 – Sensitive-data masking

Given that the transcript contains configured sensitive-data categories,

When the transcript is processed,

Then the system masks those values before they are displayed to standard reviewers.

### Scenario 3 – Audio evidence

Given that I select a transcript segment,

When I request the supporting evidence,

Then playback starts at the corresponding timestamp if my role is authorized to access audio.

### Scenario 4 – Processing failure

Given that transcription or redaction fails,

When the call enters the review workflow,

Then the system marks the processing status clearly and prevents incomplete output from being treated as a completed review.

### Scenario 5 – Access control

Given that a user lacks the required permission,

When the user attempts to access the transcript or audio,

Then access is denied and the attempt is recorded in the audit log.

## Business Value

- Faster navigation through long calls
- Reduced unnecessary exposure to sensitive data
- Stronger auditability
- More consistent QA reviews

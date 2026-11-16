# Problem Brief: Closing the Screening-to-Care Loop

## User
Care coordinators and clinicians in Abu Dhabi health system managing actionable screening results (e.g., abnormal HbA1c, hypertension).

## Task
Ensure every actionable screening result leads to timely communication, clinical consultation, coordinated referral, and documented outcome without exposing raw PHI.

## Scope
Synthetic/simulated cases only. Privacy-preserving (ZK) pipeline from vision OCR intake to HITL review to FHIR sync. Not a medical device.

## Intended Outcome
Zero patient loss between screening and care completion. Measurable: 88%+ referral completion, <2s triage, 0 bytes raw PHI exposed.

## Constraints
- UAE PDPL, Abu Dhabi DoH, GDPR alignment
- Human-in-the-loop mandatory
- No real patient data

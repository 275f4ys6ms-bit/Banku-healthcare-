# Banku Care

Judge demo for privacy-preserving screening-to-care continuity, prepared for the Future Health Digital Innovation Challenge in Abu Dhabi.

**Live demo:** [banku-care.vercel.app](https://banku-care.vercel.app/)

Open [`index.html`](./index.html) in a browser. No build step, server, or secrets.

## What a judge can do

1. **Continue as Guest (Judge Demo)** — the full workspace, with no login.
2. **Patient Screening Intake** — three synthetic slips (HbA1c 8.4%, stage 2 blood pressure and lipids, routine low-risk). A 1.8 second pass simulates layout read, liveness, and a zk-PHI commitment.
3. **Care Coordinator** — six aliases, an explainable confidence score, and actions to approve a referral, send a discreet reminder, or mark care completed. The completion figure moves. Raw PHI stays at 0 bytes.
4. **Architecture & Governance** — vision, privacy vault, risk router, clinician review, FHIR sync, with notes for UAE PDPL, Abu Dhabi DoH, and GDPR.

## Limits

Synthetic data only. This is not a medical device and it does not diagnose. Choosing a file does not upload or read it. The commitment string is a demo label, not a live Groth16 proof, and the page is not connected to a clinical record.

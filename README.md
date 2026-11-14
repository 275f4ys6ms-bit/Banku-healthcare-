# Banku Care

Banku Care is a prototype for privacy-preserving screening-to-care continuity. It demonstrates how an abnormal screening result could be routed to a care coordinator for human review without sending raw patient identity through the coordination workflow.

## Demo

**Live demo:** [banku-care.vercel.app](https://banku-care.vercel.app/)

To run it locally, open [`index.html`](./index.html) in a modern web browser. The demo is a static HTML page with inline CSS and JavaScript; no build step, server, or environment variables are required.

The project is deployed on Vercel at the live demo URL above.

The demo includes:

- A patient screening intake with three synthetic screening presets and a simulated file-upload flow.
- A simulated scan showing liveness, OCR, metric extraction, and creation of a salted SHA-256 commitment.
- A care coordinator dashboard for reviewing, approving referrals, sending reminders, and marking care complete.
- An architecture and governance overview covering the prototype's intended privacy and interoperability concepts.

## Important limitations

This is a demonstration prototype, not a medical device or clinical decision system. It does not process uploaded documents: choosing a file only starts a synthetic preset. Screening values, queue entries, and performance figures are illustrative demo data. The displayed SHA-256 commitment is not a zero-knowledge proof, and the prototype does not connect to clinical systems or implement the listed regulatory controls.

Do not use this demo for diagnosis, treatment, or real patient information.

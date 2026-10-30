# LearnLens — HJKS Squad

**Affordable, teacher-first adaptive learning for Classes 6–10.**

LearnLens is a lightweight classroom prototype designed for schools where students may not own personal smartphones or tablets. It runs in a browser on one shared classroom computer or teacher-led screen.

## Problem
Students learn at different speeds, but access to personal devices and reliable connectivity is unequal. A solution that assumes every learner owns a device can exclude the students who need support most.

## Solution
- Shared-device-first classroom use; no personal phone or learner account required for this demo.
- Short diagnostic quizzes with immediate explanations.
- Transparent next-step recommendations: guided revision, standard practice, or challenge.
- Teacher view with clearly labelled sample class data.
- Static browser prototype; no backend or paid service required.

## Run locally
Open `index.html` in a modern browser, or run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy
Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save. The public URL will appear in Pages settings after publishing. A GitHub Actions workflow is also included.

## Files
- `index.html` — prototype interface
- `styles.css` — responsive styling
- `app.js` — quiz and adaptive recommendation logic
- `docs/ARCHITECTURE.md` — architecture and data flow
- `docs/DEMO-SCRIPT.md` — 3-minute recording plan
- `architecture.svg` — architecture diagram

## Demo limitations
Quiz questions, score thresholds, and teacher dashboard figures are illustrative. This is not a validated assessment product. Review content with subject teachers before classroom use. No real learner data is collected or transmitted by this static demo.

## Team
**HJKS Squad** · Code Kernel '26 | Decode

## Future work
Teacher-authored curriculum question banks, offline synchronization, multilingual explanations, accessibility testing, secure teacher accounts, privacy review, and pilot evaluation.

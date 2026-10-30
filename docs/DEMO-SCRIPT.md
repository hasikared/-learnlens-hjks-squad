# LearnLens — 3-minute product demonstration

**Team:** HJKS Squad  
**Event:** Code Kernel '26 | Decode  
**Format:** Screen recording + natural voice narration  
**Target duration:** 3:00  
**Prototype:** Static browser demo; sample teacher metrics

## Before recording

1. Open the deployed LearnLens page if GitHub Pages is live. Otherwise open `index.html` locally in Chrome.
2. Use a laptop screen at 1920×1080 if available. Set browser zoom to 90–100%.
3. Close personal tabs and notifications. Do not show real student information.
4. Keep this script beside the recording window. Speak naturally; pause between sections.
5. For the quiz demonstration, choose Class 8 → Mathematics → Fractions & percentages. Answer one or two questions deliberately, then finish the quiz so the recommendation appears. To show the challenge path, answer all three correctly; for revision, intentionally miss two.
6. Record one continuous take if possible. If editing, use simple cuts and quiet background music only if it does not compete with narration.

## Timed storyboard and narration

### 0:00–0:20 — Opening / the problem
**On screen:** Start at the LearnLens landing page. Slowly scroll just enough to show the headline.

**Say:**
"Imagine a classroom where every student learns at a different pace—but not every student has a smartphone, tablet, or reliable internet. If adaptive learning depends on every child owning a device, the students who need support most can be left behind. That is the problem our team wanted to address."

### 0:20–0:45 — Introduce LearnLens
**On screen:** Point to the LearnLens name and the shared-classroom message. Scroll to the learning check.

**Say:**
"Meet LearnLens, our shared-device-first adaptive learning prototype for Classes 6 to 10. Instead of asking every learner to bring a personal device, a teacher can use one classroom computer or screen. Students can take turns or work in small groups, with the teacher guiding the activity."

### 0:45–1:10 — Set up a learning check
**On screen:** Select Class 8, Mathematics, and Fractions & percentages. Click Begin learning check.

**Say:**
"Let's see how it works. I will choose Class 8 Mathematics and a topic on fractions and percentages. The learner starts with a short check designed to reveal what they understand and where they may need another explanation."

### 1:10–1:45 — Show the quiz and feedback
**On screen:** Select an answer, click Check answer, and show the explanation. Continue through the questions.

**Say:**
"Each question gives immediate feedback and a simple explanation. So the experience is not just about marking an answer right or wrong. It gives the learner a chance to understand the idea and try again. The questions in this prototype are examples, and teachers would review and expand the question bank before classroom use."

### 1:45–2:10 — Show the adaptive next step
**On screen:** Finish the quiz and pause on the recommendation.

**Say:**
"After the check, LearnLens recommends a next activity. A lower score leads to guided revision, a middle score suggests more practice, and a full score unlocks a challenge activity. These are transparent demonstration rules—not a claim that the prototype uses a trained AI model or replaces a teacher."

### 2:10–2:35 — Teacher view
**On screen:** Scroll to the Teacher View. Pause on the four sample metrics and suggested action.

**Say:**
"Here is the teacher view. It shows an example of how class-level patterns could help a teacher decide whether to revise a concept, offer more practice, or extend learning. The numbers shown are sample demo data, not real student records. The teacher stays in control of the next step."

### 2:35–2:52 — Architecture / responsible design
**On screen:** Briefly show the architecture diagram in the repository, then return to the website.

**Say:**
"Technically, this version runs in the browser: a question bank, answer checker, and recommendation rules work together without sending learner answers to a server. Our next steps are curriculum-reviewed content, multilingual support, offline capability, accessibility testing, and a secure teacher system."

### 2:52–3:00 — Close
**On screen:** Return to the landing page and show the team name.

**Say:**
"LearnLens is built on one belief: technology should open doors, not create barriers. We are HJKS Squad. Thank you."

## Recording checklist

- [ ] Show the working website, not only slides.
- [ ] Demonstrate at least one answer and its explanation.
- [ ] Show the final recommendation.
- [ ] Show the teacher view and label its figures as sample data.
- [ ] Keep narration clear, steady, and conversational.
- [ ] Export as MP4 (H.264), 1080p if possible, approximately 3 minutes.
- [ ] Watch the final export once to check sound, spelling, and timing.

## Accuracy notes

- This is a front-end demonstration, not a deployed production learning platform.
- The recommendation logic uses simple score thresholds (below 50%: guided revision; 50–99%: standard practice; 100%: challenge).
- Teacher dashboard figures are illustrative sample values.
- Do not describe the current prototype as a trained AI system, validated assessment, or live student analytics platform.
- Do not include real student names, phone numbers, or private information in the recording.

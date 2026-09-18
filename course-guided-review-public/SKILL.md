---
name: course-guided-review-public
description: Guide exam review from user-supplied course materials through source-grounded, problem-driven dialogue. Use when the user wants to learn a course through authentic questions, course-specific methods, adaptive scaffolding, exam mapping, or review of handwritten work. Do not use for an ordinary one-off homework answer that does not require a course-grounded tutoring workflow.
---

# Course-Grounded Guided Review

Help the learner prepare for an exam by learning through authentic course questions. Ground explanations in the supplied course materials, adapt the amount of guidance to the learner's current mastery, and teach both the calculation and how to recognize the method next time.

## Core commitments

- Treat original lectures, notes, assignments, exams, and official solutions as the evidence base. Treat normalized LaTeX notes as a searchable middle layer, not as a replacement for the originals.
- Never equate uploaded with read, keyword-matched with page-reviewed, or OCR output with reliable mathematics.
- Never claim that a method is the instructor's method unless the supplied sources support that claim.
- Start from a real course question whenever possible. Translate what the prompt asks before beginning the solution.
- Ensure the learner understands the recognition layer at consequential method choices: why the method applies, what in the question signals it, the first action to take, and how to recognize it next time. Do not turn this into a mandatory multi-label output at every step.
- Adapt between direct teaching, guided prompting, and independent solving. Do not use Socratic prompting when the learner lacks the prerequisite mental model.
- Do not proactively create plots or diagrams. Use them when the learner asks, or briefly offer one after repeated conceptual blockage.
- Preserve the learner's correct work and correct the earliest consequential error first.

## Route the task

- For many files, course onboarding, source coverage, scans, or retrieval from LaTeX notes, read [source-audit.md](references/source-audit.md).
- For building or updating the exam/course map, read [course-map-schema.md](references/course-map-schema.md).
- For tutoring, checking handwritten work, pacing, and exam-time adaptation, read [teaching-modes.md](references/teaching-modes.md).

Read only the references relevant to the current task.

## Working sequence

1. Establish the course context: exam date, permitted materials, official scope, available sources, and whether the learner wants fast, standard, or deep review. Infer these from the conversation when already known; do not repeatedly ask.
2. Establish the evidence boundary. State which materials are available, which have actually been inspected, and which parts remain uncertain.
3. Match preparation depth to the request:
   - for a targeted question or topic, retrieve and verify only the relevant course materials;
   - for comprehensive course review, complete the first-pass inventory/index of all supplied materials and build a preliminary course/exam map before tutoring begins.
   Keep unresolved coverage gaps visible, and never claim comprehensive coverage without an auditable map.
4. Select one authentic question or sub-question. Begin by translating its command words into the required deliverable.
5. Diagnose the learner's state from their response:
   - no usable model: teach the idea and demonstrate enough connected steps to establish a usable mental model;
   - partial model: ask for one small next action;
   - stable model: let the learner solve, then inspect the work.
6. Work in short cycles: prompt, attempt, diagnose, correct, and continue. Do not reveal a long solution before the learner has a usable entry point unless time pressure or zero foundation makes direct teaching better.
7. At key method-selection points, ensure the recognition layer covers:
   - **Signal:** the wording, equation form, data, or structure that matters;
   - **Reason:** why that signal selects the method;
   - **Method:** the named pipeline, model, or theorem;
   - **First move:** what to write or do immediately in an exam;
   - **Transfer cue:** what should trigger the same idea next time.
   Treat these as a reasoning checklist, not a required five-part response template. During ordinary steps, surface only the cue that materially helps; use the full structure for major method choices, final recaps, or when the learner asks.
8. Finish the question with only the useful consolidation: an exam-ready solution, a short method pipeline, the key trigger, and the learner's main error pattern. Add a transfer question only when it helps.

## Explanation and language

- Use the language requested by the learner. If no language is specified, match the learner's language while preserving important course terminology in the language used by the source materials.
- Match the notation and solution style used in the course materials.
- Explain both `calculation` and `recognition`; a derivation alone is incomplete if the learner would not know when to use it.
- Prefer a concrete first action over a large formula dump.
- Under severe time pressure, prioritize recurring methods, exam wording, minimal complete solutions, and common traps.

## Boundaries

- Do not substitute a more advanced or generic textbook method for the course method without clearly labeling it as an external alternative.
- Stay within the user-declared source boundary. Do not search for or introduce external course content unless the user explicitly requests or permits supplementation. Clearly label every permitted external supplement, and never present it as the instructor's method without course evidence.
- Do not claim full course coverage without an auditable source inventory and coverage record.
- Do not silently guess unclear equations or text in scans; mark them uncertain and inspect the page image.
- Do not edit, reorganize, or overwrite the learner's source materials unless explicitly asked.
- Do not imitate an instructor's personality. Model only evidenced methods, notation, expectations, and grading patterns.

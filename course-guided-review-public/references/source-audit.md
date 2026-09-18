# Source Audit and Retrieval

Use this procedure when the course has many PDFs, scans, notes, exams, or a normalized LaTeX project.

## Keep an honest coverage ledger

Assign each source or relevant section one of these states:

- **Registered:** filename and basic metadata are known; content has not been inspected.
- **Indexed:** searchable text, headings, or page thumbnails have been inspected sufficiently for navigation.
- **Page-reviewed:** the relevant pages have been read visually or from reliable electronic text.
- **Question-verified:** the exact passage, worked example, solution method, or exam question has been checked against the original page.
- **Unclear:** scan quality, notation, missing pages, or conflicting sources prevent a reliable conclusion.

Never report a stronger state than the work actually completed.

## Respect the declared source boundary

- Default to the lectures, notes, assignments, exams, and other materials the user has placed in scope.
- Do not search for or introduce external textbooks, webpages, or alternative methods unless the user explicitly requests or permits supplementation.
- When the supplied materials do not support a needed claim, report the gap instead of silently filling it from general knowledge.
- Clearly label every permitted external supplement. Do not describe it as course-taught or as the instructor's method without evidence from the course materials.

## Large-corpus workflow

Use two passes rather than pretending to read everything at equal depth.

For comprehensive course review, completing Pass 1 across all supplied materials and producing a preliminary course/exam map is a gate before tutoring begins. For a targeted question or topic, inspect only the relevant sources and do not delay the answer for a whole-course inventory.

### Pass 1: inventory and index

1. List all candidate files without changing them.
2. Record file type, page count when available, likely topic, source role, and whether it is electronic or scanned.
3. Extract text from electronic PDFs for search. Render representative or relevant pages when formulas, figures, or layout matter.
4. For scans, render pages and inspect them visually. Use OCR only as a navigation aid; do not trust OCR for mathematical symbols without visual verification.
5. Locate existing LaTeX notes, source registers, clarification logs, and practice workbooks.
6. Mark duplicates, missing files, unreadable sections, and uncertain provenance.

### Pass 2: priority deep reading

1. Deep-read the official scope and high-signal exam materials first.
2. Trace recurring question types back to lectures, examples, and official solutions.
3. Verify each high-stakes formula, convention, and method against the original page.
4. Read lower-priority material when it fills a real gap in the course map or current problem.
5. Stop when the core scope, approved method, and representative exam pattern have enough authoritative support for the current task. Report what remains only indexed or unread.

## Source authority and exam signal

Keep two ideas separate.

**Authority for course scope and approved method** usually follows:

1. official scope, announcements, and explicit instructor instructions;
2. lecture materials and instructor notes;
3. official solutions and worked examples;
4. tutorials and assignments;
5. user-permitted external textbooks or web references, clearly labeled as supplements.

**Signal for likely exam tasks** usually follows:

1. recent past exams, mock exams, quizzes, and marked assignments;
2. repeated lecture or tutorial problems;
3. explicit review sheets and learning objectives;
4. isolated examples or generic textbook coverage.

If sources conflict, explain the conflict and prefer explicit course authority. Never infer official scope solely from one or two past exams.

## Using normalized LaTeX notes

Treat LaTeX notes as the retrieval layer:

1. Search the `.tex` files for the topic, formula, command word, or notation.
2. Read the entire surrounding section, not only the matched line.
3. Follow source/page references in the notes or source register.
4. Verify important claims and instructor-specific methods on the original PDF or scan page.
5. If the LaTeX project is incomplete, fall back to originals and record the gap.

LaTeX notes improve searchability, consistency, and cross-linking. They do not prove that every source page has been transcribed correctly or completely.

## Minimal audit table

Use a compact table or equivalent record with these fields:

| Source | Role | Format | Coverage state | Topics/questions | Source pages | Issues/gaps |
|---|---|---|---|---|---|---|

For a large course, add `exam signal`, `authority level`, and `last verified` only when useful.

## Evidence language

Prefer precise statements:

- “I indexed all 18 PDFs and page-reviewed the six sections relevant to this topic.”
- “This method appears in Lecture 7 and the official solution to Exam A.”
- “The scan is unclear at this symbol, so I cannot confirm the sign yet.”

Avoid unsupported statements:

- “I read everything.”
- “This is definitely on the exam.”
- “This is how your instructor always solves it.”

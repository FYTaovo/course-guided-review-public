# Course-Guided Review Public

A reusable Codex skill for source-grounded, question-driven exam review.

Instead of beginning with a generic formula dump, the skill works from the learner's own lectures, notes, assignments, scans, and past exams. It builds an evidence-backed course map, translates what real questions are asking, and adapts between direct teaching, guided practice, and independent solution checking.

## Highlights

- Keeps original course materials authoritative.
- Treats normalized LaTeX notes as a searchable middle layer.
- Distinguishes uploaded, indexed, page-reviewed, and question-verified sources.
- Uses authentic course questions to drive review.
- Explains both how to calculate and how to recognize the method next time.
- Adapts support to the learner's demonstrated mastery.
- Avoids silently introducing external methods outside the declared source boundary.
- Handles electronic PDFs, scanned documents, handwritten work, and time-pressured review.
- Matches the learner's requested language while preserving important course terminology.

## Installation

Clone the repository and copy the skill folder into your Codex skills directory:

```bash
git clone https://github.com/FYTaovo/course-guided-review-public.git
mkdir -p ~/.codex/skills
cp -R course-guided-review-public/course-guided-review-public ~/.codex/skills/
```

## Usage

Invoke the skill explicitly:

```text
Use $course-guided-review-public to review this course from the materials I provide.
```

You can also specify the teaching mode or time constraint:

```text
Use $course-guided-review-public. My exam is tomorrow, so prioritize recurring question types and exam-ready solution pipelines.
```

```text
Use $course-guided-review-public. I have some foundation, so guide me one meaningful step at a time instead of revealing the whole solution.
```

## Repository layout

```text
course-guided-review-public/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── course-map-schema.md
    ├── source-audit.md
    └── teaching-modes.md
```

## Scope and privacy

The repository contains only the reusable skill instructions. It does not include private course materials, student work, exams, or personal learning records.

## License

MIT License. See [LICENSE](LICENSE).

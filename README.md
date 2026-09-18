# Course-Guided Review Public

[中文介绍](#中文介绍) · [English](#english)

## 中文介绍

这是一个用于考试复习的 Codex Skill，核心特点是：**以用户提供的课程资料为依据，通过真实题目开展循序渐进的对话式复习。**

它不会一开始就倾倒通用公式和课外方法，而是优先阅读学习者自己的课件、笔记、作业、扫描件和历年试题，建立有证据支持的课程与考试地图。随后，它会先解释题目究竟要求完成什么，再根据学习者当前的掌握程度，在直接讲解、逐步引导和独立作答检查之间灵活切换。

### 主要特点

- 将原始课程资料作为主要依据，不擅自偏离课程范围。
- 将整理后的 LaTeX 讲义作为便于检索的中间层，但不会代替原始资料。
- 明确区分“文件已上传”“已建立索引”“已逐页阅读”和“已核对具体题目”。
- 通过课程中的真实题目带动知识点复习，而不是单纯复述定理。
- 不仅解释题目怎么算，还解释为什么要使用这个方法，以及下次如何识别。
- 根据学习者实际表现，在直接讲解、引导式练习和独立作答之间切换。
- 默认不引入用户指定材料之外的方法；经过允许的外部补充也必须明确标注。
- 支持电子 PDF、扫描版资料、手写答案检查和考前时间紧张的复习场景。
- 自动匹配学习者使用的语言，同时保留课程中的重要专业术语。

### 安装方法

克隆仓库，并将 Skill 文件夹复制到 Codex 的 Skills 目录：

```bash
git clone https://github.com/FYTaovo/course-guided-review-public.git
mkdir -p ~/.codex/skills
cp -R course-guided-review-public/course-guided-review-public ~/.codex/skills/
```

### 使用方法

可以直接调用：

```text
使用 $course-guided-review-public，根据我提供的课程材料带我复习这门课。
```

也可以说明复习时间和希望采用的教学方式：

```text
使用 $course-guided-review-public。我的考试就在明天，请优先复习反复出现的题型和考试书写步骤。
```

```text
使用 $course-guided-review-public。我已经有一些基础，请每次只引导我完成一个真正有意义的步骤，不要立刻公布完整答案。
```

### 仓库结构

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

### 范围与隐私

这个仓库只包含可复用的 Skill 指令，不包含任何私人课程资料、学生作业、考试文件或个人学习记录。

### 开源许可

采用 MIT License，详见 [LICENSE](LICENSE)。

---

## English

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

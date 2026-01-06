# Contributing to Eisengrau

Thank you for your interest in contributing to **Eisengrau**.

This repository is a long-term, pedagogy-first knowledge base for algorithmic
problem solving. Contributions are welcome, provided they align with the
project’s goals of clarity, rigor, and transferable understanding.

---

## What This Repository Values

Eisengrau prioritises:
- **algorithmic reasoning over submission results**,
- **clear explanation over minimal code**,
- **transferable patterns over one-off tricks**,
- **correctness and insight over cleverness**.

Contributions should aim to *teach* something reusable.

---

## What You Can Contribute

You are welcome to contribute:
- new problems and solutions,
- alternative solution approaches,
- optimisations or generalisations,
- explanatory notes or proofs,
- clarifications of common pitfalls,
- improvements to organisation or documentation.

Both beginner-friendly and advanced material are welcome, provided they are
clearly framed.

---

## Where to Place Content

Content should be placed according to the **dominant algorithmic idea** it
illustrates.

When deciding where something belongs, ask:
- Which paradigm is essential to the solution?
- What concept should a reader recognise and reuse?
- If teaching this problem, which idea is central?

Avoid duplicating the same problem across multiple folders.
If a problem admits multiple paradigms, document alternative approaches
within the same directory.

If you are unsure where something fits, open an issue or discussion first.

---

## Problem Directory Structure

Each problem topic in this repository follows a **standardised, author-aware
directory structure**.

The purpose of this structure is to:
- preserve clear authorship,
- separate theory from implementation,
- enable rigorous mathematical referencing,
- ensure long-term maintainability and pedagogical clarity.

---

### Required Directory Layout

At minimum, each problem topic must be organised as follows:

```
<problem_topic>/
└── <language>/
  └── <author_name>/
    └── <approach_name>/
      ├── notes/
      │ ├── theory.tex
      │ └── mathematics.tex
      │
      └── code/
      └── submission.<ext>
```
Where:
- `<problem_topic>` represents the algorithmic problem or concept,
- `<language>` is the programming language used (e.g. `python`, `cpp`, `java`),
- `<author_name>` is the contributor’s name or handle,
- `<approach_name>` identifies a distinct solution strategy,
- `<ext>` corresponds to the chosen language.

---

### Example

For example:
```
when_dp_fails/
  └── java/
    └── matthew_maksymilian_miezaniec/
      ├── greedy_attempt/
      │ ├── notes/
      │ │ ├── theory.tex
      │ │ └── mathematics.tex
      │ └── code/
      │ └── submission.java
      │
      └── dp_solution/
        ├── notes/
        │ ├── theory.tex
        │ └── mathematics.tex
        └── code/
        └── submission.java
```

Each `<approach_name>` directory represents **one coherent solution strategy**.

---

## Notes Directory

The `notes/` directory is **mandatory**.

### `theory.tex`
This file must include:
- a full theoretical explanation of the algorithmic approach,
- justification of design decisions,
- discussion of alternative paradigms where relevant,
- complexity analysis.

It should be readable as a **standalone exposition**.

### `mathematics.tex`
This file is required **only when** the solution relies on non-trivial
mathematical reasoning or proof-based arguments.

When present, it must include:
- relevant definitions, lemmas, and derivations,
- formal proofs where appropriate,
- references to known results when applicable.

It must not contain general algorithmic discussion or implementation details.

---

## Code Directory

Each `code/` directory must contain **exactly one primary submission file**.

The code must:
- be clean, sanitised, and production-quality,
- follow standard conventions for the chosen language,
- contain no malicious, obfuscated, or misleading behaviour,
- be suitable for direct compilation or execution.

---

### Code–Notes Alignment

Implementations must:
- follow logically from the corresponding notes,
- include comments referencing relevant sections of the notes,
- preserve traceability between theory and code.

Contributors are encouraged to:
- annotate code with references to sections or equations,
- structure implementations to mirror theoretical decomposition.

---

## General Requirements

- All submissions must be original work or properly attributed adaptations.
- Multiple authors may submit independent solutions to the same problem.
- Language-specific conventions must be respected.
- Readability and correctness take precedence over brevity or cleverness.

Submissions that do not follow this structure may be requested to revise
before acceptance.

---

## Attribution and Authorship

Eisengrau is a multi-author repository.

If you contribute:
- you retain authorship of your contributions,
- your name may appear in file headers or documentation,
- your work is distributed under the repository’s license.

When adapting existing material:
- preserve original attribution,
- clearly indicate modifications or extensions.

If you believe attribution is missing or incorrect, please open an issue.

---

## Licensing

By contributing, you agree that:
- your contributions are licensed under the same license as the repository,
- others may reuse your work under those terms with proper attribution.

If you are unsure whether material is compatible with this license,
do not submit it without clarification.

---

## Academic Integrity

If you are a student:
- ensure compliance with your institution’s academic integrity policies,
- do not submit assessed or restricted coursework.

This repository exists for learning and teaching, not for violating rules.

---

## How to Contribute

1. Fork the repository.
2. Create a new branch for your changes.
3. Add your contribution following the structure above.
4. Open a pull request describing what you added and why.

Small, focused contributions are preferred.

---

## Final Note

Eisengrau is designed to grow **slowly, thoughtfully, and coherently**.

If your contribution improves understanding, clarity, or long-term value,
it is welcome.

Thank you for helping build a rigorous and shared resource for algorithmic
thinking.

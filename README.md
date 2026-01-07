# Eisengrau

**Eisengrau** is a structured, pedagogy-first repository for exploring algorithmic
problem solving using competitive programming problems as canonical reference points.

This repository is **not** a submission dump and **not** an interview-cram archive.  
Its purpose is to document *how* to think about problems, compare solution paradigms,
and teach transferable algorithmic patterns through carefully organised examples,
notes, and implementations.

---

## Philosophy

Competitive programming and algorithmic problem solving are fundamentally about:
- recognising structure,
- selecting appropriate paradigms,
- understanding trade-offs,
- and reasoning rigorously under constraints.

Accordingly, this repository focuses on:
- multiple solution strategies per problem,
- explicit comparison of time and space complexity,
- failed or suboptimal approaches kept for instructional value,
- pattern-first organisation rather than problem-first memorisation.

---

## Repository Structure

Problems are organised **by algorithmic pattern and paradigm**, not by difficulty or
arbitrary ordering.  
An example of how this repository is structured includes the following layout:

```
Eisengrau/
├── arrays/
│ ├── two_pointers/
│ ├── prefix_sums/
│ └── sliding_window/
│
├── graphs/
│ ├── bfs/
│ ├── dfs/
│ ├── shortest_paths/
│ └── spanning_trees/
│
├── dynamic_programming/
│ ├── classic/
│ ├── interval_dp/
│ └── state_compression/
│
├── math/
│ ├── number_theory/
│ ├── combinatorics/
│ └── modular_arithmetic/
│
└── README.md
```

Each problem folder typically contains:
- multiple implementations (different paradigms or trade-offs),
- a dedicated `README.md` explaining ideas and pitfalls,
- notes on when each approach is appropriate.

---

## Intended Audience

This repository is intended for:
- students learning competitive programming or algorithms,
- educators and tutors teaching algorithmic thinking,
- programmers who want to understand *why* solutions work,
- readers preparing for ICPC-style contests or technical interviews *properly*.

If you are looking for minimal code to paste into an online judge, this repository
is probably not what you want.

---

## Contributions

Contributions are welcome.

If you think a problem, approach, explanation, optimisation, or organisational
improvement would be useful or interesting to others, feel free to add it.

This repository is intended to grow as a **shared knowledge base** for algorithmic
thinking, and thoughtful contributions that improve clarity, depth, or coverage
are encouraged.

### Contribution Guidelines

If you contribute:
- keep explanations clear and pedagogically motivated,
- prioritise correctness and reasoning over brevity,
- place material in the appropriate pattern-based section,
- document trade-offs and limitations where relevant.

By submitting a contribution, you agree that:
- your contribution may be edited for clarity or consistency,
- your contribution will be distributed under the same license as the repository,
- authorship credit will be preserved where appropriate.

If you are unsure where or how something fits, feel free to open an issue or
discussion first.

---

## Use, Reuse, and Attribution (IMPORTANT)

You are **explicitly permitted** to:
- read, study, and learn from all code and notes in this repository,
- reuse implementations or explanations in your own work,
- adapt material for teaching, coursework, or educational content.

However, **attribution is mandatory**.

### Mandatory Credit Requirement

If **any** code, explanation, idea, structure, or non-trivial fragment from this
repository is used **anywhere**, you **must** provide clear and visible credit to
the original source.

Attribution must:
- credit the **repository** as a whole, and
- credit **individual authors** where their contributions are directly used or
  adapted and authorship is known.

This includes, but is not limited to:
- coursework submissions,
- lecture notes or teaching material,
- blog posts or articles,
- GitHub repositories,
- interview preparation resources,
- competitive programming notes,
- online solutions or discussion posts.

### Required Form of Credit

At minimum, attribution must include:
- the repository name: **Eisengrau**
- a link to the original repository or specific file used

Where applicable, attribution **must also include**:
- the name(s) of the original author(s) of the material used

**Examples of acceptable attribution:**
```
Adapted from Eisengrau (originally by Matthew Maksymilian Miezaniec)
```
or
```
Based on material from:
Eisengrau - see individual file authors for attribution
```
or
```
Based on Eisengrau.
Specific implementation adapted from <author name>.
```


### No Attribution Loopholes

The following **do not** exempt you from attribution:
- rewriting variable names,
- changing programming language,
- minor refactoring or reformatting,
- combining this material with other sources,
- using the idea rather than the exact code.

If the material meaningfully informed your solution or explanation, **credit is
required**.

---

## Academic Integrity Notice

If you are a student:
- you are responsible for ensuring that reuse of this material complies with your
  institution’s academic integrity policies,
- proper attribution does **not** automatically make reuse permissible in assessed
  work.

This repository is intended as a learning resource, not as a substitute for original
assessed submissions.

---

## Disclaimer

This repository is provided for educational purposes.  
The author makes no guarantees regarding correctness, optimality, or suitability for
any specific contest, interview, or assessment.

---

## Maintainers and Contributors

### Project Founder and Lead Maintainer

**Matthew Maksymilian Miezaniec**  
President @ KCPC · President @ Orthant Research Group

**Mehmet Kutay Bozkurt**
Vice-President @ KCPC

**Annoor (Beed) Mustafi**  
Treasurer @ KCPC · General-Secretary @ KCPC

All listed founders and lead maintainers share **equal roles and responsibilities**, including responsibility for:
- the original design and structure of the repository,
- its pedagogical direction and taxonomy,
- overall maintenance and review.

### Contributors

This repository includes contributions from multiple authors.

Individual files or directories may list their respective authors where
appropriate. Contribution history is also preserved via version control.

Unless otherwise stated, contributions are made under the same license as the
repository.

If you believe your contribution is not properly attributed, please open an issue
or contact the maintainers.

---

## Final Note

If you find this repository useful, attribution is not only required - it is
appreciated.

Good algorithmic thinking spreads best when credit is preserved.

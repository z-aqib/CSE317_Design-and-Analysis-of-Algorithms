# CSE317 — Design and Analysis of Algorithms (DAA)

A student-focused, exam-oriented repository for **CSE317 (Design and Analysis of Algorithms)** at **IBA Karachi**.  
This repo is meant to save future students time by keeping **past exams, quizzes, problem sets, practice questions, lectures, and curated external resources** in one place—so you can practice patterns across semesters instead of hunting materials everywhere.

## Quick Links
- [Course Outline (Fall 2025 — Dr. Shahid Hussain)](./course_outline_fall_2025.pdf)
- [Exams (First/Second Term, Mid, Final)](./exams/)
- [Problem Sets / Homeworks](./problem-sets/)
- [Quizzes](./quizzes/)
- [Lectures (by semester/instructor)](./lectures/)
- [Practice Questions](./practice-questions/)
- [External CMU Resources (GitHub pack)](./cmu_github_resources/)
- [CMU Notes (Fall 2011, Fall 2016, Spring 2023)](./cmu_notes/)
- [Books / References](./books/)

---

## Table of Contents
- [Context and Coverage](#context-and-coverage)
- [How to Use This Repo (Recommended Exam Prep Flow)](#how-to-use-this-repo-recommended-exam-prep-flow)
- [Spring 2025 (Dr. Jibran Rashid) Course Components](#spring-2025-dr-jibran-rashid-course-components)
- [Mid Exam Survival Checklist (Up to Week 7)](#mid-exam-survival-checklist-up-to-week-7)
- [Final Exam Survival Checklist (After Week 8)](#final-exam-survival-checklist-after-week-8)
- [Repository Structure](#repository-structure)
- [Notes on Policy and Updates](#notes-on-policy-and-updates)

---

## Context and Coverage

I studied **DAA in Spring 2025** with **Dr. Jibran Rashid**, and I **TA-ed in Fall 2025** with **Dr. Shahid Hussain**.

Since LMS tabs can get removed after semesters end, this repo contains **whatever I had access to and collected** (including external references I personally used while preparing). The goal is not “follow one semester’s plan,” but instead:
- **Practice across semesters**
- Recognize **question patterns**
- Use missing-topic coverage from one term to complement another

---

## How to Use This Repo (Recommended Exam Prep Flow)

If you’re using this repo for serious prep, this flow works well:

1. **Start with past exams**
   - Mid: go to [`exams/03_mid_exam`](./exams/03_mid_exam/)
   - Final: go to [`exams/04_final_exam`](./exams/04_final_exam/)
   - Build a list of topics that repeat and the level of depth expected.

2. **Backfill concepts using lectures + notes**
   - Sir Shahid resources: [`lectures/2025-fall_-_shahid-hussain`](./lectures/2025-fall_-_shahid-hussain/)
   - Sir Jibran resources: [`lectures/2025-spring_-_jibran-rashid`](./lectures/2025-spring_-_jibran-rashid/)
   - Extra: older sir Shahid materials in [`lectures/2023-spring_-_shahid-hussain`](./lectures/2023-spring_-_shahid-hussain/) and [`lectures/2024-fall_-_shahid-hussain`](./lectures/2024-fall_-_shahid-hussain/)

3. **Do problem sets like timed practice**
   - Start from your closest style/semester, then diversify:
     - [`problem-sets/2025-fall`](./problem-sets/2025-fall/) (programming + theory)
     - [`problem-sets/2025-spring`](./problem-sets/2025-spring/) (my psets + sources)
     - [`problem-sets/2023-spring`](./problem-sets/2023-spring/), [`problem-sets/2022-spring`](./problem-sets/2022-spring/)

4. **Use quizzes to lock fundamentals**
   - [`quizzes/`](./quizzes/) has multiple semesters—great for fast revision and pattern recognition.

5. **Use curated external resources only when needed**
   - CMU-style materials are extremely useful for tough topics:
     - [`cmu_github_resources`](./cmu_github_resources/)
     - [`cmu_notes`](./cmu_notes/)

---

## Spring 2025 (Dr. Jibran Rashid) Course Components

This repository includes two Spring 2025-specific course components that were part of the grading structure when I took DAA with Dr. Jibran Rashid.

### Creative Explanation (5%)
**Weightage:** 5%  
Students were required to **creatively explain a Computer Science concept to a non-Computer Science audience**. The explanation had to be understandable for a general listener and was presented **in front of the entire class**.  

You can find related artifacts here:
- `creative-explanation/`

### Peer Assessment (5%)
**Weightage:** 5%  
This was a structured peer-review activity. Students paired up and selected **two questions** (from any problem set / quiz / exam) that they initially got wrong. They then:
1. Re-solved the questions correctly,
2. Got their corrected solutions reviewed by their peer,
3. Presented and justified the corrected approach in front of the TA.

You can find related artifacts here:
- `peer-assessment/`

---

## Mid Exam Survival Checklist (Up to Week 7)

Mid coverage varies by instructor/semester, but **up to Week 7 (Fall 2025 outline)** is a solid baseline.

**Week 1 — Foundations**
- Introduction
- Big-O / asymptotics, mathematical preliminaries
- Sorting: Merge sort, insertion sort

**Week 2 — Divide and Conquer**
- Closest pair of points
- Integer multiplication
- Strassen’s matrix multiplication
- Matrix exponentiation

**Week 3 — Greedy Algorithms**
- Activity selection / scheduling
- Huffman coding
- Greedy correctness (matroid basics)
- Counterexamples

**Week 4 — Dynamic Programming I**
- LCS
- Edit distance
- Knapsack

**Week 5 — Dynamic Programming II**
- Bellman–Ford
- Floyd–Warshall
- Matrix-chain multiplication

**Week 6 — Supporting Data Structures**
- Dynamic arrays
- Binary heaps, heap ops
- Priority queues

**Week 7 — Graph Algorithms**
- Topological sort
- Strongly connected components
- Dijkstra
- Prim

Recommended practice for mid:
- **1–2 mid papers** + **2–3 quizzes** + **2 problem sets** from the semesters closest to your instructor’s style.

---

## Final Exam Survival Checklist (After Week 8)

After mid, what matters most (based on typical patterns and the Fall 2025 outline) is Weeks **10–16**.

**Week 10 — String Algorithms**
- Naive string matching, Rabin–Karp
- Finite automata-based matching
- KMP
- Z-algorithm

**Week 11 — Randomized Algorithms I**
- Probability basics
- Las Vegas vs Monte Carlo
- Randomized Quicksort, Quickselect

**Week 12 — Randomized Algorithms II**
- String equality testing
- Random sampling
- Pattern matching
- Primality testing

**Week 13 — Computational Complexity I**
- P, NP, NP-complete, NP-hard
- Polynomial-time reductions
- SAT/3SAT, Vertex Cover, Clique, etc.

**Week 14 — Computational Complexity II**
- coNP
- Intro to space complexity

**Week 15 — Approximation Algorithms I**
- Performance bounds
- Polynomial approximation schemes

**Week 16 — Approximation Algorithms II**
- FPTAS
- Intro to parameterized complexity

Recommended practice for final:
- Do **at least 3 finals** from different years/terms + **1–2 “hard” problem sets**.
- Use **CMU notes/resources** when your course mirrors that depth (especially for flow/LP/network-flow style thinking).

---

## Repository Structure

High-level map of where everything lives:

- `course_outline_fall_2025.pdf`  
  Official outline (Fall 2025, Dr. Shahid Hussain)

- `lectures/`
  - `2025-fall_-_shahid-hussain/` (main lecture + handout sets)
  - `2025-spring_-_jibran-rashid/`
  - Older supporting lecture sets (e.g., 2024-fall, 2023-spring)

- `exams/`
  - `01_first_term/` (term exams from multiple years)
  - `02_second_term/`
  - `03_mid_exam/`
  - `04_final_exam/`

- `problem-sets/`
  - Multiple years (Spring/Fall) including my submissions and older sets

- `quizzes/`
  - Multiple years (useful for quick revision and fundamentals)

- `practice-questions/`
  - Mixed practice PDFs + helpful diagrams

- `cmu_github_resources/` and `cmu_notes/`
  - External high-quality references used during Spring 2025 prep

- `books/`
  - Reference textbooks and supporting material

---

## Notes on Policy and Updates

- This repository is built to help **future students** using **past material and patterns**.
- For semesters where I am involved as a TA, I follow academic policy—materials meant for current students should be shared **after the semester ends** (where appropriate).
- External resources included here were used for learning/practice and are kept to reduce search time for students.
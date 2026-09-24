# Artifact 2.2: Mini Programming Portfolio Diagnostic Rubric & Interview Guide

> **Used in:** COSC 1010, COSC 1030, COSC 2409  
> **Instructor:** Trevor Swarm  

---

## 1. Diagnostic Scoring Rubric (100 Points Total)

| Criteria | Exemplary (Full Points) | Proficient | Developing | Unsatisfactory | Points |
| :--- | :--- | :--- | :--- | :--- | :---: |
| **Problem Decomposition & Architecture** | Program is divided into logical, modular components (functions/classes). Data structures chosen are optimal. | Code is modular with minor redundancies; clear functional breakdown. | Monolithic code structure; functions too broad or underutilized. | Disorganized code; no apparent structural decomposition. | 25 |
| **Logic & Correct Execution** | Code compiles/executes without uncaught exceptions. Handles edge cases gracefully. | Executes correctly on primary test cases; edge cases cause minor errors. | Logic errors in execution; basic requirements incomplete. | Code does not run or produces widespread runtime exceptions. | 25 |
| **Verbal Explanation & Defense** | Student lucidly explains control flow, variable lifecycles, and design rationale. Explains *why* choices were made. | Student explains what the code does line-by-line; minor hesitation on deep theoretical questions. | Student struggles to explain underlying mechanics; appears unfamiliar with portions of code. | Student cannot articulate how the code functions or who authored it. | 35 |
| **Code Style & Defensive Conventions** | Meaningful variable names, consistent indentation, helpful comments, proper error handling. | Readable code with minor stylistic inconsistencies; basic comments present. | Hardcoded magic numbers, vague variable names, inconsistent formatting. | Illegible code, zero comments, poor formatting. | 15 |

---

## 2. Sample Diagnostic Verbal Questions

During the live code clinic or video walkthrough, students are prompted to address questions such as:

1. *"Explain what would happen to memory if we passed this data structure by value instead of by reference here."*
2. *"Walk me through the lifecycle of this loop variable. When does it initialize, and when is it garbage-collected?"*
3. *"Why did you choose a dictionary/hash map here instead of a nested list? What is the trade-off in lookup time?"*
4. *"If a user inputs negative numbers or text into this prompt, how does your program recover?"*

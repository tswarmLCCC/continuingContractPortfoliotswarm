# Artifact 2.3: "Learn with AI" Socratic Practice Drill & Student Debrief

> **Evidence Group:** Classroom Practice, AI Literacy & Soft-Skill Scaffolding  
> **Course:** CMAP 1815 (Database Applications, Fall 2026)  
> **Instructor:** Trevor Swarm  
> **Source Archive:**  
> * **[Download Assignment Page (.pdf)](Unit_1_Learn_with_AI_Practice_Drill.pdf)**  
> * **[View Student Discussion Screenshot (.png)](AI_Prompt_Student_Use_Example.png)**

---

## 1. Instructional Design: Coaching Students to Struggle Productively

Alongside weekly units, students complete optional, low-stakes **"Learn with AI" Supplemental Practice Drills** designed to build both technical reasoning and soft skills (self-advocacy, curiosity, and critical verification) before high-stakes assessment. Rather than using AI as an answer generator, students assign a free-tier AI assistant (ChatGPT, Claude, Gemini, or Copilot) a strict Socratic persona—**Professor Codd**—and practice working through conceptual traps one question at a time.

### Coaching & Permission to Struggle
Students are explicitly coached that **not knowing is part of the process** and are given starter prompts to normalize productive struggle:
* **Say `"I don't know"` or `"I'm stuck"`:** Treating the AI as a tutor rather than a test.
* **Ask for Explanations & Hints:** *"Can you explain the underlying concept without giving me the code?"*
* **Ask for More Practice & Official Docs:** Requesting additional puzzles or links to official PostgreSQL 16 documentation.
* **Explore Edge Cases:** *"What happens if our data contains `NULL`s, empty strings, or duplicate rows?"*

### The Human-On-The-Loop (HOTL) Verification & Defense Protocol
Every drill pairs AI exploration with strict personal accountability:
> **The Golden Rule of CMAP 1815:** Never assume an AI's SQL answer is correct! Every single SQL snippet must be executed and verified against your live PostgreSQL 16 database in GitHub Codespaces before submission. You are 100% accountable for every query you submit and must be able to explain it line-by-line.

### Copy-and-Paste Master Prompt (Unit 1: Execution Order & Projection Hazards)
```text
Act as a strict, Socratic SQL professor named Professor Codd. I am a student learning SQL SELECT statements and relational database fundamentals in PostgreSQL 16. Do NOT give me direct answers or write the SQL for me. Instead, ask me one challenging question at a time to test my understanding of:
1. Why PostgreSQL evaluates FROM before SELECT during query execution.
2. The fundamental difference between physical row storage and relational projection.
3. Why 'SELECT *' is considered a dangerous anti-pattern in production microservices and reporting pipelines.
Start by asking me your first question about query execution order. Wait for my response before evaluating my reasoning and asking the next question.
```

---

## 2. Asynchronous Debrief & Evidence of Student Learning

After completing the interactive drill, students post a reflection in the **Unit 1 Discussion: Learn with AI Debrief & Reflection** answering:
1. The toughest question Professor Codd asked them.
2. What they realized about how PostgreSQL executes queries behind the scenes.
3. Why `SELECT *` causes production microservice failures.

### Anonymized Student Debrief Excerpts

#### Student A (Used Google Gemini) — *Conceptual Transfer & Mental Model Shift*
> *"The question Professor Codd asked me that was difficult was regarding the data structures and how the engine organizes information. It was a bit difficult to understand how PostgreSQL pulls and organizes the data and why it uses the tables in the format it does. One of the big things that was interesting to me was the way the code organizes the entries... The way it is built is quite interesting and the math involved in using the logical schema to break up the data architecture is definitely different from my way of thinking. The select statement is very broad and includes searching the entire data structure. This is great for simple queries, but if the SQL is being used for an application, this can lead to loss of functionality and the degradation of the database structure. Gemini is the one who ran the questions, and I did learn a decent amount from this activity."*

* **Instructional Takeaway:** The Socratic framing pushed the student beyond syntax memorization into thinking about logical schemas and why broad `SELECT *` queries degrade real-world applications.

#### Student B (Used Anthropic Claude) — *Critical AI Literacy & Cross-Disciplinary Reasoning*
> *"I found that the toughest question was not the question itself but how it was asked. When Claude asks me does where or select run first. I remembered the reading stating select runs first BUT it was asking in the context of the sample code it created rather than what rules of the language I should know. The example was also weak because it asked me why a value did not exist, and my AI major brain went to the data first. I responded with there is no value within the dataset that is >100. What I learned is that just like in coding, and math the order of which one enters a query is going to affect how the language understands it. For example, in trig and in C++ not having parenthesis around a value vs having parenthesis around a value changes the operation completely as well as the order of which it is read. All in all claude is great for taking data and making downloadable documents with visual charts and tables to reference but maybe is not the best AI for Socratic teaching as it does not specify context enough."*

* **Instructional Takeaway:** Demonstrates the **Human-On-The-Loop** goal in action—the student not only connected SQL execution order to Trigonometry and C++, but actively critiqued the AI tutor's pedagogical limitations rather than passively accepting its framing.

---

## 3. Primary Document Verification
* **Assignment Page PDF:** [Unit_1_Learn_with_AI_Practice_Drill.pdf](Unit_1_Learn_with_AI_Practice_Drill.pdf)
* **Student Discussion Screenshot:** [AI_Prompt_Student_Use_Example.png](AI_Prompt_Student_Use_Example.png)
* **Return to Project Portfolio:** [Project 2 Rationale & Analysis](../README.md)


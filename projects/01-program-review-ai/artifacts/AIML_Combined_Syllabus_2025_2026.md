# Artifact 1.2: AIML Course Curriculum Scaffold & Official Competencies

> **Program:** Associate of Applied Science in Artificial Intelligence  
> **Course Prefix:** AIML (Artificial Intelligence & Machine Learning) & COSC  
> **Author & Lead Designer:** Trevor Swarm  
> **Collaborators:** Program Director, Director of Assessment, STEM Leadership  
> **Original Documents:**  
> * **[Download Master AIML Syllabi (.docx)](AIML_Combined_Syllabus_2025_2026.docx)**  
> * **[Download Curriculog Competency Revision Matrix (.xlsx)](Curriculog_Competency_Mappings_Revisions.xlsx)**  
> * **[Download Revised Course Competencies (.docx)](Artificial_Intelligence_Course_Competencies_Revised.docx)**  
> **Source Archives:** `legacy/otherdocs/Artificial Intelligence Course Comptencies.docx`, `legacy/otherdocs/Comptency Mappings for Curriculog - May 1 Revisions.xlsx`, and `legacy/Project 1 Course Development/Artifacts/AIML Combined Syllabus 2025-2026.docx`  

---

## 1. Continuous Improvement: Program-Level Competency Evolution

Following the initial state approval of the AAS in Artificial Intelligence, we recognized that the original approved competencies were overly complex and contained significant redundancy across seven sprawling, multi-clause statements. 

To ensure our program outcomes were transparent, robust, and assessment-ready, I worked directly with my **Program Director** and **LCCC's Director of Assessment** to refine those competencies into simpler, more accessible, and easier-to-understand benchmarks. Together, we synthesized the framework into **four core, measurable Program Competencies** that capture the complete technical, strategic, ethical, and engineering scope of the degree. Our team then systematically mapped these refined competencies directly to course outcomes across different courses in the program.

### Comparison: Initial Approved Competencies vs. Refined Program Competencies

| Initial Approved Competencies (Complex & Redundant) | Refined Program Competencies (Simpler & Measurable) | Curricular Focus & Course Outcome Mapping |
| :--- | :--- | :--- |
| *1. "Evaluate business problems using common artificial intelligence concepts..."*<br>*2. "Evaluate usefulness of AI solutions with statistical analysis..."* | **1. Technical Execution:**<br>Evaluate machine learning and deep learning methodologies, and implement efficient models using appropriate programming frameworks and statistical analysis. | Core algorithmic modeling, Python frameworks (PyTorch/Scikit-Learn), regression/classification, neural architectures. |
| *3. "Solve social and business issues by applying AI project development principles..."*<br>*4. "Create AI solutions using appropriate programming languages..."* | **2. Strategic Application:**<br>Analyze organizational requirements to engineer effective solutions through the AI development lifecycle. | Problem decomposition, business intelligence, feasibility studies, end-to-end client deliverables. |
| *5. "Communicate in varied settings in a culturally responsive manner..."*<br>*6. "Create AI solutions in collaboration with diverse teams..."*<br>*7. "Evaluate issues of bias, culture, environment, ethics, regulations, and professional expectations..."* | **3. Responsible AI Practice:**<br>Assess the ethical, cultural, and regulatory implications of artificial intelligence systems to actively mitigate bias and ethical risks. | Bias mitigation, data sovereignty, privacy governance, ACM Code of Ethics compliance, oral/written technical defense. |
| *(Originally fragmented across disparate general IT and database electives)* | **4. Data Engineering:**<br>Design and evaluate data pipelines to prepare, clean, and govern datasets for machine learning applications. | Relational SQL, NoSQL, cloud ETL pipelines, data schema validation, quality assurance. |

---

## 2. Curriculog Competency Scaffolding Matrix (I &rarr; R &rarr; M)

Working with the Program Director and Director of Assessment, our team systematically mapped these refined competencies directly to course outcomes across the curriculum in Curriculog to indicate whether a competency is **Introduced (I)**, **Reinforced (R)**, or **Mastered (M)**:

| Course Prefix & Title | Technical Execution | Strategic Application | Responsible AI Practice | Data Engineering |
| :--- | :---: | :---: | :---: | :---: |
| **`AIML 1010`** Intro to Artificial Intelligence | **I** | **I** | **I** | — |
| **`AIML 1020`** Ethics in Artificial Intelligence | — | **I** | **M** | — |
| **`AIML 1030`** Intro to Machine Learning | **R** | **R** | **R** | **I** |
| **`COSC 2060`** Data Engineering | — | **R** | **R** | **M** |
| **`AIML 2030`** Natural Language Processing | **R** | **R** | **R** | **R** |
| **`AIML 2040`** AI for Computer Vision | **R** | **R** | — | **R** |
| **`AIML 2050`** AI for Business Solutions | **R** | **M** | **R** | **R** |
| **`AIML 2395`** AI Capstone Project | **M** | **M** | **M** | **M** |

---

## 3. Official Course Outlines & Approved Course Competencies

### 1. AIML 1010: Intro to Artificial Intelligence (3 Credits)
* **Catalog Description:** Provides an overview of Artificial Intelligence, its history, evolution, and its impact on various industries. Explores narrow AI, general AI, superintelligent AI, search algorithms, and intelligent agents.
* **Approved Course Competencies:**
  * Define and explain core concepts in artificial intelligence, including agent-based models and heuristic search.
  * Evaluate real-world problem domains appropriate for rule-based vs. statistical learning systems.
  * Formulate effective prompt engineering and human-in-the-loop workflows.
  * Construct basic decision trees and rule-based systems without requiring low-level syntax.

### 2. AIML 1020: Ethics in Artificial Intelligence (3 Credits)
* **Catalog Description:** Explores ethical considerations and implications of AI. Students explore issues related to privacy, algorithmic bias, automated decision-making, and societal impact.
* **Approved Course Competencies:**
  * Analyze systemic bias, training data provenance, and disparate algorithmic impact.
  * Evaluate intellectual property rights, data sovereignty, and copyright law in generative AI.
  * Formulate comprehensive algorithmic risk assessments for commercial and public sector AI deployments.
  * Articulate professional ethical responsibilities aligned with the ACM Code of Ethics.

### 3. AIML 1030: Introduction to Machine Learning (3 Credits)
* **Catalog Description:** Introduces fundamental concepts of machine learning: data acquisition, supervised learning, unsupervised learning, and model evaluation.
* **Approved Course Competencies:**
  * Evaluate the appropriateness of different machine learning algorithms for specific tasks, weighing strengths and weaknesses.
  * Build and train machine learning models on structured datasets using regression, decision trees, KNN, and SVMs.
  * Interpret model evaluation metrics (Accuracy, Precision, Recall, F1-Score, ROC-AUC) and diagnose overfitting/underfitting.
  * Analyze machine learning models for potential bias and suggest appropriate mitigation strategies.
  * Explain core machine learning concepts clearly to non-technical stakeholders.

### 4. AIML 2030: Natural Language Processing (3 Credits)
* **Catalog Description:** Explores computational techniques for analyzing, understanding, and generating human language, from text preprocessing to modern language models.
* **Approved Course Competencies:**
  * Preprocess, tokenize, and vectorize unstructured text data using NLP pipelines.
  * Implement supervised and unsupervised text classification, sentiment analysis, and topic modeling.
  * Apply semantic search and retrieval architectures using vector embeddings.
  * Design and evaluate prompt-engineered and fine-tuned language model workflows.

### 5. AIML 2040: Artificial Intelligence for Computer Vision (3 Credits)
* **Catalog Description:** Introduces computer vision techniques that train computers to interpret and understand visual data, including image processing, object detection, and segmentation.
* **Approved Course Competencies:**
  * Implement computer vision applications using industry libraries (OpenCV, Python) to solve specific visual recognition problems.
  * Apply image filtering, feature detection (edges, corners, blobs), and pixel segmentation techniques.
  * Critically assess the performance and latency of computer vision algorithms for real-time edge tasks.
  * Decompose real-world visual inspection challenges into modular image processing and vision sub-tasks.

### 6. AIML 2050: Artificial Intelligence for Business Solutions (3 Credits)
* **Catalog Description:** Practical application of AI technologies to solve modern business challenges, optimize enterprise operations, and build automated decision systems.
* **Approved Course Competencies:**
  * Identify and scope viable AI use cases across business verticals (finance, marketing, logistics, customer support).
  * Build workflow automations and decision-support prototypes integrating API-based AI models.
  * Perform cost-benefit, ROI, and feasibility analyses for adopting commercial vs. custom AI tools.
  * Evaluate regulatory compliance, privacy safeguards, and governance in enterprise deployments.

### 7. AIML 2395: Artificial Intelligence Capstone (3 Credits)
* **Catalog Description:** Capstone experience providing students the opportunity to apply accumulated knowledge and skills to a real-world client problem. Students design, implement, and present a complete AI solution.
* **Approved Course Competencies:**
  * Design an end-to-end technical solution for an authentic AI problem, weighing trade-offs of competing techniques.
  * Design, train, test, and deploy a machine learning or deep learning model to solve a real-world stakeholder problem.
  * Communicate the findings and technical architecture of an AI project effectively to both technical and non-technical audiences.
  * Critically analyze the ethical implications and operational safety guardrails of the deployed AI application.

### 8. COSC 2060: Data Engineering (3 Credits)
* **Catalog Description:** Comprehensive overview of data engineering: data ingestion, cleaning, transformation, storage, relational modeling, data warehousing, and cloud ETL pipelines.
* **Approved Course Competencies:**
  * Implement customized data pipelines to transform, clean, and stage data for delivery to a data warehouse.
  * Apply appropriate storage and processing techniques (relational SQL, NoSQL, data lakes) for specific engineering challenges.
  * Assess the performance, scalability, and latency of a data processing pipeline.
  * Resolve data quality, schema integrity, and governance issues within production data systems.

---

## 4. Planned Changes, IT Pathway Transition & AI Currency

* **Advisory Committee Consolidation & Pathway Transition:** While the program will continue leveraging strong advisory oversight, our AI Professional Advisory Committee will be formally merged and combined with the **Information Technology (IT) Pathway Professional Advisory Committee**. This consolidation directly aligns with the program transitioning administratively and academically from the School of Arts and Sciences over to the IT Pathway, creating a unified advisory pipeline for tech workforce education in Cheyenne.
* **Curriculum Sustainability & Emerging AI Currency:** Maintaining relevant technical curricula in artificial intelligence requires continuous adaptation. Moving forward, program evolution will rely on ongoing alignment with this unified IT advisory board, coupled with my continuous personal professional development through **Intel** and the **National Applied AI Consortium (NAAIC)**. By staying ahead of rapidly accelerating AI developments—specifically Large Language Models (LLMs) and, more recently, multi-level agentic AI instruction—we ensure the curriculum remains a living, state-of-the-art workforce credential.

---

## 5. Primary Document Verification
* **Download Master Syllabi:** [AIML_Combined_Syllabus_2025_2026.docx](AIML_Combined_Syllabus_2025_2026.docx)
* **Download Curriculog Mapping Matrix:** [Curriculog_Competency_Mappings_Revisions.xlsx](Curriculog_Competency_Mappings_Revisions.xlsx)
* **Download Revised Program Competencies:** [Artificial_Intelligence_Course_Competencies_Revised.docx](Artificial_Intelligence_Course_Competencies_Revised.docx)
* **Return to Project Portfolio:** [Project 1 Rationale & Analysis](../README.md)

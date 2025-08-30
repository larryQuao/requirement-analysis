# Requirement Analysis in Software Development.

## Introduction
This is the documentation about Requirement Analysis in Software Development

## What is Requirement Analysis?
Requirement analysis is a crucial stage in software development where the needs and expectations of stakeholders are identified and documented.

This phase ensures that the development team clearly understands what the software should achieve and the specific conditions it must meet. Thoroughly gathering and analyzing requirements at the start helps avoid misunderstandings and reduces the likelihood of costly changes later in development.

The requirements are typically categorized into two types: functional requirements and non-functional requirements.

Functional Requirements: These define the specific actions the software must be able to perform. Functional requirements focus on the core features and operations that the system needs to support.
Example: For an online banking application, a functional requirement might be: “The system must allow users to transfer funds between accounts.”
Non-Functional Requirements: Unlike functional requirements, non-functional requirements address the quality and performance of the system. They include criteria such as speed, security, scalability, and user experience, and describe how the system should perform under various conditions.
Example: A non-functional requirement for the same banking system might be: “The application should be able to handle 1,000 transactions per minute without performance issues.”
Both functional and non-functional requirements are vital for ensuring that the software not only fulfills its intended tasks but also performs efficiently and meets user expectations. Properly defining these requirements upfront helps guide the development process, leading to a more successful project outcome.

## Why is Requirement Analysis Important?
Requirement Analysis is arguably the most critical phase of the SDLC. Its importance cannot be overstated, as the success or failure of a project often hinges on how well this stage is executed.
1. **Forms the Foundation for the Entire Project**
  The requirements document (like the SRS) is the blueprint for the entire project. It guides the work of designers, developers, testers, and project managers. A solid foundation leads to a stable structure; a weak one guarantees problems down the line.
2. **Aligns the Final Product with Business Goals**
  The process ensures that the software being built actually solves the right business problem and delivers tangible value to the organization. It bridges the gap between the vague business needs of the stakeholders and the technical specifications needed by the developers.
3. **Reduces Costs and Rework**
  Fixing a requirement error during the coding phase is up to 10 times more expensive than fixing it during the analysis phase. Fixing the same error after release can be up to 100 times more expensive. Thorough analysis catches misunderstandings and errors early, when they are cheapest and easiest to correct.
4. **Manages Scope and Prevents "Scope Creep"**
  A well-defined and approved requirements document acts as a contract between the development team and the client. It sets clear boundaries for what will and will not be delivered in a given timeframe or budget, helping to manage expectations and prevent uncontrolled changes ("scope creep") that can derail a project.
5. **Enables Accurate Estimation and Planning**
  With clear requirements, project managers can better estimate the time, resources, and budget needed for development and testing. This leads to more realistic project plans and schedules.
6. **Provides a Basis for Testing and Quality Assurance**
  Test cases are derived directly from the requirements. A clear, testable requirement allows QA teams to create precise tests to verify that the software functions as intended. Without this, testing becomes subjective and incomplete.
7. **Improves Communication and Stakeholder Satisfaction**
  The process fosters continuous communication between the technical team and non-technical stakeholders. This shared understanding minimizes surprises at the end of the project and ensures the final product is what the stakeholders expected, leading to higher satisfaction and adoption.

## Key Activities in Requirement Analysis.
These key steps ensure that the captured needs accurately reflect the project's goals, are achievable, and are understood by all parties before development begins. 

### 1. Requirement Gathering
This is often considered the initial **"boots on the ground"** phase. It's the broad process of collecting all relevant information about what the system should do from various sources.

**What it is:**  
The proactive collection of any and all information, needs, desires, and constraints from stakeholders and existing systems.

**Key Focus:**  
Volume and breadth. Casting a wide net to ensure no potential need is missed.

**Common Techniques:**
- **Interviews:** One-on-one conversations with stakeholders to get detailed, deep insights.  
- **Surveys & Questionnaires:** Useful for gathering input from a large number of users quickly.  
- **Document Analysis:** Reviewing existing documentation, such as business process manuals, old system specs, or policy documents.  
- **Study of Existing Systems:** Analyzing the current system (if one exists) to understand its functionalities and shortcomings.  

**Analogy:**  
Think of it as a journalist gathering facts for a story—interviewing witnesses, collecting reports, and examining evidence. The goal is to get all the raw data.

---

### 2. Requirement Elicitation
This is a more nuanced and sophisticated subset of gathering. Requirements are often hidden, unstated, or assumed and need to be **"drawn out"** through careful techniques.

**What it is:**  
The art of discovering the underlying, often unarticulated, needs of stakeholders. It's about **why** something is needed, not just **what** is wanted.

**Key Focus:**  
Depth and understanding. Uncovering the true business problem that needs to be solved.

**Common Techniques:**
- **Requirements Workshops:** Facilitated meetings (e.g., JAD sessions) for collaborative definition of requirements.  
- **Brainstorming:** Generating a large number of creative ideas and potential solutions.  
- **Observation / Ethnography:** Watching users perform their jobs in their environment to capture real workflows and pain points.  
- **User Story Mapping:** Collaborative outlining of user activities and tasks to build a holistic view of functionality.  

**Analogy:**  
A therapist doesn’t just record a patient’s statements; they elicit deeper motivations and root causes. It’s the difference between a patient saying *“I’m stressed”* (gathered fact) and the therapist discovering it’s due to *fear of failure* (elicited need).

**Crucial Distinction:**  
- **Gathering** = collecting explicit information  
- **Elicitation** = discovering implicit/hidden needs  

---

### 3. Requirement Documentation
This is the process of formally recording the requirements in a **clear, consistent, structured, and unambiguous** manner. The output becomes the single source of truth for the project.

**What it is:**  
Creating a repository of analyzed requirements that can be understood by both technical and non-technical stakeholders.

**Key Focus:**  
Clarity, consistency, and organisation.

**Common Outputs:**
- **Software Requirements Specification (SRS):** A comprehensive formal document detailing all requirements.  
- **User Stories:** Short descriptions of a feature from an end-user perspective (*As a [user], I want [goal] so that [benefit]*).  
- **Use Cases:** Detailed interaction flows between a user (actor) and the system.  
- **Requirements Traceability Matrix (RTM):** A table linking requirements to their origin, design, implementation, and testing.  

**Analogy:**  
An architect takes ideas from the client (gathering/elicitation) and creates **blueprints (documentation)**. These ensure all builders work from the same plan.

---

### 4. Requirement Analysis and Modeling
This is the core **"sense-making"** activity. It involves refining, prioritizing, and modeling requirements for better understanding.

**What it is:**  
Breaking down, synthesizing, and representing requirements to uncover **errors, conflicts, and gaps**. It often includes abstract models to simplify complexity.

**Key Focus:**  
Analysis, refinement, and visualization.

**Common Activities:**
- **Prioritization:** Techniques like **MoSCoW** (Must-have, Should-have, Could-have, Won’t-have).  
- **Feasibility Analysis:** Checking technical and financial feasibility.  
- **Conflict Resolution:** Mediating between conflicting stakeholder requirements.  
- **Modeling:**  
  - **Process Models:** Data Flow Diagrams (DFDs), Flowcharts  
  - **Behavior Models:** Use Case Diagrams, Activity Diagrams  
  - **Data Models:** Entity-Relationship Diagrams (ERDs)  

**Analogy:**  
A detective analyzes gathered evidence—looking for connections, inconsistencies, and creating a timeline (model) to identify the culprit (core requirement).

---

### 5. Requirement Validation
This is the **quality check** to ensure requirements reflect stakeholders' intentions before development begins.

**What it is:**  
Confirming that the requirements define the system the stakeholder actually needs. It answers:  
👉 *“Are we building the right product?”*

**Key Focus:**  
Accuracy and agreement.

**Common Techniques:**
- **Reviews / Walkthroughs:** Formal presentations of the requirements for feedback.  
- **Prototyping:** Building mockups or simplified working models to validate user interface and features.  
- **Sign-off:** Formal approval by stakeholders confirming correctness and completeness.  

**Analogy:**  
Before construction begins, the architect walks the client through the blueprints (validation). The client confirms, *“Yes, this is the house I want.”* This prevents costly changes later.

---

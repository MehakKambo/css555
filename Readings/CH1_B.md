# Answers to Chapter-End Questions: Basic Concepts of Design

### (1–1) Discuss whether an activity can be considered a design activity if it has no fixed goals or objectives to achieve.
No, an activity cannot be considered a design activity if it lacks fixed goals or objectives. Design inherently involves intentionality and problem-solving to achieve specific outcomes. Without defined objectives, there is no framework to guide the design process, evaluate progress, or determine success.

---

### (1–2) Discuss why the output of design is a symbolic representation of an artefact for implementation rather than a real product.
The output of design is a symbolic representation because design involves planning and conceptualizing before actual implementation. Symbolic representations, such as diagrams, models, and specifications, allow for exploration, comparison, and refinement of ideas without the costs or risks of physical production. This approach is especially crucial for complex systems like software.

---

### (1–3) Discuss whether code in a high-level programming language is an appropriate form to represent the results of software design.
Code can represent the results of a software design but only partially. High-level code reflects implementation details rather than the abstract architecture or rationale behind the design. Proper software design documentation should include diagrams (e.g., UML), rationale, and constraints in addition to code.

---

### (1–4) Regarding design as a process of transformation, discuss what is transformed in software design.
In software design, user requirements (needs and constraints) are transformed into an actionable plan comprising architectural models, design patterns, and implementation instructions. This transformation bridges the gap between abstract needs and functional software artefacts.

---

### (1–5) Discuss why design is a creative activity.
Design is creative because it requires generating novel solutions to unique, often ill-structured problems. Designers must use abstraction, elaboration, and imaginative thinking to address constraints, resolve conflicts, and innovate within the solution space.

---

### (1–6) Discuss why design problems are often said to be ill-structured. Give an example of an ill-structured design problem.
Design problems are ill-structured because they lack clear definitions, have competing constraints, and involve dynamic and incomplete requirements. For example, designing a self-driving car involves unclear requirements (e.g., ethical decision-making), numerous constraints (e.g., safety, cost), and evolving technology.

---

### (1–7) Discuss why decision-making in the design process often faces uncertainty.
Decision-making faces uncertainty because:
1. Requirements and constraints may be incomplete or ambiguous.
2. Outcomes of design choices cannot always be predicted.
3. Multiple valid solutions often exist, each with trade-offs.
4. Design contexts, such as user needs or available technology, may change during the process.

---

### (1–8) Apply Lawson’s theory of constraints to analyze the following constraints:
#### (a) The software is to be executed on a PDA.
- **Generator:** External (hardware platform).
- **Domain:** External (outside designer’s control).
- **Function:** Practical (limits execution environment).

#### (b) The output of the software must be displayed on a screen of size 3″×2″.
- **Generator:** External (device specification).
- **Domain:** External.
- **Function:** Practical (usability and user interface design).

#### (c) The software should be easy to operate through a small keypad.
- **Generator:** User.
- **Domain:** External.
- **Function:** Practical (usability).

#### (d) The software can only be used if the user subscribes to a specific online service.
- **Generator:** Client (business requirement).
- **Domain:** Internal (designers can control implementation).
- **Function:** Economic (monetization strategy).

#### (e) The software will be implemented using the C language.
- **Generator:** Internal (development constraint).
- **Domain:** Internal.
- **Function:** Practical (resource and compatibility).

---

### (1–9) Discuss why testing and evaluation of designs are important.
Testing and evaluation ensure that:
1. The design meets all requirements and constraints.
2. Potential issues are identified and resolved early, reducing downstream costs.
3. Stakeholders' feedback is incorporated, improving usability and acceptance.
4. The final product aligns with its intended goals and performs as expected.

---

### (1–10) Design a bookshelf and answer the questions:
#### (i) Activities during the design process:
1. Define purpose and size of the bookshelf.
2. Identify constraints like material, budget, and space.
3. Sketch initial designs and refine them based on feedback.
4. Select materials and create a production plan.

#### (ii) Questions:
(a) **Objectives:** To create a functional, durable, and visually appealing bookshelf. These objectives are interrelated as durability influences functionality and aesthetics.
(b) **Initial Constraints:** Available space, material cost, and tools. Additional constraints, such as load capacity, discovered during design.
(c) **Stakeholders:** Designer (myself), user (myself), and potential manufacturers.
(d) **Designed Product:** A wooden bookshelf with adjustable shelves, described through diagrams and material specifications.
(e) **Production Plan:** Build frame first, then add shelves using pre-cut wood. Use screws and brackets for stability.
(f) **Design Decisions:** Use adjustable shelves for versatility; rationale: adapt to different book sizes.
(g) **Usage Conditions:** Indoors, stable surface. Consequences of violation: instability or damage.
(h) **Changes Brought:** Improved organization and accessibility of books.

---

### (1–11) Design a software system:
#### (i) Elements in the document:
1. Objectives: Functional requirements for the software.
2. Product Description: Diagrams and text.
3. Rationale: Justification of design choices.
4. Production Plan: Development timeline and tools.
5. Usage: Conditions under which the software operates.

#### (ii) Replacement of “bookshelf”:
(a) Objectives: Define user functionality and scalability.
(b) Constraints: Platform, user interface requirements.
(c) Stakeholders: Users, developers, and testers.
(d) Product Description: Diagrams, API specifications.
(e) Production Plan: Development in agile sprints.
(f) Design Decisions: Use modular architecture for maintainability.
(g) Usage Conditions: Proper configuration of dependencies.
(h) Changes: Streamlined user tasks.

#### (iii) Consequences of missing elements:
Incomplete documentation leads to misunderstandings, implementation errors, and stakeholder dissatisfaction.

---

### (1–12) Example of an outdated software system:
Early text-based email clients were considered user-friendly but are now outdated due to the rise of graphical interfaces. This shift aligns with Mayall’s axioms, such as **Time** (evolving user expectations) and **Value** (modern emphasis on usability).

---

### (1–13) Example of a bad design that became good:
Git was initially criticized for its complexity but is now widely adopted due to improved GUIs and user education. Mayall’s axioms like **Iteration** and **Change** highlight the iterative improvement process.

---

### (1–14) Examples of Information Systems:
- **Automational:** Payroll systems.
- **Informative:** Business intelligence dashboards.
- **Transformational:** Online marketplaces like Amazon.

---

### (1–15) Stakeholders in a hospital’s online patient information system:
1. Patients.
2. Doctors.
3. Nurses.
4. IT administrators.
5. Hospital management.
6. Regulatory authorities.

---

### (1–16) Applying Mayall’s axioms:
The bookshelf design demonstrates principles like **Iteration** (refining designs), **Synthesis** (combining features), and **Resources** (material availability).

---

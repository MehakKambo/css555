# Answers to Chapter-End Questions: Chapter 2 - Design Quality

### (2–1) The ISO standard ISO 9126 defines a hierarchical model of software quality with six top-level quality characteristics.  
#### (i) Definitions of software quality attributes:  
- **Functionality:** The ability to meet specified requirements (e.g., accuracy, suitability).  
- **Reliability:** Consistency of performance under specified conditions.  
- **Usability:** Ease of use and learning for users.  
- **Efficiency:** Resource utilization in relation to performance.  
- **Maintainability:** Ease of making changes to the system.  
- **Portability:** Ability to transfer software to different environments.  

#### (ii) Mapping ISO 9126 attributes to McCall’s model:
- **Functionality:** Correctness, reliability, and integrity.  
- **Reliability:** Reliability.  
- **Usability:** Usability.  
- **Efficiency:** Efficiency.  
- **Maintainability:** Maintainability, flexibility, and testability.  
- **Portability:** Portability and reusability.  

---

### (2–2) Consider the design of the bookshelf from exercise (1–10).  
#### (i) Evaluation of the design:  
The bookshelf design can be evaluated based on its modularity, simplicity, and practicality. It meets the stated requirements, uses available resources effectively, and accommodates future modifications.  

#### (ii) Quality-related properties of the design:  
- **Modularity:** Adjustable shelves for versatility.  
- **Simplicity:** Straightforward assembly process.  
- **Flexibility:** Ability to adapt to different book sizes and weights.  
- **Durability:** Materials chosen ensure long-term use.  

---

### (2–3) Discuss the most important quality attributes of a B2C e-commerce system.  
- **Usability:** Intuitive navigation and ease of use for customers.  
- **Reliability:** Consistent uptime to ensure transactions can be completed.  
- **Security:** Protection of sensitive customer data.  
- **Efficiency:** Fast response times during browsing and checkout.  
- **Scalability:** Ability to handle increased traffic during peak periods.  
- **Maintainability:** Easy updates for new products or services.  
- **Interoperability:** Integration with payment gateways and logistics systems.  

---

### (2–4) Discuss how architectural design, detailed design, and interface design affect robustness.  
- **Architectural Design:** A well-structured architecture ensures fault-tolerant mechanisms, like redundancy and failover systems, enhancing robustness.  
- **Detailed Design:** Robust algorithms and data validation prevent failures during abnormal conditions.  
- **Interface Design:** User-friendly interfaces reduce the likelihood of user errors, contributing to system robustness.  

---

### (2–5) Effects of architectural designs on specific software quality attributes:  
#### (a) **Testability:** Modular architecture simplifies testing by isolating components for individual verification.  
#### (b) **Usability:** A well-structured system allows smoother integration of user-friendly interfaces.  
#### (c) **Integrity:** Secure architecture protects data flows and interactions between components.  
#### (d) **Security:** Architectures with strict access controls and encryption protocols enhance system security.  

---

### (2–6) Using the quality attributes in section 2.3, build models of software design quality:  
#### (i) **Hierarchical Model:**  
- **Top Level:** Design quality.  
  - **Product-Oriented Attributes:** Modularity, simplicity, flexibility, efficiency, and conceptual integrity.  
  - **Process-Oriented Attributes:** Feasibility, manageability, risk, productivity, and resourcefulness.  

#### (ii) **Relational Model:**  
- **Direct Relationships:** Modularity ↔ Maintainability; Simplicity ↔ Efficiency.  
- **Inverse Relationships:** Flexibility ↔ Security; Efficiency ↔ Reusability.  
- **Neutral Relationships:** Usability ↔ Efficiency; Portability ↔ Integrity.  

---

### (2–7) Definitions of the following terms:  
#### (a) **Fault:** A defect or flaw in the software code or design that may lead to failure.  
#### (b) **Failure:** The inability of the software to perform its intended function under specified conditions.  
#### (c) **Error:** A mistake made by a human during software development, leading to a fault in the system.  

---
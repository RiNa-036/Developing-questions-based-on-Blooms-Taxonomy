# Software Engineering: Software Design

## OBE-Based Assessment (Bloom's Taxonomy, BNQF-Aligned)

| Item | Detail |
|------|--------|
| Name | Rina Akter |
| ID | IT24036 |
| University | Mawlana Bhashani Science and Technology University (MBSTU) |
| Department | Information and Communication Technology (ICT) |
| Course | Software Engineering |
| Total Marks | 40 |
| Time | 1 Hour |
| Domain | Cognitive |
| Bloom Levels | C1 Remember (Knowledge), C2 Understand (Understanding) |
| Framework | OBE, BNQF Level 7 |

---

## 1. Course Outcomes (CO)

| CO | Course Outcome | Bloom Level |
|----|----------------|:-----------:|
| CO1 | Define software design and explain its process. | C1, C2 |
| CO2 | Explain the principles of good design and interpret basic design metrics. | C1, C2 |
| CO3 | Describe software architecture and compare architectural styles. | C1, C2 |
| CO4 | Explain design patterns with their benefits and liabilities. | C1, C2 |
| CO5 | Describe user interface design principles and interaction styles. | C1, C2 |

---

## 2. Question Paper

**Answer all questions.**

### Question 1: Software Design Process (8 Marks, CO1)

| Part | Question | Marks | Bloom |
|:----:|----------|:-----:|:-----:|
| a) | Define software design and state its main input. | 2 | C1 |
| b) | Distinguish between architectural design and detailed design. | 3 | C2 |
| c) | Explain why recording the reasons behind design decisions helps software maintenance. | 3 | C2 |

### Question 2: Design Principles and Metrics (8 Marks, CO2)

| Part | Question | Marks | Bloom |
|:----:|----------|:-----:|:-----:|
| a) | Define coupling and cohesion. | 2 | C1 |
| b) | Explain why a good design aims for low coupling and high cohesion. | 3 | C2 |
| c) | Explain what CBO measures, and what LCOM2 = 0 and LCOM2 = 1 indicate. | 3 | C2 |

### Question 3: Software Architecture (8 Marks, CO3)

| Part | Question | Marks | Bloom |
|:----:|----------|:-----:|:-----:|
| a) | Define software architecture and name any two architectural styles. | 2 | C1 |
| b) | Compare the Layered style with the Pipes-and-Filters style, giving one suitable use of each. | 3 | C2 |
| c) | Explain the roles of the Model, View and Controller in the MVC style. | 3 | C2 |

### Question 4: Design Patterns (8 Marks, CO4)

| Part | Question | Marks | Bloom |
|:----:|----------|:-----:|:-----:|
| a) | Define a design pattern and name the three GoF pattern categories. | 2 | C1 |
| b) | Explain how the Observer pattern works and state one benefit. | 3 | C2 |
| c) | Explain the purpose of the Data Mapper pattern, with one benefit and one liability. | 3 | C2 |

### Question 5: User Interface Design (8 Marks, CO5)

| Part | Question | Marks | Bloom |
|:----:|----------|:-----:|:-----:|
| a) | Name any four user interface design principles. | 2 | C1 |
| b) | Explain consistency and recoverability, giving one example of each. | 3 | C2 |
| c) | Compare menu selection with command language interaction, giving one advantage of each and the type of user each suits. | 3 | C2 |

---

## 3. Question–CO Mapping

| Question | CO1 | CO2 | CO3 | CO4 | CO5 | Marks | Bloom |
|:--------:|:---:|:---:|:---:|:---:|:---:|:-----:|:-----:|
| 1(a) | ✔ |  |  |  |  | 2 | C1 |
| 1(b) | ✔ |  |  |  |  | 3 | C2 |
| 1(c) | ✔ |  |  |  |  | 3 | C2 |
| 2(a) |  | ✔ |  |  |  | 2 | C1 |
| 2(b) |  | ✔ |  |  |  | 3 | C2 |
| 2(c) |  | ✔ |  |  |  | 3 | C2 |
| 3(a) |  |  | ✔ |  |  | 2 | C1 |
| 3(b) |  |  | ✔ |  |  | 3 | C2 |
| 3(c) |  |  | ✔ |  |  | 3 | C2 |
| 4(a) |  |  |  | ✔ |  | 2 | C1 |
| 4(b) |  |  |  | ✔ |  | 3 | C2 |
| 4(c) |  |  |  | ✔ |  | 3 | C2 |
| 5(a) |  |  |  |  | ✔ | 2 | C1 |
| 5(b) |  |  |  |  | ✔ | 3 | C2 |
| 5(c) |  |  |  |  | ✔ | 3 | C2 |
| **Total per CO** | **8** | **8** | **8** | **8** | **8** | **40** | |

---

## 4. Distribution

| Bloom Level | BNQF Descriptor | Marks |
|-------------|-----------------|:-----:|
| C1 Remember | Knowledge | 10 |
| C2 Understand | Understanding | 30 |
| **Total** | | **40** |

---

## 5. BNQF Alignment

This paper assesses the Fundamental domain (discipline-specific knowledge and understanding) at BNQF Level 7 (Bachelor's).

---

## 6. Answer Hints (Marking Guide)

Accept any correct answer written in the student's own words.

### Question 1

- **a) [2]** Design is a problem-solving process that decides how software will be structured to meet its requirements (1). Input: the requirements (1).
- **b) [3]** Architectural design organises the software into components and shows their relationships (1.5). Detailed design describes the behaviour of each component (1.5).
- **c) [3]** Future maintainers understand why a choice was made (1). They avoid repeating rejected options (1). They can change the software more safely (1).

### Question 2

- **a) [2]** Coupling: a measure of interdependence among components (1). Cohesion: a measure of the strength of association of the elements within a component (1).
- **b) [3]** Low coupling keeps the effect of changes local (1). High cohesion gives each component a focused responsibility (1). Together they make software easier to understand, test and maintain (1).
- **c) [3]** CBO: the number of classes used by a class (1). LCOM2 = 0: every method uses every attribute, so cohesion is highest (1). LCOM2 = 1: no method uses any attribute, so cohesion is lowest (1).

### Question 3

- **a) [2]** Architecture: the structures of a system, made of elements, their relations and properties (1). Any two styles: layered, event-based, MVC, blackboard/repository, pipes and filters (0.5 + 0.5).
- **b) [3]** Layered: components are arranged in layers and each depends on the layer below (1). Pipes and filters: filters process data that flows through pipes (1). Uses: web information system; Unix command pipeline (0.5 + 0.5).
- **c) [3]** Model: represents information about the domain (1). View: displays the model in the user interface (1). Controller: takes user input, changes the model and gets the view updated (1).

### Question 4

- **a) [2]** Design pattern: a reusable core solution to a recurring design problem (1). Categories: Creational, Structural, Behavioral (1).
- **b) [3]** A subject keeps a list of registered observers (1). When its state changes, it notifies them automatically (1). Benefit: subject and observers are loosely coupled (1).
- **c) [3]** Data Mapper moves data between objects and the database while keeping them independent (1). Benefit: objects and database schema can change separately (1). Liability: the extra layer adds complexity (1).

### Question 5

- **a) [2]** Any four, 0.5 each: learnability, user familiarity, consistency, minimal surprise, recoverability, user guidance, user diversity.
- **b) [3]** Consistency: similar operations work in the same way (1). Recoverability: users can recover from mistakes (1). Examples: same Save button on every screen; an Undo option (0.5 + 0.5).
- **c) [3]** Menu selection: little to memorise and few typing errors; suits new or occasional users (1.5). Command language: fast and flexible; suits experienced users (1.5).

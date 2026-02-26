# SDLC Capstone — Sprint 1 Process Analysis

**Course:** Software Quality Assurance  
**Sprint:** Sprint 1  
**Model Selected:** Waterfall  
**Submission Type:** Team  
**Due:** End of class Thursday  

---

## Section 1 — Model Selection and Rationale

**Selected Model:** Waterfall  

### Rationale

The reason we chose the Waterfall model is that we had strict weekly deadlines and only a short amount of time to complete tasks. Each deadline aligned closely with a phase in the Waterfall SDLC.

* **Week 1:** Requirements, Design, Implementation  
* **Week 2:** Organized QA Testing  
* **Week 3:** Deployment and Maintenance  

We had only one week to produce an MVP, so organization was necessary to ensure a working product by the end of the week. Although the phases did not always feel distinct in the moment, they were still present and tied to deadlines.

While we did test features daily after adding them, this was informal testing by developers rather than structured QA. Structured QA occurred in Week 2.

Despite some feedback loops and iterative fixes, the overall structure still followed a phased, sequential approach consistent with Waterfall.

---

## Section 2 — Phase Analysis

### Phase: Requirements

**What Sprint 1 produced:**

* Spent all of Day 1 creating an action plan  
* Brainstormed ideas for the game  
* Selected *Karim Fistbumper*  
* Created a requirements document listing desired features  

**What strict adherence would have looked like:**

* No changes or additions after finalizing requirements  
* A more formal document  
* Formal sign-off from a client or company authority  

---

### Phase: Design

**What Sprint 1 produced:**

* Created a game skeleton  
* Defined game type, specs, and features  
* Brainstormed UI elements (theme, images, etc.)  

**What strict adherence would have looked like:**

* Fully completed design documentation  
* No coding before design was finalized  

---

### Phase: Implementation

**What Sprint 1 produced:**

* Built the game  
* Followed most planned features and specs  
* Sent issues back “up the chain” when problems were discovered  

**What strict adherence would have looked like:**

* Implemented only what was in the design plan  
* No added features outside the plan (e.g., Snake game)  

---

### Phase: Testing

**What Sprint 1 produced:**

* Week 2 dedicated to QA  
* Tested other teams’ games and our own  
* Fixed issues based on feedback  
* Prepared for deployment  

**What strict adherence would have looked like:**

* All testing confined strictly to the testing phase  
* No revisiting testing after the testing week concluded  

---

### Phase: Deployment

**What Sprint 1 produced:**

* Finalized product  
* Presented it in a slideshow  

**What strict adherence would have looked like:**

* Formal sign-off from compliance teams or external auditors  
* Official release approval process  

---
## Section 3 — Defect Case Studies

### Bug 1

**GitHub Issue:**  
[https://github.com/Staiwo100/Karim-Clicker-QA/issues/5](https://github.com/Staiwo100/Karim-Clicker-QA/issues/5)

**Description:**  
Game crashes when there are too many Nayans (800+).

**Phase that introduced the defect:**  
Implementation  

**Phase that caught it:**  
Testing  

**Would the model have caught it earlier?**  
Even with strict Waterfall adherence, this bug likely would not have been caught earlier because in-depth testing occurs during the formal Testing phase.

**Cost of catching it late:**

* Minimal cost in our case  
* Required rushed fixes  
* In a more complex project, this could have delayed delivery and required additional resources  

---

### Bug 2

**GitHub Issue:**  
[https://github.com/Staiwo100/Karim-Clicker-QA/issues/1](https://github.com/Staiwo100/Karim-Clicker-QA/issues/1)

**Description:**  
Players cannot buy an upgrade using coins earned through upgrades alone unless they click Karim first.

**Phase that introduced the defect:**  
Implementation  

**Phase that caught it:**  
Implementation (preliminary testing), later reinforced during QA  

**Would the model have caught it earlier?**  
Under strict Waterfall, it would likely have been discovered during the Testing phase instead of Implementation. However, we performed informal testing and caught it early.

**Cost of catching it late:**

* Would have been significantly harder to debug  
* QA identified the symptom but not the root cause  
* Early detection during implementation made the fix manageable  

## Section 4 — QA Assessment

### How QA actually operated

Gate model — We had a specific week dedicated solely to QA.

### Comparison to chosen model

This aligns with the Waterfall model, which includes a distinct Testing phase after Implementation.

### What QA would have looked like under strict adherence

* Direct collaboration between QA and developers during the testing phase  
* Immediate fixes rather than waiting for a separate week  

---

## Section 5 — Team Retrospective on Process

### The Gap

Lack of formalized testing toward the end when adding features and self-testing before deployment.

### What it cost the team

No significant cost due to small scope and team size.

### One change for Sprint 2

Strictly adhere to requirements and design plans to mitigate scope creep.



---

## Contributors

| Name              | Section Led |
|-------------------|------------|
| Jack Daubman     | 4          |
| Parth Thite       | 1          |
| Lucas Campbell | 2          |
| Biruk Yidnekachew | 3          |

---


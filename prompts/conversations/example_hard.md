# InterviewCoach Assistant - Hard Level Conversation

**Candidate:** Hi, I want to challenge myself with a hard-level technical mock interview.

**InterviewCoach:** Great! Let’s start with a system design question. How would you design a **URL shortening service** like bit.ly?

**Candidate:** First, I’d define requirements: short URLs, redirect to original URLs, analytics tracking. I’d use a database to store mappings. For generating short URLs, I can use a **hash function** or **base62 encoding** of an auto-increment ID. To handle scalability, I’d implement **load balancers**, **distributed caching** like Redis, and sharding for the database. Analytics can be collected asynchronously to avoid slowing redirects.

**InterviewCoach:** Excellent. Next, a complex algorithm question: “Given a **directed graph**, how do you detect cycles?”

**Candidate:** I would use **DFS**. During DFS, I maintain a recursion stack. If a node is visited and is in the recursion stack, we have a cycle. Alternatively, for a topological sort approach, if the number of visited nodes in the topological order is less than the number of nodes, there’s a cycle.

**InterviewCoach:** Correct. Now, a tricky behavioral scenario: “You have two conflicting project deadlines, and resources are limited. How do you prioritize?”

**Candidate:** I’d assess the **business impact** of both projects, talk with stakeholders to negotiate scope or deadlines, and reallocate resources for critical tasks. I’d also communicate risks clearly and provide a realistic timeline. Transparency and data-driven prioritization are key.

**InterviewCoach:** Very well answered. Hard-level mock complete.

---

**Feedback Summary:**
- Strengths: Strong system design thinking, clear algorithms, professional conflict management.
- Areas to Improve: Could add diagrams or pseudo-code in system design explanations for extra clarity.

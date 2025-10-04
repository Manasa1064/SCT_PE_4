# Example Conversation – Hard Level

**User:** Hi, I want to practice interview questions for a Software Engineer role.  

**Assistant:** Great! Let’s get started 🚀  
First, would you like **technical** or **behavioral** questions?  

---

**User:** Technical.  

**Assistant:** Alright, here’s a challenging one:  
👉 *"Explain how you would detect a cycle in a directed graph."*  

---

**User:** I’d use Depth-First Search (DFS) and maintain a recursion stack. If a node is visited and is also in the recursion stack, there’s a cycle. Alternatively, I could use topological sorting—if I can’t visit all nodes, a cycle exists.  

**Assistant (Feedback):**  
1. **Strength:** Strong algorithmic approach and alternative method mentioned.  
2. **Improvement:** Could explain the time complexity (O(V+E)) for clarity.  
3. **Tip:** Mention edge cases like disconnected graphs.  

**Score:** 4.5/5  

👉 Follow-up: *"Can you give a real-world scenario where detecting cycles in a graph is critical?"*  

---

**User:** In project task scheduling, tasks are dependent on each other. Detecting cycles ensures there are no circular dependencies, which would block completion. Another example is detecting deadlocks in operating systems.  

**Assistant (Feedback):**  
1. **Strength:** Real-world examples clearly linked to the concept.  
2. **Improvement:** Could mention how cycle detection integrates into build systems or databases.  
3. **Tip:** Always connect abstract algorithms to practical scenarios.  

**Score:** 5/5  

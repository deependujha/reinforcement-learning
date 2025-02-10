# Topics to be covered

- Markov Decision Processes & Planning
- Model-free Evaluation
- Model-free Control
- Policy Search
- Offline RL including RL from human feedback and Direct Preference Optimization
- Exploration
- Advanced Topics

!!! info "Offline RL?"
    Offline RL: Limited data

---

## AI tutor as a Decision Process

- Student initially doesn't know either addition (easier) or subtraction (harder).
- AI tutor agent can provide practice problems about addition or subtraction.
- AI agent gets rewarded +1 if student gets the problem right, -1 if wrong.
- Model this as a **`Decision Process`**. Define `state space`, `action space`, and `reward model`.
- What does the dynamics model represent? What would a policy to optimize the expected discounted sum of rewards yield?

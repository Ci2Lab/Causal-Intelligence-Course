# Causal Intelligence Course
## From Prediction to Reasoning to Decision Intelligence

![img](lectures/img/Cover/WHY.png)

**Instructor:** [Prof. Reza Arghandeh](https://www.hvl.no/en/employee/?user=Reza.Arghandeh)<br>
**Institution:** Western Norway University of Applied Sciences (HVL), Norway<br>
**Course level:** PhD/MS<br>  
**Year:** 2026

---

## Course Overview

This course introduces **causal intelligence** as a practical framework for moving beyond statistical prediction toward intervention, counterfactual reasoning, robust generalization, explainability, adaptivity, and decision-oriented AI.

Modern machine learning is highly effective at learning patterns from data. However, many scientific, engineering, and business problems require more than prediction. We often need to answer questions such as:

- What would happen if we changed a treatment, policy, process, or decision rule?
- Why did an outcome occur?
- What would have happened under a different action?
- Which intervention should be prioritized under limited resources?
- Will an AI model remain reliable when deployed in a new environment?

The central message of the course is:

> Prediction tells us what is likely to happen. Causality helps us understand what would happen if we act, what would have happened otherwise, and why a system behaves as it does.

The course combines conceptual foundations, mathematical formulation, causal graphs, simulated examples, Python implementation, and project-based learning.

---

## Learning Outcomes

By the end of the course, students should be able to:

1. Distinguish between association, prediction, intervention, and counterfactual reasoning.
2. Explain why standard machine learning is not sufficient for causal decision-making.
3. Formulate causal research questions from domain-specific problems.
4. Construct and interpret Directed Acyclic Graphs.
5. Understand causal discovery as a tool for proposing candidate causal structures.
6. Estimate average and heterogeneous treatment effects using causal machine learning.
7. Apply a disciplined causal workflow from research question to responsible interpretation.
8. Explain how causal reasoning supports robust, explainable, and adaptive AI systems.


---

## Course Chapters


| Chapter | Title | Main Points |
|---|---|---|
| 1 | Foundations of Causal Intelligence | Prediction vs. causality; association, intervention, and counterfactuals; Pearl’s causal ladder; observational vs. experimental data; confounding and selection bias. |
| 2 | Causal Graphs and Discovery | DAGs as assumption maps; forks, chains, and colliders; d-separation; backdoor adjustment; causal discovery as graph refinement. |
| 3 | Causal Machine Learning | Potential outcomes; ATE, ATT, ATU, and CATE; meta-learners; heterogeneous treatment effects; Double Machine Learning. |
| 4 | Causal Intelligence in Practice | Causal question formulation; variable audit; candidate DAGs; identification strategy; estimation; robustness checks; responsible reporting. |
| 5 | Causal AI for Robust, Explainable, and Adaptive Systems | Distribution shift; shortcut learning; causal explainability; intervention effects; decision intelligence; adaptive AI systems. |

---

## Course Progression

The course moves from foundational causal concepts to practical decision intelligence for real-world AI systems.

```text
Prediction
   ↓
Association, intervention, and counterfactuals
   ↓
Causal assumptions and graphical reasoning
   ↓
Causal discovery and adjustment
   ↓
Causal machine learning
   ↓
Applied causal workflow
   ↓
Robust, explainable, and adaptive AI
   ↓
Decision intelligence
```

---

## Suggested Reading

The course notebooks include chapter-specific references and further reading.

---

## Notes

The course material may be updated before or during teaching. Some examples, notebooks, references, and project instructions may change slightly to reflect student backgrounds, available time, and recent developments in causal AI.

---

## License

This repository is intended for educational and research use. Please cite the course and instructor when reusing or adapting the material.

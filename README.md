# Algorithmic Fairness Beyond Technical Metrics

### A Focused Literature Review

This literature review examines why algorithmic fairness cannot be understood through technical metrics alone. It focuses on how different mathematical definitions of fairness encode different assumptions, how bias can enter machine-learning systems through data and measurement, and why algorithmic systems should be evaluated within their broader sociotechnical context.

## Focus

The review examines three connected questions:

- How do different mathematical definitions of fairness lead to different evaluations of the same system?
- How can bias enter machine-learning systems before a model makes any predictions?
- Why might satisfying a technical fairness metric still be insufficient for evaluating fairness in practice?

## Key Themes

### Competing Definitions of Fairness

The review compares **demographic parity**, **equal opportunity**, and **equalized odds**, highlighting that satisfying one fairness criterion does not necessarily imply satisfying another. Choosing a fairness metric therefore also requires deciding what form of equality is relevant in a particular context.

### Sources of Bias

The review considers how **historical bias**, **representation bias**, and problems of measurement can affect machine-learning systems. A model may accurately learn patterns from its training data while still reproducing inequalities already present in that data.

### Fairness Beyond the Algorithm

Drawing on the sociotechnical perspective of Selbst et al. (2019), the review discusses the **Framing Trap** and **Formalism Trap**. These concepts illustrate why evaluating an algorithm in isolation can overlook social processes and institutional decisions that shape its real-world effects.

## Main Takeaway

Mathematical fairness metrics are useful tools for identifying particular forms of inequality, but they cannot determine by themselves what should count as fair. Evaluating algorithmic fairness also requires examining the assumptions behind the chosen metric, the data used to build the system, and the broader environment in which the system operates.

## Literature Review

The full review is available here:

**[Read the full literature review](literature_review.pdf)**

## References

- Barocas, S., Hardt, M., & Narayanan, A. (2023). *Fairness and Machine Learning: Limitations and Opportunities*. MIT Press.
- Mehrabi, N., Morstatter, F., Saxena, N., Lerman, K., & Galstyan, A. (2021). Bias and fairness in machine learning: A survey. *ACM Computing Surveys, 54*(6), Article 115.
- Mitchell, S., Potash, E., Barocas, S., D'Amour, A., & Lum, K. (2021). Algorithmic fairness: Choices, assumptions, and definitions. *Annual Review of Statistics and Its Application, 8*, 141–163.
- Selbst, A. D., Boyd, D., Friedler, S. A., Venkatasubramanian, S., & Vertesi, J. (2019). Fairness and abstraction in sociotechnical systems. *Proceedings of the Conference on Fairness, Accountability, and Transparency*, 59–68.

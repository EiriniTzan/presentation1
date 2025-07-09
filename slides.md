# From Concept Drift to Model Degradation
## An Overview on Performance-Aware Drift Detectors
Based on the review by Bayram et al., 2022  
Eirini Tzanaki, 2025

---

# What is this paper about?

- Review paper
- Focus: performance-based concept drift detection
- Surveys methods from 2011-2021
- Classifies existing methods and highlights gaps for future research

---

# Key Concepts

- **Concept Drift** = change in $P_t(X, y)$
- Types: real, virtual, recurring, sudden, gradual
- Focus: model performance degradation
- Variables: $X$ = input, $y$ = output

---

# Main Detection Strategies

### Statistical Process Control (SPC)
- DDM, EDDM, FHDDM
- Monitor error with thresholds

### Windowing Techniques
- ADWIN, STEPD, MDDM
- Compare recent vs past performance

### Ensemble Methods
- DWM, AWE, Learn++.NSE
- Detect disagreement between ensemble members (learners)

---

# Tools & Metrics
- **Tools**: Hoeffding bound, Fisher/Wilcoxon test, CUSUM
- **Metrics**: Accuracy, AUC, Entropy, Confusion Matrix
- **Learners**: Hoeffding Tree, Naive Bayes, ELM

---

# Why this paper matters?
- Clarifies terminology in the field
- Categorizes a wide range of methods
- Helps design robust ML systems in real-world (non-stationary) settings

---

# Thank you!




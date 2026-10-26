# Rutuja Patil

Final-year Computer Science student, Jaypee University of Engineering and Technology.  
I build and validate machine learning systems for prediction and decision problems, and I coordinate the technical work required to deliver them on schedule.

---

## Technical Work

### Drug-Likeliness Classification (Research-Oriented Pipeline)
**Problem.** Many “drug-likeness” models report high accuracy on random splits yet fail to generalize once chemical scaffolds are held out or the endpoint definition changes. The practical question is how much of the observed discrimination survives stricter validation and external transportability tests.

**Approach.** I constructed a balanced development set of 8,196 standardized molecules (DrugCentral-derived positives and ChEBI-derived negatives), generated 2048-bit Morgan fingerprints (radius 2), and trained a Random Forest (500 trees, class-balanced). Evaluation progressed through random splits → scaffold-separated splits (five seeds) → descriptor-calibrated matching → chemical-space applicability-domain analysis → external ClinTox endpoint-shift test. Logistic regression served as a simpler baseline. Bootstrap confidence intervals and systematic error analysis were included.

**Outcome.** Random-split ROC-AUC 0.916; repeated scaffold ROC-AUC 0.892 ± 0.022; descriptor-matched ROC-AUC 0.875 ± 0.023. Discrimination collapsed on the external ClinTox endpoint (ROC-AUC ≈ 0.47). The work quantifies that internal performance is real but chemically local and endpoint-dependent. Full pipeline, protocols, and frozen results are in the repository.

[Repository](https://github.com/rutujapatil-afk/drug-likeliness-v3)

### Rocket Launch Feasibility Prediction
**Problem.** Launch decisions depend on interacting weather and readiness variables. Manual rules are brittle; a data-driven go/no-go signal reduces uncertainty.

**Approach.** I assembled features (wind speed, temperature, humidity, pressure, technical readiness indicators), performed preprocessing and scaling, and compared logistic regression, Random Forest, and SVM under consistent evaluation.

**Outcome.** The ensemble produced reliable binary predictions that map directly to operational go/no-go decisions under the observed feature distributions.

[Repository](https://github.com/rutujapatil-afk/Predicting-rocket-launch-feasibility)

### Weather Trend Forecasting
**Problem.** Multi-location temperature series contain seasonality, non-stationarity, and occasional extremes that single models handle unevenly.

**Approach.** After cleaning, outlier filtering, and scaling of a global weather repository, I compared ARIMA, Prophet, Random Forest, and XGBoost, added Isolation Forest anomaly detection, and examined feature importance and spatial patterns.

**Outcome.** Prophet and XGBoost delivered the lowest error on held-out periods; anomaly detection flagged extreme events; air-quality variables showed measurable association with temperature in urban locations.

[Repository](https://github.com/rutujapatil-afk/Weather-Forecasting-Assessment)

### CO₂ Emission Forecasting (GAIL India)
**Problem.** Accurate short-term emission forecasts are required to adjust process parameters and reduce actual output.

**Approach.** Feature engineering on operational data followed by Random Forest regression, with explicit focus on predictive accuracy and downstream use of the forecasts.

**Outcome.** R² of 0.9989 on the evaluation set. The forecasts supported operational adjustments that reduced measured emissions by 14.46 %.

---

## Leadership and Coordination

I treat project coordination as an extension of the technical work rather than a separate activity.

- In the BuildWithIndia Hackathon I led a four-person team: defined the technical scope, maintained a shared task board (Trello/Asana), set experiment and integration milestones, and produced the status reports that kept the team aligned. The team finished in the top 5 000 of more than 25 000 entries.
- Across longer projects I maintain Gantt charts and MS Project schedules, map model-development stages to deliverable dates, and produce lightweight dashboards that surface blockers early. Technical decisions (feature sets, evaluation protocols, model selection) are documented so that non-technical stakeholders can track progress without re-deriving the rationale.

The same rigor applied to model validation is applied to schedule and communication: every claim is tied to an artifact or metric.

---

## Core Tools

**Languages**  
Python, C, C++, JavaScript

**Machine Learning & Data**  
scikit-learn, PyTorch, TensorFlow, Hugging Face, RDKit, Pandas, NumPy

**Experimentation & Delivery**  
Streamlit, Jupyter, Git, Google Colab

**Coordination**  
MS Project, Trello, Asana, Gantt reporting

---

## Selected Recognition

- AWS AI/ML Scholarship 2024  
- BuildWithIndia Hackathon – top 5 000 / 25 000+ teams  
- Academic record: 98.8 % (HSC), 95.2 % (SSC)

---

I am preparing applications for Master’s programs that emphasize reliable machine-learning systems, rigorous validation, and the ability to move from research prototype to operational use. The repositories above contain the code, evaluation protocols, and results that support the statements on this page.

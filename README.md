# Rutuja Patil

Final-year Computer Science student at Jaypee University of Engineering and Technology.  
I design and validate machine learning systems for prediction and decision problems, and I coordinate the technical work required to deliver them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rutuja-patil20/)
[![GitHub](https://img.shields.io/badge/GitHub-rutujapatil--afk-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rutujapatil-afk)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR.EMAIL@example.com)

---

## Selected Work

### Drug-Likeliness Classification
**Problem.** Models that report high accuracy on random splits often lose performance once chemical scaffolds are held out or the endpoint definition changes. The practical question is how much of the observed discrimination survives stricter validation.

**Approach.** Built a balanced set of 8,196 standardized molecules, generated 2048-bit Morgan fingerprints (radius 2), and trained a Random Forest (500 trees). Evaluation progressed from random splits to repeated scaffold-separated splits, descriptor-calibrated matching, chemical-space applicability-domain analysis, and an external ClinTox endpoint-shift test.

**Outcome.** Random-split ROC-AUC 0.916; repeated scaffold ROC-AUC 0.892 ± 0.022; descriptor-matched ROC-AUC 0.875 ± 0.023. Discrimination collapsed on the external endpoint (ROC-AUC ≈ 0.47). The results show that internal performance is real but chemically local and endpoint-dependent.

[Repository](https://github.com/rutujapatil-afk/drug-likeliness-v3)

### SeSE: Structural Analysis of Uncertainty in LLM Responses
**Problem.** Black-box uncertainty quantification for large language models is often reduced to token-level probabilities. Structural entropy of the semantic response graph may provide a complementary signal, but its robustness under controlled changes had not been systematically characterized.

**Approach.** Multiple responses per question were collected and organized into weighted semantic graphs using clustering and natural-language-inference relations. Structural entropy was computed with the original SeSE implementation. Controlled experiments examined threshold sensitivity, graph perturbation (edge-weight noise and dropout), repeated-evaluation stability, complexity conditions, and case-level failure structure.

**Outcome.** Threshold changes produced very small entropy variation (range 0.000198). Repeated evaluation and edge-weight noise produced substantially larger variation. In factual cases, incorrect responses consistently formed isolated singleton clusters; reasoning cases showed more fragmented structure. The work maps where the structural signal is stable and where it is sensitive.

[Repository](https://github.com/rutujapatil-afk/sese-reliability-study)

### Rocket Launch Feasibility Prediction
**Problem.** Launch decisions depend on interacting weather and readiness variables. Manual rules are brittle under changing conditions.

**Approach.** Assembled weather and technical-readiness features, performed preprocessing and scaling, and compared logistic regression, Random Forest, and SVM under consistent evaluation.

**Outcome.** The models produced reliable binary go/no-go predictions aligned with the observed feature distributions.

[Repository](https://github.com/rutujapatil-afk/Predicting-rocket-launch-feasibility)

---

## Leadership and Coordination

I treat project coordination as an extension of the technical work.

- Led a four-person team in the BuildWithIndia Hackathon: defined scope, maintained shared task boards, set experiment and integration milestones, and produced status reports. The team ranked in the top 5,000 of more than 25,000 entries.
- Across longer projects I maintain schedules in MS Project and Trello/Asana, map model-development stages to deliverable dates, and surface blockers early through lightweight status dashboards. Technical decisions are documented so progress remains traceable.

---

## Skills

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Machine Learning & Data**  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![RDKit](https://img.shields.io/badge/RDKit-8CA0A8?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Tools & Delivery**  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![MS Project](https://img.shields.io/badge/MS%20Project-217346?style=flat-square&logo=microsoft&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=flat-square&logo=trello&logoColor=white)

---

## Recognition

- AWS AI/ML Scholarship 2024  
- BuildWithIndia Hackathon – top 5,000 / 25,000+ teams  
- Academic record: 98.8 % (HSC), 95.2 % (SSC)

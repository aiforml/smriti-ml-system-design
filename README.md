# Smriti — ML System Design & Research Contribution

Smriti is an AI-powered learning retention platform that predicts memory decay and helps learners revise topics at the optimal time.

This repository documents my contribution to the project's research, planning, ML system design, and architecture.

## My Contributions

### Problem Identification
- Identified the problem of long-term memory decay in learning.
- Proposed an adaptive revision system based on forgetting curve theory.

### ML Research
- Researched the Ebbinghaus Forgetting Curve.
- Studied Duolingo's Half-Life Regression approach.
- Evaluated different ML approaches for retention prediction.

### Model Selection
Proposed the use of:
- Polynomial Regression for forgetting curve prediction
- Decision Tree Classification for weak topic detection
- K-Means Clustering for grouping similar learning topics

### Data Strategy
- Planned feature engineering for memory retention prediction.
- Defined evaluation metrics including R² Score and RMSE.
- Researched large-scale learning datasets for model training.

### System Architecture
Designed the overall workflow:

User Input
→ Retention Prediction
→ Topic Classification
→ Quiz Generation
→ Progress Tracking
→ Personalized Revision Recommendations

### AI Integration Planning
- Researched LLM-based quiz generation.
- Proposed Bloom's Taxonomy based question generation.
- Planned integration of external knowledge sources.

## Technologies Researched

- Python
- Scikit-learn
- Groq API
- Supabase
- Streamlit
- Machine Learning
- Bloom's Taxonomy
- Forgetting Curve Modeling

## Note

This repository represents my research, planning, and system design contribution in a team-developed project. The implementation was completed collaboratively by team members.

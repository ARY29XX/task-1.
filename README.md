CampusPulse Relationship Prediction Project — README

Overview This project delves into the CampusPulse dataset to learn and forecast student relationship status through a systematic, multi-level data science workflow. The notebook is divided into five incremental levels, each dependent on the previous one to offer predictive capability as well as interpretability.

Notebook Structure & Approach Level 1: Data Familiarization & Correlation Analysis

Loaded and explored the raw dataset.

Performed initial data inspection and cleaning.

Created a correlation heatmap to determine correlations between numeric features, laying the ground for further analysis.

Level 2: Cleaning & Preprocessing

Handled missing values, outliers, and inconsistent entries.

Executed encoding of categorical variables and normalization where required.

Got a clean dataset ready for strong analysis and modeling.

Level 3: Exploratory Data Analysis (EDA)

Derived and resolved at least five meaningful questions regarding student behavior, academics, and social life.

Developed and explored corresponding plots (e.g., violin plots, scatterplots, bar charts) to draw actionable conclusions.

Collated conclusions into concise, plot-based explanations, highlighting what the data indicates regarding student experiences.

Level 4: Relationship Prediction Modeling

Constructed and compared a range of classification models (including XGBoost, Ensemble, and CatBoost) to predict the relationship status.

Assessed each model using precision, recall, F1-score, and accuracy, with an emphasis on the relationship (positive) class.

Justified dropping less capable models and ultimately chose CatBoost for its better accuracy and well-balanced performance on the dataset.

Level 5: Model Explanation & Interpretation

Visualized decision boundaries using relevant 2D feature pairs to illustrate the ways that the model splits classes.

Used SHAP (SHapley Additive exPlanations) for both global feature importance and local explanations for individual students (one was predicted "Yes," one "No").

Offered plain-English explanations, identifying which scholarly, behavioral, and social attributes most impact the model's predictions.

Key Takeaways The workflow is reproducible and transparent, with every level well-separated in the notebook.

The end CatBoost model not only supplies the best predictive outcomes but, with SHAP, also offers actionable, explainable insights for stakeholders.

The project manages to balance interpretability with technical completeness in the sense that both modeling and results are made accessible and understandable to non-technical readers.

For specifics, see the notebook sections designated LEVEL 1 through LEVEL 5. Software Versions Used Python: 3.11.11

NumPy: 1.26.4

Pandas: 2.2.3

Seaborn: 0.12.2

Matplotlib: 3.7.2

Scikit-learn (sklearn): 1.2.2

SHAP: 0.42.1

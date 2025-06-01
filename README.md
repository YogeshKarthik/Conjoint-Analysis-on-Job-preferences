# Conjoint-Analysis-on-Job-preferences
📊 MBA Conjoint Analysis on Job Preferences (MNL Model)

This project uses Multinomial Logit (MNL) Regression to analyze how MBA students in India make trade-offs when choosing between job offers with varying attributes.
🎯 Objective

To identify which job-related attributes most influence MBA students' preferences and decision-making using choice-based conjoint analysis.
🧪 Methodology

    Choice Tasks: Each respondent answered 10 pairwise job choice tasks.

    Data Collection: Responses collected via a Google Form.

    Model Used: Multinomial Logit (MNL) using statsmodels.

    Encoding: One-hot encoding with user-specified base levels (e.g., 12 LPA as base salary).

    Analysis:

        Estimation of attribute-level coefficients.

        Utility-based attribute importance scores.

        Visualizations using heatmaps and bar plots.

📂 Project Contents

    conjoint_transformed_sample_csv.csv: The transformed dataset used for analysis.

    conjoint_analysis.ipynb / main script: End-to-end implementation of the MNL model, encoding, and visualization.

    Heatmaps and charts of model outputs.

    Supplementary data from demographic questionnaire (e.g., work experience, relocation preference).

📈 Sample Insights

    Job Security and Work-Life Balance emerged as the most influential attributes.

    Surprisingly, Salary was less important than expected for some respondents.

    The analysis helped uncover trade-offs individuals make between money, security, and lifestyle.

🧮 Techniques Covered

    Multinomial Logit regression (statsmodels.MNLogit)

    One-hot encoding with custom category ordering (sklearn.OneHotEncoder)

    Utility range-based attribute importance

    Hypothesis testing (t-tests) on demographic variables (via Excel)

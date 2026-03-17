# Instructor Effectiveness Modeling (EdTech)

## Project Overview

This project analyzes instructor effectiveness in an EdTech platform using machine learning.

Each instructor may teach multiple course batches. The goal is to evaluate instructor effectiveness using learner outcomes, engagement metrics, and feedback scores.

The analysis includes:

- Exploratory Data Analysis (EDA)
- Instructor Effectiveness Score definition
- Aggregation of batch-level data to instructor-level
- Machine learning model for predicting effectiveness tiers
- Feature importance analysis

---

## Dataset

Each row represents a **course batch** with the following metrics:

### Learner Outcomes
- completion_rate
- dropout_rate
- avg_score_improvement
- avg_quiz_score

### Engagement
- avg_watch_time
- assignment_submission_rate
- forum_activity_rate

### Feedback
- avg_feedback_score
- feedback_response_rate

---

## Methodology

1. Perform exploratory data analysis
2. Define an Instructor Effectiveness Score
3. Convert effectiveness score into tiers (Low / Medium / High)
4. Aggregate batch metrics to instructor-level
5. Train a Random Forest classifier
6. Evaluate model performance and interpret results

---

## Key Insights

- Completion rate and score improvement strongly influence instructor effectiveness.
- Engagement metrics such as watch time and assignment submission rate also play an important role.
- Feedback scores provide useful but potentially subjective signals.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Conclusion

This project demonstrates how machine learning can be used to estimate instructor effectiveness using learning outcomes, engagement, and feedback data. The model provides useful insights but should be used as a decision-support tool rather than the sole method for instructor evaluation.

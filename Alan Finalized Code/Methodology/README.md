# Methodology Directory

This directory contains documents and notes related to the methodology employed for predicting actual shipments by week aggregated using a current model.

## Files:

### ideas.pdf
- **Description:** Contains various ideas and considerations for improving the predictive model.
- **Contents:**
  - Removing outliers from the training set while retaining them in the testing set to reduce noise influence during prediction.
  - Utilizing previous actuals and latest estimates to predict actual shipments instead of omitting them from inputs.
  - Incorporating external economic data as indicators for actual shipments.
  - Exploring the use of correlation coefficient as weights in the neural network.
  - Considering the adoption of a sales prediction model found online.
  - Addressing issues related to categorical features and multicollinearity.

## Future Priorities (Time Permitted):
- **Analyze the Research Question:** Evaluate whether economic indicators serve as reliable predictors for actual shipments by comparing models with and without economic data inputs.
- **Experiment with External Dataset:** Investigate the effectiveness of using an external dataset to compare Kel and competitor brands' performance.
- **Create a Dashboard:** Develop a dashboard to visualize economic model results for enhanced insights and decision-making.

For any inquiries, please contact leonalan@msu.edu.

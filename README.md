# econ3916-lab19-random-forests
# Tree-Based Models: Random Forests

## Objective
I compared a single decision tree, linear models and a random forest on the California Housing data to see how they differ in accuracy and in what they say about which features matter.

## Methodology
- Loaded the California Housing dataset and split it into training and test sets.
- Fit four models on the training set: a single decision tree, ordinary least squares (OLS), Ridge regression and a random forest.
- Scored each model on the test set using R².
- Measured feature importance for the random forest in two ways: impurity-based importance (MDI) and permutation importance on held-out data.
- Tuned the random forest's hyperparameters with cross-validation on the training set, then scored the tuned model on the test set.
- Wrote my own prompt asking an AI assistant to produce a feature-importance chart, revised the prompt over [YOUR VALUE] rounds, and checked the chart against the importance values I had calculated myself.

## Key Findings
- **Model comparison:** On the test set, the single decision tree reached an R² of [YOUR VALUE], Ridge reached [YOUR VALUE], and the random forest reached [YOUR VALUE].
- **Feature importance:** The two importance methods did not agree on Latitude. MDI gave it a score of [YOUR VALUE], while permutation importance gave it [YOUR VALUE]. This shows that the method I use to measure importance can change how much a feature seems to matter.
- **Tuning:** After tuning the forest with cross-validation, its test R² was [YOUR VALUE].
- **AI-generated chart:** After [YOUR VALUE] rounds of prompting, I compared the AI's chart to my own numbers. Result: [YOUR RESULT].

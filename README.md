# sampling_assignment
## Alok Shree Koirala
## 102103157
## 3COE6

# Sampling and Model Evaluation in Data Analysis

Sampling is a methodology employed to gain insights into a population by analyzing statistics derived from a representative subset, thereby eliminating the need to examine each individual. To address the initial imbalance in the dataset, where there were 763 non-fraudulent cases and only 9 fraudulent cases, an oversampling approach was implemented. This involved generating additional instances of the minority class (fraudulent cases) to match the size of the majority class (non-fraudulent cases), resulting in a balanced dataset consolidated into a single data frame.

## Utilized Sampling Techniques:

1. **Simple Random Sampling:**
   - Involves randomly selecting samples from the population.

2. **Systematic Sampling:**
   - Entails regular interval selection after a random start.

3. **Cluster Sampling:**
   - Randomly selects clusters from the population.

4. **Stratified Sampling:**
   - Divides the population into subgroups based on certain criteria.

5. **Bootstrap Sampling:**
   - Resamples with replacement to create multiple samples from the original dataset.

These various sampling techniques were employed to ensure the representation of diverse subsets of the data, facilitating a more robust analysis and addressing the initial class imbalance.

## Models Used:

- **Random Forest**
- **Logistic Regression**
- **Naive Bayes**
- **Decision Trees**
- **KNN (K-Nearest Neighbors)**

## Model Evaluation Table:

| Model                | Simple Random Sampling | Systematic Sampling | Cluster Sampling | Stratified Sampling | Bootstrap Sampling |
|----------------------|------------------------|----------------------|-------------------|----------------------|---------------------|
| Random Forest        |    1.0000              |   1.0000             |    1.0000         |        0.9925        |        1.0000       |
| Logistic Regression  |    0.8831              |   0.8926             |    0.9717         |        0.8507        |        0.9250       |
| Naive Bayes          |    0.7403              |   0.7047             |    1.0000         |        0.7910        |        0.6000       |
| Decision Trees       |    0.9610              |   1.000              |    1.0000         |        0.9925        |        0.9625       |
| KNN                  |    0.8701              |   0.9329             |    0.9717         |        0.9478        |        0.9375       |

The line that follows indicates that Random Forest performed the best overall.

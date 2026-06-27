```markdown
# Top Machine Learning Algorithms

## Supervised Learning

### Linear Models

| ALGORITHM | DESCRIPTION | APPLICATIONS | ADVANTAGES | DISADVANTAGES |
|-----------|-------------|--------------|-------------|---------------|
| Linear Regression | A simple algorithm that models a linear relationship between inputs and a continuous numerical output variable | Use CASES | 1. Stock price prediction<br>2. Predicting customer lifetime value | 1. Explicable method<br>2. Interpretable by its output coefficients<br>3. Faster to train than other machine learning methods | 1. Assumes linearity between inputs and outputs<br>2. Can be overfit with small, high-dimensional data |

| Logistic Regression | A simple algorithm that models a linear relationship between inputs and a categorical output (0 or 1) | Use CASES | 1. Credit risk prediction<br>2. Customer churn prediction | 1. Interpretable and explainable<br>2. Less prone to overfitting when using regularization | 1. Assumes linearity between inputs and outputs<br>2. Can be overfit with small, high-dimensional data |

| Ridge Regression | Part of the regression family – it penalizes regression coefficients that have low predictive outcomes by shrinking their coefficients to zero. Can be used for classification or regression | Use CASES | 1. House price prediction for accommodate<br>2. Sales revenue prediction | 1. Less prone to overfitting<br>2. Better suited where data suffers from multicollinearity | 1. All the predictions are kept in the final model<br>2. Doesn't perform feature selection |

| Lasso Regression | Part of the regression family – it penalizes regression coefficients that have low predictive outcomes by shrinking their coefficients to zero. Can be used for classification or regression | Use CASES | 1. Predicting housing prices<br>2. Predicting clinical outcomes based on medical data | 1. Less prone to overfitting<br>2. Can handle correlated data<br>3. No need for feature selection | 1. Leads to poor interpretability as it can keep highly correlated variables |

### Tree-Based Models

| ALGORITHM | DESCRIPTION | APPLICATIONS | ADVANTAGES | DISADVANTAGES |
|-----------|-------------|--------------|-------------|---------------|
| Decision Tree | Decision Tree models make decision rules on the basis of input conditions. It can be used for classification or regression. | Use CASES | 1. Predicting credit churn prediction<br>2. Credit score modeling<br>3. Disease prediction | 1. Explicable and Interpretable<br>2. Can handle missing values | 1. Prone to overfitting<br>2. Sensitive to outliers |

| Random Forests | An ensemble learning method that combines the output of multiple decision trees | Use CASES | 1. Predicting house price modeling<br>2. Predicting housing prices | 1. Reduces overfitting<br>2. Higher accuracy compared to other models | 1. Training complexity can go high<br>2. Not easy to interpret |

### Gradient Boosting Regression

| ALGORITHM | DESCRIPTION | APPLICATIONS | ADVANTAGES | DISADVANTAGES |
|-----------|-------------|--------------|-------------|---------------|
| Gradient Boosting Regression | Gradient Boosting Regression engine boosts to make predictive models from an ensemble of weak predictive learners | Use CASES | 1. Predicting car emissions<br>2. Predicting rice yields based on weather data | 1. Better accuracy compared to other regression models<br>2. Can handle non-linear relationships | 1. Sensitive to outliers and can therefore cause overfitting<br>2. Computationally expensive and has high complexity |

| XGBoost | Gradient Boosting algorithm that is efficient & flexible. Can be used for both classification and regression tasks | Use CASES | 1. Predicting flight right on airlines<br>2. Claims processing in insurance | 1. Provides accurate results<br>2. Captures non-linear relationships | 1. Hyperparameter tuning can be complex<br>2. Does not perform well on sparse datasets |

| LightGBM Regressor | A gradient boosting framework that is designed to be more efficient than other implementations | Use CASES | 1. Predicting flight right on airlines<br>2. Predicting churn levels based on health data | 1. Can handle large amounts of data<br>2. High performance and fast training speed<br>3. Low memory usage | 1. Can be slow due to tree splitting and high memory usage<br>2. Hyperparameter tuning can be complex |

### Clustering

| ALGORITHM | DESCRIPTION | APPLICATIONS | ADVANTAGES | DISADVANTAGES |
|-----------|-------------|--------------|-------------|---------------|
| K-Means | K-Means is the most widely used clustering approach—it determines K clusters based on euclidean distances | Use CASES | 1. Customer segmentation<br>2. Recommendation systems | 1. Scales to large datasets<br>2. Simple to implement and Interpretable<br>3. Results in tight clusters | 1. Requires the expected number of clusters from the beginning<br>2. More sensitive with varying cluster sizes and densities |

| Hierarchical Clustering | A “bottom-up” approach where each data point starts as a separate cluster and the two closest clusters are merged together recursively | Use CASES | 1. File type detection<br>2. Document clustering based on similarity | 1. There is a need to specify the number of clusters<br>2. The resulting dendrogram is informative | 1. Does not result in good clustering for large datasets due to high complexity |

| Gaussian Mixture Models | A probabilistic model for normally distributed clusters within a dataset | Use CASES | 1. Customer segmentation<br>2. Recommendation systems | 1. Completes a probability on an observation belonging to a cluster<br>2. Can identify overlapping clusters<br>3. More accurate results compared to K-means | 1. Requires complete training data<br>2. Requires setting the number of expected mixture components or clusters |

### Association

| ALGORITHM | DESCRIPTION | APPLICATIONS | ADVANTAGES | DISADVANTAGES |
|-----------|-------------|--------------|-------------|---------------|
| Apriori algorithm | Rule-based approach that identifies the most frequent itemsets in a dataset without any prior knowledge of frequent itemsets property is used | Use CASES | 1. Customer segmentation<br>2. Recommendation engines<br>3. Prediction application | 1. Results are intuitive and Interpretable<br>2. Efficiently handles large datasets and can use based on the confidence and support | 1. Generates many uninteresting itemsets<br>2. Requires a large amount of training iterations<br>3. Results in many overlapping item sets |
```
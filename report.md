# AI Midterm Report — Eric Gerner

## 1. Preprocessing Summary
- **Dataset**: CIFAR-10, which consists of 50,000 training and 10,000 test images across 10 classes.

## 2. Model Development & Hyperparameter Tuning

| Model         | Key Hyperparameter(s)     | Value(s) Used             |
|---------------|----------------------------|---------------------------|
| KNN           | `n_neighbors`              | 5                         |
| Decision Tree | `max_depth`                | 25                        |
| Random Forest | `n_estimators`             | 100                       |
| SVM (SVC)     | `C`, `kernel`              | 10.0               |
| MLP           | `hidden_layer_sizes`, `max_iter` |100 |

## 3. Evaluation Metrics

| Model         | Accuracy | Precision | Recall | F1 Score |
|---------------|----------|-----------|--------|----------|
| KNN           | 0.XX     | 0.XX      | 0.XX   | 0.XX     |
| Decision Tree | 0.XX     | 0.XX      | 0.XX   | 0.XX     |
| Random Forest | 0.XX     | 0.XX      | 0.XX   | 0.XX     |
| SVM           | 0.XX     | 0.XX      | 0.XX   | 0.XX     |
| MLP           | 0.XX     | 0.XX      | 0.XX   | 0.XX     |

## 4. Confusion Matrices

_Insert confusion matrix screenshots here._

## 5. Insights & Model Comparison

- **Best Performing Model**: _ModelName_ — because it achieved the highest _accuracy/F1-score_ with generalizable predictions.
- **Worst Performing Model**: _ModelName_ — possibly due to _overfitting/high bias/slower convergence_.
- **Why Some Models Work Better**:
  - SVM and MLP handle high-dimensional space better (especially post-PCA).
  - KNN is sensitive to noise and lacks generalization.
  - Random Forest and Decision Tree vary with depth and ensemble size.
- **PCA Tradeoff**: Helped reduce runtime significantly, though it may remove important features affecting model accuracy.
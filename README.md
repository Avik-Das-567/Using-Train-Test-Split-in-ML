# Using Train-Test Split in ML
### App Link
- https://using-train-test-split-in-ml.streamlit.app/
---
### Why Use Train-Test Split in Machine Learning?
- In machine learning, we must **train** our model on some data and then **test** how well it performs on unseen data.
- **train_test_split** helps separate data into two parts:
  - **Training set -** used to train the model
  - **Testing set -** used to check model performance
---
### Common Usage in ML Flow
- **Collect data** (CSV, API, etc.)
- **Split data** into X (features) and y (target).
- **Use train_test_split** to divide into training and testing sets.
- **Train model** using training data.
- **Evaluate accuracy** on test data.
---
### Required Python Packages
- **`scikit-learn`**
- **`streamlit`**
---
### Output Example

| Area | Predicted Price |
| ---- | --------------- |
| 2000 | 298.0           |
| 1800 | 265.5           |

---
### Some Important Points
- Always split before training to prevent **data leakage**
- Use **`random_state`** for consistent results
- Models trained on all data may **overfit**
---

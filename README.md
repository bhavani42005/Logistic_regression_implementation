# Logistic Regression from Scratch

A complete implementation of **Logistic Regression from scratch** using only NumPy, built to understand the mathematics behind binary classification without relying on machine learning libraries.

The model is trained using **Gradient Descent** and evaluated against **scikit-learn's LogisticRegression** implementation. Both models achieved the **same accuracy** on the dataset, validating the correctness of the implementation.

---

## Features

- Logistic Regression implemented completely from scratch
- Gradient Descent optimization
- Sigmoid activation function
- Binary Cross-Entropy (Log Loss)
- Weight and bias updates using gradients
- Prediction using probability thresholding
- Performance comparison with scikit-learn

---

## Mathematical Concepts Implemented

- Linear combination:
  z = XW + b

- Sigmoid activation

- Binary Cross-Entropy Loss

- Gradient computation

- Gradient Descent optimization

---

## Project Structure

```
Logistic-Regression-From-Scratch/
│
├── logistic_regression.py     # Logistic Regression implementation
├── README.md
```

---

## Results

The custom implementation was compared against **scikit-learn's LogisticRegression** on the same dataset.

| Model | Accuracy |
|--------|----------|
| Logistic Regression (Scratch) | 92.30% |
| Logistic Regression (scikit-learn) | 92.30% |

Both implementations achieved the **same accuracy**, confirming that the custom implementation correctly reproduces the behavior of logistic regression.

---

## Technologies Used

- Python
- NumPy
- Pandas
- scikit-learn (only for comparison)

---

## What I Learned

Building Logistic Regression from scratch provided a deeper understanding of:

- How probabilities are generated using the sigmoid function
- Binary Cross-Entropy loss
- Gradient computation through differentiation
- Gradient Descent optimization
- Model convergence
- Weight initialization and updates
- How scikit-learn's Logistic Regression works internally

---

## Acknowledgements

This project was built as part of my journey to understand machine learning algorithms from first principles before using high-level libraries.

# ML-Learning

Applying concepts from Andrew Ng's ML Specialization through small hands-on projects.

## Projects

### Linear Regression — Student Performance
Built linear regression **from scratch** (cost function, gradient, gradient descent — no sklearn for the model itself) to predict a student performance index. Started with a single feature, then extended to a 5-feature multivariable version with feature standardization. Validated every step against scikit-learn.

- **Final R²: 0.99** on the 5-feature model
- Implemented vectorized gradient descent with NumPy
- Diagnosed and fixed convergence issues (learning rate tuning, divergence, standardization)
- Strongest predictor: previous scores (standardized weight ~17.7)

See [`Regression/`](./Regression) for the notebook.

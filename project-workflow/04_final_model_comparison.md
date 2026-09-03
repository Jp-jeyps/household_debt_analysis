# 📊 Final Model Comparison

After removing statistically insignificant variables, the reduced models were re-estimated and then compared using **R²**, **Adjusted R²**, and **standard error**.

<div align="center">

| 📐 **Model 1** | 💬 **Comparison** | 📐 **Model 2** |
|:---:|:---:|:---:|
| `Y = 1004.4 − 0.03X8 − 31839.48X11` | **VS** | `Y = 828.82 − 14343.61X9 + 2847.62X12` |
| **R² = 0.8367** | **Higher is better → Model 1** | **R² = 0.7899** |
| **Adjusted R² = 0.8004** | **Higher is better → Model 1** | **Adjusted R² = 0.7432** |
| **Standard error = 7.68** | **Lower is better → Model 1** | **Standard error = 8.71** |
| **✅ Selected** | **Model 1 performs better overall** | **❌ Not selected** |

</div>


Based on these measures, **Model 1** was selected as the final specification.

📈 **Recommended visual:**  
**Model Comparison Chart** — comparing R², adjusted R², and standard error for the two competing models.

---

# 🧪 Testing

The statistical significance of the selected model was reevaluated using the **F-test**.

**H₀:** - all slope coefficients are equal to zero.
**H₁:** - at least one explanatory variable has a non-zero coefficient.

📐**Final Model**:

- **F = 23.05**
- **p = 0.000288**

Since `p < 0.05`, the regression model is **statistically significant as a whole**.

📈 **visual:**  
**Actual vs Predicted Household Debt** — comparing observed `Y` with the values predicted by the final regression model.

---

<p align="left">
  <a href="03_regression_models.md">⬅️ Go back to: Regression models</a>
</p>

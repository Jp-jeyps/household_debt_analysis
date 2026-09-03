# 🔗 Correlation Analysis

After excluding variables with insufficient variability, the next step was to examine the relationships between the remaining explanatory variables and household debt.

## 📊 Correlation with Household Debt

**Pairwise correlation coefficients** were calculated between **Y** and the remaining explanatory variables to identify which factors showed the strongest relationships with household debt.

### Variables with relatively weak correlations with **Y** were excluded:

❌ **X2** — Average wage  
❌ **X3** — Minimum gross wage  
❌ **X5** — Social benefits  
❌ **X7** — Average loan value  
❌ **X14** — Non-interest consumer credit costs  

---

### Variables retained for further analysis:

✅ **X8** — Average value of loans  
✅ **X9** — Loans overdue by 31–90 days  
✅ **X10** — Loans overdue by 91–180 days  
✅ **X11** — Loans overdue by 181 days–1 year  
✅ **X12** — Loans overdue by more than 1 year  

📈 **Visual:** **Correlation Matrix** — a heatmap showing the pairwise correlation coefficients between household debt and the remaining explanatory variables.

## 🧩 Assessing Relationships Between Predictors

The selected variables were then compared with each other to identify **strong correlations between predictors** and assess potential **multicollinearity**.

A relatively strong correlation was found between **X8 and X11**. However, both variables were retained for the regression analysis.

📈 **Visual:** **Predictor Correlation Heatmap** — showing the pairwise correlations between **X8, X9, X10, X11, and X12**.

---

<p align="right">
  <a href="project-workflow/03_regression_models.md">➡️ Next: Regression models</a>
</p>

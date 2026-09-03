# 🔬 Regression models — Individual Coefficients

After selecting the initial variables for each specification, the two **regression models** were estimated using **Ordinary Least Squares (OLS)**:

<table align="center" width="90%">
<tr>
<th width="50%" align="center">📐 Model 1</th>
<th width="50%" align="center">📐 Model 2</th>
</tr>
<tr>
<td width="50%" align="left" valign="top">

**X8** — Average value of a loan<br>
**X11** — Share of loans overdue 181 days–1 year<br>
**X12** — Share of loans overdue over 1 year

</td>
<td width="50%" align="left" valign="top">

**X9** — Share of loans overdue 31–90 days<br>
**X10** — Share of loans overdue 91–180 days<br>
**X12** — Share of loans overdue over 1 year

</td>
</tr>
</table>

The **estimated coefficients** and their **statistical significance** were then evaluated.

---

# 🧪 Testing

<details>
  
<summary><h2>🔬 p-value Test</h2></summary>

The first test was based on the **p-value** of each estimated coefficient.

At **α = 0.05**:

`p < 0.05` → ✅ Statistically significant  
`p ≥ 0.05` → ❌ Not statistically significant

<table align="center" width="90%">
<tr>
<th width="50%" align="center">📐 Model 1</th>
<th width="50%" align="center">📐 Model 2</th>
</tr>
<tr>
<td width="50%" align="left" valign="top">

| **Variable** | **p-value** | **Result** |
|:---|---:|---|
| **X8** | 0.0045 | ✅ Significant |
| **X11** | 0.0002 | ✅ Significant |
| **X12** | 0.1260 | ❌ Not significant |

</td>
<td width="50%" align="left" valign="top">

| **Variable** | **p-value** | **Result** |
|:---|---:|---|
| **X9** | 0.0170 | ✅ Significant |
| **X10** | 0.2312 | ❌ Not significant |
| **X12** | 0.0450 | ✅ Significant |

</td>
</tr>
</table>

</details>

<details>
<summary><h2>🧮 Student's t-Test</h2></summary>

The same hypotheses were evaluated using the **Student's t-statistic**.

**H₀: βᵢ = 0** — the coefficient is not statistically different from zero.  
**H₁: βᵢ ≠ 0** — the coefficient is statistically different from zero.

The critical value was **t* = 2.262** with **9 degrees of freedom**.

`|t| > 2.262` → ✅ Statistically significant  
`|t| ≤ 2.262` → ❌ Not statistically significant

<table align="center" width="90%">
<tr>
<th width="50%" align="center">📐 Model 1</th>
<th width="50%" align="center">📐 Model 2</th>
</tr>
<tr>
<td width="50%" align="left" valign="top">

| **Variable** | **\|t\|** | **Result** |
|:---|---:|---|
| **X8** | 3.91 | ✅ Significant |
| **X11** | 6.44 | ✅ Significant |
| **X12** | 1.71 | ❌ Not significant |

</td>
<td width="50%" align="left" valign="top">

| **Variable** | **\|t\|** | **Result** |
|:---|---:|---|
| **X9** | 3.00 | ✅ Significant |
| **X10** | 1.30 | ❌ Not significant |
| **X12** | 2.37 | ✅ Significant |

</td>
</tr>
</table>

</details>

---

## 📝 Summary

The **p-value** and **Student's t-tests** confirm the same results for both models:

📐 **Model 1:** **X8** and **X11** are statistically significant; **X12** excluded ❌.  
📐 **Model 2:** **X9** and **X12** are statistically significant; **X10** excluded ❌.

---

<p align="right">
  <a href="04_final_model_comparison.md">➡️ Next: Final model comparison</a>
</p>

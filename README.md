<h1 align="left">
Household Debt in Poland </p>
  <sup>Exploratory Data Analysis & Econometric Modelling</sup>
</h1>

This project explores whether selected economic and credit-related factors are associated with **household debt in Poland.** 

🛠️ **Tools Used**: Excel Data Analysis ToolPak, Tableau</p>
📁 **Dataset**: Quarterly data for Poland, Q1 2022 – Q4 2024 (12 observations)

 ---
 
<h2>🧠 Project Goal</h1>

The main objective of the project is to identify which economic and credit-related variables are most relevant for explaining household debt.

### The analysis follows a data-driven variable selection process:

- 📊 **Exploring the data:** examining variability and correlations
- 🔎 **Selecting variables:** analysing pairwise correlations to identify relevant variables and potential multicollinearity
- 📐 **Building regression models:** estimating regression models with different sets of selected predictors
- 🔬 **Validating the model:** t-tests, p-values, and the F-test
- 📈 **Comparing models:** R², adjusted R², and standard error

<h2>📊 Data & Variables</h2>

The dependent variable is:

**Y — Household debt of Polish households (PLN billion)**

The explanatory variables were grouped into the **following categories**:

<details>
<summary>💰 <strong>Income & Labour Market</strong></summary>

| Variable | Description |
|---|---|
| **X1** | Average unemployment rate |
| **X2** | Average wage |
| **X3** | Minimum gross wage |
| **X5** | Social benefits |

</details>

<details>
<summary>💳 <strong>Credit Market</strong></summary>

| Variable | Description |
|---|---|
| **X6** | Average interest rate on consumer loans |
| **X7** | Average loan value |
| **X8** | Average value of loans |
| **X13** | Average APRC |
| **X14** | Non-interest consumer credit costs |

</details>

<details>
<summary>📉 <strong>Unpaid & Delayed Loans</strong></summary>

| Variable | Description |
|---|---|
| **X9** | Loans overdue by 31–90 days |
| **X10** | Loans overdue by 91–180 days |
| **X11** | Loans overdue by 181 days–1 year |
| **X12** | Loans overdue by more than 1 year |

</details>

<details>
<summary>📈 <strong>Macroeconomic Conditions</strong></summary>

| Variable | Description |
|---|---|
| **X4** | Consumer Price Index |

</details>

The data were collected from **NBP, GUS, BIK** and **Gov.pl**, with additional indicators calculated from the available data.

<p align="right">
  <a href="01_preliminary_analysis.md">➡️ Next: Preliminary Analysis</a>
</p>

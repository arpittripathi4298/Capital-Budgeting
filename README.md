# 📊 Capital Budgeting & Financial Performance Analysis
## 📌 Project Overview

This repository contains an end-to-end **Financial Performance & Capital Budgeting Model** built in Microsoft Excel (`Capital Budgeting.xlsx`). The model bridges historical financial trend analysis (FY21–FY25) with forward-looking investment appraisal for a **₹12,00,000** capital expenditure project over a 6-year horizon.

The goal of this workbook is to transform raw financial ledger and cash flow data into an actionable, executive-ready **Go / No-Go** investment decision.

---

## 🎯 Executive Summary & Verdict

Based on a **10% Discount Rate (Cost of Capital)**, the proposed capital investment demonstrates strong value creation, healthy liquidity recovery, and a substantial margin of safety.

### **Final Investment Verdict: STRONG GO ✅**

| Metric | Result | Benchmark / Hurdle | Interpretation |
| :--- | :--- | :--- | :--- |
| **Initial Investment** | ₹12,00,000 | — | Upfront capital outlay |
| **Net Present Value (NPV)** | **₹3,73,023.73** | $> ₹0$ | Positive net value creation above cost of capital |
| **Internal Rate of Return (IRR)** | **18.82%** | $> 10.00\%$ | Delivers an **8.82% safety buffer** over the hurdle rate |
| **Profitability Index (PI)** | **1.31** | $> 1.00$ | Generates **₹1.31** in present value per ₹1 invested |
| **Payback Period (Absolute)** | **3.75 Years** | $< 6$ Years | Capital recovered well within project lifespan |
| **Discounted Payback Period** | **4.68 Years** | $< 6$ Years | Leaves over 1.3 years of pure discounted profit generation |

---

## 📈 5-Year Company Financial Snapshot (FY21–FY25)

Before evaluating new capital allocation, the workbook establishes baseline company health through Year-over-Year (YoY) financial statement tracking:

* **Revenue Growth:** Consistent upward trajectory from **₹40,00,000** to **₹55,00,000** ($+37.5\%$ overall growth).
* **Net Profit Expansion:** Profitability doubled over the 5-year period, rising from **₹5,00,000** to **₹10,00,000** ($+100\%$).
* **Balance Sheet Tracking:** Comprehensive YoY tracking across **Assets, Liabilities, and Shareholder Equity** to assess capital structure stability.

---

## 🧮 Methodology & Core Formulas

All investment metrics are dynamically linked in Excel using Time Value of Money (TVM) principles:

* **Net Present Value (NPV):**
  $$NPV = \sum_{t=1}^{n} \frac{CF_t}{(1 + r)^t} - CF_0$$
* **Internal Rate of Return (IRR):** The discount rate $IRR$ that satisfies:
  $$0 = \sum_{t=1}^{n} \frac{CF_t}{(1 + IRR)^t} - CF_0$$
* **Profitability Index (PI):**
  $$PI = \frac{\text{Present Value of Future Cash Flows}}{CF_0}$$

*(Where $CF_t$ is the net cash inflow during period $t$, $CF_0$ is the initial investment, $r$ is the discount rate of $10\%$, and $n = 6$ years.)*

---

## 📂 Repository Contents

```text
├── Capital Budgeting.xlsx   # Core Excel model with financial statements and executive summary
└── README.md                # Project documentation and executive overview
```

---

## 🛠️ Skills Demonstrated

* **Corporate Finance:** Capital Budgeting, Time Value of Money (TVM), Discounted Cash Flow (DCF) Analysis.
* **Financial Analysis:** YoY Growth Tracking, Profitability Analysis, Balance Sheet Evaluation.
* **Technical Tools:** Microsoft Excel (Dynamic Financial Formulas, `NPV`, `IRR`, Executive Dashboards).
* **Decision Support:** Translating quantitative outputs into clear executive summaries.

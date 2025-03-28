# Financial Modeling: Blu Containers

## Overview

This project builds a comprehensive 5-year financial model for Blu Containers, a manufacturer of environmentally friendly water storage tanks made from recycled materials. The model integrates historical financials (2020–2022) with dynamic scenario-based forecasting and outputs full financial statements including Income Statement, Balance Sheet, and Cash Flow. The goal is to assess profitability, capital structure, and cash flow sustainability under multiple growth and risk conditions.

- **Powered by:** Financial Modeling Institute (FMI) 
- **Prepared by:** Vy Nguyen (Built as part of a CFA Level 1 financial modeling course)  
- **Tools Used:** Microsoft Excel

---

## Dataset

- **Input:** Audited financial statements of Blu Containers (2020–2022)  
- **Format:** Excel  
- **Structure:** Actuals for 2020–2022 and forecast from 2023–2027  
- **Output:** Dynamic model with toggling scenarios and linked statements  

---

## Modeling Methodology

The model was constructed from scratch using modular schedules and interlinked formulas to ensure consistency and traceability. Core modeling components include:

- **Revenue Forecasting:** Driven by unit volume and sales price assumptions per scenario  
- **COGS and Operating Costs:** Forecasted using inflation-adjusted per-unit or fixed cost assumptions  
- **Capital Expenditures & Depreciation:** Capex projected annually, straight-line depreciation applied across useful lives  
- **Working Capital:** Modeled via days outstanding for AR, AP, inventory, and other items  
- **Debt Schedule:** Manual senior debt repayments; interest calculated based on opening balances  
- **Tax Modeling:** 35% tax rate with deferred tax assumptions linked to timing differences  
- **Scenarios:** Toggle-based inputs for pricing, inflation, and sales volume impact full financials dynamically

---

## Key Assumptions & Scenario Design

The model includes three forecast scenarios (base, best, and worst case), allowing dynamic toggling through dropdowns. All assumptions are grounded in industry norms, company historicals, and strategic considerations for growth and cost risk.

### Key Assumptions

| Assumption Area          | Details |
|--------------------------|---------|
| **Product Pricing**      | Base case is aligned with industry research. Best case assumes 4% annual price increases driven by demand or brand positioning. Worst case applies a 4% annual decline due to market competition. |
| **Sales Volume Growth**  | Base case ranges from 4% to 2% as market matures. Best case assumes sustained 4–5% growth from market expansion. Worst case assumes reduced demand and plateaus around 2%. |
| **Cost Inflation**       | Base assumes 2.0–2.5% inflation. Best case uses lower 1.8–2.0% inflation from cost efficiencies. Worst case assumes flat 2.5% inflation across all years. |
| **Capital Expenditures** | Ranges from $16M in 2023 to $18M in 2027 to support future operations and capacity. |
| **Depreciation**         | Straight-line depreciation. Existing assets: 25 years; new assets: 30 years. |
| **Working Capital**      | Gradual improvements in receivables and inventory turnover; stable assumptions for other items. |
| **Debt & Equity**        | $25M annual repayments on senior term debt. No stock issuance or buybacks assumed. |
| **Interest Rates**       | 1% on cash balances; 6% on revolver and term loan. |
| **Tax Rate**             | 35% effective rate with $5M/year deferred tax adjustment. |
| **Extraordinary Items**  | No one-time gains, losses, or unusual flows assumed. |

### Scenario Summary

| Scenario      | Sales Price Change | Volume Growth | Cost Inflation |
|---------------|--------------------|---------------|----------------|
| **Base Case** | 0%                 | 4% → 2%       | 2.0–2.5%       |
| **Best Case** | +4% annually       | 4–5% annually | 1.8–2.0%       |
| **Worst Case**| -4% annually       | ~2%           | 2.5% flat      |

Each scenario reflects different market and cost conditions to evaluate earnings resilience and capital adequacy.

---

## Key Results

| Metric               | 2023 | 2024 | 2025 | 2026 | 2027 |
|----------------------|------|------|------|------|------|
| Revenue ($M)         | 252  | 234  | 281  | 281  | 268  |
| EBITDA Margin        | 29.3%| 20.2%| 30.7%| 27.3%| 20.3%|
| Net Income ($M)      | 30   | 13   | 39   | 33   | 19   |
| Net Income Margin    | 11.8%| 5.5% | 13.8%| 11.8%| 7.2% |
| Revenue Growth       | 23.3%| -7.5%| 20.4%| 0.0% | -4.6%|

- The model reveals substantial volatility in revenue and profitability across the forecast years  
- EBITDA margin fluctuates due to variable pricing and inflation exposure  
- Net income peaks in 2025 and declines under margin compression in later years  
- Revenue stagnates after 2025 under base case assumptions  

---

## What I Learned

- How to design and link operating, investing, and financing schedules into one model  
- The importance of transparent, logic-based assumptions for stakeholder communication  
- The impact of sales, pricing, and cost structures on margins and valuation inputs  
- How small input changes ripple through free cash flow and leverage outcomes  

---

## What I Plan to Improve

- Add dashboards and KPI visuals for clearer communication  
- Expand the model to include valuation (DCF, comps, multiples)  
- Integrate ratios such as ROIC, EBITDA margin, and FCF conversion 

---

## About Me
Hi, I’m Vy Nguyen and I’m currently pursuing my MS in Business Analytics at UC Irvine. I’m passionate about data analytics in Finance and Investment. Connect with me on [LinkedIn](https://www.linkedin.com/in/vy-ngoc-lan-nguyen).

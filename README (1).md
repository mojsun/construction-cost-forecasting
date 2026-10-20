# Construction Cost Forecast & Variance Analysis

**Forecasting cost, cash flow and schedule impacts across a portfolio of capital projects, and explaining *why* forecasts change.**

`Power BI` · `Excel` · `SQL` · `Microsoft Copilot` · `Forecasting` · `Variance Analysis` · `Scenario & Sensitivity Analysis`

> **Status:** Business problem, data model and analysis plan are complete. The dataset, Power BI dashboard and findings are being added in stages; see the [roadmap](#roadmap).

---

## Business problem

A retailer is building and renovating **20 store and distribution projects** across Canada. Finance and Construction leadership review the portfolio every month and need clear answers to:

1. **Where will each project finish on cost:** budget vs. actual-to-date vs. forecast at completion?
2. **Which projects are over or under budget, and why?** What are the main **variance drivers** (materials, labour, scope changes, schedule delays, permits)?
3. **What does the cash flow look like** month by month for the rest of the fiscal year?
4. **What if conditions change?** How sensitive is the portfolio forecast to material cost inflation or schedule delays?

## Approach

```
Project budgets   ──►  Monthly actual   ──►  Forecast at       ──►  Variance analysis     ──►  Scenario &          ──►  Executive
& schedules            costs (by cost        completion            (budget vs. forecast,      sensitivity            dashboard &
                       category)             (EAC)                 by driver)                 analysis               narrative
```

| Step | Method | Question it answers |
|---|---|---|
| 1. Data quality audit | Check missing, duplicate and miscoded cost entries; reconcile totals | Can we trust the numbers? |
| 2. Cost to date | Actual cost by project, month and cost category | Where are we today? |
| 3. Forecast at completion | Actual to date + estimate to complete, adjusted for progress (% complete) | Where will each project finish? |
| 4. Variance analysis | Budget vs. forecast, split by driver (materials, labour, scope change, delay, permits) | Why is the forecast different from the budget? |
| 5. Cash flow forecast | Monthly spend curve for remaining work | How much will we spend each month? |
| 6. Scenarios | Base, +10% materials, 2-month delay | How exposed is the portfolio? |
| 7. Narrative | Plain-language explanation of top variances and recommended actions | What should leadership do? |

## Planned deliverables

| Deliverable | What it shows | Tool |
|---|---|---|
| **Portfolio cost dashboard** | Budget vs. actual vs. forecast by project, variance by driver, cash flow, and scenario comparison | Power BI |
| **Variance explanation table** | Top variances with root cause and recommended action, written for non-technical readers | Excel |
| **Executive summary** | One page: portfolio status, key risks, and decisions needed | PowerPoint |
| **Data quality checks and assumptions log** | Audit results and documented forecasting assumptions | Excel / Markdown |

## Roadmap

- [x] Define the business problem and analysis questions
- [x] Design the data model, forecast method and variance drivers
- [ ] Prepare and document the project cost dataset
- [ ] Data quality audit
- [ ] Forecast at completion and cash flow model
- [ ] Variance analysis by driver
- [ ] Scenario and sensitivity analysis
- [ ] Power BI dashboard
- [ ] Executive summary and key findings (added to this README)

## Key findings

*To be added once the analysis and dashboard are complete.*

---

*Synthetic data created for this project. All projects and figures are fictional.*

**Moji Shahi** · Master of Management Analytics candidate, Smith School of Business, Queen's University
[LinkedIn](https://www.linkedin.com/in/m-khorashahi) · [GitHub](https://github.com/mojsun) · [Portfolio](https://moji-shahi-portfolio.vercel.app/)

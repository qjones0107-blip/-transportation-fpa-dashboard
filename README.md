# Transportation FP&A Dashboard

An executive financial planning and analysis model for a transportation operation. The project connects operating activity, service performance, cost drivers, budget variance, and scenario forecasting in one Excel workbook.

![Transportation FP&A Dashboard](images/transportation-fpa-dashboard.png)

## Executive summary

The base forecast projects **$11.08M in revenue**, **$1.79M in EBITDA**, and a **16.2% EBITDA margin** for 2026. Revenue is projected to finish **$278K above budget**, while EBITDA remains approximately **$206K below budget**. The results show that volume growth alone does not guarantee profit performance when fuel, driver labor, maintenance, empty miles, and service efficiency remain under pressure.

This project demonstrates how FP&A can translate transportation data into management decisions involving pricing, cost control, asset utilization, service performance, and profitability.

## Business questions

- Will the operation meet its annual revenue and EBITDA targets?
- Which transportation cost categories have the greatest effect on margin?
- How do empty miles and fleet utilization affect cost per mile?
- Can higher shipment volume offset fuel, labor, and maintenance costs?
- What changes under base, upside, and downside operating scenarios?

## Dashboard highlights

| Metric | Base forecast |
|---|---:|
| FY revenue | $11.08M |
| Revenue vs budget | +$278K |
| FY EBITDA | $1.79M |
| EBITDA margin | 16.2% |
| EBITDA vs budget | -$206K |
| On-time delivery | 95.5% |
| Fleet utilization | 86.7% |
| Empty miles | 13.6% |
| Cost per mile | $1.85 |

## Key findings

1. **Revenue exceeds plan, but profitability does not.** The model projects revenue above the $10.8M budget while EBITDA remains below the $2.0M budget.
2. **Margin improves during the forecast period.** Monthly EBITDA margin rises toward 19% as revenue per load improves and transportation efficiency stabilizes.
3. **Empty miles remain a controllable cost opportunity.** Lowering empty miles toward 12.5% would reduce fuel, labor-hour exposure, and maintenance costs.
4. **Service performance is close to target.** On-time delivery averages 95.5% against a 96% objective, while fleet utilization averages 86.7% against an 88% objective.
5. **Driver labor is the largest operating-cost category.** Capacity planning, route efficiency, and service-time control have a direct effect on EBITDA.

## Management recommendations

- Improve backhaul planning and lane pairing to reduce empty miles.
- Review fuel-surcharge coverage when diesel exceeds $3.70 per gallon.
- Protect on-time delivery while raising fleet utilization toward 88%.
- Track revenue per load, cost per mile, and EBITDA margin together when evaluating growth.
- Use the downside scenario during monthly forecast reviews to identify corrective actions early.

## Scenario model

The workbook includes three selectable cases:

- **Base:** current operating outlook
- **Upside:** stronger volume, pricing, utilization, and fuel efficiency
- **Downside:** weaker volume, higher fuel and labor costs, and reduced efficiency

Changing the case number on the `Assumptions` worksheet updates the September–December forecast, annual KPIs, and dashboard charts while preserving January–August actuals.

## Financial and operating methodology

The model uses driver-based calculations rather than applying one percentage to total revenue:

- Revenue = loads × revenue per load
- Loaded miles = loads × loaded miles per load
- Total miles = loaded miles ÷ (1 − empty-mile percentage)
- Fuel cost = total miles ÷ fuel economy × fuel price
- Driver labor = driver hours × labor cost per hour
- Maintenance = total miles × maintenance cost per mile
- EBITDA = revenue − total operating cost
- Cost per mile = total operating cost ÷ total miles

## Skills demonstrated

- FP&A and rolling forecasts
- Budget-versus-actual analysis
- Scenario and sensitivity modeling
- Transportation unit economics
- Revenue and expense-driver modeling
- EBITDA and margin analysis
- Executive dashboard design
- Excel formulas including `CHOOSE`, `SUM`, `SUMPRODUCT`, and linked schedules
- Management recommendations supported by financial and operating results

## Repository structure

```text
transportation-fpa-dashboard/
├── README.md
├── dashboard/
│   └── Quincy_Jones_Transportation_FP&A_Dashboard.xlsx
├── data/
│   ├── 2026_transportation_actuals.csv
│   ├── forecast_assumptions.csv
│   └── annual_summary.csv
└── images/
    └── transportation-fpa-dashboard.png
```

## How to use the workbook

1. Download the Excel workbook from the `dashboard` folder.
2. Open the `Dashboard` worksheet for the executive view.
3. Open the `Assumptions` worksheet.
4. Change the case number to `1`, `2`, or `3`.
5. Review the updated forecast, KPIs, charts, and monthly operating model.

## Data notice

All companies, records, amounts, assumptions, and operating results are synthetic. No employer, customer, employee, or proprietary transportation data is included.

## Author

**Quincy Jones**  
Transportation, Operations, Finance, and Business Analytics  
[GitHub profile](https://github.com/qjones0107-blip)

# Corporate Spend Sample PBIX

## Overview

A comprehensive corporate IT spending analysis dashboard providing year-to-date (YTD) budget tracking, variance analysis, and trend forecasting. This project enables financial and operations teams to monitor spending patterns across multiple IT business areas and geographic regions, with detailed plan variance tracking and period-by-period performance metrics.

---

## Key Features

### 📊 Two Main Dashboards:

1. **YTD IT Spend Trend Analysis**
   - Actual vs. planned spending by IT area
   - Geographic variance analysis by country/region
   - Spend trends across business areas over time
   - Period-by-period performance comparison
   - Sales region filtering (Europe focus)

2. **Plan Variance Analysis**
   - Variance tracking at multiple levels (LE1, LE2, LE3)
   - Monthly variance percentage trends
   - Variance by country and business area
   - Detailed spend breakdown by business area
   - Plan vs. actual comparison matrix

---

## Key Metrics

### Spending Summary (Europe Region)

| IT Area | Actual | Plan | Variance |
|---------|--------|------|----------|
| Infrastructure | $15.2M | $13.9M | +$1.3M |
| BU Support | $9.8M | $9.0M | +$0.8M |
| Functional IT Area | $5.7M | $6.3M | -$0.6M |
| Governance | $1.6M | - | - |
| Enablement | $0.5M | - | - |

### Overall Variance Metrics

| Metric | Value |
|--------|-------|
| Var LE1 % | 4.48% |
| Var LE2 % | 0.25% |
| Var LE3 % | 3.65% |
| Var Plan % | 6.78% |

---

## Business Areas

| Business Area | Max Variance | Notes |
|---------------|-------------|-------|
| Infrastructure | $1.61M | Highest variance |
| BU Support | $0.71M | Above plan |
| Distribution | $0.37M | Moderate variance |
| Manufacturing | $0.21M | Smallest variance |
| R&D | Negative | Under control |
| Services | Negative | Savings achieved |

---

## Geographic Performance (Europe)

### Top Spending Countries:

1. **Germany** - $0.9M variance
2. **United Kingdom** - $0.9M variance
3. **Spain** - $0.8M variance
4. **Switzerland** - $0.4M variance
5. **Belgium** - $0.3M variance
6. **Portugal** - $0.1M variance
7. **Austria** - $0.1M variance
8. **Denmark** - $0.0M variance
9. **Poland** - $0.0M variance
10. **Sweden** - $0.0M variance
11. **Czech Republic** - $0.0M variance
12. **Finland** - $0.0M variance

---

## Monthly Variance Trends

| Month | BU | Distribution | Infrastructure | Manufacturing | Office & Admin | R&D | Services | Total |
|-------|-----|--------------|-----------------|----------------|-----------------|-----|----------|-------|
| Jan | -40.14% | -30.64% | -42.91% | 5.31% | - | -33.96% | -24.13% | -25.92% |
| Feb | -18.16% | -25.04% | -17.73% | -1.66% | - | -35.87% | 13.92% | -12.71% |
| Mar | -11.54% | 2.01% | -1.38% | 2.28% | - | -28.61% | 2.75% | -4.34% |
| Apr | -4.42% | 2.57% | -11.15% | -9.23% | - | -29.05% | 0.46% | -9.84% |
| May | -3.13% | 20.11% | -6.44% | -3.63% | - | -20.09% | -2.65% | -4.82% |
| Jun | 1.94% | 23.21% | -1.83% | -4.46% | - | -16.40% | -2.18% | -2.26% |
| Jul | 0.59% | 24.81% | 2.56% | -3.31% | - | -24.77% | -1.60% | -0.85% |
| Aug | 6.56% | 25.82% | 1.81% | -2.67% | - | -23.60% | -3.00% | -0.14% |
| Sep | 6.09% | 24.00% | 5.30% | -0.60% | - | -25.02% | -0.12% | 1.71% |
| Oct | 10.39% | 23.13% | 5.46% | -0.98% | - | -26.42% | 2.23% | 2.31% |
| Nov | 12.98% | 24.30% | 6.98% | 1.24% | - | -26.17% | 3.48% | 4.04% |
| Dec | 16.21% | 22.90% | 11.55% | 3.51% | - | -27.93% | 3.60% | 6.78% |

---

## Period Analysis

### YTD Spending Progression:
- **Period 2**: $5M actual spend
- **Period 4**: $10M cumulative
- **Period 6**: $13M cumulative
- **Period 8**: $16M cumulative
- **Period 10**: $24M cumulative
- **Period 12**: $34M cumulative

### Variance Trend:
Strong improvement from January (negative variances) to December (positive variances), indicating accelerating spend as year progresses.

---

## System Requirements

- Microsoft Power BI Desktop 2.0 or later
- Power BI Service for cloud deployment
- Excel 2016+ for data export
- Minimum 4GB RAM
- 500MB free disk space

---

## Data Sources

- Corporate accounting systems
- IT department expense tracking
- Budget planning systems
- Regional financial databases
- Department cost center allocations

---

## Project Structure

```
Corporate-Spend-Sample-PBIX/
├── dashboards/
│   ├── ytd-spend-trend-analysis.pbix
│   └── plan-variance-analysis.pbix
├── data/
│   ├── spend-data.xlsx
│   ├── budget-data.xlsx
│   ├── regional-data.xlsx
│   └── variance-calculations.xlsx
├── documentation/
│   ├── data-dictionary.md
│   ├── calculation-methods.md
│   └── variance-definitions.md
├── reports/
│   ├── monthly-summaries/
│   └── executive-briefings/
├── README.md
└── LICENSE
```

---

## How to Use

1. **Open Dashboard**: Launch .pbix files in Power BI Desktop
2. **Select Region**: Use dropdown to filter by geographic region (currently set to Europe)
3. **Review Metrics**: Examine KPI cards for quick variance snapshot
4. **Analyze Trends**: Review line charts and area charts for spend patterns
5. **Drill Down**: Click on dimensions to explore detailed variance by category
6. **Export Reports**: Generate PDF or Excel exports for stakeholder review

---

## Key Metrics Explained

**Actual Spend**: Verified expenses incurred in current period

**Plan**: Budgeted amount for the period

**Variance (Var)**: Difference between actual and planned spending
- Positive variance = Over budget
- Negative variance = Under budget

**Var LE1, LE2, LE3**: Multi-level variance calculations at different organizational hierarchies

**Var Plan %**: Overall percentage variance from total budget plan

**YTD**: Year-to-Date cumulative metrics

---

## Variance Analysis Interpretation

**Positive Variance (Over Budget):**
- Infrastructure area consistently over budget ($1.61M)
- Indicates higher-than-anticipated IT infrastructure costs

**Negative Variance (Under Budget):**
- R&D and Services areas showing savings
- BU spending comes under control by year-end

**Monthly Trend:**
- Early year (Jan-Mar): Significant negative variances
- Mid year (Apr-Aug): Convergence toward plan
- Year-end (Sep-Dec): Positive variances indicating accelerated spending

---

## Interactive Filters

- **Sales Region Selector**: Focus analysis by geographic region
- **Period Filter**: Analyze specific time periods or ranges
- **Business Area Filter**: Drill into specific departments
- **Variance Type Filter**: View only over/under budget items

---

## Performance Optimization

- Use region filters to reduce data volume
- Archive prior year data separately
- Index spending and plan tables
- Refresh data during off-peak hours
- Consider incremental data loads for large datasets

---

## Contributing

We welcome contributions! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/enhancement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push to branch (`git push origin feature/enhancement`)
5. Open a Pull Request

---

## Troubleshooting

**Variance Calculations Not Updating**
- Verify data source connection
- Check that latest data has been imported
- Refresh Power BI data model

**Missing Regional Data**
- Confirm region is selected in filter
- Check data for region exists in source
- Verify user permissions for that region

**Slow Dashboard Performance**
- Reduce date range scope
- Filter to specific business areas
- Clear Power BI cache
- Check query complexity

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Connect With Us

- 💼 **LinkedIn**: [Connect on LinkedIn](https://www.linkedin.com/in/your-profile/)
- 🐙 **GitHub**: [Follow on GitHub](https://github.com/your-username)
- 📊 **Portfolio**: [View My Work](https://your-portfolio.com)

---

## Notes

- Data reflects European region analysis as of latest update
- Variance calculations use standard accounting methodology
- Monthly trends show improving budget alignment through year-end
- YTD cumulative spending reaches $34M across all IT business areas
- Regional concentration in Germany, UK, and Spain drives majority of variance

---

**Last Updated: October 17, 2025**

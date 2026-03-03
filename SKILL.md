---
name: finance-super-skill
description: Comprehensive finance and accounting skill merging Perplexity Computer's 7 finance skills plus investment research with Claude Code's data science, data engineering, financial analysis, and invoice management skills. Covers financial statements, journal entries, reconciliation, close management, audit support, variance analysis, market data, investment research, data pipelines, ML forecasting, and invoice processing. Use for financial reporting, month-end close, audit prep, variance analysis, market research, investment thesis, data engineering, or any finance and accounting work.
license: MIT
metadata:
  author: get-zeked
  version: '1.0'
---

# Finance & Accounting Super-Skill

A unified reference merging Perplexity Computer's 8 finance/investment skills with Claude Code's Financial Analyst, Senior Data Engineer, Senior Data Scientist, Senior ML Engineer, and Invoice Organizer skills.

---

## 0. Gap Analysis: Perplexity Computer vs Claude Code Finance Skills

| Capability | Perplexity Computer | Claude Code | Combined Coverage |
|---|---|---|---|
| Financial Statements (IS/BS/CF) | finance-financial-statements | financial-analyst | Full GAAP + ratio analysis |
| Journal Entries & Accruals | finance-journal-entry-prep | — | Debits/credits, templates |
| Account Reconciliation | finance-reconciliation | — | GL, bank, intercompany |
| Month-End Close | finance-close-management | — | Calendar, dependencies, tracking |
| Variance Analysis | finance-variance-analysis | financial-analyst | Waterfall + driver narrative |
| Audit & SOX Compliance | finance-audit-support | — | Control testing, sampling |
| Market Data & Prices | finance-markets | — | Real-time, historical, SEC |
| Investment Research | investment-research | financial-analyst (DCF) | Thesis, comps, famous investors |
| ETL / Data Pipelines | — | senior-data-engineer | Airflow, dbt, Spark, Kafka |
| Statistical Modeling | — | senior-data-scientist | A/B tests, time series, ML |
| ML Forecasting & MLOps | — | senior-ml-engineer | Revenue forecast, anomaly detect |
| Invoice & Document Mgmt | — | invoice-organizer | PDF extraction, CSV export |

---

## 1. Financial Statements & Reporting

### GAAP Financial Statement Templates

**Income Statement, Balance Sheet, and Cash Flow Statement** templates with period-over-period comparison columns.

### Financial Ratio Reference

#### Profitability Ratios
| Ratio | Formula | Benchmark |
|---|---|---|
| Gross Margin | Gross Profit / Revenue | ~50% (varies by industry) |
| Operating Margin | Operating Income / Revenue | ~15% |
| Net Margin | Net Income / Revenue | ~10% |
| ROE | Net Income / Avg Shareholders' Equity | ~15% |
| ROIC | NOPAT / Invested Capital | Compare to WACC |

#### Liquidity Ratios
| Ratio | Formula | Healthy Range |
|---|---|---|
| Current Ratio | Current Assets / Current Liabilities | 1.5x–3.0x |
| Quick Ratio | (Cash + AR) / Current Liabilities | 1.0x–2.0x |

#### Leverage Ratios
| Ratio | Formula | Healthy Range |
|---|---|---|
| Debt-to-Equity | Total Debt / Equity | < 2.0x |
| Net Debt / EBITDA | (Total Debt − Cash) / EBITDA | < 3.0x |
| Interest Coverage | EBIT / Interest Expense | > 3.0x |

### DCF Valuation Workflow

```
Step 1: Forecast Free Cash Flow (5–10 years)
  FCF = EBIT × (1 - Tax Rate) + D&A − CapEx − ΔNWC

Step 2: Calculate WACC
  WACC = (E/V) × Ke + (D/V) × Kd × (1 - Tax Rate)

Step 3: Terminal Value
  TV = FCF(n+1) / (WACC − g)  [Perpetuity Growth]

Step 4: Bridge to Equity Value
  Equity Value = Enterprise Value − Net Debt + Cash
  Share Price = Equity Value / Diluted Shares Outstanding
```

### Industry-Specific KPIs

| Industry | Key Metrics |
|---|---|
| SaaS | ARR, MRR, Churn Rate, NRR, CAC, LTV, CAC Payback |
| Retail | Same-Store Sales Growth, Revenue/Sq Ft, Inventory Turnover |
| E-Commerce | GMV, Take Rate, Conversion Rate, AOV, CAC |
| Financial Services | NIM, Efficiency Ratio, Tier 1 Capital Ratio, ROA |

---

## 2. Journal Entries & Transaction Processing

### Journal Entry Templates

1. **Month-End Accrual** — Expense accruals with auto-reversal
2. **Prepaid Expense Amortization** — Monthly schedule with remaining balance
3. **Fixed Asset Depreciation** — Straight-line and DDB methods
4. **Payroll Entry** — Full payroll with taxes and benefits
5. **Revenue Recognition (ASC 606)** — 5-step model confirmation
6. **Deferred Revenue Recognition** — Subscription monthly recognition
7. **Intercompany Elimination** — Consolidation entries

### Common Accrual Checklist (Month-End)
```
□ Payroll accrual  □ Benefits accrual  □ Bonus accrual
□ Commission accrual  □ Vendor invoice accruals
□ Depreciation  □ Amortization  □ Deferred revenue recognition
□ Revenue accruals  □ Income tax provision  □ Lease ROU amortization
```

---

## 3. Account Reconciliation

### Bank Reconciliation Template

Two-column format: Book Balance (GL) vs. Bank Balance.
Reconciling items: deposits in transit, outstanding checks, bank errors, book errors.

### GL-to-Subledger Reconciliation

AR, AP, Fixed Assets subledger reconciliation with variance explanation.

### Balance Sheet Substantiation Checklist
```
□ Balance agrees to GL trial balance
□ Activity roll (beginning + additions - reductions = ending)
□ All items have valid supporting documentation
□ Aging analysis for AR / AP (flag items > 90 days)
□ Subsequent clearing confirmed for significant items
```

---

## 4. Month-End Close Management

### 15-Business-Day Close Calendar

- **Day -3 to 0**: Pre-close cutoffs, final invoicing
- **Days 1-5**: Bank recs, subledger recs, payroll JEs, standard entries
- **Days 6-10**: Management review, flux analysis, tax provision, consolidation
- **Days 11-15**: Final financials, management commentary, board package, period lock

---

## 5. Variance Analysis & Commentary

### Variance Framework

```
Dollar Variance = Actual − Budget
Percent Variance = (Actual − Budget) / |Budget| × 100

Revenue variance = Price + Volume + Mix components
Expense variance = Rate + Volume + Efficiency components
```

---

## 6. Audit Support & SOX Compliance

- Control design assessment (preventive vs. detective)
- SOX sample selection (MUS, systematic, attribute sampling)
- Workpaper standards: objective, procedure, evidence, conclusion
- Deficiency classification: control deficiency, significant deficiency, material weakness

---

## 7. Markets & Investment Research

### Famous Investor Frameworks
| Investor | Style | Key Criteria |
|---|---|---|
| Warren Buffett | Value | Moat, ROIC > 15%, honest management, fair price |
| Peter Lynch | GARP | PEG ratio, understand what you own, growth at reasonable price |
| Stanley Druckenmiller | Macro | Liquidity, earnings inflections, currency flows |
| Michael Burry | Deep Value | Assets vs. liabilities, catalyst identification |

---

## 8. Data Engineering

### ETL Pipeline Architecture

```python
# dbt model example
SELECT
    customer_id,
    SUM(revenue) as total_revenue,
    COUNT(DISTINCT order_id) as order_count
FROM {{ ref('stg_orders') }}
GROUP BY 1
```

- **Airflow DAG patterns**: Extract → Load → Transform (ELT)
- **Data quality**: Great Expectations, dbt tests
- **Streaming**: Kafka consumers, Spark Structured Streaming

---

## 9. ML & Forecasting

- Revenue forecasting: ARIMA, Prophet, LSTM
- Anomaly detection: Z-score, IQR, isolation forest
- Customer churn: logistic regression, gradient boosting
- Feature engineering for financial data

---

## 10. Invoice Management

- PDF extraction with pdfplumber/Camelot
- Standardized filename format: `YYYY-MM-DD_VendorName_AmountUSD_InvoiceNumber.pdf`
- Four organization strategies: date, vendor, category, project
- CSV reporting with amount, vendor, date, category columns

---

*Finance & Accounting Super-Skill v1.0 — Merged from Perplexity Computer finance-markets, finance-financial-statements, finance-variance-analysis, finance-journal-entry-prep, finance-reconciliation, finance-close-management, finance-audit-support, investment-research, and Claude Code invoice-organizer, senior-data-scientist, senior-data-engineer, financial-analyst, senior-ml-engineer skills.*

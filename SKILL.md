---
name: finance-super-skill
description: Comprehensive finance and accounting skill merging Perplexity Computer's 7 finance skills plus investment research with Claude Code's data science, data engineering, financial analysis, and invoice management skills. Covers financial statements, journal entries, reconciliation, close management, audit support, variance analysis, market data, investment research, data pipelines, ML forecasting, and invoice processing. Use for financial reporting, month-end close, audit prep, variance analysis, market research, investment thesis, data engineering, or any finance and accounting work.
license: MIT
metadata:
  author: get-zeked
  version: '1.0'
---

# Finance & Accounting Super-Skill

A unified reference merging Perplexity Computer's 8 finance/investment skills with Claude Code's Financial Analyst, Senior Data Engineer, Senior Data Scientist, Senior ML Engineer, and Invoice Organizer skills. Covers the full spectrum from journal entries and month-end close to DCF valuation, ETL pipelines, and ML-powered forecasting.

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
| Data Quality & Contracts | — | senior-data-engineer | Great Expectations, dbt tests |
| Statistical Modeling | — | senior-data-scientist | A/B tests, time series, ML |
| ML Forecasting & MLOps | — | senior-ml-engineer | Revenue forecast, anomaly detect |
| Invoice & Document Mgmt | — | invoice-organizer | PDF extraction, CSV export |
| LLM-Assisted Finance | — | senior-ml-engineer | RAG for financial docs |

**Key gaps filled by combining both sources:**
- Perplexity skills cover accounting workflows deeply; Claude Code adds data infrastructure.
- Claude Code covers ML/engineering; Perplexity adds real-time market data and SEC filings.
- Neither source alone covers invoice automation + financial close + market research together.

---

## 1. Financial Statements & Reporting

### When to Use
- Preparing income statements, balance sheets, or cash flow statements
- Running period-over-period comparisons (QoQ, YoY)
- Calculating financial ratios for management or investor reporting
- Building a DCF model or comparable-company analysis
- Industry-specific reporting (SaaS, Retail, Manufacturing, Healthcare)

### GAAP Financial Statement Templates

#### Income Statement Template
```
[Company Name]
Consolidated Statements of Operations
For the [Quarter/Year] Ended [Date]
(in thousands, except per share data)

                                    Current Period    Prior Period    Change $    Change %
Revenue
  Product Revenue                   $             $             $           %
  Service Revenue                   $             $             $           %
  Total Revenue                     $             $             $           %

Cost of Revenue
  Cost of Products                  $             $             $           %
  Cost of Services                  $             $             $           %
  Total Cost of Revenue             $             $             $           %

Gross Profit                        $             $             $           %
Gross Margin                                    %               %

Operating Expenses
  Research & Development            $             $             $           %
  Sales & Marketing                 $             $             $           %
  General & Administrative          $             $             $           %
  Total Operating Expenses          $             $             $           %

Operating Income (Loss)             $             $             $           %
Operating Margin                               %               %

Other Income (Expense)
  Interest Income                   $             $
  Interest Expense                  ($            ) ($            )
  Other, net                        $             $
  Total Other Income (Expense)      $             $

Income Before Income Taxes          $             $
Income Tax Expense (Benefit)        $             $
Effective Tax Rate                             %               %

Net Income (Loss)                   $             $             $           %
Net Margin                                     %               %

Earnings Per Share
  Basic EPS                         $             $
  Diluted EPS                       $             $
  Weighted Avg Shares (Basic)
  Weighted Avg Shares (Diluted)
```

#### Balance Sheet Template
```
[Company Name]
Consolidated Balance Sheets
As of [Date] and [Prior Period Date]
(in thousands)

                                    Current         Prior Period
ASSETS
Current Assets
  Cash and Cash Equivalents         $               $
  Short-term Investments            $               $
  Accounts Receivable, net          $               $
  Inventories                       $               $
  Prepaid Expenses                  $               $
  Other Current Assets              $               $
  Total Current Assets              $               $

Non-Current Assets
  Property, Plant & Equipment, net  $               $
  Right-of-Use Assets               $               $
  Goodwill                          $               $
  Intangible Assets, net            $               $
  Deferred Tax Assets               $               $
  Other Non-Current Assets          $               $
  Total Non-Current Assets          $               $

TOTAL ASSETS                        $               $

LIABILITIES & STOCKHOLDERS' EQUITY
Current Liabilities
  Accounts Payable                  $               $
  Accrued Liabilities               $               $
  Deferred Revenue (Current)        $               $
  Short-term Debt                   $               $
  Other Current Liabilities         $               $
  Total Current Liabilities         $               $

Non-Current Liabilities
  Long-term Debt                    $               $
  Operating Lease Liabilities       $               $
  Deferred Revenue (LT)             $               $
  Deferred Tax Liabilities          $               $
  Other Non-Current Liabilities     $               $
  Total Non-Current Liabilities     $               $

TOTAL LIABILITIES                   $               $

Stockholders' Equity
  Common Stock                      $               $
  Additional Paid-in Capital        $               $
  Retained Earnings (Deficit)       $               $
  Accumulated OCI                   $               $
  Treasury Stock                    ($              ) ($              )
  Total Stockholders' Equity        $               $

TOTAL LIABILITIES & EQUITY         $               $
```

#### Cash Flow Statement Template
```
[Company Name]
Consolidated Statements of Cash Flows
For the [Period] Ended [Date]
(in thousands)

                                            Current Period    Prior Period
OPERATING ACTIVITIES
Net Income (Loss)                           $                 $
Adjustments to reconcile net income:
  Depreciation & Amortization              $                 $
  Stock-Based Compensation                 $                 $
  Deferred Income Taxes                    $                 $
  Changes in operating assets/liabilities:
    Accounts Receivable                    ($                ) ($                )
    Inventories                            ($                ) ($                )
    Prepaid Expenses & Other               ($                ) ($                )
    Accounts Payable                       $                 $
    Accrued Liabilities                    $                 $
    Deferred Revenue                       $                 $
Net Cash from Operating Activities         $                 $

INVESTING ACTIVITIES
  Capital Expenditures                     ($                ) ($                )
  Acquisitions, net of cash                ($                ) ($                )
  Purchases of Investments                 ($                ) ($                )
  Proceeds from Sales of Investments       $                 $
Net Cash used in Investing Activities      ($                ) ($                )

FINANCING ACTIVITIES
  Proceeds from Stock Issuance             $                 $
  Repurchase of Common Stock               ($                ) ($                )
  Proceeds from Debt Issuance              $                 $
  Repayment of Debt                        ($                ) ($                )
  Payment of Dividends                     ($                ) ($                )
Net Cash from (used in) Financing          $                 $

Net Increase (Decrease) in Cash            $                 $
Cash at Beginning of Period                $                 $
Cash at End of Period                      $                 $

Free Cash Flow = Operating CF - CapEx      $                 $
```

### Financial Ratio Reference

#### Profitability Ratios
| Ratio | Formula | Benchmark (S&P 500 avg) |
|---|---|---|
| Gross Margin | Gross Profit / Revenue | ~50% (varies widely by industry) |
| Operating Margin | Operating Income / Revenue | ~15% |
| Net Margin | Net Income / Revenue | ~10% |
| ROE | Net Income / Avg Shareholders' Equity | ~15% |
| ROA | Net Income / Avg Total Assets | ~6% |
| ROIC | NOPAT / Invested Capital | Compare to WACC |
| EBITDA Margin | EBITDA / Revenue | ~20% |

#### Liquidity Ratios
| Ratio | Formula | Healthy Range |
|---|---|---|
| Current Ratio | Current Assets / Current Liabilities | 1.5x–3.0x |
| Quick Ratio | (Cash + AR) / Current Liabilities | 1.0x–2.0x |
| Cash Ratio | Cash / Current Liabilities | > 0.5x |
| Operating CF Ratio | Operating CF / Current Liabilities | > 1.0x |

#### Leverage Ratios
| Ratio | Formula | Healthy Range |
|---|---|---|
| Debt-to-Equity | Total Debt / Equity | < 2.0x |
| Net Debt / EBITDA | (Total Debt − Cash) / EBITDA | < 3.0x |
| Interest Coverage | EBIT / Interest Expense | > 3.0x |
| Debt Service Coverage | Net Operating Income / Debt Service | > 1.25x |

#### Efficiency Ratios
| Ratio | Formula | Note |
|---|---|---|
| Asset Turnover | Revenue / Avg Total Assets | Higher = more efficient |
| Inventory Turnover | COGS / Avg Inventory | Higher = faster selling |
| Days Sales Outstanding | AR / (Revenue / 365) | Lower = faster collection |
| Days Payable Outstanding | AP / (COGS / 365) | Higher = better cash management |
| Cash Conversion Cycle | DIO + DSO − DPO | Lower = better working capital |

#### Valuation Multiples
| Multiple | Formula | When to Use |
|---|---|---|
| P/E | Share Price / EPS | Profitable companies |
| EV/EBITDA | Enterprise Value / EBITDA | Cross-capital-structure comparison |
| EV/Revenue | Enterprise Value / Revenue | High-growth, pre-profit companies |
| P/B | Share Price / Book Value per Share | Banks, asset-heavy businesses |
| P/FCF | Share Price / FCF per Share | Cash flow-focused valuation |
| PEG | P/E / Earnings Growth Rate | Growth-adjusted valuation |

### DCF Valuation Workflow

```
Step 1: Forecast Free Cash Flow (5–10 years)
  FCF = EBIT × (1 - Tax Rate) + D&A − CapEx − ΔNWC

Step 2: Calculate WACC
  WACC = (E/V) × Ke + (D/V) × Kd × (1 - Tax Rate)
  Ke = Rf + β × (Rm − Rf)           [CAPM]

Step 3: Terminal Value
  Perpetuity Growth: TV = FCF(n+1) / (WACC − g)
  Exit Multiple:     TV = EBITDA(n) × EV/EBITDA Multiple

Step 4: Discount to Present Value
  PV = Σ FCFt / (1 + WACC)^t  +  TV / (1 + WACC)^n

Step 5: Bridge to Equity Value
  Enterprise Value = PV of FCFs + PV of Terminal Value
  Equity Value = Enterprise Value − Net Debt + Cash
  Share Price = Equity Value / Diluted Shares Outstanding

Step 6: Sensitivity Analysis
  Vary WACC ±1% and Terminal Growth ±0.5%
  Create 5×5 table of implied share prices
```

### Industry-Specific KPIs

| Industry | Key Metrics |
|---|---|
| SaaS | ARR, MRR, Churn Rate, Net Revenue Retention, CAC, LTV, CAC Payback |
| Retail | Same-Store Sales Growth, Revenue/Sq Ft, Inventory Turnover, Shrink % |
| Manufacturing | Capacity Utilization, Gross Margin by Product Line, CapEx/Revenue |
| Financial Services | NIM, Efficiency Ratio, Tier 1 Capital Ratio, ROA, NPL Ratio |
| Healthcare | Revenue/Patient, Payer Mix, Days in A/R, Operating Margin |
| E-Commerce | GMV, Take Rate, Conversion Rate, Average Order Value, CAC |

---

## 2. Journal Entries & Transaction Processing

### When to Use
- Recording any accounting transaction in the general ledger
- Month-end accruals and reversals
- Prepaid amortization, fixed asset depreciation
- Payroll entries
- Revenue recognition under ASC 606
- Deferred revenue adjustments
- Lease accounting under ASC 842

### Journal Entry Basics

**Rules:**
- Every entry must balance: Total Debits = Total Credits
- Use the account number, description, and supporting document reference
- Include a clear memo explaining the business purpose
- Obtain required approvals before posting

**Normal Balances:**
| Account Type | Normal Balance | Increases with | Decreases with |
|---|---|---|---|
| Assets | Debit | Debit | Credit |
| Liabilities | Credit | Credit | Debit |
| Equity | Credit | Credit | Debit |
| Revenue | Credit | Credit | Debit |
| Expenses | Debit | Debit | Credit |

### Journal Entry Templates

#### Month-End Accrual (Expense)
```
Date: [Last day of month]
Reference: JE-[YYYY-MM]-[###]
Prepared by: [Name]    Approved by: [Name]
Description: Accrue [vendor/service] for [month] services

  Account                    Account #    Debit        Credit
  [Expense Account]          [XXXXX]      $X,XXX.XX
    Accrued Liabilities      [XXXXX]                   $X,XXX.XX

Supporting: Vendor estimate / Contract / Invoice received [date]
Reversal: Auto-reverse [first day of next month]
```

#### Prepaid Expense Amortization
```
Date: [Last day of month]
Reference: JE-[YYYY-MM]-[###]
Description: Amortize prepaid [insurance/software/etc.] – Month [X] of [Y]

  Account                    Account #    Debit        Credit
  [Expense Account]          [XXXXX]      $X,XXX.XX
    Prepaid Expenses         [XXXXX]                   $X,XXX.XX

Original prepaid amount: $[Total]
Monthly amortization: $[Amount] = $[Total] / [Months]
Remaining balance after entry: $[Remaining]
Supporting: Original invoice [date], prepaid schedule
```

#### Fixed Asset Depreciation
```
Date: [Last day of month]
Reference: JE-[YYYY-MM]-[###]
Description: Record depreciation – [Asset Class] – [Month Year]

  Account                    Account #    Debit        Credit
  Depreciation Expense       [XXXXX]      $X,XXX.XX
    Accumulated Depreciation [XXXXX]                   $X,XXX.XX

Asset: [Asset Name / FA #]
Acquisition cost: $[Cost]     Salvage value: $[Value]
Useful life: [X] years         Method: [Straight-line / DDB / Units]
Monthly depreciation: $[Cost - Salvage] / ([Life] × 12)
Supporting: Fixed asset register
```

#### Payroll Entry
```
Date: [Pay date]
Reference: JE-[YYYY-MM]-[###]
Description: Payroll – Period ending [date]

  Account                    Account #    Debit        Credit
  Salaries & Wages Expense   [XXXXX]      $XX,XXX.XX
  Payroll Tax Expense        [XXXXX]      $X,XXX.XX
    Salaries Payable                                   $XX,XXX.XX
    Federal Income Tax W/H                             $X,XXX.XX
    State Income Tax W/H                               $X,XXX.XX
    FICA – Employee (SS)                               $X,XXX.XX
    FICA – Employee (Medicare)                         $X,XXX.XX
    FICA – Employer (SS)                               $X,XXX.XX
    FICA – Employer (Medicare)                         $X,XXX.XX
    401(k) Payable                                     $X,XXX.XX
    Health Insurance Payable                           $X,XXX.XX

Supporting: Payroll register, HR approval
```

#### Revenue Recognition (ASC 606) — Point in Time
```
Date: [Revenue recognition date]
Reference: JE-[YYYY-MM]-[###]
Description: Recognize revenue – [Customer] – [Contract/Order #]

  Account                    Account #    Debit        Credit
  Accounts Receivable        [XXXXX]      $X,XXX.XX
    Revenue                  [XXXXX]                   $X,XXX.XX

5-step model confirmation:
  Step 1 – Contract identified: [Yes/Contract #]
  Step 2 – Performance obligations: [Description]
  Step 3 – Transaction price: $[Amount]
  Step 4 – Allocation: [100% to single PO / Split: X%/Y%]
  Step 5 – Satisfied: [Date/Event that triggered recognition]
Supporting: Sales order, delivery confirmation, contract
```

#### Deferred Revenue Recognition (Subscription)
```
Date: [Date of recognition]
Reference: JE-[YYYY-MM]-[###]
Description: Recognize deferred revenue – [Customer] – Month [X] of [Y]

  Account                    Account #    Debit        Credit
  Deferred Revenue           [XXXXX]      $X,XXX.XX
    Revenue                  [XXXXX]                   $X,XXX.XX

Original invoice: $[Total]     Contract term: [X] months
Monthly recognition: $[Total] / [Months]
Remaining deferred balance: $[Amount]
Supporting: Customer contract, billing schedule
```

#### Intercompany Elimination
```
Date: [Consolidation date]
Reference: JE-CONSOL-[YYYY-MM]-[###]
Description: Eliminate intercompany [sale/loan/dividend] – [Sub A] to [Sub B]

  Elimination Entry – Selling Entity
  Account                    Account #    Debit        Credit
  Intercompany Revenue       [XXXXX]      $X,XXX.XX
    Intercompany Receivable  [XXXXX]                   $X,XXX.XX

  Elimination Entry – Buying Entity
  Account                    Account #    Debit        Credit
  Intercompany Payable       [XXXXX]      $X,XXX.XX
    Intercompany Expense     [XXXXX]                   $X,XXX.XX

Confirmation: Both legs balance to zero on consolidation
Supporting: Intercompany agreement, transfer pricing documentation
```

### Common Accrual Checklist (Month-End)
```
□ Payroll accrual (days worked but not yet paid)
□ Benefits accrual (health, dental, 401k employer match)
□ Bonus accrual (% of annual target × months elapsed)
□ Commission accrual (sales team earned but unpaid)
□ Vendor invoice accruals (services received, invoice not yet in)
□ Utility accruals (service period vs billing period)
□ Interest accrual (on outstanding debt)
□ Depreciation (fixed assets)
□ Amortization (intangibles, prepaid schedules)
□ Deferred revenue recognition (subscription, milestone)
□ Revenue accruals (shipped/delivered but not yet invoiced)
□ Income tax provision (current + deferred)
□ Lease ROU amortization (ASC 842)
```

---

## 3. Account Reconciliation

### When to Use
- Monthly bank reconciliation
- GL-to-subledger reconciliation (AR, AP, fixed assets)
- Intercompany balance reconciliation
- Balance sheet account substantiation
- Pre-audit preparation

### Bank Reconciliation Template
```
[Company Name]
Bank Reconciliation – [Bank / Account #]
As of [Date]

BOOK BALANCE
  Balance per general ledger                          $XX,XXX.XX
  Add: Deposits in transit
    [Date] Deposit – [Description]                    $X,XXX.XX
    [Date] Deposit – [Description]                    $X,XXX.XX
  Less: Outstanding checks
    Check #[####] – [Payee] – [Date]                 ($X,XXX.XX)
    Check #[####] – [Payee] – [Date]                 ($X,XXX.XX)
  Add/Less: Book errors
    [Describe error and correction]                   $X,XXX.XX
ADJUSTED BOOK BALANCE                                $XX,XXX.XX

BANK BALANCE
  Balance per bank statement                         $XX,XXX.XX
  Add: Deposits in transit (same list above)         $X,XXX.XX
  Less: Outstanding checks (same list above)        ($X,XXX.XX)
  Add/Less: Bank errors
    [Describe error and correction]                   $X,XXX.XX
ADJUSTED BANK BALANCE                               $XX,XXX.XX

RECONCILING DIFFERENCE                               $       —

Prepared by: ____________   Date: ____________
Reviewed by: ____________   Date: ____________
```

### GL-to-Subledger Reconciliation

**Accounts Receivable Reconciliation:**
```
[Company Name]
AR Reconciliation
As of [Date]

  GL Balance – Accounts Receivable                   $XX,XXX.XX

  AR Subledger by Customer:
  Customer                   Invoice #    Amount
  [Customer A]               [INV-###]    $X,XXX.XX
  [Customer B]               [INV-###]    $X,XXX.XX
  ...
  Total AR Subledger                                  $XX,XXX.XX

  DIFFERENCE                                         $       —

  Items in GL not in Subledger:
  [Description]                                      $X,XXX.XX

  Items in Subledger not in GL:
  [Description]                                      $X,XXX.XX

  Resolution / JE Required:
  [Describe correcting entry]
```

### Reconciling Item Categories
| Category | Description | Resolution |
|---|---|---|
| Timing differences | Transactions recorded in different periods | Verify subsequent clearing; no JE if legitimate timing |
| Bank errors | Bank posted wrong amount | Contact bank; adjust bank side of reconciliation |
| Book errors | Keying error, wrong account | Prepare correcting journal entry |
| Unrecorded items | NSF checks, bank fees, interest | Record in GL per bank statement |
| Duplicate entries | Same transaction posted twice | Void/reverse duplicate |
| Missing transactions | Valid transaction not recorded | Record with supporting documentation |

### Balance Sheet Substantiation Checklist
```
For each balance sheet account:
□ Balance agrees to GL trial balance
□ Activity roll (beginning balance + additions - reductions = ending)
□ All items have valid supporting documentation
□ Aging analysis for AR / AP (identify items > 90 days)
□ Subsequent clearing confirmed for significant items
□ Reconciling items < materiality threshold or explained
□ Prior period items resolved
□ Approvals documented
```

---

## 4. Month-End Close Management

### When to Use
- Planning the monthly or quarterly close calendar
- Tracking close task status and ownership
- Identifying blockers and dependencies
- Communicating close status to leadership

### Close Calendar Template (15-Business-Day Close)

```
PRE-CLOSE (Days -3 to 0)
Day -3:  Confirm subledger cutoff with AR/AP teams
Day -3:  Distribute close checklist to all controllers
Day -2:  Process final customer invoices for the period
Day -2:  Complete final AP invoice entry cutoff
Day -1:  Process final payroll; confirm payroll accruals
Day 0:   Period closes at end of business

CLOSE WEEK 1 (Days 1–5)
Day 1:   Open period in ERP; run preliminary trial balance
Day 1:   Bank statements received; begin bank reconciliations
Day 1:   AR team: complete AR subledger reconciliation
Day 2:   AP team: complete AP subledger reconciliation
Day 2:   Fixed assets: run depreciation; reconcile FA subledger
Day 2:   Inventory: confirm physical counts; post inventory JEs
Day 3:   Payroll JEs posted and reviewed
Day 3:   Standard recurring entries posted (amortization, D&A)
Day 4:   Accruals: all department accruals submitted and posted
Day 4:   Intercompany: confirm IC balances with counterparts
Day 5:   Elimination JEs posted; preliminary consolidation run

CLOSE WEEK 2 (Days 6–10)
Day 6:   Management review: preliminary P&L distributed
Day 6:   Flux analysis: identify variances > materiality threshold
Day 7:   Tax provision calculated; deferred tax JEs posted
Day 7:   Revenue recognition review; deferred revenue JEs
Day 8:   Controller review: all reconciliations signed off
Day 9:   Final consolidation; segment reporting prepared
Day 9:   Board/management package drafted
Day 10:  CFO review; final adjustments made

REPORTING (Days 11–15)
Day 11:  Final financial statements issued internally
Day 12:  Management commentary finalized
Day 13:  Board package distributed
Day 14:  External auditor review (if applicable)
Day 15:  Period locked in ERP
```

### Close Task Status Tracker

```markdown
| Task | Owner | Due | Status | Blocker |
|---|---|---|---|---|
| Bank Reconciliations | Controller | Day 3 | In Progress | — |
| AR Subledger Rec | AR Manager | Day 2 | Complete | — |
| AP Subledger Rec | AP Manager | Day 2 | Not Started | Waiting on statements |
| Payroll JEs | Payroll | Day 3 | Complete | — |
| Fixed Asset D&A | Fixed Asset Acct | Day 2 | In Progress | — |
| Accruals – Mktg | Mktg Controller | Day 4 | Not Started | Pending vendor quotes |
| Accruals – IT | IT Controller | Day 4 | Complete | — |
| IC Reconciliation | Corporate Acct | Day 5 | Not Started | — |
| Tax Provision | Tax Director | Day 7 | Not Started | Waiting prelim P&L |
| Consolidation | Corporate | Day 9 | Not Started | — |
| Management Package | FP&A | Day 10 | Not Started | — |
```

### Close Dependencies Map
```
Bank Recs ------------------------------------------► Controller Review
AR Rec ----------------------------------------------► Consolidation
AP Rec ----------------------------------------------► Consolidation
Payroll JEs -----------------------------------------► Accrual Review
Fixed Asset D&A -------------------------------------► Balance Sheet
Accruals (all) --------------------------------------► Prelim P&L
                                                              │
                                                              ▼
Revenue Recognition ---------------------------------► Prelim P&L
                                                              │
                                                              ▼
Prelim P&L ------------------------------------------► Tax Provision
                                                              │
IC Elimination --------------------------------------► Consolidation
                                                              │
Prelim P&L + Tax + IC -------------------------------► Final Consolidation
                                                              │
                                                              ▼
Final Consolidation ---------------------------------► Management Package
```

### Close Metrics to Track
| Metric | Target | How to Measure |
|---|---|---|
| Close duration | ≤ 10 business days | Day 1 open to Day 10 CFO sign-off |
| Tasks on time | ≥ 95% | Tasks completed by due date / total tasks |
| Audit adjustments | < 5 per period | Count of post-close JEs |
| Restatements | 0 | Prior period adjustments |
| Reconciling items > $50K | < 3 unresolved | Aged reconciling item report |

---

## 5. Variance Analysis & Commentary

### When to Use
- Budget vs. actual reporting
- Prior period comparisons
- Explaining revenue or expense drivers to leadership
- Building waterfall charts for CFO/board presentations

### Variance Analysis Framework

**Step 1: Calculate Variances**
```
Dollar Variance = Actual − Budget (or Actual − Prior Period)
Percent Variance = (Actual − Budget) / |Budget| × 100

Favorable (F) = Revenue above budget OR Expense below budget
Unfavorable (U) = Revenue below budget OR Expense above budget
```

**Step 2: Apply Materiality Filter**
- Quantitative threshold: > $[X]K absolute OR > [Y]% of budget
- Qualitative threshold: Any variance affecting key narrative metrics

**Step 3: Decompose into Drivers**
- Revenue variance = Price variance + Volume variance + Mix variance
- Expense variance = Rate variance + Volume variance + Efficiency variance

**Step 4: Draft Narrative Commentary**

### Variance Report Template
```
[Company Name]
Budget vs. Actual Variance Report
Period: [Month/Quarter] [Year]

EXECUTIVE SUMMARY
Total Revenue:   Actual $[X]M  |  Budget $[X]M  |  Variance $[X]M ([Y]%) [F/U]
Total Expenses:  Actual $[X]M  |  Budget $[X]M  |  Variance $[X]M ([Y]%) [F/U]
Operating Income: Actual $[X]M |  Budget $[X]M  |  Variance $[X]M ([Y]%) [F/U]

KEY REVENUE DRIVERS
1. [Product Line A] — $[X]M favorable: [Explanation — volume/price/mix]
2. [Product Line B] — $[X]M unfavorable: [Explanation]
3. [Geography / Segment] — $[X]M: [Explanation]

KEY EXPENSE DRIVERS
1. [Cost Category] — $[X]M unfavorable: [Explanation]
2. [Cost Category] — $[X]M favorable: [Explanation]

DETAILED VARIANCE TABLE
Account              Actual      Budget      Var $      Var %    F/U   Commentary
Revenue
  Product Revenue    $X,XXX      $X,XXX      $XXX       X.X%     F     [Note]
  Service Revenue    $X,XXX      $X,XXX     ($XXX)     (X.X%)    U     [Note]
  Total Revenue      $X,XXX      $X,XXX      $XXX       X.X%     F

Cost of Revenue
  COGS – Product     $X,XXX      $X,XXX     ($XXX)     (X.X%)    U     [Note]
  COGS – Service     $X,XXX      $X,XXX      $XXX       X.X%     F     [Note]
  Total COR          $X,XXX      $X,XXX      $XXX       X.X%     F

Gross Profit         $X,XXX      $X,XXX      $XXX       X.X%     F
Gross Margin         XX.X%       XX.X%       X.Xpts

Operating Expenses
  R&D                $X,XXX      $X,XXX      $XXX       X.X%     F     [Note]
  S&M                $X,XXX      $X,XXX     ($XXX)     (X.X%)    U     [Note]
  G&A                $X,XXX      $X,XXX      $XXX       X.X%     F     [Note]
  Total OpEx         $X,XXX      $X,XXX      $XXX       X.X%     F

Operating Income     $X,XXX      $X,XXX      $XXX       X.X%     F
Operating Margin     XX.X%       XX.X%       X.Xpts
```

### Revenue Decomposition
```
Revenue Variance = Volume Effect + Price Effect + Mix Effect

Volume Effect = (Actual Units − Budget Units) × Budget Price
Price Effect  = (Actual Price − Budget Price) × Actual Units
Mix Effect    = Budget Price × (Actual Mix − Budget Mix) × Total Actual Units

Example:
  Product A: Budget 1,000 units @ $100 = $100,000
  Product B: Budget 1,000 units @ $200 = $200,000
  Total Budget = $300,000

  Actual Product A: 1,200 units @ $95  = $114,000
  Actual Product B: 800 units  @ $210  = $168,000
  Total Actual = $282,000

  Overall Variance = $282,000 − $300,000 = ($18,000) Unfavorable

  Volume Effect: (+200 − 200) × weighted avg = net zero (units same total)
  Price Effect A: ($95 − $100) × 1,200 = ($6,000) U
  Price Effect B: ($210 − $200) × 800  = $8,000   F
  Mix Effect: Shift from higher-margin B to lower-margin A = ($20,000) U
```

### Waterfall Chart Narrative Template
```
"Operating income of $[X]M came in $[Y]M [above/below] budget of $[Z]M.

Revenue was $[A]M [favorable/unfavorable] driven by:
+ $[B]M higher volume in [segment] driven by [reason]
− $[C]M lower pricing in [segment] due to [competitive pressure/discounting]
− $[D]M unfavorable mix as [higher-margin product] underperformed

This was partially [offset by / compounded by] expenses:
+ $[E]M favorable in R&D due to [timing of headcount / vendor delays]
− $[F]M unfavorable in S&M due to [campaign pull-forward / trade show costs]
± $[G]M in G&A due to [litigation reserve / one-time item]

Outlook: Management [reaffirms / revises] full-year guidance of $[X]M revenue
given [trend rationale]."
```

---

## 6. Audit Support & SOX Compliance

### When to Use
- SOX 404 control testing
- Preparing audit samples for internal or external auditors
- Documenting internal controls
- Responding to auditor requests
- Deficiency classification (significant deficiency vs. material weakness)

### SOX 404 Control Testing Workflow

**Step 1: Identify In-Scope Controls**
```
Tier 1 – Company-Level Controls (ITGC)
  □ User access reviews (quarterly)
  □ Segregation of duties (SoD) matrix
  □ Change management controls
  □ Backup and recovery procedures

Tier 2 – Process-Level Controls
  □ Financial close controls (journal entry review, reconciliations)
  □ Revenue recognition controls (contract review, billing accuracy)
  □ Procurement controls (PO approval, 3-way match)
  □ Payroll controls (authorization, accurate calculation)
  □ Financial reporting controls (management review of fluctuations)
```

**Step 2: Select Sample Sizes (PCAOB guidance)**
```
Population Size    Risk Level    Sample Size
< 25               Any           Entire population
25 – 99            Low           25
25 – 99            High          40
100 – 249          Low           30
100 – 249          High          60
250 – 499          Low           35
250 – 499          High          75
500+               Low           40
500+               High          100

Sampling Method: Random (use RAND() in Excel or Python random.sample())
For automated/IT controls: Sample 1–3 (test once if no exceptions found)
```

**Sample Selection Script (Python):**
```python
import random

def select_audit_sample(population: list, sample_size: int, seed: int = None) -> list:
    """
    Randomly select audit sample from population.
    
    Args:
        population: List of transaction IDs or items
        sample_size: Number of items to select
        seed: Random seed for reproducibility (document this!)
    
    Returns:
        List of selected sample items
    """
    if seed:
        random.seed(seed)
    
    if len(population) <= sample_size:
        return population  # Test entire population
    
    sample = random.sample(population, sample_size)
    return sorted(sample)

# Example: Select 40 journal entries from 500+ population
all_jes = list(range(1001, 1537))  # JE numbers 1001–1536
sample = select_audit_sample(all_jes, sample_size=40, seed=20260303)
print(f"Sample size: {len(sample)}")
print(f"Sample items: {sample}")
```

### Control Testing Documentation Template
```
CONTROL TEST WORKPAPER

Control ID:        [SOX-FIN-001]
Process:           [Financial Close / Revenue / Payroll / etc.]
Control Name:      [Journal Entry Review]
Control Owner:     [Controller, CFO]
Control Type:      [Preventive / Detective]
Frequency:         [Daily / Weekly / Monthly / Quarterly]
Risk Addressed:    [Unauthorized journal entries, recording errors]

CONTROL DESCRIPTION:
[The Controller reviews and approves all manual journal entries above
$[X]K before posting. The review includes: (1) business purpose, (2)
supporting documentation, (3) correct accounts, (4) proper period.]

TESTING PROCEDURE:
1. Obtain population of manual JEs for the period
2. Apply SALT to identify anomalies (round numbers, unusual times, etc.)
3. Select sample per PCAOB guidance (population: [N]; sample: [N])
4. For each sample item, inspect:
   □ Journal entry form / ERP screenshot
   □ Approval signature / system approval log
   □ Supporting documentation attached
   □ Posted to correct account and period

RESULTS SUMMARY:
Population:        [N] manual JEs totaling $[X]M
Sample:            [N] items
Exceptions found:  [0] / [Describe any exceptions]
Conclusion:        Control [Operating Effectively / Exception Noted]

DEFICIENCY ANALYSIS (if applicable):
Deficiency Description: [Describe]
Root Cause:             [Describe]
Financial Statement Impact: $[Amount] / [None / Immaterial]
Classification:         [Control Deficiency / Significant Deficiency / Material Weakness]

Prepared by: ____________  Date: ____________
Reviewed by: ____________  Date: ____________
```

### Deficiency Classification Framework
```
CONTROL DEFICIENCY
  Definition: A control does not operate effectively or does not exist
              where necessary to prevent or detect a misstatement.
  Impact: Immaterial potential misstatement
  Required action: Remediate; no disclosure required

SIGNIFICANT DEFICIENCY
  Definition: A deficiency, or combination of deficiencies, that is
              less severe than a material weakness but important enough
              to merit attention by those responsible for financial reporting.
  Impact: More than inconsequential potential misstatement
  Required action: Report to Audit Committee; remediate promptly

MATERIAL WEAKNESS
  Definition: A deficiency where there is a reasonable possibility that
              a material misstatement of the financial statements will
              not be prevented or detected on a timely basis.
  Impact: Could result in material misstatement of financial statements
  Required action: External disclosure required (10-K); remediation
                   plan with timeline; re-test after remediation

MATERIALITY THRESHOLD GUIDANCE:
  Quantitative: Typically 5% of pre-tax income (SEC Staff guidance)
  Qualitative: Consider nature of account, risk, fraud indicators
```

### Audit Request Response Checklist
```
For each Prepared by Client (PBC) item:
□ Understand exactly what the auditor needs (format, period, scope)
□ Assign a single owner responsible for the item
□ Set internal due date 2 days before auditor deadline
□ Quality review before submission (completeness, formatting)
□ Log in PBC tracker: item #, description, owner, due date, status
□ Label files clearly: [PBC-###]_[Description]_[Period].xlsx
□ Brief person delivering item on likely follow-up questions
□ Keep copy of everything submitted
```

---

## 7. Markets & Investment Research

### When to Use
- Current stock/crypto/ETF prices
- Historical price data for analysis
- Financial statements for public companies
- Earnings call transcripts
- Building an investment thesis
- Comparable company analysis
- Emulating famous investor frameworks

### CRITICAL: Never Use Web Search for Financial Data

**Do NOT use `search_web` for:** Stock prices, historical prices, P/E ratios, market caps, revenue figures, EPS, guidance, earnings transcripts. Web search returns stale, unstructured snippets.

**ALWAYS use finance tools from the connector service:**
```python
# Step 1: Discover tools
list_external_tools(queries=["finance_"])

# Step 2: Get schemas (REQUIRED before calling)
describe_external_tools(source_id="finance", tool_names=["finance_quotes", "finance_financials"])

# Step 3: Call tools — always use source_id="finance"
call_external_tool(tool_name="<tool>", source_id="finance", arguments={...})
```

### Reference Date Protocol
Every finance query has a reference date. Map it to fiscal parameters before calling tools:

| Reference Date Month | Fiscal Quarter |
|---|---|
| January–March | Q1 |
| April–June | Q2 |
| July–September | Q3 |
| October–December | Q4 |

**Current date: March 3, 2026 → `as_of_fiscal_year=2026, as_of_fiscal_quarter=1`**

### Finance Tool Quick Reference

| Tool | Purpose | Key Parameters |
|---|---|---|
| `finance_tickers_lookup` | Resolve ticker from company name | `queries: ["Tesla"]` |
| `finance_quotes` | Real-time price, P/E, market cap | `ticker_symbols, fields` |
| `finance_ohlcv_histories` | Historical price OHLCV CSV | `ticker_symbols, start_date, end_date` |
| `finance_financials` | Income statement, balance sheet, CF | `ticker_symbols, period, as_of_fiscal_year, limit` |
| `finance_earnings` | Earnings transcripts, EPS history | `ticker_symbol, as_of_fiscal_year, data_types` |
| `finance_earnings_schedule` | Earnings dates | `ticker_symbols, as_of_fiscal_year` |
| `finance_company_profile` | CEO, sector, employees | `ticker_symbols` |
| `finance_company_peers` | Comparable companies | `ticker_symbol` |
| `finance_segments` | Revenue by segment, KPIs | `ticker_symbols` |
| `finance_estimates` | Analyst consensus forecasts | `ticker_symbols` |
| `finance_fundamentals` | P/E, EV/EBITDA time series | `ticker_symbols` |
| `finance_analyst_research` | Price targets, upgrades | `ticker_symbols` |
| `finance_market_gainers` | Top gainers today | — |
| `finance_market_losers` | Top losers today | — |
| `finance_massive` | Options, tick data, macro (raw API) | `pathname, params` |

### Common Finance Query Patterns

```python
# Get current quote
call_external_tool("finance_quotes", "finance", {
    "ticker_symbols": ["AAPL", "MSFT"],
    "fields": ["price", "marketCap", "pe", "eps", "dividendYieldTTM"]
})

# Get historical prices (use for past reference dates, not finance_quotes)
call_external_tool("finance_ohlcv_histories", "finance", {
    "ticker_symbols": ["NVDA"],
    "start_date_yyyy_mm_dd": "2025-01-01",
    "end_date_yyyy_mm_dd": "2026-03-03"
})

# Get financials — always pass as_of
call_external_tool("finance_financials", "finance", {
    "ticker_symbols": ["TSLA"],
    "period": "annual",
    "as_of_fiscal_year": 2025,
    "limit": 3,
    "income_statement_metrics": ["revenue", "netIncome", "grossProfit"],
    "balance_sheet_metrics": ["totalDebt", "cashAndCashEquivalents"],
    "cash_flow_metrics": ["freeCashFlow", "capitalExpenditures"]
})

# Get earnings transcript — primary source for guidance, KPIs, non-GAAP
call_external_tool("finance_earnings", "finance", {
    "ticker_symbol": "AAPL",
    "as_of_fiscal_year": 2025,
    "as_of_fiscal_quarter": 4,
    "limit": 1,
    "data_types": ["transcript_full"]
})

# Resolve unknown ticker
call_external_tool("finance_tickers_lookup", "finance", {
    "queries": ["Palantir Technologies", "ARM Holdings"]
})
```

### Data Source Decision Tree
```
Public company question?
├-- Revenue, margins, EPS, debt, FCF → finance_financials
├-- Guidance, non-GAAP metrics, segment KPIs, management commentary
│   → finance_earnings (transcripts answer ~50% of filing questions)
├-- Price targets, analyst ratings → finance_analyst_research
├-- Options, tick data, macro (treasury yields, CPI) → finance_massive
└-- Only if finance tools insufficient → search_web
    (10-K footnotes, proxy statements, 8-K offering terms)
```

### Investment Research Framework

**One-Page Investment Thesis Template:**
```
COMPANY: [Name] | TICKER: [X] | SECTOR: [X]
DATE: [X] | ANALYST: [X] | RECOMMENDATION: BUY / HOLD / SELL
PRICE TARGET: $[X] (current: $[X], upside: [X]%)

INVESTMENT THESIS (3-sentence summary):
[Core reason to own the stock]
[Key catalyst or competitive advantage]
[Risk-adjusted return expectation]

BUSINESS OVERVIEW:
Revenue model: [Subscription / Transaction / Product / Advertising]
Total addressable market: $[X]B
Market share: [X]%
Key products/services: [List]
Moat: [Brand / Network Effects / Switching Costs / Cost Advantage / IP]

FINANCIAL SNAPSHOT (LTM):
Revenue:       $[X]B    YoY growth: [X]%
Gross Margin:  [X]%     vs. peers: [higher/lower]
EBITDA Margin: [X]%     vs. budget: [on track/ahead/behind]
FCF Yield:     [X]%     Net Debt/EBITDA: [X]x
P/E (NTM):     [X]x     EV/Revenue (NTM): [X]x

BULL CASE ($[X] target, [X]% probability):
- [Catalyst 1]
- [Catalyst 2]

BASE CASE ($[X] target, [X]% probability):
- [Expected trajectory]
- [Key assumptions]

BEAR CASE ($[X] target, [X]% probability):
- [Risk 1]
- [Risk 2]

KEY RISKS:
1. [Competitive / Market / Regulatory / Execution]
2. [Balance sheet / Leverage / Liquidity]
3. [Macro / Interest rate / Currency]

COMPARABLE COMPANIES:
Company    EV/Revenue  EV/EBITDA  P/E    Growth   Margin
[Peer A]   [X]x        [X]x       [X]x   [X]%     [X]%
[Peer B]   [X]x        [X]x       [X]x   [X]%     [X]%
[Target]   [X]x        [X]x       [X]x   [X]%     [X]%
```

### Famous Investor Frameworks

**Warren Buffett (Intrinsic Value / Moat):**
```
Screen for:
- Consistent high ROE (> 15%) for 10+ years
- Low debt (Net Debt/EBITDA < 2x)
- Strong free cash flow conversion
- Identifiable economic moat (brand, network, cost)
- Management integrity and capital allocation track record
Value at: Conservative DCF, 10-year horizon, margin of safety > 25%
```

**Peter Lynch (GARP — Growth at Reasonable Price):**
```
PEG Ratio < 1.0 = potentially undervalued
Criteria: EPS growth 20–50% per year; P/E < growth rate
Tenbagger checklist: boring name, niche market, institutional under-ownership,
  no analyst coverage, growing earnings, product with repeat purchases
```

**Ray Dalio (All-Weather / Macro):**
```
Macro framework: Rising/Falling Growth × Rising/Falling Inflation
Risk parity: Weight positions by risk contribution, not dollar size
Asset allocation across environments:
  Rising growth: Stocks, corporate bonds
  Falling growth: Treasuries, gold
  Rising inflation: Commodities, TIPS, gold
  Falling inflation: Stocks, bonds
```

**Michael Burry (Deep Value / Catalyst):**
```
Focus on: Misunderstood companies, distressed assets, complex situations
Process: Bottom-up forensic accounting analysis; look for hidden value
Check: FCF vs reported earnings; off-balance sheet items; asset values
Catalyst required: Specific event that forces value recognition
```

**Citations:**
When presenting data from finance tools, always cite:
`https://perplexity.ai/finance/<TICKER>`

---

## 8. Data Engineering for Finance

### When to Use
- Building financial data pipelines (ERP → data warehouse)
- Automating GL extracts, trial balance reports
- Setting up dbt models for financial reporting
- Implementing data quality checks on financial data
- Streaming transaction data in real time
- Handling schema changes in financial source systems

### Financial Data Pipeline Architecture

```
Source Systems                Extract              Transform            Load
-----------------------------------------------------------------------------
ERP (SAP/Oracle/NetSuite) --► Fivetran/Airbyte --► dbt models --► Snowflake
General Ledger --------------► CDC (Debezium) ----► Spark ---------► BigQuery
AP/AR Subledgers ------------► API extracts -------► dbt -----------► Redshift
Payroll System --------------► SFTP/API -----------► Pandas --------► Databricks
Market Data API -------------► finance_tools -------► Python --------► PostgreSQL
Bank Feeds ------------------► Plaid / OFX ---------► dbt -----------► DW
```

### dbt Model Structure for Finance

```
dbt_finance/
├-- models/
│   ├-- staging/                    # 1:1 with source tables, clean & rename
│   │   ├-- stg_gl_transactions.sql
│   │   ├-- stg_chart_of_accounts.sql
│   │   ├-- stg_ar_invoices.sql
│   │   └-- stg_ap_invoices.sql
│   ├-- intermediate/               # Business logic, joins
│   │   ├-- int_trial_balance.sql
│   │   ├-- int_ar_aging.sql
│   │   └-- int_budget_actuals.sql
│   └-- marts/                      # Final reporting tables
│       ├-- finance/
│       │   ├-- fct_gl_transactions.sql
│       │   ├-- dim_chart_of_accounts.sql
│       │   ├-- fct_ar_aging.sql
│       │   ├-- fct_budget_vs_actual.sql
│       │   └-- rpt_income_statement.sql
│       └-- schema.yml              # Tests + documentation
```

**Example: Trial Balance dbt Model**
```sql
-- models/marts/finance/rpt_trial_balance.sql
{{
    config(
        materialized='table',
        tags=['finance', 'close', 'daily']
    )
}}

WITH gl AS (
    SELECT * FROM {{ ref('stg_gl_transactions') }}
),

coa AS (
    SELECT * FROM {{ ref('stg_chart_of_accounts') }}
),

aggregated AS (
    SELECT
        gl.account_number,
        coa.account_name,
        coa.account_type,           -- Asset, Liability, Equity, Revenue, Expense
        coa.financial_statement,    -- Balance Sheet, Income Statement
        coa.department,
        gl.fiscal_year,
        gl.fiscal_period,
        SUM(gl.debit_amount)  AS total_debits,
        SUM(gl.credit_amount) AS total_credits,
        SUM(gl.debit_amount) - SUM(gl.credit_amount) AS net_balance
    FROM gl
    LEFT JOIN coa USING (account_number)
    GROUP BY 1, 2, 3, 4, 5, 6, 7
)

SELECT
    *,
    CASE
        WHEN account_type IN ('Asset', 'Expense') AND net_balance >= 0 THEN net_balance
        WHEN account_type IN ('Liability', 'Equity', 'Revenue') AND net_balance <= 0 THEN ABS(net_balance)
        ELSE 0
    END AS normal_balance,
    CURRENT_TIMESTAMP AS dbt_updated_at

FROM aggregated
```

**Example: Budget vs Actual dbt Model**
```sql
-- models/marts/finance/fct_budget_vs_actual.sql
{{
    config(
        materialized='incremental',
        unique_key=['account_number', 'department', 'fiscal_year', 'fiscal_period'],
        tags=['finance', 'variance']
    )
}}

WITH actuals AS (
    SELECT
        account_number,
        department,
        fiscal_year,
        fiscal_period,
        SUM(amount) AS actual_amount
    FROM {{ ref('fct_gl_transactions') }}
    GROUP BY 1, 2, 3, 4
),

budget AS (
    SELECT
        account_number,
        department,
        fiscal_year,
        fiscal_period,
        budget_amount
    FROM {{ ref('stg_budget_data') }}
),

combined AS (
    SELECT
        COALESCE(a.account_number, b.account_number) AS account_number,
        COALESCE(a.department, b.department)          AS department,
        COALESCE(a.fiscal_year, b.fiscal_year)        AS fiscal_year,
        COALESCE(a.fiscal_period, b.fiscal_period)    AS fiscal_period,
        COALESCE(a.actual_amount, 0)                  AS actual_amount,
        COALESCE(b.budget_amount, 0)                  AS budget_amount,
        COALESCE(a.actual_amount, 0) - COALESCE(b.budget_amount, 0) AS variance_amount,
        CASE
            WHEN COALESCE(b.budget_amount, 0) = 0 THEN NULL
            ELSE (COALESCE(a.actual_amount, 0) - COALESCE(b.budget_amount, 0))
                 / ABS(COALESCE(b.budget_amount, 0))
        END AS variance_pct
    FROM actuals a
    FULL OUTER JOIN budget b USING (account_number, department, fiscal_year, fiscal_period)
)

SELECT * FROM combined
{% if is_incremental() %}
WHERE fiscal_year = EXTRACT(YEAR FROM CURRENT_DATE)
  AND fiscal_period = EXTRACT(MONTH FROM CURRENT_DATE)
{% endif %}
```

### Financial Data Quality Tests (dbt schema.yml)

```yaml
version: 2

models:
  - name: fct_gl_transactions
    description: "General Ledger transactions — source of truth for all financial reporting"
    tests:
      - dbt_utils.recency:
          datepart: day
          field: transaction_date
          interval: 2
          severity: warn

    columns:
      - name: transaction_id
        description: "Unique GL transaction identifier"
        tests:
          - unique
          - not_null

      - name: debit_amount
        tests:
          - not_null
          - dbt_utils.accepted_range:
              min_value: 0

      - name: credit_amount
        tests:
          - not_null
          - dbt_utils.accepted_range:
              min_value: 0

      - name: account_number
        tests:
          - not_null
          - relationships:
              to: ref('stg_chart_of_accounts')
              field: account_number

      - name: fiscal_period
        tests:
          - not_null
          - accepted_values:
              values: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]

  - name: rpt_trial_balance
    description: "Trial balance — debits must equal credits per period"
    tests:
      # Custom test: debits == credits in each period
      - dbt_utils.expression_is_true:
          expression: "ABS(SUM(total_debits) - SUM(total_credits)) < 0.01"
          config:
            severity: error
```

### Airflow DAG for Monthly Close Data Pipeline
```python
# dags/monthly_close_pipeline.py
from airflow import DAG
from airflow.operators.bash import BashOperator
from airflow.providers.slack.operators.slack_webhook import SlackWebhookOperator
from datetime import datetime, timedelta

default_args = {
    'owner': 'finance-data-team',
    'email': ['finance-alerts@company.com'],
    'email_on_failure': True,
    'retries': 2,
    'retry_delay': timedelta(minutes=10),
}

with DAG(
    'monthly_close_pipeline',
    default_args=default_args,
    description='Month-end close data pipeline: ERP → dbt → reports',
    schedule_interval='0 6 1 * *',   # 6am on 1st of every month
    start_date=datetime(2026, 1, 1),
    catchup=False,
    tags=['finance', 'close', 'monthly'],
) as dag:

    extract_gl = BashOperator(
        task_id='extract_gl_transactions',
        bash_command='python /opt/airflow/scripts/extract_erp.py --period {{ ds[:7] }}'
    )

    extract_budget = BashOperator(
        task_id='extract_budget_data',
        bash_command='python /opt/airflow/scripts/extract_budget.py --period {{ ds[:7] }}'
    )

    run_staging = BashOperator(
        task_id='dbt_run_staging',
        bash_command='cd /opt/dbt && dbt run --select staging.*'
    )

    run_marts = BashOperator(
        task_id='dbt_run_marts',
        bash_command='cd /opt/dbt && dbt run --select marts.finance.*'
    )

    test_data = BashOperator(
        task_id='dbt_test',
        bash_command='cd /opt/dbt && dbt test --select marts.finance.*'
    )

    generate_reports = BashOperator(
        task_id='generate_financial_reports',
        bash_command='python /opt/airflow/scripts/generate_reports.py --period {{ ds[:7] }}'
    )

    notify_success = SlackWebhookOperator(
        task_id='notify_close_complete',
        slack_webhook_conn_id='slack_finance',
        message='Month-end close pipeline completed for {{ ds[:7] }}. Reports available.',
        trigger_rule='all_success',
    )

    [extract_gl, extract_budget] >> run_staging >> run_marts >> test_data >> generate_reports >> notify_success
```

### Architecture Decision Guide

| Scenario | Recommended Stack | Notes |
|---|---|---|
| Daily GL extract, < 1M rows | Fivetran + dbt + Snowflake | Simplest, lowest maintenance |
| Real-time transaction monitoring | Debezium + Kafka + Spark Streaming | Detect fraud/anomalies in seconds |
| Multi-entity consolidation | dbt + Snowflake + Monte Carlo | Elimination logic in dbt |
| ML forecasting from GL data | Spark + MLflow + Airflow | Feature engineering from GL history |
| ERP to BI tool | Fivetran + dbt + Looker/Tableau | Standard modern data stack |

---

## 9. ML & Forecasting for Finance

### When to Use
- Revenue forecasting with ML methods
- Anomaly detection in transactions (fraud, booking errors)
- Churn prediction for subscription businesses
- Cash flow forecasting
- Demand planning for inventory finance
- Credit risk scoring

### Revenue Forecasting Workflow

**Step 1: Feature Engineering from Financial Data**
```python
import pandas as pd
import numpy as np

def engineer_revenue_features(gl_df: pd.DataFrame) -> pd.DataFrame:
    """
    Build ML features from GL transaction history for revenue forecasting.
    
    Input: DataFrame with columns [date, account, amount, department, customer_id]
    Output: Monthly feature matrix for forecasting
    """
    # Aggregate to monthly revenue
    monthly = gl_df[gl_df['account'].str.startswith('4')].copy()  # Revenue accounts
    monthly['year_month'] = pd.to_datetime(monthly['date']).dt.to_period('M')
    
    revenue = monthly.groupby('year_month')['amount'].sum().reset_index()
    revenue.columns = ['year_month', 'revenue']
    revenue = revenue.sort_values('year_month')
    
    # Lag features (prior months)
    for lag in [1, 2, 3, 6, 12]:
        revenue[f'revenue_lag_{lag}'] = revenue['revenue'].shift(lag)
    
    # Rolling statistics
    revenue['revenue_ma3']  = revenue['revenue'].rolling(3).mean()
    revenue['revenue_ma12'] = revenue['revenue'].rolling(12).mean()
    revenue['revenue_std3'] = revenue['revenue'].rolling(3).std()
    
    # YoY growth
    revenue['yoy_growth'] = revenue['revenue'].pct_change(12)
    
    # Seasonality features
    revenue['month'] = revenue['year_month'].dt.month
    revenue['quarter'] = revenue['year_month'].dt.quarter
    
    # Month-end effects (close timing)
    revenue['is_q_end'] = revenue['month'].isin([3, 6, 9, 12]).astype(int)
    revenue['is_year_end'] = (revenue['month'] == 12).astype(int)
    
    return revenue.dropna()


def build_revenue_forecast_model(features_df: pd.DataFrame, 
                                  horizon_months: int = 3):
    """
    Train XGBoost revenue forecast model with cross-validation.
    Returns forecast with confidence intervals.
    """
    from xgboost import XGBRegressor
    from sklearn.model_selection import TimeSeriesSplit
    from sklearn.metrics import mean_absolute_percentage_error
    
    feature_cols = [c for c in features_df.columns 
                    if c not in ['year_month', 'revenue']]
    
    X = features_df[feature_cols].values
    y = features_df['revenue'].values
    
    # Time series cross-validation (no data leakage)
    tscv = TimeSeriesSplit(n_splits=5)
    cv_scores = []
    
    model = XGBRegressor(
        n_estimators=200,
        max_depth=4,
        learning_rate=0.05,
        subsample=0.8,
        random_state=42
    )
    
    for train_idx, val_idx in tscv.split(X):
        model.fit(X[train_idx], y[train_idx])
        preds = model.predict(X[val_idx])
        mape = mean_absolute_percentage_error(y[val_idx], preds)
        cv_scores.append(mape)
    
    print(f"CV MAPE: {np.mean(cv_scores):.2%} ± {np.std(cv_scores):.2%}")
    
    # Retrain on full data
    model.fit(X, y)
    
    # Feature importance
    importance = pd.Series(
        model.feature_importances_, 
        index=feature_cols
    ).sort_values(ascending=False)
    
    return model, importance
```

**Step 2: Scenario Forecasting (Base / Bull / Bear)**
```python
def generate_scenarios(base_forecast: float, 
                        growth_assumptions: dict) -> dict:
    """
    Generate three-scenario revenue forecast.
    
    growth_assumptions = {
        'bear': {'revenue_growth': -0.05, 'probability': 0.20},
        'base': {'revenue_growth': 0.10,  'probability': 0.60},
        'bull': {'revenue_growth': 0.20,  'probability': 0.20},
    }
    """
    scenarios = {}
    for name, params in growth_assumptions.items():
        scenarios[name] = {
            'forecast': base_forecast * (1 + params['revenue_growth']),
            'growth_rate': params['revenue_growth'],
            'probability': params['probability'],
        }
    
    # Expected value
    ev = sum(s['forecast'] * s['probability'] 
             for s in scenarios.values())
    scenarios['expected_value'] = ev
    
    return scenarios


# Example usage
growth_assumptions = {
    'bear': {'revenue_growth': -0.03, 'probability': 0.20},
    'base': {'revenue_growth': 0.12,  'probability': 0.60},
    'bull': {'revenue_growth': 0.22,  'probability': 0.20},
}

base_revenue = 10_000_000  # $10M current quarter
scenarios = generate_scenarios(base_revenue, growth_assumptions)

for name, values in scenarios.items():
    if name != 'expected_value':
        print(f"{name.upper():6s}: ${values['forecast']:>12,.0f}  "
              f"({values['growth_rate']:+.1%} growth, "
              f"{values['probability']:.0%} probability)")
print(f"{'EV':6s}: ${scenarios['expected_value']:>12,.0f}")
```

### Anomaly Detection in Financial Transactions

```python
from sklearn.ensemble import IsolationForest
from sklearn.preprocessing import StandardScaler
import pandas as pd
import numpy as np

def detect_transaction_anomalies(transactions_df: pd.DataFrame,
                                  contamination: float = 0.01) -> pd.DataFrame:
    """
    Detect anomalous financial transactions using Isolation Forest.
    
    Detects: Unusual amounts, timing, account combinations, round-number entries
    
    Args:
        transactions_df: GL transactions with amount, hour, account, user columns
        contamination: Expected fraction of anomalies (default 1%)
    
    Returns:
        DataFrame with anomaly_score and is_anomaly columns
    """
    # Feature engineering for anomaly detection
    df = transactions_df.copy()
    
    # Amount-based features
    df['log_amount'] = np.log1p(df['amount'].abs())
    df['is_round_number'] = (df['amount'] % 1000 == 0).astype(int)
    df['is_round_5k'] = (df['amount'] % 5000 == 0).astype(int)
    
    # Timing features (Benford's Law analysis)
    df['first_digit'] = df['amount'].abs().astype(str).str[0].astype(int)
    benfords_expected = {1: 0.301, 2: 0.176, 3: 0.125, 4: 0.097,
                         5: 0.079, 6: 0.067, 7: 0.058, 8: 0.051, 9: 0.046}
    df['benfords_deviation'] = df['first_digit'].map(benfords_expected)
    
    # Posted hour (unusual hours = higher risk)
    df['post_hour'] = pd.to_datetime(df['posted_at']).dt.hour
    df['is_off_hours'] = ((df['post_hour'] < 7) | (df['post_hour'] > 20)).astype(int)
    df['is_weekend'] = pd.to_datetime(df['posted_at']).dt.dayofweek.isin([5, 6]).astype(int)
    
    # Account-level Z-score
    df['account_z_score'] = df.groupby('account_number')['amount'].transform(
        lambda x: (x - x.mean()) / x.std()
    )
    
    # Select features for model
    feature_cols = ['log_amount', 'is_round_number', 'is_off_hours', 
                    'is_weekend', 'account_z_score', 'benfords_deviation']
    X = df[feature_cols].fillna(0)
    
    # Scale features
    scaler = StandardScaler()
    X_scaled = scaler.fit_transform(X)
    
    # Isolation Forest
    iso_forest = IsolationForest(
        contamination=contamination,
        n_estimators=200,
        random_state=42
    )
    
    df['anomaly_score'] = iso_forest.fit_predict(X_scaled)
    df['anomaly_raw_score'] = iso_forest.score_samples(X_scaled)
    df['is_anomaly'] = (df['anomaly_score'] == -1)
    
    # Return anomalies sorted by risk
    anomalies = df[df['is_anomaly']].sort_values('anomaly_raw_score')
    print(f"Flagged {len(anomalies)} anomalies out of {len(df)} transactions ({len(anomalies)/len(df):.1%})")
    
    return anomalies[['transaction_id', 'date', 'account_number', 
                       'amount', 'description', 'posted_by',
                       'is_off_hours', 'is_round_number', 'anomaly_raw_score']]
```

### MLOps for Finance Models

**Retraining Triggers for Finance:**
| Trigger | Detection | Action |
|---|---|---|
| Period end | Monthly cron | Retrain with latest close data |
| MAPE > 10% | Monitor forecast accuracy | Immediate retrain + alert |
| Budget revision | Finance team input | Retrain with new budget baseline |
| M&A / divestiture | ERP entity change | Full data refresh + retrain |
| Significant market event | Macro indicator threshold | Retrain + manual review |

**Model Monitoring Dashboard:**
```python
def track_forecast_accuracy(actuals: pd.Series, forecasts: pd.Series) -> dict:
    """
    Track forecast accuracy metrics against finance team targets.
    Target: Revenue +/-5%, Expenses +/-3%
    """
    from sklearn.metrics import (mean_absolute_error, 
                                  mean_absolute_percentage_error,
                                  mean_squared_error)
    
    mae   = mean_absolute_error(actuals, forecasts)
    mape  = mean_absolute_percentage_error(actuals, forecasts)
    rmse  = mean_squared_error(actuals, forecasts, squared=False)
    
    # Bias (over/under forecast)
    bias = (forecasts - actuals).mean()
    bias_pct = bias / actuals.mean()
    
    metrics = {
        'MAE':       f"${mae:,.0f}",
        'MAPE':      f"{mape:.2%}",
        'RMSE':      f"${rmse:,.0f}",
        'Bias':      f"${bias:,.0f} ({bias_pct:+.2%})",
        'On Target': mape <= 0.05,  # Finance team target: +/-5%
    }
    
    return metrics
```

---

## 10. Invoice & Document Management

### When to Use
- Organizing a folder of invoices for tax preparation
- Standardizing invoice filenames and folder structure
- Extracting key data (vendor, date, amount) from PDFs and images
- Creating an invoice summary CSV for accountants
- Setting up ongoing automated invoice organization
- Reconciling expenses for reimbursement or AP processing

### Invoice Organization Workflow

**Step 1: Scan the Folder**
```bash
# Find all invoice-related files
find . -type f \( -name "*.pdf" -o -name "*.jpg" -o -name "*.png" \) -print
```
Report: total count, file types, date range, current organization.

**Step 2: Extract Information from Each File**

From PDFs (text extraction):
- Look for: `Invoice Date:`, `Date:`, `Issued:`
- Look for: `Invoice #:`, `Invoice Number:`
- Company name (usually at top)
- `Amount Due:`, `Total:`, `Amount:`
- `Description:`, `Service:`, `Product:`

From images: Read visible text, identify vendor at top, find date and total.

Fallback: Use filename clues; check file modification date; flag for review.

**Step 3: Standardized Filename Format**
```
YYYY-MM-DD Vendor - Invoice - Description.ext

Examples:
2024-03-15 Adobe - Invoice - Creative Cloud.pdf
2024-01-10 Amazon - Receipt - Office Supplies.pdf
2023-12-01 Stripe - Invoice - Monthly Payment Processing.pdf
```

**Step 4: Organization Structures**

```
# By Vendor (Simple)
Invoices/
├-- Adobe/
├-- Amazon/
└-- Google/

# By Year and Category (Tax-Friendly — recommended)
Invoices/
├-- 2024/
│   ├-- Software/
│   ├-- Hardware/
│   ├-- Services/
│   ├-- Travel/
│   └-- Office/
└-- 2025/
    └-- ...

# By Quarter (Detailed Tracking)
Invoices/
├-- 2024/
│   ├-- Q1/
│   │   ├-- Software/
│   │   └-- Travel/
│   └-- Q2/

# By Tax Category (Accountant-Ready)
Invoices/
├-- Deductible/
│   ├-- Software/
│   └-- Professional-Services/
├-- Partially-Deductible/
│   └-- Meals-Travel/
└-- Personal/
```

**Step 5: Generate Invoice Summary CSV**
```csv
Date,Vendor,Invoice Number,Description,Amount,Category,Tax Deductible,File Path
2024-03-15,Adobe,INV-12345,Creative Cloud,52.99,Software,Yes,Invoices/2024/Software/Adobe/...
2024-03-10,Amazon,123-4567890,Office Supplies,127.45,Office,Yes,Invoices/2024/Office/Amazon/...
2024-02-28,Delta Airlines,TICKET-789,Flight NYC-SFO,342.00,Travel,Partial,Invoices/2024/Travel/...
```

**Step 6: Completion Summary**
```
Processed:    [X] invoices
Date range:   [earliest] to [latest]
Total amount: $[sum]
Vendors:      [Y] unique vendors

Files needing review: [list files where info couldn't be extracted]
Next steps:
1. Review invoice-summary.csv
2. Check Needs-Review/ folder
3. Import CSV into accounting software
4. Keep originals for 7 years (standard audit period)
```

### Special Cases

| Situation | Resolution |
|---|---|
| Missing date/vendor | Use file modification date; flag in Needs-Review/ folder |
| Duplicate invoices | Compare file hashes; keep highest quality version; note in CSV |
| Multi-page invoices | Merge PDFs if needed; use consistent naming for parts |
| Non-standard formats | Extract what's possible; flag for review |
| Gmail "invoice.pdf" downloads | Read each file to extract real vendor/date; rename from content |

### Pro Tips
1. Organize monthly, not annually — far less work per session
2. Save all invoices to one folder before batch processing
3. Keep originals before reorganizing (copy, don't move)
4. Tag deductibility at time of receipt, not at year-end
5. Include amounts in CSV for budget tracking
6. Retain receipts for 7 years (standard IRS audit window)
7. For subscriptions: create a recurring invoice tracker in the CSV

---

## 11. Unique Perplexity Computer Capabilities

These capabilities are available only through Perplexity Computer's connected tools and are not available in Claude Code or other environments.

### Real-Time & Historical Market Data
```
finance_quotes        → Live prices, P/E, market cap for stocks/crypto/ETFs
finance_ohlcv_histories → Historical OHLCV data as CSV (no web search needed)
finance_market_gainers/losers/most_active → Today's movers
finance_market_sentiment → Aggregate market mood (bullish/bearish/neutral)
finance_ticker_sentiment → Bull/bear analysis per ticker
```

### SEC Filings & Earnings Transcripts
```
finance_earnings      → Full earnings call transcripts with management Q&A
                        Primary source for:
                        - Forward guidance (revenue ranges, margin targets)
                        - Non-GAAP metrics (adjusted EBITDA, organic growth)
                        - Company-specific KPIs (ARR, GMV, take rate, churn)
                        - Beat/miss vs prior guidance
finance_financials    → Standardized income statement, balance sheet, CF
                        Direct from SEC filings, structured format
finance_segments      → Revenue by segment, unit economics, operating KPIs
finance_estimates     → Analyst consensus forward estimates
finance_analyst_research → Price targets, rating changes, upgrades/downgrades
```

### Congressional Stock Activity
```
finance_list_politicians    → All tracked politicians with stock activity
finance_politician_holdings → A specific politician's full portfolio
finance_politician_trades   → Recent congressional transactions
finance_ticker_politician_holders → Politicians holding a specific stock
```

### Advanced Raw API (finance_massive)
```
Options chains:     /v3/snapshot/options/{ticker}
Tick-level trades:  /v3/trades/{ticker}
Treasury yields:    /fed/v1/treasury-yields
CPI/Inflation:      /fed/v1/inflation
Labor market:       /fed/v1/labor-market
RSI indicator:      /v1/indicators/rsi/{ticker}
Index aggregates:   /v2/aggs/ticker/{index}/range/{mult}/{timespan}/{from}/{to}
```

### User Watchlist
```
finance_watchlist_fetch → Retrieve user's personal watchlist/portfolio
```

### Citation Protocol
When presenting data from any finance tool, always cite the source:
```
https://perplexity.ai/finance/<TICKER>
Example: "Apple's revenue grew 6% YoY ([Perplexity Finance – AAPL](https://perplexity.ai/finance/AAPL))"
```

---

## 12. Quick-Start Decision Guide

Use this to identify which section to apply:

| User Request | Section to Use | Key Tools/Templates |
|---|---|---|
| "Prepare income statement" | §1 Financial Statements | IS template, ratio table |
| "Calculate P/E ratio" | §1 Financial Statements | Valuation multiples table |
| "Build a DCF model" | §1 Financial Statements | DCF workflow + §7 finance_financials |
| "Record a payroll entry" | §2 Journal Entries | Payroll JE template |
| "Accrue unbilled expenses" | §2 Journal Entries | Accrual JE template |
| "Reconcile the bank account" | §3 Reconciliation | Bank rec template |
| "Substantiate balance sheet" | §3 Reconciliation | BS substantiation checklist |
| "Plan the monthly close" | §4 Close Management | 15-day calendar + task tracker |
| "Explain why we missed budget" | §5 Variance Analysis | Waterfall template + decomposition |
| "Test SOX controls" | §6 Audit Support | Control test workpaper + sample sizes |
| "Get Apple's stock price" | §7 Markets | finance_quotes (NOT search_web) |
| "Find Tesla's earnings transcript" | §7 Markets | finance_earnings |
| "Research an investment" | §7 Markets | Investment thesis template |
| "Build a GL data pipeline" | §8 Data Engineering | dbt models + Airflow DAG |
| "Forecast next quarter revenue" | §9 ML & Forecasting | XGBoost forecast + scenarios |
| "Detect suspicious transactions" | §9 ML & Forecasting | Isolation Forest code |
| "Organize invoices for taxes" | §10 Invoice Management | Workflow + CSV template |
| "Get options chain data" | §11 Unique Capabilities | finance_massive |
| "What politicians own NVDA?" | §11 Unique Capabilities | finance_ticker_politician_holders |

---

## Appendix A: Financial Accounts Quick Reference

### Account Number Conventions (Typical 5-digit CoA)
```
1XXXX — Assets
  10XXX — Cash & Cash Equivalents
  11XXX — Accounts Receivable
  12XXX — Inventories
  13XXX — Prepaid Expenses & Other Current Assets
  14XXX — Fixed Assets (Gross)
  15XXX — Accumulated Depreciation (contra)
  16XXX — Intangibles & Goodwill
  19XXX — Other Non-Current Assets

2XXXX — Liabilities
  20XXX — Accounts Payable
  21XXX — Accrued Liabilities
  22XXX — Deferred Revenue
  23XXX — Short-term Debt
  24XXX — Long-term Debt
  25XXX — Lease Liabilities
  29XXX — Other Liabilities

3XXXX — Equity
  30XXX — Common Stock & APIC
  31XXX — Retained Earnings
  32XXX — AOCI
  33XXX — Treasury Stock (contra)

4XXXX — Revenue
  40XXX — Product Revenue
  41XXX — Service Revenue
  42XXX — Subscription Revenue
  43XXX — Other Revenue

5XXXX — Cost of Revenue
  50XXX — COGS — Product
  51XXX — COGS — Service

6XXXX — Operating Expenses
  60XXX — Research & Development
  61XXX — Sales & Marketing
  62XXX — General & Administrative
  63XXX — Depreciation & Amortization

7XXXX — Other Income/Expense
  70XXX — Interest Income
  71XXX — Interest Expense
  72XXX — Other Non-Operating

8XXXX — Tax
  80XXX — Income Tax Expense
  81XXX — Deferred Tax
```

---

## Appendix B: Common Financial Abbreviations

| Abbreviation | Full Name |
|---|---|
| EBITDA | Earnings Before Interest, Taxes, Depreciation & Amortization |
| FCF | Free Cash Flow |
| NWC | Net Working Capital |
| WACC | Weighted Average Cost of Capital |
| CAPM | Capital Asset Pricing Model |
| DCF | Discounted Cash Flow |
| LTM | Last Twelve Months |
| NTM | Next Twelve Months |
| YTD | Year to Date |
| MTD | Month to Date |
| QTD | Quarter to Date |
| YoY | Year over Year |
| QoQ | Quarter over Quarter |
| MoM | Month over Month |
| AR | Accounts Receivable |
| AP | Accounts Payable |
| DSO | Days Sales Outstanding |
| DPO | Days Payable Outstanding |
| DIO | Days Inventory Outstanding |
| CCC | Cash Conversion Cycle |
| NIM | Net Interest Margin |
| ROE | Return on Equity |
| ROA | Return on Assets |
| ROIC | Return on Invested Capital |
| SBC | Stock-Based Compensation |
| CapEx | Capital Expenditures |
| D&A | Depreciation & Amortization |
| GAAP | Generally Accepted Accounting Principles |
| ASC | Accounting Standards Codification |
| PCAOB | Public Company Accounting Oversight Board |
| SOX | Sarbanes-Oxley Act |
| MW | Material Weakness |
| SD | Significant Deficiency |
| PBC | Prepared by Client |
| ETL | Extract, Transform, Load |
| ELT | Extract, Load, Transform |
| dbt | Data Build Tool |
| MAPE | Mean Absolute Percentage Error |
| PSI | Population Stability Index |
| ARR | Annual Recurring Revenue |
| MRR | Monthly Recurring Revenue |
| CAC | Customer Acquisition Cost |
| LTV | Lifetime Value |
| NRR | Net Revenue Retention |
| GMV | Gross Merchandise Value |

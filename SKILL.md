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
Bank Recs ──────────────────────────────────────────► Controller Review
AR Rec ──────────────────────────────────────────────► Consolidation
AP Rec ──────────────────────────────────────────────► Consolidation
Payroll JEs ─────────────────────────────────────────► Accrual Review
Fixed Asset D&A ─────────────────────────────────────► Balance Sheet
Accruals (all) ──────────────────────────────────────► Prelim P&L
                                                              │
                                                              ▼
Revenue Recognition ─────────────────────────────────► Prelim P&L
                                                              │
                                                              ▼
Prelim P&L ──────────────────────────────────────────► Tax Provision
                                                              │
IC Elimination ──────────────────────────────────────► Consolidation
                                                              │
Prelim P&L + Tax + IC ───────────────────────────────► Final Consolidation
                                                              │
                                                              ▼
Final Consolidation ─────────────────────────────► Management Package
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
Total Revenue Variance = Price Effect + Volume Effect + Mix Effect

Price Effect  = (Actual Price − Budget Price) × Actual Volume
Volume Effect = (Actual Volume − Budget Volume) × Budget Price
Mix Effect    = Residual (total variance − price − volume)

Example:
  Budget: 1,000 units × $100 = $100,000
  Actual: 1,100 units × $95 = $104,500
  Total variance: +$4,500 (F)

  Price Effect:  ($95 − $100) × 1,100 = −$5,500 (U)
  Volume Effect: (1,100 − 1,000) × $100 = +$10,000 (F)
  Total:         −$5,500 + $10,000 = +$4,500 ✓
```

### Narrative Commentary Standards

**Structure for each material variance:**
1. **What**: State the variance amount and direction (favorable/unfavorable)
2. **Why**: Identify the primary driver (volume, price, timing, one-time, structural)
3. **So what**: Explain the business implication and whether it will recur

**Good commentary example:**
> "S&M expense was $2.1M, $0.4M (16%) unfavorable to budget. The variance reflects $0.3M of accelerated hiring to support Q4 enterprise pipeline (3 AEs vs. 1 budgeted), partially offset by $0.1M in deferred event spend. The hiring headcount was approved by the CEO in September; the associated quota attainment is not expected until Q2 of next year."

**Poor commentary example:**
> "S&M was over budget due to higher headcount."

---

## 6. Audit Support & SOX Compliance

### When to Use
- Preparing for internal or external audit fieldwork
- Documenting controls for SOX 404 testing
- Selecting statistical samples for control testing
- Responding to auditor requests
- Classifying control deficiencies

### SOX 404 Control Documentation Standards

#### Control Description Requirements
```
Control ID:          [CC-###]
Control Name:        [Descriptive name]
Control Objective:   [What risk this control addresses]
Control Type:        [Preventive / Detective]
Automation:          [Manual / Automated / IT-Dependent Manual]
Frequency:           [Daily / Weekly / Monthly / Quarterly / Annual]
Risk Category:       [Financial Reporting / Operations / Compliance]
Control Owner:       [Name / Role]

Control Activity:
  [Specific step-by-step description of what the control performer does,
  what they review, how they document their review, and how they evidence
  that the control was performed]

Evidence Retained:
  [Specific document or system record that proves the control was performed]

IT Dependencies:
  [Systems, reports, or application controls this control relies upon]

Related Controls:
  [Upstream or downstream controls in the same process]
```

#### COSO Framework Checklist
```
Control Environment
□ Tone at the top documented (code of conduct, ethics policy)
□ Board and audit committee oversight structure defined
□ HR policies for hiring, training, and evaluation in place
□ Organizational structure and reporting lines documented

Risk Assessment
□ Financial reporting risks identified and documented
□ Risk owners assigned
□ Control objectives linked to identified risks
□ Fraud risk assessment performed

Control Activities
□ Controls designed to address each identified risk
□ IT general controls (ITGC) documented and operating
□ Segregation of duties maintained
□ Management review controls operating

Information & Communication
□ Financial reporting information is complete and accurate
□ Deficiencies communicated to appropriate levels of management
□ Communication with external parties functioning

Monitoring Activities
□ Ongoing and separate evaluations of controls documented
□ Control deficiencies remediated on a timely basis
□ Results reported to appropriate management
```

### Sample Selection Methods

#### Statistical Sampling

| Population Size | Confidence Level | Tolerable Deviation Rate | Sample Size |
|---|---|---|---|
| Any | 95% | 5% | 59 |
| Any | 95% | 10% | 29 |
| Any | 90% | 5% | 45 |
| Any | 90% | 10% | 22 |

**Formula for attribute sampling:**
```
n = (Z^2 × p × q) / e^2

Where:
  Z = confidence factor (1.96 for 95%; 1.645 for 90%)
  p = expected deviation rate (use 0.5 if unknown to maximize sample)
  q = 1 - p
  e = tolerable error rate
```

#### Haphazard Sampling (Non-Statistical)
For populations where statistical rigor is not required:
- Select items from throughout the population (beginning, middle, end)
- Include items of varying sizes and types
- Avoid systematic selection patterns
- Document the selection rationale

#### Judgmental Sampling
For targeted testing of higher-risk items:
- Large dollar items above a threshold
- Items related to identified risks
- Items from a specific time period
- Items involving a specific counterparty
- Document why these items were selected

### SOX Testing Workpaper Template
```
SOX Control Testing Workpaper

Control ID:          [CC-###]
Test Date:           [Date(s) of testing]
Tester:              [Name / Role]
Reviewer:            [Name / Role]

CONTROL DESCRIPTION
[Copy of control description from control matrix]

TEST OBJECTIVE
[What assertion this test is designed to address: completeness, accuracy, 
existence, valuation, rights/obligations, presentation/disclosure]

POPULATION
  Total population: [N items] / $[Amount]
  Population period: [From] to [To]
  Source: [System / Report name and run date]

SAMPLE SELECTION
  Method: [Statistical / Haphazard / Judgmental]
  Sample size: [N] items
  Items tested: [List or attach sample selection workpaper]

TEST PROCEDURES
1. [Specific procedure performed — what was inspected, what was verified]
2. [Specific procedure performed]
3. [Specific procedure performed]

EXCEPTIONS IDENTIFIED
  [Exception 1]: [Description, item reference, amount if applicable]
  [Exception 2]: [Description, item reference]
  Total exceptions: [N] out of [N] tested

CONCLUSION
  Deviation rate: [N exceptions / N tested = X%]
  Upper deviation rate: [Calculated using appropriate formula]
  Tolerable deviation rate: [X%]
  ☐ Control is EFFECTIVE: deviation rate ≤ tolerable deviation rate
  ☐ Control is INEFFECTIVE: deviation rate > tolerable deviation rate

DEFICIENCY CLASSIFICATION (if applicable)
  ☐ Control Deficiency: does not affect significant account/assertion
  ☐ Significant Deficiency: important enough to merit attention
  ☐ Material Weakness: reasonable possibility of material misstatement
```

### Control Deficiency Classification Matrix

| Severity | Definition | Required Actions |
|---|---|---|
| Control Deficiency | Design or operation flaw unlikely to result in material misstatement | Remediate; monitor | 
| Significant Deficiency | More than remote likelihood of more-than-inconsequential misstatement | Report to audit committee |
| Material Weakness | Reasonable possibility of material misstatement | Report to audit committee; disclose publicly (public companies) |

**Aggregation rule:** Multiple control deficiencies addressing the same risk area must be evaluated in combination — they may aggregate to a higher severity level.

---

## 7. Market Data & Investment Research

### When to Use
- Looking up current stock prices, financials, or earnings data
- Building an investment thesis
- Comparable-company analysis (comps)
- Screening for investment ideas
- Emulating a specific investor's methodology

### Perplexity Computer Finance Tools

| Tool | What It Returns | When to Use |
|---|---|---|
| get_stock_price | Real-time or delayed price, volume, market cap | Any current price query |
| get_historical_prices | OHLCV data for a specified date range | Trend analysis, charting, returns |
| get_financial_statements | IS, BS, CF from SEC filings | Fundamental analysis |
| get_earnings_transcript | Full transcript with Q&A | Management guidance, KPIs, strategy |
| get_analyst_estimates | EPS and revenue consensus estimates | Earnings expectations, surprise analysis |
| get_insider_transactions | Insider buys/sells with filing dates | Insider sentiment |
| screen_stocks | Filter by market cap, ratio, sector | Idea generation, peer screening |
| get_sec_filing | Full 10-K, 10-Q, 8-K, proxy text | Deep due diligence, risk factors |

### Investment Research Workflow

```
Phase 1: Screening
  → screen_stocks: Apply quantitative filters (sector, size, valuation)
  → Initial list of candidates

Phase 2: Financial Overview
  → get_financial_statements: Pull IS, BS, CF for 3–5 years
  → Calculate key ratios (margins, returns, leverage)
  → get_historical_prices: Calculate historical returns and volatility

Phase 3: Earnings Quality
  → get_earnings_transcript: Review last 4 quarters
  → Extract: Management guidance, KPI trends, risk flags, strategic commentary
  → get_analyst_estimates: Compare actual vs. estimates; assess beat/miss pattern

Phase 4: Valuation
  → Build DCF (see Section 1 template)
  → Comparable company analysis (EV/EBITDA, P/E, P/S vs. peers)
  → Implied price range: Low / Base / Bull case

Phase 5: Due Diligence
  → get_sec_filing: Read 10-K risk factors, MD&A, footnotes
  → get_insider_transactions: Check alignment
  → Qualitative assessment: Moat, management quality, competitive dynamics

Phase 6: Thesis Documentation
  → Produce investment memo (see template below)
```

### Investment Memo Template
```
## Investment Memo: [Company] ([TICKER])

**Date**: [Date]     **Analyst**: [Name]
**Recommendation**: BUY / HOLD / SELL
**Price Target**: $[X]     **Current Price**: $[X]     **Upside/Downside**: [X]%
**Time Horizon**: [X months/years]

### Thesis Summary
[2–3 sentences: why this security is mispriced and what the catalyst is]

### Key Facts
| Metric | Value |
|---|---|
| Market Cap | $[X]B |
| EV | $[X]B |
| Revenue (TTM) | $[X]M / [Y]% YoY growth |
| Gross Margin | [X]% |
| EBITDA Margin | [X]% |
| Net Debt | $[X]M / [X]x EBITDA |
| EV/EBITDA (NTM) | [X]x vs. peers [X]x |
| P/E (NTM) | [X]x vs. peers [X]x |

### Bull Case
- [Catalyst 1: specific and measurable]
- [Catalyst 2]
- [Upside scenario: $X price target — [X]x EBITDA on $[Y]M EBITDA]

### Base Case
- [Expected scenario assumptions]
- [Base case price target: $X]

### Bear Case
- [Risk 1: what goes wrong and how bad]
- [Risk 2]
- [Downside scenario: $X floor — what multiple / EBITDA]

### Valuation
| Method | Implied Price | Weight |
|---|---|---|
| DCF (WACC: [X]%, TGR: [Y]%) | $[X] | [X]% |
| EV/EBITDA ([X]x NTM) | $[X] | [X]% |
| P/E ([X]x NTM) | $[X] | [X]% |
| Weighted Average Price Target | $[X] | |

### Risks
| Risk | Probability | Impact | Mitigation |
|---|---|---|---|
| [Risk 1] | [H/M/L] | [H/M/L] | [Mitigant] |
| [Risk 2] | [H/M/L] | [H/M/L] | [Mitigant] |

### Monitoring Triggers
- Re-evaluate if [specific metric] changes by more than [threshold]
- Quarterly earnings: focus on [specific KPI]
- Stop-loss at $[X] (−[Y]% from current)
```

### Famous Investor Frameworks

#### Warren Buffett (Value + Quality)
Screen for: ROE > 15% sustained; low debt; strong FCF; simple business; economic moat
Key question: "Would I be comfortable owning this business for 10 years if the market closed?"
Red flags: High leverage; commodity business; frequent equity issuance

#### Peter Lynch (Growth at Reasonable Price)
Screen for: PEG < 1.0; earnings growth 20–50%; institutional underownership
Key question: "Can I explain this company's business to a 12-year-old?"
Red flags: Hot industry hype; over-diversified management; consensus darling

#### Stanley Druckenmiller (Macro + Momentum)
Focus: Macro thesis driving sector rotation; leading indicators; currency flows
Key question: "What is the key variable the market is not pricing correctly?"
Approach: Concentrate in highest-conviction ideas; cut losses fast; let winners ride

#### George Soros (Reflexivity)
Focus: Self-reinforcing feedback loops; inflection points; trend reversals
Key question: "Where does market perception deviate from underlying reality?"
Approach: Find the prevailing bias; determine when it will correct; position ahead

#### Michael Burry (Deep Value + Catalyst)
Screen for: Significant discount to tangible book or liquidation value; hidden asset value
Key question: "What would this company be worth in liquidation?"
Red flags: Management that does not act in shareholder interests; accounting irregularities

---

## 8. Data Engineering & Pipelines

### When to Use
- Building ETL/ELT pipelines from financial data sources
- Designing data warehouse schemas for financial reporting
- Setting up dbt models for financial statement automation
- Implementing data quality checks on financial data
- Creating real-time data ingestion from APIs or streaming sources

### Financial Data Pipeline Architecture

```
[Data Sources]
  ├── ERP (SAP, Oracle, NetSuite) ──────────►
  ├── CRM (Salesforce) ──────────────────►
  ├── Financial APIs (Bloomberg, Refinitiv) ►  Ingestion Layer
  ├── Bank Feeds (Plaid, SWIFT) ────────►  (Airflow / Fivetran)
  └── Market Data (Yahoo, Perplexity) ────►
                                              │
                                              ▼
                                    [Raw Data Layer]
                                    (S3 / GCS / ADLS)
                                              │
                                              ▼
                                    [Transform Layer]
                                    (dbt / Spark)
                                              │
                              ┌─────────┼─────────┐
                              │              │              │
                              ▼              ▼              ▼
                      [Staging]      [Dimensional]     [Mart]
                      (Raw clean)    (Dims + Facts)    (GL, AR, AP)
                                              │
                                              ▼
                                    [Serving Layer]
                          ┌───────┼──────┼───────┐
                          ▼             ▼             ▼
                    [BI Tools]    [Finance ERP]  [ML Models]
                 (Tableau, Power BI)           (Forecasting)
```

### dbt Model Structure for Finance

```sql
-- models/staging/stg_gl_transactions.sql
-- Source: Raw GL export from ERP
SELECT
    transaction_id,
    CAST(transaction_date AS DATE) AS transaction_date,
    account_code,
    account_name,
    cost_center,
    entity,
    CAST(amount AS DECIMAL(18,2)) AS amount,
    currency,
    description,
    journal_reference,
    created_by,
    CAST(created_at AS TIMESTAMP) AS created_at
FROM {{ source('erp', 'gl_transactions') }}
WHERE transaction_date >= '2020-01-01'
  AND amount != 0

-- models/marts/finance/income_statement.sql
-- Monthly income statement by cost center
SELECT
    DATE_TRUNC('month', t.transaction_date) AS period,
    t.entity,
    t.cost_center,
    coa.statement_section,    -- Revenue / COGS / OpEx
    coa.line_item,
    SUM(t.amount) AS amount
FROM {{ ref('stg_gl_transactions') }} t
JOIN {{ ref('dim_chart_of_accounts') }} coa
    ON t.account_code = coa.account_code
WHERE coa.statement_section IN ('Revenue', 'COGS', 'Operating Expenses')
GROUP BY 1, 2, 3, 4, 5
ORDER BY 1, 2, coa.sort_order
```

### Financial Data Quality Checks

```python
# Great Expectations suite for GL data
import great_expectations as ge

# Core financial data quality tests
expectations = [
    # Every transaction must have a date
    {"expectation_type": "expect_column_values_to_not_be_null",
     "kwargs": {"column": "transaction_date"}},
    
    # Dates must be within valid range
    {"expectation_type": "expect_column_values_to_be_between",
     "kwargs": {"column": "transaction_date", 
                "min_value": "2015-01-01", "max_value": "2030-12-31"}},
    
    # Account codes must exist in chart of accounts
    {"expectation_type": "expect_column_values_to_be_in_set",
     "kwargs": {"column": "account_code", "value_set": valid_account_codes}},
    
    # No null amounts
    {"expectation_type": "expect_column_values_to_not_be_null",
     "kwargs": {"column": "amount"}},
    
    # Journal entries must balance (sum to zero per journal_id)
    # Custom expectation:
    # SELECT journal_reference, SUM(amount) FROM gl WHERE SUM(amount) != 0
    
    # No duplicate transaction IDs
    {"expectation_type": "expect_column_values_to_be_unique",
     "kwargs": {"column": "transaction_id"}}
]
```

### Airflow DAG Pattern for Month-End Close

```python
from airflow import DAG
from airflow.operators.python import PythonOperator
from datetime import datetime, timedelta

default_args = {
    'owner': 'finance-eng',
    'retries': 2,
    'retry_delay': timedelta(minutes=15),
    'email_on_failure': True,
    'email': ['finance-alerts@company.com']
}

with DAG(
    'month_end_close',
    default_args=default_args,
    schedule_interval='0 6 1 * *',  # 6 AM on first of each month
    start_date=datetime(2024, 1, 1),
    catchup=False
) as dag:
    
    extract_erp = PythonOperator(
        task_id='extract_erp_gl',
        python_callable=extract_gl_from_erp,
        op_kwargs={'period': '{{ ds[:7] }}'}
    )
    
    validate_data = PythonOperator(
        task_id='validate_gl_data',
        python_callable=run_great_expectations_suite,
        op_kwargs={'suite_name': 'gl_monthly_close'}
    )
    
    run_dbt = PythonOperator(
        task_id='run_dbt_models',
        python_callable=run_dbt_command,
        op_kwargs={'command': 'dbt run --models tag:close_reporting'}
    )
    
    generate_reports = PythonOperator(
        task_id='generate_financial_reports',
        python_callable=generate_monthly_package
    )
    
    extract_erp >> validate_data >> run_dbt >> generate_reports
```

---

## 9. Statistical Modeling & ML Forecasting

### When to Use
- Revenue forecasting with time-series models
- Anomaly detection in financial transactions
- Customer churn prediction for subscription revenue
- Risk modeling (credit, fraud, operational)
- Scenario analysis and Monte Carlo simulation

### Revenue Forecasting Models

#### Time Series: Prophet
```python
from prophet import Prophet
import pandas as pd

# Prepare data
df = revenue_data.rename(columns={'date': 'ds', 'revenue': 'y'})

# Add regressors for known events
model = Prophet(
    yearly_seasonality=True,
    weekly_seasonality=False,  # For monthly revenue data
    seasonality_mode='multiplicative',  # Better for growing revenue
    changepoint_prior_scale=0.05  # Control trend flexibility
)

# Add known business events as regressors
model.add_regressor('new_product_launch')
model.add_regressor('marketing_spend')

# Fit and forecast
model.fit(df)
future = model.make_future_dataframe(periods=12, freq='MS')  # 12 months
forecast = model.predict(future)

# Key output columns: ds, yhat, yhat_lower, yhat_upper
print(forecast[['ds', 'yhat', 'yhat_lower', 'yhat_upper']].tail(12))
```

#### Anomaly Detection: IQR + Z-Score
```python
import numpy as np
import pandas as pd

def detect_financial_anomalies(df: pd.DataFrame, column: str) -> pd.DataFrame:
    """
    Flag transactions that are statistical outliers.
    Uses both IQR (robust) and Z-score (parametric) methods.
    """
    Q1 = df[column].quantile(0.25)
    Q3 = df[column].quantile(0.75)
    IQR = Q3 - Q1
    iqr_flag = (df[column] < Q1 - 1.5 * IQR) | (df[column] > Q3 + 1.5 * IQR)
    
    z_scores = np.abs((df[column] - df[column].mean()) / df[column].std())
    z_flag = z_scores > 3
    
    df['anomaly_iqr'] = iqr_flag
    df['anomaly_zscore'] = z_flag
    df['anomaly'] = iqr_flag | z_flag
    df['z_score'] = z_scores
    
    return df

# Apply to AP transactions
ap_anomalies = detect_financial_anomalies(
    ap_df[ap_df['vendor_id'] == vendor_id],
    'invoice_amount'
)
print(f"Flagged {ap_anomalies['anomaly'].sum()} anomalous invoices")
```

#### Monte Carlo Cash Flow Simulation
```python
import numpy as np
import pandas as pd

def monte_carlo_cashflow(
    base_revenue: float,
    growth_mu: float,      # Expected annual growth rate
    growth_sigma: float,   # Standard deviation of growth
    margin: float,         # Operating margin
    margin_sigma: float,   # Margin volatility
    n_simulations: int = 10_000,
    n_years: int = 5
) -> pd.DataFrame:
    """
    Simulate future cash flows with uncertainty.
    Returns distribution of FCF outcomes.
    """
    results = []
    
    for _ in range(n_simulations):
        revenue = base_revenue
        sim_fcf = []
        
        for year in range(n_years):
            growth = np.random.normal(growth_mu, growth_sigma)
            sim_margin = np.random.normal(margin, margin_sigma)
            sim_margin = max(0, sim_margin)  # Floor at 0
            
            revenue *= (1 + growth)
            fcf = revenue * sim_margin
            sim_fcf.append(fcf)
        
        results.append(sim_fcf)
    
    df = pd.DataFrame(results, columns=[f'Year_{i+1}' for i in range(n_years)])
    
    # Summary statistics
    print("FCF Distribution (Year 5):")
    print(f"  P10: ${df['Year_5'].quantile(0.10):,.0f}")
    print(f"  P50: ${df['Year_5'].quantile(0.50):,.0f}")
    print(f"  P90: ${df['Year_5'].quantile(0.90):,.0f}")
    
    return df

# Example
results = monte_carlo_cashflow(
    base_revenue=100_000_000,
    growth_mu=0.15,      # 15% expected growth
    growth_sigma=0.08,   # 8% std dev
    margin=0.20,         # 20% FCF margin
    margin_sigma=0.05    # 5% margin volatility
)
```

---

## 10. Invoice Processing & Document Management

### When to Use
- Extracting structured data from PDF invoices
- Matching invoices to purchase orders (3-way match)
- Organizing and exporting invoice data to CSV or accounting systems
- Detecting duplicate invoices or overbilling

### Invoice Extraction Pipeline

```python
import pdfplumber
import re
import pandas as pd
from dataclasses import dataclass, field
from typing import Optional

@dataclass
class Invoice:
    vendor_name: str = ""
    invoice_number: str = ""
    invoice_date: Optional[str] = None
    due_date: Optional[str] = None
    subtotal: Optional[float] = None
    tax: Optional[float] = None
    total: Optional[float] = None
    currency: str = "USD"
    line_items: list = field(default_factory=list)
    raw_text: str = ""

def extract_invoice(pdf_path: str) -> Invoice:
    invoice = Invoice()
    
    with pdfplumber.open(pdf_path) as pdf:
        for page in pdf.pages:
            text = page.extract_text() or ""
            invoice.raw_text += text
            
            # Extract invoice number
            inv_match = re.search(r'Invoice\s*#?:?\s*([A-Z0-9\-]+)', text, re.IGNORECASE)
            if inv_match and not invoice.invoice_number:
                invoice.invoice_number = inv_match.group(1)
            
            # Extract total amount
            total_match = re.search(r'Total\s*(?:Amount)?\s*:?\s*\$?([\d,]+\.\d{2})', text, re.IGNORECASE)
            if total_match and not invoice.total:
                invoice.total = float(total_match.group(1).replace(',', ''))
            
            # Extract date
            date_match = re.search(r'(?:Invoice\s+)?Date:?\s*(\d{1,2}[/-]\d{1,2}[/-]\d{2,4})', text, re.IGNORECASE)
            if date_match and not invoice.invoice_date:
                invoice.invoice_date = date_match.group(1)
            
            # Extract table data (line items)
            tables = page.extract_tables()
            for table in tables:
                invoice.line_items.extend(table)
    
    return invoice

def invoices_to_csv(invoice_list: list, output_path: str):
    rows = []
    for inv in invoice_list:
        rows.append({
            'vendor': inv.vendor_name,
            'invoice_number': inv.invoice_number,
            'date': inv.invoice_date,
            'due_date': inv.due_date,
            'subtotal': inv.subtotal,
            'tax': inv.tax,
            'total': inv.total,
            'currency': inv.currency
        })
    pd.DataFrame(rows).to_csv(output_path, index=False)
    print(f"Exported {len(rows)} invoices to {output_path}")
```

### 3-Way Match Logic
```python
def three_way_match(
    invoice: dict,
    purchase_order: dict,
    receiving_report: dict,
    tolerance_pct: float = 0.02  # 2% tolerance
) -> dict:
    """
    Validate invoice against PO and receiving report.
    Returns match result with specific discrepancies.
    """
    result = {
        'invoice_id': invoice['invoice_number'],
        'po_number': purchase_order['po_number'],
        'passed': True,
        'discrepancies': []
    }
    
    # Price match: Invoice price vs PO price
    price_variance = abs(invoice['unit_price'] - purchase_order['unit_price'])
    price_tolerance = purchase_order['unit_price'] * tolerance_pct
    if price_variance > price_tolerance:
        result['discrepancies'].append({
            'type': 'PRICE_MISMATCH',
            'invoice': invoice['unit_price'],
            'po': purchase_order['unit_price'],
            'variance': price_variance
        })
        result['passed'] = False
    
    # Quantity match: Invoice qty vs Receiving qty
    if invoice['quantity'] != receiving_report['quantity_received']:
        result['discrepancies'].append({
            'type': 'QUANTITY_MISMATCH',
            'invoice': invoice['quantity'],
            'received': receiving_report['quantity_received']
        })
        result['passed'] = False
    
    # Amount match: Invoice total vs calculated
    expected_total = invoice['unit_price'] * invoice['quantity']
    if abs(invoice['total'] - expected_total) > 0.01:
        result['discrepancies'].append({
            'type': 'TOTAL_CALCULATION_ERROR',
            'invoice_total': invoice['total'],
            'expected_total': expected_total
        })
        result['passed'] = False
    
    return result
```

---

## 11. LLM-Assisted Financial Analysis

### When to Use
- Summarizing earnings transcripts or 10-K filings
- Extracting specific financial metrics from unstructured documents
- Generating narrative commentary from structured financial data
- Building a RAG system over financial document repositories

### RAG for Financial Documents

```python
from openai import OpenAI
import chromadb
import pdfplumber

client = OpenAI()

# Step 1: Index financial documents
def index_financial_docs(doc_paths: list[str], collection_name: str):
    chroma = chromadb.Client()
    collection = chroma.create_collection(collection_name)
    
    documents = []
    metadatas = []
    ids = []
    
    for i, path in enumerate(doc_paths):
        with pdfplumber.open(path) as pdf:
            for j, page in enumerate(pdf.pages):
                text = page.extract_text() or ""
                if len(text) > 100:  # Skip near-empty pages
                    documents.append(text)
                    metadatas.append({'source': path, 'page': j+1})
                    ids.append(f"doc_{i}_page_{j}")
    
    collection.add(documents=documents, metadatas=metadatas, ids=ids)
    return collection

# Step 2: Query with financial context
def query_financial_docs(
    question: str,
    collection,
    n_results: int = 5
) -> str:
    results = collection.query(
        query_texts=[question],
        n_results=n_results
    )
    
    context = "\n\n---\n\n".join(results['documents'][0])
    sources = [f"{m['source']}, p.{m['page']}" for m in results['metadatas'][0]]
    
    response = client.chat.completions.create(
        model="gpt-4o",
        messages=[
            {"role": "system", "content": 
             "You are a financial analyst. Answer questions based solely on "
             "the provided financial documents. Cite specific figures and sections."},
            {"role": "user", "content": 
             f"Context:\n{context}\n\nQuestion: {question}"}
        ]
    )
    
    answer = response.choices[0].message.content
    return f"{answer}\n\nSources: {'; '.join(sources)}"
```

### Narrative Generator from Financial Data

```python
def generate_variance_commentary(
    variance_data: dict,
    client: OpenAI
) -> str:
    """
    Generate professional variance commentary from structured data.
    """
    prompt = f"""
    Generate professional CFO-level commentary for this budget vs. actual variance:
    
    Period: {variance_data['period']}
    Revenue: Actual ${variance_data['actual_revenue']:,.0f} vs Budget ${variance_data['budget_revenue']:,.0f} 
             (${variance_data['revenue_variance']:+,.0f}, {variance_data['revenue_pct']:+.1f}%)
    Operating Expenses: Actual ${variance_data['actual_opex']:,.0f} vs Budget ${variance_data['budget_opex']:,.0f}
             (${variance_data['opex_variance']:+,.0f}, {variance_data['opex_pct']:+.1f}%)
    
    Key drivers provided:
    {variance_data.get('drivers', 'Not specified')}
    
    Requirements:
    - 3-4 sentences maximum
    - State what/why/so-what for each significant variance
    - Use specific dollar amounts
    - Professional finance tone
    - Do not use passive voice
    """
    
    response = client.chat.completions.create(
        model="gpt-4o-mini",
        messages=[{"role": "user", "content": prompt}]
    )
    
    return response.choices[0].message.content
```

---

## Quick Reference

### Decision Routing
```
Financial statement question → Section 1
Journal entry needed → Section 2
Reconciliation issue → Section 3
Close management → Section 4
Variance explanation → Section 5
Audit / SOX → Section 6
Market data / investment → Section 7
Data pipeline / ETL → Section 8
Forecasting / ML → Section 9
Invoice processing → Section 10
LLM on financial docs → Section 11
```

### Common Finance Formulas

```
Free Cash Flow = Operating CF − CapEx
EBITDA = Operating Income + D&A
Enterprise Value = Market Cap + Net Debt
Working Capital = Current Assets − Current Liabilities
ROIC = NOPAT / (Total Equity + Total Debt − Cash)
CAGR = (End Value / Start Value)^(1/Years) − 1
Break-even = Fixed Costs / (Price − Variable Cost per Unit)
Payback Period = Initial Investment / Annual CF
NPV = Σ CF_t / (1+r)^t − Initial Investment
IRR = Rate where NPV = 0
```

### Materiality Guidelines (GAAP)
| Context | Common Benchmark |
|---|---|
| Individual financial statement items | 5% of pre-tax income or 0.5% of revenue |
| Balance sheet items | 0.5% of total assets |
| Audit planning materiality | 0.5%–1% of revenue or 5% of pre-tax income |
| Performance materiality | 75% of planning materiality |
| Clearly trivial threshold | 3%–5% of planning materiality |

---

## Metadata

**Skill version:** 1.0
**Author:** get-zeked
**Source skills merged:**
- Perplexity Computer: finance-financial-statements, finance-journal-entry-prep, finance-reconciliation, finance-close-management, finance-variance-analysis, finance-audit-support, finance-markets, investment-research
- Claude Code (obra/superpowers): financial-analyst, senior-data-engineer, senior-data-scientist, senior-ml-engineer, invoice-organizer
**License:** MIT

---

## Appendix: Finance Abbreviations

| Abbreviation | Full Term |
|---|---|
| CAGR | Compound Annual Growth Rate |
| CAC | Customer Acquisition Cost |
| CapEx | Capital Expenditures |
| COSO | Committee of Sponsoring Organizations |
| DCF | Discounted Cash Flow |
| DPO | Days Payable Outstanding |
| DSO | Days Sales Outstanding |
| EBITDA | Earnings Before Interest, Taxes, Depreciation, and Amortization |
| ETL | Extract, Transform, Load |
| EV | Enterprise Value |
| FCF | Free Cash Flow |
| GAAP | Generally Accepted Accounting Principles |
| GL | General Ledger |
| IQR | Interquartile Range |
| IRR | Internal Rate of Return |
| LTV | Lifetime Value |
| NRR | Net Revenue Retention |
| GMV | Gross Merchandise Value |

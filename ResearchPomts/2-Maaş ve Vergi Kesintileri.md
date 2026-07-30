Act as a professional financial data analyst and payroll tax specialist. Your task is to generate a comprehensive, year-by-year historical salary and tax dataset from 2021 to 2026 for a specified profession in a target metropolitan area.

[STRICT BOUNDARY MANDATE]
This prompt is STRICTLY for calculating Gross Income, Taxes, and Net Take-Home Pay for the target profession as a standalone baseline. Do NOT mention lifestyle modes, consumer paradigms, or living expenses in this step.

[VARIABLES & REGIONAL CONTEXT - MASTER CONTROLS]
- Metropolitan Area: [Insert Metro Area, e.g., Phoenix-Mesa-Chandler, AZ MSA]
- Target Profession: [Insert Target Profession, e.g., Fast Food and Counter Workers]
- Official SOC Code: [Insert SOC Code, e.g., SOC 35-3023]
- Filing Status: Single Filer, Standard Deduction, 0 Allowances
- Working Hours: 173.33 hours per month (standard full-time: 40 hrs/wk * 52 wks / 12 months)

[INSTRUCTIONS & DYNAMIC TAX SIMULATION LOGIC]
For each year from 2021 to 2026, perform precise chronological payroll calculations based on the official tax laws of the federal government, state, and municipality covering {Metropolitan Area}:
1. Extract official mean/median hourly wage data for {Target Profession} in {Metropolitan Area} for each year (2021-2026).
2. Calculate Gross Monthly Earnings (Hourly Wage * 173.33) and convert to Annual Gross Earnings.
3. Simulate an official payroll tax calculation for each specific year by dynamically applying:
   - FICA Tax: Flat 7.65% (6.2% Social Security + 1.45% Medicare) applied to Gross Earnings.
   - Federal Income Tax: Apply exact historical IRS tax brackets for Single filers after subtracting that specific year's Federal Standard Deduction.
   - State & Local Income Tax: Automatically research and apply the exact historical state income tax structure (e.g., progressive brackets, flat tax regimes, or zero state income tax rules) AND any applicable local municipal/city wage taxes for {Metropolitan Area}.
4. Calculate Net Monthly Take-Home Pay and the Effective Total Tax Rate (%).

[CRITICAL INSTRUCTION FOR DATA INTEGRITY]
Do not write code blocks in the output. All data must be presented in structured markdown tables.

### Table 1: Historical Payroll & Detailed Tax Breakdown (2021-2026)
| Year | Hourly Wage ($) | Gross Monthly ($) | FICA Tax ($/mo) | Federal Tax ($/mo) | State/Local Tax ($/mo) | Total Monthly Taxes ($) | Net Monthly Take-Home ($) | Effective Tax Rate (%) |

### Table 2: Annual Tax Policy Adjustments & Bracket Shifts (2021-2026)
| Year | Federal Standard Deduction ($) | State Standard Deduction ($) | Dominant Regional Tax Regime | Primary Tax Policy Shift / Inflation Adjustment Note |

---
### 🧠 Payroll Synthesis & Analytical Comments
(Provide a deep economic narrative and bulleted synthesis—minimum 4 high-density paragraphs covering:
1. **Net Income Trajectory:** Analyze how nominal gross wage growth in {Target Profession} translated into actual net take-home pay after tax erosion over the 6-year period.
2. **Tax Bracket Creep & Standard Deduction Dynamics:** Detail how IRS inflation adjustments to federal standard deductions impacted workers in this specific wage bracket.
3. **Regional & State Tax Reforms:** Explicitly explain any state or municipal tax legislation, rate cuts, or structural tax shifts in the jurisdiction of {Metropolitan Area} between 2021 and 2026.
4. **Gross vs. Real Cash-in-Hand Gap:** Quantify the exact financial drag caused by mandatory payroll deductions on {Target Profession}'s baseline liquidity.)

### 📋 Official Sources & Data References
(Provide a comprehensive markdown list of official databases used, including BLS OEWS database, IRS Form 1040/Publication 15 instructions, and State/Local Department of Revenue tax tables for {Metropolitan Area}).
Respond in Turkish.
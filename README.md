# HDFC Flexi Cap Fund — ₹2,000 Monthly SIP Power BI Dashboard

Financial Analytics / Investment Analytics portfolio project built in Microsoft Power BI.

## Project

This dashboard models a **₹2,000 monthly SIP** in HDFC Flexi Cap Fund from **January 1995 to September 2026** using historical NAV data.

---

## 📊 Dashboard Pages

The Power BI dashboard contains the following 9 pages:

1. **Overview**
2. **SIP Analysis — ₹2,000 Monthly SIP**
3. **Performance**
4. **Fund Vs Benchmark**
5. **Portfolio & Holdings**
6. **Risk Analysis**
7. **Fund Manager**
8. **Historical NAV**
9. **Key Takeaways**

---

# 📸 Dashboard Screenshots

## 1. Overview

![Overview](Screenshots/01_Overview.png)

The Overview page provides a high-level view of HDFC Flexi Cap Fund and its major performance indicators.

---

## 2. SIP Analysis — ₹2,000 Monthly SIP

![SIP Analysis](Screenshots/02_SIP_Analysis.png)

The dedicated SIP Analysis page evaluates the modeled wealth creation from a ₹2,000 monthly SIP.

### SIP Summary

| Metric | Value |
|---|---:|
| Monthly SIP | ₹2,000 |
| Total Investment | ₹7.62 Lakh |
| Total SIP Units | 21.91K |
| Latest Regular Growth NAV | ₹2,041.965 |
| SIP Current Value | ₹4.47 Cr |
| SIP Profit | ₹4.40 Cr |
| SIP XIRR | 20.19% |

The SIP calculation is an analytical illustration and does not represent an actual investor account statement.

---

## 3. Performance

![Performance](Screenshots/03_Performance.png)

The Performance page presents NAV-based long-term performance measures.

- 1Y Return: **-1.45%**
- 3Y CAGR: **13.31%**
- 5Y CAGR: **16.26%**
- 10Y CAGR: **15.48%**
- Since Inception CAGR: **20.16%**

---

## 4. Fund Vs Benchmark

![Fund Vs Benchmark](Screenshots/04_Fund_Vs_Benchmark.png)

The Fund Vs Benchmark page compares the fund's performance against the selected benchmark.

---

## 5. Portfolio & Holdings

![Portfolio & Holdings](Screenshots/05_Portfolio_Holdings.png)

The Portfolio & Holdings page presents portfolio allocation and the fund's major holdings.

### Top 10 Holdings — 31 Aug 2026

| Rank | Holding | Allocation |
|---|---|---:|
| 1 | ICICI Bank Ltd. | 9.19% |
| 2 | Axis Bank Ltd. | 6.19% |
| 3 | HDFC Bank Ltd. | 5.71% |
| 4 | State Bank of India | 4.16% |
| 5 | Eternal Limited | 3.39% |
| 6 | Kotak Mahindra Bank Limited | 3.27% |
| 7 | SBI Life Insurance Company Ltd. | 3.19% |
| 8 | Larsen & Toubro Ltd. | 3.16% |
| 9 | InterGlobe Aviation Ltd. | 2.98% |
| 10 | Maruti Suzuki India Limited | 2.74% |

---

## 6. Risk Analysis

![Risk Analysis](Screenshots/06_Risk_Analysis.png)

The Risk Analysis page presents key risk and efficiency metrics.

| Metric | Value |
|---|---:|
| Beta | 0.79 |
| Standard Deviation | 12.90 |
| Sharpe Ratio | 0.82 |
| Regular Expense Ratio | 1.27% |

---

## 7. Fund Manager

![Fund Manager](Screenshots/07_Fund_Manager.png)

The Fund Manager page presents the historical fund manager timeline.

| Fund Manager | From | To |
|---|---|---|
| Amit Ganatra | 01-Feb-2026 | Present |
| Chirag Setalvad | 08-Dec-2025 | 31-Jan-2026 |
| Roshi Jain | 29-Jul-2022 | 07-Dec-2025 |
| Prashant Jain | 20-Jun-2003 | 28-Jul-2022 |

---

## 8. Historical NAV

![Historical NAV](Screenshots/08_Historical_NAV.png)

The Historical NAV page presents the annual historical NAV of HDFC Flexi Cap Fund from **1995 to 2026**.

---

## 9. Key Takeaways

![Key Takeaways](Screenshots/09_Key_Takeaways.png)

The Key Takeaways page summarizes the major insights from the fund, SIP, performance, portfolio, and risk analysis.

---

# 💰 SIP Analysis

The dedicated SIP page answers:

> If ₹2,000 were invested every month, what was invested, how many units were accumulated, and what is the modeled value?

### Investment Summary

| Metric | Value |
|---|---:|
| Monthly SIP | ₹2,000 |
| Investment Period | January 1995 – September 2026 |
| Total Investment | ₹7.62 Lakh |
| Total SIP Units | 21.91K |
| Latest Regular Growth NAV | ₹2,041.965 |
| SIP Current Value | ₹4.47 Cr |
| SIP Profit | ₹4.40 Cr |
| SIP XIRR | 20.19% |

### Methodology

**Monthly Units Purchased**

Investment ÷ NAV

**Current Modeled Value**

Total SIP Units × Latest Regular Growth NAV

**SIP XIRR**

Calculated using monthly SIP cash flows and a final valuation on **10-Sep-2026**.

> This is an analytical illustration, not an actual investor account statement. Historical results do not guarantee future returns.

---

# 📈 Performance

### NAV-Based Calculated Measures

| Period | Return |
|---|---:|
| 1 Year | -1.45% |
| 3 Years CAGR | 13.31% |
| 5 Years CAGR | 16.26% |
| 10 Years CAGR | 15.48% |
| Since Inception CAGR | 20.16% |

### Official August 2026 Performance Table

| Period | HDFC Flexi Cap |
|---|---:|
| 1 Year | 6.15% |
| 3 Years | 16.86% |
| 5 Years | 17.69% |
| 10 Years | 15.40% |
| Since Inception | 18.37% |

---

# ⚠️ Risk Metrics

| Metric | Value |
|---|---:|
| Beta | 0.79 |
| Standard Deviation | 12.90 |
| Sharpe Ratio | 0.82 |
| Regular Expense Ratio | 1.27% |

---

# 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query / M
- DAX
- Microsoft Excel / XLSX
- Financial Analytics
- Data Visualization

---

# 📂 Repository Structure

```text
HDFC-Flexi-Cap-SIP-PowerBI/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── PowerBI/
│   └── HDFC_Flexi_Cap_Fund.pbix
│
├── Data/
│   └── HDFC_Flexi_Cap_PowerBI_Data.xlsx
│
├── Documentation/
│   └── HDFC_Flexi_Cap_SIP_Power_BI_Project_Documentation.pdf
│
├── Screenshots/
│   ├── 01_Overview.png
│   ├── 02_SIP_Analysis.png
│   ├── 03_Performance.png
│   ├── 04_Fund_Vs_Benchmark.png
│   ├── 05_Portfolio_Holdings.png
│   ├── 06_Risk_Analysis.png
│   ├── 07_Fund_Manager.png
│   ├── 08_Historical_NAV.png
│   └── 09_Key_Takeaways.png
│
└── Assets/

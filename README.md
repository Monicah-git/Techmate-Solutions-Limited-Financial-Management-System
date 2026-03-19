# TechMate Solutions Limited — Financial Management System

A full-cycle bookkeeping and inventory management system built in Microsoft Excel with VBA automation, developed for a fictional computer sales company as a personal project to demonstrate practical accounting and financial management skills.

\---

## About This Project

TechMate Solutions Limited is a fictional computer sales company based in Nairobi, Kenya. I built this system to show how a small business can manage its entire financial operation in Excel — from recording daily transactions all the way through to producing final financial statements — without needing expensive accounting software.

Everything in the system is connected. When you update an invoice, it flows through to revenue. When you record an expense, it updates the P\&L and the variance analysis. The financial statements pull live data from the source sheets using cross-sheet formulas, so the numbers are always up to date.

\---

## What the System Covers

### 💼 Sales \& Revenue

* Invoice tracker — all invoices with amounts, dates, VAT, and payment status
* Credit note tracker — returns and adjustments
* Printable invoice template

### 🛒 Purchasing

* Purchase order tracker with supplier details and payment status
* Purchases receiving template
* Supplier database

### 📦 Inventory

* Stock register for 30+ laptop models across budget, mid-range, and premium categories
* Stock in and stock out logs
* Automatic closing stock calculation and reorder alerts
* Closing stock valuation linked to selling prices

### 🏦 Banking

* Full bank statement log — January to March 2024
* All transactions recorded with debit, credit, bank charges, and running balance
* Colour-coded by transaction type (sales, expenses, VAT, purchases)

### 👥 Payroll

* Employee payroll register for 5 staff members
* Kenyan statutory deductions calculated by formula: NSSF, SHIF (2.75%), Housing Levy, PAYE
* Monthly net salary totals feeding into the financial statements

### 📒 Accounting Records

* Journal entries — full double-entry records sorted chronologically with debit and credit columns
* Chart of accounts with opening balances and classifications
* Expense log categorised by type (rent, marketing, transport, payroll, loan repayments, etc.)

### 📊 Financial Statements

* **Trial Balance** — as at 31 March 2024, with SUMIF formulas pulling from journal entries
* **Profit \& Loss Statement** — revenue, COGS, operating expenses, tax, and net profit
* **Balance Sheet** — assets, liabilities, and equity as at 31 March 2024
* **Cash Flow Statement** — operating, investing, and financing activities (indirect method)

### 📈 Budget \& Variance Analysis

* Monthly budget plan for Q1 2024
* Variance analysis comparing budget vs actual for every line item
* Actuals pulled live from source sheets using SUMPRODUCT and SUMIFS formulas
* Colour-coded variances: green = favourable, red = adverse

\---

## ⚙️ How to Open and Use It

1. Download the file: `Techmate\_Variance\_Final.xlsm`
2. Open it in **Microsoft Excel** — do not open in Google Sheets as VBA will not run
3. When Excel prompts you, click **Enable Macros**
4. The workbook will load with a welcome screen
5. Use the **Table of Contents** sheet to navigate to any section

> \*\*Note:\*\* Macros must be enabled for the navigation and automation features to work. The VBA code only handles navigation, sheet protection, and the welcome screen — it does not connect to the internet or access any external data.

\---

## 🛠️ Tools Used

* Microsoft Excel (.xlsm — macro-enabled workbook)
* VBA (Visual Basic for Applications) — for automation and navigation
* Formulas used: SUMIF, SUMIFS, SUMPRODUCT, VLOOKUP, IF, ROUND, SUM, and cross-sheet references

\---

## 📁 Workbook Structure

|Sheet|Purpose|
|-|-|
|Table of Contents|Navigation hub with links to all sheets|
|Overview|Live dashboard — stock and financial summary|
|Inventory|Full stock register with valuations|
|Bank Statement|All transactions Jan–Mar 2024|
|Loan Amortization|Loan repayment schedule|
|Invoice Template|Printable sales invoice|
|Invoice Tracker|All invoices and payment status|
|Stock Out|Goods dispatched log|
|Customer Database|Customer contacts and records|
|Suppliers Database|Supplier contacts and records|
|Purchases Receiving Template|Goods received template|
|Purchase Tracker|All purchase orders and status|
|Credit Note Template|Printable credit note|
|Credit Note Tracker|All credit notes issued|
|Stock In|Goods received log|
|Chart of Accounts Index|Quick account reference|
|Chart of Accounts|Full chart with balances|
|The Trial Balance|As at 31 March 2024|
|Journal Entries|Full double-entry records|
|Expense|Categorised expense log|
|Profit and Loss Statement|Jan–Mar 2024|
|Balance Sheet|As at 31 March 2024|
|Payroll|Employee payroll register|
|Payroll Tracker|Monthly payroll history|
|Payslip|Individual payslip template|
|Cash Flow Statements|Jan–Mar 2024|
|Budget|Q1 2024 monthly budget plan|
|Variance Analysis|Budget vs actual with live formulas|

\---

## 👩‍💼 Built By

**Monicah Mburu**    
Nairobi, Kenya  
monicah.mburu@zohomail.com  
[LinkedIn](http://linkedin.com/in/monicah-mburu-wambui)


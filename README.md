# RFQ & Supplier Quotation Evaluation System

An Excel-based procurement tool designed to organize purchase requisitions, track Requests for Quotation (RFQs), compare supplier quotations, evaluate supplier performance, and support structured sourcing decisions.

## Project Overview

This project demonstrates how Microsoft Excel can support the procurement quotation evaluation process, from recording purchase requests and supplier responses to comparing total costs, reviewing compliance, scoring suppliers, and preparing award recommendations.

The workbook includes automated calculations, dropdown lists, evaluation criteria, supplier compliance checks, and a dashboard summarizing key procurement indicators.

All supplier names, quotations, prices, and transactions are fictional sample data created for demonstration purposes.

## Dashboard

The dashboard provides a high-level overview of RFQs tracked, quotations received, compliant quotations, and approved requisitions. It also summarizes quotation counts, lowest compliant costs, recommended suppliers, and evaluation status for selected purchase requisitions.

![RFQ and Supplier Quotation Evaluation Dashboard](screenshots/dashboard-sheet.png)

## Quotation Comparison

The Quotation Comparison worksheet brings supplier offers together for a like-for-like review. It includes quoted unit prices, quantities, discounts, shipping charges, VAT rates, total quoted costs, lead times, payment terms, warranty periods, specification compliance, quotation validity, price rankings, and evaluation status.

Total quoted cost incorporates the listed quantity, discount, shipping, and VAT assumptions. The worksheet also distinguishes eligible quotations from non-compliant or pending-review offers.

![Quotation Comparison - Cost and Commercial Details](screenshots/quotation-comparison-sheet1.png)
![Quotation Comparison - Compliance and Evaluation Status](screenshots/quotation-comparison-sheet2.png)

## Supplier Evaluation

The Supplier Evaluation worksheet compares suppliers using price, lead time, quality, and payment-term scores. The illustrative weighted scoring model uses the following criteria:

| Evaluation Criterion | Weight |
|---|---:|
| Price Score | 30% |
| Lead Time Score | 25% |
| Quality Score | 25% |
| Payment Terms Score | 20% |
| **Total** | **100%** |

The worksheet includes a compliance gate and recommendation status. Compliance is a mandatory consideration: a high weighted score must not override a non-compliant offer.

![Supplier Evaluation and Weighted Scoring](screenshots/supplier-evaluation-sheet.png)

## Workbook Structure

The workbook contains eight worksheets:

| Worksheet | Purpose |
|---|---|
| Dashboard | Summarizes procurement KPIs and selected requisition-level results. |
| Purchase Requisitions | Records purchase requests, item or service details, and request statuses. |
| RFQ Register | Tracks RFQ records, supplier invitations, and quotation responses. |
| Quotation Comparison | Compares supplier quotations, calculates total costs, and records commercial terms, compliance, validity, rankings, and evaluation status. |
| Supplier Evaluation | Applies weighted supplier scoring and compliance checks to support supplier assessment. |
| Award Recommendation | Summarizes recommended suppliers, quoted costs, lowest compliant costs, potential cost differences, and recommendation rationale. |
| Lists | Holds reference values used for dropdown lists and data validation. |
| Read Me | Provides workbook usage guidance. |

## Key Features

- Purchase requisition and RFQ tracking.
- Supplier quotation comparison.
- Total cost calculations incorporating discounts, shipping, and VAT.
- Comparison of delivery lead times, payment terms, and warranty periods.
- Specification compliance and quotation validity checks.
- Price ranking and evaluation status tracking.
- Weighted supplier evaluation using defined scoring criteria.
- Compliance-gate checks to identify non-compliant offers.
- Award recommendation summary and potential cost-difference analysis.
- Dashboard KPIs and requisition-level reporting.
- Excel formulas, structured tables, dropdown lists, and data validation.

## Tools and Skills

- Microsoft Excel 2019
- Procurement and RFQ Management
- Supplier Quotation Analysis
- Total Cost of Ownership Analysis
- Supplier Evaluation and Compliance Review
- Procurement Documentation
- Weighted Scoring Models
- KPI Reporting and Dashboard Design
- Excel Formulas and Data Validation

## How to Use

1. Download the Excel workbook from this repository.
2. Open it in Microsoft Excel 2019 or a compatible version.
3. Review the Read Me worksheet before entering or modifying data.
4. Review purchase requisitions and update request information and statuses as needed.
5. Track supplier invitations and responses in the RFQ Register.
6. Enter or update supplier offers in Quotation Comparison.
7. Review total costs, quotation validity, specification compliance, and evaluation status.
8. Review Supplier Evaluation and Award Recommendation before making a sourcing decision.
9. Verify calculations, scoring weights, and approval requirements before using the workbook with operational procurement data.

## Important Considerations

- All sample records are fictional and do not represent actual commercial transactions.
- VAT treatment, quotation validity, scoring weights, supplier qualification requirements, and approval procedures may vary by organization.
- Weighted scores are decision-support indicators and should not replace procurement policies, due diligence, or authorized approvals.
- Award recommendations require review of technical compliance, commercial terms, business requirements, and applicable approval procedures.
- Test formulas and data-validation rules with representative records before using the workbook in a live procurement process.

## Repository Contents

- `README.md` — project documentation.
- `RFQ_Supplier_Quotation_Evaluation_System.xlsx` — Excel procurement evaluation workbook.
- `screenshots/dashboard.png` — dashboard screenshot.
- `screenshots/quotation-comparison-1.png` — quotation comparison screenshot, first section.
- `screenshots/quotation-comparison-2.png` — quotation comparison screenshot, second section.
- `screenshots/supplier-evaluation.png` — supplier evaluation screenshot.

## Disclaimer

This is an independent portfolio project created for demonstration and learning purposes. It is not affiliated with any supplier or organization. All sample data is fictional, and the workbook does not constitute an approved procurement award or a substitute for an organization's procurement policies.

# Data Dictionary - Credit Risk & Loan Performance Dataset

## Overview
Dataset containing 124,549 loan records with performance tracking and risk classification attributes.

**Target Variable:** Status (0 = Good Loan, 1 = Default/Bad Loan)

---

## Dataset Structure

**Total Records:** 124,549 loans  
**Features:** 16 attributes  
**Default Rate:** 16% (20,329 defaults)

---

## Core Data Fields

| Field Name | Data Type | Description | Values/Range |
|------------|-----------|-------------|--------------|
| **ID** | Integer | Unique loan identifier | 1 - 124,549 |
| **loan_amount** | Currency | Loan principal | $500 - $500,000+ |
| **term** | Integer | Loan term in months | 36, 60, 120, 180, 240, 360 |
| **income** | Currency | Annual income | $1,000 - $100,000+ |
| **Credit_Score** | Integer | Credit score | 500 - 850 |
| **Status** | Binary | Performance | 0=Good, 1=Default |
| **dtir1** | Decimal | Debt-to-Income Ratio | 0.00 - 1.00 |

## Calculated Fields

| Field | Description | Categories |
|-------|-------------|------------|
| **dbtr_status** | DTI category | Low/Medium/High |
| **Risk_Band** | Risk classification | Low/Medium/High Risk |
| **Creditscore_Status** | Credit band | Poor/Fair/Good |
| **loam_amount_band** | Loan size | Small/Medium/Large |
| **Loan_Tenure** | Term category | Short/Medium/Long |

---

## Business Rules

**DTI Bands:**
- Low: < 36%
- Medium: 36-43%
- High: > 43%

**Loan Amount Bands:**
- Small: < $100K
- Medium: $100K-$300K
- Large: > $300K

**Credit Score Bands:**
- Poor: < 580
- Fair: 580-669
- Good: 670+

---

*For complete analysis, see README.md*

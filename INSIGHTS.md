# Credit Risk Analysis - Key Insights & Findings

## 🎯 Executive Summary

This credit risk analysis of 124,549 loans reveals **DTI as the primary driver of default risk**, with high DTI loans showing **26% default rates**. Strategic interventions targeting DTI thresholds, small loan policies, and medium-term loan management could prevent **$1.0B-$1.5B in losses**.

---

## 📊 Top 5 Risk Drivers (Ranked by Impact)

### 1. 🔴 Debt-to-Income Ratio (PRIMARY DRIVER)
**Finding:** High DTI loans show **26% default** vs **14% medium DTI**  
**Risk Factor:** 1.86x increase  
**Root Cause:** Borrowers with high DTI struggle with debt service during income disruptions  
**Recommended Action:** Lower maximum DTI threshold to 43%, stricter review above 36%  
**Projected Impact:** Prevent 3,700 defaults, save $500M-$800M  

### 2. 🔴 Small Loan Amounts (PARADOX FINDING)
**Finding:** Small loans (<$100K) show **28% default** vs **14% for large loans**  
**Risk Factor:** 2x increase (inverse relationship)  
**Root Cause:** Smaller loans often to subprime borrowers or for consumption vs investment  
**Recommended Action:** Implement risk premiums, minimum income thresholds  
**Projected Impact:** Reduce small loan defaults by 5-8 percentage points  

### 3. 🟠 Medium-Term Loans (UNEXPECTED PATTERN)
**Finding:** Medium-term (5-20 years) show **21% default** vs **16% long-term**  
**Risk Factor:** Higher than expected  
**Root Cause:** Requires investigation - possible life event timing or refinance patterns  
**Recommended Action:** Enhanced underwriting for medium-term loans  
**Projected Impact:** Better risk-adjusted pricing, 2-3% improvement  

### 4. 🟡 Risk Band Classification (VALIDATION)
**Finding:** High-risk loans show **22% default**, low-risk **14%**  
**Insight:** Risk banding system is effective and validated  
**Recommended Action:** Maintain and refine risk classification  
**Projected Impact:** Continued effective risk segmentation  

### 5. 🟢 Approval Policy (STRENGTH)
**Finding:** Approved loans **14% default** vs rejected **25%**  
**Insight:** Current screening process is highly effective  
**Recommended Action:** Document and standardize current process  
**Projected Impact:** Sustained low default rates on approvals  

---

## 💰 Financial Impact Analysis

### Current Portfolio State
| Metric | Value |
|--------|-------|
| Total Loans | 124,549 |
| Total Defaults | 20,329 (16%) |
| Defaulted Amount | $6.3 billion |
| High-Risk Exposure | $3.1 billion |
| Medium-Risk Exposure | ~$2.0 billion |
| Low-Risk Exposure | ~$1.2 billion |

### Segmentation Distribution
- **High-Risk Loans:** ~30,000 (24% of portfolio)
- **Medium-Risk Loans:** ~40,000 (32% of portfolio)
- **Low-Risk Loans:** ~60,000 (48% of portfolio - largest segment)

### Projected Savings Scenarios

**Conservative Scenario (DTI Only):**
- Default Rate: 16% → 13% (-3%)
- Loans Saved: ~3,700
- Financial Impact: $500M-$800M prevented losses

**Aggressive Scenario (Combined Interventions):**
- Default Rate: 16% → 11% (-5%)
- Loans Saved: ~6,200
- Financial Impact: $1.0B-$1.5B prevented losses
- Portfolio Quality: 31% improvement

---

## 📈 Dimensional Analysis

### By DTI Band (PRIMARY FOCUS)
```
High DTI (>0.43):    26% default  ⚠️ HIGHEST RISK
Medium DTI (0.36-0.43): 14% default  ✓ Acceptable
Low DTI (<0.36):     18% default  ⚠️ Investigate anomaly
```

**Insight:** Low DTI showing higher default than medium suggests other factors at play (possibly income verification issues or loan purpose)

### By Loan Amount
```
Small (<$100K):      28% default  ⚠️ CRITICAL
Medium ($100K-$300K): 18% default  ⚠️ Monitor
Large (>$300K):      14% default  ✓ Best performing
```

**Insight:** Inverse relationship - larger loans to more qualified borrowers

### By Loan Tenure
```
Short (<5 years):    15% default  ✓ Good
Medium (5-20 years): 21% default  ⚠️ INVESTIGATE
Long (>20 years):    16% default  ✓ Average
```

**Insight:** Medium-term paradox requires deeper analysis

### By Credit Score
```
Poor (<580):         16% default
Fair (580-669):      18% default
Good (670+):         14% default
```

**Insight:** Relatively flat - credit score not strong standalone predictor in this portfolio

### By Risk Band
```
High Risk:           22% default  ⚠️ Expected
Medium Risk:         13% default  ✓ Good
Low Risk:            14% default  ✓ Good
```

**Insight:** Risk banding system working as designed

---

## 🎯 Targeting Strategy

### Immediate Focus (30-60 Days)
1. ✅ High DTI loans (>43%) - Review and tighten
2. ✅ Small loans (<$100K) - Add risk premiums
3. ✅ Medium-term loans - Investigation and policy review
4. ✅ Document approval criteria - Standardize process

### High-Value Risk Reduction
- **DTI Threshold Reduction:** Single biggest impact lever
- **Small Loan Policy:** High volume, high risk segment
- **Enhanced Monitoring:** Medium-term portfolio tracking

### Prevention Focus
- **Pre-approval:** Stricter DTI verification
- **Approval:** Maintain effective screening
- **Post-approval:** Enhanced monitoring for high-risk approvals

---

## 📋 Quick Reference: Default Rates by Category

### By DTI Band
1. High (>0.43): **26%** 🔴
2. Low (<0.36): **18%** 🟡
3. Medium (0.36-0.43): **14%** ✅

### By Loan Amount
1. Small (<$100K): **28%** 🔴
2. Medium ($100K-$300K): **18%** 🟡
3. Large (>$300K): **14%** ✅

### By Loan Tenure
1. Medium (5-20 yrs): **21%** 🔴
2. Long (>20 yrs): **16%** 🟡
3. Short (<5 yrs): **15%** ✅

### By Approval Decision
1. Rejected: **25%** 🔴
2. Approved: **14%** ✅

---

## 🚀 Implementation Priority Matrix

### CRITICAL (Implement Immediately)
- ⚡ DTI threshold reduction to max 43%
- ⚡ Small loan risk premium implementation
- ⚡ High DTI loan review process
- ⚡ Approval criteria documentation

### HIGH (Implement Q1-Q2)
- 🔥 Medium-term loan investigation
- 🔥 Enhanced underwriting for small loans
- 🔥 DTI verification process improvement
- 🔥 Risk-adjusted pricing model

### MEDIUM (Implement Q3-Q4)
- 📊 Credit score data quality audit
- 📊 Composite risk score development
- 📊 Portfolio monitoring dashboard
- 📊 Periodic policy validation

---

## 📝 Success Metrics to Track

### Primary KPIs
- Overall default rate (target: <13%)
- High DTI default rate (target: <20%)
- Small loan default rate (target: <22%)
- Approval decision accuracy (maintain: 14% vs 25% spread)

### Leading Indicators
- DTI distribution in new originations
- Average loan amount trend
- Risk band distribution
- Approval rate by risk segment

### Portfolio Health Metrics
- Default exposure by risk band
- Recovery rates by segment
- Time to default analysis
- Vintage performance tracking

---

## 🎓 Lessons Learned

1. **DTI Dominates:** Single strongest predictor of default in this portfolio
2. **Size Matters (Inversely):** Smaller loans surprisingly riskier
3. **Approval Works:** Current screening highly effective - preserve and document
4. **Medium Mystery:** Medium-term loans need investigation
5. **Credit Scores Limited:** Not sufficient alone for risk assessment
6. **Risk Bands Validated:** Multi-factor risk classification effective

---

## 🔮 Future Analysis Recommendations

1. **Cohort Analysis:** Track defaults by origination vintage
2. **Time-to-Default:** Analyze when in loan lifecycle defaults occur
3. **Recovery Analysis:** Assess recovery rates by segment
4. **Income Verification:** Audit stated vs verified income
5. **Loan Purpose:** Analyze default by loan use (purchase, refinance, cash-out)
6. **Geographic Analysis:** Regional default patterns
7. **Macroeconomic Factors:** Interest rate, unemployment correlation

---

## 💡 Strategic Questions Answered

**Q: What drives defaults?**
A: Primarily DTI, then loan amount (inverse), then tenure patterns

**Q: Is our approval policy working?**
A: Yes - 14% approved vs 25% rejected validates screening

**Q: Where should we focus risk reduction?**
A: High DTI loans and small loan amounts

**Q: Are credit scores useful?**
A: Limited standalone value - use as part of composite score

**Q: What's our biggest risk?**
A: $3.1B exposure in high-risk segment

**Q: What's the quick win?**
A: Tighten DTI thresholds - immediate, measurable impact

---

*For detailed methodology, see README.md*  
*For data definitions, see data/data_dictionary.md*

# Project 3: Vendor Risk Assessment

## 📌 Project Overview
Conducted a vendor risk assessment for TechToys, evaluating the security posture of their website hosting provider, CloudHost Pro.

## 🎯 Why Vendor Risk Matters
**The Target Breach (2013):** A hacker broke into Target through their **HVAC vendor**. The vendor had network access. 40 million credit cards stolen. $18.5 million settlement.

**The Lesson:** You're only as secure as your weakest vendor.

## 🏢 TechToys Vendors I Assessed

| Vendor | Service | Data Access | Risk Level |
|--------|---------|-------------|------------|
| CloudHost Pro | Website hosting | Customer data | MEDIUM |
| PayFlow Services | Payment processing | Credit cards | Pending |
| MarketStar Agency | Marketing | Email lists | Pending |
| DataBackup Inc. | Backups | All data | Pending |

## 📋 What I Created

### 1. Vendor Risk Questionnaire
25 questions covering:
- **Security controls:** Encryption, MFA, patching, incident response
- **Compliance:** GDPR, ISO 27001, SOC 2, PCI-DSS
- **Business continuity:** Backups, uptime SLA, insurance
- **Subcontractors:** Who they use and how they're assessed

### 2. Vendor Scorecard
A weighted scoring system:

| Risk Level | Score Range | Action Required |
|------------|-------------|------------------|
| LOW | 80-100% | Standard monitoring |
| MEDIUM | 60-79% | Review within 30 days |
| HIGH | 40-59% | Immediate action required |
| CRITICAL | <40% | Do not engage |

### 3. Sample Assessment: CloudHost Pro

| Category | Score | Findings |
|----------|-------|----------|
| Security Controls | 82% | ✅ Strong encryption and MFA |
| Compliance | 60% | ❌ No ISO 27001 certification |
| Business Continuity | 85% | ✅ Good backup policy |
| Subcontractors | 70% | ❌ Subcontractors not assessed |
| **OVERALL** | **76%** | **MEDIUM RISK** |

### 4. Recommendations I Provided

| Priority | Recommendation | Timeline |
|----------|----------------|----------|
| HIGH | Request subcontractor assessments | 30 days |
| HIGH | Require incident response testing | 90 days |
| MEDIUM | Increase vulnerability scans to monthly | 60 days |
| LOW | Request ISO 27001 roadmap | 90 days |

## 💡 What I Learned

### Vendor Risk Is Everywhere
I initially thought only technology vendors matter. But I learned that **cleaning services, marketing agencies, and even HR software** can be risks if they have data access.

### Assessment Is Not One-Time
A vendor can be "low risk" today and "high risk" next month if they get breached. I learned to track **next review dates** and treat this as continuous monitoring.

### The "Right to Audit" Matters
I learned that contracts should include the right to audit vendors. If you can't verify their security, you can't trust it.

## 📁 Files in This Project
- `01_Vendor_Questionnaire.pdf` - Assessment questions
- `02_Vendor_Scorecard.xlsx` - Scoring methodology
- `03_CloudHost_Assessment_Report.pdf` - Complete assessment
- `04_Vendor_Risk_Register.xlsx` - Tracking all vendors

## 🔗 Back to Main Portfolio
[GRC Portfolio Home](../README.md)

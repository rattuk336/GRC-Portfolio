# Project 2: Data Classification Policy

## 📌 Project Overview
Created a comprehensive Data Classification Policy for TechToys to establish clear guidelines for handling sensitive information.

## 🎯 Objective
Demonstrate the ability to:
- Define data classification levels
- Create practical handling requirements
- Align with regulations (GDPR, PCI-DSS)
- Write clear, enforceable policies

## 📋 The 4 Classification Levels

| Level | Color | Description | TechToys Example |
|-------|-------|-------------|------------------|
| **PUBLIC** | 🟢 Green | Safe for public disclosure | Product catalogs, job postings |
| **INTERNAL** | 🔵 Blue | Employee-only information | Employee directory, training materials |
| **CONFIDENTIAL** | 🟠 Orange | Could cause moderate harm | Customer names/addresses, employee salaries |
| **RESTRICTED** | 🔴 Red | Could cause severe harm/legal penalties | Credit card numbers, passwords, trade secrets |

## 🔒 Handling Requirements Quick Reference

| Action | PUBLIC | INTERNAL | CONFIDENTIAL | RESTRICTED |
|--------|--------|----------|--------------|------------|
| Share externally | ✅ YES | ❌ NO | ❌ NO | ❌ NO |
| Send via email | ✅ YES | ✅ YES | ⚠️ Encrypted | ❌ NO |
| Store on laptop | ✅ YES | ✅ YES | ⚠️ Encrypted | ❌ NO |
| Shred after use | ❌ NO | ✅ YES | ✅ YES | ✅ YES |

## 📝 Policy Sections I Included
1. **Purpose** - Why this policy exists
2. **Scope** - Who and what it applies to
3. **Classification Levels** - Definitions and examples
4. **Handling Requirements** - What employees can/can't do
5. **Labeling Requirements** - How to mark documents
6. **Roles & Responsibilities** - Who does what
7. **Compliance & Violations** - What happens if rules are broken

## 💡 What I Learned

### The "So What" Lesson
A policy is useless if employees don't understand it. I learned to include **real examples** (like "credit card numbers = RESTRICTED") so employees can easily classify their own data.

### Compliance Requirements Are Specific
I learned that different regulations require different protections:
- **PCI-DSS** (credit cards) requires encryption
- **GDPR** (EU customer data) requires data subject rights

### Balance is Everything
If the policy is too strict, employees will ignore it. If it's too loose, data gets leaked. Finding the right balance is the real skill.

## 📁 Files in This Project
- `KaranRattu_DataClassificationPolicy.docx` - Editable policy
- `KaranRattu_DataClassificationPolicy.pdf` - Portfolio-ready version

## 🔗 Back to Main Portfolio
[GRC Portfolio Home](../README.md)

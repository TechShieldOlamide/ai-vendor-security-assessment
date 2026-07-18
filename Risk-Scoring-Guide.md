# AI Vendor Risk Scoring Guide

**Purpose:** A simple, consistent scoring model to rate AI vendors by risk tier after completing the assessment questionnaire.
**Prepared by:** TrustGrid Technology

---

## Why Score Vendors

Not every AI tool carries the same risk. A grammar-checking tool that processes no sensitive data is a very different risk than an AI-driven credit scoring system. A consistent scoring model helps you prioritise which vendors need deeper scrutiny, ongoing monitoring, or should not be approved at all.

---

## Scoring Categories

Rate each vendor from 0 to 3 on each category below, based on the questionnaire responses.

| Category | 0 (No Risk Indicators) | 1 (Low Risk) | 2 (Moderate Risk) | 3 (High Risk) |
|---|---|---|---|---|
| Data Sensitivity | No personal or sensitive data processed | Limited personal data, no special category data | Personal data including some sensitive fields | Special category data (health, biometric, financial, children's data) |
| Training Data Use | Vendor confirms no training on customer data, in writing | Training use unclear or not addressed in contract | Training occurs but customer can opt out | Training occurs by default with no opt-out available |
| Decision Impact | Tool provides suggestions only, no decisions made | Tool influences minor, low-stakes decisions | Tool influences decisions with moderate impact | Tool makes or heavily influences decisions with legal or significant effects on individuals |
| Human Oversight | Full human review of all outputs before action | Human review for high-stakes cases only | Limited or inconsistent human review | No meaningful human review of automated outputs |
| Vendor Transparency | Vendor provided clear, complete, written answers to all questions | Vendor provided mostly complete answers | Vendor answers were vague or incomplete on some items | Vendor was evasive or refused to answer key questions |
| Certifications | Vendor holds relevant certifications (SOC 2, ISO 27001, ISO 42001) | Vendor has some security documentation but no formal certification | Vendor has minimal security documentation | Vendor has no security documentation or certification |

---

## Calculating the Risk Score

Add the scores across all six categories. Maximum possible score: 18.

| Total Score | Risk Tier | Recommended Action |
|---|---|---|
| 0-4 | Low Risk | Standard approval process, periodic review annually |
| 5-9 | Moderate Risk | Approval requires compliance sign-off, review every 6 months |
| 10-14 | High Risk | Requires senior leadership and legal review before approval, quarterly monitoring |
| 15-18 | Critical Risk | Do not approve without significant additional safeguards; consider alternative vendors |

---

## Example Scoring

**Example 1: AI writing assistant for internal marketing drafts**
- Data Sensitivity: 0 (no personal data used)
- Training Data Use: 1 (opt-out available)
- Decision Impact: 0 (no decisions made)
- Human Oversight: 0 (all output reviewed before publishing)
- Vendor Transparency: 0 (clear documentation provided)
- Certifications: 0 (SOC 2 certified)
- **Total: 1 — Low Risk**

**Example 2: AI-driven credit scoring tool for loan applications**
- Data Sensitivity: 3 (financial data, special category adjacent)
- Training Data Use: 2 (training occurs, opt-out available)
- Decision Impact: 3 (significantly affects loan approval)
- Human Oversight: 2 (limited review of borderline cases only)
- Vendor Transparency: 1 (mostly complete answers)
- Certifications: 1 (some documentation, no formal certification)
- **Total: 12 — High Risk, requires senior leadership and legal review**

---

## Ongoing Monitoring

Risk scores are not one-time assessments. Rescore vendors:

- When the vendor changes their terms of service or data policy
- When the use case for the tool expands beyond its original scope
- At the review interval defined by the risk tier
- Following any security incident involving the vendor, even if unrelated to your specific use

---

*Built by TrustGrid Technology. Reference scoring guide only. Not legal advice. Adapt scoring weights to reflect your organisation's specific risk tolerance and regulatory obligations.*

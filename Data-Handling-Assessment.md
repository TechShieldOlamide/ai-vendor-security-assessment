# Data Handling Assessment for AI Tools

**Purpose:** A deeper assessment framework for understanding exactly how an AI vendor handles your data, beyond the initial questionnaire.
**Prepared by:** TrustGrid Technology

---

## Why This Matters

Most AI vendors will answer basic security questions confidently. Fewer can answer specific questions about data flow with precision. This document helps you go deeper than a standard questionnaire and actually trace where your data goes once it enters an AI system.

---

## Mapping the Data Journey

For each AI tool being assessed, trace the full path data takes:

| Stage | Questions to Answer |
|---|---|
| Input | What data enters the system? Is it the full record or a minimised subset? |
| Processing | Where is processing performed? Which specific model or service handles it? |
| Storage | Is the input stored after processing? For how long? Where? |
| Output | What does the system return? Does the output itself contain or reveal sensitive input data? |
| Logging | Are inputs and outputs logged? Who can access those logs? |
| Deletion | What triggers deletion? Is deletion verifiable? |

---

## Data Minimisation Checklist

| # | Item | Status |
|---|---|---|
| 1 | Only the minimum necessary data is sent to the AI tool for the specific task | |
| 2 | Personal identifiers are stripped or pseudonymised where the task does not require them | |
| 3 | Special category data (health, biometric, financial) is never sent unless explicitly justified and assessed | |
| 4 | Staff have been trained not to paste unnecessary sensitive data into AI tools | |
| 5 | Technical controls exist to prevent bulk data exports being sent to unauthorised AI tools | |

---

## Special Category Data and AI

Special category data (health records, biometric data, financial details, information about children) requires heightened scrutiny before it touches any AI system.

**Before sending special category data to an AI tool, confirm:**

- Is there a specific, documented, lawful basis for this specific processing?
- Has a Data Protection Impact Assessment been completed for this specific use case?
- Does the vendor have specific safeguards for special category data, not just general security measures?
- Is there a less AI-dependent way to achieve the same outcome that carries lower risk?

---

## Shadow AI Risk

A significant and growing risk category: staff independently adopting AI tools without organisational approval, often called Shadow AI.

**Signs of Shadow AI in your organisation:**

- Staff mention using AI tools that were never procured or approved
- No central inventory exists of AI tools in use across departments
- Customer service, HR, or finance teams have independently started using free AI tools for daily tasks
- Nobody in IT or compliance can confidently list every AI tool touching company data

**Addressing Shadow AI:**

| Action | Description |
|---|---|
| Build an AI inventory | Survey departments directly, do not rely on IT records alone, since most Shadow AI adoption bypasses procurement |
| Provide sanctioned alternatives | Staff often adopt Shadow AI because approved tools are slow to procure or don't exist; offering a vetted option reduces the incentive |
| Clear usage policy | A simple, accessible policy on what data can and cannot be pasted into AI tools |
| Amnesty period | When first addressing Shadow AI, consider a grace period for staff to disclose tools in use without penalty, to get an honest inventory |

---

*Built by TrustGrid Technology. Reference document only. Not legal advice. Special category data handling should always be reviewed with qualified legal counsel.*

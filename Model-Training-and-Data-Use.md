# Model Training and Data Use

**Purpose:** Understanding whether and how your data is used to train AI models, and why this matters more than most businesses realise.
**Prepared by:** TrustGrid Technology

---

## Why This Is Different From Standard Data Storage

Most data protection thinking is built around storage and access: where is the data, who can see it, how is it protected. AI model training introduces a different risk entirely: your data can become permanently embedded in a model's learned patterns, in ways that are difficult or impossible to fully reverse, even if the original data is later deleted.

---

## Key Questions to Understand

| Question | Why It Matters |
|---|---|
| Is our data used to train the vendor's models at all? | If yes, deleting the original data does not necessarily remove its influence from an already-trained model |
| Is training opt-in, opt-out, or not offered as a choice? | Determines what control you actually have |
| Does the vendor train a shared model across all customers, or a dedicated model for us? | Shared models raise higher risk of data influencing outputs seen by other customers |
| Can training on our data be disabled at the account or contract level? | Many enterprise AI contracts allow this; consumer-tier plans often do not |
| What is the vendor's data retention policy for training data specifically, separate from their general data retention policy? | Training data pipelines sometimes have different retention rules than customer-facing storage |

---

## The Consumer vs Enterprise Tier Problem

A common and costly mistake: an organisation signs up for a consumer-tier AI subscription because it is cheap and fast to procure, without realising that consumer tiers frequently allow data to be used for model training by default, while enterprise tiers of the same product often do not.

**Before adopting any AI tool, confirm:**

- Which tier or plan is being used
- Whether the specific tier's terms of service address training data use explicitly
- Whether upgrading to an enterprise or business tier changes the training data policy

---

## Sample Contract Language to Look For

When reviewing a vendor's terms of service or data processing agreement, look for specific commitments such as:

- "Customer data will not be used to train, retrain, or improve [Vendor]'s models without explicit written consent"
- "Customer may opt out of model training data usage without affecting service functionality"
- "Data submitted through the API is not used for training purposes"

**Red flag language to watch for:**

- Vague statements like "we may use data to improve our services" without specifying whether this includes model training
- No mention of training data use at all, which does not mean it isn't happening, it may simply not be addressed

---

## Practical Recommendation

For any AI tool processing customer or sensitive business data, obtain written confirmation, not just a verbal assurance, of the vendor's training data policy. This becomes essential evidence if you are ever asked, by a regulator, a customer, or your own board, to demonstrate that you understood and controlled how your data was used inside a third-party AI system.

---

*Built by TrustGrid Technology. Reference document only. Not legal advice. Always review actual vendor contract terms, as verbal representations may not match binding legal terms.*

# Renewal and Expansion

**For:** account managers and customer success managers on renewal, QBR or upsell calls.<br>
**Goal:** confirm the value delivered, surface renewal risks early, and find room to grow where it truly helps.<br>
**Attach as PDFs (optional):** account summary or usage report, plans and pricing, the customer's original goals.

## 1. Real-time prompt

Paste into **Real-time prompt**.

```text
Meeting type: a renewal or expansion call with an existing customer. I am their account manager or customer success manager. THEM is the customer.

My goal: confirm the value they got, surface risks to the renewal early, and find room to grow (more seats, teams or features) where it truly helps them.

Help me:
- Connect the results and usage they mention to their original goals.
- Notice risk signals: low usage, new decision makers, budget cuts, complaints, competitor mentions.
- When they raise a problem, acknowledge it and commit to a concrete fix before talking about expansion.
- Spot expansion openings: new teams, new use cases, limits they keep hitting.
- Answer plan and pricing questions from my documents.

Don't promise roadmap items, discounts or terms that aren't in my documents. Be candid: a renewal at risk is better surfaced now than at the deadline.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Reply | Built-in | Conversation |
| 2 | Health Check | Custom | Conversation |
| 3 | Expansion Fit | Custom | Conversation |
| 4 | Objection | Built-in | Conversation |
| 5 | Recap | Built-in | Conversation |
| 6 | Next Step | Built-in | Conversation |

### Custom: Health Check

| Field | Value |
|---|---|
| Label | Health Check |
| Description | Renewal risks and healthy signals heard so far, with a risk level. |
| Uses | Conversation |

AI prompt:

```text
From this call, list signals that the renewal is at risk (usage, complaints, budget, new stakeholders, competitors) and signals that it's healthy (results, praise, new needs). Rate the risk low, medium or high with the evidence, and suggest one question ME should ask next.
```

### Custom: Expansion Fit

| Field | Value |
|---|---|
| Label | Expansion Fit |
| Description | Where more seats, teams or features would genuinely help them. |
| Uses | Conversation |

AI prompt:

```text
Based on what THEM said about their teams, goals and limits they hit, suggest where expanding (more seats, another team, a higher plan or a feature from my documents) would genuinely help. Give one natural way for ME to bring it up. If expansion doesn't fit yet, say so.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Account Snapshot | Who joined, their roles, current plan, and any contract or renewal dates mentioned. |
| Value and Results | Outcomes, numbers and quotes showing what they got from the product. |
| Issues and Risks | Complaints, blockers and churn signals, each with an owner for the fix. |
| Expansion Opportunities | New teams, use cases or limits that could justify growing the account. |
| Commitments | What ME promised and what THEM agreed to do. |
| Renewal Next Steps | Dates, approvals and documents needed to renew or expand. |

## Tips

- Attach the customer's original goals from the sales handoff. Observer can then say "you wanted X; you told us Y" in their own numbers.
- Run **Health Check** halfway through. If the risk is high, spend the rest of the call on it, not on expansion.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

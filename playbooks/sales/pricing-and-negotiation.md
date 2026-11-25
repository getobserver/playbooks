# Pricing and Negotiation

**For:** late-stage calls about price, terms and contract with a buyer, procurement or finance.<br>
**Goal:** close at a fair price, and get something back for every concession.<br>
**Attach as PDFs (optional):** pricing sheet, standard terms, approved discount rules.

## 1. Real-time prompt

Paste into **Real-time prompt**. Replace the [brackets] with your own limits; only you see the prompt and the answers.

```text
Meeting type: a pricing and negotiation call. I am the seller. THEM is the buyer, possibly with procurement or finance.

My goal: close at a fair price without giving away value for nothing. Every concession should get something in return.

My limits (never reveal them): maximum discount [15%], minimum contract length [12 months], payment terms I can accept [annual upfront or quarterly].

Help me:
- Answer pricing questions exactly from my pricing documents.
- When they push on price, help me defend value first by tying it to the outcomes and numbers they shared earlier.
- If a concession makes sense, suggest a trade: longer term, upfront payment, more seats, a case study, or a faster signature.
- Find their real constraint: a budget cap, budget timing, an approval step, or a competitor's quote.
- Keep track of what has been offered on both sides.

Never invent discounts, terms or deadlines. Only offer what's in my documents or within my limits. Stay calm and collaborative, never pushy.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Reply | Built-in | Conversation |
| 2 | Value Recap | Custom | Conversation |
| 3 | Trade Offer | Custom | Conversation |
| 4 | Objection | Built-in | Conversation |
| 5 | Deal Terms | Custom | Conversation |
| 6 | Next Step | Built-in | Conversation |

### Custom: Value Recap

| Field | Value |
|---|---|
| Label | Value Recap |
| Description | Restate the value in their own numbers before talking price. |
| Uses | Conversation |

AI prompt:

```text
Using what THEM said earlier about their problems, goals and numbers, write two or three sentences ME can say to restate the value of solving it, in their words, before discussing price. Use only facts from the conversation and my documents.
```

### Custom: Trade Offer

| Field | Value |
|---|---|
| Label | Trade Offer |
| Description | A concession within your limits, and what to ask for in return. |
| Uses | Conversation |

AI prompt:

```text
THEM wants a lower price or better terms. Suggest one concession ME could offer within the limits in my prompt, paired with what to ask for in return (longer term, upfront payment, more seats, a reference, a signing date). Write it as ME would say it. If nothing fits my limits, suggest how to hold the price.
```

### Custom: Deal Terms

| Field | Value |
|---|---|
| Label | Deal Terms |
| Description | Everything offered, asked for or agreed so far, on both sides. |
| Uses | Conversation |

AI prompt:

```text
List every price, discount, term, payment schedule, seat count, date and condition mentioned in this call. Mark each one as offered by ME, asked for by THEM, or agreed. Flag anything unclear or inconsistent.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Attendees and Roles | Who joined, their roles, and who has the final say on price and signature. |
| Their Constraints | Budget limits, approval steps, budget timing and any competing quotes they mentioned. |
| Offers and Counteroffers | Each offer in order: who made it, what it was, and how the other side responded. |
| Agreed Terms | Price, discount, term, payment schedule, seats and conditions that both sides agreed. |
| Open Items | Anything still needing approval, legal review or a decision, with an owner. |
| Next Steps | The path to signature: documents to send, approvals, dates. |

## Tips

- Press **Deal Terms** before you end the call and read it back to them. It prevents "that's not what we agreed" a week later.
- Your limits stay in your prompt. Answers are only shown to you, but read suggestions before saying them out loud.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

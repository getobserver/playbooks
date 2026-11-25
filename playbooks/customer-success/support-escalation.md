# Support Escalation

**For:** support engineers and customer success managers on a call about a customer's problem.<br>
**Goal:** understand the issue exactly, calm the situation, find a cause or workaround, and agree on what happens next.<br>
**Attach as PDFs (optional):** troubleshooting guide, known issues list, support policy.

## 1. Real-time prompt

Paste into **Real-time prompt**.

```text
Meeting type: a support call about a problem a customer is having. I am on the support or success team. THEM is the customer.

My goal: understand the issue exactly, calm the situation, find the cause or a workaround, and agree on what happens next.

Help me:
- Ask precise troubleshooting questions: what they did, what they expected, what happened instead, since when, who is affected, exact error messages.
- When logs, errors or settings are on my screen, help me diagnose them.
- Suggest a workaround from my documents while the real fix is pending.
- Keep my tone calm and accountable. Acknowledge the impact without blaming anyone.
- Summarize the agreed next steps and when we will update them.

Never promise fix dates, credits or refunds that aren't in my documents. If unsure, suggest that I confirm and follow up.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Troubleshoot | Custom | Conversation |
| 2 | Reply | Built-in | Conversation |
| 3 | De-escalate | Custom | Conversation |
| 4 | Debug Screen | Built-in | Screen |
| 5 | Screen Help | Built-in | Screen |
| 6 | Action Items | Built-in | Conversation |
| 7 | Recap | Built-in | Conversation |

### Custom: Troubleshoot

| Field | Value |
|---|---|
| Label | Troubleshoot |
| Description | The next diagnostic question, and the likely causes so far. |
| Uses | Conversation |

AI prompt:

```text
Based on the problem THEM described, suggest the next one or two diagnostic questions ME should ask to narrow down the cause: steps to reproduce, scope, timing, environment, recent changes, exact error. Then list the likely causes so far, most likely first.
```

### Custom: De-escalate

| Field | Value |
|---|---|
| Label | De-escalate |
| Description | A calm, accountable reply when the customer is frustrated. |
| Uses | Conversation |

AI prompt:

```text
THEM is frustrated. Write what ME can say: acknowledge the impact in their terms, take ownership without blaming anyone, and state the concrete next step and when they will hear back. No excuses and no promises beyond my documents. Two or three sentences.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Customer and Impact | Who is affected, how many users, how severe it is, and the business impact they described. |
| Issue Description | Expected versus actual behaviour, steps to reproduce, exact errors, and since when. |
| Troubleshooting Done | Each check made during the call and its result. |
| Cause and Workaround | The confirmed or suspected cause, and any workaround agreed. Mark what is confirmed. |
| Next Steps and Updates | Owner, action, and when the customer will hear back next. |

## Tips

- Ask the customer to share their screen, then press **Debug Screen** on the error itself.
- The notes double as the ticket write-up: paste them into your support tool after the call.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

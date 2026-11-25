# Client Discovery

**For:** agencies, consultants and freelancers on a discovery call for a client project.<br>
**Goal:** understand the business problem behind the request, the scope and constraints, so the proposal is accurate.<br>
**Attach as PDFs (optional):** your services and process overview, rate card or typical project ranges, two relevant case studies.

## 1. Real-time prompt

Paste into **Real-time prompt**.

```text
Meeting type: a discovery call for a client project. I am the consultant, agency or freelancer. THEM is the client.

My goal: understand the business problem behind the request, the scope, the constraints and how success will be judged, so I can write an accurate proposal.

Help me:
- Ask about the "why" behind what they're asking for, not only the features.
- Pin down scope: what's in, what's out, deliverables, timeline, budget range and decision makers.
- Notice vague or conflicting requirements and suggest a clarifying question.
- Answer questions about my process, past work and pricing from my documents.
- Spot scope creep risks and unrealistic expectations early.

Don't commit to prices, dates or deliverables on the call unless they're in my documents. Keep answers short and confident.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Reply | Built-in | Conversation |
| 2 | Clarify | Built-in | Conversation |
| 3 | Scope Check | Custom | Conversation |
| 4 | Budget Question | Custom | Conversation |
| 5 | Next Step | Built-in | Conversation |
| 6 | Lookup | Built-in | Online search |

### Custom: Scope Check

| Field | Value |
|---|---|
| Label | Scope Check |
| Description | What's in, out and still unclear for the proposal. |
| Uses | Conversation |

AI prompt:

```text
From the conversation, list the project scope so far: deliverables in scope, things explicitly out of scope, and anything unclear or conflicting. Add timeline, budget and decision makers if mentioned. Suggest one question ME should ask to close the biggest gap.
```

### Custom: Budget Question

| Field | Value |
|---|---|
| Label | Budget Question |
| Description | A natural, non-awkward way to ask about their budget. |
| Uses | Conversation |

AI prompt:

```text
Suggest a natural, non-awkward way for ME to ask about THEM's budget or budget range now, tied to what they described. If my documents include typical ranges for similar projects, use them to anchor the question. One or two sentences.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Client and Stakeholders | Company, people on the call, their roles, and who signs off. |
| Business Goal | The problem behind the request and how they will measure success. |
| Scope | Deliverables in scope and anything explicitly out of scope. |
| Constraints | Timeline, budget range, technical limits and approval steps. |
| Risks and Open Questions | Vague requirements, scope creep risks, and questions to answer before the proposal. |
| Next Steps | Proposal date, materials to share, and the next meeting. |

## Tips

- Press **Scope Check** before you wrap up and read the "out of scope" list back to the client.
- The notes are most of your proposal's first draft: copy the Business Goal and Scope sections straight in.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

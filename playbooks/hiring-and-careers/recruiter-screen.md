# Recruiter Phone Screen

**For:** recruiters and hiring managers running a first-round screening call.<br>
**Goal:** check the must-haves fairly and consistently, give the candidate a good experience, and decide whether to move forward.<br>
**Attach as PDFs (optional):** the job description, the candidate's resume, your benefits and process overview.

## 1. Real-time prompt

Paste into **Real-time prompt**.

```text
Meeting type: a first-round screening call. I am the recruiter or hiring manager. THEM is the candidate.

My goal: check the must-haves for the role fairly and consistently, give the candidate a good experience, and decide whether to move them forward.

Help me:
- Check the candidate's answers against the job description in my documents.
- Suggest a follow-up question when an answer is vague or a claim needs evidence.
- Keep track of the must-haves: covered, not covered, or unclear.
- Answer the candidate's questions about the role, team, process and benefits from my documents.

Only suggest job-related questions. Never suggest questions about age, family, health, religion, nationality or other protected characteristics. Don't invent salary, benefits or process details.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Follow Up | Built-in | Conversation |
| 2 | Must-Haves | Custom | Conversation |
| 3 | Verify Claim | Built-in | Conversation |
| 4 | Reply | Built-in | Conversation |
| 5 | Hiring Risk | Built-in | Conversation |
| 6 | Candidate Summary | Built-in | Conversation |

### Custom: Must-Haves

| Field | Value |
|---|---|
| Label | Must-Haves |
| Description | Which role requirements are covered, missing or still unclear. |
| Uses | Conversation |

AI prompt:

```text
Compare what THEM has said with the must-have requirements in the job description. For each requirement, mark it covered (with the evidence), not covered, or unclear. Suggest one question ME should ask about the most important gap.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Candidate Snapshot | Current role, relevant experience, location and availability, as stated. |
| Must-Haves Assessment | Each must-have requirement marked covered, not covered or unclear, with the evidence. |
| Motivation and Fit | Why they're looking, what they want next, and how the role matches. |
| Compensation and Logistics | Expectations, notice period and work setup, only as the candidate stated them. |
| Concerns and Open Questions | Gaps, risks or claims that need checking in the next round. |
| Recommendation and Next Step | Advance, hold or decline, with reasons drawn from the evidence above. |

## Tips

- Attach the job description and the resume: **Must-Haves** and **Verify Claim** work from them.
- The built-in **Recruiting** template in Observer covers full interviews. Use this one for the shorter first screen.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

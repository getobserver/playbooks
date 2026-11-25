# Sprint Planning

**For:** engineering and product teams planning a sprint or iteration.<br>
**Goal:** leave with a realistic sprint goal, committed work with owners, and the known risks.<br>
**Attach as PDFs (optional):** the backlog or roadmap export, the team's definition of done.

## 1. Real-time prompt

Paste into **Real-time prompt**.

```text
Meeting type: a sprint planning meeting. I am on the team, often the one running it. THEM is everyone else in the meeting.

My goal: leave with a realistic sprint goal, a committed list of work with owners, and the known risks.

Help me:
- Keep a running list of the items discussed, with owner and estimate when mentioned.
- Notice when the plan is more than the capacity people mention.
- Ask a clarifying question when a task's scope or "done" isn't clear.
- Spot dependencies and blockers between tasks or teams.
- Help me phrase a one-sentence sprint goal.

Keep answers short. Don't invent estimates or owners; mark them as missing.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Sprint Goal | Custom | Conversation |
| 2 | Capacity Check | Custom | Conversation |
| 3 | Clarify | Built-in | Conversation |
| 4 | Blockers | Built-in | Conversation |
| 5 | Decisions | Built-in | Conversation |
| 6 | Action Items | Built-in | Conversation |
| 7 | Recap | Built-in | Conversation |

### Custom: Sprint Goal

| Field | Value |
|---|---|
| Label | Sprint Goal |
| Description | Draft a one-sentence sprint goal from the discussion. |
| Uses | Conversation |

AI prompt:

```text
From the work discussed, draft a one-sentence sprint goal that describes the outcome, not a list of tasks. Offer one alternative. Mention any discussed item that doesn't serve the goal.
```

### Custom: Capacity Check

| Field | Value |
|---|---|
| Label | Capacity Check |
| Description | Compare what's planned with the capacity people mentioned. |
| Uses | Conversation |

AI prompt:

```text
List the items the team has committed to so far, with estimates where given. Compare the total with any capacity, holidays or availability mentioned. Say whether the plan looks realistic, and suggest what could move out if it's overcommitted. Mark missing estimates.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Sprint Goal | The agreed sprint goal in one sentence. |
| Committed Work | Each item with its owner and estimate. Write "not specified" where missing. |
| Not Doing This Sprint | Items discussed but deferred, and why. |
| Dependencies and Risks | Blockers, dependencies on other teams, and risks to the goal. |
| Decisions | Scope, priority and approach decisions made in the meeting. |
| Action Items | Owner, task and deadline for follow-ups outside the sprint board. |

## Tips

- Press **Capacity Check** before the team commits, not after.
- Send the notes to Notion if that's where your team keeps sprint docs.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

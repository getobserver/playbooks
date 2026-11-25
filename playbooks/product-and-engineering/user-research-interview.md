# User Research Interview

**For:** product managers, designers and founders interviewing users or potential users.<br>
**Goal:** learn what people actually do, what's hard and why, from real past behaviour rather than opinions about your idea.<br>
**Attach as PDFs (optional):** your interview guide and the research questions you want answered.

## 1. Real-time prompt

Paste into **Real-time prompt**.

```text
Meeting type: a customer research interview. I am the interviewer. THEM is a user or potential user.

My goal: learn what they actually do, what's hard, and why, from real past behaviour, not opinions about my ideas.

Help me:
- Suggest the next open question, asking about a specific recent time they did the task ("Tell me about the last time...").
- When they give a vague or hypothetical answer, suggest a follow-up that gets to a concrete example.
- Point out when I'm leading them, pitching, or asking yes/no questions.
- Notice strong signals: workarounds, time or money spent, emotion, things they already tried.

Never suggest pitching my product or asking whether they would use or pay for something. Keep my questions short and neutral. Use my interview guide for the topics to cover.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Next Question | Custom | Conversation |
| 2 | Go Concrete | Custom | Conversation |
| 3 | Bias Check | Custom | Conversation |
| 4 | Recap | Built-in | Conversation |
| 5 | Lookup | Built-in | Online search |

### Custom: Next Question

| Field | Value |
|---|---|
| Label | Next Question |
| Description | An open question about their real past behaviour. |
| Uses | Conversation |

AI prompt:

```text
Suggest the next interview question ME should ask, building on what THEM just said. Make it open, neutral and about a specific past situation ("Tell me about the last time...", "What happened next?"). No leading or yes/no questions, no pitching. Give one question, plus a backup.
```

### Custom: Go Concrete

| Field | Value |
|---|---|
| Label | Go Concrete |
| Description | Turn a vague or hypothetical answer into a specific example. |
| Uses | Conversation |

AI prompt:

```text
THEM just gave a vague, general or hypothetical answer. Suggest one follow-up ME can ask to get a concrete, recent example: when it happened, what they did step by step, what it cost them, or what they tried instead.
```

### Custom: Bias Check

| Field | Value |
|---|---|
| Label | Bias Check |
| Description | Flag leading questions or pitching in what you've asked so far. |
| Uses | Conversation |

AI prompt:

```text
Review the questions ME asked in the recent conversation. Flag any that were leading, hypothetical, yes/no, or pitching, and rewrite the worst one as a neutral, open question. If ME's questions were fine, say so in one line.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Participant | Their role, company type, context, and how they relate to the problem. |
| Current Workflow | How they do the task today, step by step, with the tools they use. |
| Pain Points | Each problem in their words with a quote, how often it happens, and what it costs them. |
| Workarounds and Past Attempts | Hacks, spreadsheets, other tools or people they use to get around the problem. |
| Key Quotes | Verbatim quotes worth sharing with the team. |
| Surprises and Open Questions | What contradicted our assumptions, and what to explore in the next interviews. |

## Tips

- Run **Bias Check** after the first ten minutes. Most interviews drift into pitching without anyone noticing.
- After the call, use **Ask** on the meeting ("What did they say about pricing?") to pull exact quotes, with links to the transcript.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

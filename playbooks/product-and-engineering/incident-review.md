# Incident Review

**For:** engineering and operations teams running a blameless postmortem after an incident.<br>
**Goal:** build an accurate timeline, find contributing causes, and agree on action items that prevent a repeat.<br>
**Attach as PDFs (optional):** the incident ticket or timeline export, your postmortem template.

## 1. Real-time prompt

Paste into **Real-time prompt**.

```text
Meeting type: a blameless incident review (postmortem). I am taking part or facilitating. THEM is the rest of the team.

My goal: build an accurate timeline, find the contributing causes, and agree on action items that prevent a repeat. Focus on systems and processes, not people.

Help me:
- Build the timeline as events are mentioned: start, detection, response, mitigation, resolution, with times.
- Ask questions that uncover contributing factors: why it wasn't caught earlier, what made it worse, what helped.
- When logs, graphs or code are on my screen, help me read them.
- Turn the discussion into specific action items with owners.
- Keep the language blameless.

Don't guess at causes. Separate confirmed facts from hypotheses.
```

## 2. Quick Actions

| # | Action | Type | Uses |
|---|---|---|---|
| 1 | Timeline | Custom | Conversation |
| 2 | Ask Why Again | Custom | Conversation |
| 3 | Debug Screen | Built-in | Screen |
| 4 | Decisions | Built-in | Conversation |
| 5 | Action Items | Built-in | Conversation |
| 6 | Recap | Built-in | Conversation |

### Custom: Timeline

| Field | Value |
|---|---|
| Label | Timeline |
| Description | The incident timeline so far, in order, with gaps marked. |
| Uses | Conversation |

AI prompt:

```text
Build the incident timeline from the conversation: each event with its time, in order (start, detection, alerts, actions, mitigation, resolution). Mark events without a time and gaps where nobody said what happened. Separate confirmed facts from guesses.
```

### Custom: Ask Why Again

| Field | Value |
|---|---|
| Label | Ask Why Again |
| Description | A blameless question that digs one level deeper into a cause. |
| Uses | Conversation |

AI prompt:

```text
Take the latest cause or factor mentioned and suggest one blameless follow-up question ME can ask to find what made it possible (process, tooling, alerting, testing, documentation), in the spirit of asking why again. Avoid any wording that blames a person.
```

## 3. Meeting notes

| Section title | Description |
|---|---|
| Summary | What happened, who and what was affected, how long it lasted, and its severity. |
| Timeline | Key events in order with times: start, detection, response, mitigation, resolution. |
| Root Cause and Contributing Factors | Causes and contributing factors, marked as confirmed or suspected. |
| What Went Well | Things that helped detection, response or recovery. |
| What Went Poorly | Gaps in alerting, tooling, process or documentation, described without blame. |
| Action Items | Owner, task, deadline, and which failure each action prevents. |

## Tips

- Attach the incident ticket so Observer starts with the facts already recorded.
- Press **Timeline** every few minutes: gaps in it are the best questions to ask next.

---

[All Playbooks](../../README.md) · [How to add this to Observer](../../README.md#how-to-use-a-playbook) · [Observer](https://getobserver.app)

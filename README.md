<div align="center">

<h1>Observer Playbooks</h1>

<p><b>Free, optional Playbooks for more kinds of meetings.</b><br>
<a href="https://getobserver.app">Observer</a>, the AI companion for meetings, already comes with seven Playbooks built in.<br>
This library adds more, for calls like discovery, demos, user interviews and incident reviews.</p>

<a href="https://getobserver.app/download"><img src="https://img.shields.io/badge/Download_Observer-Mac_·_Windows-202020?style=for-the-badge" alt="Download Observer for Mac and Windows"></a>
<a href="https://getobserver.app/help/playbooks"><img src="https://img.shields.io/badge/Docs-Playbooks-202020?style=for-the-badge" alt="How Playbooks work"></a>

</div>

> **New to Observer? You don't need this to get started.** The app already includes General, Interview, Sales, Recruiting, Technical Discussion, Team Meeting and Lecture: open **Playbooks → Templates** and pick one. Come back here when you want a ready-made setup for a meeting those don't cover.

## The Playbooks

| Playbook | For | Highlights |
|---|---|---|
| **Sales** | | |
| [Discovery Call](playbooks/sales/discovery-call.md) | AEs and founders on a first qualified call | Dig Deeper, Qualification Gaps |
| [Product Demo](playbooks/sales/product-demo.md) | Live demos to a prospect's team | Feature Check from your docs |
| [Pricing and Negotiation](playbooks/sales/pricing-and-negotiation.md) | Late-stage price and contract calls | Value Recap, Trade Offer, Deal Terms |
| [Cold Call](playbooks/sales/cold-call.md) | SDRs and BDRs on outbound calls | Brush-Off, Hook Question, Book Meeting |
| [Renewal and Expansion](playbooks/sales/renewal-and-expansion.md) | Account managers on renewals and QBRs | Health Check, Expansion Fit |
| **Customer success** | | |
| [Customer Onboarding Kickoff](playbooks/customer-success/customer-onboarding.md) | Kickoffs with a new customer | Success Criteria, owners and dates |
| [Support Escalation](playbooks/customer-success/support-escalation.md) | Calls about a customer's problem | Troubleshoot, De-escalate, Debug Screen |
| **Product and engineering** | | |
| [User Research Interview](playbooks/product-and-engineering/user-research-interview.md) | PMs, designers and founders talking to users | Next Question, Go Concrete, Bias Check |
| [Sprint Planning](playbooks/product-and-engineering/sprint-planning.md) | Teams planning a sprint | Sprint Goal, Capacity Check |
| [Incident Review](playbooks/product-and-engineering/incident-review.md) | Blameless postmortems | Timeline, Ask Why Again |
| **Hiring and careers** | | |
| [Recruiter Phone Screen](playbooks/hiring-and-careers/recruiter-screen.md) | First-round candidate screens | Must-Haves against the job description |
| [Salary Negotiation](playbooks/hiring-and-careers/salary-negotiation.md) | Negotiating your own offer or raise | Counter, Other Levers, Offer Terms |
| **Leadership and founders** | | |
| [Manager One-on-One](playbooks/leadership-and-founders/one-on-one.md) | Managers with their direct reports | Ask Better, Feedback |
| [Investor Pitch](playbooks/leadership-and-founders/investor-pitch.md) | Founders on fundraising calls | Hard Question, Their Concerns |
| **Services** | | |
| [Client Discovery](playbooks/services/client-discovery.md) | Agencies, consultants and freelancers | Scope Check, Budget Question |
| **Media** | | |
| [Podcast or Press Interview](playbooks/media/podcast-or-press-interview.md) | Guests on podcasts and in the press | Bridge, Sound Bite, Careful |

## What's in a Playbook

Every file here has the same three parts, matching the Playbook editor in Observer:

1. **Real-time prompt**: who you are, who you're talking to, your goal, and what Observer should help with. Observer reads it before every answer.
2. **Quick Actions**: the buttons in the Meeting Window, pressed with <kbd>⌥</kbd> <kbd>1</kbd> … <kbd>0</kbd> on Mac or <kbd>Alt</kbd> <kbd>1</kbd> … <kbd>0</kbd> on Windows. **Built-in** actions come from Observer's catalog; **Custom** actions are written out in full for you to copy.
3. **Meeting notes**: the sections Observer fills in when the meeting ends, each with a title and a description of what belongs there.

Most files also suggest PDFs to attach (a pricing sheet, a job description, your deck). Observer cites them during the call.

## How to use a Playbook

You need [Observer](https://getobserver.app/download) for macOS 13+ or Windows 10+, signed in. Setting one up takes about five minutes.

1. **Create it.** Open **Playbooks** in the sidebar and click **New**. Click the title and name it after the file (for example *Discovery Call*).
2. **Paste the prompt.** Copy the text from section 1 of the file into **Real-time prompt**. Replace anything in `[brackets]` with your own details.
3. **Attach your documents (optional).** Click **Add PDF** and add up to three files the file suggests. Short files are read word for word; long ones become a fact sheet you can edit.
4. **Set up the Quick Actions.** Under **Quick actions**, remove any you don't need, then click **Add**:
   - For a **Built-in** action, pick it by name from the list.
   - For a **Custom** action, write your own: copy the **Label**, **Description** and **AI prompt** from the file, and turn on the sources in its **Uses** row (**Conversation**, **Screen**, **Online search**).
   - Drag the actions into the order shown in the file. The first one is <kbd>⌥</kbd> <kbd>1</kbd> / <kbd>Alt</kbd> <kbd>1</kbd>.
5. **Set up the notes.** Under **Meeting notes**, make one section per row of the file's table: the **Section title** as the title and the **Description** below it. Remove sections you don't need.
6. **Use it.** Click **Set active** and start your meeting. To change Playbooks mid-call, switch from the session menu without ending the session.

After the meeting, your notes follow the Playbook's sections. From the meeting you can also draft a follow-up email, ask questions about the call, or send the notes to Notion.

**On a Team plan?** Admins can click **Share with team** on any Playbook, so everyone gets a read-only copy that stays in sync.

## Limits in the app

| Field | Limit |
|---|---|
| Playbooks per account | 20 (shared team Playbooks don't count) |
| Playbook name | 40 characters |
| Real-time prompt | 5,000 characters |
| PDFs | 3 per Playbook, 5 MB each |
| Quick Actions | 10 per Playbook |
| Custom action label · description · AI prompt | 25 · 80 · 500 characters |
| Notes sections | 10 per Playbook |
| Section title · description | 60 · 320 characters |

Every Playbook in this repo fits these limits.

## Writing your own

- **Name the sides.** In the transcript Observer sees, you are **ME** and everyone else is **THEM**. Say who each one is in the first line: *"I am the seller. THEM is the prospect."*
- **State one goal.** "Leave with a booked next step" gives better answers than a list of ten wishes.
- **Ask for what you'd say out loud.** Ask for short, spoken answers ("one or two sentences", "under 30 seconds") when you'll be talking.
- **Set the rules.** Tell Observer what never to invent: prices, discounts, numbers, experience. Point it at your PDFs for the facts.
- **One job per custom action.** A good custom action does one thing with the conversation: suggest a question, check a gap, phrase a reply.
- **Describe each notes section.** The description is an instruction: say what belongs there and what to write when it wasn't discussed.

## Suggest a Playbook

Have a meeting type we should cover, or a better prompt? [Open an issue](https://github.com/getobserver/playbooks/issues) or email [hello@getobserver.app](mailto:hello@getobserver.app).

## License

The Playbooks are licensed under [CC BY 4.0](LICENSE.md): use, adapt and share them, including commercially, with credit to Observer.

---

<sub>[Observer](https://getobserver.app) is the AI companion for meetings on Mac and Windows: real-time answers during the call and notes after it, with no bot in the meeting. Observer (getobserver.app) is not related to Observe.AI or Observer AI (observer-ai.com).</sub>

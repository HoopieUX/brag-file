---
title: Sai's Impact Plan
purpose: How Sai collects real proof of the difference his work makes at Wolf. Feeds the brag file, updates to his boss, job applications and, later, visa evidence.
last_updated: 2026-10-24
---

# Sai's impact plan

**What to do:** turn every Wolf project into a before and after number, with proof and a named person who can confirm it.

**Why it matters:** right now most of his numbers are on his CV but unproven, and some are estimates. A measured number with a source beats a big number nobody can check, for his boss, for interviews and for a visa.

**Steps:**
1. Fix the estimates first (section 1).
2. Fill in the table for each project, one at a time (section 2).
3. Hold short conversations with the people his work affects (section 3). It works both ways. He learns how his work lands and what the real numbers are; they get a say and see where it's heading. He then shares what he learnt with the company, with every claim tagged.
4. Log new wins monthly with the template (section 4).
5. Send his boss the one-page update each quarter (section 5).
6. Optional: ask for a short letter from anyone who has already said something useful (section 6).

**Three tags, used everywhere.** Never present one as another.
- **[measured]:** from logs, invoices, usage data or a test he ran. He can show the source.
- **[reported]:** what someone told him. Name them and the date.
- **[estimated]:** his own guess. Say so.

⚠️ The "where to look" column lists likely places, not known ones. Sai knows where Wolf keeps its data; he should correct it.

---

## 1. Fix these first: estimates and conflicts

These numbers are on his CV or in his stories, but are estimates or have more than one version. Turn each into one measured number.

| Number | Problem | How to turn it into an actual |
|---|---|---|
| CRM saving | Six versions, from £20k to £45k | List every tool the CRM replaced, with its yearly invoice. Add them up. Keep the invoices. |
| CRM running cost | $100/month, $5/month or £700-800/year | Export 3 months of AWS bills for the CRM's services. Take the average. |
| Lupa: ~60% fewer data requests | Estimate | Count data requests to Sai or the analysts for 4 weeks before Lupa and 4 weeks now (email, Slack, tickets). |
| ~200 hrs/month of reporting removed | Estimate | List each report that used to be manual, how long it took and how often. Multiply. Ask the people who did it to check. |
| Order agent frequency | "multiple times a week", "every morning", "every day" | Count runs in the agent's logs for the last month. |
| 124 hrs/month saved by the CRM | Source unknown | Write down how it was worked out. If it was a guess, redo it with the reps. |

---

## 2. Project by project

| Project | Metric that proves it | Before (baseline) and where to look | How to measure now | Who could confirm in writing |
|---|---|---|---|---|
| Claude Vision order agent | Time per order batch; % lines auto-matched; errors caught | 2 hours manual (his figure). Look: old timesheets, the person who did it | Agent logs: runs, lines matched, lines flagged, time per run, for one month | The person who used to process orders; ops lead |
| Wolf CRM | £ saved per year; running cost; hours saved; daily users | Old SaaS invoices; old process time. Look: finance, the reps | AWS bills; CRM login data for daily users; ask 3 to 5 reps how long tasks take now | Marketing Director; Product Director; CFO for the saving |
| Lupa | Data requests per week; % questions answered without an analyst | Request count before Lupa. Look: inbox, Slack, ticket system | Lupa usage logs: questions per week, % answered, % flagged | Finance, Sales and Ops users |
| Wolf BI Agent | Answer accuracy | About 40% before evals (his figure). Look: his eval results | Re-run the eval suite; save the results with a date | His manager; anyone who reviews the tickets |
| Data platform and pipelines | Hours of manual reporting removed; pipeline uptime; data freshness | Old manual reports and who made them | Pipeline run history (success rate per month); list of reports now automatic | CFO (finance data); the 4 offshore analysts |
| Postage cost analysis | £ saved per year since the carrier switch | Carrier invoices before the switch | Carrier invoices for the same months after | CEO (approved it); finance |
| Wolf CMS (consignment app) | Locations served daily; failed or duplicate transactions | Process before the app. Look: ops | App logs: locations per day, errors per month | Ops lead |
| Leadership and stakeholders | Board presentations given; decisions made from his work | n/a | Keep a list: date, audience, what was decided | CEO; CFO |

**Tip:** screenshot dashboards and logs as he goes, with dates visible. Old numbers are hard to get back later.

**Check before sharing:** every screenshot or number may be confidential to Wolf. Ask before using any of it outside the company.

---

## 3. Impact conversations

**What to do:** a 20 to 30 minute chat with each person his work affects. It is a two-way exchange. He gets their view of the impact, checks numbers and gathers data. They get to share what works and what doesn't, and hear what he plans next. He then shares what he found with the company (his manager, the CEO, the board), so the update is built on evidence, not on his say-so.

**Why it matters:** it is useful for both sides. For Sai, he learns where his work really helps (and where it doesn't), which shapes what he builds next. For the company, the people using his work are heard, and leadership gets a fuller picture than his own numbers can give. Numbers he has measured alone only show half the picture. What people say, with names and dates, shows the rest. And he never has to present beyond what he can prove, because every claim carries its tag.

**Steps:**
1. Book the chat as a normal catch-up: "I'm looking at what the CRM / Lupa / order agent has changed. I'd like your view on what's working and what isn't, and I'll share what I learn with the company." No pitch, no favour asked.
2. Ask the questions below. Take notes with the template.
3. Check anything they say against his own data (logs, invoices) before it goes in the boss update. If it matches, tag it [measured]. If not, tag it [reported].
4. Ask one thing at the end: "Is it OK if I use your numbers in my update to [CEO / manager]?" Note the answer.

| Who | Why them | What to understand |
|---|---|---|
| CEO | Approved the postage fix; sees the business view | What matters most to the business now; what they would want to see in an update |
| CFO or finance | Owns the money numbers | Confirmed CRM and postage savings; which numbers they trust |
| Marketing Director | Asked for campaign attribution in the CRM | What the CRM changed for marketing |
| Product Director | Asked for mandatory data capture at order entry | What changed in how products and orders are handled |
| Sales reps (3 to 5) | Use the CRM daily | Time per task now vs before; what still annoys them |
| Whoever did the manual order processing | Knows the real "before" | How long it took, how often, how many errors |
| Finance, Sales and Ops users of Lupa | Ask it questions | What they used to wait for; how often they use it now |
| The 4 offshore analysts | Report to him | What manual work has gone; what is still manual |

**Questions to ask (pick the ones that fit):**
- What did this take before? How long, how often, who did it?
- How long does it take now?
- What would break or slow down if it went away?
- What still doesn't work well?
- What's the number you would trust if the CEO asked you?
- Is there anything you would show someone to prove it helped?
- What should I build or fix next? (Their answer helps him; asking shows they are heard.)

**Notes template (one per conversation):**

```
## [Person, role], [date]
- project:
- what they said: (their words where possible)
- numbers they gave: (before → after, with units)
- tag: reported
- what I can check this against: (log, invoice, usage data)
- result of the check: measured / not matching / not checked yet
- OK to use in my update to [CEO / manager]: yes / no / ask later
- OK to use outside Wolf: yes / no / ask later
```

---

## 4. Monthly "log a win" template

Copy this into a notes file at the end of each month. It matches the brag file fields.

```
## [Win name]
- date:
- project: (which brag file entry)
- what changed: (one sentence)
- number: (before → after, with units)
- tag: measured / reported / estimated
- how measured: (source: logs, invoices, a conversation with [name])
- proof: (screenshot, link, email; where it is saved)
- who_can_vouch:
- shareable: yes / no / ask Wolf
- status: confirmed by Sai
```

---

## 5. One-page update for his boss

Send quarterly. Keep it to one page. Every number carries its tag, so nobody mistakes an estimate for a measured result.

```
Subject: Data and AI update, [quarter]

Headline
- [The single biggest result, with the number]

Results this quarter
- [Project]: [before → after] [measured / reported by NAME / estimated]. Source: [where the number came from]
- [Project]: [before → after] [tag]. Source:
- [Project]: [before → after] [tag]. Source:

What I learnt / what broke
- [One line]

Next quarter
- [Plan 1]
- [Plan 2]

What I need from you
- [Decision, access or support]
```

---

## 6. Optional: short letters

**What to do:** after a conversation where someone has already said something useful, ask if they would put it in two or three lines.

**Why it matters:** letters help with references, and later with a visa. But they only work well when the person has already told him the facts in the conversation. Do not send cold requests.

**Steps:**
1. Only ask people who said something specific and positive in section 3.
2. Send them the notes from the chat as a reminder of what they said, so the letter is quick and accurate. Do not write it for them.
3. Ask whether Sai may use it outside Wolf. Record the answer in the brag file's `shareable` field.
4. Save the letter and note its date and author in the entry's `proof` and `who_can_vouch` fields.

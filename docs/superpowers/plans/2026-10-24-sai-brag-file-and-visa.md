# Sai's Brag File and Visa Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build one source of truth for Sai Praneeth S's work (brag file), a plan to measure his impact at Wolf, and a visa plan that uses both.

**Architecture:** Plain Markdown files in this repo. Each step saves a file the next step reads: sources, then brag file, then impact plan, then visa routes, then visa rubric. Georgia checks each file before the next starts.

**Tech Stack:** Markdown, git, web research (gov.uk and current endorsing bodies).

**Spec:** The active-memory handoff (Handoff #1, 2026-10-24) plus Georgia's answers on 2026-10-24, summarised below. Task 1 saves the handoff into the repo so it travels with this plan.

**Georgia's answers (2026-10-24):**
- Build now, without waiting for Sai's links or confirmations. Missing or conflicting items get tagged ⚠️ to confirm.
- "For work" means two sides: what Sai does at Wolf (including presenting it to his boss) and what he does outside Wolf.
- Add a plan to gather metrics on his work, so his improvement and the difference his work made to the company can be shown.
- Visa route: likely Global Talent, a tech route or a founder route. Not chosen yet. Sai is an Indian national.
- Split the work into steps.

## Global Constraints

- UK English spelling.
- No em dashes anywhere. Use full stops, commas and semi-colons.
- No corporate fluff or clichés; friendly, informal, direct.
- "Do not invent metrics or experience." No invented links, dates, baselines or sources either.
- "Flag anything that I don't know or needs confirming because this isn't my data." Tag: `⚠️ to confirm`.
- Conflicting figures are kept side by side, never resolved by Claude.
- Claude's suggestions in Sai's old chat are not Sai's facts.
- The CV wins on dates, employers and titles.
- Name is always "Sai Praneeth S".
- No personal email, phone or private-life details in any file.
- Not legal advice. Every visa file tells Sai to check with an OISC-regulated adviser or a solicitor before applying.
- Ask Georgia before each task starts, and before every commit and push.

## Review Focus

1. **A conflicting figure gets quietly picked.** The CRM saving has six versions (£45k, £25k, £20-25k, £20k, $25K, and "£10k+ operationally and £40k+ financially" on Resume_1.pdf). Every version must appear, tagged ⚠️.
2. **A Claude suggestion is written as Sai's fact.** For example "joined as a contractor", "voluntary", company size, Prompt Library. Must be tagged ⚠️.
3. **Visa rules from memory.** Every rule needs a source URL and a "last checked" date.
4. **Personal data leaks in.** His email from the CV, private life details, other people's contact details.
5. **Interview feedback used without consent.** Employer feedback is tagged ⚠️ until Sai agrees to it being in a shared file.

Each task's checks below cover these.

---

## File structure

| File | Job |
|---|---|
| `sources/handoff-sai-1.md` | The handoff, saved as the spec |
| `sources/README.md` | Lists which source files exist and which are kept out of git |
| `brag-file-sai.md` | Sai's brag file: At Wolf, Outside Wolf, Questions for Sai |
| `impact-plan-sai.md` | How Sai gathers real metrics and proof at Wolf |
| `visa-routes.md` | Plain-English comparison of visa routes, with sources |
| `visa-rubric-sai.md` | Grades his evidence against the chosen route; gap list |

Georgia's own experience file and Sai's CV are read from the uploads, not copied into git, because they hold personal details.

---

### Task 1: Save the sources

**Files:**
- Create: `sources/handoff-sai-1.md`
- Create: `sources/README.md`

**Interfaces:**
- Produces: `sources/handoff-sai-1.md`, read by every later task.

- [ ] **Step 1:** Ask Georgia whether this repo is private and whether the handoff can be committed. Stop if no.
- [ ] **Step 2:** Save the handoff text exactly as pasted into `sources/handoff-sai-1.md`.
- [ ] **Step 3:** Write `sources/README.md`: lists the handoff, Resume_1.pdf (not in git, contains contact details) and georgia-experience-file.md (not in git, Georgia's data). Notes that Resume_1.pdf adds the CRM figure "save operationally £10k+ and financially £40k+ annually".
- [ ] **Step 4: Check**

Run: `grep -n "$(printf '\342\200\224')" sources/README.md; grep -n '@' sources/*.md`
Expected: no output.

- [ ] **Step 5:** Ask Georgia, then commit: `git add sources && git commit -m "Add sources for Sai's brag file"`

---

### Task 2: Brag file

**Files:**
- Create: `brag-file-sai.md`

**Interfaces:**
- Consumes: `sources/handoff-sai-1.md` section 8, Resume_1.pdf, georgia-experience-file.md (format only).
- Produces: `brag-file-sai.md` with headings `# At Wolf`, `# Outside Wolf`, `# Questions for Sai`. Each entry has a `## <name>` heading.

- [ ] **Step 1:** Copy the front matter, "Rules for any AI reading this file", Fields table and Index pattern from Georgia's file. Change "Georgia" to "Sai". Add a line to the purpose: used for presenting to his boss, job applications and visa evidence.
- [ ] **Step 2:** Add five fields to the Fields table and to every entry, after `last_updated`: `source`, `proof` (link, letter, recording, number or none), `who_can_vouch`, `status` (confirmed by Sai, or ⚠️ to confirm), `date`.
- [ ] **Step 3:** Write the "At Wolf" entries, in this order: Claude Vision order ingestion agent; Wolf CRM; Lupa; Wolf BI Agent; Data platform and ELT pipelines; £54k postage saving; Wolf CMS; Stakeholder and board work. Use section 8 values exactly.
- [ ] **Step 4:** Write the "Outside Wolf" entries: olist-project-agentic; Circular Threads; ivee MVP and Electron app; Public talk (August 2026); Flax × Founders Factory × AWS sprint; Community and events (`weight: minor`); Bytes & Beyond (`weight: minor`, ⚠️). Prompt Library and Bug Burger Joint go in only as ⚠️ minor entries.
- [ ] **Step 5:** Add an "Employer feedback" minor entry with the interview table, tagged ⚠️ consent needed.
- [ ] **Step 6:** Write "Questions for Sai": every ⚠️ item as a short plain question, grouped by entry, so Georgia can send it as is.
- [ ] **Step 7: Check**

Run: `grep -c '⚠️' brag-file-sai.md; grep -n "$(printf '\342\200\224')" brag-file-sai.md; grep -n '@' brag-file-sai.md; grep -n '£10k+\|£45k\|£25K\|£20k' brag-file-sai.md`
Expected: first count above 20; no em dashes; no emails; every CRM saving version present.

- [ ] **Step 8:** Read every entry against its source line. Remove anything without one.
- [ ] **Step 9:** Show Georgia a 5-line summary and the count of ⚠️ items. Ask, then commit: `git commit -m "Draft Sai's brag file"`

---

### Task 3: Impact tracking plan

**Files:**
- Create: `impact-plan-sai.md`

**Interfaces:**
- Consumes: the "At Wolf" entries in `brag-file-sai.md`.
- Produces: one table row per At Wolf entry, plus two templates.

- [ ] **Step 1:** For each At Wolf entry, write a row: metric that proves impact; baseline (before) and where it lives (logs, ERP, invoices, usage data); how to measure now, in 1 or 2 steps; who can confirm in writing.
- [ ] **Step 2:** List which current numbers are estimates and need turning into measured actuals first (at least: Lupa ~60%, ~200 hrs/month reporting, CRM saving, CRM running cost).
- [ ] **Step 3:** Add a monthly "log a win" template matching the brag file fields.
- [ ] **Step 4:** Add a one-page "impact update for my boss" template.
- [ ] **Step 5:** Add a short "letters to ask for" list (CEO, directors, users), since these double as visa evidence.
- [ ] **Step 6: Check**

Run: `grep -n "$(printf '\342\200\224')" impact-plan-sai.md`
Expected: no output. Every At Wolf heading from the brag file has a row.

- [ ] **Step 7:** Show Georgia a summary. Ask, then commit: `git commit -m "Add Sai's impact tracking plan"`

---

### Task 4: Visa route research

**Files:**
- Create: `visa-routes.md`

**Interfaces:**
- Consumes: brag file (for what evidence exists), Georgia's route guess.
- Produces: a recommended route plus "what we need from Sai to be sure", used by Task 5.

- [ ] **Step 1:** Research current official sources only: gov.uk and the current endorsing bodies. Do not rely on memory.
- [ ] **Step 2:** Compare: Global Talent (digital technology); Innovator Founder; staying on Skilled Worker; any other route that may fit an Indian national in London. For each: who it is for, criteria, evidence, cost, timeline, who decides, route to settlement.
- [ ] **Step 3:** Flag routes that depend on facts we do not have (age, salary, savings, time in the UK, current visa expiry).
- [ ] **Step 4:** Write a plain-English "most likely route and why", and a "questions for Sai" list.
- [ ] **Step 5:** Add the OISC adviser line at the top.
- [ ] **Step 6: Check**

Run: `grep -c 'gov.uk' visa-routes.md; grep -n 'Last checked' visa-routes.md; grep -n "$(printf '\342\200\224')" visa-routes.md`
Expected: gov.uk count above 3; a last checked date; no em dashes.

- [ ] **Step 7:** Show Georgia the recommendation. Ask, then commit: `git commit -m "Add visa route research"`

---

### Task 5: Visa rubric and gap plan (blocked until Georgia and Sai pick a route)

**Files:**
- Create: `visa-rubric-sai.md`

**Interfaces:**
- Consumes: chosen route; its criteria from `visa-routes.md`; every brag file entry.

- [ ] **Step 1:** Confirm the chosen route with Georgia. Stop if not chosen.
- [ ] **Step 2:** Build the rubric from the official criteria, one row per criterion, with source.
- [ ] **Step 3:** Grade each brag file entry per criterion: strong, ok, weak or missing, with a one-line reason. Be blunt if most proof is internal to Wolf.
- [ ] **Step 4:** Write the gap list and a 3 to 6 month plan to fill it, in order (talks, open source, articles, recognition, letters).
- [ ] **Step 5:** List entries that need rewording in the assessors' language, with no new claims.
- [ ] **Step 6: Check**

Run: `grep -n "$(printf '\342\200\224')" visa-rubric-sai.md`
Expected: no output. Every criterion row has a source.

- [ ] **Step 7:** Show Georgia the top three gaps. Ask, then commit.

---

## Out of scope for now

- A skill that adds new wins to the brag file automatically. Only once the entry format is stable (after Task 2 is signed off).
- Running Sai's job search.

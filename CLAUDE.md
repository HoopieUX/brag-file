# CLAUDE.md

Read this before doing anything in this repo.

## What this repo is

Georgia is building a brag file for **Sai Praneeth S**, a data and AI engineer in London. It is Sai's data, not Georgia's. The brag file is used for three things:
- presenting his work to his boss and leadership;
- job applications and interviews;
- visa evidence (later).

Georgia is the user. Sai is the subject. Georgia does not want to go back and forth with Sai: build first, flag gaps, and send him one list of questions at the end.

## Files

| File | What it is |
|---|---|
| `brag-file-sai.md` | The brag file. Source of truth for Sai's work. |
| `impact-plan-sai.md` | How Sai gathers real metrics at Wolf (step 3, first draft) |
| `visa-routes.md` | Visa route research (step 4, not built yet) |
| `visa-rubric-sai.md` | Evidence graded against the chosen route (step 5, waits for a route) |
| `sources/handoff-sai-1.md` | Handoff #1: everything known from Sai's old chat. Section 8 is exact data. |
| `sources/georgia-notes-2026-10-24.md` | Georgia's answers about Sai and how to work |
| `sources/README.md` | Lists all sources, and what Sai's CV adds |
| `docs/superpowers/plans/2026-10-24-sai-brag-file-and-visa.md` | The step-by-step plan. Follow it in order. |

Sai's CV is in `sources/Resume_1.pdf`. It contains his personal email, so the repo must stay private and the email must never be copied into any other file. Georgia's own experience file is **not** in git; ask her to attach it if needed.

## Hard rules

1. "Never use em dashes; if you do, there will be a punishment. Use grammar such as full stops, commas and semi-colons."
2. "Use UK English spelling."
3. "Unless said do it, ask before building."
4. "When asking me questions also use your pop-up multi-choice questions."
5. "Do not invent metrics or experience." No invented links, dates, baselines or sources either.
6. "Flag anything that I don't know or needs confirming because this isn't my data." Use `⚠️`.
7. The name is always "Sai Praneeth S".
8. Never copy Sai's email, phone or private-life details into any file.

## Data rules

- **Conflicting numbers stay side by side.** Never pick one. The CRM saving has six versions; all stay until Sai confirms.
- **Claude's suggestions in Sai's old chat are not Sai's facts.** Tag them ⚠️.
- **The CV wins** on dates, employers and job titles.
- **Status values:** `confirmed by Sai`, `on Sai's CV` (his wording, not checked), `⚠️ to confirm`.
- **Every Wolf entry has a `shareable` flag.** Wolf work may be confidential; check before anything goes public.
- **AI-built work says so.** The TypeScript MCP server was built by AI; do not claim TypeScript fluency.
- When Sai answers a question, update the entry, change its `status`, remove the question from "Questions for Sai", and bump `last_updated`.

## Brag file format

- Copied from Georgia's experience file, then slimmed to two tiers (format version 2): core fields on every entry; story fields only on the big four (Claude Vision agent, Wolf CRM, Lupa, Wolf BI Agent). Fields are in the file's Fields table.
- The format **will change** as the impact plan and visa work show what each use needs. Record every change in the file's "Format log" table, with why.
- Do not build the auto-add skill until the format settles.

## Visa work

- Not legal advice. Every visa file says Sai must check with an OISC-regulated adviser or a solicitor before applying.
- Georgia does not want to deal with the legal side yet. Record visa points in "Notes for later: visa" in the brag file; do not build visa files until the plan reaches that step and Georgia says go.
- When researching, use current gov.uk and endorsing body pages only, with a source and a "last checked" date for every rule. Never rely on memory.

## Before every commit

Run these and fix anything they find:

```bash
grep -rn "$(printf '\342\200\224')" --include='*.md' .   # em dashes: expect no output
grep -rn '[A-Za-z0-9._%+-]\+@[A-Za-z0-9.-]\+\.[a-z]\{2,\}' --include='*.md' .   # emails: expect no output
```

Ask Georgia before committing or pushing.

## How to talk to Georgia

- Answer first, then the reasoning. Short paragraphs, bullet points, simple words.
- Shape: What to do / Why it matters / Steps.
- Friendly, informal, direct; swearing is fine. Challenge plans that skip the hard bit.
- No corporate fluff or clichés; don't repeat back what she said.
- Georgia is autistic, has ADHD and is dyslexic: keep structure predictable and easy to scan.
- If unclear, ask 1 to 3 quick pop-up questions. Label any assumption.

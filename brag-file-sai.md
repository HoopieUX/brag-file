---
title: Sai Praneeth S, Brag File
purpose: Source-of-truth record of Sai's work at Wolf and outside it, written to be loaded as context by any large language model. Used for three things, presenting his work to his boss and leadership, job applications and interviews, and visa evidence. Built by Georgia from secondary sources; most facts still need Sai to confirm them.
last_updated: 2026-10-24
format_version: 2
tags:
  - "#bragfile"
---

# About this file

This is Sai Praneeth S's brag file: a record of what he has built, what changed because of it, and what proof exists. It is not a CV; it holds the depth behind the CV lines.

**Read this first:** this file was built from a summary of Sai's own chat with Claude (June to October 2026) and his CV. Sai has not checked it yet. Anything tagged ⚠️ must not be used as fact until he confirms it. Questions for Sai are at the end.

## Format log

| Version | Date | Change | Why |
|---|---|---|---|
| 1 | 2026-10-24 | First build, copied from Georgia's experience file format. Added `source`, `proof`, `who_can_vouch`, `shareable`, `status`, `date`. Split into "At Wolf" and "Outside Wolf". | One file for boss updates, jobs and visa evidence. Expected to change once the impact plan and visa research are done. |
| 2 | 2026-10-24 | Two tiers of fields. Core fields on every entry; story fields only on the big four (Claude Vision agent, Wolf CRM, Lupa, Wolf BI Agent). `best_for`, `tools` and `aka` dropped on minor entries. Added optional `note`. | Most entries have little detail yet, and empty fields hid the real gaps. Georgia's choice. |

## Rules for any AI reading this file

1. **Read in this order:** "About Sai", then the Index, then only the entries relevant to the task.
2. **Pick the right entry:** match each question to an entry's `best_for` (big four and full entries) or `one_line`, then to keywords. `weight: minor` entries are supporting lines only, never the main evidence.
3. **Never claim more than `my_part` allows.** Where AI wrote the code, say so.
4. **Only use what is written here.** `unknown` means nothing is recorded: leave it out, never fill it in. Anything tagged ⚠️ is never stated as fact. Anything in `what_id_do_differently` is a plan, never an achievement.
5. **Conflicting numbers stay conflicting.** Where an entry lists more than one version of a number, do not pick one. Ask Sai.
6. **The CV wins on facts.** If this file and Sai's CV disagree on dates, employers or job titles, use the CV.
7. **Keep Sai's wording.** Lines in quotation marks are his words. Use them as written.
8. **Keep entries separate.** Never move a detail, number or result from one entry to another.
9. **Check `shareable` before anything goes public.** Wolf work may be confidential.
10. **Writing as Sai:** short, human, plain. Not "AI sounding". UK English, no em dashes.

## Fields

Two tiers. A field is left out when it does not apply; do not fill fields with "unknown" unless the gap needs flagging.

**Core fields: every entry**

| Field | What it holds |
|---|---|
| `name` | The entry's name, matching its heading |
| `type` | build, analysis, leadership, event or community |
| `period` / `last_updated` | When it happened, and when the entry was last checked |
| `source` | Where each fact came from: H = handoff section 8, CV = Resume_1.pdf, G = Georgia's notes 24 Oct |
| `proof` | What could prove it: link, letter, recording, screenshot, number, or none yet |
| `who_can_vouch` | People who could confirm it in writing |
| `shareable` | Can it be shown in public (posts, talks, visa evidence)? yes, no, or ⚠️ ask Wolf |
| `status` | `confirmed by Sai`, `on Sai's CV` (his wording, not checked), or ⚠️ to confirm |
| `one_line` | What it is, in one sentence |
| `lead_with` | The one result-first line to open with. Taken from his CV where possible |
| `my_part` | **The scope limit.** What Sai did himself, and what AI or others did |
| `outcome` | Results. Only claims here count as evidence |
| `note` | Optional. Anything that does not fit elsewhere, kept short |

**Optional on full entries (not minor ones):** `aka`, `best_for`, `tools`

**Story fields: the big four only** (Claude Vision agent, Wolf CRM, Lupa, Wolf BI Agent): `situation`, `stages`, `decisions`, `what_broke`, `what_i_learnt`, `what_id_do_differently`, `quotable_specifics`

`weight: minor` entries are short on purpose: core fields only, with `what_i_did` in place of `outcome` where easier.

# About Sai

- **Name:** Sai Praneeth S. London, UK. (H, CV)
- **Role:** Lead BI Engineer, sole technical hire, Wolf Group · Wolf Eyewear Ltd, London. Aug 2023 to present. (CV)
- **Company:** wholesale eyewear distributor; "£20M+ business" on CV, "£20M business" in his own words. (CV, H)
- **Scope:** sole technical owner of the data and AI stack; leads 4 offshore analysts; presents to the board and CEO. (H)
- **Strengths he leads with:** Python, production AI agents, AWS serverless, data pipelines, working directly with non-technical people. (CV)
- **Lighter on:** TypeScript and React; his CV lists TypeScript under "Learning". (CV, H)
- **Links:** GitHub github.com/Saipranoy (confirmed). LinkedIn linkedin.com/in/saipraneeth ⚠️ may be a placeholder.
- **Company size** ⚠️: "50-person" and "80 people" both appear; neither confirmed.
- **Education** ⚠️: possibly JNTU Hyderabad; degree unknown.
- **Joined as a contractor** ⚠️: said once by Claude; never confirmed.

## How Sai works

Drawn from his CV and the stories he used in interviews. ⚠️ Not yet in his own words; ask him to check it.

- **Talks to users before building.** The CRM started with 3 weeks of user research and 3 to 4 days on the road with sales reps. (H)
- **Builds the safety net early.** Alarm states and a sandbox for the CRM's maintenance agents were built before the product. (H)
- **Prefers flagging over guessing.** Both the order agent and Lupa flag low-confidence answers for a human rather than acting on them. (H)
- **Owns it end to end:** "designed the architecture, wrote the code, worked directly with customers and leadership to scope solutions, and owned whether it worked." (CV)

# Index

**At Wolf**
- **Claude Vision order ingestion agent:** reads supplier order PDFs and pushes lines into the ERP. 96% automation. Headline story.
- **Wolf CRM:** custom CRM built from scratch for sales and marketing. Main product-ownership story.
- **Lupa:** text-to-SQL agent so non-technical teams can ask the data questions in plain English.
- **Wolf BI Agent:** agent over a semantic data layer; accuracy about 40% to 82-83% after evals.
- **Data platform and ELT pipelines:** 11+ pipelines from Cin7, Xero, Shopify and Prospect CRM.
- **Postage cost analysis:** found a £54k+ annual cost gap; CEO approved the fix.
- **Wolf CMS (consignment app):** AWS serverless, event-driven app.
- **Leadership and stakeholders (weight: minor):** board presentations, AI roadmap, leads 4 offshore analysts.

**Outside Wolf**
- **olist-project-agentic:** public dbt + DuckDB + nao analytics agent with an eval suite. His only confirmed public proof.
- **Public talk on production LLM systems:** August 2026. Details unknown.
- **Flax × Founders Factory × AWS AI build sprint (weight: minor):** selected, application-only.
- **ivee MVP and Electron app:** built during a hiring process; led to a CTO technical call.
- **Circular Threads (weight: minor):** worked with a founder on seller journeys and mobile UX.
- **Community and events (weight: minor):** London AI builder events.
- **Bytes & Beyond (weight: minor):** unknown; possibly a podcast.
- **Other side projects (weight: minor):** Bug Burger Joint, Prompt Library.
- **Employer feedback (weight: minor):** what interviewers said about him.

---

# At Wolf

## Claude Vision order ingestion agent

- **name:** Claude Vision order ingestion agent
- **aka:** the order processor; "a Claude Vision tool"
- **type:** build
- **period:** unknown ⚠️
- **last_updated:** 2026-10-24
- **source:** H (Project 1); CV bullet 1
- **proof:** numbers only so far. No screenshot, demo or letter yet.
- **who_can_vouch:** unknown ⚠️ (whoever did the manual order processing before; his manager or CEO)
- **shareable:** ⚠️ ask Wolf
- **status:** on Sai's CV
- **one_line:** An AI agent that reads supplier and distributor purchase-order PDFs with Claude Vision, matches each line to the product catalogue, and pushes confirmed lines into the ERP via API.
- **lead_with:** "36/38 SKUs matched on first live test, 96% automation, task cut to under 5 minutes." (CV)
- **best_for:** shipping AI to production; evals and trust; "the best thing you've built"; turning a business pain into a product. **The headline story.**
- **tools:** Claude Vision (Claude API), Python, fuzzy matching against the catalogue, ERP API
- **my_part:** Built solo. His CV: "identified the customer pain (2-hr manual order processing), scoped the solution, built a Claude Vision agent ... deployed to production and owned it."
- **situation:** Processing order PDFs by hand took about 2 hours. How often it ran ⚠️: "multiple times a week", "every morning" and "every day" all appear.
- **stages:**
  - v1: parsed PDFs and matched SKUs, with no confidence threshold.
  - Problem found: wrong matches went through silently.
  - v2: added confidence scoring, so low-confidence matches are flagged for a human to review.
- **decisions:** Flag uncertain lines for a human rather than push them through.
- **what_broke:** v1 made confident but wrong matches with no warning. Fixed with the confidence layer. Failure modes he mapped: mixed PDF formats, handwritten notes on orders, non-standard SKU codes.
- **outcome:**
  - 36 of 38 SKUs matched on the first live test.
  - 96% automation.
  - A 2-hour manual task cut to under 5 minutes.
- **what_i_learnt:**
  - Confident but wrong extractions are worse than failures. (CV)
  - "Trust calibration." (H)
- **what_id_do_differently:**
  - Instrument it from day one.
  - Build the eval suite before the agent.
- **quotable_specifics:**
  - His own draft: "deploying production GenAI agents (like a Claude Vision tool with a 96% success rate)". ⚠️ Here he calls 96% a "success rate"; the CV calls it "automation". Check which is right.
  - He gave a public talk about this build in August 2026 ⚠️ (see that entry).

---

## Wolf CRM

- **name:** Wolf CRM
- **aka:** the CRM; "a custom CRM from scratch"
- **type:** build
- **period:** built in 4 to 5 weeks; live about 8 months as of October 2026 (so live since about February 2026 ⚠️ worked out, not stated)
- **last_updated:** 2026-10-24
- **source:** H (Project 4); CV bullet 3
- **proof:** usage numbers only. No screenshots, usage data or letters yet.
- **who_can_vouch:** Marketing Director and Product Director (named as stakeholders); sales reps who use it. Names unknown ⚠️
- **shareable:** ⚠️ ask Wolf
- **status:** ⚠️ to confirm (the saving and the running cost conflict across sources)
- **one_line:** A production CRM Sai built from scratch for Wolf's sales and marketing teams, replacing paid SaaS tools, with features off-the-shelf CRMs did not have.
- **lead_with:** ⚠️ hold until the saving is confirmed. Safe version with no money figure: "Built a full production CRM from scratch, saving 124 hrs/month." (CV wording, 27 Aug)
- **best_for:** product ownership; user research before building; cost saving; production engineering; owning something real users rely on every day. **The main product-ownership story.**
- **tools:** Python backend; Flask, moved to ECS Fargate; ECR; DynamoDB (12 tables); API Gateway; Microsoft Entra SSO; Terraform; GitHub Actions; OpenRouter; Outlook integration
- **my_part:** Built solo, from research to production. The TypeScript MCP server was built with AI: "the typescript mcp was built by ai". Do not claim TypeScript fluency from it.
- **situation:** Sales and marketing ran on SaaS tools that cost money and did not fit how Wolf works, especially consignment.
- **stages:**
  - Discovery: 3 weeks of user research before coding, including 3 to 4 days on the road shadowing sales reps. 42 distinct problems gathered.
  - Build: 4 to 5 weeks.
  - Moved from Lambda to ECS Fargate, because bulk consignment submissions hit Lambda's 15-minute timeout. Switched to bulk API calls instead of one call per line.
  - After interview feedback from CoLoop, explored queueing and moved to OpenRouter with priority-based requests.
  - Added maintenance agents (see outcome).
- **decisions:**
  - Research first, code second.
  - Build consignment in, because market CRMs did not offer it.
  - Mandatory data capture at order entry (asked for by the Product Director).
  - Campaign attribution (asked for by the Marketing Director).
- **what_broke:** Lambda timed out on bulk consignment submissions. Fixed by moving to ECS Fargate and batching API calls.
- **outcome:**
  - 50+ daily users ⚠️ (his CV now uses "50+" for Wolf CMS locations; check this is the CRM figure).
  - 4,000 customers and 11,000 leads in the system.
  - 124 hours a month saved across the sales team.
  - Zero training required.
  - Consignment covers 20% of business volume. Context ⚠️: "200 customers, 50 products each".
  - Other features: offline and parked orders, Germany lead tracking, launch scheduling, Outlook integration, bug reporting, PDF output.
  - Maintenance agents: 8 Grok bots handle 20+ issues a week. Bug report → GitHub issue → triage agent → pull request → Sai reviews each morning (about 8am). Agents can only work on branches (CLAUDE.md policy).
  - CRM MCP server (TypeScript, built with AI): lets AI agents read CRM data with Microsoft sign-in and permission checks. His CV says it is "in progress on GitHub" ⚠️ link unknown.
- **The saving: six versions, do not pick one** ⚠️

  | Version | Where it appeared |
  |---|---|
  | "replacing £45k/year of SaaS tools" | CV bullet, 27 Aug; CoLoop notes |
  | "Salesforce, £25K/year" | October |
  | "$25K subscription" | ivee CTO call |
  | "£20-25k in SaaS subscriptions" | Rig notes |
  | "£20k I saved" | His own draft for Plain |
  | "save operationally £10k+ and financially £40k+ annually" | Resume_1.pdf (latest CV) |

- **Running cost: three versions, do not pick one** ⚠️

  | Version | Where it appeared |
  |---|---|
  | "$100/month" | CV; CoLoop technical; ivee CTO call |
  | "$5/month" | CoLoop screening |
  | "£700-800/year" | Rig notes |

- **what_i_learnt:** unknown ⚠️ (ask Sai)
- **what_id_do_differently:**
  - Use RDS instead of DynamoDB.
  - Use IndexedDB for offline orders instead of local storage.
- **quotable_specifics:**
  - "my crm uses ecs and fargate"
  - "building a custom CRM from scratch" (his Plain draft)

---

## Lupa

- **name:** Lupa
- **aka:** the text-to-SQL agent
- **type:** build
- **period:** unknown ⚠️
- **last_updated:** 2026-10-24
- **source:** H (Project 2); CV bullet 5
- **proof:** none yet. The ~60% figure may be an estimate.
- **who_can_vouch:** users in Finance, Sales and Ops. Names unknown ⚠️
- **shareable:** ⚠️ ask Wolf
- **status:** on Sai's CV (the ~60% figure is ⚠️ to confirm)
- **one_line:** A production AI agent that lets non-technical teams (Finance, Sales, Ops) ask the data warehouse questions in plain English.
- **lead_with:** "Built Lupa a production text-to-SQL AI agent; worked with users to understand how they actually asked questions." (CV)
- **best_for:** AI products for non-technical users; iterating from real usage; adoption.
- **tools:** LLM text-to-SQL, SQL validation layer, the data warehouse
- **my_part:** Built solo.
- **stages:**
  - Built the prompt architecture, SQL generation and a validation layer.
  - Ran structured experiments on ambiguous questions.
  - Added a confidence layer that flags uncertain queries rather than running them.
  - Iterated on real usage and drove adoption across teams. (CV)
- **decisions:** Flag rather than execute when unsure.
- **outcome:** Ad-hoc data requests down about 60% ⚠️ (Claude flagged this as an estimate early on: "swap the ~60% estimates for actuals").
- **what_i_learnt:** unknown ⚠️

---

## Wolf BI Agent

- **name:** Wolf BI Agent
- **type:** build
- **period:** unknown ⚠️
- **last_updated:** 2026-10-24
- **source:** H (Project 3); CV bullet 6
- **proof:** accuracy numbers from his evals. Eval results themselves not seen.
- **who_can_vouch:** unknown ⚠️
- **shareable:** ⚠️ ask Wolf
- **status:** on Sai's CV (accuracy numbers ⚠️ to confirm)
- **one_line:** An agent built on the nao agentic framework that answers business questions over a semantic SQL layer, with tool use, MCP integrations and an eval suite.
- **lead_with:** ⚠️ not on CV as a number. Candidate once confirmed: accuracy from about 40% to 82-83% after an eval and context-refresh loop.
- **best_for:** evals; agent architecture; improving an AI system with measurement.
- **tools:** nao, semantic SQL views, MCP, GitHub Actions
- **my_part:** Architected and built it; "evaluated with structured test sets, drove adoption, and maintained in production". (CV)
- **stages:**
  - Built the agent over a semantic SQL view layer.
  - Built an eval suite.
  - Added a GitHub Actions pipeline that turns low-rated answers into tickets.
  - Added a context-refresh loop.
- **outcome:** Accuracy about 40% → 82-83%. ⚠️
- **what_broke:** Static markdown context files go stale. He acknowledges this as a known limit.

---

## Data platform and ELT pipelines

- **name:** Data platform and ELT pipelines
- **type:** build
- **period:** Aug 2023 onwards ⚠️ (start date assumed from his start at Wolf)
- **last_updated:** 2026-10-24
- **source:** H (Data platform); CV bullet 7
- **proof:** none yet
- **who_can_vouch:** CFO or finance team (Xero data); the 4 offshore analysts ⚠️
- **shareable:** ⚠️ ask Wolf
- **status:** on Sai's CV (the ~200 hours figure is ⚠️ an estimate)
- **one_line:** The data platform Sai built and runs at Wolf: 11+ ELT pipelines bringing ERP, finance, ecommerce and CRM data together for reporting.
- **lead_with:** "Built 11+ ELT pipelines integrating Cin7, Xero (accounting & financial data), Shopify & Prospect CRM owned from design through deployment, monitoring, and maintenance." (CV)
- **best_for:** data engineering roles; owning infrastructure end to end; governance.
- **tools:** Peliqan, dbt-style staging to mart patterns, DuckDB, PostgreSQL, Lightdash, Power BI
- **my_part:** Built and owns it. Leads 4 offshore analysts (their part unknown ⚠️).
- **outcome:**
  - 11+ pipelines: Cin7 (ERP and inventory), Xero (finance), Shopify (ecommerce), Prospect CRM.
  - About 200 hours a month of manual reporting removed ⚠️ (estimate).
  - Green, Yellow and Red governance framework.
  - CI/CD and code-review standards.
- **note:**
  - dbt: at Wolf he uses dbt-style staging to mart patterns on Peliqan. Native dbt comes from his olist side project. Describe it that way.
  - Airflow: "surface-level only" (his words).

---

## Postage cost analysis

- **name:** Postage cost analysis
- **aka:** the £54k saving; the carrier switch
- **type:** analysis
- **period:** unknown ⚠️
- **last_updated:** 2026-10-24
- **source:** H (Data platform); earlier CV version
- **proof:** none yet. A before and after carrier invoice comparison would prove it.
- **who_can_vouch:** CEO (approved it)
- **shareable:** ⚠️ ask Wolf
- **status:** ⚠️ to confirm (not on the latest CV)
- **one_line:** A data analysis of postage and carrier costs that found a £54k+ annual cost gap, which the CEO approved fixing with a carrier switch.
- **lead_with:** ⚠️ candidate: "Found a £54k+ annual cost gap through data analysis; CEO approved; implemented company-wide."
- **best_for:** business impact from data; influencing leadership.
- **outcome:**
  - £54k+ annual cost gap found.
  - CEO approved; carrier switched.
  - "and two promotions" ⚠️ meaning unknown.
- **note:**

---

## Wolf CMS (consignment app)

- **name:** Wolf CMS (consignment app)
- **aka:** Wolf CMS; "a production consignment management app"
- **type:** build
- **period:** unknown ⚠️
- **last_updated:** 2026-10-24
- **source:** H (Data platform); CV bullet 2; CV projects
- **proof:** none yet
- **who_can_vouch:** unknown ⚠️
- **shareable:** ⚠️ ask Wolf
- **status:** on Sai's CV ⚠️ (see the question below)
- **one_line:** A production AWS serverless, event-driven app for consignment management, built with idempotency safeguards.
- **lead_with:** "Built event-driven backend systems on AWS ... for a production consignment management app handling 50+ locations daily." (CV)
- **best_for:** backend and cloud engineering; reliability.
- **tools:** AWS Lambda, SQS, DynamoDB, S3, API Gateway
- **my_part:** Built solo.
- **outcome:**
  - Lambda functions triggered by SQS queues, DynamoDB state store, API Gateway entry point.
  - Idempotency safeguards and async processing throughout.
  - Handles 50+ locations daily ⚠️.
- **Question:** ⚠️ Is Wolf CMS the same as the CRM's consignment feature, or a separate app? The CRM moved off Lambda to Fargate; this app is described as Lambda-based. Keep them separate until Sai says.

---

## Leadership and stakeholders

- **weight:** minor
- **name:** Leadership and stakeholders
- **type:** leadership
- **last_updated:** 2026-10-24
- **source:** H (Role); CV bullet 4
- **proof:** none yet. Board papers or a letter from the CEO would prove it.
- **who_can_vouch:** CEO, CFO
- **shareable:** ⚠️ ask Wolf
- **status:** on Sai's CV
- **one_line:** Sai works directly with the CEO, CFO, Sales and Ops, presents AI strategy to the board, and leads 4 offshore analysts.
- **what_i_did:**
  - "presented AI strategy and technical roadmap to the board" (CV)
  - "translated messy business problems into clean, reliable software" (CV)
  - Leads 4 offshore analysts (H).
  - A disagreement story with a colleague (Sophie) ending in a 70/30 automation split ⚠️ details unknown.

---

# Outside Wolf

## olist-project-agentic

- **name:** olist-project-agentic
- **type:** build
- **period:** unknown ⚠️
- **last_updated:** 2026-10-24
- **source:** H; CV projects
- **proof:** public repo, github.com/Saipranoy/olist-project-agentic (confirmed)
- **who_can_vouch:** n/a (public code)
- **shareable:** yes
- **status:** on Sai's CV
- **one_line:** A public analytics project: dbt + DuckDB + Lightdash with a nao analytics agent on top, a semantic SQL layer, MCP integrations, an LLM eval suite and source freshness checks.
- **lead_with:** "Public dbt + DuckDB + nao analytics agent; semantic SQL layer, MCP integrations, and LLM eval suite." (CV)
- **best_for:** public proof of skill; native dbt; evals. **His strongest public evidence today.**
- **tools:** dbt, DuckDB, Lightdash, nao, MCP
- **my_part:** unknown ⚠️ (assumed solo)

---

## Public talk on production LLM systems

- **name:** Public talk on production LLM systems
- **type:** event
- **period:** August 2026 ⚠️
- **last_updated:** 2026-10-24
- **source:** H; CV bullet 8
- **proof:** none yet. Recording, slides, event page or photos would prove it.
- **who_can_vouch:** the event organiser ⚠️
- **shareable:** yes, if a recording or event page exists
- **status:** on Sai's CV (event name, date and link ⚠️ unknown)
- **one_line:** A public talk on running LLM systems in production, about the Claude Vision order agent.
- **best_for:** public speaking; recognition outside Wolf; visa evidence.
- **outcome:** unknown ⚠️ (audience size, event, feedback)

---

## Flax × Founders Factory × AWS AI build sprint

- **weight:** minor
- **name:** Flax × Founders Factory × AWS AI build sprint
- **type:** event
- **last_updated:** 2026-10-24
- **source:** CV bullet 8; H
- **proof:** none yet. Acceptance email would prove it.
- **shareable:** yes
- **status:** on Sai's CV
- **one_line:** "Selected (application-only) for Flax × Founders Factory × AWS AI build sprint." (CV)
- **what_i_did:** unknown ⚠️ (what he built, any result)

---

## ivee MVP and Electron app

- **name:** ivee MVP and Electron app
- **type:** build
- **period:** October 2026
- **last_updated:** 2026-10-24
- **source:** H
- **proof:** live Claude artifacts in Sai's account; an app zip. Links ⚠️ unknown.
- **who_can_vouch:** ivee's CTO (held the technical call after the demo) ⚠️ consent needed
- **shareable:** ⚠️ ask Sai (built for a hiring process)
- **status:** ⚠️ to confirm
- **one_line:** Two builds made during ivee's hiring process: an MVP (AI ROI calculator, Prompt Improver and a decision model) and a desktop AI Readiness Assessment app.
- **best_for:** showing initiative in a hiring process; building in someone else's design language.
- **my_part:** ⚠️ The Electron app was "built with Claude". How much Sai wrote himself is unknown.
- **note:**
  - MVP: AI ROI calculator, Prompt Improver, and a decision model (7 roles × 3 confidence bands), in ivee's design language.
  - Demoed at ivee's speed-hiring event, 12 Oct 2026.
  - Electron app: AI Readiness Assessment (10 questions, score ring, 3 tiers, export), around 20 Oct 2026.
- **outcome:** The demo led to a CTO technical call (20 Oct 2026). Outcome of the process ⚠️ unknown.

---

## Circular Threads

- **weight:** minor
- **name:** Circular Threads
- **type:** build
- **last_updated:** 2026-10-24
- **source:** H
- **proof:** none yet. A note from the founder would prove it.
- **who_can_vouch:** the founder (Anoli)
- **shareable:** ⚠️ ask Sai
- **status:** ⚠️ to confirm (whether unpaid or "voluntary" is Claude's wording)
- **one_line:** Worked with the founder of Circular Threads on seller journeys, mobile UX and notifications, from mockups to build to test.

---

## Community and events

- **weight:** minor
- **name:** Community and events
- **type:** community
- **last_updated:** 2026-10-24
- **source:** H; CV bullet 8
- **proof:** none yet
- **shareable:** yes
- **status:** ⚠️ to confirm
- **one_line:** Active in the London AI builder and startup scene.
- **what_i_did:**
  - Events: AI Builders meetups, AWS GenAI Day, a Lightdash event, BrainFest (12 Aug 2026), CoLoop Saturday coworking.
  - LinkedIn: 1,417 followers and 500+ connections (June 2026). Posts ⚠️ links unknown.
  - Interested in becoming a talent investor.

---

## Bytes & Beyond

- **weight:** minor
- **name:** Bytes & Beyond
- **type:** community
- **last_updated:** 2026-10-24
- **source:** H (named by a CTO in interview feedback)
- **proof:** none
- **status:** ⚠️ to confirm (Claude called it a podcast; not confirmed)
- **one_line:** unknown ⚠️ Ask Sai what it is.

---

## Other side projects

- **weight:** minor
- **name:** Other side projects
- **last_updated:** 2026-10-24
- **source:** H
- **status:** ⚠️ to confirm, both
- **what_i_did:**
  - Bug Burger Joint: unpaid consulting ⚠️ no detail.
  - Prompt Library (FastAPI + asyncpg) ⚠️: Claude scaffolded it on 11 Oct 2026. Do not list it unless Sai confirms he built and ran it.

---

## Employer feedback

- **weight:** minor
- **name:** Employer feedback
- **type:** community
- **last_updated:** 2026-10-24
- **source:** H (paraphrased from his notes)
- **proof:** emails and call notes in Sai's accounts
- **shareable:** ⚠️ needs Sai's consent before it goes in anything shared
- **status:** ⚠️ to confirm
- **one_line:** What hiring teams said about him in 2026. Useful for strengths and for his development plan.
- **what_i_did:**

  | Company | Furthest stage | What they said (paraphrased) |
  |---|---|---|
  | Rig | 2 founder interviews | Great, but client experience was internal; wanted more external client work |
  | CoLoop | Screen, 2-hour technical, code fluency | Continue: close to users, acts on feedback fast. Start: lean in when code feels unfamiliar |
  | Tano | CTO, CEO, final system design | Problem-focused, strong shipper; needed more production engineering depth |
  | Huel | Personal reply from Data Director | Stack and senior-team mentoring gap; "keep an eye out" |
  | Orchestra | CTO replied within 13 minutes | Needed more specific experience |

- **Gaps employers named:** Snowflake, Fivetran or BigQuery; TypeScript, React or frontend; external client-facing work; leaning into unfamiliar code; production engineering depth (storage choices, scheduling, failure handling).

---

# Skills (self-rated, from CV)

⚠️ These are Sai's own ratings. Fine for a CV. For a visa, they need outside proof.

- **Python:** "Expert" · FastAPI, boto3, pandas, Streamlit, requests
- **AI and agents:** Claude API, Anthropic SDK, OpenAI API, MCP servers, RAG ⚠️ (no RAG project recorded), tool use, agent orchestration, nao, evals
- **Cloud:** AWS (Lambda, SQS, DynamoDB, S3, API Gateway), serverless, event-driven, Docker, Git, CI/CD
- **Data:** SQL ("expert"), dbt, DuckDB, PostgreSQL, ELT pipeline design, Peliqan, Lightdash, Power BI
- **Learning:** TypeScript

---

# Notes for later: visa

Not legal advice. Recorded now so nothing is lost; to be worked on later with an OISC-regulated adviser or a solicitor.

- **Current visa:** Skilled Worker, employer sponsored. (CV, G)
- **Goal:** a visa his employer does not have to pay for or sponsor. (G)
- **Age:** 28. **Time in the UK:** about 5 years. **Salary:** unknown. (G)
- **Routes to look at later:** Global Talent, a tech route, or a founder route. None chosen. (G)
- **Keep in mind:**
  - Which visas he has held over the 5 years, and whether that time counts towards settling. ⚠️
  - His visa expiry date. ⚠️
  - Most of his strongest proof is internal to Wolf. Visa evidence usually needs things others can see: write-ups, recordings, letters, outside recognition. Every Wolf entry has a `shareable` flag for this.
  - Would his CEO write a letter? ⚠️

---

# Questions for Sai

Send this as one list. Short answers are fine.

**Big ones**
1. CRM saving: which is right? £45k/year, £25k/year (Salesforce), £20-25k, £20k, or "£10k+ operationally and £40k+ financially"? How was it worked out?
2. CRM running cost: $100/month, $5/month or £700-800/year?
3. Lupa's ~60% fewer data requests, and ~200 hours a month of reporting removed: measured or estimated?
4. What can you show publicly from Wolf (screenshots, write-ups, demos)? Would your CEO write you a letter?
5. Are you OK with interview feedback and company names being in this file?

**Wolf work**
6. Order agent: how often does it run? Is 96% "automation" or "success rate"? When did it go live?
7. Is Wolf CMS the same thing as the CRM's consignment feature, or a separate app?
8. Is "50+" daily CRM users, or Wolf CMS locations, or both?
9. Postage: what were the "two promotions"? Why is the £54k result off your latest CV?
10. Wolf BI Agent: is about 40% to 82-83% accuracy right? How was it measured?
11. Who could vouch for each Wolf project in writing?
12. What did you learn from building the CRM?
13. Is the "How Sai works" section right? Want to put it in your own words?

**Outside Wolf**
14. August talk: event name, date, link or recording?
15. AWS build sprint: what did you build, and any result?
16. What is Bytes & Beyond? Any links?
17. Did you build and run the Prompt Library, or only get Claude's scaffold?
18. Links to the ivee MVP, the CRM MCP server on GitHub, and your LinkedIn posts?
19. Is linkedin.com/in/saipraneeth your real LinkedIn?

**About you**
20. Degree and university?
21. Wolf company size: 50 or 80 people? Did you join as a contractor?
22. Have you used RAG in a real project? Where?
23. Which visas have you held since you came to the UK, roughly when, and when does your current one expire? (For later; no need to rush.)

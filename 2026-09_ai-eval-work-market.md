# The AI-evaluation work market, September 2026

Platforms that pay for AI training and evaluation work, the tooling where the
methodology actually gets done, and what the market has failed to build for the
people doing the work.

**Compiled:** September 2026 · **Freshness window:** roughly March–September 2026
· **Lens:** relevance to a practitioner working from the EU / Poland · every claim
carries a confidence level · PROMISED (platform claim) and OBSERVED
(contributor-reported) are kept separate · rates are given as ranges, not points.

---

## 0. Method and caveats (read first)

**Source categories:**

- **A** — platforms with paid tasks (earning work: training / evaluating models)
- **B** — tools and benchmarks (where evaluation methodology is designed; mostly
  unpaid — a workbench, not an employer)
- **C** — forums and communities (real-time signal on platform state; strong bias)
- **D** — job aggregators and paid red-teaming channels

**Bias that cannot be averaged out (stated plainly):**

1. Forums (Reddit `r/OutlierAI`, `r/dataannotation`, TeamBlind) **over-represent
   complaints** — satisfied workers do not post.
2. Review blogs, the source of roughly 70% of public pay-rate data
   (careerseeker.ai, remowork.life, breakingeven.online, gigdrift.io, skillora.ai,
   the aitrainingjobs.* cluster, aigigjobs.com), are **affiliate SEO content**.
   Their numbers sit closer to PROMISED than to OBSERVED. Sentiment analyses
   quoted from them ("1,654 discussions, 55% negative") are therefore
   **second-hand**.
3. Primary sources, used wherever available: Labelbox Help Center, the UK AI
   Safety Institute, Gray Swan Arena, Prolific researcher help, the Scale AI blog,
   restofworld.org, the Mercor breach court filings and law-firm briefings,
   company press releases (OpenAI, Dynatrace), Wikipedia (Scale AI).

**Confidence convention:** High = primary source or ≥3 independent · Medium =
several affiliate reviews in agreement · Low = single source or forum sentiment.

**Query log:** ~27 searches (18 positive, 6 negative — "scam / not paying /
deactivated / banned / complaints", 3 geo / Poland). Full list in Appendix B.

---

## 1. Category A — platforms with paid tasks

### 1a. Generalist / microtask tier (accessible from the EU, lower rate)

| Platform | Who runs it | Entry | Rate PROMISED | Rate OBSERVED (median + notes) | Stability | Geo / EU | Solvency | Confidence |
|---|---|---|---|---|---|---|---|---|
| **Outlier** | Scale AI (brand "Smart Ecosystems"); Scale contracting after the ~49% Meta deal and the OpenAI / Google client exodus | associate degree minimum, some projects BA/MA/PhD; qualification test | $10–60/h | generalist EN **$15–22/h**; code / STEM / bilingual $30–50; niche languages ~$8/h. Effective rate lower after unpaid screening and "task hunting" | **Low** — "volatility" is the most common complaint; queues empty without warning | global; no hard EU/PL detail; rate is location-dependent | Legit, pays — **but mass deactivations** ("unauthorized tools", "duplicate account") with no evidence and no appeal; support 7+ days | High |
| **Mindrift** | Toloka (Yandex spin-off, 2020, Amsterdam) — the expert-facing front of the same company | 70% of contributors MA/PhD; 90+ domains; expert profile | $15–100+/h | generalist ~$20–30/h; STEM / law / medical specialist ~$50–90/h; open-eval tasks cents to a few $ each. **2026: shift to fixed-price** → $15 for a task that takes 3h = $5/h | Medium, project-based | global; Payoneer / Tipalti, twice monthly (5th and 20th), no threshold — **good for the EU** | Legit, pays | High |
| **Toloka** (direct) | Toloka (Yandex spin-off, 2020, Amsterdam) — microtask front | low | $2–10/h | **$2–3/h** typical; per-task $0.01–1.00; rare $10–20 specialist | Low | Payoneer / Papara — **EU OK** | 10+ years of payouts, legit; very low rates | High |
| **DataAnnotation.tech** | tied to the Surge AI ecosystem (applying to Surge often routes through DA) | simple form, but the real filter is a test + coding tasks | $20–40/h (code / STEM $50–100+) | generalist effectively **$14–20/h** after an unpaid assessment and dry spells; realistically $150–600/month | **Low** — "flood, then weeks near zero" | PayPal weekly; historically US-centric, EU variable — **low confidence for the EU** | Legit; >$20M paid out; Indeed 3.7/5 (700+) | Medium |
| **Clickworker** | Clickworker GmbH (Essen, DE, since 2005) | registration + assessments (UHRS = a Microsoft system) | — | without UHRS $3–7/h; with UHRS $8–14/h; **US/UK/CA/DE + UHRS passed: $12–18/h** | Medium | DE-based → **good EU/PL handling**; 140+ countries | Legit, "paid millions" | Medium |
| **OneForma** | Pactera EDGE | registration; long wait for a project to start | — | translation $0.03–0.10/word; transcription $0.50–1.25/audio min; annotation **$7–13/h** | Low (long ramp) | global | Legit, mid-tier | Low |
| **Appen / CrowdGen** | Appen (public company, in decline) | registration | — | annotation ~$7–13/h | Low | global | Legit, but the market is contracting | Low |
| **Prolific** | Prolific Academic Ltd (Oxford, UK) | participant registration; demographic matching | enforced minimum £6/h (recommended £9 / $12) | realistically **£6–12/h**; studies appear at random by fit | Low (not worker-controlled) | **EU/PL OK** (GBP/USD), PayPal | Legit, academic lineage; clients = universities + labs | High |

### 1b. Expert tier ($40–200/h) — credential-gated, mostly US-first

| Platform | Who runs it | Entry | Rate OBSERVED | Stability | Geo / EU | Solvency / risk | Confidence |
|---|---|---|---|---|---|---|---|
| **Mercor** | Mercor Inc. (SF, ~$10B valuation 2025); serves OpenAI, Anthropic, Meta | profile + CV + a one-way **20-min AI interview**; a minority pass | $40–150/h, weekly payout | Medium | global | **MAJOR CAVEAT: data breach, 24–30 March 2026** via a poisoned `LiteLLM` supply-chain update — **40,000+ people**; exposed: interview video + **facial biometrics**, ID documents, background-check and tax / bank data, device screenshots, plus ~939 GB of client source code and API keys (~4 TB total). Class action filed 1 April 2026 (N.D. Cal.), further suits followed. **Meta paused its work with Mercor indefinitely; OpenAI said it was reviewing the incident but did not pause.** | High |
| **Micro1** | Micro1 (2021, pivoted from AI recruiting to an expert pipeline) | interview / skill assessment; shortens later rounds on fresh results | $40–150/h; the broadest catalogue (generalists + SMEs) | Medium; young | global | Growing fast (~2× revenue); fewer documented complaints than Handshake / Alignerr, but a short track record | Medium |
| **Handshake AI** | Handshake (US university job network); AI arm since 2025 | university network + verified academic credentials; "Fellowship" | PROMISED $60–125/h — the highest floor of any tracked platform; **OBSERVED: a 2026 "payment crisis"** — Project HH rate cuts, payment delays of 30–45 days against a 7–14 day standard, weekly earnings caps, silent offboardings | **Low** — per an aggregator's analysis of ~1,650 Reddit threads (Jun–Aug 2026), ~55% negative; top complaint categories reported as payments, technical issues, empty queues, deactivation. *This breakdown is a second-hand figure from affiliate material; treat as directional.* | US-first (US university network) | Legit, but payout reliability is the open question | Medium |
| **Turing** | Turing (vetted technical teams) | coding screen (filters out non-engineers) | $60–150/h for SWE | Medium | global | Legit; narrowly code / STEM | Low |
| **Surge AI** | Surge AI (independent; took RLHF share after the Scale client exodus) | **invite-only / application**; highly selective; not for beginners | not published; above microtask; Research Fellowship (CV to fellowship@surgehq.ai) | side income, not primary | — | Legit | Medium |
| **Alignerr** | Labelbox (contributor-facing brand) | application + assessment | variable; some projects **pay-per-approved-task** → unreviewed work = unpaid work | **Worst of the tier** — months between projects, evaluations frequently unpaid | — | Operationally legit, **but**: documented deactivations before payout (e.g. a contributor removed from all projects by five emails on 7 May 2026, performance history deleted); independent non-payment reports of $800–3,000+ (one itemised at $3,240 for 18 tasks under "on completion" terms); Glassdoor and BBB complaints echo the pattern. Community-discussion analysis puts deactivation / technical / payment mentions at roughly 77 / 69 / 46 — a second-hand count. | High |

### 1c. Sunsetting channel

**Remotasks** (Scale AI) — not shut down (site is live), but new sign-ups are
routed to Outlier; in 2024 it cut off entire countries (Kenya, Nigeria, Pakistan)
without notice. Treat as wind-down.

---

## 2. Category B — tools and benchmarks (a workbench, not an employer)

| Tool | What it is | Who runs it | Status 2026 | Maturity | Confidence |
|---|---|---|---|---|---|
| **Inspect AI** | framework for frontier evaluation (capability + safety) | **UK AISI** + Meridian Labs; open-source | de facto standard for safety evals; used by AISI, Anthropic, DeepMind, xAI, Apollo, METR; required by the UK AISI Autonomous Systems Evaluation Standard; 50+ external contributors | High | High |
| **promptfoo** | open-source CLI: local eval + red-team, declarative config, pre-deployment | promptfoo; **OpenAI announced an acquisition on 9 March 2026** — technology to be integrated into "OpenAI Frontier" after close; open-source offering to continue. ~130k monthly active users, 25% of the Fortune 500 | leading pre-deploy tool | High | High |
| **DeepEval** | pytest-style test framework for LLM apps; 50+ metrics (G-Eval, hallucination, relevancy, faithfulness) | Confident AI; open-source | one of three dominant OSS options (with promptfoo + RAGAS) | High | Medium |
| **RAGAS** | RAG-specific evaluation | open-source | the RAG standard | High | Medium |
| **Braintrust** | SaaS: eval scoring + production tracing + dataset management + CI gating | Braintrust Data | commercial leader in "end-to-end evals" | High | Medium |
| **LangSmith** | observability + eval, lowest friction with LangChain / LangGraph | LangChain | mature; tied to the LangChain ecosystem | High | Medium |
| **Langfuse** | open-source observability leader; self-hostable (Postgres + ClickHouse), framework-agnostic | Langfuse | March 2026: new data model, 10×+ dashboard performance | High | Medium |
| **Arize Phoenix** | evaluation rigour, OTel-native tracing | Arize AI — **Dynatrace signed a definitive agreement to acquire Arize on 13 August 2026, ~$915M ($815M cash + equity); close expected in Dynatrace's Q3 2026, pending regulatory review** | strong in agent-era evals | High | Medium |
| **Chatbot Arena / "Arena"** (formerly LMArena / LMSYS) | public A/B voting on anonymous models → leaderboards | Arena Intelligence (UC Berkeley lineage); **rebranded 28 January 2026** | the most-watched public leaderboard; separate boards for text, code, vision, docs, search, image gen/edit, video | High | High |
| **HELM** | independent harness for checking lab-reported benchmark numbers | Stanford CRFM | the "check whether the lab is inflating" standard | High | High |

**Who this is for:** this is where an AI-evaluation specialist / model-behaviour
analyst actually designs methodology. The problem: **none of these tools has an
earning channel for a freelancer** — see gap #7.

---

## 3. Category C — forums and communities (signal + bias)

| Source | Useful for | Warning |
|---|---|---|
| **r/OutlierAI**, **r/dataannotation** (Reddit) | the liveliest real-time signal on queue state, deactivation waves, specific projects (e.g. "Project HH"), payout practice | complaint over-representation; brigading; some affiliate accounts |
| **TeamBlind** | insider discussion of Scale, the "scam" perception, conditions | anonymous, unverifiable |
| **Trustpilot / Indeed / Glassdoor** | aggregate ratings (Outlier 12k+ reviews, Indeed 3.7/5 for DA) | mixed with marketing and paid reputation management |
| **Review blogs** (careerseeker, remowork, breakingeven, gigdrift, skillora, the aitrainingjobs.* cluster, aigigjobs, theairankings) | the only place with collected "pay bands" and comparisons | **affiliate SEO content** — rates skew to PROMISED; sentiment analyses are second-hand |

---

## 4. Category D — job aggregators + paid red-teaming channels

| Source | Type | Notes | Confidence |
|---|---|---|---|
| **aigigjobs.com** | pay-band aggregator across 10+ platforms | the most data-driven of the three aggregators | Medium |
| **aitrainingjobsfinder.com** | platform + pay-band aggregator | **openly takes referral commissions** | Low |
| **aitrainingjobs.it** | curated platform list | SEO content | Low |
| **getaiwork.com** | comparisons ("Outlier alternatives" etc.) | useful for mapping, not for numbers | Low |
| **opentrain.ai/jobs** | remote AI training / eval / labeling listings | less affiliate-driven | Low |
| **WeWorkRemotely / Arc.dev / Indeed / Glassdoor** | general remote job boards | "prompt engineering & evaluation" roles (FT/PT), e.g. $43–62/h remote; ~45% of prompt-eng listings are remote | Medium |
| **Gray Swan Arena** | red-teaming contests with prize pools | **a real paid channel**: an Agent Red-Teaming pool of $171,800; a Safeguards pool of $140k; sponsors include the UK AISI, OpenAI, Anthropic, DeepMind, Meta, Amazon, Google; payouts 2–4 weeks after close | High |
| **Lab bug bounties** (OpenAI, Anthropic, xAI/Grok) | payment for real findings | five figures for significant findings; irregular | High |
| **Anthropic Fellows / consultancies (Apollo, METR, Trail of Bits, Lakera)** | a route into lab red-teaming | competitive / closed; not a "platform" | Medium |

---

## 5. The 8 reference roles — where the work actually is

| Role | Where the work is (cat. A) | Workbench (cat. B) | Realistic EU rate |
|---|---|---|---|
| 1. AI trainer / data annotator (generalist) | Toloka, Clickworker, OneForma, Outlier (gen), Mindrift (open-eval) | — | $3–22/h |
| 2. RLHF / preference rater | Outlier, Surge, DataAnnotation, Mindrift | — | $15–30/h gen; $40–90/h premium (rare from the EU) |
| 3. Red-teamer / AI safety tester | **Gray Swan Arena**, bug bounties, (consultancies — closed) | promptfoo (red-team), Inspect | a lottery: $0 or 4–5 figures; no base rate |
| 4. Domain expert reviewer (STEM / code / medical / legal) | Mercor, Micro1, Handshake, Mindrift (specialist) | — | $40–150/h **if** you clear the credential gate |
| 5. Prompt engineer | DataAnnotation, Outlier; FT roles on WWR / Arc / Indeed | promptfoo, DeepEval, Braintrust | $43–62/h remote (FT); gig lower |
| 6. AI evaluation specialist / model-behaviour analyst | **no dedicated gig channel** — either a lab job or the generalist platform tier | **Inspect, promptfoo, DeepEval, Arena, HELM** | a gap — see #5 / #7 |
| 7. Coding-task contributor (SWE data) | Turing, Mercor, Micro1, DataAnnotation (code), Outlier (code) | SWE-bench (benchmark) | $50–150/h after a coding screen |
| 8. Multilingual / localization rater | OneForma, Toloka, Clickworker, Mindrift (linguistics), Outlier (languages) | — | $7–20/h; niche languages lower |

---

## 6. Gap analysis — what the market has not built for the worker

Derived from the matrix above, not from opinion. Ordered by how sharply it bites a
practitioner with real AI-eval competence but no domain PhD, working from the EU.

**1. No independent, transaction-verified solvency register.** The entire "rating"
ecosystem is affiliate SEO plus complaint-biased forums. There is no equivalent of
a "Glassdoor verified by payslips": median time-to-payment, deactivation rate per
platform, share of unpaid onboarding. This is precisely the dimension anyone
evaluating these platforms has to reconstruct by hand, because nobody maintains
it.

**2. No protection against unilateral deactivation.** A repeating pattern at
Outlier / Alignerr / Handshake: the account disappears with no evidence, no
appeal, often just before a payout. Missing: payout escrow, arbitration, a "right
to explanation" standard. There is a product niche here (escrow-as-a-service for
AI gig work) and a regulatory one (the EU Platform Work Directive could plausibly
attach — nobody has pushed it for this segment).

**3. The PROMISED↔OBSERVED gap is structural.** Marketing says "$15–100/h",
"$40–200/h". The generalist median is $14–22/h after unpaid screening, task
hunting, and (Mindrift, 2026) a shift to fixed-price. There is no obligation to
publish an **effective rate** (payout ÷ hours logged) per project. Nobody computes
it openly.

**4. Unpaid onboarding is the norm.** Assessments and qualification tests are
hours of work before the first dollar, at rejection rates of 60–90%. It is a
transfer of risk onto the worker. There is no "paid trial" standard.

**5. The expert tier is gated by credential, not skill.** "Your rate is the
diploma you already hold" is a near-verbatim description of the market. Someone
with genuine AI-eval fluency — a documented body of cases, a methodology — but no
MA/PhD in a narrow domain is pushed down to the generalist $15–22/h. There is no
route to validate AI-eval competence as a standalone qualification —
portfolio-based rather than diploma-based. This is the gap a strong portfolio aims
at, and the market has no mechanism to score it.

**6. Contributor data security below fintech standard.** Mercor: 40,000+ people;
interview video + biometrics + bank data + device screenshots; breached through a
dependency (LiteLLM). Platforms collect ever more (productivity monitoring,
recordings) with weaker safeguards than banking. Missing: enforced minimums (MFA,
encryption at rest, retention limits), third-party audit as a listing condition.

**7. No bridge from tool (B) to paid work (A).** Real evaluation methodology gets
built in Inspect / promptfoo / DeepEval. Category-A platforms pay for clicking
preference pairs, not for designing evals. Someone who can write an eval in
Inspect has nowhere to sell it as a freelancer short of a lab job or a closed
consultancy (Apollo, METR, Trail of Bits). A marketplace for "eval engineering"
as a service — portfolio-first, not annotation — does not exist.

**8. Red-teaming as income is a lottery, not a job.** Gray Swan / bug bounties:
real pools ($40k–170k+), but winner-take-most, irregular, no base. There is no
"retainer + bounty" model for verified red-teamers — standard in mature security,
absent in AI.

**9. EU lens: the expert tier is US-first.** Realistically accessible from the EU
with predictable payout: Mindrift, Toloka, Prolific, Clickworker (DE), OneForma —
mostly the lower / mid tier. Mercor / Handshake / Surge / DataAnnotation are
US-first. "Available worldwide" in practice means "the US and selected countries;
the rest get a lower rate or a block with no explanation" (precedent: Remotasks
cutting off whole countries). No expert-tier platform offers an explicit
EU-eligibility policy with SEPA / Payoneer payout and no hidden geo limits.

**10. No progression, no portable reputation.** The model is "get it while you
can" — task waves, then silence. No platform offers a path (junior annotator →
eval specialist → project lead), and reputation does not travel: work on Outlier
does not count on Mercor. There is no "GitHub for AI-eval work" — a verified,
cross-platform credential.

**Synthesis:** the market has maturely solved *lab-side expert sourcing*
(Mercor / Micro1 / Handshake / Surge) and *eval tooling* (Inspect / promptfoo /
Arena). It has solved nothing on the *worker* side: solvency, account protection,
non-diploma competence validation, the workbench→income bridge, and equal-terms
access from the EU. The single largest gap for a portfolio-based practitioner is
**#5 + #7** — there is no channel where documented AI-eval methodology, without a
domain PhD, converts into an expert rate.

---

## Appendix A — sources (selected, grouped by strength)

**Primary / strong:**

- Scale AI blog, "A New Era of Outlier" — scale.com/blog/new-era-outlier
- Labelbox Help Center — Alignerr Payment FAQs — help.labelbox.com
- UK AISI — "Announcing Inspect Evals" / inspect.aisi.org.uk ; github.com/UKGovernmentBEIS/inspect_ai
- Gray Swan Arena — app.grayswan.ai/arena/about ; challenge/agent-red-teaming
- Prolific researcher help — "What is your pricing?" — researcher-help.prolific.com
- restofworld.org/2024/scale-ai-remotasks-banned-workers/ ; computerworld.com
- Mercor breach: hausfeld.com (Mercor Data Breach) ; class action N.D. Cal. 1 Apr 2026 ; businesswire ; biometricupdate.com ; staffingindustry.com ; computing.co.uk ; thenextweb.com
- OpenAI–promptfoo: openai.com/index/openai-to-acquire-promptfoo ; promptfoo.dev/blog/promptfoo-joining-openai ; techcrunch.com (9 Mar 2026) ; cnbc.com
- Dynatrace–Arize: dynatrace.com/news/press-release/dynatrace-to-acquire-arize ; businesswire 20260813 ; ir.dynatrace.com (13 Aug 2026)
- en.wikipedia.org/wiki/Scale_AI
- LMArena rebrand (28 Jan 2026): coverage aggregated

**Secondary / affiliate (rate data — treat as PROMISED-biased):**

- feedkin.com, careerseeker.ai, skycodetalks.com, remowork.life, breakingeven.online,
  aiworkfinder.com, talentsforai.com, remoteonlineevaluator.com (Outlier / DA /
  Alignerr / Toloka / OneForma / Clickworker reviews)
- gigdrift.io, mindrift.ai/blog, annotation.academy, skillora.ai
- medium.com (micro1 vs Mercor vs Handshake), aitrainingjobsfinder.com,
  aigigjobs.com, theairankings.com, getaiwork.com
- theinterviewguys.com (red-teaming / RLHF pay), herohunt.ai, mercor.com/resources
- trustpilot.com/review/outlier.ai ; trustpilot.com/review/toloka.ai
- ziprecruiter.com / salary.com / levels.fyi / glassdoor (Surge, prompt-eng salary)
- kili-technology.com/blog/llm-red-teaming-in-2026 ; wraith.sh
- inference.net ; digitalapplied.com ; benchmarkingagents.com/inspect-uk-aisi
- sidehustlenation.com/toloka-review ; thecashden.com/clickworker-review
- 100kpathway.com ; weworkremotely.com ; arc.dev/remote-jobs/prompt-engineering

## Appendix B — query log (27)

**Positive (A):** "Outlier AI review 2026 pay rates qualification Europe Poland" ·
"Mindrift AI review 2026 pay rate legit freelance expert" · "Alignerr review 2026
pay Labelbox payment problems" · "DataAnnotation.tech review 2026 legit pay rate
assessment" · "best AI data annotation RLHF platforms 2026 comparison" · "Surge AI
contributor pay 2026 review how to join" · "Prolific study participant pay 2026 UK
researcher platform" · "Remotasks shutdown 2025 Scale AI replacement contributor" ·
"new AI training platforms 2026 Handshake AI Micro1 Turing expert" · "Mercor AI
interview hire experts contract 2026" · "Toloka 2026 review tasks pay Yandex
spinoff legit" · "Appen Clickworker OneForma 2026 AI tasks decline pay review" ·
"AI training platforms available Poland EU eligibility payment Payoneer 2026" · "AI
evaluation jobs market 2026 model behavior analyst RLHF specialist salary".

**Negative:** "Outlier AI not paying scam deactivated account 2026" · "Alignerr …
payment problems" · "Handshake AI Micro1 review complaints pay delays 2026 reddit"
· "Mercor privacy concerns data micro1 complaints 2026" · "reddit OutlierAI
dataannotation worker experience 2026 pay complaints".

**Cat. B/D:** "LLM evaluation frameworks 2026 promptfoo Inspect DeepEval Braintrust
comparison" · "Chatbot Arena LMArena HELM 2026 public LLM benchmark leaderboard" ·
"Gray Swan Arena crowdsourced AI red teaming prize money 2026" · "Inspect AI UK
AISI evaluation framework 2026 adoption" · "LangSmith Arize Phoenix Langfuse LLM
observability eval 2026" · "prompt engineering AI evaluation remote jobs board
2026" · "AI safety red team evaluation contractor apply 2026 Anthropic OpenAI
external" · "aitrainingjobs getaiwork aggregator AI gig platform listings 2026" ·
'"Outlier AI" owned by Scale AI Smart Ecosystem staffing agency'.

**Saturation criterion:** the final pass (3 queries) added no new platform or
dimension — it confirmed the existing patterns (payment delays, empty queues,
deactivations) at Handshake / Micro1. Category A treated as saturated.

---

## Changelog

**2026-09 — primary-source re-verification of load-bearing claims:**

- **Mercor breach** confirmed (Hausfeld, court filing, BusinessWire, Biometric
  Update). Precision added: attack window 24–30 March 2026; class action filed
  1 April 2026 (N.D. Cal.). Corrected: **Meta paused indefinitely; OpenAI
  reviewed but did not pause** — earlier phrasing ("Meta and others paused")
  overstated it.
- **promptfoo → OpenAI** confirmed against openai.com and promptfoo.dev; date set
  to the announcement, 9 March 2026; framed as "announced, integration after
  close".
- **Arize → Dynatrace** confirmed exactly (Dynatrace press release, BusinessWire,
  13 August 2026). Added deal value ~$915M and expected Q3-2026 close pending
  regulatory review.
- **Alignerr** non-payment and pre-payout deactivation confirmed via Glassdoor,
  BBB, and an itemised $3,240 case. The complaint-category counts (77 / 69 / 46)
  are retained but flagged as a second-hand community-discussion analysis.
- **Handshake** "55% of ~1,650 Reddit threads negative" traced to a single
  affiliate source with no primary backing; downgraded to directional and no
  longer stated as fact.

---
name: marketscope
description: Evidence-driven product and competitor intelligence, hardware/software analysis, company/brand/business-unit competition, market/industry studies, organizational and hiring signals, social, retail and go-to-market signals, professional workflows, strategy, procurement, product planning, and explicit investment or transaction due diligence. Route a product/company/brand/industry name or decision question to the correct research protocol.
metadata:
  output-language: "request-language"
---

# MarketScope — Principles

> Module 1 of 4. `SKILL.md` defines the **universal integrity, completeness, orchestration and stop rules**. The three References implement classification/routing, research execution and delivery. Do not replace one module with another or let a lower-priority rule override research integrity.

## 1. Purpose and trigger

Convert product, company, brand, business-unit, industry, category or multiple-entity input into a decision-oriented, evidence-driven investigation. Product, competitor-actor and investment/transaction diligence are distinct primary protocols using a shared evidence system. Company/brand reports must explain competitive **mechanisms, durability, actions and threats**, not merely catalog corporate facts; product reports test product value and real tasks; explicit due diligence examines investability, downside, rights, cash/valuation and decision conditions.

- Bare **Product** → `Strategic Product Intelligence`; bare **Company / Brand / Business Unit** → `Competitor Intelligence`; bare **Category / Industry** → `Market & Industry Intelligence`; **Multiple Entities** → `Comparative Intelligence` on normalized units.
- `Investment Due Diligence` requires explicit investment/acquisition/transaction/diligence intent. A competitor report may borrow Commercial Due Diligence (CDD) methods but must not claim completed transaction DD.
- Defaults for a bare name: `Highest / Strategic Deep Research`, `Remote`, actual `Public` access unless other access is established; infer audience from context, else a product/strategy reader; report in request language. Explicit Intent and Depth override defaults; audience only adjusts weighting and presentation, not depth.
- Keep `Research Subject`, `Intent`, `Audience`, `Depth`, `Evidence Mode`, `Evidence Access`, `Scope`, `Reference Actor`, `Completion Criteria`, `Materiality`, `Priority` and `Report Visibility` independent.
- Do not force a questionnaire. Ask only about a high-impact unknown that cannot reasonably be inferred and would materially change the decision; otherwise state assumptions and proceed.

## 2. Rule precedence and mandatory execution

1. Research Integrity Guardrails in this file.
2. Explicit decision, scope, depth, access and output requirements, if consistent with integrity.
3. Routing and subject-specific coverage contract (`references/classification-routing.md`).
4. Research execution and evidence testing (`references/research-sop.md`).
5. Output/data contract and verification (`references/output-contract.md`).

**Call chain:** `Resolve Research Subject & Decision → Classification & Routing → select one primary SOP + applicable cross-calls → validate Evidence → synthesize Findings → apply Output Contract → verify both completion gates`. The product category and the company/brand/entity boundary are different classification dimensions; never assign Hardware/Software to a company simply because a product line belongs there.

## 3. Research Integrity Guardrails — non-overridable

1. Do not fabricate facts, measurements, tests, users, market size/share, financials, margins, unit economics, valuations, suppliers, contracts, ownership, legal rights, sources, approvals, access or internal records. **Unknown remains Unknown**; do not manufacture numerical precision.
2. Separate `Source`, `Evidence`, `Finding`, `Interpretation`, `Hypothesis`, `Recommendation`; also separate Fact, Measurement, Observation and Customer Report. An official claim can establish what was stated, not that performance, adoption or strategic intent was independently verified.
3. Attribute third-party measures to their source and method; never imply first-party hands-on testing without primary data. Record version, SKU, region, firmware/app, method, settings, deployment, date, scenario and price/accounting context when materially relevant.
4. Customer reports reveal patterns and failure modes but do not establish market incidence without representative evidence. Investigate selection/incentive/platform/language/region/version biases; preserve raw customer material and provenance.
5. For material causal or strategic claims, test credible alternatives, counter-evidence and falsifiers. Association is not causation. Source count is not source independence: detect shared original records, reposts, press releases and evidence lineages.
6. Preserve material contradictions until reconciled by method/fit/recency/independence or explicitly marked unresolved. Never resolve by majority vote. A difference must pass `Measurable → Perceptible → Decision-relevant` before supporting a meaningful advantage.
7. Every material Finding and Recommendation must have a traceable `Recommendation → Finding → Evidence → Source` chain and an appropriate qualitative Confidence. Where feasible, seek two independent evidence dimensions; otherwise disclose Single-source / Limited Evidence.
8. Do not silently mix product/generation/SKU/region/software, legal company/holding group/issuer/subsidiary/brand/BU, geographic and reporting perimeters, revenue/GMV/bookings/ARR, quoted prices, transaction status or event dates. A brand is not automatically a separate legal or accounting entity.
9. Keep `Official Targeting`, `Verified Adoption`, `Potential Fit` and `Unknown` distinct; only the first two substantiate an evidenced market label. Consumer / Professional / Enterprise / Government / Defense can overlap. No inferred public-sector or defense suitability, authorization or deployment from dual-use features alone.
10. Press coverage, financing announcements, registry snapshots, patent filings, hiring notices, social posts, advertisements, awards and customer logos are signals with bounded claim roles: announcement ≠ funds received; application ≠ enforceable patent; listing ≠ completed hire or net headcount growth; social engagement/ad presence ≠ sales, retention or advertising effectiveness; logo ≠ retained paying customer; public registry ≠ complete beneficial ownership.
11. Follow actual permissions for public, licensed, authorized internal and specialist sources. Never assume paid databases, accounts, APIs, real-time monitoring, data rooms or restricted documents are accessible; no circumvention of access controls, login gates, CAPTCHA, platform privacy settings or terms. Public professional profiles, employee discussions and recruitment messages are not blanket consent to collect personal data; minimize person-level information and prefer aggregate, job-relevant organizational signals.
12. Diligence must separate `Material Red Flag` (credible risk signal), `Decision Blocker` (unresolved decision condition) and verified mandate-dependent `Deal Breaker`; allegations and negative searches are not proof of misconduct, clearance, or absence of liabilities.
13. Product recommendations are conditional on evidenced market, buyer, end-user task, deployment, price, ecosystem, constraints and uncertainty. Actor/transaction decisions must specify reference comparison, incentives, economics and risks; unsupported forecasts or return predictions are forbidden.
14. Preserve all valid Findings, failures, limits, contrary evidence and lower-materiality analyses; organization into `Core / Supporting / Appendix` is not content deletion. Never trim findings solely to meet report length.
15. A company report does not require a product hero image or universal specification matrix. Product reports do require an official high-resolution image (or `Unavailable`) and source-backed Product Specification Matrix by default. Public-source due diligence must not be labeled comprehensive transaction diligence.
16. Do not fabricate organization authority, direct reports, responsibilities, approvals, deliverable status or schedules. Translate validated findings into lateral collaboration, upward decisions or downward management outputs only when requested and distinguish proposed from authorized assignments.
17. Public hiring, professional-network and social-platform material is **signal evidence**, with distinct publisher identity, provenance, observation window and selection bias. Resolve employer vs recruiter, brand vs legal entity, original posting vs syndication, and corporate voice vs personal report. Triangulate material interpretations against independent operating, product, customer or financial evidence; missing platform access is an evidence limit, not a negative finding.
18. Social networks, content communities, messaging/CRM, social commerce, retail marketplaces, DTC storefronts, B2B wholesale and digital marketplaces are **source/channel roles**, not new Research Subjects or mutually exclusive platform identities. Screen decision-relevant channel families; retrieve selectively based on the customer job, buyer journey, region, category, provenance, permissible access and incremental information value. Resolve official account/store versus reseller/affiliate/fan, and product/SKU/market/offer/seller/fulfillment scope. A listing or badge does not prove authorization, availability, completed transactions, sales volume, profit, market share, advertising return or retention. Platform reviews are nonrepresentative VoC unless sampling supports broader inference; no automated full-platform sweep or platform connectivity is implied.

19. Distinguish **source-family screening**, **actual retrieval attempt**, **retrieved observation**, **verified actor attribution**, and **verified commercial outcome**. Screening completion is not a claim that every named platform was queried; a failed or blocked retrieval is not evidence of no presence. For material channel claims, record why sources were selected or omitted, exact query/market/time boundaries, original links or inaccessible fields, and the comparative basis. Treat a channel as a capability only after its mechanism and decision relevance are demonstrated, not merely because a profile, store, advert, listing, or feature exists.

20. For decision-relevant commerce performance, distinguish `Reconciled Actual`, `Officially Reported`, `Method-disclosed Estimate`, `Observed Sales Indicator`, and `Unknown` before interpreting sales. A displayed sold-count, bestseller rank, purchase badge, review count or advertised GMV is not automatically a completed, refunded-adjusted sell-through measure, channel revenue or net profit. Resolve the exact reporting entity, product/SKU, merchant, marketplace, period, order/payment/fulfillment/refund basis, currency, attribution and duplication risk; use authorized seller exports or original financial disclosures when legitimately available, otherwise preserve uncertainty and estimation method. Do not infer platform dashboards, nonpublic order data or paid analytics access from this instruction; follow the cross-cutting Commerce Sales Intelligence protocol.

## 4. Independent execution state

| Field | Allowed semantics |
|---|---|
| Scope Status | `In Scope`, `Out of Scope` |
| Coverage Requirement | `Mandatory`, `Conditional` |
| Execution Priority | `P0`, `P1`, `P2`, `P3`: **when** to research, never **whether** |
| Coverage Status | `Pending`, `Resolved`, `Limited Evidence`, `Unknown`, `Unavailable`, `Not Applicable` |
| Materiality | `Critical`, `High`, `Medium`, `Low`, `None`: decision impact |
| Report Visibility | `Core`, `Supporting`, `Appendix`: reporting placement |
| Evidence Mode | `Remote`, `Hands-on`, `Internal` |
| Evidence Access | `Public`, `Licensed / Subscription`, `Authorized Internal / Data Room`, `Professional Third-party`, `Unavailable / Unknown` |
| Market Claim Basis | `Official Targeting`, `Verified Adoption`, `Potential Fit`, `Unknown` |
| Confidence | `High`, `Medium`, `Low`, `Unknown`; not the same as Coverage Status |

`Pending` is not terminal. `Not Applicable` needs a structural explanation; never use `Not Relevant` as a Highest-depth completion status. Low Priority or Materiality cannot erase mandatory research. Materiality may change Visibility, not Coverage.

## 5. Highest-depth breadth contract

At Highest depth, select the **subject-specific** mandatory research domains in `references/research-sop.md` and process *each* in-scope ResearchItem to a terminal status, even if evidence is missing. Product-level domains do not mechanically transfer to company/brand/BU or investment reports; the correct protocol controls applicability. All frameworks must be screened; execute only applicable, evidence-sufficient tools, otherwise explain `Not Applicable` / `Unknown` / `Limited Evidence`.

**Product mandatory domains:**

1. Product / SKU / version / price / positioning.
2. Target market / buyer / decision authority / end user / industry / segment / JTBD / substitutes.
3. Scenario / workflow / human factors / failure modes.
4. Claims / measurements / benchmark / evaluation.
5. VoC / long-term / lifecycle / reliability / TCO.
6. Previous generation / internal alternative / substitution / benchmark / emerging competition.
7. Trade-offs / conditional winner / price–value.
8. Portfolio / naming / SKU role / cannibalization / upgrade path.
9. Ecosystem / cross-device workflow / switching cost.
10. Company capability / organization / R&D / IP / brand / channel / GTM, with decision-relevant hiring, social, commerce and DTC signals.
11. Value chain / supply chain / BOM / ODM-OEM / yield / tooling / capacity / lead time / supplier risks.
12. Business model / revenue / subscription / services / unit economics where evidence permits.
13. Market definition / growth / segments / WTP / sizing / profit pool where evidence permits.
14. Macro environment; industry structure.
15. Capital / financing / transactions where evidence permits.
16. Resources / capabilities / defensibility.
17. Growth options / scenarios / sensitivity.
18. Risk / opportunity / resource allocation.

**Competitor Intelligence domains:** actor boundary/control; history/strategic evolution; portfolio; customers/buyers/JTBD; market rivalry; commercialization; financial/growth quality; product/tech/IP; operations/supply chain; channels/GTM/brand and attributable public social, marketplace and DTC activity; organization/talent and hiring signals; capital/ownership/partners; legal/regulatory/security; defensibility; strategic moves/scenarios; threats/opportunities/responses. The exact domain questions reside in SOP.

**Investment DD domains:** corporate/cap table, commercial, financial, legal, tax, technical/cybersecurity, operations/supply, people, customers/partners/channels, regulation/ESG/privacy, valuation/capital requirements, integration/exit. Evidence-access gaps remain visible; no implication of audit, assurance, legal or tax advice.

For Category/Industry/Multiple Entities, define the market and comparison unit, then create a decision-specific mandatory Coverage Plan addressing structure, actors, relevant economics, change drivers and uncertainty.

## 6. Shared synthesis and quality gates

- Select applicable frameworks by research question, analysis unit, minimum evidence, relevance and non-duplication. Screening is mandatory; producing every framework graphic is not.
- Findings pipeline: `Evidence → Finding → Confidence → Materiality → Contradictions → Ranking → Clustering → Strategic Synthesis → Core Thesis → Decision-changing Unknowns`.
- **Breadth Completion Gate:** all in-scope items processed to terminal status in P0–P3 order; all mandatory subject domains terminal; each screened framework executed or explicitly bounded; major competitors normalized or limitations explicit; material contradictions resolved or bounded; preliminary DD gaps and next requests disclosed.
- **Depth Saturation Gate:** additional feasible evidence is unlikely to change a Finding, Confidence, boundary, trade-off, recommendation or action. If access blocks further verification, finish a clearly **limited** report, not a falsely verified one.
- Final checks: subject/intent/perimeter and financial dates consistent; classification/markets evidence-based; source lineage, competing explanations, consequential risks and unknowns visible; hiring/social/commerce signals de-duplicated, correctly attributed and not converted into realized outcomes; source-family screening distinguished from actual searches and verified presence, with material channel selection/omission reasons logged; marketplace offers normalized by seller/SKU/region/time/price conditions; sales measures separated by verification tier, period, transaction/refund basis and deduplicated channel scope; product images/specs from primary sources where available; all identifiers/record links valid; no unauthorized monitoring, approval or team execution claims.

## 7. Resource loading map

| Purpose | Load |
|---|---|
| Identify subject, intent, hardware/software category, market, buyer, peer universe, corporate/recruitment/social/commerce source-access route, clarification | `references/classification-routing.md` |
| Execute Product P0–P10, Competitor C0–C8, DD D0–D8; hiring/social/commerce signal analysis, source testing, VoC, finance, strategy, failure & lifecycle | `references/research-sop.md` |
| Build finding-led reports, source/coverage/record tables, legal/market provenance, team/executive outputs, validate delivery | `references/output-contract.md` |

Do not ask for clarification or call a specialist protocol solely to fill a form. Research is **protocol-driven; reporting is finding-driven**. Preserve decision-relevant completeness and honest limits over a cosmetic claim of exhaustive certainty.

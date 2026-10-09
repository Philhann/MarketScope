# Output Contract
> Module 4 of 4. Compile only **after** `SKILL.md` → `references/classification-routing.md` → `references/research-sop.md`. This module governs report form, complete evidence-linked records, auditability and final validation. It does not redefine subject routing or retroactively remove research coverage.
## Shared delivery contract
- Answer the Decision Question and expose the subject, intent, evidence mode/access, scope, research cutoff, confidence, competing explanations, residual risks and decision-changing unknowns.
- Generate headings **after Finding clustering**, not as fixed analytical framework chapters. Preserve all valid Findings via `Core / Supporting / Appendix` regardless of length. Merge only genuine duplicates with lineage maintained.
- Use the selected Product/Actor/Investment/Industry contract. Product visuals and official specification matrices apply by default to Product reports only; company/brand visuals are optional; preliminary public-source diligence may not masquerade as comprehensive authorized transaction diligence.
- Each material recommendation must reverse-trace to existing `FindingRecord → EvidenceRecord → SourceRecord` IDs. Use conditional actions with context, alternatives, trade-offs and falsifiers; provenance must carry exact original URLs, dates and entity/metric/region boundaries. Public hiring and social signals require employer/account attribution, observation windows, source lineage, and explicit separation of stated intent from realized results.
## Report architecture, decision snapshots and writing
### Completeness-first reporting
Preserve valid research, counter-evidence, boundary conditions, secondary Findings and extended analysis regardless of length; manual downstream review may refine presentation. Remove only true duplication, erroneous/corrupted data, unsupported filler or material outside Scope—not evidence for brevity or visual neatness.
### Research coverage vs report organization
Full research coverage should remain inspectable in the delivered report set.

Use:
- Coverage Status — whether research was resolved; Materiality — how strongly the result can change the decision; Report Visibility — where the result should appear
Report Visibility values are `Core`, `Supporting`, and `Appendix`. Appendix placement organizes extended or lower-materiality detail; it is not an automatic deletion mechanism.
### Finding pipeline
Use:

`Evidence → Finding → Confidence Check → Materiality Pass → Contradiction Check → Ranking → Clustering → Strategic Synthesis → Thesis → Recommendation`

Preserve valid Findings regardless of Materiality. Consolidate only true duplicates while preserving lineage.
### Dynamic IA
After Finding Clustering (never predefine final L1/L2 headings):
1. identify the Decision and Core Thesis;
2. identify the causal/decision chain needed to explain it;
3. combine market, segment, product, evidence, competition, economics, and strategy by that logic;
4. create precise thesis-oriented headings;
5. order by decision comprehension, not research chronology;
6. use Appendix for methods, raw/extended data, source registers, large specification tables, and additional detail when that improves navigation.
Recommended hierarchy:

`L1 Thesis → L2 Strategic Finding Clusters → L3 Evidence / Analysis / Matrix → L4 Methods / Extended Data / Sources`

Do not impose a hard cap on Finding Clusters. Do not merge or drop analytically distinct Findings merely to keep the report shorter.
### Subject-specific report openings
**Generate the information architecture from Findings, but select the minimum subject-appropriate report contract before research.** Product Competitive Analysis, Competitor Intelligence, and Investment Due Diligence should never share a mandatory product-specification opening. The same research domain may appear at different depths, depending on the decision and evidence.
| Intent / subject | Required report identity and opening assets | Decision output |
|---|---|---|
| Product / Product Competitive Analysis | Formal product name, first-party high-resolution product image (or `Unavailable`), Product Specification Matrix, SKU/region/price/version/cutoff | Product performance, workflow, relative value, trade-offs, conditional actions |
| Company / Brand / BU Competitor Intelligence | Formal competitor/entity name, Company/Brand/BU boundary and ownership relationship, comparison reference actor/industry scope, research cutoff; optional sourced official corporate/brand visual | Competitive thesis, business/brand portfolio, mechanisms, capability comparison, threats, counter-theses, responses |
| Explicit Investment Due Diligence | Transaction asset/legal entity and deal mandate, evidence-access and diligence status (`Preliminary / Public-source DD` where applicable), research cutoff, conditions; optional sourced corporate visual | Invest/Conditional/Defer/Decline or other mandate-dependent decision, thesis tests, valuation if supportable, risks/blockers and document requests |
| Market & Industry / Comparative Intelligence | Explicit category/industry or peer universe and normalized units, region/time/metric basis and decision reference | Structure, relative winners, risks, scenarios and strategic options |
#### Competitor Intelligence opening scaffold
```md
# <Company / Brand / Business Unit Formal Name>
**Research Subject:** <Company / Brand / Business Unit>
**Entity / Brand Ownership & Reporting Boundary:** <verified description / Unknown>
**Reference Actor / Competitive Market:** <actor or industry benchmark / Unknown>
**Research Cutoff / Geography / Time Period:** <values>
**Evidence Access:** <public / authorized / licensed as actually available>
> **Competitive Thesis:** <finding-based, conditional, evidence-linked answer>
<Dynamic, finding-led analytical body>
## Decision-changing Unknowns and Revalidation Triggers
## Appendix: Evidence & Source Register
```
Use suitable actor-specific visuals only when available from attributed authentic sources. A company logo, brand identity, or portfolio map may help, but **do not force a hero image or Product Specification Matrix into a competitor report**. Product specs belong only in product-level supporting analyses.
#### Investment DD opening scaffold
```md
# <Target / Transaction Asset>
**Review Type:** <Investment Due Diligence / Preliminary Public-source Due Diligence>
**Entity / Equity / Business Perimeter:** <verified description / Unknown>
**Decision Mandate / Investment Thesis:** <defined / Unknown>
**Evidence Access & Material Data Gaps:** <access and limitations>
**Research Cutoff / Geography / Reporting Period:** <values>
> **Decision Thesis / Conditional Recommendation:** <finding-led, no false precision>
<Dynamic, finding-led diligence body>
## Material Risks, Conditions and Unresolved Verification
## Appendix: Due Diligence Coverage, Evidence & Source Registers
```
Never imply that missing signed contracts, source ledgers, specialist reviews or private board materials were examined; unavailable access is a limitation, not proof that a deal should succeed or fail. Cite originating financial/legal records and state whether figures are verified, reported, estimated, or modeled.
### Default opening assets
Default **Product** report opening order:
1. Product title / identity
2. Official high-resolution product image
3. Image caption and first-party source
4. Product Specification Matrix
5. Research Cutoff / Region / SKU / Version / Price Observation Date
6. Decision Snapshot when useful
7. Finding-led main body
For official product imagery prefer the largest suitable matching first-party product/newsroom/media-library asset, preserve original URL/Source ID and variant attribution; use `Unavailable` rather than unofficial, mirrored or generated imagery.
For Markdown delivery, use the report-opening scaffold below when appropriate. The opening structure should adapt to product type and evidence availability. The full specification table should cover all reasonably accessible official specifications, not merely the example row.
```md
# <Product Formal Name>
![Official high-resolution product image](<official-first-party-asset-url>)

*Official product image. Source: <Source ID / first-party page or asset URL>.*
## Product Specifications
| Parameter | Value | Unit | SKU / Region / Version | Evidence Status | Source ID |
|---|---|---|---|---|---|
| <parameter> | <value> | <unit> | <context> | Official Fact / Unknown | <Sxx> |
**Research Cutoff:** <YYYY-MM-DD>
**Region:** <region>
**SKU / Version:** <context>
**Price Observation Date:** <YYYY-MM-DD or Unknown>
```
If no suitable first-party high-resolution image exists, replace the image with `Official Product Image: Unavailable`. Keep the result grounded in real product visuals and source records.

Specification Matrix: include all reasonably accessible official parameters with unit, SKU/region/version, status and Source ID; use `Unknown` where unpublished and separate third-party measurements.
#### Actor / diligence Decision Snapshot
A company/brand/BU competitor Decision Snapshot may prioritize `Competitor / Reference Actor → Competitive Thesis → Market & Business Exposure → Relative Advantages / Constraints → Counter-evidence → Competitive Threat / Scenario → Conditional Strategic Response → Confidence / Trigger`. An Investment DD snapshot instead prioritizes `Mandate → Thesis → Quality of Growth / Cash / Rights → Verified and Unverified Risks → Valuation Condition if feasible → Recommendation / Conditions → Unresolved Requests`. The snapshot is a decision interface, not a substitute for full evidence coverage.
### Decision Snapshot
When useful, open with:
- Decision / Verdict; Target market and buyer / end-user context when it changes the decision; Strategic Thesis; Key Findings; Key Trade-off; Best Fit / Non-fit; Price / Economics; Recommendation / Action; Confidence
- Decision-changing Unknowns
The Decision Snapshot is a navigation layer, not a substitute for full analysis.
### Tables vs prose
Use a table when comparability × information density × review speed is better than prose.

Prefer matrices for:
- ≥3 products **or competing actors** and ≥2 comparable dimensions; multiple scenarios / workflows; Result + Benchmark + Delta + Implication + Confidence; Claim–Evidence mapping; Gain ↔ Cost trade-offs; Product specifications
- Price–Value / TCO / WTP; Target Market × Buyer × End-user Job × Deployment context when markets overlap; Portfolio / Ecosystem; Capability / Replication; Opportunity / Resource allocation; Risk / Unknown / dependency
- Evidence & Source Register
Use prose for:
- causality; mechanisms; boundary conditions; counter-evidence; counterfactuals; second-order effects; unresolved uncertainty
Do not mechanically restate every table row in prose, but retain any interpretation or implication that adds analytical value.
### Writing discipline
Every paragraph should perform at least one function:
- Finding; Evidence; Interpretation; Mechanism; Implication; Limitation / Counter-evidence; Recommendation
Avoid filler transitions, heading restatement, unsupported adjectives, and framework-driven exposition. Do not remove substantive detail merely to make the report shorter.

Prefer precise domain terminology. Preserve useful English terms when more exact than translation.
### Recommendation language
Prefer conditional form:

`For evidenced target market A, buyer B, end-user task C, scenario D, price E, and ecosystem F, option X is stronger; if condition G changes, the recommendation shifts to Y.`

Competitor/actor decisions: Match / Differentiate / Partner / Defend / Avoid / Monitor / Explore, qualified by reference actor, segment, resource needs, evidence and triggers. Investment/transaction decisions: Proceed / Conditional / Defer / Decline where the actual mandate and review state justify those verbs. Do not infer that a suggested plan was approved.

Consumer actions: Buy / Skip / Upgrade / Keep.

Product / strategy actions: Keep / Match / Differentiate / Avoid / Explore, plus Evidence, Risk, Dependency, Success Metric, and resource implication when material.

Upward management output should include Recommendation, Business Impact, Risk/Uncertainty, and Decision/Resource Ask. Downward management output should turn authorized decisions into appropriately delegated deliverables, decision rights, success criteria, checkpoints, and feedback; distinguish proposed work from approved assignments.
### Audience outputs
#### Cross-functional working output
`Finding → Evidence → Impact → Open Question → Action → Owner → Done Criteria`

Do not infer technical root cause without evidence.
#### Executive output (upward)
`Conclusion → Business Impact → Evidence → Options → Recommendation → Risk / Uncertainty → Ask`
#### Team leadership and execution output (downward)
`Authorized Decision / Goal → Prioritized Deliverable → Accountable Owner & Decision Rights → Resources / Dependencies → Milestones → Acceptance Criteria → Review / Escalation → Evidence-based Feedback / Next Action`

When appropriate, provide an assignment register from `references/output-contract.md`. Do not turn an analyst recommendation into an apparently approved directive, imply line-management authority over cross-functional peers, invent owners or dates, or evaluate individuals without observable evidence. Include coaching/support and a review loop when team capability or repeated execution is material.

Use these communication routes only when the request needs an internal organizational output. Place extended process detail in Appendix when that improves navigation. Preserve valid detail rather than compressing it solely for brevity.
## Structured records, schemas and reusable registers
### Purpose
This reference defines the structured research records, reusable reporting registers, and verification checks. It governs data shape and traceability, not what the evidence must conclude.
### Common rules
- Keep stable unique record IDs (`S01`, `E01`, `F01`, etc. where appropriate). Preserve cross-record references and evidence lineage.
- Fields marked **Required** must be present even if a research value remains legitimately `Unknown`. Do not fabricate a value merely to populate a required field.
- When serializing a record using these field contracts, do not add undeclared fields to the eight defined record types. For scope-specific extensions, use a separate domain record rather than silently modifying the contract.
- `null` is allowed only for properties listed as nullable; arrays may be empty unless the record definition states otherwise.
- Resolve `Research Subject`, `Intent`, and `Evidence Access` independently. `DecisionBrief.scope` may contain subject type, legal/entity/group/brand/BU boundaries, reference actor, diligence mandate and evidence-access details; preserve the original eight strict record contracts unchanged.
- `Coverage Status` is an execution result, not a confidence score. `Pending` is a working state, not terminal.
- `Materiality` governs decision importance; `Report Visibility` governs where a finding appears; neither removes a mandatory coverage item.
- Preserve `Product`, `Generation`, `SKU`, `Region`, `Firmware`, `Software`, `Date`, `Scenario`, `Method`, and `Price Context` when material to interpretation.
- Do not confuse report `Audience` or `Intent` with a product's target markets, purchasing decision makers, or end users. `target_markets[]` accepts overlapping labels; `Professional` is a cross-cutting practitioner/workflow lens, and `Defense` may overlap with `Government` or `Enterprise`.
- Market claims need a basis: `Official Targeting` / `Verified Adoption` / `Potential Fit` / `Unknown`. Only the first two may support an evidenced `target_markets[]` label; `Potential Fit` belongs in `potential_fit_markets[]`. Keep source lineage and scope for each assertion.
### Record fields
In the tables below, **Required** identifies fields that must be included in structured records. Type constraints and enumerated values must be preserved.
#### DecisionBrief
| Field | Type / Allowed values | Required |
|---|---|---|
| `question` | string | Yes |
| `intent` | string | Yes |
| `audience` | string | Yes |
| `depth` | string | Yes |
| `evidence_mode` | `Remote` / `Hands-on` / `Internal` | Yes |
| `scope` | object | Yes |
| `region` | string / null | No |
| `time_window` | string / null | No |
| `research_cutoff` | string / null | No |
| `completion_criteria` | array of string | Yes |
#### ResearchItem
| Field | Type / Allowed values | Required |
|---|---|---|
| `id` | string | Yes |
| `question` | string | Yes |
| `scope_status` | `In Scope` / `Out of Scope` | Yes |
| `coverage_requirement` | `Mandatory` / `Conditional` | Yes |
| `execution_priority` | `P0` / `P1` / `P2` / `P3` | Yes |
| `coverage_status` | `Pending` / `Resolved` / `Limited Evidence` / `Unknown` / `Unavailable` / `Not Applicable` | Yes |
| `materiality` | `Critical` / `High` / `Medium` / `Low` / `None` | Yes |
| `report_visibility` | `Core` / `Supporting` / `Appendix` | Yes |
| `method` | string / null | No |
| `notes` | string / null | No |
#### CoverageRecord
| Field | Type / Allowed values | Required |
|---|---|---|
| `domain` | string | Yes |
| `coverage_requirement` | `Mandatory` / `Conditional` | Yes |
| `coverage_status` | `Pending` / `Resolved` / `Limited Evidence` / `Unknown` / `Unavailable` / `Not Applicable` | Yes |
| `materiality` | `Critical` / `High` / `Medium` / `Low` / `None` | Yes |
| `report_visibility` | `Core` / `Supporting` / `Appendix` | Yes |
| `reason` | string / null | No |
| `finding_ids` | array of string | Yes |
#### SourceRecord
| Field | Type / Allowed values | Required |
|---|---|---|
| `id` | string | Yes |
| `source_type` | string | Yes |
| `publisher_owner` | string | Yes |
| `title` | string | Yes |
| `date` | string / null | No |
| `product_context` | string / null | No |
| `claim_role` | string / null | No |
| `primary_origin` | string / null | No |
| `lineage_id` | string / null | No |
| `confidence_notes` | string / null | No |
| `url_or_internal_ref` | string / null | No |
#### EvidenceRecord
| Field | Type / Allowed values | Required |
|---|---|---|
| `id` | string | Yes |
| `type` | `Fact` / `Measurement` / `Observation` / `Customer Report` / `Interpretation` / `Hypothesis` | Yes |
| `claim` | string | Yes |
| `source_ids` | array of string | Yes |
| `primary_origin` | string / null | No |
| `lineage_id` | string / null | No |
| `source_independence` | `Independent` / `Partially Independent` / `Shared Origin` / `Unknown` | Yes |
| `directness` | `Direct` / `Indirect` / `Unknown` | Yes |
| `freshness` | string / null | No |
| `version_fit` | `Exact` / `Close` / `Weak` / `Unknown` | Yes |
| `scenario_fit` | `Exact` / `Close` / `Weak` / `Unknown` | Yes |
| `method_quality` | `High` / `Medium` / `Low` / `Unknown` | Yes |
| `confidence` | `High` / `Medium` / `Low` / `Unknown` | Yes |
#### ContradictionRecord
| Field | Type / Allowed values | Required |
|---|---|---|
| `id` | string | Yes |
| `claim` | string | Yes |
| `evidence_ids` | array of string; minItems=2 | Yes |
| `version_difference` | string / null | No |
| `method_difference` | string / null | No |
| `scenario_difference` | string / null | No |
| `possible_explanation` | string / null | No |
| `resolution_status` | `Resolved` / `Partially Resolved` / `Unresolved` | Yes |
| `remaining_uncertainty` | string / null | No |
| `decision_impact` | string / null | No |
#### FindingRecord
| Field | Type / Allowed values | Required |
|---|---|---|
| `id` | string | Yes |
| `finding` | string | Yes |
| `evidence_ids` | array of string | Yes |
| `counter_evidence_ids` | array of string | Yes |
| `alternative_explanations` | array of string | Yes |
| `confidence` | `High` / `Medium` / `Low` / `Unknown` | Yes |
| `materiality` | `Critical` / `High` / `Medium` / `Low` / `None` | Yes |
| `report_visibility` | `Core` / `Supporting` / `Appendix` | Yes |
| `decision_impact` | string / null | No |
| `trade_off` | string / null | No |
| `implication` | string / null | No |
| `action` | string / null | No |
#### StrategicFrameworkRecord
| Field | Type / Allowed values | Required |
|---|---|---|
| `framework` | string | Yes |
| `analysis_unit` | string / null | No |
| `scope` | string / null | No |
| `screening_status` | `Execute` / `Not Applicable` / `Unknown` / `Limited Evidence` | Yes |
| `minimum_evidence_check` | array of string | Yes |
| `input_finding_ids` | array of string | Yes |
| `input_evidence_ids` | array of string | Yes |
| `assumptions` | array of string | Yes |
| `result` | string / null | No |
| `counter_evidence_ids` | array of string | Yes |
| `confidence` | `High` / `Medium` / `Low` / `Unknown` | Yes |
| `materiality` | `Critical` / `High` / `Medium` / `Low` / `None` | Yes |
| `strategic_implication` | string / null | No |
| `report_visibility` | `Core` / `Supporting` / `Appendix` | Yes |
### Additional working records
`ProductRecord`, `CompanyRecord`, `BrandRecord`, `BusinessUnitRecord`, `EntityRelationshipRecord`, `InvestmentThesisRecord`, `RiskRecord`, `DueDiligenceRecord`, `IntelligenceEventRecord`, `HiringSignalRecord`, `SocialGTMSignalRecord`, `HypothesisRecord`, `IssueRecord` and optional `ExecutionAssignment` are **additional, scope-specific working objects**. The eight strict record types above retain their existing field contracts and enum values. New domain records extend the system **without silently adding fields** to the eight legacy contracts.
#### ProductRecord — recommended classification and market fields
| Field | Type / Allowed values | Meaning |
|---|---|---|
| `product_form` | `Hardware` / `Software` | Primary top-level product route. |
| `category`, `subcategory`, `product_type` | string / null | Function-based category hierarchy; do not store target market here. |
| `secondary_categories[]`, `linked_layers[]` | arrays of string | Connected categories, device/app/cloud/service layers. |
| `target_markets[]` | array of `Consumer` / `Professional` / `Enterprise` / `Government` / `Defense` | Non-exclusive markets with official targeting or verified adoption support. |
| `potential_fit_markets[]` | array using the same labels | Hypothetical opportunities, kept separate from proven targeting/adoption. |
| `market_assessments[]` | array of market assessment objects described below | Per-market claim basis, evidence and confidence. |
| `market_routes[]` | array of context objects | Preserve market → buyer → procurement authority → end-user role → industry → scenario/deployment relationships without mixing segments. |
| `primary_buyer`, `procurement_owner` | string / null | Economic buyer and entity controlling procurement; `Unknown` where not verified. |
| `decision_makers[]` | array of string | Selection, approval, IT/security, procurement, or other decision roles. |
| `end_users[]`, `user_roles[]` | arrays of string | Operators and their relevant level of expertise / occupational roles. |
| `industry_verticals[]` | array of string | Education, Health, Finance, Media, Manufacturing, etc.; multiple permitted. |
| `usage_scenarios[]`, `deployment_contexts[]` | arrays of string | Concrete tasks, environments, organizational / security / scale constraints. |
| `sales_motion[]` | array of string | B2C / B2B / B2G / channel / tender / self-service when supported; never a substitute for market type. |
| `product_context`, `price_context`, `positioning`, `specification_source_ids[]` | context text / ID array as applicable | Preserve product identity, version, region, date, price, specs and provenance. |
Each `market_assessments[]` item should contain:
- `market`: one of the five allowed market labels;; `basis`: `Official Targeting` / `Verified Adoption` / `Potential Fit` / `Unknown`;; `source_ids[]` and, when available, `evidence_ids[]` linking to relevant records;
- `confidence`: `High` / `Medium` / `Low` / `Unknown`;; `scope_note`: product / market / region / timing / customer or buyer specificity and remaining limitations.
Each `market_routes[]` context should contain its `market`, `primary_buyer`, `procurement_owner`, `decision_makers[]`, `end_users[]`, `user_roles[]`, `industry_verticals[]`, `usage_scenarios[]`, `deployment_contexts[]`, and relevant `source_ids[]`; use `null`/empty arrays and explicit `Unknown` status for missing details. Do not merge roles from different market routes into a fictitious average customer.

Multiple assessment items per market are allowed, because Official Targeting and Verified Adoption can coexist; neither may be inferred from Potential Fit. A market with insufficient evidence is `Unknown`, not automatically absent. Keep unique `market` + `basis` + `scope_note` combinations and avoid counting common-origin publicity as independent proof. Where a report only needs prose rather than structured export, apply the same distinctions without manufacturing unknown data.

For `HypothesisRecord`, retain a falsifiable proposition, competing explanations, evidence need, and current status. For `IssueRecord`, retain the existing issue-log fields from `product-evaluation.md`: Issue ID, Product / SKU / Version, Scenario, Trigger, Symptom, Reproduction status, Severity, Workaround / Recovery, and Current Status.
#### CompanyRecord / BrandRecord / BusinessUnitRecord
Use these flexible domain records for actor-level research; add identifiers only when published or verified. Required working fields for each instantiated record are `id`, `subject_type` (`Company` / `Brand` / `Business Unit`), `formal_name`, `entity_boundary`, `as_of_date`, `source_ids[]`, `confidence`. Keep unresolved identifiers or group relationships as `Unknown`, not fabricated values.
| Field | Purpose |
|---|---|
| `legal_entity_names[]`, `aliases[]`, `jurisdiction`, `registration_ids[]` | Disambiguation and applicable legal context; a brand may have no standalone registration |
| `parent_entity_id`, `operating_entity_ids[]`, `brands[]`, `business_unit_ids[]` | Observed group and brand relationships; never infer undisclosed control |
| `consolidation_perimeter`, `financial_reporting_unit`, `financial_period` | Prevent attribution of group finance to subsidiary, BU or brand |
| `business_lines[]`, `product_ids[]`, `target_market_routes[]`, `geographies[]` | Portfolio and customer/market mapping; route products individually Hardware / Software |
| `reference_actor_id`, `competitor_actor_ids[]`, `competitor_roles[]` | Comparison boundary and reasons for inclusion |
| `strategic_events[]`, `intelligence_event_ids[]`, `material_finding_ids[]` | Time-linked strategy, evidence and decisions |
| `access_limitations[]`, `unknowns[]` | Published/authorized information boundaries |
#### EntityRelationshipRecord
Use `id`, `from_entity_id`, `to_entity_id`, `relationship_type` (`Owns`, `Controls`, `Operates`, `Brand Of`, `Distributes`, `Licenses`, `Partners With`, `Other / Unknown`), `percentage_or_rights` (nullable), `effective_date`, `source_ids[]`, `confidence`, and `limitations`. A relationship observed at one date is not timeless; ownership percentage is `Unknown` when not verifiable. Do not present business partnerships as equity control.
#### HiringSignalRecord / SocialGTMSignalRecord — optional working records

Use these records only when public employment, social, channel-presence or commerce signals are material to a research question. They **extend** the working-object system; they do not modify `DecisionBrief`, `ResearchItem`, `CoverageRecord`, `SourceRecord`, `EvidenceRecord`, `ContradictionRecord`, `FindingRecord` or `StrategicFrameworkRecord`. Each signal must link to an existing `SourceRecord` and, when used to support a Finding, an `EvidenceRecord`.

| Record | Recommended fields | Inference boundary |
|---|---|---|
| `HiringSignalRecord` | `id`, `subject_entity_id`, `employer_or_recruiter_identity`, `platform`, `source_ids[]`, `original_requisition_or_listing_id`, `original_url`, `role_title`, `job_function`, `skills[]`, `seniority`, `location`, `employment_type`, `displayed_salary_range`, `salary_currency_period`, `posting_date`, `update_date`, `observed_date`, `listing_status`, `lineage_id`, `original_or_syndicated`, `evidence_ids[]`, `candidate_hypothesis`, `counter_explanations[]`, `confidence`, `access_limitations` | `Observed Vacancy` / `Employer-stated Need` is not `Filled Hire`, `Net Growth`, `Team Built`, `Budget Approved`, or `Shipped Capability`; missing dates, job IDs or salary are `Unknown` |
| `SocialGTMSignalRecord` | `id`, `subject_entity_id`, `platform`, `account_or_page_identity`, `account_attribution_basis`, `business_function_tags[]`, `customer_journey_stage`, `content_kind`, `sponsorship_or_affiliate_status`, `post_or_ad_id`, `original_url`, `source_ids[]`, `publication_date`, `observed_date`, `region_or_market`, `product_or_campaign_scope`, `observable_claim_or_metric`, `metric_definition`, `conversion_destination`, `lineage_id`, `evidence_ids[]`, `candidate_hypothesis`, `counter_explanations[]`, `confidence`, `access_limitations` | `Corporate Statement`, `Public Engagement` or `Campaign Presence` is not independently verified `Ad Spend`, `Customer Conversion`, `Revenue`, `Retention`, `Market Share`, or `ROAS` |
| `PlatformPresenceRecord` | `id`, `subject_entity_id`, `platform`, `platform_family`, `business_function_tags[]`, `account_shop_site_identity`, `original_url`, `presence_status`, `attribution_basis`, `brand_or_legal_entity_scope`, `market_region`, `seller_of_record`, `fulfillment_role`, `observed_date`, `source_ids[]`, `evidence_ids[]`, `lineage_id`, `confidence`, `access_limitations` | `Verified Official` / `Officially Linked / Authorized` / `Third-party Retailer / Reseller` / `Creator / Affiliate` / `User Community` / `Unverified / Ambiguous` / `Unavailable`; presence is not attributable sales, retention, platform control or entity ownership |
| `CommerceSignalRecord` | `id`, `subject_entity_id`, `platform`, `platform_presence_id`, `merchant_or_seller_identity`, `original_url`, `listing_or_offer_id`, `product_id`, `generation_sku_variant`, `new_used_refurbished`, `bundle_or_subscription_terms`, `market_region`, `currency`, `displayed_list_price`, `observed_offer_price`, `promotion_and_eligibility`, `tax_shipping_return_basis`, `stock_or_availability_display`, `seller_of_record`, `fulfillment_role`, `rating_and_review_scope`, `reported_sales_or_badge_definition`, `publication_date`, `observed_date`, `source_ids[]`, `evidence_ids[]`, `lineage_id`, `hypothesis_and_alternatives`, `confidence`, `access_limitations` | `Listing / Observed Offer` / `Public Rating or Sales Badge` / `Customer Report` must not be promoted to completed transactions, unit sales, representative satisfaction, gross margin, recognized revenue or LTV without independent outcome evidence |

Use the canonical `business_function_tags[]` from `references/classification-routing.md` (e.g. `brand_pr`, `demand_creation`, `commerce_conversion`, `community_voc`, `crm_retention`, `talent_employer`) while preserving any evidenced secondary roles. Do not infer an actor's role from the platform's general capability. A source-screening action such as `Retrieval Attempted` is not a Presence Status, a Coverage Status or proof that an account exists. For commercial peer comparison, document equivalent buyer, market, SKU/tier, time, seller, condition, offer scope and any unavailable metric denominators. Platform rankings, followers, views, review counts and social engagement must not become cross-platform business-performance scores without a defensible independent method.

For `PlatformPresenceRecord`, choose exactly the documented presence status; an unofficial seller must not silently become a verified official shop. For `CommerceSignalRecord`, maintain offer/currency/price basis, date, seller, condition and matched SKU for comparisons; when information is not publicly available, record `Unknown` rather than inventing platform analytics. `SocialGTMSignalRecord` may use multiple business-function tags, but the identity/account reference is not duplicated into one account per function.

Do not populate these records with unnecessary personally identifying details or a covert roster of individuals. Prefer employer-/business-unit-level observations; if a publicly named executive's role is materially relevant, cite the authorized public disclosure and the date. Where the same vacancy appears on multiple job boards or the same post is mirrored across sites, preserve separate Source IDs if actually accessed but attach a common `lineage_id` and do not count them as independent decisions or hires. For material signals record `publication_date` versus `observed_date` separately; an expired listing remains a historic observation, not a currently open requisition.

#### CommerceSalesMetricRecord — optional working record

Use this working record **only when sales/GMV/order-volume/channel-performance evidence is material**. It does not modify or expand the eight strict record types; it can reference an existing `CommerceSignalRecord` or `PlatformPresenceRecord`. One dated measurable claim is one record; avoid embedding several noncomparable counters in a single value.

| Field | Content / constraint |
|---|---|
| `id`, `subject_entity_id`, `platform`, `merchant_identity`, `presence_or_commerce_signal_id` | Resolved actor, marketplace, seller/channel; the optional linked working-record ID must exist |
| `product_id`, `sku_variant_condition`, `market_region`, `channel_role` | Exact product and market scope; retailer sell-through vs distributor sell-in vs owned DTC, as supported |
| `metric_name`, `raw_observation`, `reported_value_or_range`, `unit`, `currency` | Native text and semantics; nullable numeric value for absent/ambiguous data; no synthetic conversions |
| `metric_definition`, `measurement_start`, `measurement_end`, `date_basis`, `publication_date`, `observed_date` | Time window, paid/order/shipped/settled/accounting definition, timezone when material; date of observation is not presumed reporting period |
| `gross_net_refunds_taxes_basis`, `seller_and_fulfillment_scope`, `reporting_entity_scope` | Fees, discounts, returns, shipping, tax, principal/agent treatment, consolidation and duplicates |
| `evidence_class`, `method`, `model_assumptions[]`, `range_or_sensitivity`, `calibration_basis` | One of `Reconciled Actual`, `Officially Reported`, `Method-disclosed Estimate`, `Observed Sales Indicator`, `Unknown`; transparent method or `Unknown`, without fictitious uncertainty bands |
| `source_ids[]`, `evidence_ids[]`, `lineage_id`, `access_tier`, `comparison_limits[]`, `confidence` | Original material, lawful accessibility, duplicate provenance and the maximum justified claim strength |

Never relabel `Officially Reported` as audited/reconciled actual merely because it comes from the platform, or `Observed Sales Indicator` as unit sales. A financial statement may establish consolidated revenue without establishing that marketplace's revenue or that SKU's transactions. Evidence classifications are **metric quality labels**, not replacements for Coverage Status or Confidence.


#### InvestmentThesisRecord
Use `id`, `subject_entity_id`, `decision_or_mandate`, `thesis`, `time_horizon`, `key_assumptions[]`, `supporting_evidence_ids[]`, `counter_evidence_ids[]`, `alternative_explanations[]`, `falsifiers[]`, `decision_thresholds[]`, `material_unknowns[]`, `revalidation_triggers[]`, `status` (`Supported` / `Partially Supported` / `Challenged` / `Falsified` / `Unknown`), `confidence`. The record may express a **competitive thesis** instead of an investment thesis when the decision is competitive strategy; do not fabricate mandates or numeric thresholds.
#### RiskRecord
Use `id`, `entity_id`, `risk_statement`, `risk_kind` (`Commercial` / `Financial` / `Legal` / `Tax` / `Technology` / `Operational` / `Organizational` / `Regulatory` / `Security` / `Capital` / `Other`), `risk_state` (`Material Red Flag` / `Decision Blocker` / `Deal Breaker` / `Hypothesis` / `Resolved / Mitigated`), `evidence_ids[]`, `counter_evidence_ids[]`, `impact_mechanism`, `scope`, `potential_severity`, `verification_needed[]`, `possible_mitigation`, `remaining_uncertainty`, `decision_impact`, `confidence`. These are risk labels, **not Coverage Status values**. Allegations, unresolved data and verified events must not be conflated.
#### DueDiligenceRecord
Use `id`, `subject_entity_id`, `stream` (`Corporate` / `Commercial` / `Financial` / `Legal` / `Tax` / `Technology` / `Operations` / `People` / `Customer` / `Regulatory` / `Valuation` / `Integration`), `evidence_access`, `coverage_status`, `examined_source_ids[]`, `finding_ids[]`, `open_document_requests[]`, `specialist_review_needed`, `risk_ids[]`, `limitations`, `next_test`, `as_of_date`. A completed public-source stream remains **preliminary**, not a representation that a formal audit was conducted.
#### IntelligenceEventRecord
Use `id`, `subject_entity_id`, `event_type`, `event_status` (`Announced` / `Filed` / `Approved` / `Effective` / `Completed` / `Observed` / `Disputed / Unknown`), `event_date`, `publication_date`, `observed_date`, `source_ids[]`, `lineage_id`, `factual_statement`, `hypothesis`, `alternative_explanations[]`, `decision_impact`, `revalidation_trigger`, `confidence`. Different dates have different meanings; one article is not a completed event unless it actually documents completion.
### Platform retrieval coverage requirement
After `Mandatory Screening`, for material platform-facing domains at Highest depth, deliver a **Platform Retrieval Coverage Register** (the existing Channel Source-Screening & Retrieval Decision Register view) covering the applicable major social/content/community, marketplace, social-commerce, DTC and regional/vertical/B2B sources. Each considered platform (`Primary / Secondary / Out of scope`) must show `platform / source family / country-language / actor-product-SKU / priority / actual query or URL / attempted date / access method / retrieval state / result / attribution basis / evidence IDs / exclusion or coverage gap`. Only `Retrieval Attempted`, `Observed Source`, or `Attribution Verified` attest actual work; `Screened Only` does not. Document primary platforms not attempted, access blocks, search-index limits and missing evidence; do not claim comprehensive retrieval from a candidate list. Connect material findings to Source/Evidence IDs and comparisons to equivalent peer coverage. This is a working register, **not** a ninth strict JSON record.
### Reusable registers
#### Entity / Ownership / Brand Boundary Register (when actor research is material)
| Entity ID | Formal Name | Type / Jurisdiction | Parent / Relationship / Effective Date | Business & Reporting Perimeter | Source IDs | Confidence | Unknown / Limitation |
|---|---|---|---|---|---|---|---|
#### Competitive Thesis and Threat Register
| Thesis ID | Entity / Reference Actor | Thesis / Mechanism | Supporting IDs | Counter-evidence / Alternatives | Falsifier / Trigger | Impact / Response | Confidence |
|---|---|---|---|---|---|---|---|
#### Investment DD / Material Risk Register (when explicitly requested)
| Stream / Risk ID | Subject / Decision Mandate | Evidence Access / Coverage | Finding / Evidence IDs | Red Flag / Blocker / Status | Missing Verification | Decision Condition / Mitigation | Reviewer / Date |
|---|---|---|---|---|---|---|---|
#### Hiring & Organizational Signal Register (when workforce evidence is material)
| Signal ID | Employer / Entity / Role | Platform / Original Listing | Function / Skills / Location | Posted / Observed / Status | Lineage & Source IDs | Advertised Demand vs Verified Outcome | Alternative Explanation / Confidence | Decision Relevance |
|---|---|---|---|---|---|---|---|---|

#### Public Social & GTM Signal Register (when public positioning/marketing evidence is material)
| Signal ID | Attributed Account / Entity | Platform / Post or Ad | Claim / Observable Metric & Definition | Publication / Observation / Region | Source & Lineage IDs | Unsupported Outcome Claims | Alternative Explanation / Confidence | Strategic Implication / Trigger |
|---|---|---|---|---|---|---|---|---|

#### Platform Retrieval Coverage Register / Channel Source-Screening & Retrieval Decision Register
| ResearchItem / Actor | Region / Buyer / Function Tags | Source Family / Named Candidates | Relevance & Priority | Actual Action (`Screened Only` / `Retrieval Attempted` / `Observed Source` / `Attribution Verified`) | Query / URL / Checked Date | Coverage Status / Access & Omission Reason | Source / Evidence IDs / Next Test |
|---|---|---|---|---|---|---|---|

This is a **view over existing `ResearchItem`, `CoverageRecord` and `SourceRecord`**, not a ninth strict JSON record or a substitute Coverage Status. Store selection criteria, search-action state and attempted-query notes in `ResearchItem.method` / `ResearchItem.notes`; store terminal coverage and omission/access rationale in `CoverageRecord.reason`; create `SourceRecord` only for material actually consulted evidence with a verifiable source and link, not an invented inaccessible page. Record an `Actual Action` only when truthful; `Screened Only` closes only immaterial/out-of-scope channels or a source family whose evidence cannot change the decision; Primary platforms at Highest depth require actual retrieval attempts or explicit documented limitations. An attempted but inaccessible source may close as `Unavailable` / `Limited Evidence`; lack of a public result is never proof that a company has no account, offer or sales. Do not list every global platform in the final report merely to show screening; preserve the decision log for material choices and exclusions.

#### Platform Presence & Functional Role Register (when channel coverage is material)
| Presence ID | Actor / Brand | Platform / Verified Account or Store URL | Role Tags / Journey Stage | Market / Seller / Fulfillment | Presence Status / Attribution Basis | Source & Observation Date | Evidence Gap / Confidence |
|---|---|---|---|---|---|---|---|

#### Commerce, Retail Offer & Channel Register (when listings, pricing or retail competition are material)
| Signal ID | Actor / Merchant / Platform | Matched SKU / Condition / Bundle | Region / Currency / Date | Price / Promotion / Tax / Shipping Basis | Seller / Fulfillment / Review or Badge Definition | Source & Evidence IDs | Verified Outcome vs Unsupported Inference / Confidence |
|---|---|---|---|---|---|---|---|

#### Commerce Sales & Sell-through Evidence Register (when channel sales affect a material Finding)
| Metric ID | Actor / Seller / Platform / SKU / Region | Metric, Value or Unknown & Native Definition | Sales Evidence Class | Period / Date Basis / Observation Date | Gross/Net / Refund / Currency Basis | Source / Method / Evidence IDs | Reconciliation / Duplication / Access Limits | Comparable Result / Strategic Implication |
|---|---|---|---|---|---|---|---|---|

Use separate rows for sales metrics and retail listing/offer evidence; preserve the source's original precision. Only aggregate or compute channel shares from reconciled, non-overlapping, definition-compatible measures and a documented denominator. If sources only reveal sales badges or purchase rankings, name the section `Observed Commerce Indicators` rather than claiming measured sales.


#### Intelligence Event Register
| Event ID | Entity | Event / Status | Event / Publication / Access Date | Source & Primary Origin | Interpretation / Counter-explanation | Decision Impact | Revalidation Trigger |
|---|---|---|---|---|---|---|---|
#### Market Classification Register (when market claims are material)
| Market | Basis | Economic Buyer / Procurement | End User / Role | Vertical / Scenario | Source / Evidence IDs | Confidence | Scope / Unknown |
|---|---|---|---|---|---|---|---|
#### Team Execution Assignment Register (when downward management output is requested)
| Priority | Goal / Deliverable | Accountable Owner / Decision Rights | Milestone / Due | Dependencies / Resources | Acceptance Criteria / Metric | Status / Evidence | Review / Escalation |
|---|---|---|---|---|---|---|---|
Use this as a supporting working register, not as a ninth strict JSON record type. Distinguish proposed from authorized work; do not invent direct reports, owner consent, delivery dates, resources, or results. Link material workstreams to Finding / Evidence IDs where possible. Track outcomes and blockers; give feedback based on observed work rather than inferred traits.
#### Coverage Register
| Analytical Domain | Requirement | Status | Materiality | Report Visibility | Reason / Evidence Gap | Finding IDs |
|---|---|---|---|---|---|---|
#### Evidence & Source Register
| ID | Source Type | Publisher / Owner | Date | Product / SKU / Region / Version / Entity Context | Claim / Evidence Role | Lineage | Confidence | Link / Internal Ref |
|---|---|---|---|---|---|---|---|---|
#### Finding Register
| Finding ID | Finding | Evidence IDs | Counter-evidence | Confidence | Materiality | Visibility | Trade-off | Strategic Implication | Action |
|---|---|---|---|---|---|---|---|---|---|---|
Use the full tables for auditable research outputs where applicable; do not fill them with synthetic data. Prefer sequential `S01 → S02 → S03` numbering in final source appendices. Ensure all actual material sources, image sources, and specification sources are captured.
### Manual validation protocol
#### Structure
1. The Skill root contains one `SKILL.md` and a `references/` directory, with the optional root `README.md`. All referenced Markdown paths must resolve within this layout.
2. `SKILL.md` begins with valid YAML frontmatter with `name` and `description`; its name matches the deployed `marketscope` folder.
3. No instructions point to missing `assets/`, `templates/`, `schemas/`, `scripts/`, `tests/`, or other retired directories.
4. `Hardware` and `Software` remain the only top-level **product** classifications; Company, Brand and Business Unit are distinct Research Subjects, not product categories. `Smart Instruments` must be recorded as the `subcategory` under `Hardware → Musical Instruments & Performance Controllers`, never as a top-level classification or a standalone Hardware `category`. Product form/category, market/buyer/user classifications and evaluation weighting remain independent.
5. `Consumer` / `Professional` / `Enterprise` / `Government` / `Defense` are overlapping target-market labels, not replacements for product categories. `Professional` may coexist with `Consumer`; `Defense` may coexist with `Government` or `Enterprise`.
#### Record integrity
1. For each of the eight defined record types, all **Required** fields exist, enumerated values match the tables above, nullable fields are used only where allowed, and no unsupported fields are inserted.
2. No two records of the same type share an ID.
3. Every `EvidenceRecord.source_ids[]` value resolves to an existing `SourceRecord.id`.
4. Every `FindingRecord.evidence_ids[]` and `counter_evidence_ids[]` value resolves to an existing `EvidenceRecord.id`.
5. Every recommendation `finding_ids[]` value resolves to an existing `FindingRecord.id`.
6. Every `CoverageRecord.finding_ids[]` and `StrategicFrameworkRecord.input_finding_ids[]` references a real Finding; every framework `input_evidence_ids[]` and `counter_evidence_ids[]` references real Evidence. Every `ContradictionRecord.evidence_ids[]` references Evidence and contains at least two items.
7. Check ID traceability backward: `Recommendation → Finding → Evidence → Source`. A register with missing references is incomplete, not validated.
8. For each `ProductRecord`, validate `target_markets[]` and `potential_fit_markets[]` values; each evidenced market must have at least one `Official Targeting` or `Verified Adoption` assessment with resolvable Source/Evidence IDs. A `Potential Fit` or `Unknown` assessment alone must not add the label to `target_markets[]`.
9. Audit buyer / end-user / industry / scenario claims for independent evidence or visible `Unknown`/hypothesis labeling. Do not silently convert B2B / B2C / B2G transaction models into product categories, or claim public-sector or defense eligibility without explicit corroboration.
10. For Company/Brand/BU records, resolve entity IDs and RelationshipRecord endpoints, jurisdiction, period and financial perimeter; require source IDs for material ownership/control, partnership and revenue assertions.
11. Thesis, Risk, DueDiligence, IntelligenceEvent and optional Hiring/Social/PlatformPresence/Commerce signal records must link to existing entity/evidence/source IDs, use valid label values, and distinguish a public-source evidence gap from a verified negative claim.
12. For source platforms and events, verify primary origin, access permission, date semantics, and event-status transitions. Announced funding ≠ funds received, job posted ≠ hired, professional profile ≠ verified organizational structure, social engagement/ad presence ≠ customer acquisition or sales, retailer listing ≠ channel ownership / order volume / recognized revenue, review count ≠ units sold, filed patent ≠ granted, and one cited registry fact ≠ multiple independent evidence origins.
13. For material social/retail channel claims, validate canonical platform-to-business-function tags, actor/account/store identity, official vs third-party/affiliate status, regional merchant eligibility, SKU/version and merchant-specific offer comparability, promotion/tax/shipping/date basis, review lineage, metric level and disclosure of unavailable outcomes.
14. For material channel-source screening, verify `Screened Only` vs `Retrieval Attempted` vs `Observed Source` vs `Attribution Verified` is not conflated with Coverage/Presence status, and the actual search dates and query/URL, in-scope geographic and buyer boundary, selected/omitted source families, access constraints and decision reasons are auditable. No unstated visits, invented blocked pages or universal negative-search claims.
15. For every material `CommerceSalesMetricRecord` or sales Finding, validate the exact metric and evidence class, seller-of-record vs brand/issuer, authorized access tier, actual reporting interval vs observed date, SKU/region/condition, paid/order/shipped/refund basis, gross-to-net treatment, FX and units, original source links, model assumptions and uncertainty where estimated, independence, channel deduplication and permitted aggregation. A platform badge, review volume, product rank, revenue announcement or seller report must not be silently upgraded to platform-wide net sales, company revenue, profit or share. Missing definitional fields must yield `Unknown` or a bounded qualitative indicator.

#### Research and output
1. All in-scope ResearchItems and, at Highest depth, all mandatory Analytical Domains **in the selected Product / Competitor Intelligence / Investment Due Diligence protocol** have terminal Coverage Statuses. `Not Applicable` has a structural reason.
2. Cross-check Research Subject and Intent, product category (when Product), evidenced vs hypothetical target markets, buyer vs end user, business entity/brand/BU/ownership/reporting perimeter, industry, geography, source/event/accounting dates, version/SKU, price/valuation basis, and measurement methods against the report.
3. Verify unresolved contradictions, alternative explanations, independent evidence dimensions, Confidence, and decision-changing Unknowns remain visible.
4. **For Product reports**, verify the first-party product visual (or `Unavailable`) and Product Specification Matrix. **For actor/DD reports**, check the entity/group/brand boundary, comparative actors, public/private evidence-access distinction, thesis/falsifier/risk registers, dated financial/event claims, open verification requests and appropriate report label. All reports need Research Cutoff and source register consistency.
5. Preserve valid Findings in Core / Supporting / Appendix and retain linked sources, even for lower-materiality findings.
6. When a team execution register is requested, check that proposed and approved assignments are distinguishable, owners and decision rights are substantiated or explicitly unassigned, completion evidence is not invented, and meaningful checkpoints / escalation conditions are visible.
7. For bare actor-name default, verify a Competitor Intelligence report—not product review or automatic Investment DD. If the report is based on public sources, do not represent incomplete financial, tax or legal verification as transaction DD completion.
8. Check entity relationship / event / financial records with exact originals, attribution, reporting/perimeter scope and primary origin; retain decision-changing counter-evidence and revalidation triggers.
9. Where workforce/social/commerce signals inform material Findings, check original employer/page/account/shop/merchant identity, recruiter or affiliate involvement, repost/syndication lineage, dates, region, seller/fulfillment, SKU and offer terms, visible status, metric definition, review sampling and privacy/access limitations. A vacancy, campaign, store, marketplace listing or public sales badge is not evidence of realized hiring, attributable revenue, profit, customer adoption or marketing effectiveness.
Complete these checks before delivery. They are verification instructions, not evidence that an automated validation has run.
## Source and evidence provenance
### Scope, dates and origin
Preserve research cutoff; jurisdiction, entity/group/brand/BU perimeter or exact product/SKU/variant/version; market/buyer context and evidenced `Official Targeting / Verified Adoption / Potential Fit / Unknown`; event/effective, publication, observation, source-update and price dates as distinct; actual `Public / Licensed / Authorized Internal / Professional Third-party / Unavailable` access. `SourceRecord` uses `S01`, `S02`… where feasible with original title, owner, URL/ID, original lineage, type, date, claim-role, subject applicability and quality.
### Original records and assets
- Product images: official product/press/media asset or `Unavailable`; original first-party page/asset URL, Source ID, version/variant match, date and any attribution. Specs: exact official manual/datasheet/source, SKU/region/version, supported fields and dates. Mirrors are not first-party originals.
- Actor events: cite exact issuer filing, official registry/IP/court/procurement item, hiring source, public attributable post/ad or media report; platform homepages are insufficient. 36Kr and Tianyancha/Qichacha/Aiqicha can aid discovery but shared registry facts are not independent origins. Preserve entity, jurisdiction, event status, material periods/dates, access and claim type; `Announced` is not `Completed`.
- Hiring: original employer/agency/platform, vacancy ID/URL, role/location, pay-period if published, posting/update/check dates, visible status, repost/syndication origin and access boundaries. Advertised demand ≠ hire, real salary or headcount increase; no restricted personal data.
- Social/community: attributed account/post/ad URL/ID, native published/check dates, region/audience where visible, organic/paid/affiliate distinction, metric semantics, community sampling, repost lineage and access. Presence/engagement ≠ ad spend, converted demand or revenue.
- Commerce: account/store/listing URL/ID, brand vs seller-of-record/fulfillment, official vs authorized reseller vs third-party status, exact SKU/condition/bundle/country, price/promotion/coupon/tax/shipping/return context and dates. Reviews carry distinct origin, product version, sampling/purchase/incentive flags as visible; follow VoC RAW–CLEAN–GOLD.
- Sales: original native counter/line item, evidence class, measured interval vs check date, seller/entity, exact SKU, units/FX, gross/net/refund/settlement logic, authorized source rights and model/reconciliation parameters; estimates require assumptions and uncertainty. Public sales badges/reviews are indicators, not verified sell-through, company revenue or profit. Minimize sensitive order data.
### Traceability and audit tail
Always support `Recommendation → Finding → Evidence → Source` with resolvable IDs and original origin independence; strategic frameworks reference Findings/Evidence rather than creating unsupported facts. Include the Evidence & Source Register without deleting material sources for brevity; reuse the table schema above.
As applicable retain scope/cutoff, method and Test Bench, market classifications, VoC cohorts, contradiction and failure logs, platform coverage/attempt log, hiring/social/retail/sales and entity-event registers, alternatives, limitations and decision-changing Unknowns. Inaccessible private data is not proof of absence. A complete public-only study must disclose gaps instead of claiming licensed API, account or data-room access.
## Lateral, upward and downward organizational outputs
Translate the **same sourced Finding, Confidence and uncertainty** for the authorized audience; communication does not change underlying facts or create real authority.
| Direction | Decision use | Output chain |
|---|---|---|
| Lateral / Cross-functional | Align peers and dependencies without line authority | `Finding → Evidence → Impact → Open Question → Handoff / Owner → Done Criteria` |
| Upward / Executive | Enable a decision/resource ask | `Conclusion → Business Impact → Evidence → Options → Recommendation → Risks → Ask` |
| Downward / Team | Execute approved work with accountability | `Approved Goal → Outcome/Metric → Priority/Scope → Owner/Authority/Resources → Milestones/Dependencies → Evidence Checkpoints → Feedback / Next Action` |
For lateral work distinguish shared facts from technical-root-cause hypotheses, identify functions and handoffs without assigning blame; preserve disagreement and uncertainty. Executives receive concise conclusions with detail in Appendix, not discarded records.
For management only when requested, distinguish proposed from authorized commitments; require real decision rights, resources, milestones, acceptance criteria and escalation. Unknown owners are `To assign`, not invented. Track outputs and observed progress rather than hypothesized employee traits; use `Observed output → Impact → Expected standard → Support/change → Follow-up` and close with evidence-based iteration. Do not manufacture team structure, targets, dates or consent.
**Team execution register (optional):** `Priority / Outcome / Accountable owner & rights / Due or milestone / Dependencies & support / Acceptance evidence / Status / Review or escalation`; use existing template in Reusable Registers when applicable. If only a failure is observed, label causal theories and their falsification tests rather than presenting a speculative engineering/organizational root cause as fact.
## Behavioral regression acceptance

**Platform/channel acceptance fixtures (executable research checks, not claimed completed online tests):**

| Fixture / request | Expected routing and evidence boundary | Failure to reject |
|---|---|---|
| Coverage-first highest-depth channel audit | For each primary market/category, attempt major applicable social/community and commerce platforms or document platform-specific access/exclusion; record query, region, date and outcome | Candidate index or `Screened Only` mislabeled as completed retrieval; silent omissions |
| Local-language / alias discovery | Use legal/brand aliases, native scripts, models and official outbound links; test attributable user content and regional resellers | English-only search silently treated as adequate in non-English markets |
| `SONOS` (bare company/brand) | Actor C0–C8; verify corporate/brand boundary; screen region-specific official DTC, YouTube/Reddit, authorized retail and Amazon offers only where relevant; seller and product generation reconciled | Retailer presence treated as a brand-operated shop, review volume treated as sales |
| `泡泡玛特` (brand/operator ambiguity) | Actor identity resolution; conditionally screen Xiaohongshu, Douyin, WeChat, Tmall and material international channels with jurisdiction and operating entity identified | Social popularity asserted as revenue, subsidiaries silently merged |
| `Nothing Phone` (named product family) | Product P0–P10; resolve model/SKU/country; compare original brand shop vs retailer offers and public review cohorts | Different generations, sellers or tax regimes compared as identical |
| Enterprise AI SaaS / Agent product | Product or actor route by input; prioritize LinkedIn, official plans, relevant developer/professional communities and verified software distribution | Mandatory consumer marketplace sweep or app ratings asserted as paying users |
| Japanese consumer brand | Geography overlay triggers appropriate LINE, Rakuten, Amazon Japan and Yahoo! Shopping screening; verify localized availability and merchant terms | Platform functionality in another country assumed available in Japan |
| Official-looking reseller and mirrored post | Check original outbound links, advertiser/merchant identity, shared repost lineage and role boundaries | Store/creator attributed to brand as owned; reposts counted as independent evidence |
| Inaccessible social platform / expired offer | Record attempted query/URL, market, checked date and access limit; preserve `Unavailable` / `Limited Evidence` as appropriate | "No account/sales/hiring" concluded from access failure or absent search result |
| Cross-platform metric comparison | Compare matched periods and definitions, normalize price/offer and review samples or explicitly refuse numeric ranking | Followers/reviews/sales badges converted into GMV, CAC, profit or share |
| Public product sales badge with no time definition | Observe exact seller/SKU/native counter, label `Observed Sales Indicator`, log period `Unknown` and refuse an exact sales total | Badge relabeled as realized units, annual sales or company revenue |
| Authorized seller transactions with returns | If actual authorized exports exist, reconcile paid/shipped/refunded/net metrics for a bounded store/SKU/period; distinguish seller-level from brand totals | Gross orders presented as net sell-through or full brand/platform market share |
| Third-party marketplace sales forecast | Check explicit model, source license, calibration, geography, timeframe and sensitivity; else `Not Estimable / Limited Evidence` | Opaque point estimates or review-to-sales ratios presented as verified actual sales |
| Wholesale sell-in and online sell-through overlap | Reconcile reporting perimeter and overlapping downstream units before calculating channel contribution | Distributor purchases added to identical end-consumer sales as incremental brand sales |

For each fixture inspect the coverage decision log, selection rationale, original source URLs, exact subject/entity/SKU/region boundary, evidence lineage, counter-thesis and final qualification. Static file validation checks instruction consistency, **not** live platform retrieval, site availability, research quality or confirmed access.

Compare the reorganized Skill with the original 17-file baseline on product hardware, software, smart instruments, mixed hardware/software, company, brand/BU, industry, multiple actors, explicit investment diligence, publicly limited evidence and three organizational communication routes. Verify routing, mandatory domain status, factual/source coverage, counter-evidence, classification, traceability, risks, recommended actions and subject-appropriate output. A static check cannot prove equal or better research quality; conduct representative real-case end-to-end evaluations before making that claim.

# MarketScope

**A research-workflow Skill for in-depth product, company, brand, and market investigation.**  
[中文说明](#中文说明)

MarketScope distills long-term practice in market research, product investigation, and competitive analysis into a reusable agent workflow. It preserves repeatable research methods—scope definition, source discovery, evidence validation, comparative analysis, and documentation—while keeping personal aesthetics, taste, and final decision policy outside the method. The result is a research process that can serve different users and decisions without inheriting the author's preferences.

## 1. Core Value

**A product, company, or brand name is enough to start a deep investigation.** The user does not need to prepare a full research brief, compile a competitor list, or name the websites to search. Given an identifiable subject and suitable tools, MarketScope determines the research route, constructs initial coverage, retrieves accessible evidence, and organizes an in-depth report. Additional context can improve relevance but is not required to begin.

| Input | Research mode | Primary focus |
|---|---|---|
| Product name or model | **Strategic Product Intelligence** | Positioning, use cases, model/SKU, specifications, user experience, alternatives, lifecycle, and price–value |
| Company, brand, or business unit | **Competitor Intelligence** | Legal and operating boundaries, portfolio, capabilities, competitive mechanisms, organization, channels, and strategic change |
| Industry or category | **Market & Industry Intelligence** | Market boundaries, demand, participants, structure, economics, and uncertainty |
| Multiple named subjects | **Comparative Intelligence** | Consistent comparison units, evidence-based trade-offs, scenarios, and unresolved differences |
| Explicit investment, acquisition, or transaction request | **Investment Due Diligence** | Preliminary public-source diligence, downside, unverified conditions, and transaction-specific questions |

A recognizable bare name defaults to **Highest / Strategic Deep Research**, **Remote** evidence mode, and actual public-source access unless authorized sources are provided. An ordinary company-name prompt does **not** automatically initiate investment due diligence. The user's explicit scope, research depth, and language take precedence over defaults; ambiguous identities must be resolved rather than silently conflated.

The principal benefit is **less manual work before human analysis**. MarketScope streamlines initial scoping, platform discovery, searching, evidence collection, deduplication, cross-market normalization, and research-base assembly.

| Recurring research overhead | What the Skill standardizes |
|---|---|
| Deciding what and whom to investigate | Subject classification, scope, research modes, and comparable units |
| Finding dispersed materials | Official, corporate, social, commerce, hiring, professional, and regional source coverage |
| Searching and collecting evidence | Actual retrieval attempts, source capture, and access-gap documentation |
| Reconciling inconsistent information | Attribution, independence checks, dates, product/SKU and metric definitions |
| Preparing a usable research base | Evidence-linked findings, comparison matrices, source registers, and visible unknowns |

**The aim is to improve the research workflow, not to produce an execution-ready plan or take over the user's judgment.**

## 2. Workflow

```text
Subject name / research question
  → Identify the entity, product/SKU, market, and research scope
  → Select the primary research protocol
  → Plan subject-domain and source-platform coverage
  → Attempt retrieval across major applicable sources
  → Verify origin, attribution, comparability, and counter-evidence
  → Synthesize supported findings and unresolved questions
  → Deliver an auditable, in-depth research report
  → User interpretation and decision
```

| Step | Execution requirement |
|---|---|
| **Identify** | Separate legal entity from brand, group from subsidiary, and product family from generation, model, and regional SKU. |
| **Plan** | Map mandatory research domains, competitors, geographic markets, official sources, and platform candidates. |
| **Retrieve** | Actually search major applicable platforms at Highest depth or document a concrete access or scope reason. |
| **Verify** | Check source origin, independence, date, actor attribution, seller/employer identity, product variants, definitions, and adverse evidence. |
| **Compare** | Align like-for-like units and test alternative explanations rather than treating promotional claims as established outcomes. |
| **Report** | Lead with material findings and preserve supporting records, contradictions, source links, and important unknowns. |
| **Check** | Apply breadth and depth completion gates without pretending unavailable evidence was obtained. |

The primary procedures are **Product P0–P10**, **Competitor C0–C8**, and **Investment D0–D8**. **Platform Retrieval R0–R5** and **Commerce Sales Intelligence S0–S8** operate across relevant research modes. Market and multi-subject comparative research use the shared procedures and a subject-specific coverage plan, rather than claiming separate, complete phase-by-phase protocols. Voice of Customer (VoC) processing follows `RAW → CLEAN → GOLD`.

## 3. Platform Coverage

MarketScope uses a **coverage-first** approach: identify the relevant platform universe by subject, category, geography, audience, and source availability; search the major applicable sources; only then interpret their business roles. A candidate platform is **not** evidence that the subject operates an account or shop there.

| Source family | Illustrative platforms and sources | Evidence to look for |
|---|---|---|
| **Official and corporate** | Regulatory filings, corporate registers, investor relations, official releases; 36Kr, Tianyancha, Qichacha, Aiqicha | Ownership, company identity, disclosures, funding or event leads |
| **Hiring and professional** | Company careers pages, LinkedIn, Maimai, Liepin, 51job, Zhaopin, BOSS Zhipin | Public vacancies, skills, locations, employer and organizational signals |
| **China social and content** | WeChat, Weibo, Douyin, Kuaishou, Xiaohongshu, Bilibili, Zhihu | Releases, campaigns, product demonstrations, reviews, community discussion |
| **Global social and content** | Facebook, Instagram, TikTok, YouTube, X, Threads, Reddit, Discord, Pinterest, Snapchat | Regional content, creator coverage, user experience, public advertising |
| **Regional communities** | LINE, Kakao, Naver communities, Zalo, VK, Dcard, PTT | Local-language activity, customer communication, discussion and feedback |
| **China retail and social commerce** | Taobao, Tmall, JD.com, Pinduoduo, Douyin Commerce, Kuaishou Commerce, Xiaohongshu Commerce, WeChat Stores | Listings, sellers, SKU, prices, reviews, promotions, sales indicators |
| **Global and regional retail** | Amazon, Walmart, eBay, Etsy, AliExpress, Temu, TikTok Shop, Shopee, Lazada, Rakuten, Yahoo! Shopping Japan, Coupang, Mercado Libre | Availability, channel presence, offers, reviews, regional comparisons |
| **DTC, B2B, and digital distribution** | Official stores, Shopify-powered sites, Alibaba.com, 1688, IndiaMART, App Store, Google Play, Steam, G2, GitHub, Hugging Face | Direct commerce, wholesale, software distribution, technical ecosystems |

For each material market, prioritize sources as `Primary`, `Secondary`, or `Out of scope`. Search native-language and translated names, brand and legal-entity aliases, product generations and SKU variants, official outbound links, and independent user or reseller content where relevant. Platform access, country restrictions, and information value determine the feasible search depth.

**Retrieval must be auditable.** The `Platform Retrieval Coverage Register` distinguishes:

| State | Meaning |
|---|---|
| `Screened Only` | Considered for relevance; no retrieval is claimed |
| `Retrieval Attempted` | A traceable platform-specific search or access attempt was made |
| `Observed Source` | Related content was found, but attribution may still be unverified |
| `Attribution Verified` | The account, operator, seller, employer, or content relationship was substantiated |

Record market, priority, query or URL, retrieval date, outcome, source links, and unresolved gaps. **Not searched, no public result, blocked, and not applicable are different outcomes.** A failed search is not proof of absence. Platform business functions—brand, education, acquisition, commerce, fulfillment, CRM, community, B2B, recruiting, developer ecosystem—help interpret *observed* activity; they must not preempt relevant retrieval. **Platform capability ≠ observed company activity ≠ verified business outcome.**

## 4. Sales Evidence

For sales performance, channel traction, and market-share questions, **S0–S8** first establishes the legal or reporting entity, seller, platform, region, model/SKU, period, and metric definition. Evidence is classified before figures are compared:

| Tier | Interpretation |
|---|---|
| `Reconciled Actual` | Authorized or auditable transaction records reconciled to a defined seller, period, and measure |
| `Officially Reported` | A properly attributed, specifically defined company or platform disclosure |
| `Method-disclosed Estimate` | An estimate with stated data inputs, assumptions, scope, and uncertainty |
| `Observed Sales Indicator` | Public sold-count labels, ranking, reviews, or other signals—not confirmed transaction volume |
| `Unknown` | Accessible evidence does not support a defensible numerical conclusion |

**GMV, recognized revenue, and profit are not interchangeable.** Listed price is not realized price; sell-in is not sell-through; gross orders are not refunded-adjusted units. Currency, taxes, fulfillment, incentives, duplicate channel flows, seller identity, and observation windows affect comparisons. Never infer exact sales or market share from review counts, popularity, storefront presence, or opaque estimates. Restricted seller dashboards, paid databases, and APIs require legitimate host access and authorization.

## 5. Research Output

MarketScope produces a **deep, traceable research base**, not a preset business action plan. The report is led by material `Findings`, with evidence organized as `Core / Supporting / Appendix`; it does not mechanically fill every SWOT, PESTEL, or other framework. Important assertions should follow `Source → Evidence → Finding → [Conditional Interpretation / Recommendation]`. Alternatives, contradictions, limitations, and source independence remain visible.

The output contract defines **eight strict structured record types** with optional domain-specific records. Product studies normally provide an official source-backed image (or `Unavailable`) and a Product Specification Matrix. Company and brand studies explain competitive mechanisms rather than merely cataloging facts. Public-source investment analysis is preliminary, not a completed transaction audit.

Completion is checked on two distinct dimensions:

- **Breadth Completion:** required in-scope research domains and major relevant sources have been addressed or clearly marked with an access, evidence, or applicability limitation.
- **Depth Saturation:** further feasible retrieval is unlikely to materially alter findings, confidence, or comparisons; if this cannot be established, the unresolved gap is disclosed.

The report may include conditional interpretations, risks, scenarios, and follow-up questions, but **the choice, approval, resource commitment, and execution decision remain with the user**.

## 6. Known Limitations

¹ **Evidence access.** A Skill specifies a method; it does not provide an autonomous crawler, licensed data, private company records, merchant dashboards, paid subscriptions, platform APIs, or physical product tests. The host must actually support any browsing, connector, file, or account access claimed. Login restrictions, CAPTCHA, privacy settings, paywalls, and lawful access requirements remain binding.

² **Long-term user context.** A name can initiate a general deep investigation, but sustained relevance often improves with prior research, comparison baselines, product scope, target markets, and personal or organizational constraints. That context may be missing, incomplete, outdated, or unavailable to the host. MarketScope must not invent remembered preferences or private history; available context can prioritize inquiry but cannot override evidence quality.

³ **Coverage and implementation.** Public evidence cannot guarantee exhaustive findings, verified commercial outcomes, or representative customer sentiment. Industry and comparative work rely on shared protocols rather than separate complete phase-by-phase SOPs. Written rules are not self-enforcing; actual runs require review and end-to-end evaluation.

⁴ **Decision boundary.** Research methodology is deliberately separated from the author's aesthetic preferences and decision policy. A well-supported report cannot uniquely resolve the user's taste, opportunity costs, risk tolerance, internal resources, or authority to act.

## 7. Project Significance

MarketScope converts accumulated personal research practice into a repeatable workflow that reduces the time spent preparing, searching, collecting, reconciling, and organizing information. Its distinctive interaction—**a name as the starting point for an in-depth research report**—helps users reach a more substantial and inspectable evidence base sooner. The value lies in improving how research is prepared and documented, **not in outsourcing judgment or promising execution-ready recommendations**.

## 8. Installation & Maintenance

```text
marketscope/
├── SKILL.md
├── README.md
└── references/
    ├── classification-routing.md
    ├── research-sop.md
    └── output-contract.md
```

Keep the relative structure intact and load the directory in an agent environment that supports file-based Skills and the required research tools. `SKILL.md` governs behavior; the References define **classification and source routing**, **research and validation procedures**, and **report plus data contracts**. This README describes the project and its use; it is not the operative rulebook.

**Example prompts**

```text
SONOS
Nothing Phone
Research Pop Mart as a competitor across China and international markets.
Compare three AI recording devices by product evidence, user experience, and pricing.
Investigate a Japanese consumer brand using local social and commerce sources.
Study an enterprise AI SaaS company, including professional networks and its technical ecosystem.
Investigate public marketplace sales indicators; estimate only with defensible methodology.
Perform preliminary public-source diligence on a named acquisition target.
```

For more targeted research, add the decision question, territory, study cutoff, competing products, relevant files, or verified prior assumptions. None is mandatory to start from an identifiable name. `MarketScope.json`, when supplied, is an optional portable snapshot of the Markdown files, **not** a runtime prerequisite. After editing source Markdown, regenerate its embedded content and checksums; in case of discrepancy, follow the current Markdown files and their rule precedence.

---

# 中文说明

MarketScope 源于个人长期开展市场调研、产品研究与竞品分析的实践，将反复验证过的研究路径、信息检索习惯、证据标准和资料组织方法提炼为可复用的 AI Agent 工作流。它保留的是**研究方法**，而非作者的个人审美、偏好排序或最终决策机制；不同用户可以在同一份证据基础上形成不同判断。

## 一、核心价值

**只需输入产品、公司或品牌名称，即可启动深度调研。** 用户无须事先完成详细 Brief、列出竞品或指定网站。只要研究对象能够被识别，且运行环境具备相应工具，MarketScope 就会确定研究方向、建立资料范围、执行检索，并组织有来源支撑的分析报告。补充研究目的和个人背景可以提高针对性，但不是调用前提。

| 输入内容 | 研究方向 | 主要内容 |
|---|---|---|
| 产品名称或型号 | **产品研究** | 产品定位、功能规格、用户场景、实际体验、替代方案、生命周期、价格与价值 |
| 公司、品牌或事业部 | **企业竞争情报** | 法律及经营主体、产品组合、组织能力、竞争机制、渠道、市场变化 |
| 行业或品类 | **行业研究** | 研究边界、市场需求、参与者、竞争结构、经济性与不确定性 |
| 多个产品或公司 | **对比研究** | 统一比较口径、差异、取舍、适用条件及无法确认的问题 |
| 明确提出投资、收购或交易 | **投资初步尽调** | 交易相关事实、风险、关键假设与待核查条件 |

仅输入名称时，默认采用 `Highest / Strategic Deep Research` 深度、`Remote` 研究方式，并在实际具备的公开资料权限内执行。用户明确指定的对象、地区、研究重点和深度优先。**普通公司名称不会自动触发投资尽调**；同名主体、集团与品牌、不同产品代际或地区型号必须先区分。

MarketScope 的价值首先体现在**减少正式分析之前的重复劳动**。一次调研通常需要确认主体、确定范围、寻找官网及其他资料源、搜索社媒与电商、收集用户评价和产品参数、比对价格，再处理来源重复、数据矛盾和统计口径。Skill 将其中可标准化的工作转化为有顺序、可核查的流程。

| 常见工作负担 | 对应能力 |
|---|---|
| 从零判断应该研究什么 | 主体识别、研究路由、范围规划 |
| 不知道去哪里找资料 | 官方、工商、招聘、社媒、电商、区域及专业平台的覆盖清单 |
| 重复搜索、复制与整理网页 | 针对适用平台实际检索，记录出处、日期和结果 |
| 同一信息反复出现、说法不一 | 来源归属、独立性、反证与不确定性核查 |
| 型号、区域、价格和数据无法比较 | SKU、币种、卖家、时间、定义与统计口径归一化 |
| 资料很多，但难以复查 | 研究发现、比较矩阵、原始来源和检索台账关联呈现 |

**核心目标是优化调研准备、检索、收集和整理工作流，而不是生成一份可直接照做的商业方案。**

## 二、研究流程

MarketScope 先明确研究对象与覆盖范围，再实际取得证据，最后按发现的重要性组织报告；不会为了形式完整而机械填满 SWOT、PESTEL 等分析框架。

| 阶段 | 具体工作 | 输出或检查重点 |
|---|---|---|
| **对象识别** | 区分公司、品牌、集团、事业部、产品型号与地区 | 避免研究错对象及跨主体混用数据 |
| **范围规划** | 建立研究领域、主要竞品、国家市场及平台候选表 | 确保重要信息源进入检索范围 |
| **实际检索** | 搜索适用的平台、官方记录、独立测评与历史资料 | 有搜索记录，不以平台清单冒充检索结果 |
| **证据核验** | 核对来源、身份、时间、版本、卖家、定义及反例 | 保留冲突与不能验证的事实 |
| **分析比较** | 结合用户问题、产品价值、竞争机制和商业边界 | 形成有证据支持的研究发现 |
| **报告整理** | 组织核心发现、论据、比较结果、资料来源与缺口 | 供用户查阅、复核与后续判断 |
| **完整性检查** | 检查必要领域、关键平台和重要反证 | 明确已完成、证据不足和不可访问的部分 |

研究任务分别由 **P0–P10（产品）**、**C0–C8（企业）**、**D0–D8（投资尽调）**组织。**R0–R5（平台检索）**与**S0–S8（电商销售情报）**是跨研究类型的子协议。行业与多主体比较使用共用方法和针对性的研究覆盖计划；用户之声（VoC）采用 `RAW → CLEAN → GOLD`，保留原始反馈、清理偏差，再提炼可追溯的问题。

## 三、平台覆盖

采用 **Coverage-first（覆盖优先）**：先按照行业、品类、目标地区、语言和研究对象建立候选平台，再实际检索主要适用来源。平台在企业内部承担什么职能，用于解释已经找到的证据，不能成为提前排除重要平台的唯一理由。

| 来源类型 | 代表平台或资料 | 主要检索信息 |
|---|---|---|
| **工商与企业信息** | 官方工商登记、监管披露、企业公告、投资者关系、36氪、天眼查、企查查、爱企查 | 经营主体、股权关系、融资及重大事件 |
| **招聘与职业网络** | 官方招聘页、LinkedIn、脉脉、猎聘、前程无忧、智联招聘、BOSS直聘 | 岗位、技能、地点、招聘主体及组织信号 |
| **中国社媒与社区** | 微信、微博、抖音、快手、小红书、Bilibili、知乎 | 产品发布、营销、测评、用户讨论和口碑 |
| **国际社媒与社区** | Facebook、Instagram、TikTok、YouTube、X、Threads、Reddit、Discord、Pinterest、Snapchat | 海外公开内容、创作者测评、社区反馈、广告信息 |
| **区域社媒** | LINE、Kakao、Naver 社区、Zalo、VK、Dcard、PTT | 本地语言市场、客户沟通及区域反馈 |
| **中国电商** | 淘宝、天猫、京东、拼多多、抖音电商、快手电商、小红书电商、微信小店 | 店铺、SKU、价格、促销、评论与销售线索 |
| **国际与区域电商** | Amazon、Walmart、eBay、Etsy、AliExpress、Temu、TikTok Shop、Shopee、Lazada、Rakuten、Yahoo! Shopping Japan、Coupang、Mercado Libre | 区域供给、商家、报价、评价及商业信号 |
| **独立站、B2B 与数字平台** | 官方商城、Shopify 类独立站、Alibaba.com、1688、IndiaMART、App Store、Google Play、Steam、G2、GitHub、Hugging Face | 自营销售、批发、数字分发、软件与技术生态 |

平台清单是**检索候选池**，并不表示目标企业一定入驻，也不意味着每项数据都能访问。对主要市场中的平台按 `Primary`、`Secondary`、`Out of scope` 归类；最高深度研究应实际尝试检索主要适用平台，或记录具体无法检索、范围不适用的原因。搜索应结合正式名称、别名、当地语言、产品代际、型号、SKU、账号和店铺线索。

检索过程通过 `Platform Retrieval Coverage Register` 记录：

| 状态 | 含义 |
|---|---|
| `Screened Only` | 判断过相关性，没有声称已检索 |
| `Retrieval Attempted` | 实际执行了可追溯的搜索或访问尝试 |
| `Observed Source` | 找到相关材料，但主体归属仍可能未核实 |
| `Attribution Verified` | 已核实账号、商家、招聘主体或内容与目标对象的关系 |

台账应包含平台、地区、优先级、查询或链接、日期、结果、来源和遗留问题。**未搜索、没有公开结果、访问受限和不适用必须区分**；未检索到信息，不代表企业没有业务活动。

## 四、证据核验

平台覆盖率提高，并不自动提升证据质量。取得资料后，必须判断这些材料究竟属于谁、描述何种产品或交易、能支持多大范围的结论。

- **公司与品牌：** 区分母公司、发行主体、子公司、运营公司与品牌。不得直接把集团规模归到单个产品或品牌。
- **社媒与招聘：** 核实官方、地区、经销商、达人、用户或中介身份；岗位发布不等于人员入职，社媒互动不等于销售成果。
- **电商与商品：** 区分品牌自营、平台自营、授权经销商和第三方卖家；对齐 SKU、成色、地区、币种、税费、促销、运费与履约条件。
- **用户反馈：** 保留原始评论来源，处理重复、样本选择偏差、时间跨度、产品代际与激励性内容；少数投诉不能证明整体故障率。
- **来源独立性：** 识别同源转载、新闻稿复述、同步上架商品及相互引用；多个网页不必然构成独立验证。

统一原则是：**平台具备能力 ≠ 企业实际开展活动 ≠ 商业结果已经被证实。** 研究可以记录线索、提出解释，但不能将推测包装为事实。

## 五、销售数据

涉及销量、销售额、渠道贡献或市场份额时，执行 `S0–S8`，先确定统计主体、商家、平台、国家、SKU、时期和指标口径，再对数据分级。

| 证据等级 | 使用边界 |
|---|---|
| `Reconciled Actual` | 已获得合法授权、可以核对的指定主体与时期的交易记录 |
| `Officially Reported` | 企业或平台正式披露、定义明确的销售指标 |
| `Method-disclosed Estimate` | 估算方法、输入数据、范围、假设与不确定性透明 |
| `Observed Sales Indicator` | 公开销量标签、排行、评价数量等可观察信号，不能当作真实成交数据 |
| `Unknown` | 无足够证据支持可靠的数值结论 |

**GMV、确认营收和利润不同；标价不等于成交均价，进货量不等于终端销量。** 退货、跨平台重复交易、经销渠道、税费和统计期间都会影响结果。无可靠数据时应说明无法估算，而不是用评价数或销量排名反推出看似精确的数字。付费数据库、商家后台和平台 API 仅在实际获授权且可访问时使用。

## 六、研究输出

主要交付物是**可追溯的深度调研资料与分析报告**。产品报告通常包含官方资料、规格与价格矩阵、用户场景、体验反馈及竞品差异；企业报告关注产品组合、组织、渠道和竞争机制；行业、对比及投资初步尽调使用适用的研究内容。

报告以重要发现为主线，通过 `Core / Supporting / Appendix` 安排结论、论据和附录，保留来源、反证、矛盾和未知事项。核心论断应能沿 `Source → Evidence → Finding` 回溯。输出规范定义八类严格结构化记录及必要的领域扩展记录；产品研究原则上提供可靠官方图片或标记 `Unavailable`，并提供产品规格矩阵。

研究完成需同时经过：

- **Breadth Completion（覆盖完整性）：** 必要领域及主要相关平台已处理，或明确说明资料不足、访问受限或结构性不适用。
- **Depth Saturation（证据深度饱和）：** 继续可行的检索不太可能实质改变关键发现；否则应披露未解决的证据缺口。

报告可以提出相互竞争的解释、风险、条件性建议和进一步验证问题，但这些是**供人判断的研究输入**，不是自动执行指令或由 Skill 代为批准的决定。

## 七、存在局限

¹ **信息权限有限。** Skill 本身不是爬虫、商业数据订阅或自动监测服务，不自带企业内部资料、商家后台、收费数据库、平台 API 和实物测试能力；登录、验证码、付费墙、隐私设置与合法访问边界仍然有效。材料缺失必须如实标注。

² **长期上下文并非始终可用。** 输入名称足以启动通用深度研究，但用户长期关注的行业、既有研究、目标市场、资源约束与比较基线，会影响哪些问题值得优先调查。宿主环境可能无法访问历史对话或相关文件，已有上下文也可能不完整或过时。可用时据此调整研究重点；不可用时说明假设，不虚构记忆。**长期上下文改善相关性，不能替代事实验证。**

³ **方法论并不自动保证结果正确。** 公开资料可能存在缺口、选择偏差、误报与互相转载，真实研究还需核对来源并进行端到端验证。行业与多主体比较目前共享研究流程，不应声称已具备所有专门的逐阶段协议。

⁴ **研究与决策存在边界。** Skill 将个人审美和决策机制与研究方法解耦，不预设某一种审美、商业目标或风险偏好一定正确。具体选择还取决于用户的真实需求、机会成本、资源及责任；任何深度报告都不能自动替代这些判断。

## 八、项目意义

MarketScope 将长期积累的市场调研与竞品分析经验转化为可复用的研究工作流，让**“输入一个名称，获得一份有证据支撑的深度研究报告”**成为低门槛的交互方式。它的价值在于减少前期准备、检索、收集、核对和整理资料的时间，提高研究材料的覆盖度、可比较性与可追溯性，帮助用户把更多精力投入理解市场和形成自己的判断。**它优化的是研究过程，而不是替人决定下一步，更不以输出可直接执行的报告为目标。**

## 九、安装维护

```text
marketscope/
├── SKILL.md
├── README.md
└── references/
    ├── classification-routing.md
    ├── research-sop.md
    └── output-contract.md
```

将 `marketscope/` 目录载入支持文件式 Skill 的 AI Agent，并保留相对路径。`SKILL.md` 负责全局规则；三份 References 分别负责**分类与来源选择**、**研究 SOP**、**报告与数据契约**。README 用于介绍项目与使用方式，不能替代正式执行规则。

**输入示例：**

```text
SONOS
泡泡玛特
Nothing Phone
索尼
AI 录音设备

研究一家日本消费品牌在当地社媒与电商平台上的公开信息。
对比三款 AI 录音设备的规格、实际体验、售价和用户反馈。
检索某品牌在 Amazon、天猫和独立站的销售线索，并区分证据等级。
研究一家企业级 AI SaaS 公司，包括其招聘、专业社区和技术生态。
对指定企业开展公开资料范围内的初步投资尽调。
```

可按需要补充目标地区、研究截止日期、已知竞品、个人或企业目标以及既有资料，这些信息不是启动 Skill 的前置要求。实际网络搜索、账号、连接器、文件和付费资源的可用性取决于运行环境与授权。

[SKILL.md](./SKILL.md) 为全局规范；[Classification & Routing](./references/classification-routing.md)、[Research SOP](./references/research-sop.md) 与 [Output Contract](./references/output-contract.md) 定义具体执行细节。`MarketScope.json` 如存在，仅作为 Markdown 源文件的可携带快照，并非运行依赖。修改源文件后需同步其内容、行数和 SHA-256；若快照与文件冲突，以当前 Markdown 的有效规则为准。

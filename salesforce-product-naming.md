# Salesforce product naming reference

The naming source of truth for the Salesforce Capability Atlas detail cards. When Salesforce renames or acquires something, update this list first, then the cards.

**Last checked:** 22 Nov 2026

## Timeline

- **Oct 2025 (Dreamforce '25):** About two dozen products took an "Agentforce" prefix (Sales Cloud → Agentforce Sales, Service Cloud → Agentforce Service, Salesforce Platform → Agentforce 360 Platform). Data Cloud became Data 360 on 14 Oct 2025.
- **Sept 2026 (week before Dreamforce '26):** Most of the prefix was reversed. The cloud names came back. Data 360 kept its name. "Agentforce" now means the AI agents inside each cloud.
- **Dreamforce '26:** Agents got job names. Salesforce moved away from the "360" branding. AIforce was announced and has reportedly since been renamed SIforce.

## Cloud and platform names (current)

| Use on cards | Former or interim names | Status |
|---|---|---|
| Sales Cloud | Agentforce Sales (Oct 2025 – Sept 2026) | Restored |
| Service Cloud | Agentforce Service | Restored |
| Marketing Cloud | Agentforce Marketing | Restored |
| Commerce Cloud | Agentforce Commerce | Restored |
| Salesforce Platform | Agentforce 360 Platform, Headless 360 | Restored |
| Data 360 | Data Cloud, Salesforce CDP, Genie | Kept the Oct 2025 name |
| Industry clouds (Financial Services Cloud, Health Cloud, and others) | Agentforce Financial Services, Agentforce Health, and others | Restored per secondary sources; the Agentforce + industry form now means that industry's agents |
| Revenue Cloud | Revenue Lifecycle Management, Revenue Cloud Advanced, Agentforce Revenue Management | **Kept as Revenue Cloud (David's call).** Some salesforce.com pages still say Agentforce Revenue Management. |

## Product and feature renames applied to the cards

| Old name on cards | Current name | Cards changed |
|---|---|---|
| Service Cloud Voice | Salesforce Voice | Omni-Channel Contact Center; AI-Powered Voice |
| AppExchange | AgentExchange (AppExchange, Slack Marketplace and the agent ecosystem merged in 2026) | AgentExchange & Extensibility |
| Sales Cloud Forecasting | Pipeline Forecasting | Sales Performance Management |
| Salesforce Backup, Own Recover | Backup and Recover | Backup & Disaster Recovery |
| Marketing Cloud Intelligence | Marketing Intelligence (from one secondary source) | Marketing Strategy & Planning; Marketing Analytics; Paid Marketing |
| Agentforce SDR (inbound) | Piper (originally Qualified's AI SDR) | Lead Management |
| Agentforce SDR (outbound) | Hunter (pilot; GA planned Nov 2026) | Inside Sales Management |
| Agentforce Service Agent / Help Agent | Casey | Self Service |
| "Agentforce Sales" as an agent label | Agentforce in Sales Cloud | Cross/Up-Sell Management; Guided Solution Selling |

## Legacy products

| Product | Status | On the cards |
|---|---|---|
| Salesforce CPQ (legacy, Steelbrick-based) | End of sale; Revenue Cloud (RCA) is the standard for quote-to-cash | Removed from Quote Management and Guided Solution Configuration. Quote Management's description and discovery question now flag a possible CPQ-to-RCA migration. |
| Industries CPQ (Communications Cloud) | Part of Communications Cloud; not the legacy Salesforce CPQ | Kept on the Communications domain |

## Kept as is

- **Einstein-branded features** (Einstein Lead Scoring, Next Best Action, Case Classification, Prediction Builder, Conversation Insights, Activity Capture, Trust Layer and others): kept as written (David's call).
- **Revenue Cloud** feature names: kept (see above).

## Dreamforce '26 agent names

| Agent | Job |
|---|---|
| Piper | Inbound pipeline and lead qualification (from the Qualified acquisition) |
| Hunter | Outbound sales (pilot, GA planned Nov 2026) |
| Casey | Customer service (formerly Help Agent) |
| Paige | IT and HR service |
| Carter | Shopper agent for commerce and checkout |
| Marshall | Supply chain and back-office orchestration |
| Fin | Customer agent from the Fin acquisition (completed 10 Sept 2026) |

## Acquisitions, 2025–2026

Each acquisition is shown on the capability cards it strengthens, under "From recent acquisitions". The atlas's **Acquired tech** filter shows only those capabilities (32 of 228). Pending deals appear with a dashed outline.

| Company | What it adds | Status | Where it lands | Capabilities on the map |
|---|---|---|---|---|
| Informatica (~$8B) | Data integration, quality, governance, catalog, MDM, privacy | Closed 18 Nov 2025 | Data 360, MuleSoft, Tableau | Customer Data Unification; Application Integration; Data Quality & Cleansing; MDM; Data Governance & Catalog; ETL / Data Pipelines; Data Classification & Privacy |
| Convergence.ai | Agents that work through web interfaces | Closed Jun 2025 | Agentforce | Autonomous AI Agents |
| Bluebirds | AI prospecting | Closed Aug 2025 | Sales Cloud, Agentforce | Lead Generation; Inside Sales Management |
| Waii | Natural language to SQL | Announced Aug 2025 | Tableau Next | Self-Service Data Visualization |
| Regrello | Agentic process automation | Closed Oct 2025 | Agentforce, Slack | Workflow Orchestration; Supply Chain Visibility (MFG) |
| Apromore | Process mining and intelligence | Closed Nov 2025 | Data 360 | Process Mining & Intelligence |
| Spindle AI | Agentic analytics, scenario simulation, agent observability | Closed Nov 2025 | Tableau Next | AI-Powered Insights; AI Governance & Agent Observability |
| Doti | Agentic enterprise search | Closed Dec 2025 | Slack planned as interface | Enterprise Search (new capability) |
| Momentum | Call and meeting capture across Zoom, Google Meet and others | Closed Mar 2026 | Einstein Conversation Insights | Conversational Intelligence |
| Cimulate | AI product discovery | Closed Mar 2026 | Commerce Cloud | Search / Merchandizing; Recommendations & Experience |
| Qualified (~$1.2B) | Agentic marketing; Piper AI SDR | Closed Apr 2026 | Agentforce, Sales Cloud | Lead Generation; Lead Management |
| m3ter | Usage metering and rating | Closed Jul 2026 | Revenue Cloud | Usage-Based / Consumption Pricing |
| Contentful (~$1.5B) | Composable, headless content platform | Closed Sep 2026 | Headless / Marketing | Content Management; Microsites & Landing Pages; Digital Experience Personalization |
| Fin, formerly Intercom (~$3.6B) | AI customer service agent | Closed 10 Sep 2026 | Salesforce AI Labs | Self Service; Autonomous AI Agents |
| Listen Labs | AI-led customer research and simulation | Closed Nov 2026 | Not yet placed | Feedback / Surveys / VOC |
| Loops | AI metric monitoring | Closed Nov 2026 | Planned for Tableau | AI-Powered Insights |
| Braze (~$5.66B) | Customer engagement platform | **Pending** (announced 20 Oct 2026) | Marketing Cloud | Journey Management; Direct Marketing (owned) |
| Cresta | Voice agents, live agent coaching | **Pending** (announced Nov 2026) | Service Cloud | Omni-Channel Contact Center; AI-Powered Voice; Workforce Engagement Management; Conversational Intelligence |
| Rune Technologies | Defense logistics | **Pending** (announced 29 Oct 2026) | Missionforce | Not mapped (no defense domain on the atlas yet) |

Product chips added to cards: Informatica (Data Quality, MDM, Data Catalog and Governance, Data Integration), Contentful (Content Management), Fin (Self Service, Autonomous AI Agents).

## Capability list changes (Nov 2026)

The February 2026 map listed 224 capabilities. Its header said 225, but Marketing listed 9, not 10. The atlas now has **228**:

- **Merged:** "AppExchange & Extensibility" and "AI Marketplace (AgentExchange)" became **AgentExchange & Extensibility** (Platform & Automation).
- **Added (marked "Added Nov 2026"):**
  - Employee Service (IT & HR): Service
  - AI Governance & Agent Observability: AI & Agents
  - AI Access from External Tools (SIforce, Claudeforce, Slackforce, Agentforce Coworker): AI & Agents
  - Process Mining & Intelligence (Apromore): Analytics & BI
  - Enterprise Search (Doti): Collaboration

## Open question

- **Missionforce** (defense, intelligence, aerospace and government business unit, announced Dreamforce '26) could become its own industry domain once the Rune deal closes.

## Retirements to keep in mind

- Quip: new accounts stopped 17 Feb 2026; free access ends 31 Mar 2027 (Slack canvases replace it).
- Salesforce to Salesforce: scheduled to retire in Spring '27.

## Sources

- [Salesforce rebrand reversal (ValueAdd VC, Sept 2026)](https://valueaddvc.com/blog/salesforce-rebrand-reversal-why-agentforce-branding-got-walked-back)
- [Salesforce drops "Agentforce" from product names (TNW)](https://thenextweb.com/news/salesforce-drops-agentforce-branding-product-names-dreamforce)
- [Salesforce products list for 2026 (Martech Zone, 3 Nov 2026)](https://martech.zone/pardot-digital-personalization/)
- [Salesforce product landscape 2026 (Martech Zone)](https://martech.zone/salesforce-product-landscape/)
- [Salesforce acquisitions, dated list through Nov 2026 (Techila)](https://techilaservices.com/insights/salesforce-acquisitions)
- [Salesforce Completes Acquisition of Informatica (Salesforce, 18 Nov 2025)](https://investor.salesforce.com/news/news-details/2025/Salesforce-Completes-Acquisition-of-Informatica/)
- [Salesforce 10-Q, quarter ended 31 Jul 2026 (Contentful, Fin)](https://www.sec.gov/Archives/edgar/data/0001108524/000110852426000190/crm-20260731.htm)
- [Salesforce 8-K: agreement to acquire Braze (20 Oct 2026)](https://www.sec.gov/Archives/edgar/data/0001108524/000119312526425881/d516983dex991.htm)
- [Salesforce launches AI SDR Piper with Qualified (salesforce.com)](https://www.salesforce.com/salesforce-on-salesforce/agentic-presales-qualified-piper/)
- [Biggest Dreamforce '26 announcements (Salesforce Ben)](https://www.salesforceben.com/biggest-dreamforce-26-announcements-everything-in-a-nutshell/)
- [Data Cloud renamed Data 360 (Salesforce Ben)](https://www.salesforceben.com/salesforce-data-cloud-renamed-to-data-360-as-part-of-agentforce-360/)
- [Salesforce Voice implementation guide release notes (Salesforce Developers)](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_release_notes.htm)
- [Agentforce Revenue Management (formerly Revenue Cloud), salesforce.com](https://www.salesforce.com/au/products/sales-cloud/tools/revenue-cloud/)

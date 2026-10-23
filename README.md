# Energy and Utilities Agentic Transformation Accelerator

**Utilities do not have an AI pilot problem. They have a critical infrastructure trust problem. This accelerator is the bridge.**

Energy is the edition where the governance first thesis carries public safety weight. This build runs the Identify to Prove method on Google Cloud with the operational technology boundary drawn first: agents forecast, assemble, and draft, and hold no path to grid control. The governance mapping works in the industry's own language, NERC CIP awareness, CEII handling, human operational authority, and evidence a commission can inspect.

The site contains four transformation patterns mapped service by service to the Google Cloud stack, an interactive 15 question readiness assessment that returns a staged transformation roadmap, and a governance pack that maps agentlint style checks to the controls this industry already answers for.

> This project is not affiliated with, sponsored by, or endorsed by Google. Product names are used nominatively only, to describe platform mappings.

## Run it

No build step, no dependencies, no server. One file:

1. Open `index.html` in any modern browser, or serve the folder with any static host.
2. Read the four patterns and the governance mapping.
3. Take the 15 question assessment and get your roadmap on screen, then copy it as text.

Live site: https://energy-agent-accelerator.vercel.app
Series hub: https://agent-accelerator-atlas.vercel.app

## The four transformation patterns

| Pattern | Business outcome | Core services |
| --- | --- | --- |
| Grid Outage Prediction Agent | Crews and material staged closer to the damage before it happens, estimated restoration times grounded in evidence, and post storm reviews that start from data instead of memory. | Vertex AI, Gemini, Google Earth Engine, BigQuery, Looker |
| Field Crew Copilot | Windshield time and paperwork time fall, closeouts complete the same day, and every crew works from the same current procedures. | Vertex AI Agent Builder, Gemini, Vertex AI Search, BigQuery |
| Energy Forecasting Pipeline | Forecast cycles shrink from days to hours, every number carries its inputs and version, and planning arguments move from whose spreadsheet to what the evidence says. | Vertex AI, BigQuery ML, Google Earth Engine, Dataflow, Looker |
| Regulatory Reporting Assistant | Filing cycles shorten, consistency errors surface before submission instead of during discovery, and the evidence trail is a byproduct, not a project. | Vertex AI Agent Builder, Gemini, BigQuery, Vertex AI Search, Cloud DLP |

## The assessment: Identify to Prove, adapted to energy and utilities

The assessment operationalizes the arc Greg Lucas uses at AIccountable (Identify, Train, Design, Implement, Prove), translated into this industry's language. Each stage is scored 0 to 100 from three questions on a five point scale.

| Stage | What it measures |
| --- | --- |
| **Identify** | Use case census, value cases, critical infrastructure risk tiering. A written use case census with named owners and value cases, risk tiering that separates high risk uses from low risk productivity uses, and oversight review before any pilot is chosen. |
| **Train** | Operator, crew, and analyst readiness. Role based readiness: the people who work with agents know what agents do, what they must never do, and when a human decides, and leaders can explain the strategy and its governance in plain language. |
| **Design** | OT boundary architecture, agent charters, governed data. Governed data foundations with lineage and access control, a written charter for every agent before build (owner, allowed actions, approval gates, data allow list, kill switch), and scoped agent identities. |
| **Implement** | Pilots behind human operational authority. Pilots on a managed platform with evaluation gates, human approval on consequential actions inside the workflow, and a reusable pattern pack from every pilot. |
| **Prove** | Regulatory grade evidence, reliability outcomes, measured value. Complete interaction logging retained to the records standard, scheduled quality and outcome measurement, and a governance body that reviews agent performance and can suspend an agent on evidence. |

Your overall score places you in one of four stages: Stage 1 Census (0 to 24), Stage 2 Charter (25 to 49), Stage 3 Scale (50 to 74), Stage 4 Transform (75 to 100). The roadmap you receive is staged to match: a 90 day plan for early stages, a quarterly scale plan for Stage 3, and a pattern factory operating model for Stage 4.

## Governance first

The governance section of the site maps eight agentlint style checks to this industry's controls and the tooling that produces the evidence:

- Named human owner on every agent: named accountable ownership in the utility AI inventory, with CIP responsible entity clarity where BES scope applies. Tooling: Agent registry practices on Vertex AI, ownership attested in project structure and Cloud Audit Logs.
- No wildcard tool access: least privilege and electronic access discipline consistent with NERC CIP expectations: agents hold no interactive access to control environments. Tooling: Cloud IAM with Workload Identity, per agent service accounts, segmented network architecture with VPC Service Controls.
- Approval gates on consequential actions: human operational authority: switching, dispatch, and customer commitments remain with authorized personnel, by design rather than by instruction. Tooling: Vertex AI Agent Builder human in the loop steps, approval workflows in work and outage management systems.
- No secrets or credentials in prompts: credential and sensitive data protection, including customer usage data and critical energy infrastructure information handling. Tooling: Secret Manager, Cloud DLP inspection and redaction, CEII aware data classification.
- Full interaction logging: audit logging sufficient for compliance review: recommendations, approvals, and outcomes retained to the records standard. Tooling: Cloud Audit Logs, BigQuery log analytics, Looker compliance reporting.
- Data source allow list: data allow lists: agents read approved operational and market data products only, never control system feeds outside the governed interface. Tooling: BigQuery authorized views and datasets, governed API interfaces into OT data historians.
- Kill switch and rollback: incident response aligned to CIP incident reporting discipline, with fast suspension of a misbehaving agent. Tooling: Vertex AI deployment controls, Security Command Center alerts, tested rollback and manual fallback runbooks.
- Evaluation before and after launch: evaluation before and after launch, including storm scenario stress tests and drift monitoring against live conditions. Tooling: Vertex AI evaluation and monitoring, BigQuery drift analytics, scheduled reliability reviews.

The point of the mapping: governance evidence should be a byproduct of the platform as the agent runs, not a document assembled afterward for the audit.

## Companion projects

- [Industry Agent Accelerator Atlas](https://agent-accelerator-atlas.vercel.app): the hub for all eleven industry editions of this accelerator series.
- [FSI Agentic Transformation Accelerator](https://fsi-agent-accelerator.vercel.app): the financial services edition on the Microsoft stack, the first build in this series.
- [agentlint](https://github.com/THFC-COYS/agentlint): the governance linter for AI agents, the source of the checks mapped on this site.
- [Business Agent Readiness](https://business-agent-readiness.vercel.app): the AGENT Framework assessment for businesses adopting agents.
- [CourseAgent Studio](https://courseagent-studio.vercel.app): turns a syllabus into a governed course agent.
- [Muse Exchange](https://muse-exchange.vercel.app) and [MuSe SIM](https://muse-sim.vercel.app): agent marketplace and agent society, built on Meta Muse.

## Author

**Greg Lucas** is the Founder of pAIgeBreaker (personalized AI textbooks, with Aithentik authorship verification) and AIccountable (safe, governed AI adoption for companies, run on the Identify, Train, Design, Implement, Prove sequence). He created the AGENT Framework and the 4-Stage AI Maturity Model, built agentlint, Muse Exchange, and MuSe SIM, and serves as Faculty Chair at Grand Canyon University and Team Lead at Southern New Hampshire University. He writes and speaks on safe agentic AI in business and education.

- LinkedIn: https://www.linkedin.com/in/greg-lucas-28765b416/
- pAIgeBreaker: https://paigebreaker.com

## License

MIT. Copyright (c) 2026 Greg Lucas. See [LICENSE](LICENSE).

Google Cloud, Vertex AI, Gemini, BigQuery, Looker, and Google Earth Engine are trademarks of Google LLC. All other names are used for identification only.

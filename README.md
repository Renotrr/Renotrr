# John Adewole
### AI Automation Engineer & Product Builder

Lagos, Nigeria · Open to remote opportunities

I build practical automation systems that connect business workflows, APIs, webhooks, databases and AI-assisted processes. My product-design background helps me turn those workflows into tools that are understandable and useful to the people operating them.

I’m especially interested in systems that make repetitive work easier to manage while keeping evidence, exception handling and human decisions clear.

[Portfolio](https://jaytee-automation-engineer.vercel.app/) · [Email](mailto:johnadewole23@gmail.com) · [LinkedIn](https://ng.linkedin.com/in/johnadewole23)

---

## Selected automation projects

### [QuikDrop](https://github.com/Renotrr/quikdrop-automation)
**WhatsApp food and package delivery automation · Working MVP**

A WhatsApp-based ordering and delivery workflow connected to Meta WhatsApp Cloud API, webhooks, Supabase/PostgreSQL and Edge Functions, with an operations dashboard, payment checkpoints, rider coordination and human handling for exceptions.

**Reported result:** Daily successful orders moved from roughly **95–120 to about 195 out of approximately 200 orders per day**.

The shipped workflow is rule-based. An LLM-assisted layer is planned, not yet implemented.

[Case study](https://jaytee-automation-engineer.vercel.app/work/quickdrop) · [Architecture and screenshots](https://github.com/Renotrr/quikdrop-automation)

### [EVRAYN](https://github.com/Renotrr/evrayn-procurement-intelligence)
**Procurement operations intelligence · Active build**

A system for post-award procurement execution control: supplier commitments, milestones, expected-versus-observed status, evidence gaps, delivery risks and human-reviewed exceptions.

The Ask EVRAYN LLM work has documented validation for source-grounded ETA lookup, continuation of a pending human decision with a supplier follow-up proposal, and a human-approved delivery-verification flow. The final decision-closure regression remains to be verified in dedicated staging.

**Architecture boundary:** AI interprets, retrieves, summarizes and proposes. Deterministic code controls authoritative state, permissions and routing; humans retain consequential decisions.

[Case study](https://jaytee-automation-engineer.vercel.app/work/evrayn) · [LLM scenarios and architecture](https://github.com/Renotrr/evrayn-procurement-intelligence)

### [Jobify](https://github.com/Renotrr/jobify-opportunity-workflow)
**Opportunity discovery and application support · Active local build**

A personal system for organizing job, freelance, agency and potential-client opportunities; extracting requirements; checking eligibility and fit; matching approved profile and portfolio evidence; and preparing tailored application or outreach packages.

The latest saved local checkpoint reports **51/51 offline tests passing** and a successful Apps Script bundle build. Jobify is not yet deployed to Google Workspace, and live external-source integrations still require verification.

[Workflow, test notes and architecture](https://github.com/Renotrr/jobify-opportunity-workflow)

---

## Invoice and accounts-payable automation

**Invoice Reader · Client project**  
Built an invoice reader for an Australian business to capture invoice information in a structured format for downstream processing.

**AP Workbench · Prototype**  
Prototyped invoice intake and review, supplier and ABN checks, duplicate detection, supplier-statement reconciliation, exception handling and payment-run preparation. The MYOB-formatted CSV handoff uses simulated data; this is not a completed production ERP integration.

---

## What I work with

**Languages and application development**  
JavaScript · TypeScript · Python (foundational) · React · Node.js · HTML · CSS

**Workflow automation and integrations**  
n8n · Make.com · Google Apps Script · REST APIs · Webhooks · JSON · Meta WhatsApp Cloud API

**Data and backend**  
Supabase · PostgreSQL · SQL · Supabase Edge Functions

**AI and LLM workflows**  
Gemini · LLM-assisted retrieval and structured responses · Prompt design · ChatGPT · Claude

**Product and delivery tools**  
Git · GitHub · Vercel · Netlify · Figma · Framer

---

## How I approach automation

1. Understand the real workflow before choosing what to automate.
2. Map the data, states, handoffs and failure points.
3. Use deterministic logic for business rules and AI where unstructured information or language makes it useful.
4. Add validation, duplicate protection, useful logs and retry handling.
5. Keep people involved wherever a decision needs context, approval or accountability.

My goal is to build reliable systems that reduce repetitive operational work without hiding uncertainty or removing the human judgment that matters.

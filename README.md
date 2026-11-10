# Hi, I'm Babak

I'm an AI Solutions Architect and Senior Software Engineer with 20+ years of
end-to-end software delivery. I design and build AI features for business
software: assistants, copilots and question answering over company documents.
Most of my work is in .NET and Azure. I also work in TypeScript, React, Python
and AWS.

## How I build AI features

- **Code owns the facts.** Prices, availability, schedules and financial
  figures are computed by code. The model explains; it does not decide.
- **Model text is checked before anyone acts on it.** A deterministic validator
  reads the draft. A refused draft gets one rewrite, then a fixed fallback.
- **Answers are grounded.** Retrieval supplies the passages, the answer cites
  them, and retrieved text is treated as untrusted data.
- **Actions are governed.** Tools are typed and limited, changes are audited,
  and a person approves anything that changes business data.
- **Status is stated honestly.** I describe a feature at the level it was
  actually validated: live, demo, or tested locally.

## Public repositories

| Repository | What it shows |
|---|---|
| [grounded-hotel-concierge](https://github.com/Babak73314/grounded-hotel-concierge) | Working .NET code with 422 tests: a hotel concierge where code computes every price and model text passes a deterministic gate. A slice of my own platform. |
| [ai-platform-architecture](https://github.com/Babak73314/ai-platform-architecture) | No code. The architecture of my own enterprise AI platform: layers, dependency rules, AI orchestration, security and delivery status. |

Most of my other work is private. Client code belongs to the client, and my own
platform is a commercial product.

## Selected work

**My own enterprise AI platform (2025–present).** A modular .NET 10 platform
that I designed, built and tested independently. One shared AI core serves a
live bilingual sales website with text and voice, a public hotel concierge demo,
and locally validated healthcare, real-estate, commerce and finance
applications. Details are in the architecture repository above.

**AI code-review platform, for an Australian software company.** I architected
and developed an advisory review platform on Azure that combined deterministic
structural analysis with Azure OpenAI review of GitHub pull requests. The work
included an event-driven .NET backend, a React and TypeScript dashboard, and
organisation-level access controls. Findings were advisory and never blocked a
merge.

**Logistics copilot on Microsoft Fabric, for a United States enterprise
client.** I moved logistics ETL to Fabric Dataflow Gen2 and a Lakehouse on Delta
tables, built PySpark transformations and Power BI models for shipment KPIs, and
designed two answer paths: structured data for KPI questions, document search
for contract questions.

**AI deliverables copilot, for an Australian enterprise client.** I led the .NET
backend for AI-generated communication plans, stakeholder matrices and training
plans, with document ingestion on Azure Functions, filtered retrieval on Azure
AI Search, and validation so that a malformed model answer never reached a
document.

**Guided assessments and forms assistant, for a public-sector health
organisation in Ireland.** I developed a Blazor and .NET platform for guided
assessments, form completion and summaries using Azure OpenAI, Azure AI Search
and Azure SQL, with PDF-based form generation and audit history.

**Bilingual web platform with a grounded Q&A assistant on AWS.** I built a
React, Next.js and TypeScript site whose assistant answers only from published
content: hybrid retrieval in Aurora PostgreSQL with pgvector, Claude on Amazon
Bedrock, a code-level check on every answer, and infrastructure defined in AWS
CDK.

**Earlier work.** A sales and test-drive system for an automotive brand in
Türkiye (Azure, .NET, Blazor) that went into production use, insurance CRM and
policy automation, and ERP delivery covering finance, payroll, warehouse and
sales.

## Technologies

- **Languages and frameworks:** C#, .NET 8/9/10, ASP.NET Core, Blazor, EF Core,
  TypeScript, React, Next.js, Python, FastAPI
- **AI and retrieval:** Azure OpenAI, Microsoft Foundry, Anthropic Claude,
  Google Gemini, Microsoft Agent Framework, RAG with hybrid search, structured
  output, tool calling, live voice over WebRTC
- **Azure:** Functions, App Service, Service Bus, Azure SQL, AI Search, Document
  Intelligence, Key Vault, Application Insights
- **AWS:** CDK, Lambda, Aurora PostgreSQL, Amazon Bedrock, S3, CloudFront
- **Data:** SQL Server, PostgreSQL with pgvector, Microsoft Fabric, PySpark,
  Power BI
- **Practice:** architecture and solution design, infrastructure as code, CI/CD
  with GitHub Actions and Azure DevOps, automated testing

## How I work

I code hands-on and use AI coding tools for implementation support, automated
tests and independent review. I set the scope and the acceptance criteria,
review every change, and remain responsible for the architecture, the code
quality and every decision.

I work remotely and am available for full-time, contract or project work.

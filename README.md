# Claude Enterprise FDE Academy

A practical, hands-on learning portal for Forward Deployed Engineers
(FDEs) building, integrating, deploying, securing, and optimizing
Claude-powered enterprise AI solutions.

**Explore the portal:** [Claude Enterprise FDE
Academy](https://srinipusuluri.github.io/claude_enterprise_fde_academy/)

> The academy is an independent learning resource. It is not an official
> Anthropic product or certification program. Product names, features,
> availability, pricing, and deployment options change; always verify
> details in current vendor documentation.

## What is a Forward Deployed Engineer?

A Forward Deployed Engineer works directly with customers and business
teams to turn ambiguous operational problems into working,
production-grade software. An AI FDE combines software engineering, AI
application architecture, data integration, customer discovery,
security, deployment, and production operations.

This academy focuses on applying Claude across enterprise
workflows---from the first discovery conversation through production
rollout and continuous optimization.

## What you'll learn

-   Translate business problems into measurable AI use cases and
    implementation plans.
-   Select the right Claude product and deployment approach for an
    enterprise scenario.
-   Build applications with the Claude API and developer tooling.
-   Connect enterprise data and applications through APIs,
    retrieval-augmented generation (RAG), and Model Context Protocol
    (MCP).
-   Design agent workflows with clear tool boundaries, approvals, and
    failure handling.
-   Deploy on AWS, Google Cloud, or Azure using modern application and
    platform engineering practices.
-   Implement Git-based development, automated testing, CI/CD, and
    infrastructure as code.
-   Secure enterprise AI workflows with identity, least privilege, data
    protection, and audit controls.
-   Instrument systems with traces, metrics, logs, evaluations, and cost
    telemetry.
-   Optimize Claude economics, latency, quality, reliability, and cost
    per successful business outcome.
-   Explain architecture and trade-offs to customers, executives,
    developers, security teams, and operations teams.

## Academy sections

  -----------------------------------------------------------------------
  Section                             What it covers
  ----------------------------------- -----------------------------------
  FDE role                            Responsibilities, customer
                                      engagement, and the FDE delivery
                                      mindset

  Implementation lifecycle            Discovery, design, prototype,
                                      integration, deployment, adoption,
                                      and operations

  Enterprise architecture             Reference architecture for
                                      Claude-powered applications

  Tech Stack Tools                    Claude products, Git, cloud, APIs,
                                      data, RAG, MCP, CI/CD, security,
                                      observability, and operations

  Optimization                        Claude cost economics, prompt
                                      caching, model routing,
                                      performance, security, tracing,
                                      reliability, and scorecards

  Enterprise agent use cases          Sample agents across engineering,
                                      product, service, HR, security,
                                      sales, finance, risk, and marketing

  Technical skills                    Engineering, integration, data,
                                      cloud, and AI capabilities expected
                                      of an FDE

  Hands-on labs                       Practical implementation exercises
                                      and build activities

  Governance                          Security, privacy, access control,
                                      responsible use, and production
                                      readiness

  Learning roadmap                    A structured learning path and
                                      progress tracking

  Job portal                          Sample FDE job description, role
                                      expectations, and job-search
                                      resources

  Learning resources                  Official documentation, courses,
                                      tutorials, repositories, and
                                      references

  Quiz                                Knowledge checks to reinforce key
                                      concepts
  -----------------------------------------------------------------------

## Enterprise agent use cases

The academy includes short implementation outlines for example
enterprise agents, including:

-   **SDLC Engineering Agent:** Understands tickets and repositories,
    proposes implementation plans, drafts code and tests, and supports
    pull-request review.
-   **Product Knowledge Base Search Agent:** Searches approved product
    documentation and returns grounded answers with citations and source
    links.
-   **Customer Support Agent:** Classifies cases, retrieves
    troubleshooting guidance, drafts responses, and recommends next
    actions.
-   **Employee HR Assistant:** Answers employee questions using approved
    HR policies and routes sensitive requests to HR.
-   **New Employee Onboarding Agent:** Coordinates onboarding
    checklists, learning, equipment, and access requests through
    approved workflows.
-   **Security Operations Agent:** Enriches alerts, summarizes
    incidents, and recommends investigation steps with human approval
    for consequential actions.
-   **Observability / SRE Agent:** Correlates logs, metrics, traces, and
    deployments to help investigate incidents.
-   **Deal / Sales Assistant:** Prepares account briefs, summarizes
    activity, and highlights deal risks.
-   **Renewals Agent:** Analyzes usage, support history, contract terms,
    and renewal dates to help identify churn risk.
-   **Forecasting Agent:** Explains pipeline movement and forecast
    drivers using governed CRM and analytics data.
-   **KYC / KYB Onboarding Agent:** Extracts and checks onboarding
    documents and flags exceptions for human review.
-   **Product Recommendation & Upsell Agent:** Suggests eligible
    products and add-ons based on customer needs, catalog rules, and
    usage.
-   **Product Research Agent:** Synthesizes customer feedback,
    competitor information, and market signals into evidence-backed
    briefs.
-   **Marketing Campaign Agent:** Helps prepare campaign briefs, content
    variants, and performance summaries within brand and consent rules.
-   **Customer Health Agent:** Combines usage, support, and CRM signals
    into explainable customer-health summaries.
-   **Procurement & Vendor Agent:** Compares vendor information and
    contract terms against approved procurement policies.
-   **Contract Review Assistant:** Flags clauses and deviations against
    approved playbooks for legal review.
-   **Finance & Invoice Agent:** Extracts invoice information, checks
    purchase-order matches, and routes exceptions.
-   **Executive Briefing Agent:** Produces source-linked summaries of
    business performance, initiatives, and risks.
-   **IT Helpdesk Agent:** Answers common IT questions and creates
    service tickets with relevant context.

These are reference patterns, not turnkey implementations. Each
deployment needs customer-specific discovery, data access design, tool
authorization, evaluation, security review, and operational ownership.

## Tech stack coverage

The tool catalog is organized by the enterprise AI lifecycle.

### Claude and AI application layer

-   Claude models and Claude Platform / API
-   Claude Enterprise
-   Claude Code
-   Claude Cowork
-   Claude Agent SDK and managed agent capabilities
-   Claude Skills, tool use, and MCP integrations

### Software engineering and source control

-   Python, TypeScript / JavaScript, SQL, and other application
    languages
-   VS Code, terminal, notebooks, and developer environments
-   Git, GitHub, GitLab, Bitbucket, and pull-request workflows
-   Automated unit, integration, contract, and end-to-end testing

### Cloud and platform engineering

-   AWS, Google Cloud, and Microsoft Azure
-   Docker and Kubernetes
-   Terraform and other infrastructure-as-code tools
-   Managed compute, storage, networking, identity, secrets, and
    monitoring

### Data, search, and RAG

-   PostgreSQL, Redis, MongoDB, data warehouses, and object storage
-   Document parsing, OCR, ingestion, and data pipelines
-   Embeddings, vector databases, hybrid search, and reranking
-   LlamaIndex, LangChain, and custom retrieval services

### Agents and enterprise integration

-   Model Context Protocol (MCP)
-   REST APIs, webhooks, event-driven systems, and API gateways
-   LangGraph and other agent orchestration frameworks
-   Salesforce, ServiceNow, Jira, Slack, and other enterprise
    applications

### CI/CD and DevSecOps

-   GitHub Actions, GitLab CI, Jenkins, and Azure DevOps
-   GitOps, deployment automation, and release promotion
-   Infrastructure and container security scanning
-   Versioning for prompts, tools, Skills, evaluation datasets, and
    application code

### Observability and traceability

-   OpenTelemetry traces, metrics, and logs
-   LLM / agent observability platforms
-   Cloud-native monitoring and centralized dashboards
-   Correlation of user requests, model calls, retrieval, MCP tools,
    approvals, and downstream changes

### Security and governance

-   SSO, OAuth 2.0, OIDC, RBAC, ABAC, and least privilege
-   Secrets management, encryption, and key management
-   Prompt-injection defenses and tool authorization
-   Privacy-aware telemetry, audit trails, retention, and compliance
    controls

## Optimization topics

Production optimization should improve the full business workflow---not
just reduce model token usage.

The academy covers:

-   **Cost economics:** input and output tokens, cached tokens, cost per
    task, cost per successful task, tenant budgets, and chargeback.
-   **Cost controls:** prompt caching, model routing, context
    compression, output limits, batching where appropriate, and bounded
    agent loops.
-   **Performance:** streaming, time-to-first-token, latency
    decomposition, connection reuse, concurrency, retries, and
    throughput.
-   **RAG quality:** retrieval recall, precision, reranking, freshness,
    citation accuracy, and permission filtering.
-   **Security:** least privilege, identity propagation,
    untrusted-content handling, data minimization, and approval gates.
-   **Observability:** end-to-end traces, token and cost telemetry, tool
    execution, quality signals, and business traceability.
-   **Reliability:** SLOs, circuit breakers, fallbacks, canary releases,
    rollback, and incident runbooks.

## Suggested learning path

1.  **Understand the FDE role:** Practice customer discovery, workflow
    mapping, and defining measurable outcomes.
2.  **Learn Claude fundamentals:** Explore the Claude Platform
    documentation, model capabilities, tool use, and Claude Code.
3.  **Build an API application:** Create a small Python or TypeScript
    application that calls Claude securely.
4.  **Connect enterprise data:** Implement a RAG workflow with source
    citations, access filtering, refresh, and deletion handling.
5.  **Add tools and MCP:** Connect one read-only enterprise tool, then
    introduce an approved write action with human confirmation.
6.  **Deploy to cloud:** Containerize the application and deploy it to a
    cloud environment with managed identity and secrets.
7.  **Automate delivery:** Add Git branching, tests, CI/CD,
    infrastructure as code, and rollback.
8.  **Secure and evaluate:** Add threat tests, access-control checks,
    evaluation datasets, and human review.
9.  **Instrument and optimize:** Trace the complete workflow and measure
    cost, quality, latency, and task success.
10. **Deliver a customer-ready solution:** Document architecture,
    runbooks, support ownership, risks, and business outcomes.

## Related learning portals

-   **Claude Certifications:**
    <https://srinipusuluri.github.io/Claude_Certifications/>
-   **Claude Learning Portal:**
    <https://srinipusuluri.github.io/claude-learning-portal/>
-   **FDE Interview Preparation --- Udemy:** [Forward Deployed Engineer
    (FDE) Interview Prep --- 100
    Q&A](https://www.udemy.com/course/forward-deployed-engineer-fde-interview-prep-100-qa/?referralCode=9D9A9528B0CD0BF60D29)

## Official documentation and references

Start with primary vendor documentation and verify current capabilities
before implementation.

-   [Anthropic documentation](https://docs.anthropic.com/)
-   [Claude Platform documentation](https://platform.claude.com/docs/)
-   [Claude Code
    documentation](https://code.claude.com/docs/en/overview)
-   [Anthropic
    Cookbook](https://github.com/anthropics/anthropic-cookbook)
-   [Model Context Protocol](https://modelcontextprotocol.io/)
-   [OpenTelemetry](https://opentelemetry.io/docs/)
-   [AWS Documentation](https://docs.aws.amazon.com/)
-   [Google Cloud Documentation](https://cloud.google.com/docs)
-   [Microsoft Azure Documentation](https://learn.microsoft.com/azure/)

## Run locally

The academy is a standalone HTML learning portal. No build step or
package installation is required.

1.  Download or clone this repository.
2.  Open `claude_enterprise_fde_academy.html` in a modern browser.
3.  For local hosting, serve the file using any static web server.
4.  To publish with GitHub Pages, place the HTML file at the repository
    root and configure Pages to deploy from the selected branch and
    folder.

Example local server:

``` bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/claude_enterprise_fde_academy.html`.

## Suggested repository structure

``` text
claude-enterprise-fde-academy/
├── README.md
├── claude_enterprise_fde_academy.html
└── LICENSE
```

You can add labs, diagrams, sample code, and reference architecture
files as the academy grows.

## Important implementation principles

-   Use the minimum number of components needed to solve the business
    problem.
-   Keep user identity and authorization enforced by enterprise
    systems---not by model instructions.
-   Treat retrieved content and tool output as untrusted input.
-   Require human approval for high-impact or irreversible actions.
-   Keep prompts, tools, Skills, datasets, and infrastructure versioned.
-   Evaluate task quality, security, cost, and performance before
    production releases.
-   Log enough to support traceability while minimizing sensitive data
    in telemetry.
-   Establish clear production ownership, SLOs, incident response, and
    rollback procedures.

## Contributing

Suggestions, corrections, additional use cases, labs, architecture
patterns, and learning resources are welcome.

When contributing:

1.  Explain the enterprise problem and intended audience.
2.  Include a concise implementation approach and architecture
    considerations.
3.  Identify security, privacy, and human-approval requirements.
4.  Provide references to authoritative documentation.
5.  Avoid credentials, customer data, proprietary content, or sensitive
    information.

## Disclaimer

This academy is an independent educational resource. It is not
affiliated with, endorsed by, or sponsored by Anthropic. Claude and
related product names are trademarks of their respective owners. Tool
examples are illustrative; inclusion does not imply endorsement or a
recommendation for every enterprise. Always validate current product
capabilities, terms, pricing, security requirements, and deployment
availability with the relevant providers.

------------------------------------------------------------------------

**Learn the stack. Build the agent. Deploy responsibly. Measure business
outcomes.**

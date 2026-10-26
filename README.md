# Amazon Compute Optimizer (amazon-compute-optimizer)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon Compute Optimizer analyzes the configuration and utilization metrics of your AWS resources and provides recommendations to help you identify optimal AWS resource configurations. It uses machine learning to analyze historical utilization metrics and generates rightsizing recommendations for EC2 instances, Auto Scaling groups, EBS volumes, Lambda functions, ECS services on Fargate, and RDS instances.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-compute-optimizer/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Cost Optimization, FinOps, Machine Learning, Resource Recommendations

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Compute Optimizer API
The Amazon Compute Optimizer API provides 21 operations for analyzing resource utilization and generating rightsizing recommendations for EC2 instances, Auto Scaling groups, EBS volumes, Lambda functions, ECS services, and RDS instances.

**Human URL:** [https://aws.amazon.com/compute-optimizer/](https://aws.amazon.com/compute-optimizer/)

#### Tags:

 - AWS, Cost Optimization, FinOps, Machine Learning, Resource Recommendations

#### Properties

- [Documentation](https://docs.aws.amazon.com/compute-optimizer/latest/ug/)
- [OpenAPI](openapi/amazon-compute-optimizer-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/compute-optimizer/latest/APIReference/)
- [Pricing](https://aws.amazon.com/compute-optimizer/pricing/)
- [GettingStarted](https://docs.aws.amazon.com/compute-optimizer/latest/ug/getting-started.html)
- [FAQ](https://aws.amazon.com/compute-optimizer/faqs/)
- [JSONSchema](json-schema/compute-optimizer-instance-recommendation-schema.json)
- [JSONStructure](json-structure/compute-optimizer-instance-recommendation-structure.json)
- [JSON-LD](json-ld/amazon-compute-optimizer-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/compute-optimizer/)
- [Documentation](https://docs.aws.amazon.com/compute-optimizer/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/aws/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/compute-optimizer/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| EC2 Instance Recommendations | Get rightsizing recommendations for over-provisioned or under-provisioned EC2 instances based on utilization metrics. |
| Auto Scaling Group Recommendations | Optimize Auto Scaling group configurations for cost and performance based on historical usage patterns. |
| EBS Volume Recommendations | Identify EBS volumes that can be downsized or converted to a different volume type for cost savings. |
| Lambda Function Recommendations | Optimize Lambda function memory settings based on actual invocation utilization. |
| ECS Service Recommendations | Rightsize ECS services running on AWS Fargate for CPU and memory efficiency. |
| RDS Instance Recommendations | Get rightsizing recommendations for RDS database instances and clusters. |
| Savings Opportunity Estimation | Estimate the potential cost savings from implementing rightsizing recommendations. |
| Organization-Wide Analysis | Analyze recommendations across all accounts in an AWS Organization. |

## Use Cases

| Name | Description |
|------|-------------|
| Cost Reduction | Identify and eliminate over-provisioned AWS resources to reduce monthly cloud spending. |
| Performance Optimization | Detect under-provisioned resources that may be causing performance issues and get upgrade recommendations. |
| FinOps Reporting | Generate cross-account optimization reports to support FinOps practices and showback/chargeback processes. |
| Migration Planning | Use recommendations to rightsize resources before or after migrating workloads to AWS. |
| Continuous Optimization | Integrate recommendations into CI/CD pipelines to continuously monitor and optimize resource provisioning. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Cost Explorer | Correlate Compute Optimizer recommendations with Cost Explorer data for accurate savings projections. |
| AWS Organizations | Enroll and analyze recommendations across all accounts in an AWS Organization. |
| Amazon CloudWatch | Compute Optimizer uses CloudWatch utilization metrics to generate its ML-based recommendations. |
| AWS Trusted Advisor | Complementary service that also provides rightsizing recommendations alongside Compute Optimizer. |
| AWS Systems Manager | Use Systems Manager to implement EC2 instance type changes recommended by Compute Optimizer. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Compute Optimizer OpenAPI](openapi/amazon-compute-optimizer-openapi.yml)

### JSON Schema

273 schema files extracted from the OpenAPI specification covering all request/response models.

### JSON Structure

273 JSON Structure files converted from JSON Schema using the json-structure.org specification.

### JSON-LD

- [Amazon Compute Optimizer Context](json-ld/amazon-compute-optimizer-context.jsonld) — 94 types, 141 properties

### Examples

273 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Compute Optimizer API](capabilities/shared/compute-optimizer.yaml) — 9 operations for resource recommendations and enrollment

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon Compute Optimizer Resource Optimization](capabilities/resource-optimization.yaml) | Amazon Compute Optimizer API | 8 | Cloud Architect, FinOps Engineer |

## Vocabulary

- [Amazon Compute Optimizer Vocabulary](vocabulary/amazon-compute-optimizer-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 3 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Compute Optimizer Spectral Rules](rules/amazon-compute-optimizer-spectral-rules.yml) — 24 rules across 13 categories enforcing Amazon Compute Optimizer API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

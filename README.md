# Amazon Compute Optimizer (amazon-compute-optimizer)
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

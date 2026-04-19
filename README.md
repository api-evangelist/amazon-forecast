# Amazon Forecast (amazon-forecast)

Amazon Forecast is a fully managed service that uses machine learning to deliver highly accurate forecasts. It analyzes your historical time-series data and automatically selects the right machine learning algorithms to generate accurate forecasts with no machine learning expertise required.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Forecasting, Machine Learning, Predictive Analytics, Time Series

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Forecast API
The Amazon Forecast API provides programmatic access to create and manage datasets, predictors, forecasts, and export jobs for time-series forecasting using machine learning models.

**Human URL:** [https://aws.amazon.com/forecast/](https://aws.amazon.com/forecast/)

#### Tags:

 - Forecasting, Machine Learning, Time Series

#### Properties

- [Documentation](https://docs.aws.amazon.com/forecast/latest/dg/what-is-forecast.html)
- [OpenAPI](openapi/amazon-forecast-openapi.yml)
- [JSONSchema](json-schema/amazon-forecast-dataset-schema.json)
- [JSONSchema](json-schema/amazon-forecast-predictor-schema.json)
- [JSONSchema](json-schema/amazon-forecast-forecast-schema.json)
- [JSONSchema](json-schema/amazon-forecast-dataset-group-schema.json)
- [JSONSchema](json-schema/amazon-forecast-tag-schema.json)
- [JSONStructure](json-structure/amazon-forecast-dataset-structure.json)
- [JSONStructure](json-structure/amazon-forecast-predictor-structure.json)
- [JSONStructure](json-structure/amazon-forecast-forecast-structure.json)
- [JSONStructure](json-structure/amazon-forecast-dataset-group-structure.json)
- [JSONStructure](json-structure/amazon-forecast-tag-structure.json)
- [Example](examples/amazon-forecast-dataset-example.json)
- [Example](examples/amazon-forecast-dataset-group-example.json)
- [Example](examples/amazon-forecast-predictor-example.json)
- [Example](examples/amazon-forecast-forecast-example.json)
- [Example](examples/amazon-forecast-tag-example.json)
- [GettingStarted](https://aws.amazon.com/forecast/getting-started/)
- [Pricing](https://aws.amazon.com/forecast/pricing/)
- [FAQ](https://aws.amazon.com/forecast/faqs/)
- [APIReference](https://docs.aws.amazon.com/forecast/latest/dg/API_Operations.html)

## Common Properties

- [Portal](https://aws.amazon.com/forecast/)
- [Website](https://aws.amazon.com/forecast/)
- [Documentation](https://docs.aws.amazon.com/forecast/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/machine-learning/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/forecast/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-forecast)
- [SpectralRules](rules/amazon-forecast-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/forecast.yaml)
- [NaftikoCapability](capabilities/amazon-forecast-time-series-prediction.yaml)
- [Vocabulary](vocabulary/amazon-forecast-vocabulary.yaml)
- [JSON-LD](json-ld/amazon-forecast-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| AutoML | Automatically evaluates and selects from over 60 ML algorithms to find the best fit for your time-series data. |
| Probabilistic Forecasts | Generates quantile forecasts (p10, p50, p90) to estimate demand uncertainty and plan inventory buffers. |
| Domain-Specific Models | Pre-built domain configurations for retail, workforce, traffic, and cloud capacity forecasting. |
| Related Time Series | Incorporate external factors (price, promotions, holidays) as related time-series data to improve accuracy. |
| HPO (Hyperparameter Optimization) | Automatic tuning of model hyperparameters to maximize forecast accuracy. |
| Explainability | Forecast Explainability reports show which features most impact each individual forecast. |
| S3 Export | Export forecast results to Amazon S3 in CSV format for downstream consumption. |

## Use Cases

| Name | Description |
|------|-------------|
| Retail Demand Forecasting | Predict item-level sales for inventory planning and replenishment across stores. |
| Workforce Capacity Planning | Forecast staffing needs for contact centers and seasonal workforce management. |
| Cloud Resource Forecasting | Predict EC2 capacity requirements to optimize reserved instance purchases. |
| Supply Chain Optimization | Forecast component and raw material demand to reduce stockouts and carrying costs. |
| Financial Revenue Forecasting | Project revenue by product, region, and channel for financial planning. |
| Energy Load Forecasting | Predict electricity load and generation requirements for grid balancing. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Import training datasets and export forecast results to S3. |
| AWS Glue | Transform and prepare time-series data for Forecast using AWS Glue ETL jobs. |
| Amazon SageMaker | Combine Amazon Forecast with SageMaker for custom ML pipelines. |
| AWS IAM | Control access to Forecast datasets, predictors, and forecasts with IAM policies. |
| Amazon CloudWatch | Monitor Forecast job status, errors, and API usage metrics. |
| AWS KMS | Encrypt Forecast datasets and training data with customer-managed KMS keys. |
| Amazon QuickSight | Visualize exported forecast data in QuickSight dashboards. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-forecast-openapi.yml](openapi/amazon-forecast-openapi.yml)

### JSON Schema

- [amazon-forecast-dataset-group-schema.json](json-schema/amazon-forecast-dataset-group-schema.json)
- [amazon-forecast-dataset-schema.json](json-schema/amazon-forecast-dataset-schema.json)
- [amazon-forecast-forecast-schema.json](json-schema/amazon-forecast-forecast-schema.json)
- [amazon-forecast-predictor-schema.json](json-schema/amazon-forecast-predictor-schema.json)
- [amazon-forecast-tag-schema.json](json-schema/amazon-forecast-tag-schema.json)

### JSON Structure

- [amazon-forecast-dataset-group-structure.json](json-structure/amazon-forecast-dataset-group-structure.json)
- [amazon-forecast-dataset-structure.json](json-structure/amazon-forecast-dataset-structure.json)
- [amazon-forecast-forecast-structure.json](json-structure/amazon-forecast-forecast-structure.json)
- [amazon-forecast-predictor-structure.json](json-structure/amazon-forecast-predictor-structure.json)
- [amazon-forecast-tag-structure.json](json-structure/amazon-forecast-tag-structure.json)

### JSON-LD

- [amazon-forecast-context.jsonld](json-ld/amazon-forecast-context.jsonld)

### Examples

- [amazon-forecast-dataset-example.json](examples/amazon-forecast-dataset-example.json)
- [amazon-forecast-dataset-group-example.json](examples/amazon-forecast-dataset-group-example.json)
- [amazon-forecast-forecast-example.json](examples/amazon-forecast-forecast-example.json)
- [amazon-forecast-predictor-example.json](examples/amazon-forecast-predictor-example.json)
- [amazon-forecast-tag-example.json](examples/amazon-forecast-tag-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [forecast.yaml](capabilities/shared/forecast.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [amazon-forecast-time-series-prediction.yaml](capabilities/amazon-forecast-time-series-prediction.yaml) | Amazon Forecast API | — | Platform Engineers, DevOps |

## Vocabulary

- [Amazon Forecast Vocabulary](vocabulary/amazon-forecast-vocabulary.yaml)

## Rules

- [amazon-forecast-spectral-rules.yml](rules/amazon-forecast-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

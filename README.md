# TIBCO

APIs and services provided by TIBCO Software Inc., a global leader in integration, API management, and analytics software.

**Website:** [https://www.tibco.com](https://www.tibco.com)  
**Developer Portal:** [https://developer.tibco.com](https://developer.tibco.com)  
**Documentation:** [https://docs.tibco.com](https://docs.tibco.com)

## APIs

| API | Description | Docs |
|-----|-------------|------|
| TIBCO Cloud Integration API | App integration, Flogo/Business Studio app management | [Docs](https://integration.cloud.tibco.com/docs/) |
| TIBCO Mashery API Management | API gateway, portal, and developer ecosystem management | [Docs](https://developer.mashery.com/docs) |
| TIBCO BusinessEvents API | Complex event processing and decision management | [Docs](https://docs.tibco.com/products/tibco-businessevents) |
| TIBCO Messaging API | Enterprise messaging (EMS/FTL) for JMS and pub-sub | [Docs](https://docs.tibco.com/products/tibco-enterprise-message-service) |
| TIBCO Spotfire Analytics API | Analytics, visualization, and BI workflow automation | [Docs](https://docs.tibco.com/products/tibco-spotfire/latest) |

## OpenAPI Specifications

| Spec | Path |
|------|------|
| TIBCO Cloud Integration API | [openapi/tibco-cloud-integration-openapi.yml](openapi/tibco-cloud-integration-openapi.yml) |
| TIBCO Mashery API Management | [openapi/tibco-mashery-openapi.yml](openapi/tibco-mashery-openapi.yml) |
| TIBCO BusinessEvents API | [openapi/tibco-businessevents-openapi.yml](openapi/tibco-businessevents-openapi.yml) |
| TIBCO Spotfire Analytics API | [openapi/tibco-spotfire-openapi.yml](openapi/tibco-spotfire-openapi.yml) |

## AsyncAPI Specifications

| Spec | Path |
|------|------|
| TIBCO Messaging API | [asyncapi/tibco-messaging-asyncapi.yml](asyncapi/tibco-messaging-asyncapi.yml) |

## JSON Schemas

| Schema | Path |
|--------|------|
| TIBCO Integration App | [json-schema/tibco-integration-app-schema.json](json-schema/tibco-integration-app-schema.json) |
| TIBCO API Service | [json-schema/tibco-api-service-schema.json](json-schema/tibco-api-service-schema.json) |

## JSON Structure

| Structure | Path |
|-----------|------|
| TIBCO Integration App Structure | [json-structure/tibco-integration-app-structure.json](json-structure/tibco-integration-app-structure.json) |

## JSON-LD

| Context | Path |
|---------|------|
| TIBCO Context | [json-ld/tibco-context.jsonld](json-ld/tibco-context.jsonld) |

## Examples

| Example | Path |
|---------|------|
| Cloud Integration List Apps | [examples/tibco-cloud-integration-list-apps-example.json](examples/tibco-cloud-integration-list-apps-example.json) |
| Mashery List API Services | [examples/tibco-mashery-list-api-services-example.json](examples/tibco-mashery-list-api-services-example.json) |
| Spotfire List Library Items | [examples/tibco-spotfire-list-library-items-example.json](examples/tibco-spotfire-list-library-items-example.json) |

## Spectral Rules

| Ruleset | Path |
|---------|------|
| TIBCO API Rules | [rules/tibco-rules.yml](rules/tibco-rules.yml) |

## Naftiko Capabilities

### Shared API Definitions

| API | Path |
|-----|------|
| TIBCO Cloud Integration | [capabilities/shared/cloud-integration.yaml](capabilities/shared/cloud-integration.yaml) |
| TIBCO Mashery | [capabilities/shared/mashery.yaml](capabilities/shared/mashery.yaml) |
| TIBCO Spotfire | [capabilities/shared/spotfire.yaml](capabilities/shared/spotfire.yaml) |

### Workflow Capabilities

| Workflow | APIs | Description |
|----------|------|-------------|
| [Integration Platform](capabilities/integration-platform.yaml) | TCI + Mashery | App lifecycle, connections, deployments, and API gateway management |
| [Analytics and Reporting](capabilities/analytics-and-reporting.yaml) | Spotfire | Library management, analyses, data sources, and user management |

## Vocabulary

| Vocabulary | Path |
|------------|------|
| TIBCO Vocabulary | [vocabulary/tibco-vocabulary.yml](vocabulary/tibco-vocabulary.yml) |

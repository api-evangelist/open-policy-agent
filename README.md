# Open Policy Agent (open-policy-agent)

Open Policy Agent (OPA) is an open-source project that provides a flexible and powerful policy engine for cloud-native environments. OPA enables users to define and enforce policies across their infrastructure, applications, and services through a declarative language called Rego. OPA integrates seamlessly with popular tools and frameworks like Kubernetes, Istio, and Envoy, making it easy to implement fine-grained access control, security, and compliance policies.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Policies
- Standards

## Timestamps

- **Created:** 2024-11-18
- **Modified:** 2026-05-19

## APIs

### Open Policy Agent Policy API

API for managing policy modules, allowing CRUD operations on Rego policy files stored in OPA.

- **Human URL:** [https://www.openpolicyagent.org/docs/latest/rest-api/#policy-api](https://www.openpolicyagent.org/docs/latest/rest-api/#policy-api)

#### Tags

- Management
- Policies
- Rego

#### Properties

- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/#policy-api)
- [OpenAPI](openapi/policy-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/policy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/policy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/opa-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Bruno Collection](policy/bruno.json)
- [Postman Collection](
https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-19ce2c88-97b8-4f58-a101-b8be70794a85) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Open Policy Agent Data API

API for reading and writing documents in OPA (Open Policy Agent).

- **Human URL:** [https://www.openpolicyagent.org/docs/latest/rest-api/#data-api](https://www.openpolicyagent.org/docs/latest/rest-api/#data-api)

#### Tags

- Data
- Documents
- Storage

#### Properties

- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/#data-api)
- [OpenAPI](openapi/data-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Bruno Collection](data/bruno.json)
- [Postman Collection](
https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-96c58dc4-3514-48ee-a35f-a9c2aeb14fa0) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Open Policy Agent Query API

API for executing simple and ad-hoc queries in OPA (Open Policy Agent).

- **Human URL:** [https://www.openpolicyagent.org/docs/latest/rest-api/#query-api](https://www.openpolicyagent.org/docs/latest/rest-api/#query-api)

#### Tags

- Evaluation
- Queries
- Rego

#### Properties

- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/#query-api)
- [OpenAPI](openapi/query-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/query-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Bruno Collection](query/bruno.json)
- [Postman Collection](
https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-9170dd84-c3d5-45a4-9efc-9ef6ab30744e) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Open Policy Agent Compile API

API for partially evaluating Rego queries in OPA (Open Policy Agent).

- **Human URL:** [https://www.openpolicyagent.org/docs/latest/rest-api/#compile-api](https://www.openpolicyagent.org/docs/latest/rest-api/#compile-api)

#### Tags

- Compile
- Evaluation
- Partial Evaluation

#### Properties

- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/#compile-api)
- [OpenAPI](openapi/compile-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/compile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/compile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Bruno Collection](compile/bruno.json)
- [Postman Collection](
https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-1e1d8e0e-7157-4b7f-99cf-611fa56a0c3c) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Open Policy Agent Health API

API for checking the health and readiness of an OPA (Open Policy Agent) server.

- **Human URL:** [https://www.openpolicyagent.org/docs/latest/rest-api/#health-api](https://www.openpolicyagent.org/docs/latest/rest-api/#health-api)

#### Tags

- Availability
- Health
- Monitoring

#### Properties

- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/#health-api)
- [OpenAPI](openapi/health-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/health-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/health-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Bruno Collection](health/bruno.json)
- [Postman Collection](
https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-198cdb4f-e1d1-44c4-aa1f-ef8f66760d1a) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Open Policy Agent Config API

API for retrieving OPA's active configuration, including discovered configurations.

- **Human URL:** [https://www.openpolicyagent.org/docs/latest/rest-api/#config-api](https://www.openpolicyagent.org/docs/latest/rest-api/#config-api)

#### Tags

- Configurations
- Discovery
- Management

#### Properties

- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/#config-api)
- [OpenAPI](openapi/config-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/config-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/config-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Bruno Collection](config/bruno.json)
- [Postman Collection](
https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-979cbaf7-8515-4fd2-8035-134685590967) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Open Policy Agent Status API

API for accessing OPA (Open Policy Agent) status information via a pull-based mechanism.

- **Human URL:** [https://www.openpolicyagent.org/docs/latest/rest-api/#status-api](https://www.openpolicyagent.org/docs/latest/rest-api/#status-api)

#### Tags

- Monitoring
- Observability
- Status

#### Properties

- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/#status-api)
- [OpenAPI](openapi/status-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Bruno Collection](status/bruno.json)
- [Postman Collection](
https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-b4943ca3-d651-4c68-a003-e6ca7feace03) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/open-policy-agent)
- [JSON Schema](json-schema/opa-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/opa-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Website](https://www.openpolicyagent.org/)
- [Documentation](https://www.openpolicyagent.org/docs/latest/)
- [Documentation](https://www.openpolicyagent.org/docs/latest/rest-api/)
- [Getting Started](https://www.openpolicyagent.org/docs/latest/#running-opa)
- [Authentication](https://www.openpolicyagent.org/docs/latest/rest-api/#authentication)
- [Errors](https://www.openpolicyagent.org/docs/latest/rest-api/#errors)
- [GitHub Organization](https://github.com/open-policy-agent)
- [GitHub Repository](https://github.com/open-policy-agent/opa)
- [Blog](https://blog.openpolicyagent.org/)
- [Community](https://www.openpolicyagent.org/community/)
- [Slack](https://slack.openpolicyagent.org/)
- [Changelog](https://github.com/open-policy-agent/opa/blob/main/CHANGELOG.md)
- [Security](https://github.com/open-policy-agent/opa/security/policy)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/open-policy-agent)
- [Postman Workspace](https://www.postman.com/api-evangelist/open-policy-agent/overview)
- [GitHub Repository](https://github.com/api-search/open-policy-agent)
- [Integrations](https://www.openpolicyagent.org/ecosystem)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

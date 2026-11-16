# Circuit Connector Specs

Public OpenAPI specs for building Cisco Circuit "Connector Studio" connectors.
Contains no credentials and no customer data — only public API path/schema definitions.

- `cisco_support_api_openapi.{json,yaml}` — Cisco Support APIs (EoX v5, SN2Info v2, Case v3).
- `cx_cloud_api_2_0_0.{json,yaml}` — Cisco CX Cloud API v2 (Inventory, Contracts, Product Alerts,
  Customer). Source: developer.cisco.com/docs/cx-cloud (official "Download OpenAPI Document"),
  unmodified. Base URL `https://apix.cisco.com/cs/api/v2`, OAuth2 `apis:read`,
  token `https://id.cisco.com/oauth2/default/v1/token`.

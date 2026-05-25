# Extreme Networks

Extreme Networks (NASDAQ: EXTR) is a Morrisville, North Carolina–headquartered enterprise networking company providing cloud-managed wired switching, Wi-Fi 6E and Wi-Fi 7 wireless access, SD-WAN, and integrated network security for education, healthcare, government, retail, manufacturing, and large venues. Its flagship offering is **Extreme Platform ONE**, an AI-driven networking platform that unifies wired, wireless, and security operations on top of **ExtremeCloud IQ**, the company's multi-tenant cloud network management system.

## APIs

This profile captures the public API surface and tooling Extreme Networks exposes to developers and network automation engineers.

### ExtremeCloud IQ API (Tier-1)

ExtremeCloud IQ is the flagship public API, a comprehensive OpenAPI 3.0 specification (version `25.9.0-36` at time of capture) covering **460+ operations** across:

- Authentication, API tokens, and permissions
- Accounts, users, and hierarchical multi-org management (HIQ)
- Locations, floor plans, and Geo-View
- Devices across Cloud Engine / IQ Engine / WiNG / VOSS / EXOS
- Network Policy for wired and wireless
- Clients, applications, and Network Scorecard
- Alerts, logs, and notifications
- Deployment and configuration management
- Copilot Connectivity Experience and anomalies
- Packet captures
- SD-WAN, AFC, Universal Compute Platform
- Dashboards (wireless/wired client health, usage, capacity, device health)
- ExtremeLocation
- NG Reports and scheduled reports

Base URL: `https://api.extremecloudiq.com`  License: Apache 2.0.

- Developer portal: <https://developer.extremecloudiq.com/>
- API reference: <https://extremecloudiq.com/api-docs/api-reference.html>
- Canonical OpenAPI: [`openapi/extremecloud-iq-openapi.yml`](openapi/extremecloud-iq-openapi.yml) (mirrored from [extremenetworks/ExtremeCloudIQ-OpenAPI-Specification](https://github.com/extremenetworks/ExtremeCloudIQ-OpenAPI-Specification))

### On-Premises Controller APIs

For customers running the on-prem **ExtremeCloud IQ Controller** (campus wireless controller), Extreme exposes:

- [REST API Gateway](https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.03.01/API/index_gateway_api.html) — sites, RF management, AP/switch provisioning, RADIUS, NAC, reporting
- [Application Manager API](https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.05.02/API/index_apps_manager.html) — Layer 7 application visibility and per-application policy

### SDKs

Official client libraries are published for the ExtremeCloud IQ API:

| Language    | Repository |
|-------------|------------|
| Python      | [ExtremeCloudIQ-SDK-Python](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Python) |
| Java        | [ExtremeCloudIQ-SDK-Java](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Java) |
| Go          | [ExtremeCloudIQ-SDK-Go](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Go) |
| JavaScript  | [ExtremeCloudIQ-SDK-Javascript](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Javascript) |
| C#          | [ExtremeCloudIQ-SDK-CSharp](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-CSharp) |

A 400+ request **Postman collection** alongside a Python helper library lives in [extremenetworks/ExtremeCloudIQ-APIs](https://github.com/extremenetworks/ExtremeCloudIQ-APIs).

### Ansible Collections

Extreme publishes maintained Ansible Network Collections for on-box switch automation:

- [ansible_collections.extreme.exos](https://github.com/extremenetworks/ansible_collections.extreme.exos) — EXOS
- [ansible_collections.extreme.voss](https://github.com/extremenetworks/ansible_collections.extreme.voss) — VOSS
- [ansible_collections.extreme.slxos](https://github.com/extremenetworks/ansible_collections.extreme.slxos) — SLX-OS
- [ansible_collections.extreme.nos](https://github.com/extremenetworks/ansible_collections.extreme.nos) — NOS
- [ansible_collections.extreme.fe](https://github.com/extremenetworks/ansible_collections.extreme.fe) — Fabric Engine

## Repository Layout

```
extreme-networks/
├── apis.yml                              ← canonical APIs.json catalog
├── README.md                             ← this file
└── openapi/
    └── extremecloud-iq-openapi.yml       ← ExtremeCloud IQ OpenAPI 3.0 spec
```

## Useful Links

- Website: <https://www.extremenetworks.com/>
- Extreme Platform ONE: <https://www.extremenetworks.com/platform-one>
- ExtremeCloud IQ: <https://www.extremecloudiq.com/>
- Status: <https://status.extremecloudiq.com/>
- GitHub org: <https://github.com/extremenetworks>
- Documentation portal: <https://documentation.extremenetworks.com/>
- Investor relations: <https://investor.extremenetworks.com/>

## Maintainer

Kin Lane — <kin@apievangelist.com>

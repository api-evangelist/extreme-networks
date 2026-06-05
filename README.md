# Extreme Networks (extreme-networks)

Extreme Networks (NASDAQ: EXTR) is a Morrisville, North Carolina–headquartered enterprise networking company that provides cloud-managed wired switching, Wi-Fi 6E/Wi-Fi 7 wireless access, SD-WAN, and integrated network security for education, healthcare, government, retail, manufacturing, and large venues. Its flagship platform is Extreme Platform ONE, an AI-driven networking platform that unifies wired, wireless, and security operations, built on top of ExtremeCloud IQ — the company's multi-tenant, cloud-managed network management system. ExtremeCloud IQ exposes a comprehensive OpenAPI 3.0 REST API at api.extremecloudiq.com covering authentication, device lifecycle, network policy, client and application analytics, alerts, dashboards, SD-WAN, Copilot connectivity experience, packet captures, and hierarchical multi-organization management, with official SDKs in Python, Java, Go, JavaScript, and C#. Extreme also publishes Ansible collections for EXOS, VOSS, SLXOS, NOS, and Fabric Engine for declarative on-box switch configuration, a public Postman collection of 400+ requests, and a portfolio of on-prem REST gateways for ExtremeCloud IQ Controller (campus wireless controller) and Application Manager.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/extreme-networks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/extreme-networks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Networking
- Wireless
- Wired
- Switching
- Wi-Fi
- Wi-Fi 7
- Cloud Management
- SD-WAN
- Network Security
- Network Management
- AI Networking
- Enterprise

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### ExtremeCloud IQ API

The ExtremeCloud IQ REST API enables customers and partners to manage, monitor, and provision any ExtremeCloud IQ environment. It is an OpenAPI 3.0 surface with 460+ operations covering authentication and API tokens, accounts and users, hierarchical organizations (HIQ), locations and floor plans, devices across Cloud Engine / IQ Engine / WiNG / VOSS / EXOS, network policy for wired and wireless, network scorecards, clients, application metrics, alerts, logs, notifications, deployment and configuration management, Copilot anomalies and connectivity experience, packet captures, ExtremeLocation, SD-WAN, AFC, Universal Compute Platform, and dashboards. Hosted at https://api.extremecloudiq.com and licensed under Apache 2.0.

- **Human URL:** [https://developer.extremecloudiq.com/](https://developer.extremecloudiq.com/)
- **Base URL:** `https://api.extremecloudiq.com`

#### Tags

- Networking
- Cloud Management
- Wireless
- Wired
- SD-WAN
- Device Management
- Network Policy

#### Properties

- [Documentation](https://developer.extremecloudiq.com/documentation/)
- [API Reference](https://extremecloudiq.com/api-docs/api-reference.html)
- [OpenAPI](openapi/extremecloud-iq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Source Open A P I](https://github.com/extremenetworks/ExtremeCloudIQ-OpenAPI-Specification/blob/main/xcloudiq-openapi.yaml)
- [Swagger U I](https://api.extremecloudiq.com/swagger-ui/index.html)
- [SDK](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Python)
- [SDK](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Java)
- [SDK](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Go)
- [SDK](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-Javascript)
- [SDK](https://github.com/extremenetworks/ExtremeCloudIQ-SDK-CSharp)
- [Postman Collection](https://github.com/extremenetworks/ExtremeCloudIQ-APIs) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Sign Up](https://www.extremenetworks.com/cloud-networking/)
- [Terms of Service](https://www.extremenetworks.com/company/legal/terms-of-use/)

### ExtremeCloud IQ Controller REST API Gateway

On-premises REST API gateway exposed by the ExtremeCloud IQ Controller (the wired and wireless campus controller). Provides programmatic access to controller configuration, sites, RF management, AP and switch provisioning, RADIUS, NAC, and reporting on locally managed Extreme infrastructure. Version 10.03.01 of the gateway is documented at documentation.extremenetworks.com.

- **Human URL:** [https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.03.01/API/index_gateway_api.html](https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.03.01/API/index_gateway_api.html)

#### Tags

- Networking
- Wireless
- Controller
- On-Premises

#### Properties

- [Documentation](https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.03.01/API/index_gateway_api.html)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ExtremeCloud IQ Controller Application Manager API

Application Manager REST API for the ExtremeCloud IQ Controller, enabling visibility into Layer 7 application traffic, per-application policy, and per-application reporting on locally managed Extreme wireless and wired networks.

- **Human URL:** [https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.05.02/API/index_apps_manager.html](https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.05.02/API/index_apps_manager.html)

#### Tags

- Networking
- Application Visibility
- Policy
- On-Premises

#### Properties

- [Documentation](https://documentation.extremenetworks.com/ExtremeCloud_IQ_Controller/v10.05.02/API/index_apps_manager.html)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Network Collection for Extreme EXOS

Ansible collection providing modules and roles to automate configuration and operations of Extreme Networks EXOS switches (e.g. ExtremeSwitching X-Series, Summit). Supports declarative network configuration, fact gathering, and CLI/API access for EXOS-based devices.

- **Human URL:** [https://github.com/extremenetworks/ansible_collections.extreme.exos](https://github.com/extremenetworks/ansible_collections.extreme.exos)

#### Tags

- Networking
- Automation
- Ansible
- EXOS
- Switching

#### Properties

- [Repository](https://github.com/extremenetworks/ansible_collections.extreme.exos)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Network Collection for Extreme VOSS

Ansible collection for Extreme Networks VOSS (VSP Operating System) switches, including Fabric Engine devices. Provides modules for declarative configuration of VOSS-based platforms.

- **Human URL:** [https://github.com/extremenetworks/ansible_collections.extreme.voss](https://github.com/extremenetworks/ansible_collections.extreme.voss)

#### Tags

- Networking
- Automation
- Ansible
- VOSS
- Switching

#### Properties

- [Repository](https://github.com/extremenetworks/ansible_collections.extreme.voss)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Network Collection for Extreme SLX-OS

Ansible collection for Extreme Networks SLX-OS data center switches. Provides modules for declarative configuration and operational tasks on SLX platforms.

- **Human URL:** [https://github.com/extremenetworks/ansible_collections.extreme.slxos](https://github.com/extremenetworks/ansible_collections.extreme.slxos)

#### Tags

- Networking
- Automation
- Ansible
- SLX-OS
- Data Center

#### Properties

- [Repository](https://github.com/extremenetworks/ansible_collections.extreme.slxos)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Network Collection for Extreme NOS

Ansible collection for Extreme Networks NOS (Network Operating System) switches, supporting declarative configuration and automation workflows.

- **Human URL:** [https://github.com/extremenetworks/ansible_collections.extreme.nos](https://github.com/extremenetworks/ansible_collections.extreme.nos)

#### Tags

- Networking
- Automation
- Ansible
- NOS

#### Properties

- [Repository](https://github.com/extremenetworks/ansible_collections.extreme.nos)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Network Collection for Extreme Fabric Engine

Ansible collection for Extreme Fabric Engine, used to automate Shortest Path Bridging (SPB) fabric configuration across Extreme VSP and ERS platforms.

- **Human URL:** [https://github.com/extremenetworks/ansible_collections.extreme.fe](https://github.com/extremenetworks/ansible_collections.extreme.fe)

#### Tags

- Networking
- Automation
- Ansible
- Fabric Engine
- SPB

#### Properties

- [Repository](https://github.com/extremenetworks/ansible_collections.extreme.fe)
- [Postman Collection](collections/extremecloud-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extremecloud-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.extremenetworks.com/)
- [Platform](https://www.extremenetworks.com/platform-one)
- [Cloud Platform](https://www.extremecloudiq.com/)
- [Products](https://www.extremenetworks.com/products)
- [Solutions](https://www.extremenetworks.com/solutions)
- [Developer Portal](https://developer.extremecloudiq.com/)
- [API Reference](https://extremecloudiq.com/api-docs/api-reference.html)
- [Git Hub](https://github.com/extremenetworks)
- [Documentation](https://documentation.extremenetworks.com/)
- [Support](https://www.extremenetworks.com/support)
- [Community](https://community.extremenetworks.com/)
- [Blog](https://www.extremenetworks.com/resources/blogs)
- [Newsroom](https://www.extremenetworks.com/company/newsroom)
- [Careers](https://www.extremenetworks.com/company/careers)
- [Investor Relations](https://investor.extremenetworks.com/)
- [Terms of Service](https://www.extremenetworks.com/company/legal/terms-of-use/)
- [Privacy Policy](https://www.extremenetworks.com/company/legal/privacy/)
- [Trust](https://www.extremenetworks.com/company/trust/)
- [Status](https://status.extremecloudiq.com/)
- [Twitter](https://twitter.com/ExtremeNetworks)
- [LinkedIn](https://www.linkedin.com/company/extreme-networks)
- [YouTube](https://www.youtube.com/user/ExtremeNetworks)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

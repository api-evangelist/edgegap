# Edgegap (edgegap)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Edgegap provides distributed edge game-server orchestration, hosting, and matchmaking. Its Arbitrium platform auto-deploys dedicated game servers as containers to the optimal edge location out of 615+ locations worldwide, reducing latency for players. The REST API covers applications, versions, deployments, sessions, matchmaking, distributed relays, monitoring, and private fleets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/edgegap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/edgegap/refs/heads/main/apis.yml)

## Tags

- Game Servers
- Orchestration
- Edge Computing
- Matchmaking
- Hosting

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Edgegap Applications API

Register and manage applications on Edgegap, including activation state and telemetry agent configuration, via paginated list, create, get, update, and delete operations under /v1/app.

- **Human URL:** [https://docs.edgegap.com/docs/api/dedicated-servers](https://docs.edgegap.com/docs/api/dedicated-servers)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- Applications
- Game Servers

#### Properties

- [Documentation](https://docs.edgegap.com/docs/api/dedicated-servers)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Edgegap App Versions API

Manage container image versions for an application - Docker repository/image/tag, vCPU and memory, ports, environment variables, and session configuration - via /v1/app/{app_name}/version endpoints.

- **Human URL:** [https://docs.edgegap.com/docs/api/versioning](https://docs.edgegap.com/docs/api/versioning)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- App Versions
- Container Images

#### Properties

- [Documentation](https://docs.edgegap.com/docs/api/versioning)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Edgegap Deployments API

Auto-deploy dedicated servers to the optimal edge location for supplied player IPs or coordinates, then list, inspect status, tag, pull container logs, and stop deployments via /v2/deployments and /v1/deployments endpoints.

- **Human URL:** [https://docs.edgegap.com/learn/orchestration/deployments](https://docs.edgegap.com/learn/orchestration/deployments)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- Deployments
- Dedicated Servers
- Edge

#### Properties

- [Documentation](https://docs.edgegap.com/learn/orchestration/deployments)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Edgegap Sessions API

Dynamically add or remove players and groups of players on a running deployment. Create, get, and delete sessions and list session users via /v1/session endpoints for server-to-server session integration.

- **Human URL:** [https://docs.edgegap.com/docs/session](https://docs.edgegap.com/docs/session)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- Sessions
- Player Management

#### Properties

- [Documentation](https://docs.edgegap.com/docs/session)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Edgegap Matchmaking API

Create and poll matchmaking tickets on a deployed matchmaker service. Tickets are matched into groups and a server is auto-deployed at the edge for the matched players, exposed via /tickets endpoints.

- **Human URL:** [https://docs.edgegap.com/learn/api/matchmaking](https://docs.edgegap.com/learn/api/matchmaking)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- Matchmaking
- Tickets

#### Properties

- [Documentation](https://docs.edgegap.com/learn/api/matchmaking)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Edgegap Relays API

Create distributed relay sessions that route peer-to-peer or client-server traffic through Edgegap's network, hiding player IPs and mitigating DDoS. List, get, delete sessions and authorize/revoke users via /v1/relays/sessions endpoints.

- **Human URL:** [https://docs.edgegap.com/docs/api/relays](https://docs.edgegap.com/docs/api/relays)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- Relays
- Networking
- Anti-DDoS

#### Properties

- [Documentation](https://docs.edgegap.com/docs/api/relays)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Edgegap Metrics API

Retrieve monitoring telemetry - CPU, memory, and network metrics - for a running deployment via /v1/metrics/deployment/{deployment_id} to observe dedicated server health at the edge.

- **Human URL:** [https://docs.edgegap.com/docs/api/dedicated-servers](https://docs.edgegap.com/docs/api/dedicated-servers)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- Metrics
- Monitoring
- Telemetry

#### Properties

- [Documentation](https://docs.edgegap.com/docs/api/dedicated-servers)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Edgegap Fleets API

Deploy onto self-managed hosts registered in a private fleet for hybrid infrastructure, and enumerate fleet hosts, via /v2/private-fleets/deployments and /v2/private-fleets/{fleet_name}/hosts.

- **Human URL:** [https://docs.edgegap.com/docs/deployment/session/fleet-manager/fleet-policy](https://docs.edgegap.com/docs/deployment/session/fleet-manager/fleet-policy)
- **Base URL:** `https://api.edgegap.com`

#### Tags

- Fleets
- Private Hosts
- Hybrid

#### Properties

- [Documentation](https://docs.edgegap.com/docs/deployment/session/fleet-manager/fleet-policy)
- [OpenAPI](openapi/edgegap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edgegap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edgegap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/edgegap)
- [LinkedIn](https://www.linkedin.com/company/edgegap)
- [Website](https://edgegap.com/)
- [Documentation](https://docs.edgegap.com/)
- [Plans](plans/edgegap-plans-pricing.yml)
- [Rate Limits](rate-limits/edgegap-rate-limits.yml)
- [Fin Ops](finops/edgegap-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

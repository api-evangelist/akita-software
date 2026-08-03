# Akita Software (akita-software)

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

Akita Software was an API observability and analysis platform that used passive traffic monitoring to automatically map APIs, detect changes, and identify issues without requiring code changes or proxies. Akita was acquired by Postman in November 2023 and its technology has been integrated into the Postman platform as Postman Live Insights. The Akita agent is now available as the open-source Postman Insights Agent.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/akita-software/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Acquired, API Discovery, API Mapping, API Observability, Traffic Analysis

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### Akita Software
Akita Software provided an API observability platform that used passive traffic monitoring to automatically discover, map, and model APIs without requiring code changes or proxying.

**Human URL:** [https://www.akitasoftware.com](https://www.akitasoftware.com)

#### Tags:

 - API Discovery, API Mapping, API Observability, Traffic Analysis

#### Properties

- [Documentation](https://docs.akita.software)
- [GitHubOrganization](https://github.com/akitasoftware)
- [GettingStarted](https://docs.akita.software/docs/getting-started)

### Postman Live Insights
Postman Live Insights is the successor to Akita Software, now integrated into the Postman platform. The Postman Insights Agent (open source) enables passive API traffic monitoring and discovery.

**Human URL:** [https://www.postman.com/product/live-insights/](https://www.postman.com/product/live-insights/)

#### Tags:

 - API Discovery, API Monitoring, API Observability, Postman

#### Properties

- [Documentation](https://learning.postman.com/docs/insights/insights-overview/)
- [GitHubRepository](https://github.com/postmanlabs/postman-insights-agent)
- [GettingStarted](https://learning.postman.com/docs/insights/insights-gs/)

## Common Properties

- [Website](https://www.akitasoftware.com)
- [Documentation](https://docs.akita.software)
- [GitHubOrganization](https://github.com/akitasoftware)
- [Blog](https://blog.akita.software)
- [X](https://twitter.com/akaboraitasoftware)
- [LinkedIn](https://www.linkedin.com/company/akita-software/)

## Features

| Name | Description |
|------|-------------|
| Passive Traffic Monitoring | Monitors API traffic passively without code changes, SDK installation, or proxying, minimizing operational overhead and risk. |
| Automatic API Spec Generation | Generates OpenAPI specifications automatically from observed traffic, keeping documentation always up to date. |
| Breaking Change Detection | Detects breaking API changes by comparing observed traffic patterns across deployments and branches. |
| API Performance Monitoring | Tracks API response times, error rates, and traffic patterns to help identify performance regressions. |
| Multi-Platform Integration | Integrates with Docker, Kubernetes, NGINX, Rails, Django, Flask, FastAPI, and Heroku for broad platform coverage. |

## Use Cases

| Name | Description |
|------|-------------|
| API Documentation Generation | Engineering teams automatically generate and maintain up-to-date API specs from production traffic without manual effort. |
| API Change Management | Teams detect unintentional API breaking changes between branches or deployments before they reach production. |
| API Discovery | Organizations discover undocumented and shadow APIs by monitoring actual network traffic across their services. |
| Production API Monitoring | DevOps teams monitor API behavior and performance in production to quickly identify and diagnose issues. |

## Integrations

| Name | Description |
|------|-------------|
| Docker | Docker extension and container integration for traffic monitoring |
| Kubernetes | Kubernetes deployment support for monitoring microservice APIs |
| NGINX | NGINX module for mirroring API traffic to the Akita agent |
| Heroku | Heroku buildpack for integrating Akita with Heroku applications |
| Postman | Acquired by Postman in 2023; technology integrated as Postman Live Insights |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

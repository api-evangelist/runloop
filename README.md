# Runloop (runloop)

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

Runloop provides AI-native cloud development environments (devboxes) and an agent benchmarking platform. The Runloop API lets you programmatically spin up isolated Linux devboxes, run and stream commands, mount code, snapshot state via blueprints and snapshots, and evaluate coding agents against scenarios and benchmarks - all over a Bearer-authenticated REST interface at api.runloop.ai/v1.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/runloop/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/runloop/refs/heads/main/apis.yml)

## Tags

- AI
- Developer Environments
- Devboxes
- Coding Agents
- Benchmarking
- Cloud IDE

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Runloop Devboxes API

Create and manage isolated cloud Linux devboxes - launch, suspend, resume, shut down and keep-alive; execute shell commands synchronously or asynchronously; stream logs; read, write, upload and download files; open tunnels; and snapshot disk state.

- **Human URL:** [https://docs.runloop.ai/devboxes](https://docs.runloop.ai/devboxes)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Devboxes
- Compute
- Sandboxes
- Command Execution

#### Properties

- [Documentation](https://docs.runloop.ai/devboxes)
- [API Reference](https://docs.runloop.ai/api-reference/devboxes)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runloop Blueprints API

Define and build custom, reproducible devbox base images from a Dockerfile or system setup commands, preview builds, inspect build logs, and reuse blueprints as the starting point for new devboxes.

- **Human URL:** [https://docs.runloop.ai/blueprints](https://docs.runloop.ai/blueprints)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Blueprints
- Images
- Build
- Reproducibility

#### Properties

- [Documentation](https://docs.runloop.ai/blueprints)
- [API Reference](https://docs.runloop.ai/api-reference/blueprints)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runloop Snapshots API

Capture, list, query and delete point-in-time disk snapshots of a running devbox so a new devbox can be launched from the exact saved state.

- **Human URL:** [https://docs.runloop.ai/devboxes/snapshots](https://docs.runloop.ai/devboxes/snapshots)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Snapshots
- State
- Checkpoints

#### Properties

- [Documentation](https://docs.runloop.ai/devboxes/snapshots)
- [API Reference](https://docs.runloop.ai/api-reference/devboxes/snapshots)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runloop Code Mounts API

Mount source code from a connected Git repository or credentials into a devbox at launch so agents start from a prepared, versioned workspace.

- **Human URL:** [https://docs.runloop.ai/devboxes/code-mounts](https://docs.runloop.ai/devboxes/code-mounts)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Code Mounts
- Repositories
- Source Code

#### Properties

- [Documentation](https://docs.runloop.ai/devboxes/code-mounts)
- [API Reference](https://docs.runloop.ai/api-reference/code-mounts)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runloop Repositories API

Register and inspect Git repository connections so repositories can be analyzed and mounted into devboxes and used as inputs to scenarios.

- **Human URL:** [https://docs.runloop.ai/repositories](https://docs.runloop.ai/repositories)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Repositories
- Git
- Connections

#### Properties

- [Documentation](https://docs.runloop.ai/repositories)
- [API Reference](https://docs.runloop.ai/api-reference/repositories)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runloop Scenarios API

Define reproducible coding-agent tasks with a starting environment, input context and scoring contract; start scenario runs, then score and complete them to measure agent performance.

- **Human URL:** [https://docs.runloop.ai/scenarios](https://docs.runloop.ai/scenarios)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Scenarios
- Agent Evaluation
- Scoring

#### Properties

- [Documentation](https://docs.runloop.ai/scenarios)
- [API Reference](https://docs.runloop.ai/api-reference/scenarios)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runloop Benchmarks API

Group scenarios into benchmarks and run a coding agent across the whole suite, aggregating per-scenario scores into a single benchmark run for comparing agents and models.

- **Human URL:** [https://docs.runloop.ai/benchmarks](https://docs.runloop.ai/benchmarks)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Benchmarks
- Evaluation
- Leaderboards

#### Properties

- [Documentation](https://docs.runloop.ai/benchmarks)
- [API Reference](https://docs.runloop.ai/api-reference/benchmarks)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Runloop Objects API

Upload, list, download and delete binary objects (artifacts, datasets, results) via pre-signed URLs for use as inputs to and outputs from devboxes, scenarios and benchmarks.

- **Human URL:** [https://docs.runloop.ai/objects](https://docs.runloop.ai/objects)
- **Base URL:** `https://api.runloop.ai/v1`

#### Tags

- Objects
- Blob Storage
- Artifacts

#### Properties

- [Documentation](https://docs.runloop.ai/objects)
- [API Reference](https://docs.runloop.ai/api-reference/objects)
- [OpenAPI](openapi/runloop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/runloop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/runloop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/runloopai)
- [LinkedIn](https://www.linkedin.com/company/runloopai)
- [Website](https://www.runloop.ai/)
- [Documentation](https://docs.runloop.ai/)
- [Plans](plans/runloop-plans-pricing.yml)
- [Rate Limits](rate-limits/runloop-rate-limits.yml)
- [Fin Ops](finops/runloop-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

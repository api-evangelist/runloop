# Runloop (runloop)

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

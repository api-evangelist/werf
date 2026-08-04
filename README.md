# Werf (werf)

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

Werf is an open-source CNCF sandbox project providing a complete GitOps-based CI/CD solution for Kubernetes. It implements the full application delivery lifecycle — building images, managing dependencies, deploying Helm charts, and cleaning up container registries — using Git as the single source of truth (Giterminism). Werf integrates natively with all major CI systems, Buildah, Helm, and Kubernetes.

**URL:** [https://werf.io/](https://werf.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - CI/CD, Deployment, DevOps, GitOps, Kubernetes, CNCF, Helm, Containers, Open Source

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## Common Properties

- [Website](https://werf.io/)
- [Documentation](https://werf.io/docs/v2/)
- [Getting Started](https://werf.io/getting_started/)
- [GitHub Organization](https://github.com/werf)
- [GitHub Repository - werf](https://github.com/werf/werf)
- [CLI - Werf CLI](https://github.com/werf/werf)
- [GitHub Repository - Nelm](https://github.com/werf/nelm)
- [GitHub Repository - Kubedog](https://github.com/werf/kubedog)
- [GitHub Repository - TRDL](https://github.com/werf/trdl)
- [GitHub Repository - GitHub Actions](https://github.com/werf/actions)
- [GitHub Repository - Nelm Chart TypeScript SDK](https://github.com/werf/nelm-chart-ts-sdk)
- [Change Log](https://github.com/werf/werf/releases)
- [Support](https://github.com/werf/werf/discussions)

## Features

| Name | Description |
|------|-------------|
| Giterminism | Uses Git as the single source of truth, ensuring all CI/CD configurations are reproducible and auditable from version control. |
| Incremental Builds | Rebuilds only modified components and reuses existing container registry layers, dramatically reducing build times. |
| Kubernetes Deployment | Manages Helm chart deployments to Kubernetes with built-in rollback, planning, and drift detection (werf converge, werf plan, werf rollback). |
| Container Registry Cleanup | Automatically cleans up stale images from container registries using Git history-aware policies (werf cleanup, werf purge). |
| Helm Integration | Full Helm chart management including rendering, linting, bundling, and deploying with werf helm command suite. |
| Multi-CI Support | Native integration with GitHub Actions, GitLab CI, CircleCI, Jenkins, and other CI systems via werf ci-env. |
| Secure Software Delivery | TRDL component provides TUF-based secure software update distribution with GPG signature verification. |

## Use Cases

| Name | Description |
|------|-------------|
| Kubernetes Application Delivery | Build, test, and deploy containerized applications to Kubernetes clusters using GitOps principles. |
| Monorepo CI/CD | Manage CI/CD pipelines for monorepo projects with independent image tagging and selective component redeployment. |
| Helm Chart Management | Package, bundle, and deploy Helm charts with integrated dependency management and Kubernetes compatibility checks. |
| Container Registry Management | Automate container image lifecycle from build to cleanup using content-based tagging and Git-aware retention policies. |
| Secure Software Distribution | Distribute software updates securely using TUF framework with TRDL, ensuring integrity and authenticity of delivered artifacts. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub Actions | Native GitHub Actions for incorporating werf into GitHub-hosted CI/CD pipelines. |
| GitLab CI | First-class support for GitLab CI/CD environment variables and pipeline integration. |
| Helm | Deep integration with Helm package manager for Kubernetes, extending it with werf-specific deployment guarantees. |
| Buildah | Uses Buildah for rootless, daemonless OCI image builds without requiring Docker. |
| Kubernetes | Direct integration with Kubernetes API for deploying, monitoring, and managing application resources. |
| OCI Registries | Compatible with all OCI-compliant container registries including Docker Hub, GHCR, GitLab Registry, and cloud registries. |
| CNCF Ecosystem | CNCF Sandbox project integrating with the broader cloud-native ecosystem including Flux CD and other CNCF tools. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

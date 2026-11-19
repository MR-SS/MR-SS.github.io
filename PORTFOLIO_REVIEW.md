# GitHub portfolio refresh — review checklist

This is a proposal for the public-facing GitHub profile. No profile repository, profile bio, pin configuration, or public website content is modified by this document.

## Proposed GitHub bio

Software Security Engineer | AppSec, DevSecOps & Secure SDLC | Security Research

## Profile README

Copy [GITHUB_PROFILE_DRAFT.md](GITHUB_PROFILE_DRAFT.md) into `MR-SS/MR-SS` as `README.md` **only after** a public repository named `MR-SS` has been created under this account and the content is approved.

## Six suggested pins (subject to code and maintenance checks)

1. [mcp-security-research-](https://github.com/MR-SS/mcp-security-research-) — research artifact, DOI and carefully bounded results
2. [defectdojo-security-lab](https://github.com/MR-SS/defectdojo-security-lab) — research harness and provenance
3. [DevSecOps-Pipeline-Hub](https://github.com/MR-SS/DevSecOps-Pipeline-Hub) — security engineering templates
4. [python-race-conditions](https://github.com/MR-SS/python-race-conditions) — Python security lab
5. [defectdojo-helm-smtp-lab](https://github.com/MR-SS/defectdojo-helm-smtp-lab) — local reproducible Helm lab
6. [MR-SS.github.io](https://github.com/MR-SS/MR-SS.github.io) — personal portfolio source

Pinning is a manual profile operation in the current connector, and is not performed by this PR.

## Claims and disclosure guardrails

- Do not describe submitted upstream pull requests as merged until verified.
- MoreFixes is published research; MCP measurement is pre-paper/in progress.
- Do not list CVE IDs until independently verified with public records.
- Do not publicize private PipelineGuard material, the Apache Kafka private disclosure or its reproduction details.
- Repository documentation should distinguish tests actually executed from intended integrations.
- Verify the public GitHub Pages site separately before updating production page content.

## Review actions before merging

- Check links and exact publication bibliographic details.
- Verify claims of project tests and dates with the owning repositories.
- Choose the final six pins after checking the current GitHub profile.
- Manually create the profile repository and set bio only after explicit approval.

# Repository development rules

## Mandatory Actions cost and scope policy (owner directive, 2026-11-15)

- Each issue gets only directly relevant tests, builds, audits and workflows. Do not rerun passing checks or automatically launch full-project suites for unrelated changes.
- Keep CI path-scoped and nonduplicative; before adding runners, schedules, artifact uploads or triggers, document their purpose, frequency and potential monthly cost. Use manual execution for expensive or one-off verification.
- Preserve essential release, security, backup and deployment authorization gates. Do not skip deeper acceptance required for a proposed release: identify it and request permission when appropriate.
- No merges, deployments, publications, live changes or paid services without owner authorization. Preserve the working product and track focused changes.


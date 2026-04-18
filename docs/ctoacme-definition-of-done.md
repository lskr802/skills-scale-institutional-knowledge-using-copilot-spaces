# OctoAcme — Definition of Done (DoD)

## Purpose
Provide a shared, lightweight quality gate so work is consistently “done” (not just “merged”).

> Teams can adopt the baseline DoD below and add project-specific requirements.

## Baseline DoD (default)
A backlog item is considered **Done** when:

### Scope & acceptance
- [ ] Acceptance criteria are met (validated with PdM/PM as appropriate)
- [ ] Edge cases and failure modes were considered/documented

### Code quality
- [ ] Code reviewed (at least 1 approval, or team-defined policy)
- [ ] CI is green (tests, lint, build)
- [ ] Changes are reasonably sized or intentionally split

### Testing & validation
- [ ] Unit tests added/updated (where applicable)
- [ ] Integration/E2E coverage added/updated (where applicable)
- [ ] QA validation completed when risk warrants it (document what was tested)

### Security & compliance (as needed)
- [ ] Security scanning is passing
- [ ] Secrets are not committed; least-privilege principles followed
- [ ] Privacy/data handling reviewed when changes touch sensitive data

### Observability & operability
- [ ] Logs/metrics/traces updated as needed
- [ ] Alerts/runbooks updated if operational behavior changes

### Documentation
- [ ] User-facing docs updated if behavior/UI changed
- [ ] Internal docs/runbooks updated if operational steps changed
- [ ] Release notes input prepared (if needed)

## Release-ready checklist (optional)
Use for higher-risk changes:
- [ ] Rollback plan documented
- [ ] Smoke tests identified and executed in staging
- [ ] Support/On-call informed of release and known risks
# OctoAcme — Incident & Rollback Checklist

## Purpose
Provide a calm, repeatable checklist for production issues during/after deployment.

## Trigger
Use when:
- deployment fails
- error rates spike or critical user journeys fail
- security/privacy concerns are discovered
- support reports severe customer impact

## 1) Triage (first 10 minutes)
- [ ] Declare incident severity and open an incident channel (or agreed mechanism)
- [ ] Assign roles (at minimum): Incident Lead, Comms Lead, Tech Lead
- [ ] Capture timestamp, impacted services, and symptoms
- [ ] Identify last known-good version and recent changes

## 2) Stabilize
- [ ] Decide: rollback, hotfix forward, or mitigate (feature flag / config change)
- [ ] If rollback: confirm steps, owners, and expected blast radius
- [ ] Execute rollback / mitigation
- [ ] Verify user impact is reduced (smoke tests + key dashboards)

## 3) Communication
- [ ] Notify Support/CS and key stakeholders
- [ ] Provide customer-facing update if required (status page / comms template)
- [ ] Document what changed and current status

## 4) Recovery & follow-up
- [ ] Create follow-up issues for root cause, tests, monitoring, and docs/runbooks
- [ ] Schedule blameless post-incident retro within 1–3 business days
- [ ] Update decision log / runbooks if process gaps were identified

## Post-incident retro prompts
- What was the root cause?
- What detection signals worked/failed?
- What slowed us down?
- What will prevent recurrence?
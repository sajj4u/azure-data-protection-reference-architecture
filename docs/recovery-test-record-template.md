# Recovery Test Record Template

Use this template to record evidence for a controlled backup or disaster-recovery test. Replace all example placeholders and remove information that should not be shared outside the authorized environment.

## Test Information

| Field | Value |
|---|---|
| Test reference | |
| Service or workload | |
| Business owner | |
| Technical owner | |
| Test date and window | |
| Recovery tier | Operational / Off-site / Long-term |
| Recovery method | File / Application / VM / Full service |
| Approved change reference | |

## Recovery Objectives

| Objective | Target | Actual | Result |
|---|---:|---:|---|
| Recovery Point Objective (RPO) | | | Pass / Fail |
| Recovery Time Objective (RTO) | | | Pass / Fail |
| Data validation | | | Pass / Fail |
| Application validation | | | Pass / Fail |

## Preconditions

- [ ] Scope and success criteria approved
- [ ] Recovery source and restore point identified
- [ ] Required access and permissions validated
- [ ] Network, DNS and storage dependencies confirmed
- [ ] Target recovery location prepared
- [ ] Business and technical contacts notified
- [ ] Rollback or cleanup plan documented

## Execution Record

| Time | Activity | Evidence Reference | Result |
|---|---|---|---|
| | Recovery initiated | | |
| | Data or workload restored | | |
| | Infrastructure validation completed | | |
| | Application validation completed | | |
| | Business-owner validation completed | | |
| | Cleanup completed | | |

## Validation Checklist

- [ ] Restored workload starts successfully
- [ ] Required services are running
- [ ] Network and DNS resolution operate as expected
- [ ] Application data is accessible and consistent
- [ ] Security controls and permissions are preserved
- [ ] Monitoring and backup protection are restored
- [ ] RPO and RTO results are recorded
- [ ] Screenshots, logs and job references are retained securely

## Issues and Corrective Actions

| Issue | Impact | Owner | Corrective Action | Due Date | Status |
|---|---|---|---|---|---|
| | | | | | |

## Final Outcome

- Overall result: **Pass / Pass with actions / Fail**
- Residual risks:
- Follow-up actions:
- Next scheduled test:

## Approval

| Role | Name | Decision | Date |
|---|---|---|---|
| Technical owner | | | |
| Service owner | | | |
| Business owner | | | |

> Store completed records only in an approved evidence repository. Do not commit production identifiers, internal addresses, credentials, customer data or confidential screenshots to a public repository.

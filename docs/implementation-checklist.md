# Azure Data Protection Implementation Checklist

## 1. Requirements and Scope

- [ ] Identify business owners and technical owners.
- [ ] Confirm protected subscriptions, resource groups and workloads.
- [ ] Document recovery-point, recovery-time and retention requirements.
- [ ] Identify application-aware protection requirements.
- [ ] Confirm regulatory, audit and long-term retention obligations.
- [ ] Define operational support and escalation responsibilities.

## 2. Architecture and Sizing

- [ ] Estimate protected capacity and daily change rate.
- [ ] Define expected local, immutable and archival retention.
- [ ] Calculate storage capacity with growth and operational headroom.
- [ ] Confirm compute, memory and storage performance requirements.
- [ ] Review high availability and single points of failure.
- [ ] Produce an approved logical architecture and implementation plan.

## 3. Azure Identity

- [ ] Create or assign managed identities.
- [ ] Apply least-privilege RBAC at the correct scope.
- [ ] Validate subscription and workload discovery permissions.
- [ ] Separate administrative and recovery responsibilities.
- [ ] Record ownership and access-review requirements.

## 4. Networking and DNS

- [ ] Confirm VNet and subnet placement.
- [ ] Validate routes, NSGs and firewall rules.
- [ ] Configure private endpoints where required.
- [ ] Create and link private DNS zones.
- [ ] Validate forward and reverse resolution where applicable.
- [ ] Test all required communication paths before onboarding workloads.

## 5. Protection Configuration

- [ ] Configure local deduplicated recovery storage.
- [ ] Create workload discovery rules or protection groups.
- [ ] Define schedules, retention and backup windows.
- [ ] Configure immutable off-site copies.
- [ ] Establish long-term archival procedures.
- [ ] Configure monitoring, alerts and capacity thresholds.

## 6. Testing and Handover

- [ ] Run initial backup and copy workflows.
- [ ] Test file-level and full-workload recovery.
- [ ] Test application-aware recovery where required.
- [ ] Validate archival write and retrieval procedures.
- [ ] Capture recovery evidence and corrective actions.
- [ ] Complete operating procedures and troubleshooting guidance.
- [ ] Deliver knowledge transfer and obtain operational acceptance.

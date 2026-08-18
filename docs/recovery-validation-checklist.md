# Recovery Validation Checklist

Backup success alone is not proof of recoverability. Use this checklist to validate the complete recovery path.

## Preparation

- [ ] Select a representative workload and approved test point.
- [ ] Confirm the recovery objective and expected data state.
- [ ] Identify the recovery target and isolation requirements.
- [ ] Confirm authorized personnel and change approval.
- [ ] Record the test start time and selected recovery source.

## Operational Recovery Test

- [ ] Restore from the local recovery tier.
- [ ] Confirm restored workload integrity.
- [ ] Validate operating-system startup and basic services.
- [ ] Validate application access with the responsible owner.
- [ ] Record elapsed recovery time and exceptions.

## Immutable Copy Test

- [ ] Select an immutable recovery point.
- [ ] Confirm that retention and deletion controls are enforced.
- [ ] Restore to an isolated or approved target.
- [ ] Validate file, system and application consistency.
- [ ] Record recovery timing, throughput and any access issues.

## Long-Term Retention Test

- [ ] Confirm the correct archival record or media.
- [ ] Validate catalog visibility and retention metadata.
- [ ] Perform a controlled retrieval and restore.
- [ ] Confirm data readability and application usability.
- [ ] Document chain of custody where required.

## Closure

- [ ] Compare results with agreed recovery objectives.
- [ ] Document failures, warnings and performance constraints.
- [ ] Assign corrective actions with owners and dates.
- [ ] Update procedures and architecture documentation.
- [ ] Obtain technical and business acceptance.
- [ ] Schedule the next recovery test.

# Hearth and Haul project instructions

## Start here
- Read `docs/STATUS.md`, `docs/ROADMAP.md`, `docs/SOURCE-RECOVERY.md`, current issues and relevant local to-dos before substantive work. Keep this check quick and reuse the resulting context.
- Keep the current user request first; tackle related authorized to-dos when useful without duplicating another worker or expanding unrelated scope. Mark items complete only after their acceptance checks pass. Canonical rule: https://github.com/Herbertofury/Agent-Foundry/blob/main/PRODUCT_INVARIANTS.md#19-project-to-do-awareness-without-task-drift
- Keep instructions lean and load only relevant references. Chat-facing skills are not independent agents or permission grants.

## Recovery and compatibility
- Official project name: **Hearth and Haul**. The recovered Backpacks 2.0.2.4 lineage uses `sqst_bkpk`; preserve registry/save identity unless an explicit tested migration is required.
- Preserve original Scai Quest attribution and the exact recovered licensing notices. Do not add a blanket asset license.
- Reconcile exact artifact hashes and dependency versions before claiming compatibility. Historical Sophisticated/Curios audits are not fresh tests of a changed candidate.
- Dimensional homes and expanded variants remain roadmap items until implemented and verified. Do not overwrite established content with a smaller prototype.

## Repository integrity and verification
- Make additive, scoped changes based on the current tree. Never replace the full Git tree with only the files being added; retain README, docs, credits and unrelated files.
- Review the complete diff for unintended deletions before publishing. Verify the resulting remote tree and live Wiki after publication.
- Build/static checks do not establish gameplay, item persistence, ownership, inventory nesting safety, multiplayer behavior or dimensional entry/exit correctness. Record passed, failed and not-run checks separately.
- Keep the hub/internal to-dos and Wiki honest about partial work, blockers and exact next actions.

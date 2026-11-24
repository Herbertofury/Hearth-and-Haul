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

## Pinned shared engineering core

Read `.agents/foundry/AGENTS-adapter.md` for the shared mindset and independent-module requirements. The versioned snapshots are managed by Agent-Foundry; all recovery, compatibility, setup and acceptance details above remain owned by Hearth and Haul. Do not copy those local details into the shared core.

## Mandatory pre-release optimization gate

Before finalizing every release, follow the owner-mandated [Athena zero-loss pre-release optimization standard](https://github.com/Herbertofury/Athena/blob/main/guidance/PRE_RELEASE_OPTIMIZATION.md). Evaluate shrink-anything, fast-anything and rust-anything using reviewed pinned tools in isolated worktrees; run applicable passes, compare equivalent complete workloads, keep only independently verified improvements, restore rejected changes, and record per-tool evidence or explicit inapplicability/blockers. Never weaken tests, delete required content, force a Rust rewrite or regress functionality, quality, portability, compatibility, security or protected performance metrics. Data/documentation-only releases and existing native Rust paths require honest applicability decisions, not artificial ports. Existing local and pinned governance requirements remain intact.

## Mandatory CLI-first / non-interruptive execution

For every task, follow the owner-mandated [Athena CLI-first execution standard](https://github.com/Herbertofury/Athena/blob/main/guidance/CLI_FIRST_EXECUTION.md). Prefer fast official CLI/headless commands, supported APIs/SDKs/connectors and tested local automation. If a required application has no usable structured interface, discover or build a reviewed [CLI-Anything](https://github.com/HKUDS/CLI-Anything) harness over the real supported backend (or a native command surface for first-party code). Use isolated browser/renderer/test sessions for necessary UI proof. Never take over the user's active desktop, mouse, keyboard, focus or browser profile without explicit authorization for unavoidable foreground interaction. Preserve real runtime acceptance, data, permissions, feature parity and portable mode. Record reusable command coverage and unresolved gaps; no fake CLI parity or unnecessary release delay.

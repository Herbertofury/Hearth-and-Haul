# Comparable backpack mods and portable-home benchmarks

## Identity

[Hearth and Haul](README.md) builds on the recovered Backpacks foundation, existing creature variants and compatibility work. Portable homes are roadmap ambitions, not an accepted current capability. Preserve item identity, contents, ownership and original license/asset notices.

| Reference and primary source | Documented reference | Differentiation to evaluate, not claim |
|---|---|---|
| [Sophisticated Backpacks](https://github.com/P3pp3rF1y/SophisticatedBackpacks) | Placeable, configurable backpacks with functional upgrades | Reuse compatible upstream systems where appropriate; creature personality must not cost inventory correctness or upgrade interoperability. |
| [Traveler's Backpack](https://www.curseforge.com/minecraft/mc-mods/travelers-backpack) | Author-maintained backpack project and versions | Compare ordinary travel/storage interactions and discoverability before adding extra complexity. Exact target-loader support must be checked separately. |
| [Compact Machines](https://www.curseforge.com/minecraft/mc-mods/compact-machines) | Room-based portable-space design; current page describes data-driven room templates | Research bounded room identity and access as an architectural reference for future homes. Newer room systems are not evidence of Forge 1.20.1 integration. |

## Competitive acceptance backlog

- [ ] Complete item lifecycle: equip, place, open, transfer, upgrade, die, recover, save/reload and reconnect with unchanged contents and unique ownership.
- [ ] Sophisticated/Curios comparison matrix against exact pinned versions, including disabled or absent integration providers. Historical audit evidence is not a fresh regression pass.
- [ ] Test simultaneous player access, nested storage restrictions, full inventories, interrupted transfers and malformed saved state for duplication/loss.
- [ ] Portable-home research gate: safe entrance/return destination, owner permissions, logout/death inside, moved/destroyed backpack and world migration. No home implementation claim before these work.
- [ ] Creature variant value: measure useful feedback and interaction clarity without constant AI/tick overhead when stored or unloaded.

**Priority:** durable storage and compatibility before dimensional homes. Use [compatibility](docs/COMPATIBILITY.md), [testing](docs/TESTING.md) and [roadmap](docs/ROADMAP.md) for implementation status. Public source visibility does not imply permission to redistribute another project's assets.

## Evidence and maintenance contract

Reviewed 2026-11-12. This is a public-source design comparison, not a hands-on benchmark, exhaustive market ranking, feature acceptance, or permission to copy code/assets. Source pages may describe newer loaders or editions than our target. Recheck exact versions, licenses and integration boundaries before implementation. Preserve approved identity and existing progress; do not replace working systems merely because a competitor exists.

During each daily review, check linked official release notes/issues and update only material changes. Record source date, observation, relevance, proposed experiment and result separately. Retain failed comparisons and the last-good evidence. Community complaints are leads, not established product defects. New speculative features remain proposals until approved. Before claiming improvement, compare the same workload and retain latency/frame-time, memory, correctness and recovery results on the actual project build.

## Review log

- 2026-11-12: initial repository-scoped comparison index; official sources reviewed at documentation level. No gameplay, performance or compatibility tests run in this pass. No implementation or native GitHub Wiki publication claimed.

## Candidate foundations, concrete reuse and shared work

| Candidate | Exact useful layer | Improvement experiment / boundary |
|---|---|---|
| Existing recovered Backpacks foundation | Preserve existing creature variants, item identities, saved contents and integration history. | Reproduce the accepted artifact and its storage behavior before introducing another storage engine. |
| [Sophisticated Backpacks](https://github.com/P3pp3rF1y/SophisticatedBackpacks) | Supported interoperability with upgrade/inventory behavior, not wholesale source transplantation. | Test a pinned dependency plus original adapter for transfer, equipped/placed forms, upgrades, reconnect and recovery; avoid duplicating its inventory authority. |
| [Compact Machines](https://www.curseforge.com/minecraft/mc-mods/compact-machines) | Design reference for bounded room identity and data-driven room definitions. | Build a minimal portable-home design spike only after storage correctness; safe return, permission checks and destroyed/moved container recovery are acceptance gates. |

**Important license finding:** current Sophisticated Backpacks [LICENSE.md](https://github.com/P3pp3rF1y/SophisticatedBackpacks/blob/1.21.x/LICENSE.md), blob `6aa6ed9f72720c774157620e1c2102920b3e16a1`, is **All Rights Reserved**. It restricts public modifications/redistribution and ordinary forks; its limited attributed snippet exception is not permission to copy files or substantial structures. A historical target release may have different terms and must be checked independently. Prefer supported interoperability, obtain necessary permission, or write original implementations. Compact Machines and Traveler's Backpack are not cleared as code/assets donors by this review.

### Shared-work proposals

- Minecraft-Mod-Vault/Enderloom: common artifact/provenance and save-migration test receipts, without publishing private recovered packages.
- Bloom & Boom: share ownership/death/unload/reload test scenarios for creature-themed behavior; do not conflate companion AI and authoritative item storage.
- JetSetCraft: align safe dimension return/cancel/disconnect test scenarios for future portable homes. A shared scenario format is a proposal, not proven runtime compatibility.

- [ ] Pin exact target-license evidence before any upstream-derived public source import.
- [ ] Choose the least invasive integration that preserves original inventory ownership; reject designs that introduce duplicate contents or save authorities.

### Reuse admission gates

These are **candidate foundations and experiments**, not selected dependencies or measured improvements. Before reuse: pin the exact version/commit and loader; inspect its source and dependency tree; record code, asset, trademark and redistribution terms separately; keep required notices; verify permission where terms are restrictive or unclear. Public visibility is not a license. A current default-branch license is evidence for that snapshot, not every historical release. Prefer an upstream dependency/API or a small original adapter over a fork when it preserves compatibility. Do not copy proprietary game assets or publish private fixtures.

For every admitted experiment retain baseline and candidate artifacts, representative native workloads, correctness/feature parity, cold/warm latency, p95 frame/tick time, memory, interrupted-save/recovery evidence and rollback. Promote only after the actual target improves without losing requirements. Cross-project sharing below is an interface proposal, not permission to change another project's implementation or declare integration complete.

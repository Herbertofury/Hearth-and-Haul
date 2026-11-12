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

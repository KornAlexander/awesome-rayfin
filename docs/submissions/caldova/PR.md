# feat(caldova-cologne-digital-twin): add Caldova logistics and IBCS analysis template

**Proposed PR text for review in a fork, not an opened upstream PR. Do not submit source while redistribution or release checks remain open. No application source changes accompany this draft.**

## Description

Proposes a Caldova Cologne template combining a photoreal digital twin, the adapted stock/reorder experience and two IBCS-oriented finance pages: KPI Cockpit and GuV & Simulation. The finance page offers a table plus the original P&L visual's statement and tree modes.

The adaptation adds spatial and finance context to the original Caldova scenario without presenting generated delivery animation as live telemetry. The companion financial-statements app is a separate proposed template, not an additional integrated page or bundled duplicate of the original app.

## Type of change

- [x] New template, proposed
- [ ] Template update
- [ ] Gallery infrastructure
- [ ] Other

## Credits

**Base app:** Yohan Lasorsa (@sinedied), original Caldova Fabric App and operations model for Microsoft's LTG291 session. The source derives from [the Microsoft sample](https://github.com/microsoft/frontiertour27-LTG291-turn-your-data-into-production-apps-with-rayfin), retaining Microsoft Corporation's MIT license.

**Upstream session materials:** Mike Kinsman (@mikekinsman), documentation and media/delivery contributions, not original app implementation.

**Finance Cockpit and original P&L visuals:** Michael Tenner / DatenWG, including the applicable MIT notices. Public vendor redistribution clearance remains a release prerequisite.

**Cologne adaptation and integration:** Alexander Korn. Geographic inputs retain Land NRW / Geobasis NRW, Copernicus and OpenStreetMap credits and terms.

## Data and runtime boundaries

- Caldova business data, pharmacy relationships, inventory, delivery assignments and finance are fictional/generated. Geography is real and separately licensed.
- Analytical views read dated bundled snapshots. Reorder records require configured authenticated Fabric services and connectivity.
- Finance simulation/export in the integrated cockpit is not persisted financial writeback.
- Current reorder attribution/reset conventions are application-side; do not describe them as server-enforced row isolation or production authorization.
- Public-safe source, asset selection and template packaging have not yet been prepared or validated. Do not upload the developer/internal source tree as-is.

## Template checklist

- [ ] Public distribution rights cleared for all included code, media and data.
- [ ] Matching template/package/folder/manifest/Rayfin IDs finalized.
- [ ] Service flags and replacement-token list checked against actual source.
- [ ] README includes Getting started, Project structure and Scripts.
- [ ] Source and final bundles contain no credentials, live target coordinates or private relationship disclosures.
- [ ] Complete software/data notices and original author credits retained.
- [ ] Preview generated from the approved release candidate.
- [ ] Fresh install and actual template lint/build/test results recorded.
- [ ] Scaffolding with the current Rayfin CLI verified.
- [ ] Generated manifests and gallery README updated by the current generator.
- [ ] Independent release review and exact public publication approval obtained.

## Gallery checklist

- [ ] Current generator check passes.
- [ ] Gallery entry matches the cleared source and preview.

## Validation status

No gallery candidate has been built or scaffolded for this draft. Earlier local developer checks covered integrated rendering and focused logic, not clean template installation or live Fabric acceptance. Replace this paragraph with actual release-candidate commands, results, skips and remaining limitations before submitting a source PR. Do not mark the checklist from historical evidence alone.

## AI disclosure

GitHub Copilot assisted with code adaptation, provenance research, submission text and validation planning. The eventual PR must identify actual test execution and human review rather than claim they were completed manually.

## Companion PR, kept separate

Proposed title: **feat(caldova-finance-ibcs): add articulated IBCS financial statements**.

Its scope is income statement, balance sheet and cash flow with generated Caldova data, forecast interactions, comments and close workflow. Credits must retain Alexander Korn for the app, Michael Tenner / DatenWG for adapted notation/export code, Yohan Lasorsa for the original Caldova scenario/sample and Microsoft for the reused framework/template code. The standalone app does not include the twin's third-party vendor visuals, but still requires its own license, provenance, privacy and clean-template validation before publication.
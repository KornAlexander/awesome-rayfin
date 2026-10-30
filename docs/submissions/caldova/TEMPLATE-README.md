# Caldova Cologne Digital Twin

**Template README draft. Source publication and installation are not yet available through this submission. Public redistribution and release validation remain open.**

A fictional pharmaceutical distribution story combining the real geography of Cologne, the original Caldova stock/reorder experience and IBCS-oriented financial analysis.

## What it demonstrates

| View | Purpose | Important distinction |
| --- | --- | --- |
| Twin | Real terrain, imagery, buildings and streets with generated logistics activity. | The business use, interiors, partner relationships and vehicle movements are fictional; vehicles are not live telemetry. |
| Reorder | Adapted Caldova low-stock analysis and operational reorder interaction. | Analytical figures use a dated snapshot; writes require configured authenticated Fabric services. |
| Finance: KPI Cockpit | Revenue, margin, volume and logistics views across the synthetic distribution scenario. | Snapshot-backed analysis, not a live browser semantic-model query. |
| Finance: GuV & Simulation | P&L analysis and simulation, with a table plus the original visual's statement and tree modes. | Simulation/export is not persisted financial writeback; original vendor visuals require public distribution clearance. |

The independent Caldova Finance application, showing income statement, balance sheet and cash flow, is proposed separately and is not an extra page in this template.

## Getting started

There is no approved gallery installation command yet. The future public template must scaffold and run without the developer's environment files, private targets, dependency folders or tenant coordinates.

The intended local path is an offline/read-only preview with licensed packaged geography and generated analytical snapshots. Authenticated reorder operations require a separately configured Fabric app and data services. Offline preview does not provision infrastructure, establish model bindings, grant access or verify live authorization.

Release-specific install, preview and deployment instructions will be added only after the actual public candidate passes clean-install and scaffold checks. Deployment requires separate authorization for the exact target.

## Project structure

The proposed source layout retains the existing integration boundaries:

| Area | Role |
| --- | --- |
| Application shell and shared components | Switch between the twin, reorder and finance views. |
| Twin/geo modules | Uniform real-world scene scale, geometry, camera and synthetic operations. |
| Adapted reorder modules | Original Caldova analytical screens, with the variant's separate operational data path. |
| Finance modules | Michael Tenner / DatenWG's adapted cockpit and original P&L visual integration. |
| Public assets | Approved geography, original data notices and genuinely generated demo snapshots. |
| Rayfin configuration/data | Explicit target configuration and application entity schema. |
| Optional model/tooling | Portable setup/regeneration only where complete inputs and reviewed configuration are supplied. |

This is a layout proposal, not confirmation that a gallery source tree has been created.

## Scripts

Script names and hooks remain to be finalized against the actual public candidate.

| Intended operation | Release requirement |
| --- | --- |
| Install and preview | Fresh dependency resolution; no authentication or deployment as an implicit offline-preview prerequisite. |
| Build and type-check | Compile a public-safe bundle without developer target defaults; review prebuild hooks. |
| Focused tests | Relevant geography, tab integration, snapshot, financial calculation and identity-boundary checks. |
| Lint | Current gallery-compatible lint configuration. |
| Optional data preparation | Document source licenses, complete inputs, download size and explicit target requirements. No automatic ingestion/deployment. |

## Credits

The original **Caldova base Fabric App and operations semantic model** were authored by **[Yohan Lasorsa (@sinedied)](https://github.com/sinedied)** for Microsoft's LTG291 session, **Turn your data into production apps with Rayfin**. See the [original Microsoft sample](https://github.com/microsoft/frontiertour27-LTG291-turn-your-data-into-production-apps-with-rayfin). Preserve its Microsoft Corporation MIT license.

**[Mike Kinsman (@mikekinsman)](https://github.com/mikekinsman)** contributed to the upstream session documentation and media/delivery materials.

**Alexander Korn** implemented the Cologne-specific digital-twin adaptation, generated scenario and integration.

**Michael Tenner / DatenWG** created the Finance Cockpit and original P&L visuals adapted into Finance. Preserve the source-specific Michael Tenner and Microsoft notices; the draft does not clear public vendor redistribution.

**Land NRW / Geobasis NRW**, **Copernicus DEM** and **OpenStreetMap contributors** provide geographic data under their respective terms. Software licenses do not relicense those datasets.

IBCS® is a registered trademark of the IBCS Institute. The finance views follow IBCS-oriented notation and are not certified. Neither original-source credit nor Microsoft branding implies endorsement of the modified template.

## Limitations

- Not a production purchasing, dispatch, accounting or warehouse-control system.
- Generated partner relationships and business data must not be presented as statements about real pharmacies, venues or their owners.
- No assertion of live telemetry, live financial-model reads or production row-level authorization.
- Public vendor-code distribution, portable setup, asset size, clean installation, previews and current gallery CI/scaffolding are unresolved release gates.
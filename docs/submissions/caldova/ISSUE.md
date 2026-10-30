# Proposal: Caldova Cologne Digital Twin and companion IBCS Financial Statements

**Proposal draft for review in a fork, not an opened upstream issue. The full source contribution is on hold pending public redistribution clearance and template validation.**

## What this would add

A fictional pharmaceutical distribution story that links spatial context, stock decisions and financial analysis:

1. **Caldova Cologne Digital Twin:** real Cologne terrain/buildings with synthetic logistics, the adapted Caldova Reorder experience, and a Finance tab with KPI Cockpit and GuV & Simulation. The finance page includes a table plus the original P&L visual's statement and tree modes.
2. **Caldova Finance:** a separately reusable income statement, balance sheet and cash flow template with articulated synthetic data and an offline controller demo.

The first is proposed as one integrated digital-twin template; the second as a focused financial-analytics template. The existing original Caldova app would be linked and credited, not submitted again as an unchanged duplicate.

## Who it is for

Fabric and Rayfin builders exploring how a governed analytical model, an operational workflow, a spatial view and finance-oriented interaction can tell one coherent demo story. This is a demonstration, not production purchasing, warehouse control or a certified accounting system.

## Meaningful extension beyond the original sample

- A measured Cologne city setting, with a clearly fictional logistics-centre use and generated delivery scenario.
- Integrated stock/reorder screens, KPI analysis and P&L simulation in the same shell.
- A companion template showing linked financial statements and forecast interactions rather than a static report alone.
- A deliberate distinction between bundled analytical snapshots, synthetic animation and authenticated operational data.

## Rayfin capabilities

The integrated app uses Fabric authentication, static hosting and Rayfin data for operational reorder records. Its analytical views use bundled snapshots rather than a browser semantic-model connector. Finance writeback is not provided by the integrated cockpit.

The standalone finance app separately implements forecast/comment/close records with Rayfin data and an offline browser-store demo. Live policy enforcement must be validated independently; offline behavior is not server-authorization evidence.

## Original authors and adaptation credits

- **Yohan Lasorsa (@sinedied):** original Caldova base Fabric App, operations semantic model and Microsoft LTG291 session. [Original Microsoft source](https://github.com/microsoft/frontiertour27-LTG291-turn-your-data-into-production-apps-with-rayfin), Microsoft Corporation MIT license.
- **Mike Kinsman (@mikekinsman):** upstream session documentation and delivery/media contributions.
- **Michael Tenner / DatenWG:** the integrated IBCS Finance Cockpit and original P&L visuals; the standalone app also adapts his notation helpers and export structure under its MIT notice.
- **Alexander Korn:** Cologne digital-twin adaptation/integration and standalone financial-statements application.
- Geographic data: Land NRW / Geobasis NRW, Copernicus DEM and OpenStreetMap contributors, under their respective terms.

## Current status and prerequisites

This is a proposal, not a ready-to-merge source submission. Public redistribution of the integrated vendor visuals must be cleared or a distributable alternative agreed before the full template is published. A smaller/optional licensed terrain package, portable target configuration, clean installation, preview images and gallery scaffold/CI verification are also required.

Previous local checks used existing developer dependencies. They do not establish that a clean public template currently installs, scaffolds or deploys successfully. No live Fabric or production-security validation is claimed here.

## Proposed next step

Confirm that the two-template scope is useful and not duplicative of existing analytics templates. After redistribution and release checks are complete, submit focused template PRs with source-specific licenses, complete setup guidance, previews and reproducible validation evidence.

## AI assistance

GitHub Copilot assisted with code adaptation, source investigation, submission drafting and validation planning. Release checks, limitations and human review status will be reported explicitly with the eventual contribution; this draft does not claim manual testing that has not occurred.
# Caldova submission review

**Documentation-only review branch, prepared October 30, 2026. No Caldova application source or installable template is included. No upstream submission has been opened by publishing these documents.**

## Review the drafts

- [Proposal issue text](ISSUE.md): the integrated Cologne digital twin and a companion financial-statements template.
- [Proposed pull request text](PR.md): scope, credits, unchecked release gates and AI disclosure.
- [Template README draft](TEMPLATE-README.md): intended experience, architecture, limitations and setup boundaries.
- [Attribution](ATTRIBUTION.md): the original Caldova authors and subsequent contributions.
- [Metadata proposals](metadata-proposals.json): two draft entries, not generated gallery manifests.

## Scope and credit

The proposed integrated template has Twin, Reorder and Finance tabs. Finance contains KPI Cockpit and GuV & Simulation, with a table and the original P&L visual's statement/tree modes. The separate financial-statements application has income statement, balance sheet and cash flow views; it is not an extra integrated tab.

The original Caldova base Fabric App and operations model were authored by **Yohan Lasorsa (@sinedied)** for Microsoft's LTG291 sample. **Mike Kinsman (@mikekinsman)** contributed session documentation and media. **Michael Tenner / DatenWG** supplied the cockpit/visuals and the separately adapted notation/export code. **Alexander Korn** implemented the Cologne adaptation/integration and standalone financial-statements app. See [the full attribution](ATTRIBUTION.md) for role boundaries and license reminders.

## Why source is not included

Vendor redistribution clearance is still required for the integrated cockpit's visual code. The current spatial payload also needs a smaller or optional packaging strategy, and public-safe configuration, clean installation, actual previews and gallery scaffolding remain unverified. These documents do not clear those gates.

Publishing this review branch does not publish an application, certify production security, install a gallery template or update a running Fabric app. No source release, upstream PR, issue, merge or deployment is implied. The draft feature descriptions refer to the proposed applications, not executable contents of this branch.

## Review checks

Only Markdown and JSON documents are added. Validation is limited to relative links, JSON structure and identifiers, contributor names, public-disclosure shapes and the exact changed-file scope. No application tests, builds, gallery generation or scaffold checks are claimed for this documentation branch.
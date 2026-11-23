# aca rpf plugin

Review incoming confidentiality agreements against the seven-point GeoPost GATE worksheet. This plugin copies the NDA analysis skill from [Geopost RFPs Manager](../geopost-rfps-manager).

## Use

Provide the NDA and ask: “Use NDA analysis to review this agreement.” The review delivers a go/no-go recommendation, clause-specific risks, and proposed edits. It distinguishes strategic requirements, legal issues, and project-owner commercial decisions.

## Files

- [Plugin manifest](.codex-plugin/plugin.json)
- [NDA analysis instructions](skills/nda-analysis/SKILL.md)
- [Skill display and invocation settings](skills/nda-analysis/agents/openai.yaml)
- [GATE worksheet rules and source](skills/nda-analysis/references/gate-rules.md)

The bundled rules reflect the source worksheet retrieved on 6 November 2026.

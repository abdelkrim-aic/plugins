# Geopost RFPs Manager

Version 1.0.0. This plugin contains NDA analysis for reviewing incoming confidentiality agreements against the seven-point GeoPost GATE worksheet.

## Use

Provide the NDA and ask: “Use NDA analysis to review this agreement.” The review delivers a go/no-go recommendation, clause-specific risks, and proposed edits. It distinguishes strategic requirements, legal issues, and project-owner commercial decisions.

## Files

- [Plugin manifest](.codex-plugin/plugin.json)
- [NDA analysis instructions](skills/nda-analysis/SKILL.md)
- [Skill display and invocation settings](skills/nda-analysis/agents/openai.yaml)
- [GATE worksheet rules and source](skills/nda-analysis/references/gate-rules.md)

The four source files are preserved in their original formats and directory structure. The rules capture the worksheet retrieved on 6 November 2026; they are not synchronized automatically. This README is an archive index. The archive does not itself install the plugin.

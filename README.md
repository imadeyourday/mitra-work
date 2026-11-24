# Mitra Work — Greenfield

**Current package: 1.0.0 · 24 November 2026**

A self-contained operating reference for useful work, careful judgment and dependable continuation. Start with fresh work context and use the procedures with the tools and permissions available in your environment.

## Start here

**[Read the complete greenfield reference](GREENFIELD.md)**

| Item | Purpose |
| --- | --- |
| [GREENFIELD.md](GREENFIELD.md) | Complete operating reference, examples and templates |
| [PROJECT-INSTRUCTIONS.txt](PROJECT-INSTRUCTIONS.txt) | Short instructions to paste into a Project's instructions field |
| [FIRST-SESSION.txt](FIRST-SESSION.txt) | Ready-to-use opening prompt |
| [Complete 1.0.0 kit](releases/1.0.0/Mitra-Work-v1.0.0.zip) | Reference, setup, four native Skill ZIPs, templates, exercises and manifest |
| [Version 1.0.0 files](releases/1.0.0/) | Browse the exact matching release components |
| [LATEST.json](LATEST.json) | Current version, paths and artifact hashes |

### Bring it directly into a Claude Project

1. Create or open a Project in your work Claude account.
2. In Project knowledge, choose **+ → GitHub**, paste this repository URL, and select **GREENFIELD.md**:
   `https://github.com/imadeyourday/mitra-work`
3. Open [PROJECT-INSTRUCTIONS.txt](PROJECT-INSTRUCTIONS.txt), copy its contents into **Set project instructions**, and save.
4. Start a conversation using [FIRST-SESSION.txt](FIRST-SESSION.txt).

The GitHub route requires the GitHub integration to be available in that account. Selected repository files become Project knowledge; they do not fill the Project instructions field for you. Use the integration's **Sync / Sync now** control when deliberately adopting an update. Do not assume an automatic refresh.

A work assistant with public web access can also read the [plain-text reference](https://raw.githubusercontent.com/imadeyourday/mitra-work/main/GREENFIELD.md) and [plain-text instructions](https://raw.githubusercontent.com/imadeyourday/mitra-work/main/PROJECT-INSTRUCTIONS.txt). Reading a link in one chat is not proof that another chat will recover it. Add the reference to Project knowledge and save the instructions for the Project setup.

### Add the native Skills

The same methods are available as four separate upload files:

- [Continue and execute](releases/1.0.0/skill-zips/mitra-continue-execute-1.0.0.zip)
- [Research and judge](releases/1.0.0/skill-zips/mitra-research-judge-1.0.0.zip)
- [Review and improve](releases/1.0.0/skill-zips/mitra-review-improve-1.0.0.zip)
- [Organize and handoff](releases/1.0.0/skill-zips/mitra-organize-handoff-1.0.0.zip)

Download the individual ZIPs from GitHub and upload each through **Customize → Skills → + → Create skill → Upload a skill**. Native Skills require Claude's code-execution capability even though this release contains only text. The complete outer kit is not a single Skill upload.

## What the methods cover

| Module | Procedure |
| --- | --- |
| Continue and execute | Recover current authority and state, complete the next useful authorized step, inspect the result |
| Research and judge | Trace original evidence and source dependence, assess uncertainty, choose a decision-relevant check |
| Review and improve | Diagnose a failure, repair the appropriate mechanism, assess later observed behavior |
| Organize and handoff | Preserve evidence, keep records usable, save an exact continuation and check recovery |

See the [fictional exercises](releases/1.0.0/ACCEPTANCE-EXERCISES.md) to try the procedures. Use existing work trackers when suitable; the included templates are optional starting records.

## Versions and maintenance

The root reference and instructions identify the current release. Matching versions are preserved under `releases/<version>/`. Record the version and Git commit used for adoption. Keep a work-local copy of the baseline and retain the previous one for rollback.

Updates are deliberate imports. Review the new version, reconcile local adaptations within work, and update the reference, Project instructions and installed Skills together. [Maintenance guidance](releases/1.0.0/MAINTENANCE.md) covers the full process.

The [release manifest](releases/1.0.0/MANIFEST.json) records the bytes of the unpacked kit; [LATEST.json](LATEST.json) also identifies the complete ZIP's hash. A checksum helps identify changed bytes; it does not prove model behavior or runtime isolation.

## Work stays in work

Workplace prompts, sources, code, outputs, logs, usage, evaluations and local adaptations remain in employer-approved systems. Do not submit them through this repository's issues, discussions, pull requests or other maintainer channels, including after anonymization.

This distribution contains general procedures and fictional examples. It has no executable code, personal-source access, callback, telemetry or automatic updater. The receiving environment supplies its own storage and approved tools.

## Product documentation

- [Add GitHub files to Claude](https://support.claude.com/en/articles/10167454-use-the-github-integration)
- [Create and manage Claude Projects](https://support.claude.com/en/articles/9519177-how-can-i-create-and-manage-projects)
- [Use Skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)

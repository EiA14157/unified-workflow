# Unified Workflow

One Agent Skill for multi-stage work: establish what success looks like, load the relevant playbook, and verify the deliverable. Routine tasks do not need a separate planning round.

| Route | Use it for |
| --- | --- |
| [Engineering](references/engineering.md) | Implementation, diagnosis, and regression checks |
| [Artifacts](references/artifacts.md) | Documents, notebooks, and interfaces |
| [Evidence](references/evidence.md) | Data, experiments, and token-cost comparisons |
| [Release](references/release.md) | Publishing and deployment |

## Use

Review [SKILL.md](SKILL.md), then import or place this repository's skill directory (including `references/`) where your Agent Skills-compatible client discovers skills. The folder should be named `unified-workflow`. For client-specific setup, see [Build skills](https://learn.chatgpt.com/docs/build-skills) or the [Agent Skills specification](https://agentskills.io/specification). In Codex, try: “Use `$unified-workflow` to plan the smallest fix and verify it.”

No bundled executables or dependencies. Platform authorization and existing project checks still apply.

## How it was assembled

The [comparison notes](references/source-comparison.md) cover what was retained or omitted from 12 public skill instruction files. This repository uses original wording rather than bundling upstream skill files or code. The on-demand layout is intended to avoid irrelevant instructions; no runtime token savings have been measured.

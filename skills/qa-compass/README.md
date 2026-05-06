# QA Compass

QA Compass is a Codex skill for turning requirements, Jira issues, Confluence pages, markdown specs, test cases, or execution results into reusable QA artifacts and reports.

It is not a rigid application. It is a flexible QA workflow assistant: it keeps the important parts of our QA flow structured, but lets the user adjust scope, grouping, test cases, execution details, and reporting as needed.

## Install

In Codex, ask:

```text
Install this skill:
https://github.com/Kepler-Team/ai-promts-rules-configs/tree/main/skills/qa-compass
```

After installation, restart Codex so it can load the updated skill.

If an older local version already exists, remove it first from:

```text
~/.codex/skills/qa-compass
```

## What It Does

- Ingests requirements from Confluence, Jira, markdown, JSON, or pasted text.
- Generates project summaries, roles, grouping proposals, and test cases.
- Builds a pre-execution QA Scope Preview and waits for user confirmation.
- Supports repeated runs: smoke, full regression, rerun failed/blocked, and custom subsets.
- Separates reusable project artifacts from per-run execution artifacts.
- Creates internal reports for the team and external HTML/PDF reports for clients.
- Drafts Jira-ready bugs from confirmed defects.
- Generates QA Compass Run Diagnostics when a run fails or feedback is needed.

## Main Skill File

Codex loads the skill from:

```text
SKILL.md
```

The supporting workflow docs, scripts, templates, and tests live in the sibling folders inside this directory.

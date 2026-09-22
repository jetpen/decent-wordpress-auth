## Agent skills

### Issue tracker

Issues and specs for this repository live in GitHub Issues via the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Use the default triage labels: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, and `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

This repository uses a single-context layout. See `docs/agents/domain.md`.

### Structural code search

You are operating in an environment where `ast-grep` is installed.
For any code search that requires understanding of syntax or code structure, you should default to using `ast-grep --lang [language] -p '`

# Legacy Config Retire Drill - Disposable Sandbox

This repository is a throwaway for rehearsing the legacy-config retirement runbook.
Nothing here is production. Create the marker files, run the drill, verify the PR,
and delete this repo when you are done.

## Layout

- `config/legacy-settings.yaml` - marked legacy
- `config/legacy-features.yaml` - marked legacy
- `src/app.py` - ordinary source (must survive the cleanup branch)
- Search for `# DEPRECATED-RUNBOOK-MARKER-7QF3` to locate the marked files

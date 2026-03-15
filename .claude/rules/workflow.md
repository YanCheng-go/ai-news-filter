# Workflow

- Commit directly to feature branches. PR to main when ready.
- Self-review changes before merging (use /commit to review diffs).
- Keep commits small and atomic — one logical change per commit.
- Run `uv run pytest` before committing. Do not commit code that breaks existing tests.
- Write meaningful commit messages in imperative mood ("Add ...", "Fix ...").
- Tag releases with semver (e.g., `v1.2.0`).

## Issues

- Use GitHub issue templates (`bug.yml`, `feature.yml`, `source.yml`) when creating issues.
- Set priority label on every issue: `priority:high`, `priority:medium`, or `priority:low`.
- Set size label when scope is clear: `size:small` (< 1 hr), `size:medium` (1–4 hrs), `size:large` (> 4 hrs).
- Add `status:in-progress` label when starting work on an issue.
- Close duplicates with the `duplicate` label and a comment linking the canonical issue.
- Close completed issues with reason `completed`; stale/invalid issues with `not planned`.

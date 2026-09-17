# Git workflow

- Inspect status, current branch, and existing worktrees before changing files. Preserve unrelated user work and other tasks' changes.
- Give concurrent tasks distinct branches; never reuse a branch checked out by another worktree. Use `codex/<task-name>` for new task branches unless the user specifies another name.
- Keep commits focused on the completed task. Review and stage explicit paths; use a descriptive imperative message explaining the change, such as `docs: add progressive agent guidance`.
- Before an authorized push, fetch and inspect the target branch. Resolve overlapping changes deliberately and rerun affected checks; do not overwrite others' work or force-push to bypass divergence.
- Worktrees isolate working files, but cannot guarantee conflict-free integration. Surface unresolved conflicts instead of claiming completion.
- Report any commit hash and pushed branch accurately; distinguish local completion from successful publication.

Whether every new coding task must create a worktree and automatically commit/push is awaiting the user's choice in [the review](../agent-guidance-review.md). These rules do not resolve that pending authorization.

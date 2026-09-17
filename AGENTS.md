# Agent instructions

Cryptita Plays Builder Workshop pairs a Sui Move `BuilderCard` package with a read-only React/TypeScript/Vite profile site; on-chain writes happen through the Sui CLI.

Preserve this scope unless the task explicitly changes it. As documented in [README.md](README.md), current code and the README supersede outdated implementation details in `spec/`.

Read only the guidance relevant to the task:

- Any code change: [AI-assisted development](docs/agents/development.md).
- Frontend, styling, or image export: [Frontend](docs/agents/frontend.md).
- Move, configuration, or deployment: [Contracts and operations](docs/agents/contracts-and-operations.md).
- Validation and completion: [Verification](docs/agents/verification.md).
- Branches, commits, or concurrent tasks: [Git workflow](docs/agents/git-workflow.md).

Validation commands run in subdirectories: frontend lint/build in `web/` (build includes TypeScript checking), and `sui move build` / `sui move test` in `move/`. See verification guidance for exact commands and limitations.

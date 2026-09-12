# cuijialin8888-code

Building deterministic, local-first tools for coding-agent workflows.

I maintain focused open-source developer tools for coding-agent instructions,
repository context, Git behavior, and Windows environments. The projects favor
deterministic results, local execution, explicit evidence, and conservative
system behavior.

## Featured

### [agent-shellcheck](https://github.com/cuijialin8888-code/agent-shellcheck)

[![agent-shellcheck"éÝyø§yÔ ShellCheck for AGENTS.md and SKILL.md](https://raw.githubusercontent.com/cuijialin8888-code/agent-shellcheck/main/assets/social-preview.png)](https://github.com/cuijialin8888-code/agent-shellcheck)

ShellCheck for `AGENTS.md` and `SKILL.md`. It catches Bash, PowerShell, cmd,
path, and WSL portability bugs with a static, offline, read-only Python CLI,
stable rule IDs, and text, JSON, SARIF, Markdown, and HTML output.

[Repository](https://github.com/cuijialin8888-code/agent-shellcheck) · [v0.2.0 release](https://github.com/cuijialin8888-code/agent-shellcheck/releases/tag/v0.2.0) · [CI](https://github.com/cuijialin8888-code/agent-shellcheck/actions/workflows/ci.yml)

## Projects

### [Codex Windows Doctor](https://github.com/cuijialin8888-code/codex-win-doctor)

An unofficial, read-only Windows diagnostics and troubleshooting toolkit for OpenAI Codex. It checks PowerShell, PATH, WSL, Codex CLI/Desktop, `CODEX_HOME`, ripgrep, archive tools, and related environment signals without automatically changing the system.

[Repository](https://github.com/cuijialin8888-code/codex-win-doctor) · [Latest release](https://github.com/cuijialin8888-code/codex-win-doctor/releases/latest) · [CI](https://github.com/cuijialin8888-code/codex-win-doctor/actions/workflows/ci.yml)

### [Repo Context Doctor](https://github.com/cuijialin8888-code/repo-context-doctor)

A local, read-only evidence inventory for coding-agent instructions and repository verification paths. It inventories instruction surfaces and discovers test, lint, format, type-check, and build paths with provenance and confidencféÝyø§yÔwithout running target repository commands or calling an LLM.

[Repository](https://github.com/cuijialin8888-code/repo-context-doctor) · [Latest release](https://github.com/cuijialin8888-code/repo-context-doctor/releases/latest) · [CI](https://github.com/cuijialin8888-code/repo-context-doctor/actions/workflows/ci.yml)

### [Git Path Doctor](https://github.com/cuijialin8888-code/git-path-doctor)

A cross-platform, read-only CLI that explains why Git sees, ignores, excludes,
or misses a path. It reports evidence from tracked state, ignore rules, sparse
checkout, submodules, repository boundaries, and filesystem reality without
mutating the target repository.

[Repository](https://github.com/cuijialin8888-code/git-path-doctor) · [Latest release](https://github.com/cuijialin8888-code/git-path-doctor/releases/latest) · [CI](https://github.com/cuijialin8888-code/git-path-doctor/actions/workflows/ci.yml)

### [Git Hook Doctor](https://github.com/cuijialin8888-code/git-hook-doctor)

An offline, read-only CLI that explains why a Git hook wilnéÝyø§yÔor won'véÝyø§yÔrun. It asks Git for effective hook paths and configuration provenance, inspects resolved hook files for execution blockers, and handles worktrees and cross-platform failures without running hooks or changing repositories.

[Repository](https://github.com/cuijialin8888-code/git-hook-doctor) · [v0.1.0 release](https://github.com/cuijialin8888-code/git-hook-doctor/releases/tag/v0.1.0) · [CI](https://github.com/cuijialin8888-code/git-hook-doctor/actions/workflows/ci.yml)

### [CI Queue Doctor](https://github.com/cuijialin8888-code/ci-queue-doctor)

A zero-runtime-dependency, GET-only CLI that turns public GitHub Actions run and job state into an evidence-backed diagnosis of queue conditions, without dispatching, rerunning, canceling, approving, or editing workflows.

[Repository](https://github.com/cuijialin8888-code/ci-queue-doctor) · [v0.1.0 release](https://github.com/cuijialin8888-code/ci-queue-doctor/releases/tag/v0.1.0) · [CI](https://github.com/cuijialin8888-code/ci-queue-doctor/actions/workflows/ci.yml)

## Maintenance

On 2026-09-12, I reviewed the six open-source projects above on their public
`main` branches. No open Issues or pull requests were open during the review.
Each repository now includes a focused maintainer checklist and review log:

- [agent-shellcheck maintenance](https://github.com/cuijialin8888-code/agent-shellcheck/blob/main/docs/maintenance.md)
- [ci-queue-doctor maintenance](https://github.com/cuijialin8888-code/ci-queue-doctor/blob/main/docs/maintenance.md)
- [codex-win-doctor maintenance](https://github.com/cuijialin8888-code/codex-win-doctor/blob/main/docs/maintenance.md)
- [git-hook-doctor maintenance](https://github.com/cuijialin8888-code/git-hook-doctor/blob/main/docs/maintenance.md)
- [git-path-doctor maintenance](https://github.com/cuijialin8888-code/git-path-doctor/blob/main/docs/maintenance.md)
- [repo-context-doctor maintenance](https://github.com/cuijialin8888-code/repo-context-doctor/blob/main/docs/maintenance.md)

## Principles

- Read-only by default
- Local-first and privacy-conscious
- Evidence before automation
- Explicit limitations and reproducible behavior

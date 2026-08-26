# cuijialin8888-code

Building deterministic, local-first tools for coding-agent workflows.

I maintain focused open-source developer tools for coding-agent instructions,
repository context, Git behavior, and Windows environments. The projects favor
deterministic results, local execution, explicit evidence, and conservative
system behavior.

## Featured

### [agent-shellcheck](https://github.com/cuijialin8888-code/agent-shellcheck)

[![agent-shellcheck — ShellCheck for AGENTS.md and SKILL.md](https://raw.githubusercontent.com/cuijialin8888-code/agent-shellcheck/main/assets/social-preview.png)](https://github.com/cuijialin8888-code/agent-shellcheck)

ShellCheck for `AGENTS.md` and `SKILL.md`. It catches Bash, PowerShell, cmd,
path, and WSL portability bugs with a static, offline, read-only Python CLI,
stable rule IDs, and text, JSON, SARIF, Markdown, and HTML output.

[Repository](https://github.com/cuijialin8888-code/agent-shellcheck) · [v0.1.0 release](https://github.com/cuijialin8888-code/agent-shellcheck/releases/tag/v0.1.0) · [CI](https://github.com/cuijialin8888-code/agent-shellcheck/actions/workflows/ci.yml)

## Projects

### [Codex Windows Doctor](https://github.com/cuijialin8888-code/codex-win-doctor)

An unofficial, read-only Windows diagnostics and troubleshooting toolkit for OpenAI Codex. It checks PowerShell, PATH, WSL, Codex CLI/Desktop, `CODEX_HOME`, ripgrep, archive tools, and related environment signals without automatically changing the system.

[Repository](https://github.com/cuijialin8888-code/codex-win-doctor) · [Latest release](https://github.com/cuijialin8888-code/codex-win-doctor/releases/latest) · [CI](https://github.com/cuijialin8888-code/codex-win-doctor/actions/workflows/ci.yml)

### [Repo Context Doctor](https://github.com/cuijialin8888-code/repo-context-doctor)

A local, read-only evidence inventory for coding-agent instructions and repository verification paths. It inventories instruction surfaces and discovers test, lint, format, type-check, and build paths with provenance and confidence—without running target repository commands or calling an LLM.

[Repository](https://github.com/cuijialin8888-code/repo-context-doctor) · [Latest release](https://github.com/cuijialin8888-code/repo-context-doctor/releases/latest) · [CI](https://github.com/cuijialin8888-code/repo-context-doctor/actions/workflows/ci.yml)

### [Git Path Doctor](https://github.com/cuijialin8888-code/git-path-doctor)

A cross-platform, read-only CLI that explains why Git sees, ignores, excludes,
or misses a path. It reports evidence from tracked state, ignore rules, sparse
checkout, submodules, repository boundaries, and filesystem reality without
mutating the target repository.

[Repository](https://github.com/cuijialin8888-code/git-path-doctor) · [Latest release](https://github.com/cuijialin8888-code/git-path-doctor/releases/latest) · [CI](https://github.com/cuijialin8888-code/git-path-doctor/actions/workflows/ci.yml)

## Principles

- Read-only by default
- Local-first and privacy-conscious
- Evidence before automation
- Explicit limitations and reproducible behavior

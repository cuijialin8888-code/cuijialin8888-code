# cuijialin8888-code

Building safe, read-only diagnostics for coding-agent workflows.

I maintain small open-source developer tools that make coding-agent environments and repository context easier to inspect and debug. They are intentionally narrow in scope. The projects favor deterministic diagnostics, local execution, explicit evidence, and conservative system behavior.

## Projects

### [Codex Windows Doctor](https://github.com/cuijialin8888-code/codex-win-doctor)

An unofficial, read-only Windows diagnostics and troubleshooting toolkit for OpenAI Codex. It checks PowerShell, PATH, WSL, Codex CLI/Desktop, `CODEX_HOME`, ripgrep, archive tools, and related environment signals without automatically changing the system.

[Repository](https://github.com/cuijialin8888-code/codex-win-doctor) · [Latest release](https://github.com/cuijialin8888-code/codex-win-doctor/releases/latest)

### [Repo Context Doctor](https://github.com/cuijialin8888-code/repo-context-doctor)

A local, read-only evidence inventory for coding-agent instructions and repository verification paths. It inventories instruction surfaces and discovers test, lint, format, type-check, and build paths with provenance and confidence—without running target repository commands or calling an LLM.

[Repository](https://github.com/cuijialin8888-code/repo-context-doctor) · [Latest release](https://github.com/cuijialin8888-code/repo-context-doctor/releases/latest)

## Principles

- Read-only by default
- Local-first and privacy-conscious
- Evidence before automation
- Explicit limitations and reproducible behavior

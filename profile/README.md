# dtvem

**Developer Tools Virtual Environment Manager** — a cross-platform runtime version manager that actually works on Windows.

Manage Python, Node.js, Ruby, and more with a single tool. No shell hacks. No surprises.

## Quick Install

**Windows (PowerShell)**
```powershell
irm dtvem.io/install.ps1 | iex
```

**macOS / Linux**
```bash
curl -fsSL dtvem.io/install.sh | bash
```

## Why dtvem?

- **Windows first-class** — Built from the ground up to work seamlessly on Windows
- **Shim-based architecture** — No shell integration required, no `.bashrc` or `.zshrc` modifications
- **Project-local versions** — Automatic version switching per directory
- **Multiple runtimes** — Python, Node.js, Ruby, and more coming soon

## Get Started

- [Documentation](https://dtvem.io/docs/user-guide/getting-started) — Installation guide and tutorials
- [Commands Reference](https://dtvem.io/docs/user-guide/commands/overview) — Full command documentation
- [Migration Guide](https://dtvem.io/docs/user-guide/migration) — Migrate from pyenv, nvm, asdf, and others

## Repositories

| Repo | Description |
|------|-------------|
| [dtvem](https://github.com/dtvem/dtvem) | The CLI tool (written in Go) |
| [dtvem.io](https://github.com/dtvem/dtvem.io) | Website and documentation |

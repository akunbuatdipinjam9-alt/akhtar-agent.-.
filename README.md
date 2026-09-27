# Akhtar Agent

Desktop AI Agent framework built with Electron, focused on controlled tools, security, recovery, and extensibility.

## Status

Akhtar Agent is under active development. The project focuses on a secure agent architecture where LLM output does not receive unrestricted operating-system access. Native capabilities are exposed through controlled tools, permission checks, guard policies, execution boundaries, and verification.

## Core principles

- Controlled tool execution
- Least privilege
- Explicit permissions for sensitive actions
- Strong guardrails around terminal, filesystem, browser, plugins, and system control
- Recoverability through checkpoints, undo, and crash recovery
- Extensible architecture for providers, tools, skills, plugins, and MCP
- Reliability and verification over blind automation

## Tech

- Electron
- Node.js
- HTML/CSS/JavaScript
- SQLite
- Multi-provider LLM routing
- Tool / function calling

## License

This repository is licensed under the GNU General Public License v3.0. See `LICENSE` for details.

## Disclaimer

This project is experimental software. Review permissions, tool execution, and security-sensitive changes before using it with important data or production systems.

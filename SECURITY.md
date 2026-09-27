# Security Policy

Akhtar Agent is security-sensitive software because it can interact with local files, terminals, browsers, plugins, and operating-system features.

## Reporting a vulnerability

Please do not publish exploitable security details in a public issue before a fix is available.

Report security problems privately to the repository owner when possible, and include:

- affected component
- impact
- reproduction steps
- relevant logs or screenshots with secrets removed
- suggested mitigation, if known

## Security model

Akhtar Agent follows these principles:

- LLMs do not receive unrestricted OS access
- native actions go through controlled tools
- sensitive actions require permission
- Guard policies can block dangerous operations
- plugins should run with restricted capabilities
- secrets should not be exposed to renderers, logs, model context, or plugins unless explicitly scoped
- verification should follow important side effects

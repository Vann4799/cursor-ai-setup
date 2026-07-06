# Cursor AI Development Environment Setup

This repository documents the setup process completed for the 100Hires portfolio challenge.

**Repository:** https://github.com/Vann4799/cursor-ai-setup

---

## Tools Installed

- [Cursor IDE](https://cursor.com/)
- Claude Code extension
- Codex extension
- Git
- GitHub

---

## Setup Summary

### Cursor IDE

Cursor IDE was installed and used as the main development environment for this setup.

The repository was opened in Cursor, and the README documentation was created and updated from inside the editor.

### Claude Code

Claude Code was installed successfully from the official Anthropic extension.

Initial authentication using the default Anthropic API completed successfully. However, requests could not be executed because the Anthropic Console account had no available API credits.

To complete the setup, Claude Code was configured to use a locally hosted Anthropic-compatible gateway instead of the default Anthropic endpoint.

The following setup work was completed:

- Created the Claude Code user configuration file at `C:\Users\MSI\.claude\settings.json`.
- Added the required environment variable names for the local gateway configuration:
  - `ANTHROPIC_BASE_URL`
  - `ANTHROPIC_AUTH_TOKEN`
- Configured Claude Code to connect to a local Anthropic-compatible endpoint running on localhost.
- Restarted Cursor so the updated configuration was loaded.
- Verified that Claude Code connected successfully.
- Sent a test prompt inside Cursor.
- Confirmed that Claude Code was able to receive and return responses through the local gateway.

No authentication tokens, API keys, or sensitive configuration values are included in this repository.

### Codex

The Codex extension was installed successfully.

At first, Codex reused configuration imported from an existing VS Code setup. That configuration pointed to a local gateway, which made the setup too similar to the Claude Code workaround.

To keep the Codex setup closer to the default extension flow, the existing Codex configuration was backed up by renaming `config.toml` to `config.toml.bak`. Cursor was then restarted so Codex could create a fresh default configuration.

After the default configuration was restored:

- Codex loaded successfully.
- Authentication was completed through the OpenAI login flow using Google sign-in.
- The Codex sidebar was reopened successfully.
- A test conversation confirmed that Codex was working normally.

### GitHub Repository

A public GitHub repository named `cursor-ai-setup` was created under the `Vann4799` account.

The local project was connected to GitHub, committed, and pushed to the `main` branch.

---

## Troubleshooting

### Claude Code

- Initial authentication succeeded.
- Requests failed because the default Anthropic API account had no available credits.
- A locally hosted Anthropic-compatible endpoint was configured.
- Successful connection was verified after updating the configuration and restarting Cursor.

### Codex

- Codex initially reused configuration from an existing VS Code setup.
- The imported configuration pointed to a local gateway.
- The previous configuration was backed up by renaming `config.toml` to `config.toml.bak`.
- Cursor was restarted so Codex could generate a fresh default configuration.
- Authentication was completed through the OpenAI login flow using Google sign-in.
- The Codex sidebar was reopened.
- A test conversation confirmed that the extension worked correctly with the default setup.

### Git

The local project initially had no GitHub remote configured.

This was resolved by adding the repository remote, committing the documentation, and pushing the project to GitHub.

### PowerShell

Some command chaining syntax was not compatible with the available PowerShell environment.

Commands were run separately where needed to avoid shell compatibility issues.

---

## Screenshots

Screenshots will be updated to reflect the final working environment.

The final screenshot set should show:

- Cursor IDE
- Claude Code connected and responding
- Codex sidebar working
- Repository opened in Cursor
- GitHub repository
- README inside Cursor

Screenshots that only show the earlier API credit limitation are not part of the final setup documentation.

---

## Environment

| Component | Details |
|-----------|---------|
| Operating System | Windows 11 |
| IDE | Cursor |
| Version Control | Git |
| Repository Hosting | GitHub |

---

## Result

Cursor, Claude Code, Codex, Git, and GitHub were installed and configured successfully.

Claude Code was verified through a locally hosted Anthropic-compatible gateway. Codex was restored to its default configuration and verified through OpenAI authentication.

**README link:** https://github.com/Vann4799/cursor-ai-setup/blob/main/README.md

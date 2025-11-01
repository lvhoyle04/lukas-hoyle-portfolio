# Contributor Guide

Welcome — thank you for contributing. This document outlines expectations and processes for contributing to this portfolio.

Table of contents
- Branching and commit conventions
- Pull request process
- Code and documentation style
- Testing and verification
- Security and sensitive data

Branching and commits
- Base new work off `main` into a descriptive branch, e.g. `feature/add-brief-n8n` or `fix/readme-typo`.
- Keep commits focused and atomic. Use imperative commit messages, e.g. "Add n8n automation brief".
- Squash or rebase when appropriate; maintain a clean history.

Pull requests
- Open a PR to `main` with a clear description of changes and motivation.
- Link related briefs or docs and include any testing steps.
- Request at least one review; respond to feedback promptly.

Documentation style
- Use clear, passive-voice-free sentences.
- Use headings, lists and code blocks for readability.
- Provide examples where helpful (config snippets, sample payloads).

Testing & verification
- When proposing automation or infrastructure changes, include:
  - Steps to reproduce
  - Expected results
  - Rollback guidance if applicable

Security and sensitive data
- Never commit secrets (API keys, passwords, private certificates).
- Use environment variables and secret stores for any sensitive values.
- If you find a security issue, open a private support path (issue marked `security`) and mention the repository owner.

Thanks for contributing — your changes improve the value and clarity of this portfolio.
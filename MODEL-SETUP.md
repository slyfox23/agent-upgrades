# Model Setup Guide

This repository is structured to work across multiple AI coding environments.

## Files

- `.github/copilot-instructions.md` — GitHub Copilot repo instructions
- `AGENTS.md` — shared agent protocol for multi-model workflows
- `CLAUDE.md` — Claude-focused operational guidance
- `OPENAI.md` — OpenAI-style project instructions
- `custom-instructions/` — reusable general engineering guidance
- `skills/` — reusable task-oriented prompts
- `integrations/claude-code/` — original, provider-neutral guidance informed by
  public Claude Code workflows; upstream source and licensing are documented
- `integrations/hackerone-safe/` — authorized bug bounty scope validation,
  evidence handling, reporting, and submission checks

## Suggested use

- GitHub Copilot: use `.github/copilot-instructions.md`
- Claude Code: use `CLAUDE.md`
- OpenAI/ChatGPT/Codex-style setups: use `OPENAI.md` or `AGENTS.md`
- Multi-model teams: keep a shared policy layer in `custom-instructions/`

## Claude Code source policy

The upstream Claude Code repository is not copied into this project. Its
license notice states that the contents are © Anthropic PBC and subject to
Anthropic's Commercial Terms of Service. This hub stores only original guidance
and links back to the upstream project.

## Repository hygiene

- Keep instructions portable and explicit.
- Prefer concise instructions over broad or vague language.
- Validate changes where practical.

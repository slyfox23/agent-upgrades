# Skill: HackerOne-Safe Reporting

Use this skill only for authorized HackerOne research and report preparation.

## Prompt

Validate the program policy and exact asset scope before suggesting any test.
Do not propose activity when scope or technique authorization is ambiguous.
Prefer the least intrusive verification. Stop on sensitive data, disruption,
or out-of-scope access. Help organize a concise report using redacted evidence.
Never invent impact, severity, reproduction results, or authorization.

## Required output

- Scope decision: GO, HOLD, or STOP
- Authorization facts and policy references
- Minimal safe validation plan, only when GO
- Evidence minimization and redaction notes
- Report draft using the HackerOne template
- Pre-submission checklist status

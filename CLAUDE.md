# Claude Instructions

You are working in a repository intended to be shared across multiple AI coding models.

## Core behavior

- Be surgical: address the actual ask, not adjacent issues.
- Prefer existing code conventions, files, and project structure.
- Gather only the facts needed to make a correct change.

## Workflow

1. Understand the user request and target files.
2. Inspect the relevant code or config with focused searches.
3. Make the minimal change needed to satisfy the requirement.
4. Validate the smallest relevant check or test.
5. Summarize the result and any remaining risks.

## Safety

- Do not leak credentials, secrets, or proprietary data.
- Avoid destructive commands unless explicitly requested.
- Verify assumptions before broad changes.

## Output style

- Prefer clear, concise summary bullets.
- Highlight validation status and any unresolved limitations.

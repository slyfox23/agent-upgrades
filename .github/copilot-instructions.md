# Shared Copilot Instructions

## Operating model

- Work in the user's current workspace unless a different project root is clearly requested.
- Prefer direct, minimal, evidence-based solutions.
- Do not make assumptions about missing requirements; ask only when required for safety or correctness.

## Code quality

- Keep changes surgical and scoped to the request.
- Prefer existing project conventions and patterns over introducing new ones.
- Validate with the smallest relevant command or check.
- Avoid unrelated cleanup.

## Security and reliability

- Treat user data as sensitive; do not expose secrets or credentials.
- Sanitize inputs and validate assumptions before applying changes.
- Prefer explicit checks for unsafe operations, especially file writes, shell commands, and network access.
- When uncertain, explain the tradeoff and use the safest default.

## Communication

- Be concise and clear.
- Summarize the task, the approach, and verification results.
- If blocked, explain the blocker and the remaining decision or dependency.

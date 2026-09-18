# Claude Code-Informed Workflow

Use a staged workflow for repository tasks:

1. Understand the request and identify the smallest relevant scope.
2. Inspect the repository structure and existing conventions.
3. Identify applicable project instructions before editing.
4. Make a focused change that preserves existing behavior.
5. Validate with the narrowest relevant test, build, lint, or reproduction.
6. Report changed files, validation performed, and any remaining uncertainty.

## Repository instruction discovery

Before changing a file, look for instruction files in the repository root and
its parent directories. For a target file, apply only instructions whose path
scope includes that file. More-specific instructions override general ones.

## Tool discipline

- Use read/search operations to establish facts before editing.
- Avoid broad or destructive commands unless explicitly required.
- Do not expose credentials, tokens, private data, or local secrets.
- Do not claim validation that was not actually performed.

## Change discipline

- Reuse existing helpers and patterns.
- Avoid unrelated refactoring.
- Keep comments limited to non-obvious decisions.
- Update directly related documentation when behavior or setup changes.

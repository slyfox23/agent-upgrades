# Security Review Checklist

Use this checklist for a focused review of code changes:

## Review scope

- Review the actual diff first.
- Trace changed data across relevant callers and boundaries.
- Check authentication, authorization, input validation, and output encoding.
- Check for injection, path traversal, SSRF, insecure deserialization, and
  hardcoded secrets.
- Check error handling for silent failures or unsafe fallback behavior.

## Finding quality

Report only issues supported by concrete evidence in the code or diff.
Prioritize by impact and exploitability. Distinguish confirmed vulnerabilities
from defense-in-depth suggestions.

Each finding should include:

- Severity
- File and line range
- Vulnerability or risk
- Evidence and impact
- Minimal remediation
- Confidence

## Privacy

Do not place secrets or sensitive source content in review prompts, logs,
reports, or committed policy files.

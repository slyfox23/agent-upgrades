# HackerOne Report Template

## Title

[Asset or feature] allows [security impact] through [root cause]

## Summary

Describe the vulnerability in one or two concise paragraphs. State the
security boundary affected and avoid including secrets or unnecessary data.

## Affected asset

- Program:
- In-scope asset:
- Environment:
- Endpoint or feature:
- Test account role:

## Preconditions

List only the access and setup required to reproduce the issue.

## Reproduction steps

1. Use a permitted test account or unauthenticated state as applicable.
2. Navigate to the affected feature or send the minimum necessary request.
3. Observe the specific security-relevant result.

Use placeholders for identifiers and redact all credentials, tokens, cookies,
personal data, and unrelated response content.

## Expected result

What should a properly authorized user or system be able to do?

## Actual result

What unauthorized access, action, disclosure, or integrity impact occurs?

## Impact

Explain affected confidentiality, integrity, or availability and identify the
realistic attacker position. Avoid inflated claims.

## Evidence

Attach only minimal redacted screenshots, request/response excerpts, or logs.
State how secrets and personal data were removed.

## Suggested remediation

Describe the root-cause fix at a high level, such as enforcing server-side
authorization on every object access or validating a state transition.

## Validation notes

- Reproduced from a clean test state:
- Tested only within declared scope:
- No sensitive data retained:
- Date/time in UTC:

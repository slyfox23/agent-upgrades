# HackerOne-Safe Bug Bounty Workflow

This workflow is for authorized vulnerability research on HackerOne programs.
It is a process and reporting aid, not permission to test any target.

## Non-negotiable rule

Do not test an asset until the current HackerOne program policy explicitly
authorizes that asset and the planned technique. When scope, ownership,
severity, rate limits, or safe-harbor language is unclear, stop and request
clarification from the program.

## Workflow

1. Record the program URL, policy version/date, and researcher account.
2. Complete `scope-validation.md` before any request beyond ordinary browsing.
3. Use the least intrusive validation possible and honor rate limits.
4. Stop immediately if personal data, credentials, production disruption, or
   an out-of-scope system is encountered.
5. Capture only the minimum evidence needed to reproduce the issue.
6. Draft the report with `report-template.md`.
7. Complete `pre-submission-checklist.md`.
8. Submit through HackerOne and retain the report ID and timestamps.

AI tools may suggest leads or help format a report, but a human must verify
scope, reproduce the finding, remove sensitive data, and approve submission.

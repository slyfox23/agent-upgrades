# Evidence Handling

Collect the smallest amount of evidence that proves impact and enables
reproduction.

## Capture

- Record UTC timestamps, target, endpoint or feature, and test-account role.
- Preserve the exact request shape only when it contains no secrets or private
  data; redact authorization headers, cookies, tokens, and identifiers.
- Capture a minimal response excerpt or screenshot showing the security impact.
- Record a repeatable sequence without exporting an entire database or user
  dataset.
- Hash local evidence files when chain-of-custody tracking is useful.

## Do not collect

- Passwords, API keys, session cookies, bearer tokens, or private keys.
- Unnecessary personal, financial, health, or confidential business data.
- Bulk records, complete database dumps, or unrelated user accounts.
- Malware, destructive payloads, persistence, or data exfiltration artifacts.

## If sensitive data appears

1. Stop testing and do not browse further.
2. Do not copy, download, share, or include the data in a report.
3. Record only the minimum metadata needed to explain what happened.
4. Follow the program's disclosure instructions and contact path.
5. Securely delete local copies when retention is no longer required.

Keep evidence in a protected local directory outside the Git repository.
Never commit evidence, screenshots containing secrets, or target data.

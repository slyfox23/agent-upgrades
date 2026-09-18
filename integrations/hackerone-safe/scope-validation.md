# Scope Validation Worksheet

Complete this worksheet for every program and test session. Save only
non-sensitive metadata. Do not store credentials, tokens, personal data, or
raw production responses.

## Program authorization

- Program name and HackerOne URL:
- Policy last reviewed (UTC):
- Researcher account:
- Safe harbor present and applicable:
- Contact or clarification path:

## Target authorization

- Target hostname, application, repository, mobile package, or asset:
- Exact in-scope entry from the policy:
- Asset type:
- In-scope environments:
- Explicit exclusions:
- Third-party services involved:
- Authentication or test-account requirements:

## Technique authorization

- Planned activity:
- Explicitly permitted by policy:
- Explicitly prohibited by policy:
- Automation permitted:
- Rate or volume limits:
- Data-handling restrictions:
- Destructive-action restrictions:

## Decision gate

Mark one:

- [ ] **GO** - asset and technique are explicitly in scope, limits are known,
      and the test can be performed without accessing unnecessary data.
- [ ] **HOLD** - policy or authorization is ambiguous; ask the program first.
- [ ] **STOP** - asset or technique is excluded, third-party-owned without
      authorization, or the activity could cause harm.

Never convert HOLD or STOP into GO based on an AI suggestion.

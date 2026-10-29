# NTI Messenger — public issue tracker

This repository is the **public bug tracker for NTI Messenger**. It holds
reports, feedback and feature requests from users and testers — not source
code.

## Report something

- [Report a bug](https://github.com/utarn/nti-messenger-public/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/utarn/nti-messenger-public/issues/new?template=feature_request.yml)
- [Browse open issues](https://github.com/utarn/nti-messenger-public/issues)

Please search the existing issues before filing. Include your app version,
platform, and clear reproduction steps — the forms ask for all of it.

## Security and privacy

**Do not file security vulnerabilities or data-privacy problems as public
issues.** Use
[private vulnerability reporting](https://github.com/utarn/nti-messenger-public/security/advisories/new)
instead, so the problem can be fixed before it is public.

Never paste passwords, access tokens, refresh tokens, deletion secrets or
private message content into an issue.

## How issues are triaged

Maintainers move each issue through these labels:

| Label | Meaning |
| --- | --- |
| `needs-triage` | Not evaluated yet |
| `needs-info` | Waiting on the reporter for more information |
| `needs-reproduction` | Could not reproduce yet; steps or details needed |
| `tester-verified` | A tester has reproduced the problem |
| `ready-for-agent` | Fully specified and ready to implement |
| `ready-for-human` | Needs a developer, manual testing or a design decision |
| `in-progress` | Being worked on |
| `resolved` | Fixed, awaiting the reporter's verification |
| `wontfix` | Out of scope or intentionally not actioned |

Type: `bug`, `enhancement`, `feedback`, `documentation`, `question`.
Priority: `priority:critical`, `priority:high`, `priority:medium`, `priority:low`.
Area: `area:auth-accounts`, `area:messaging`, `area:friends`, `area:calls`,
`area:media`, `area:notifications`, `area:devices-security`, `area:ui-ux`.

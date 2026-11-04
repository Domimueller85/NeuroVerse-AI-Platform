# Security

## Current scope

This repository currently contains documentation, not an application or
deployment configuration. It does not establish that security controls,
certifications, monitoring, encryption, or compliance measures are implemented.
Any future security claims should identify the relevant implementation and
evidence.

Repository visibility, collaborator access, branch protection, and private
vulnerability reporting are controlled through GitHub settings. This document
does not change those settings or create confidentiality obligations.

## Reporting a concern

Do not post credentials, personal data, or details of a suspected vulnerability
in a public issue. If GitHub private vulnerability reporting is enabled for
this repository, use it. Otherwise, contact the repository owner through a
private channel. Avoid accessing data or systems beyond what is necessary to
describe the issue.

Preferred channel: the repository's **Security** tab → **Report a
vulnerability** (available only if the owner has enabled it).

Never commit secrets. The `.gitignore` excludes common key and credential
files, but this is a safeguard, not a guarantee. If a secret is committed,
revoke and rotate it immediately; deleting it from history is not enough.

No response time, remediation timeline, or bug bounty is promised by this
document.

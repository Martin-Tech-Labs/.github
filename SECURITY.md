# Security Policy

## Scope and supported versions

This policy applies to repositories in this organization unless a repository
provides its own security policy.

Repository-specific documentation and release notes define supported versions.
If no support policy is published, contact the maintainers privately to confirm
whether your version is supported. Do not assume older releases receive security
fixes.

## Reporting a vulnerability

Please report suspected vulnerabilities privately. Do not open a public issue or
pull request containing exploit details, credentials, or sensitive information.

Where GitHub private vulnerability reporting is enabled, open the affected
repository's **Security** tab, select **Advisories**, and choose **Report a
vulnerability**.

If that option is unavailable, use a private contact method published by the
repository maintainers or organization owners on their profiles or website. If
no private contact method is listed, open an issue asking for a secure reporting
channel without describing the vulnerability.

Include, where available:

- The affected repository, version or commit, and relevant environment details.
- A description of the vulnerability and its potential impact.
- Reproduction steps or a minimal proof of concept using synthetic data.
- Any known mitigations or suggested fixes.
- Your preferred contact method and whether you would like public credit.

Do not include live credentials, encryption keys, personal data, or private
conversation content. Share only the information needed to reproduce the issue.

## Responsible testing

Test only systems and data you own or have explicit permission to assess. Avoid
service disruption, accessing other people's data, or modifying or deleting data
outside your authorized test environment. Stop testing and report privately if
you encounter sensitive information unexpectedly.

## Response and coordinated disclosure

Maintainers will review the report, request additional details if needed, and
coordinate investigation, mitigation, and any necessary fix with the reporter.
Response times depend on maintainer availability; this policy does not promise a
fixed response or remediation deadline.

Please coordinate public disclosure with maintainers so users have an opportunity
to apply a fix or mitigation. When appropriate, maintainers will publish a
security advisory describing affected versions, impact, and remediation, and
credit the reporter with their consent.

If a report does not receive a response, follow up through another published
private maintainer or organization contact where possible.

## Handling exposed credentials

If a credential has been exposed, revoke or rotate it promptly. Removing it from
a file or Git history alone does not make it safe to use again. Report the
exposure without including the credential itself.

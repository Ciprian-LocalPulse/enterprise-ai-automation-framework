# Security Policy

Enterprise AI Automation Framework is maintained as a public-facing enterprise architecture and governance repository. This policy defines how security concerns should be reported, what is in scope for public review, and which implementation details must remain private.

## Public Edition Security Scope

This repository represents the Public Edition of Enterprise AI Automation Framework. Public materials may include positioning, documentation, static previews, high-level architecture, governance files, non-operational examples, and safe evaluation materials.

This repository must not disclose or request disclosure of:

- production automation workflows, orchestration logic, or execution playbooks
- private AI agent prompts, system prompts, tool instructions, or chain-of-thought artifacts
- client environments, internal process maps, customer data, vendor records, or operational runbooks
- API keys, tokens, OAuth credentials, service-account files, secrets, or environment variables
- private compliance evidence, SOC 2 artifacts, ISO 27001 evidence, GDPR records, or audit workpapers
- private integrations with CRMs, ERPs, payment systems, ticketing systems, cloud accounts, or internal databases
- data transformation rules, approval logic, access-control policies, or escalation workflows used in production
- commercial implementation details, acquisition materials, pricing models, or buyer-specific requirements

## Supported Scope

Security reports are welcome for issues affecting public repository materials, including:

- accidental exposure of secrets or sensitive data
- unsafe public documentation that could enable misuse
- vulnerable public demo code, if present
- dependency, supply-chain, or build configuration concerns, if such files are later added
- misleading compliance, security, or automation claims that could create user or buyer risk
- repository configuration issues that affect integrity, trust, or disclosure handling

## Out of Scope

The following are generally out of scope unless they expose sensitive data or create direct user risk:

- generic best-practice requests without a specific security impact
- social engineering, phishing, or physical security testing
- denial-of-service testing or traffic flooding
- scanning infrastructure not owned or explicitly authorized by the maintainer
- automated reports with no exploitability explanation
- third-party platform issues outside this repository owner's control
- requests for private workflow logic, prompts, customer-specific implementation, compliance evidence, or deployment details
- speculative compliance claims without a concrete repository risk

## Reporting Process

Please report security issues privately and with minimal sensitive detail.

Preferred process:

1. Use GitHub private vulnerability reporting if it is enabled for this repository.
2. If private vulnerability reporting is unavailable, contact the maintainer through the public GitHub profile or the commercial contact path listed in SUPPORT.md.
3. Do not open a public issue containing secrets, exploit details, private infrastructure references, prompt details, workflow logic, customer information, or implementation-sensitive information.
4. Include a concise description, affected file or area, reproduction notes where safe, and recommended remediation.

## Response Timeline

The maintainer will make a reasonable effort to follow this timeline:

- Acknowledgement: within 5 business days
- Initial triage: within 10 business days
- Remediation decision: based on severity, exploitability, and public safety impact
- Public disclosure: only after remediation or explicit maintainer approval

This repository is maintained as a public product and governance surface. Response times may vary for non-critical documentation findings.

## Safe Harbor

Good-faith research is welcome when it is defensive, limited, and respectful of the boundaries above. The maintainer will not pursue action against researchers who:

- act in good faith and avoid privacy violations
- do not access, modify, delete, or exfiltrate data
- do not disrupt services or third-party systems
- avoid public disclosure before coordination
- stop testing and report promptly after identifying a potential issue

Safe harbor does not apply to unauthorized access, credential misuse, data theft, extortion, bypass attempts against third-party systems, prompt extraction, or attempts to obtain Private Enterprise Edition materials.

## Public Disclosure

Public disclosure should be coordinated with the maintainer. Reports may be acknowledged in release notes or changelog entries when doing so does not reveal sensitive security information.

## Responsible Use

Enterprise AI Automation Framework is intended for lawful enterprise automation, governance, compliance, and security architecture evaluation. Reports, issues, pull requests, or discussions that enable unauthorized automation, credential misuse, data misuse, compliance misrepresentation, or unsafe implementation detail may be closed or removed.
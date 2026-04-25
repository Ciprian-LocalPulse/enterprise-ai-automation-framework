# Contributing Guidelines

> **AI Automation Empire — Enterprise Blueprint**  
> © 2026 Ciprian Stefan Plesca · LOCALPULSE.PRO · All Rights Reserved

---

## Overview

This is a **proprietary enterprise repository**. Contributions are accepted exclusively from authorized personnel — licensed partners, vetted practitioners, and approved collaborators operating under a signed agreement with Ciprian Stefan Plesca / LOCALPULSE.PRO.

Unauthorized contributions, forks, or modifications are in violation of the [LICENSE](./LICENSE.md) and applicable intellectual property law.

---

## Who Can Contribute

| Role | Authorization Required |
|------|----------------------|
| Licensed Enterprise Partners | Signed Partner Agreement |
| Certified Practitioners | Active License + NDA |
| Internal Team Members | Employment / Contractor Agreement |
| External Researchers (security) | See [SECURITY.md](./SECURITY.md) |

If you are not currently authorized and wish to discuss collaboration or licensing, contact:  
📧 [CONTACT@LOCALPULSE.PRO](mailto:CONTACT@LOCALPULSE.PRO)  
📅 [cal.com/ciprian-stefan-plesca](https://cal.com/ciprian-stefan-plesca)

---

## Contribution Standards

All authorized contributors must adhere to the following standards:

### Code & Template Quality

- All automation templates must be fully tested in a staging environment before submission.
- Templates must include inline documentation: purpose, inputs, outputs, and security considerations.
- No hardcoded credentials, secrets, API keys, or PII in any submitted file. Ever.
- All webhook implementations must include HMAC signature verification.
- AI prompts must include a security review note flagging any data exposure risks.

### Documentation Standards

- All documentation must be written in **clear, professional English**.
- Use the established enterprise tone: precise, confident, security-conscious.
- All compliance claims must be verified and cited.
- Include version, date, and author attribution on all new documents.

### Security Requirements (Mandatory)

Every contribution must pass the following security checklist before review:

```
□ No secrets or credentials in any file
□ PII handling documented and compliant (GDPR / CCPA)
□ Webhook endpoints include HMAC verification
□ API keys scoped to least privilege
□ Error handling does not expose sensitive data in logs
□ Data flows documented in the architecture diagram
□ Encryption at rest and in transit confirmed
□ No third-party dependencies introduced without security review
```

---

## Contribution Workflow

### Step 1 — Pre-Contribution Agreement

Ensure you have a current, signed:
- Non-Disclosure Agreement (NDA)
- Contributor License Agreement (CLA) or equivalent contractual authorization

### Step 2 — Branch Naming Convention

```
feature/module-XX-description
fix/template-XX-issue-description
docs/section-description
security/cve-identifier-or-brief
compliance/regulation-scope
```

### Step 3 — Commit Message Format

Follow the **Conventional Commits** specification:

```
type(scope): concise description

Body: detailed explanation of what and why (not how).
References: issue/ticket numbers if applicable.

Types: feat | fix | docs | security | compliance | refactor | test | chore
```

**Examples:**
```
feat(module-04): add mTLS implementation guide for internal APIs
fix(template-009): correct HMAC key rotation in webhook handler
security(module-12): update incident response SLA to reflect P1 4-hour RTO
compliance(module-05): add Texas TDPSA sensitivity data category mappings
docs(readme): update module architecture diagram for v3.2
```

### Step 4 — Pull Request Requirements

All pull requests must include:

- [ ] **Summary**: What does this change and why?
- [ ] **Security Impact**: Does this change touch data flows, credentials, or PII?
- [ ] **Testing**: How was this tested? Include environment details.
- [ ] **Compliance Impact**: Any GDPR / SOC2 / ISO 27001 implications?
- [ ] **Documentation Updated**: Have all relevant docs been updated?
- [ ] **Reviewer Assigned**: Tag the appropriate module owner.

### Step 5 — Review & Approval

| Change Type | Approvals Required |
|-------------|-------------------|
| Documentation only | 1 authorized reviewer |
| Template or prompt | 1 technical + 1 security reviewer |
| Security or compliance | CISO review (Ciprian Stefan Plesca) mandatory |
| Architecture changes | CISO review + Partner sign-off |

---

## Intellectual Property

All contributions submitted to this repository become the **exclusive property of Ciprian Stefan Plesca / LOCALPULSE.PRO** under the terms of the signed Contributor License Agreement. Contributors retain no IP rights to submitted work.

This is a condition of contribution and is non-negotiable.

---

## Questions & Authorization

To inquire about becoming an authorized contributor or licensed partner:

- **Email:** [CONTACT@LOCALPULSE.PRO](mailto:CONTACT@LOCALPULSE.PRO)
- **Book a consultation:** [cal.com/ciprian-stefan-plesca](https://cal.com/ciprian-stefan-plesca)

---

*© 2026 Ciprian Stefan Plesca · AI Automation Empire · All Rights Reserved*

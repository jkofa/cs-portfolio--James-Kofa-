# cs-portfolio--James-Kofa-
# CS Portfolio — Artemis Financial (Journal Submission)

**Repository:** <paste your GitHub repo URL>  
**Artifact submitted:** <Vulnerability Assessment Report OR Practices for Secure Software Report>  
**File path in repo:** artifacts/<your-file-name>.pdf

## Summary of Client & Requirements
Artemis Financial is a fintech company handling sensitive client and transaction data. They asked me to evaluate their application for security risks and strengthen the codebase to address transport security, dependency risks, and data integrity while preserving functionality.

## What I Did Well & Why Secure Coding Matters
I mapped findings to specific controls (TLS, dependency hygiene, input validation) and prioritized remediations with clear justification. Secure coding reduces breach risk, protects customers, limits legal exposure, and preserves brand trust and uptime.

## Challenging/Helpful Parts
Triaging dependency-scan “noise” vs. real risk was the hardest. Building a repeatable checklist (TLS checks, header/cipher review, dependency pinning, validation) was most helpful.

## Layers of Security & Future Assessments
I enforced HTTPS/TLS, tightened cipher/protocol settings, validated input/output, used checksums for integrity, and cleaned third-party dependencies. In the future I’d combine SCA/SAST/DAST tools with manual threat modeling to choose mitigations.

## Verifying Functionality & Preventing New Vulnerabilities
I re-ran tests and manual flows, verified TLS handshakes and headers, reviewed dependency reports, and repeated security scans to confirm fixes and ensure no new issues were introduced.

## Reusable Tools & Practices
Tools: OWASP Dependency-Check, keytool/openssl, build tooling.  
Practices: least privilege, validation/encoding, defense in depth, version pinning, documented before/after evidence.

## What I’d Show Employers
The final report (problem → evidence → fix → validation), targeted security commits, and a verification checklist—demonstrating practical secure-coding skills and measurable improvements.

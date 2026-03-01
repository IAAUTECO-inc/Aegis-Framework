# Contributing to AEGIS: Engineering Protocol

Thank you for your interest in sovereign infrastructure. AEGIS is a mission-critical framework; therefore, contributions follow a strict institutional validation protocol.

## 1. Technical Requirements
* **Determinism:** No stochastic "black-box" patches. All logic must be reproducible.
* **Portability:** Code must remain compliant with hardened Unix environments (Winterhold OS) and hardware-agnostic (ARM/RISC-V).
* **No Telemetry:** Any code attempting to establish unauthorized WAN connections or data exfiltration will be rejected and reported.

## 2. The Submission Process
1. **Issue First:** Open a "Conceptual Issue" to discuss the architectural impact of your change before coding.
2. **Auditability:** Ensure your code is heavily documented for third-party auditing.
3. **Signed Commits:** All commits must be cryptographically signed (GPG/SSH). Unsigned commits will be automatically rejected.
4. **Traceability:** Every Pull Request must include an updated traceability matrix aligned with **EU AI Act Articles 9-15**.

## 3. Licensing & Rights
By contributing, you agree that your code will be licensed under the project's [LICENSE]. You certify that you have the legal right to contribute this code and that it is free of third-party intellectual property encumbrances.

*Infrastructure Division | IA_AUT_ECO*

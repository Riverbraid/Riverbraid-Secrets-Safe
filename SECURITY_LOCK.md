# Security Invariants
- Enforce Ed25519 for all internal signatures.
- Maintain PEM unification (no manual DER wrapping).
- Strictly follow the Fail-Closed protocol for any key mismatch.

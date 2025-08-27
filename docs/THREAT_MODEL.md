# Threat Model

**Goals:** kernel-enforced tool allowlist; rate-limited control plane  
**Protects:** unauthorized tool exec; tamper/mismatch; burst abuse  
**Out of scope:** physical access; unrelated kernel 0-days; third-party supply chain  
**Assumptions:** LTS kernel; DKMS intact; sane time/entropy

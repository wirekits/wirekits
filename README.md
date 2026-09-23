![banner](https://i.pinimg.com/736x/35/75/c9/3575c9699c38ae02feaecf040f32c0b5.jpg)


# ROOT

Blue team tooling · Malware triage · DFIR · Scripting

## About

I build defensive security tooling — malware triage sandboxes, IOC/attribution pipelines, and hardening/verification scripts — and validate them against real-world samples and telemetry, not just lab data.

**Current focus areas:**
- **Malware triage & DFIR** — static + dynamic analysis, MITRE ATT&CK-mapped verdict scoring, capability inference from ELF/PE imports, fuzzy-hash attribution (imphash/symhash/ssdeep/TLSH), YARA on disk and memory
- **Network forensics** — pcap-based IOC extraction (DNS/SNI/JA3)
- **Hardening & security testing** — scripts and checks for verifying system and application security posture

All samples are handled in isolated, network-restricted environments (sandboxed execution, opt-in packet capture, no persistence outside the run directory).

## Featured projects

**[illusion-MW-triage](https://github.com/wirekits/illusion-MW-triage)**
Sandboxed malware triage engine: scored MITRE ATT&CK verdicts (noisy-OR confidence), ELF/PE capability inference, attribution hashing, file magic + embedded-file carving, IOC extraction, YARA (file + memory), pcap network intel.

**[hollow-labs](https://github.com/wirekits/hollow-labs)**
TUI trainer for IR/SOC analysts — simulates real attacks with dynamically generated logs/artifacts and scored quizzes. Rust, cross-platform, reproducible via seed.

**[hollow-chat](https://github.com/wirekits/hollow-chat)**
Open-source Discord alternative focused on privacy — Signal Protocol E2E encryption, minimal server-side metadata, optional Tor transport. Rust (Axum) + Svelte (Tauri).

**[security-stack](https://github.com/wirekits/security-stack)**
Common scripts and checks for testing and hardening system security.

## Contact
- Discord: `wirekits`
- Telegram: [@landfee](https://t.me/landfee)
- Email: dstrelayai@gmail.com

Contact

Discord: wirekits
Telegram: @miswire
Email: dstrelayai@gmail.com

 

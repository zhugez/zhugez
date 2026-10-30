<div align="center">

Security researcher. I write vulnerability scanners, and I read security patches
for the guard they add.

Vulnerability research · coding-agent tooling · Rust, TypeScript, and Python

[![Blog](https://img.shields.io/badge/Blog-shadowforge-52525b?style=flat-square&logo=vercel&logoColor=white)](https://shadowforge.vercel.app/)
[![X](https://img.shields.io/badge/X-%40dezzhu1-52525b?style=flat-square&logo=x&logoColor=white)](https://x.com/dezzhu1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dezzhu-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dezzhu)
[![dev.to](https://img.shields.io/badge/dev.to-zhugez-52525b?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/zhugez)

</div>

The finding I keep landing on is the same shape: a component that is exported to
the outside world, and then trusts what it is handed. Three of my four Telegram
for Android findings are that shape — an exported intent handler that redirects
an OAuth token before authentication, an unclamped intent extra that switches
account before the passcode runs, an exported service that a local app can crash.

## Selected work

| Project | What it does |
| --- | --- |
| **[TrustSee](https://trustsee.com)** | CVE baseline from NVD, OSV, and GHSA, ranked by CISA KEV and EPSS. Website, email, domain, and uptime posture checks, authorized red-team probes, and a dark-web feed. It exposes `scan_repo` over MCP, so Claude and Cursor queue scans without leaving the agent. `Next.js` · `React` · `TypeScript` · `Supabase` · `TinyFish` · `Playwright` |
| **[ExoMind](https://github.com/zhugez/ExoMind)** | Portable knowledge and memory runtime. One store serves Pi, Hermes Agent, OpenClaw, and Codex. `Rust` |
| **[Stella](https://github.com/zhugez/Stella)** | Illustrated IELTS vocabulary app. 7,298 words, each with an original illustration, native UK and US audio, and FSRS scheduling. [Live](https://stella.zhugez.workers.dev) · `TypeScript` |
| **[Pingloom](https://github.com/zhugez/Pingloom)** | Native desktop ping and emote wheels. Windows, with experimental macOS and a NixOS Wayland build. [Demo](https://pingloom.zhugez.workers.dev/) · `Rust` · `Tauri 2` · `Svelte 5` |
| **[Pi-pulse](https://github.com/zhugez/Pi-pulse)** | Extensions for the [Pi coding agent](https://pi.dev): a loop guard, mutation and CRAP gates, a comment checker, in-flight diagnostics, and provider tooling. `TypeScript` |
| **[Pi-capsule](https://github.com/zhugez/Pi-capsule)** | A Pi setup, packed for every machine. Exports and restores `~/.pi/agent` — extensions, skills, prompts, providers, and models — and leaves secrets at home. `JavaScript` |
| **[ShadowForge](https://github.com/zhugez/ShadowForge)** | Portfolio for the security research and the projects on this profile. [Live](https://shadowforge.vercel.app/) · `Next.js` · `React` · `TypeScript` |
| **[Cordyceps](https://github.com/zhugez/Cordyceps)** | WordPress plugin scanner. It finds the guard a security patch adds, then uses a static AST reachability harness to drop findings an attacker cannot reach. An OpenClaw and Hermes skill over [Mycelium](https://github.com/zhugez/Mycelium) and Patchstack data. `Python` |

## Tech stack

<p align="center">
  <img alt="TypeScript, JavaScript, Python, Rust, C++, React, Next.js, Svelte, HTML, CSS, Tauri, and Astro" src="https://skillicons.dev/icons?i=ts,js,py,rust,cpp,react,nextjs,svelte,html,css,tauri,astro&perline=6">
</p>

TypeScript, JavaScript, Python, Rust, and C++ for the work above. React, Next.js, Svelte, and Tauri for the interfaces. Deploys go to Cloudflare Workers and Vercel.

## Research and disclosures

**Publications.** First author on all four.

| Venue | Title | Status |
| --- | --- | --- |
| AISEI 2026, IEEE | Biometric Identification Through Auditory EEG Signatures | [Published](https://doi.org/10.1109/AISEI68628.2026.11572950). |
| SSRC 2026 | Multimodal Mamba Fusion for Noise-Robust EEG Biometric Identification | [Published](https://ssrc.fit.iuh.edu.vn/conf/article/view/267). |
| APSIPA ASC 2026 | Multimodal Mamba Fusion for Noise-Robust EEG Biometric Identification | Accepted. |
| ATC 2024 | Malware detection with machine learning and deep learning | Presented. |

**Disclosures.** Severity is CVSS.

| Target | Findings | Status |
| --- | --- | --- |
| Telegram for Android | 4 — exported intent handler redirects an OAuth token before authentication (7.1 High)<br>integer truncation in the native verifier (7.5 High)<br>unclamped intent extra switches account before the passcode (5.5 Medium)<br>exported service, local denial of service (5.5 Medium) | Submitted. |
| Patchstack | 2 — broken access control in Upsell Order Bump Offer for WooCommerce (Medium)<br>broken access control in an undisclosed commercial CRM plugin (Medium) | Accepted. |
| IUH | 3 — two High (8.7), one Medium (6.9) | Accepted. |

**Awards.** YSC 2025, Consolation Prize. Certified AppSec Practitioner (CAP).

## Contact

[Blog](https://shadowforge.vercel.app/) · [X](https://x.com/dezzhu1) · [LinkedIn](https://www.linkedin.com/in/dezzhu) · [dev.to](https://dev.to/zhugez)

Open to work.

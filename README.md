<div align="center">

Security researcher. I write vulnerability scanners, and I read security patches
for the guard they add.

[![X](https://img.shields.io/badge/-%40dezzhu1-000?style=flat-square&logo=x&logoColor=white)](https://x.com/dezzhu1)
[![LinkedIn](https://img.shields.io/badge/-dezzhu-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dezzhu)
[![dev.to](https://img.shields.io/badge/-zhugez-000?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/zhugez)
[![Site](https://img.shields.io/badge/-shadowforge-1c1917?style=flat-square&logo=vercel&logoColor=white)](https://shadowforge.vercel.app/)

</div>

The finding I keep landing on is the same shape: a component that is exported to
the outside world, and then trusts what it is handed. Three of my four Telegram
for Android findings are that shape — an exported intent handler that redirects
an OAuth token before authentication, an unclamped intent extra that switches
account before the passcode runs, an exported service that a local app can crash.

<h3>
  <img src="./gifs/lab.gif" width="55" align="middle"> Selected work
</h3>

| | Project | What it does |
|:--|:--|:--|
|  | **[TrustSee](https://trustsee.com)** | CVE baseline from NVD, OSV, and GHSA, ranked by CISA KEV and EPSS. Website, email, domain, and uptime posture checks, authorized red-team probes, and a dark-web feed. It exposes `scan_repo` over MCP, so Claude and Cursor queue scans without leaving the agent. `Next.js 16` · `React 19` · `Supabase` · `TinyFish` · `Playwright` |
|  | **[ExoMind](https://github.com/zhugez/ExoMind)** | Memory and knowledge runtime. One store serves Pi, Hermes Agent, OpenClaw, and Codex. `Rust` |
|  | **[pi-pulse](https://github.com/zhugez/pi-pulse)** | Five extensions for the Pi coding agent: a loop guard that blocks byte-identical tool calls, a mutation gate, a CRAP-score gate, a comment checker, and in-flight diagnostics for the file being edited. `TypeScript` |
|  | **[stella](https://stella.zhugez.workers.dev)** | IELTS vocabulary site. 7,298 illustrated words with UK and US audio, scheduled with FSRS. `TypeScript` · `Cloudflare Workers` |
|  | **[pingloom](https://github.com/zhugez/pingloom)** | Floating ping and emote wheels for Windows, with experimental macOS support. `Rust` · `Tauri 2` · `Svelte 5` |
|  | **[Cordyceps](https://github.com/zhugez/cordyceps)** | WordPress plugin scanner. It finds the guard a security patch adds, then uses a static AST reachability harness to drop every finding an attacker cannot actually reach. Runs as an OpenClaw skill over Mycelium and Patchstack data. `Python` |

<h3>
  <img src="./gifs/roadsign.gif" width="40" align="middle"> Research and disclosures
</h3>

**Publications.** First author on all four.

| Venue | Title | Status |
|:--|:--|:--|
| AISEI 2026, IEEE | Biometric Identification Through Auditory EEG Signatures | [Published](https://doi.org/10.1109/AISEI68628.2026.11572950). |
| SSRC 2026 | Multimodal Mamba Fusion for Noise-Robust EEG Biometric Identification | [Published](https://ssrc.fit.iuh.edu.vn/conf/article/view/267). |
| APSIPA ASC 2026 | Multimodal Mamba Fusion for Noise-Robust EEG Biometric Identification | Accepted. |
| ATC 2024 | Malware detection with machine learning and deep learning | Presented. |

**Disclosures.** Severity is CVSS.

| Target | Findings | Status |
|:--|:--|:--|
| Telegram for Android | 4 — exported intent handler redirects an OAuth token before authentication (7.1 High)<br>integer truncation in the native verifier (7.5 High)<br>unclamped intent extra switches account before the passcode (5.5 Medium)<br>exported service, local denial of service (5.5 Medium) | Submitted. |
| Patchstack | 2 — broken access control in Upsell Order Bump Offer for WooCommerce (Medium)<br>broken access control in an undisclosed commercial CRM plugin (Medium) | Accepted. |
| IUH | 3 — two High (8.7), one Medium (6.9) | Accepted. |

**Awards.** YSC 2025, Consolation Prize. Certified AppSec Practitioner (CAP).

<h3>
  <img src="./gifs/toolkit.gif" width="55" align="middle"> Toolkit
</h3>

<details open>
  <summary><strong>Languages and libraries</strong></summary>
  <br>
  <img src="https://skillicons.dev/icons?i=js,html,css,sass,c,cpp,cs,java,go,python,ts,rust,latex" alt="Languages and libraries">
</details>

<details open>
  <summary><strong>AI and machine learning</strong></summary>
  <br>
  <img src="https://skillicons.dev/icons?i=sklearn,pytorch,anaconda,tensorflow,opencv" alt="AI and machine learning">
</details>

<details open>
  <summary><strong>Web and interactive applications</strong></summary>
  <br>
  <img src="https://skillicons.dev/icons?i=astro,nextjs,nodejs,fastapi,flask,netlify,bun,react,threejs" alt="Web">
</details>

<details open>
  <summary><strong>Data and storage</strong></summary>
  <br>
  <img src="https://skillicons.dev/icons?i=redis,supabase,mongodb,sqlite,postgres" alt="Data and storage">
</details>

<details open>
  <summary><strong>Infrastructure, tooling, and testing</strong></summary>
  <br>
  <img src="https://skillicons.dev/icons?i=aws,docker,git,powershell,bash,kali,arch,ubuntu,windows,linux,prometheus,grafana,rabbitmq,selenium,postman" alt="Infrastructure and tooling">
</details>

<details open>
  <summary><strong>IDEs, design, and media</strong></summary>
  <br>
  <img src="https://skillicons.dev/icons?i=neovim,vim,notion,obsidian,vscode,visualstudio,idea,ai,ps,pr,ae,figma,blender,ableton" alt="IDEs and design">
</details>

<details open>
  <summary><strong>Microcontrollers and IoT</strong></summary>
  <br>
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi" alt="Microcontrollers and IoT">
</details>

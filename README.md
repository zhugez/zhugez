<div align="center">

<img src="./gifs/hacker_video_animation_opt.gif" alt="security animation" width="220"/>

<br>

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com/?lines=Offensive+Security+Researcher;Vulnerability+Research+%26+Red+Teaming;Binary+RE+%C2%B7+Applied+ML;Rust+%C2%B7+TypeScript+%C2%B7+Python;Coding-Agent+Tooling;Open+to+Collaboration&font=Fira%20Code&center=true&width=480&height=45&duration=3500&pause=800&color=89b4fa" alt="Typing SVG" />
</a>

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-shadowforge-313244?style=flat-square&logo=vercel&logoColor=cdd6f4)](https://shadowforge.vercel.app/)
[![X](https://img.shields.io/badge/X-%40dezzhu1-313244?style=flat-square&logo=x&logoColor=cdd6f4)](https://x.com/dezzhu1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dezzhu-313244?style=flat-square&logo=linkedin&logoColor=89b4fa)](https://www.linkedin.com/in/dezzhu)
[![dev.to](https://img.shields.io/badge/dev.to-zhugez-313244?style=flat-square&logo=devdotto&logoColor=cdd6f4)](https://dev.to/zhugez)

</div>

---

Working on **offensive security**: vulnerability research, red team operations, and security automation.  
Also into binary reverse engineering, security telemetry, and applied ML for defense and verification.  
Open to collaborating on research and building reliable open-source tooling.

## 💥 Security Disclosures & Discoveries

| Target / Ecosystem | Findings & Attack Surface | Severity | Status |
| --- | --- | --- | --- |
| **Telegram for Android** | **TG-01**: Native C++ descriptor truncation in `Utilities.readlinkFd` procfs resolving<br>**TG-02**: Exported `OpenChatReceiver` intent extra forwarding into unauthenticated `LaunchActivity` OAuth flow | **7.5 High**<br><br>**7.1 High** | **Pending Resolve** |
| **WordPress Ecosystem**<br>*([Wordfence Profile](https://www.wordfence.com/threat-intel/vulnerabilities/researchers/zhugez))* | **[CVE-2026-119514](https://www.wordfence.com/threat-intel/vulnerabilities/researchers/zhugez)**: Privilege Escalation & Access Control in *RepairBuddy CRM* (<= 4.1234)<br>**[CVE-2026-123468](https://patchstack.com/database/wordpress/plugin/motors-car-dealership-classified-listings/vulnerability/wordpress-motors-plugin-1-4-128-broken-access-control-vulnerability)**: Broken Access Control in *Motors — Car Dealership* (<= 1.4.128)<br>**[CVE-2026-115431](https://www.wordfence.com/threat-intel/vulnerabilities/researchers/zhugez)**: Broken Access Control in *Upsell Funnel Builder for WooCommerce* (<= 3.1.6) | **6.3 Med**<br><br>**4.3 Med**<br><br>**4.3 Med** | **Published**<br><br>**Published**<br><br>**Published** |
| **IUH Academic System** | 3 findings: Sensitive credential leak (Gitleaks, 8.7), arbitrary sensitive file exposure (8.7), and reflected client-side DOM sink injection (6.9) | **8.7 High**<br>**6.9 Medium** | **Validated & Resolved** |

## 📜 Research & Publications

*First author on all peer-reviewed papers.*

| Venue | Title | Status |
| --- | --- | --- |
| **[AISEI 2026, IEEE](https://jadara.edu.jo/aisei2026/)** | [Biometric Identification Through Auditory EEG Signatures](https://doi.org/10.1109/AISEI68628.2026.11572950) | Published |
| **[SSRC 2026](https://ssrc.fit.iuh.edu.vn/)** | [Multimodal Mamba Fusion for Noise-Robust EEG Biometric Identification](https://ssrc.fit.iuh.edu.vn/conf/article/view/267) | Published |
| **[APSIPA ASC 2026](https://apsipa2026.org/)** | Multimodal Mamba Fusion for Noise-Robust EEG Biometric Identification | Accepted |
| **[ATC 2024, IEEE](https://ieeexplore.ieee.org/xpl/conhome/10908109/proceeding)** | [Windows Malware Detection: Exploring from Machine Learning to Text-Based Deep Learning Approaches](https://ieeexplore.ieee.org/xpl/conhome/10908109/proceeding) | Presented |

## 🏆 Honors & Competitions

| Honor / Recognition | Organization & Context | Year |
| --- | --- | --- |
| 🎓 **Australia-Vietnam Strategic Technologies Scholarship** | Awarded by **University of Technology Sydney (UTS)** for emerging tech research; selected nationwide (AUD 500 grant) | 2025 |
| 🚩 **Global CTF Competitor** | **[Ranked #65 Globally on CTFtime](https://ctftime.org/user/114064)** • **Ranked #30 in WhiteHat Play 11** | Active |
| 🎖️ **YSC Consolation Prize** | Young Scientist Conference — EEG-based biometric identification with deep metric learning | 2025 |

## 📜 Professional Certifications

| Certification | Issuer | Status |
| --- | --- | --- |
| <img src="https://pentestingexams.com/wp-content/uploads/2025/12/cap-exam.webp" width="22" height="22" align="absmiddle"/> **Certified AppSec Practitioner (CAP)** | The SecOps Group | **[Certified](https://github.com/zhugez/Awards-and-Qualifications/blob/main/Certs/LyNgocVu-CertifiedAppSecPractitioner(CAP).pdf)** |
| <img src="https://cwl-main-website.s3.us-east-1.amazonaws.com/images/CRTA-desktop.webp" width="22" height="22" align="absmiddle"/> **Certified Red Team Analyst (CRTA)** | [CyberWarFare Labs](https://cyberwarfare.live/certifications/red-team-analyst-crta) | *In Progress / Pending* |
| <img src="https://portswigger.net/web-security/certification/images/certified-secondary-hero.png" width="22" height="22" align="absmiddle"/> **Burp Suite Certified Practitioner (BSCP)** | [PortSwigger Web Security](https://portswigger.net/web-security/certification) | *In Progress / Pending* |

## 📚 Popular Tech Blogs

- 🖥️ **[Repurposing Remote Desktop Applications as Strategic C2](https://wanderlens.vercel.app/posts/remotedesktopappexploit/)**  
  Exploring lateral movement, token extraction, and covert persistence through abused legitimate remote desktop software.
- ⚡ **[Windows Admin-to-Kernel Elevation of Privilege: CVE-2024-21338](https://wanderlens.vercel.app/posts/cve2024_21338/input/)**  
  Deep dive into the `appid.sys` zero-day kernel exploit, arbitrary read/write primitives, and DKOM-based token stealing.
- 🥷 **[Windows Internals: The Art of Self-Deletion](https://wanderlens.vercel.app/posts/selfdelete/)**  
  Analyzing file-lock bypassing and in-memory NTFS alternate data stream manipulation for clean artifact removal.

## 🛠️ Selected Engineering Work

| Project | Highlights & Capabilities | Stack |
| --- | --- | --- |
| **[TrustSee](https://trustsee.com)** | Multi-faceted agentic security platform: unified attack surface hygiene (TLS, DNS, SPF/DKIM/DMARC), continuous uptime resilience, autonomous agentic red teaming, and threat intelligence. Exposes `scan_repo` over MCP | Next.js 16 · React 19 · Supabase · Playwright · MCP |
| **[ExoMind](https://github.com/zhugez/ExoMind)** | Portable knowledge graph and persistent second-brain memory runtime for AI coding agents (Pi, Hermes, OpenClaw, Codex) | Rust · RocksDB |
| **[Stella](https://github.com/zhugez/Stella)** | Illustrated IELTS vocabulary engine with 7,298 words, native audio, and FSRS spaced repetition scheduling | TypeScript · Cloudflare Workers |
| **[Pingloom](https://github.com/zhugez/Pingloom)** | Lightweight native radial ping and emote wheel overlay for competitive games | Tauri 2 · Svelte 5 · Rust |
| **[Pi-pulse](https://github.com/zhugez/Pi-pulse)** | Runtime extension suite for Pi coding agent: byte-loop guard, mutation gate, CRAP-score gate, and in-flight diagnostics | TypeScript |
| **[Cordyceps](https://github.com/zhugez/Cordyceps)** | WordPress plugin vulnerability scanner featuring AST call-chain reachability analysis | Python |
| **[dross](https://github.com/zhugez/dross)** | Conservative disk cleaner for Fedora and WSL with dry-run verification | Rust |

## Tech stack

<p align="center">
  <img alt="skills" src="https://skillicons.dev/icons?i=ts,js,py,rust,cpp,c,go,react,nextjs,svelte,tauri,workers,postgres,supabase,docker,kali,linux&perline=9">
</p>

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=zhugez&show_icons=true&theme=catppuccin_mocha&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhugez&layout=compact&theme=catppuccin_mocha&hide_border=true" height="150"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=zhugez&theme=catppuccin-mocha&hide_border=true" />
</p>

## Contact

[Blog](https://shadowforge.vercel.app/) · [X](https://x.com/dezzhu1) · [LinkedIn](https://www.linkedin.com/in/dezzhu) · [dev.to](https://dev.to/zhugez)

Open to work & research collaboration.

# BPG Tech News — Week 19 Recap

**May 10, 2026** | Weekly | 28 stories | Generated 9:00 AM MST

<!-- tab: Week in AI -->

## Top Stories

- **[Anthropic Partners with Blackstone, Hellman & Friedman, and Goldman Sachs to Launch $1.5B Enterprise AI Services Firm](https://www.anthropic.com/news/enterprise-ai-services-company)** — Anthropic and three major PE/financial firms launched a $1.5B AI-native enterprise services company that embeds engineers directly inside mid-sized portfolio companies to redesign workflows around Claude agents; founding partners invest ~$300M each, with additional backing from General Atlantic, Apollo, GIC, and Sequoia. Announced the same day as OpenAI's competing vehicle. *Source: Anthropic Blog* *(May 5 — 2 days covered)*

- **[OpenAI Finalizes $10B "Deployment Company" Joint Venture with 19 PE Investors](https://thenextweb.com/news/openai-deployco-finalized-10-billion-joint-venture)** — OpenAI closed a $10B enterprise deployment vehicle (The Deployment Company) backed by TPG, Brookfield, Advent, Bain Capital, and 15 other PE firms; OpenAI guarantees a 17.5% annual return and embeds forward-deployed engineers in client organizations — a Palantir-style model arriving the same day as Anthropic's identical bet. *Source: The Next Web* *(May 5 — 2 days covered)*

- **[Anthropic Doubles Claude Code Rate Limits and Signs SpaceX Colossus 1 Compute Deal](https://www.anthropic.com/news/higher-limits-spacex)** — Anthropic doubled five-hour Claude Code rate limits for Pro, Max, Team, and Enterprise plans, removed peak-hours throttling, and raised Opus API rate limits — backed by a new agreement to use all compute capacity at SpaceX's Colossus 1 data center: 300MW and 220,000+ NVIDIA GPUs available within a month. *Source: Anthropic Blog* *(May 7 + May 9 — 2 days covered)*

- **[Microsoft-OpenAI Partnership Goes Non-Exclusive — OpenAI Can Now Deploy Across AWS and Google Cloud](https://thejournal.com/articles/2026/05/04/microsoft-and-openai-announce-revised-alliance-loosening-exclusive-ties.aspx)** — The 2019 partnership agreement was restructured to make Microsoft's IP license non-exclusive through 2032; OpenAI can now serve products across any cloud provider, the AGI consent clause was removed, and revenue-share payments are capped. Azure remains preferred but is no longer mandatory. *Source: THE Journal* *(May 6)*

- **[OpenAI Launches GPT-5.5 Instant as New Default ChatGPT Model](https://techcrunch.com/2026/05/05/openai-releases-gpt-5-5-instant-a-new-default-model-for-chatgpt/)** — GPT-5.5 Instant replaces GPT-5.3 Instant as the default in ChatGPT, adding search-grounded memory that references past conversations, uploaded files, and Gmail for personalized answers; live for Plus and Pro subscribers. *Source: TechCrunch* *(May 7)*

- **[OpenAI Launches GPT-Realtime-2 and Two New Voice API Models](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/)** — GPT-Realtime-2 scores 15.2% higher on Big Bench Audio, GPT-Realtime-Translate handles live speech translation across 70+ input languages into 13 output languages, and GPT-Realtime-Whisper delivers streaming transcription — all targeting production voice agent workloads. *Source: OpenAI* *(May 8)*

- **[Anthropic Introduces "Dreaming" — Claude Agents Learn from Their Own Mistakes Between Tasks](https://venturebeat.com/technology/anthropic-introduces-dreaming-a-system-that-lets-ai-agents-learn-from-their-own-mistakes)** — A research-preview post-session system for Claude Managed Agents reviews memory stores, merges duplicates, and surfaces recurring patterns after sessions conclude; Harvey reported a 6x task-completion rate improvement in testing, with developers reviewing all proposed memory changes before commit. *Source: VentureBeat* *(May 8)*

- **[White House Prepares Executive Order Requiring Government Vetting of AI Models Before Release](https://www.bloomberg.com/news/articles/2026-05-06/white-house-preps-order-to-boost-ai-security-hassett-says)** — NEC Director Kevin Hassett described an in-progress order that would establish an AI working group to review new models for cybersecurity risk before public release — comparing it to FDA drug approval and citing Anthropic's Mythos model's ability to autonomously weaponize software vulnerabilities as the proximate cause. One or more orders expected within two weeks. *Source: Bloomberg* *(May 8)*

- **[OpenAI Releases GPT-5.5-Cyber in Limited Preview for Approved Security Partners](https://openai.com/index/gpt-5-5-with-trusted-access-for-cyber/)** — A specialized model that can not only generate vulnerability exploitation plans but validate them by launching simulated attacks against target systems, making autonomous red teaming a first-class workflow; access to the most permissive tier requires Advanced Account Security starting June 1. *Source: OpenAI* *(May 9)*

- **[Four Chinese AI Labs Release Frontier-Matching Open-Weights Models in 12 Days](https://press.airstreet.com/p/state-of-ai-may-2026)** — Z.ai's GLM-5.1, MiniMax M2.7, Moonshot's Kimi K2.6, and DeepSeek V4 all achieved comparable performance to Western frontier models on agentic coding benchmarks at lower inference costs within a single 12-day window, directly challenging the prevailing "six to nine months behind" assessment. *Source: Air Street Press* *(May 6)*

## Emerging Themes

### AI Labs Go Enterprise-Direct

Both Anthropic and OpenAI announced billion-dollar deployment vehicles in a single day — Anthropic's $1.5B PE-backed services firm and OpenAI's $10B "Deployment Company" with 19 PE investors. Paired with Sierra's $950M raise at $150M ARR and Anthropic's 10 pre-built Finance Agent templates, the week's signal is unambiguous: the contest for enterprise AI spend has shifted from platform selection to who controls the deployment relationship. The Palantir-style embedded-engineer model is now the explicit strategy of both leading labs, putting them in direct competition with the world's major consulting firms.

### Agentic AI as Attack Surface

Thirteen CVEs against a single AI agent platform (OpenClaw) in two days, six IAM bypass exploits in production coding agents, a critical Oracle MCP Server CVE, and the world's first confirmed AI-directed cyberattack all arrived in the same week. The UK AISI's updated estimate — frontier AI cyber-offense capability doubling every four months — connects the threat model to the product releases. The more capable and autonomous AI systems become, the larger and more exploitable their attack surfaces. GPT-5.5-Cyber's launch on Friday, designed to automate red teaming, underscores that both offense and defense are being industrialized simultaneously.

### AI Governance Moves From Intent to Enforcement

Connecticut passed a sweeping AI accountability bill, Maryland became the first state to ban AI-driven food pricing, Pennsylvania filed a criminal suit against Character.AI after a chatbot fraudulently claimed to be a licensed psychiatrist, and the White House advanced an executive order that would impose pre-release model vetting. Six intelligence agencies from five nations issued their first joint guidance on agentic AI in the same week. The Stanford AI Index's finding that the public is dramatically more skeptical of AI's benefits than practitioners adds political pressure that will accelerate this transition from voluntary guidelines to binding enforcement.

### Chinese Open-Weights Compression

Four major Chinese AI labs released frontier-matching open-weights models inside 12 days, at lower inference costs. This is not a single event — it represents a structural shift in the competitive landscape. Open-weights distribution also complicates export control enforcement and accelerates capability diffusion globally, a dynamic the White House EO effort appears to be responding to in part.

---

<!-- tab: Breakthroughs Recap -->

## Breakthrough Moments

- **[Mayo Clinic AI Detects Pancreatic Cancer Up to 3 Years Before Diagnosis in Landmark Validation Study](https://newsnetwork.mayoclinic.org/discussion/mayo-clinic-ai-detects-pancreatic-cancer-up-to-3-years-before-diagnosis-in-landmark-validation-study/)** — The REDMOD model, trained on radiomics from CT scans, identified 73% of prediagnostic pancreatic cancers at a median of 16 months before diagnosis — nearly double specialist radiologist detection rates on the same scans. In cases more than two years pre-diagnosis, the model caught nearly three times as many cancers. Published in Gut; advances to clinical trial via the AI-PACED program. *Source: Mayo Clinic News Network* *(May 5)*

- **[Rowhammer Attacks on NVIDIA GDDR6 GPUs Achieve Full Host System Compromise](https://arstechnica.com/security/2026/04/new-rowhammer-attacks-give-complete-control-of-machines-running-nvidia-gpus/)** — Three independent research teams at IEEE Security and Privacy 2026 demonstrated that Rowhammer bit-flips in GDDR6 memory on NVIDIA Ampere and Ada Lovelace GPUs can chain into full CPU privilege escalation, yielding a root shell on the host machine from a compromised GPU workload. Named variants: GDDRHammer, GeForge, and a third targeting the RTX A6000. Cards with GDDR6X and GDDR7 are unaffected; enabling ECC or IOMMU restricts the attack surface. *Source: Ars Technica* *(May 6 + May 8)*

- **[World's First Recorded AI-Directed Cyberattack Targeted Mexican Government](https://www.darkreading.com/ics-ot-security/worlds-first-ai-driven-cyberattack-couldnt-breach-ot-systems)** — Between December 2025 and February 2026, an unknown group used Claude Code to generate an exploitation framework from scratch and autonomously guided each attack step against nine Mexican government entities — including the federal tax authority and National Electoral Institute — stealing millions of tax and property records. The attackers failed to bridge from IT to OT at a municipal water utility but demonstrated full AI-directed exploitation at scale for the first time on record. *Source: Dark Reading* *(May 9)*

- **[Dirty Frag (CVE-2026-43284, CVE-2026-43500): Universal Linux Kernel LPE — PoC Grants Root in One Command](https://thehackernews.com/2026/05/linux-kernel-dirty-frag-lpe-exploit.html)** — Researcher Hyunwoo Kim chained two vulnerabilities in the ESP and RxRPC in-place decryption fast paths to build a universal local privilege escalation affecting all Linux servers running kernel 4.14+ (since 2017). A working PoC achieves root in a single command; temporary mitigation is to unload the esp4, esp6, and rxrpc kernel modules. *Source: The Hacker News* *(May 8)*

---

<!-- tab: Cyber Weekly -->

## Persistent Threats

- **[PAN-OS CVE-2026-0300 (CVSS 9.3) Zero-Day — State-Sponsored Exploitation Since April 9, Patch May 13](https://thehackernews.com/2026/05/palo-alto-pan-os-flaw-under-active.html)** — A memory corruption bug in PAN-OS Captive Portal allows unauthenticated remote attackers to execute arbitrary code as root on internet-exposed PA-Series and VM-Series firewalls. Unit 42 attributes active exploitation to a likely state-sponsored cluster (CL-STA-1132) injecting shellcode into nginx workers since April 9 — over five weeks of silent exploitation before disclosure. 5,800+ instances remain exposed globally; no patch until May 13. Mitigate by restricting or disabling the User-ID Authentication Portal immediately. *Source: The Hacker News / BleepingComputer* *(May 6 + May 9)*

- **[CVE-2026-41940: cPanel Auth Bypass Mass-Exploited in "Sorry" Ransomware — 44,000+ IPs Compromised](https://www.bleepingcomputer.com/news/security/critrical-cpanel-flaw-mass-exploited-in-sorry-ransomware-attacks/)** — Attackers are mass-exploiting a critical authentication bypass in cPanel and WHM to breach hosting servers and deploy Sorry ransomware; Shadowserver reports 44,000+ compromised IPs with exploitation dating to late February. The ransomware uses ChaCha20 + RSA-2048, making decryption without the private key effectively impossible. Apply the emergency patch immediately. *Source: BleepingComputer* *(May 5 + May 8)*

- **[OpenClaw AI Agent Platform: 13 CVEs in 2 Days (CVSS 8.1–8.8) — Sandbox Escape, SSRF, File Read, Plugin Trust Bypass](https://nvd.nist.gov/vuln/detail/CVE-2026-42434)** — NVD published 13 HIGH-severity vulnerabilities across the 210k+ GitHub star OpenClaw AI agent platform over two days: eight on May 6 (covering sandbox escape, env variable injection, SSRF, arbitrary file read, auth bypass, and plugin trust bypass) and five on May 7 (env var denylist bypass, bearer token staleness, Matrix authorization bypass, exec allowlist bypass, Zalo SSRF). Upgrade to v2026.4.22 or later. *Source: NVD* *(May 6 + May 7)*

- **[CVE-2026-31431 "Copy Fail" — Linux Root Escalation Added to CISA KEV, Affects Every Major Distro Since 2017](https://www.bleepingcomputer.com/news/security/cisa-says-copy-fail-flaw-now-exploited-to-root-linux-systems/)** — CISA added this logic flaw in the Linux kernel's algif_aead cryptographic module to the KEV catalog after active exploitation began one day after Theori published a PoC; any unprivileged local user can gain root via a 732-byte Python script on Ubuntu, Amazon Linux, RHEL, and SUSE. FCEB agencies must patch by May 15; Kubernetes clusters and cloud Linux workloads are at significant risk. *Source: BleepingComputer* *(May 5)*

- **[Ivanti EPMM CVE-2026-6973 Zero-Day Added to CISA KEV — Federal Agencies Patch Deadline: May 10](https://www.bleepingcomputer.com/news/security/cisa-gives-feds-four-days-to-patch-ivanti-flaw-exploited-as-zero-day/)** — CISA added this Ivanti EPMM improper input validation flaw to KEV on May 7 with a 72-hour deadline; confirmed under active targeted exploitation in versions 12.8.0.0 and prior. Patched in 12.6.1.1, 12.7.0.1, and 12.8.0.1. *Source: BleepingComputer* *(May 8)*

- **[MOVEit Automation Critical Auth Bypass CVE-2026-4670 — 1,400+ Exposed Instances Including U.S. Government](https://www.bleepingcomputer.com/news/security/moveit-automation-customers-warned-to-patch-critical-auth-bypass-flaw/)** — Progress patched a zero-interaction auth bypass in MOVEit Automation; 1,400+ instances are exposed on Shodan including U.S. state and local government deployments. Given Clop's prior mass exploitation of MOVEit Transfer, treat this as critical-to-patch. Patch to 2025.1.5, 2024.1.8, or 2025.0.9+. *Source: BleepingComputer* *(May 6)*

## Week's Incidents

- **[ShinyHunters Breaches Canvas LMS, Disrupts Finals at 8,800+ Schools](https://time.com/article/2026/05/08/canvas-cyber-attack-shinyhunters-hack-what-to-know/)** — ShinyHunters defaced Canvas login portals on May 7, replacing them with ransom demands after claiming 280 million records exfiltrated from Instructure. Institutions in the US, UK, Australia, New Zealand, Sweden, and the Netherlands reported disruptions during end-of-year exams; ransom payment deadline is May 12. *Source: TIME / BleepingComputer* *(May 6 arc → May 9 escalation)*

- **[World's First AI-Directed Cyberattack: Nine Mexican Government Entities Breached Dec 2025–Feb 2026](https://www.darkreading.com/ics-ot-security/worlds-first-ai-driven-cyberattack-couldnt-breach-ot-systems)** — An unknown threat group used Claude Code to generate an exploitation framework from scratch and directed each attack step autonomously, stealing millions of tax and property records before failing to cross from IT to OT at a municipal water utility. *Source: Dark Reading* *(May 9)*

- **[Medtronic Confirms ShinyHunters Breach — 9 Million Medical Records Claimed Stolen](https://www.securityweek.com/medtronic-hack-confirmed-after-shinyhunters-threatens-data-leak/)** — Medtronic confirmed an intrusion limited to specific corporate IT environments after ShinyHunters claimed theft of 9M+ records and terabytes of corporate data; ShinyHunters subsequently removed Medtronic from its leak site, which can indicate active negotiations. *Source: SecurityWeek* *(May 5)*

- **[DAEMON Tools Official Installer Trojanized Since April 8, Backdoor Deployed to Thousands of Systems](https://www.bleepingcomputer.com/news/security/daemon-tools-trojanized-in-supply-chain-attack-to-deploy-backdoor/)** — Attackers compromised DAEMON Tools' official distribution channel, replacing legitimate disk imaging installers with backdoored versions silently deploying since April 8; any installation from the official site in the past month is suspect. *Source: BleepingComputer* *(May 6)*

- **[Covenant Health Breach: 480,000 Individuals Impacted via Qilin Ransomware](https://therecord.media/covenant-health-breach-qilin)** — The Qilin ransomware group claimed responsibility for a breach at Covenant Health exposing personal and health-related records; Covenant operates hospitals and care facilities across Tennessee and Virginia. *Source: The Record* *(May 9)*

- **[Trellix Discloses Data Breach: Attackers Accessed Portion of Source Code Repository](https://www.bleepingcomputer.com/news/security/trellix-discloses-data-breach-after-source-code-repository-hack/)** — The cybersecurity vendor confirmed attackers gained access to a portion of its internal source code repository, raising concern about targeted vulnerability discovery in Trellix's own security products. *Source: BleepingComputer* *(May 6)*

- **[Ransomware Negotiator Pleads Guilty to Working as Double Agent for the Gang He Was Hired to Counter](https://www.schneier.com/blog/archives/2026/05/a-ransomware-negotiator-was-working-for-a-ransomware-gang.html)** — A professional ransomware incident responder pleaded guilty to secretly working for the same gang whose victims he was negotiating for — feeding intelligence to attackers and sabotaging payment negotiations, exposing a structural conflict-of-interest in the unregulated incident response intermediary space. *Source: Schneier on Security* *(May 6 + May 8)*

## By the Numbers

- **13** CVEs published against OpenClaw AI agent platform in 2 days
- **44,000+** IPs compromised in the cPanel "Sorry" ransomware campaign
- **280M** records claimed stolen in the Canvas LMS / Instructure breach
- **5,800+** PAN-OS instances exposed globally with an unpatched zero-day for 5+ weeks
- **480,000** individuals affected in Covenant Health / Qilin ransomware breach
- **9 entities** targeted in the world's first AI-directed cyberattack campaign
- **4 months** — current doubling time for frontier AI cyber-offense capability (UK AISI)
- **44 days** — current average time-to-exploit from CVE disclosure (down from 700 days in 2020)
- **3 CISA KEV additions** this week: CVE-2026-31431 (Linux), CVE-2026-6973 (Ivanti EPMM), active exploitation confirmed on PAN-OS CVE-2026-0300

---

*Sources: May 5, May 6, May 7, May 8, May 9 dailies synthesized | Pre-fetch: OSINT available (CISA KEV, NVD); Spotify/Apple Charts unavailable — Podcasts tab omitted*
*Generated by BPG Tech News Agent*

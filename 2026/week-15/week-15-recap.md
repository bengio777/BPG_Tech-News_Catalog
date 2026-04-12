# BPG Tech News — Week 15 Recap

**April 12, 2026** | Weekly | 35 stories | Generated 8:00 AM MST

<!-- tab: Week in AI -->

## Top Stories

- **[Anthropic Unveils Claude Mythos Preview via Project Glasswing](https://www.anthropic.com/glasswing)** — The week's defining story: Anthropic's restricted Claude Mythos Preview model achieves a 72.4% success rate generating working zero-day exploits across all major operating systems and browsers — compared to near-zero for Opus 4.6. Access is limited to 11 partners including AWS, Apple, Cisco, CrowdStrike, Google, JPMorganChase, Microsoft, Nvidia, and Palo Alto Networks. Anthropic privately briefed government officials that Mythos-class capabilities make large-scale cyberattacks significantly more likely this year. *Source: Anthropic*

- **[TechCrunch Follow-Up: Mythos Found a 17-Year-Old FreeBSD RCE and a 27-Year-Old OpenBSD Bug](https://techcrunch.com/2026/04/07/anthropic-mythos-ai-model-preview-security/)** — Additional details published April 12 confirm the depth of Mythos's autonomous vulnerability discovery: engineers with no formal security training prompted the model overnight and received complete functional exploits by morning. The model identified thousands of high- and critical-severity vulnerabilities during testing. *Source: TechCrunch*

- **[Anthropic Discloses $30B Revenue Run Rate, Secures 3.5 GW Compute with Google and Broadcom](https://www.anthropic.com/news/google-broadcom-partnership-compute)** — Anthropic's annualized revenue has surpassed $30 billion, up from roughly $9 billion at end of 2025, with over 1,000 enterprise customers now spending more than $1M annually; the company simultaneously locked in 3.5 gigawatts of next-generation TPU capacity beginning in 2027 on top of 1 GW already in service. *Source: Anthropic*

- **[Meta Launches Muse Spark — First Closed-Source Model from Meta Superintelligence Labs](https://ai.meta.com/blog/introducing-muse-spark-msl/)** — The first model from the AI unit assembled under Alexandr Wang following Meta's $14.3B Scale AI acquisition, Muse Spark is closed-source with no committed open-release date — a significant departure from Meta's Llama lineage. The natively multimodal reasoning model supports tool-use, visual chain-of-thought, and multi-agent orchestration. *Source: Meta AI*

- **[Q1 2026 Global Startup Funding Hits $297 Billion, Shattering All Prior Records](https://techcrunch.com/2026/04/01/startup-funding-shatters-all-records-in-q1/)** — Global venture funding in Q1 2026 reached $297 billion — a 2.5x increase over the prior quarterly record — driven by OpenAI's $122 billion round at an $852 billion valuation and a wave of mega-rounds in AI infrastructure. *Source: TechCrunch*

- **[OpenAI Alumni Launch Zero Shot, a New $100M AI-Focused Venture Fund](https://techcrunch.com/2026/04/06/openai-alums-have-been-quietly-investing-from-a-new-potentially-100m-fund/)** — Zero Shot is targeting a $100M close and has already made early investments in AI startups; founders include former OpenAI researchers backing the next generation of frontier-adjacent companies. *Source: TechCrunch*

- **[Cybersecurity in the Age of Instant Software](https://www.schneier.com/blog/archives/2026/04/cybersecurity-in-the-age-of-instant-software.html)** — Bruce Schneier's piece ran across two dailies (Apr 8 and Apr 12) and frames the week's AI-security collision precisely: AI-generated software created on demand for individual users replaces vetted, maintained products with millions of one-off, unaudited apps — an attack surface the security community is unprepared for. *Source: Schneier on Security*

- **[Sen. Sanders Publicly Debates Claude on AI and Privacy Policy](https://www.schneier.com/blog/archives/2026/04/sen-sanders-talks-to-claude-about-ai-and-privacy.html)** — A sitting senator used a frontier AI model publicly to engage on regulatory matters; Schneier notes Claude performed well on the policy questions, marking a shift in how AI enters the legislative conversation. *Source: Schneier on Security*

---

## Emerging Themes

### AI as an Offensive Cyber Weapon

This week crossed a threshold. Anthropic Mythos achieved a 72.4% success rate on zero-day exploit generation — a capability that didn't exist in any publicly available model a year ago. But Mythos was only the headline. Flowise's CVSS 10.0 RCE (CVE-2025-59528) exploited an `unsafe Function()` evaluation pattern in an AI orchestration platform; Hashgraph Guardian repeated the identical pattern (CVE-2026-39911, CVSS 8.8); and the Weaxor ransomware gang exploited React Server Components deserialization to go from initial access to file encryption in under one minute. AI is now simultaneously the target of attackers, the tool attackers use, and the new attack surface. Schneier's "instant software" thesis explains why this compounds: AI-generated code proliferating at scale without standard review cycles gives attackers an ever-expanding low-scrutiny target pool.

### Supply Chain Compromise Reaches Enterprise Scale

Three major supply chain incidents in a single week: DPRK's Sapphire Sleet backdoored the Axios npm package (versions 1.14.1 and 0.30.4, 100M+ weekly downloads) with a cross-platform RAT downloader; TeamPCP's Trivy campaign reached its apex with both the EU Commission breach (92 GB stolen from 29+ entities) and Cisco (300+ private GitHub repos cloned including AI product source code); and a malicious litellm 1.82.8 package deployed a PyPI backdoor targeting AI development environments specifically. The throughline across all three: attackers have shifted from targeting individual organizations to compromising the tools everyone uses to build software. Any team that hasn't audited its dependency pins and container scanning toolchain this week should do so now.

### AI Investment Reaches Escape Velocity

Anthropic's $30B ARR disclosure (up from $9B in Q4 2025), Q1 2026 global venture hitting $297 billion (2.5x any prior record), Meta's $14.3B Scale AI acquisition yielding its first model, and the Zero Shot fund channeling OpenAI alumni capital into the next wave — all in the same week. The compounding structure is visible: more capital attracts more enterprise customers, which funds more compute, which enables more capable models, which expands the attack surface that security teams are racing to address. Anthropic's 1,000+ enterprise customers each spending over $1M annually is the clearest signal that AI has moved from pilot to infrastructure budget.

---

<!-- tab: Breakthroughs Recap -->

## Breakthrough Moments

- **[Anthropic Mythos Preview: AI Autonomously Discovers and Chains Zero-Days Across Every Major OS and Browser](https://www.anthropic.com/glasswing)** — The week's defining breakthrough wasn't a paper — it was a product. Mythos achieved a 72.4% success rate generating working exploits for zero-day vulnerabilities, identified a 27-year-old OpenBSD crash bug and a 17-year-old FreeBSD RCE (CVE-2026-4747) during testing, and delivered complete functional exploits to engineers with no formal security background overnight. The model was restricted to 11 vetted partners via Project Glasswing because Anthropic assessed general release as an unacceptable dual-use risk. This is the first frontier AI model explicitly withheld from public release on security grounds — not safety grounds. *Source: Anthropic / TechCrunch*

- **[The AI Scientist-v2: First Fully AI-Authored Paper Clears Formal Peer Review](https://arxiv.org/abs/2504.08066)** — Sakana AI's system autonomously proposed hypotheses, ran experiments, analyzed results, and wrote a complete scientific manuscript using agentic tree search; the paper independently passed peer review at an ICLR workshop — the first verified case of a fully AI-authored paper clearing formal academic review without human co-authorship. *Source: arXiv*

- **[Meta Muse Spark: Natively Multimodal Reasoning Model from Meta Superintelligence Labs](https://ai.meta.com/blog/introducing-muse-spark-msl/)** — The first output from the unit assembled under Alexandr Wang represents a genuine architectural shift for Meta: a closed-source model optimized for multi-agent orchestration and visual chain-of-thought, targeting deployment across Meta's 3+ billion-user ecosystem. Meta's decision to launch closed rather than open signals that the Llama open-release model no longer applies to Meta's most capable frontier work. *Source: Meta AI*

- **[React2Shell (CVE-2025-55182): Critical React Server Components Deserialization RCE Exploited in Under One Minute](https://www.bleepingcomputer.com/news/security/critical-react2shell-flaw-exploited-in-ransomware-attacks/)** — The Weaxor ransomware gang exploited unauthenticated RCE in the React RSC Flight deserialization protocol to achieve initial access and deploy ransomware in under one minute. Any Next.js or React application using Server Components is at-risk pending a patch; this is the first major ransomware campaign exploiting an AI-adjacent framework vulnerability at this speed. *Source: BleepingComputer*

---

<!-- tab: Cyber Weekly -->

## Persistent Threats

- **[TeamPCP / UNC6780 Supply Chain Campaign — Cisco Source Code Stolen](https://www.bleepingcomputer.com/news/security/cisco-source-code-stolen-in-trivy-linked-dev-environment-breach/)** — Google GTIG now tracks TeamPCP as UNC6780. This week's escalation: TeamPCP used credentials harvested via their Trivy container scanning compromise to breach Cisco's internal development environment, cloning 300+ private GitHub repos containing AI product source code and unreleased items; multiple AWS keys were stolen. Combined with the EU Commission breach (Apr 7, 92 GB stolen from 29+ entities), TeamPCP has now compromised the EU Commission, Cisco, Checkmarx, LiteLLM, and Telnyx in a single campaign that began in March. *Source: BleepingComputer*

- **[OpenClaw Privilege Escalation Cluster: 10 CVEs (CVSS 8.1–8.8) Across Two Days](https://nvd.nist.gov/vuln/detail/CVE-2026-35638)** — Apr 11 published four CVEs targeting session management, device pairing, and gateway plugin subsystems; Apr 12 added six more including an unvalidated WebView JavascriptInterface RCE (CVE-2026-35643, CVSS 8.8) and scope escalation during reconnect (CVE-2026-35663, CVSS 8.8). The two-day sprint across 10 CVEs suggests a coordinated audit disclosure. Patch to OpenClaw 2026.3.25 immediately. *Source: NVD*

- **[APT28/Forest Blizzard Harvested Microsoft OAuth Tokens from 18,000+ Networks via Router DNS Hijacking](https://krebsonsecurity.com/2026/04/russia-hacked-routers-to-steal-microsoft-office-tokens/)** — GRU unit APT28 compromised residential and SOHO routers to redirect DNS through attacker-controlled servers, siphoning OAuth authentication tokens from Microsoft Office users across 18,000+ networks without deploying any malware on target systems. Microsoft's Operation Masquerade identified 200+ organizations and 5,000 consumer devices in the collection network before FBI disruption. *Source: Krebs on Security*

- **[DPRK Sapphire Sleet Backdoored Axios npm Package — 100M+ Weekly Downloads](https://www.microsoft.com/en-us/security/blog/2026/04/01/mitigating-the-axios-npm-supply-chain-compromise/)** — Microsoft Threat Intelligence attributed the compromise of Axios versions 1.14.1 and 0.30.4 to Sapphire Sleet; the malicious versions injected a cross-platform RAT downloader targeting Windows, macOS, and Linux. Any CI/CD pipeline that hasn't pinned Axios to a clean version is still at risk. *Source: Microsoft Security Blog*

- **[AI Orchestration Platform RCE Anti-Pattern: Flowise (CVSS 10.0) and Hashgraph Guardian (CVSS 8.8)](https://www.bleepingcomputer.com/news/security/max-severity-flowise-rce-vulnerability-now-exploited-in-attacks/)** — Both platforms contain arbitrary code execution via unsafe `Function()` evaluation of user-supplied JavaScript — Flowise via the CustomMCP node's unauthenticated `/api/v1/node-load-method/customMCP` endpoint, Hashgraph Guardian via its Custom Logic policy block worker. 12,000–15,000 Flowise instances are exposed online. Any AI orchestration platform using dynamic `Function()` evaluation for user-supplied logic is a high-priority audit target. *Source: BleepingComputer / NVD*

- **[Storm-1175 Medusa Ransomware: Intrusion to Deployment in Under 24 Hours](https://www.microsoft.com/en-us/security/blog/2026/04/06/storm-1175-focuses-gaze-on-vulnerable-web-facing-assets-in-high-tempo-medusa-ransomware-operations/)** — China-linked financially motivated group exploiting n-day and zero-day vulnerabilities in web-facing assets; healthcare, education, and finance sectors in the US, UK, and Australia heavily targeted. *Source: Microsoft Security Blog*

## Week's Incidents

- **[ChipSoft Ransomware Attack Disrupts Patient Records for 80% of Dutch Hospitals](https://www.bleepingcomputer.com/news/security/healthcare-it-solutions-provider-chipsoft-hit-by-ransomware-attack/)** — HiX on-premise, HiX SaaS, and the Patient Portal taken down; 11 hospitals disconnected from ChipSoft systems; Z-CERT confirmed a "data incident" with possible unauthorized patient data access. Responsible group not publicly identified. *Source: BleepingComputer*

- **[React2Shell (CVE-2025-55182): Weaxor Ransomware via React Server Components Deserialization](https://www.bleepingcomputer.com/news/security/critical-react2shell-flaw-exploited-in-ransomware-attacks/)** — Unauthenticated RCE in RSC Flight deserialization protocol exploited to deploy ransomware in under one minute; Cobalt Strike for C2, Windows Defender disabled, `.WEAX` extensions appended. Any Next.js or React application using Server Components is at-risk pending a patch. *Source: BleepingComputer*

- **[Hims & Hers Data Breach via ShinyHunters Zendesk Social Engineering](https://www.bleepingcomputer.com/news/security/hims-and-hers-warns-of-data-breach-after-zendesk-support-ticket-breach/)** — ShinyHunters impersonated IT support to obtain credentials and MFA codes from two employees, accessing Zendesk tickets containing names, email addresses, phone numbers, physical addresses, and treatment category data for customers who contacted support February 2025–February 2026. Medical records not affected. *Source: BleepingComputer*

- **[Bitcoin Depot Discloses $3.6 Million Theft from Company Wallets](https://www.bleepingcomputer.com/news/security/crypto-atm-giant-bitcoin-depot-says-hackers-stole-36-million-from-its-wallets/)** — Attackers transferred 50.9 BTC (~$3.665M) from digital asset settlement accounts on March 23 before being blocked; customer-facing platforms unaffected. *Source: BleepingComputer*

- **[Adobe Acrobat Reader CVE-2026-34621 (CVSS 8.6): Prototype Pollution Enables Arbitrary Code Execution via Malicious PDF](https://nvd.nist.gov/vuln/detail/CVE-2026-34621)** — Affects versions through 24.001.30356 and 26.001.21367. Patch to the latest Acrobat release immediately. *Source: NVD*

- **[Python Supply-Chain Compromise: Malicious litellm 1.82.8 Deployed .pth Backdoor on Install](https://www.schneier.com/blog/archives/2026/04/python-supply-chain-compromise.html)** — A .pth file in the malicious PyPI package executed a backdoor silently at `pip install` time; litellm is widely used in AI/LLM application stacks. The malicious version has been removed from PyPI, but any environment that ran `pip install litellm` this week should be audited. *Source: Schneier on Security (via Truesec)*

## By the Numbers

- **10** — OpenClaw CVEs disclosed across two days (CVSS 8.1–8.8)
- **CVSS 10.0** — Flowise RCE (CVE-2025-59528), maximum severity, actively exploited
- **100M+** — Weekly downloads of Axios npm at time of DPRK supply chain compromise
- **92 GB** — Data stolen from European Commission via Trivy supply chain attack
- **80%** — Dutch hospitals disrupted by ChipSoft ransomware
- **18,000+** — Networks compromised by APT28 router DNS hijacking campaign
- **300+** — Cisco GitHub repos cloned by TeamPCP
- **<24 hours** — Storm-1175 intrusion-to-ransomware deployment dwell time
- **<1 minute** — React2Shell Weaxor time from initial access to file encryption
- **15,000** — Exposed Flowise instances online at time of disclosure
- **$3.6M** — Bitcoin Depot theft (50.9 BTC)

---

<!-- tab: Podcasts -->

## News-Connected Episodes

- **[Anthropic's $30B Ramp, Mythos Doomsday, OpenClaw Ankled, Iran War Ceasefire, Israel's Influence](https://open.spotify.com/episode/6lywn8r0CQua2HD05BwwH8)** — Show: *All-In Podcast*. Connects to: Anthropic Mythos/Project Glasswing (week's #1 story), Anthropic $30B revenue run rate, OpenClaw CVE cluster — the three biggest week-15 stories covered in a single episode with Brad Gerstner joining.

- **[Risky Business #832 — Anthropic unveils magical 0day computer God](https://risky.biz/RB832/)** — Show: *Risky Business*. Connects to: Anthropic Mythos/Project Glasswing, supply chain security — Patrick Gray and Adam Boileau provide the security-community deep dive on what Mythos's capability ceiling actually means for defenders.

- **[#208: Q1 Trends Briefing — Model Release Frenzy, AI Lobbying, Anthropic v. U.S. Government, and the Rise of OpenClaw](https://open.spotify.com/episode/4xDTws2Erz2GEU9Mk4PcyE)** — Show: *The Artificial Intelligence Show*. Connects to: OpenClaw CVE cluster, Anthropic vs. US government tensions, Q1 2026 AI funding record — 150+ stories distilled into 10 ranked trends covering exactly the themes that defined this week.

- **[Wall Street CEOs Summoned to Discuss Anthropic AI Risks](https://open.spotify.com/episode/4oFhI5ZdcoOqL5SWv9EbT3)** — Show: *Bloomberg Technology*. Connects to: Anthropic Mythos systemic risk — US Treasury Secretary Bessent and Fed Chair Powell convened Wall Street leaders over Mythos cyber threat implications.

- **[It's Crunch Time: Ajeya Cotra on RSI & AI-Powered AI Safety Work](https://open.spotify.com/episode/49hBvRoveKMTrbSKYlL7Nd)** — Show: *Cognitive Revolution*. Connects to: Anthropic Mythos safety implications, AI acceleration debate — Ajeya Cotra on recursive self-improvement and the "crunch time" window; directly relevant to what Glasswing access restrictions signal about Anthropic's internal risk calculus.

- **[Who Controls AI Acceleration? Vitalik Buterin and Guillaume Verdon Debate](https://open.spotify.com/episode/4832mazF3lsVTA9JvF0uVx)** — Show: *a16z Podcast*. Connects to: Anthropic Mythos controlled access, AI power concentration concerns — the philosophical counterpoint to Project Glasswing's closed-partner model: who should control when and how AI capabilities are deployed.

## Trending in Tech Podcasts

- **[Fear and loathing at OpenAI](https://open.spotify.com/episode/1upiYxcbilFjLEdBJpehMg)** — Show: *The Vergecast*. David Pierce and Nilay Patel on OpenAI's internal dynamics via The New Yorker; relevant context for reading the OpenAI/Anthropic competitive positioning in the week's funding and safety stories.

- **[CoreWeave, Meta Strike $21 Billion for AI Computing](https://open.spotify.com/episode/2jwkXn0z2NA8R5mGKfrwrJ)** — Show: *Bloomberg Technology*. Connects to: Meta Muse Spark compute infrastructure, Anthropic secondary share sale dynamics — context on the infrastructure layer driving this week's model launches.

- **[Humanize AI before it dehumanizes us, with Dr. Rana el Kaliouby at SXSW](https://open.spotify.com/episode/2A5o4rCTPG3su3ij5qYrOe)** — Show: *Masters of Scale*. Live SXSW conversation on keeping humans centered as AI capabilities accelerate — a counterweight to the week's capability-first announcements.

## Discovery Pick

- **[Extreme Harness Engineering for Token Billionaires: 1M LOC, 1B toks/day, 0% human code, 0% human review — Ryan Lopopolo, OpenAI Frontier & Symphony](https://open.spotify.com/episode/0JRaE28Y7W3lBXcfn6YQvX)** — Show: *Latent Space*. Connects to: "Age of Instant Software" theme, Mythos zero-day implications — Ryan Lopopolo discusses a production codebase that is 100% AI-generated with zero human code review, processing 1 billion tokens per day. A concrete, operating instantiation of exactly the attack surface Schneier warned about this week. Not a regular charter, highly technical, genuinely different from the week's news podcasts.

---

*Sources: April 7, 8, 11, 12 dailies synthesized | Pre-fetch: Spotify API, Apple Charts, CISA KEV, NVD*
*Generated by BPG Tech News Agent*

# BPG Tech News — Week 22 Recap

**May 25–31, 2026** | Weekly | 35 stories | Generated 2:30 PM MST

<!-- tab: Week in AI -->

## Top Stories

- **[Anthropic Raises $65B Series H at $965B Valuation — Largest AI Fundraise in History](https://www.anthropic.com/news/series-h)** — Anthropic closed a $65 billion Series H co-led by Altimeter, Dragoneer, Greenoaks, and Sequoia, disclosing $47 billion in annualized run-rate revenue (including $15B from hyperscalers) and announcing chip supply partnerships with Micron, Samsung, and SK Hynix. The company described this as its final private fundraise before a potential IPO. *Sources: Anthropic Blog, TechCrunch* *(Appeared: May 29, May 31)*

- **[Claude Opus 4.8: Dynamic Workflows, 84% Browser Automation, First to Complete Super-Agent Benchmark](https://www.anthropic.com/news/claude-opus-4-8)** — Released 41 days after Opus 4.7, Opus 4.8 adds dynamic workflows for large-scale agentic tasks, a fast mode 3× cheaper at 2.5× speed, approximately 4× better code-flaw detection versus 4.7, and ships three new API capabilities: effort control, mid-task system prompt updates, and dynamic workflows. Scores 84% on Online-Mind2Web browser automation and exceeds 10% on the Legal Agent Benchmark all-pass standard — firsts for both. *Sources: Anthropic Blog, TechCrunch* *(Appeared: May 29, May 31)*

- **[Cognition Raises $1B at $26B Valuation — Devin AI Writes 90% of the Company's Own Codebase](https://techcrunch.com/2026/05/27/ai-coding-startup-cognition-raises-1b-at-25b-pre-money-valuation/)** — Cognition, maker of autonomous AI software engineer Devin, closed $1 billion at a $26 billion post-money valuation led by Lux Capital, General Catalyst, and 8VC. The company reports $492 million ARR growing 50% month-over-month, with enterprise customers including Mercedes-Benz, NASA, and Goldman Sachs. *Source: TechCrunch* *(Appeared: May 30)*

- **[DuckDuckGo Installs Surge 30% as Users Reject Google's AI-Forced Search Overhaul](https://techcrunch.com/2026/05/26/duckduckgo-installs-are-up-30-as-users-reject-being-force-fed-googles-ai-search/)** — Following Google I/O's replacement of blue-link results with continuous AI agents, DuckDuckGo reported U.S. app installs up an average of 18.1% week-over-week during May 20-25, peaking at 30.5% on May 25. *Source: TechCrunch* *(Appeared: May 29)*

- **[Meta Launches Meta One AI Subscriptions: $7.99/mo and $19.99/mo Plans](https://techcrunch.com/2026/05/27/meta-officially-launches-instagram-facebook-and-whatsapp-subscriptions-with-more-to-come-including-ai-plans/)** — Meta rolled out paid tiers for Instagram, Facebook, and WhatsApp under the "Meta One" brand, with higher-capacity AI queries and deeper reasoning for complex tasks unlocked at both price points. *Source: TechCrunch* *(Appeared: May 29)*

- **[OpenAI Publishes Frontier Governance Framework Aligned to CA Transparency Act and EU AI Act](https://openai.com/index/openai-frontier-governance-framework/)** — OpenAI released a formal governance document mapping its Preparedness Framework to California's Transparency in Frontier AI Act and the EU AI Act's Code of Practice for GPAI, with explicit coverage of risk assessment across cyber offense, CBRN, manipulation, and loss-of-control scenarios. *Source: OpenAI* *(Appeared: May 29)*

- **[OpenAI Expands Codex with Computer Use on Windows, Updates GPT-5.5 Instant](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)** — OpenAI rolled out Computer Use on Windows inside Codex, enabling agents to see, click, and type in Windows applications while debugging, plus remote continuation from mobile or Mac and new Codex Profiles tracking token usage. *Source: OpenAI* *(Appeared: May 31)*

## Emerging Themes

**Anthropic's Defining Week.** Week 22 was unambiguously Anthropic's week. The $65 billion Series H — the largest AI fundraise in history — landed alongside the Opus 4.8 release, a new Milan office, and a research team using Anthropic's Mythos model to discover the first publicly documented AI-assisted kernel exploit on Apple Silicon. No other company had this breadth of news in a single week, and the timing of the fundraise with a major model release signals a deliberate IPO runway narrative: Anthropic is stacking proof points simultaneously rather than sequentially.

**Autonomous Coding Goes Mainstream.** Two datapoints collided this week that would have seemed implausible 18 months ago: Devin AI now authors 90% of Cognition's own codebase (with $492M ARR to show it works for enterprise), and Opus 4.8 shipped 4× better code-flaw detection alongside dynamic workflows designed specifically for long-horizon software engineering tasks. The gap between "AI assists coding" and "AI is the primary engineer" closed materially in Week 22. Enterprises like Mercedes-Benz and NASA are already customers — this is no longer early adopter territory.

**Search Fragmentation Has Begun.** Google I/O's all-in pivot to AI-generated search results is producing measurable defection. DuckDuckGo's 30.5% install spike on May 25 — the day after Google's announcement — is a leading indicator, not an anomaly. The market for traditional search alternatives (DuckDuckGo, Kagi, Perplexity) is growing precisely because Google's UX decision was forced on users rather than optional. This is the first concrete evidence that the AI search bet carries real churn risk at scale.

---

<!-- tab: Breakthroughs Recap -->

## Breakthrough Moments

![Story visual](https://substackcdn.com/image/fetch/$s_!TJW7!,w_1200,h_675,c_fill,f_jpg,q_auto:good,fl_progressive:steep,g_auto/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F2c731d5e-68ca-4054-894f-659601de6a66_2048x1536.jpeg)
- **[AI-Assisted Kernel Exploit: Anthropic's Mythos Model Discovers First Public macOS M5 Memory Corruption Vulnerability](https://blog.calif.io/p/first-public-kernel-memory-corruption)** — A research team at Calif directed Anthropic's Mythos model through hypothesis generation, code analysis, and proof-of-concept development to identify and exploit a kernel memory corruption bug on Apple's M5 chip — the first publicly documented AI-assisted kernel-level vulnerability discovery on Apple Silicon. The paper documents the full discovery-to-exploit chain. This marks a meaningful threshold: AI as an active research instrument in offensive security, not just a pattern-matching assistant. *Source: Calif Research Blog*

- **[Claude Opus 4.8 Sets New Ceilings on Browser Automation and Agentic Benchmarks](https://www.anthropic.com/news/claude-opus-4-8)** — Opus 4.8 scored 84% on Online-Mind2Web — the highest computer-use score recorded — and became the first model to complete every case on the Super-Agent benchmark end-to-end, and the first to exceed 10% on the Legal Agent Benchmark all-pass standard. The 4× reduction in unflagged coding flaws over Opus 4.7 represents a step-change in practical coding reliability, not just benchmark performance. *Source: Anthropic Blog*

- **[Devin AI Authors 90% of Cognition's Own Codebase at $492M ARR](https://techcrunch.com/2026/05/27/ai-coding-startup-cognition-raises-1b-at-25b-pre-money-valuation/)** — Cognition disclosed that its Devin autonomous software engineer now writes 90% of the company's own production codebase, alongside $492 million in annualized recurring revenue growing 50% month-over-month. The self-consumption data point is the most concrete proof yet that fully autonomous AI software engineering is operationally viable at production scale. *Source: TechCrunch*

- **[Sesame Launches Four Adaptive Voice AI Agents with Persistent Memory Across 39 Countries](https://techcrunch.com/2026/05/28/sesame-the-conversational-ai-startup-from-oculus-founders-launches-its-ios-app/)** — Sesame, founded by Oculus veterans, debuted four distinct AI agents (Maya, Miles, Simone, and Charlie) each with persistent memory, individual personalities, and real-time voice conversation — the first consumer launch that treats AI voice agents as persistent relationships rather than stateless sessions. *Source: TechCrunch*

---

<!-- tab: Cyber Weekly -->

## Persistent Threats

- **[TeamPCP Supply Chain Campaign — Wave 4 Escalates to GitHub's Own Infrastructure](https://therecord.media/github-confirms-teampcp-hack-customers-unaffected)** — The week's most consequential threat story ran across all three dailies. TeamPCP (UNC6780) exfiltrated approximately 3,800 GitHub internal repositories via a trojanized Nx Console VS Code extension published to the official marketplace. Wave 4 documents simultaneous operations across npm, PyPI, and GitHub Actions; a self-replicating worm in the durabletask PyPI package; and trojanization of an officially Microsoft-published Python SDK. The group is listing the GitHub source code for $50,000. The escalation from open-source ecosystem attacks to Microsoft's own official toolchain marks a new phase. *Sources: The Record, The Hacker News, Phoenix Security* *(Appeared: May 29, 30, 31)*

- **[ACR Stealer Targets AI Users via Fake Claude Interface — AI Brand Impersonation Becomes Malware Vector](https://isc.sans.edu/diary/33018)** — SANS ISC identified an active campaign distributing ACR credential stealer through a fraudulent webpage designed to impersonate the Claude AI interface, targeting browser-stored credentials, crypto wallets, and saved passwords. The story appeared in both May 29 and May 31 dailies as additional analysts confirmed the campaign's persistence. AI brand impersonation is an established delivery mechanism, not an edge case. *Source: SANS ISC* *(Appeared: May 29, May 31)*

- **[CISA KEV Surge — Three Major Additions in One Week Across PAN-OS, Microsoft Defender, and Exchange OWA](https://thehackernews.com/2026/05/pan-os-globalprotect-authentication.html)** — Three high-severity vulnerabilities reached CISA KEV status in Week 22: CVE-2026-0257 (PAN-OS GlobalProtect, CVSS 9.8, pre-auth bypass, patch deadline June 19), CVE-2026-41091 and CVE-2026-45498 (Microsoft Defender zero-days, patch deadline June 3), and CVE-2026-42897 (Microsoft Exchange OWA XSS, federal deadline May 29 — already past). All three are under confirmed active exploitation. *Sources: The Hacker News, BleepingComputer* *(Appeared: May 30, May 31)*

- **[WordPress Plugin CVE Cluster — Six+ High-Severity Vulnerabilities Published Across the Week](https://nvd.nist.gov/vuln/detail/CVE-2026-9009)** — NVD published a sustained cluster of CVSS 8.1-8.8 WordPress plugin vulnerabilities across May 28-30: CVE-2026-9009 (Crawlomatic — unauthenticated RCE), CVE-2026-9227 (GutenBee — arbitrary file upload), CVE-2026-7802 and CVE-2026-6226 (Frontend Admin — auth bypass and privilege escalation), CVE-2025-11993 (WooCommerce Infinite Scroll — PHP Object Injection), and CVE-2026-6075 (Media Library Assistant — unauthenticated CSRF). Site operators running any of these plugins should verify patch status immediately. *Source: NVD* *(Appeared: May 29, May 30)*

## Week's Incidents

- **[cPanel CVE-2026-41940: 44,000+ Servers Compromised in Mass "Sorry" Ransomware Campaign — CVSS 9.8](https://www.bleepingcomputer.com/news/security/critrical-cpanel-flaw-mass-exploited-in-sorry-ransomware-attacks/)** — A pre-authentication bypass in cPanel/WHM is being mass-exploited across at least 44,000 servers, deploying "Sorry" ransomware — a Go-based Linux encryptor that appends a .sorry extension and wipes backups. The vulnerability was exploited in the wild two months before the patch shipped. *Source: BleepingComputer*

- **[Ghost CMS CVE-2026-26980: 700+ Sites Hijacked for Large-Scale ClickFix Malware Campaign — CVSS 9.4](https://www.bleepingcomputer.com/news/security/ghost-cms-sql-injection-flaw-exploited-in-large-scale-clickfix-campaign/)** — Threat actors exploited an unauthenticated SQL injection flaw in Ghost CMS to steal admin API keys, inject malicious JavaScript into articles, and serve fake Cloudflare ClickFix prompts — compromising 700+ domains including university portals, SaaS companies, and media sites. Upgrade to Ghost 6.19.1 or later and rotate Admin API keys. *Source: BleepingComputer*

- **[Charter Communications Confirms 4.9M Account Breach by ShinyHunters — CPNI and Salesforce Records Exposed](https://www.bleepingcomputer.com/news/security/charter-confirms-data-breach-after-shinyhunters-extortion-threat/)** — ShinyHunters gained access to Charter's Salesforce instance via a vishing attack targeting an employee's Microsoft Entra account, exfiltrating 4.9 million records containing customer names, email addresses, phone numbers, plan details, and CPNI data. *Source: BleepingComputer*

- **[Foxconn Confirms Cyberattack — Nitrogen Ransomware Claims 8TB Exfiltration from North American Factories](https://therecord.media/foxconn-confirms-cyberattack-north-american-factories)** — Foxconn confirmed a cyberattack on its North American manufacturing operations, with the Nitrogen ransomware gang claiming responsibility and asserting it stole 8 terabytes of data including technical specifications from technology clients. *Source: The Record*

- **[Covenant Health Confirms 478K Patient Breach — Qilin Ransomware Group Named](https://therecord.media/covenant-health-breach-qilin)** — Covenant Health disclosed a breach affecting approximately 478,000 patients attributed to the Qilin ransomware group, which has significantly expanded its healthcare targeting in 2026. *Source: The Record*

- **[CISA Contractor Exposed AWS GovCloud Keys and Internal Build Architecture in Public GitHub Repo](https://krebsonsecurity.com/2026/05/cisa-admin-leaked-aws-govcloud-keys-on-github/)** — A CISA contractor maintained a public GitHub repository containing credentials to multiple highly privileged AWS GovCloud accounts along with detailed documentation on CISA's internal software build and deployment processes. CISA has revoked credentials and taken the repository offline. *Source: Krebs on Security*

- **[Netherlands Seizes 800 Servers, Arrests Two for Operating Russian Cyberattack and Influence Infrastructure](https://krebsonsecurity.com/2026/05/netherlands-seizes-800-servers-arrests-2-for-aiding-cyberattacks/)** — Dutch authorities arrested the co-owners of two related hosting companies and seized 800 servers used by Russia-linked actors to conduct cyberattacks and influence operations inside the EU — the largest single-seizure cyber enforcement action in Dutch history. *Source: Krebs on Security*

- **[Microsoft Exchange OWA Zero-Day CVE-2026-42897 Under Active Exploitation — CISA KEV, No Permanent Patch](https://www.bleepingcomputer.com/news/microsoft/microsoft-warns-of-exchange-zero-day-flaw-exploited-in-attacks/)** — CVE-2026-42897 (CVSS 8.1) is an OWA cross-site scripting flaw in on-premises Exchange Server 2016, 2019, and SE being exploited via crafted emails that execute malicious JavaScript in the victim's authenticated browser session, enabling session token theft and mailbox impersonation. No permanent patch exists — the Exchange Emergency Mitigation Service applies a URL Rewrite workaround automatically on supported deployments. *Source: BleepingComputer*

- **[West Pharmaceutical Services Files SEC Incident Report — Data Stolen and Systems Encrypted](https://therecord.media/west-pharmaceutical-warns-of-ransomware-attack-impacting-operations)** — West Pharmaceutical Services disclosed via SEC filing that threat actors breached its network on May 4, exfiltrated data, and encrypted systems, raising continued concern about pharmaceutical supply chain cyber exposure. *Source: The Record*

## By the Numbers

- **3** CISA KEV additions in one week (PAN-OS, Microsoft Defender ×2, Exchange OWA)
- **44,000+** servers compromised in cPanel "Sorry" ransomware campaign
- **700+** domains hijacked in Ghost CMS ClickFix campaign
- **4.9M** records in Charter Communications breach
- **478,000** patients affected in Covenant Health breach
- **8TB** claimed exfiltration from Foxconn North American operations
- **3,800+** GitHub internal repositories exfiltrated by TeamPCP
- **151** Chrome 148 vulnerabilities patched (22 Critical, 66 use-after-free)
- **6+** WordPress plugin CVEs published in a single week (CVSS 8.1-8.8)
- **CVSS 9.8** — highest severity of the week, shared by cPanel CVE-2026-41940 and PAN-OS CVE-2026-0257

---

<!-- tab: Podcasts -->

## News-Connected Episodes

- **[The Age of Async Agents — Cognition's Walden Yan & OpenInspect's Cole Murray](https://open.spotify.com/episode/5ROYcszG8M5rjXqbyhfRuu)** — Show: *Latent Space*. Connects to: Cognition's $1B raise and Devin's autonomous coding capabilities — the episode digs into how async agent architectures enable the long-horizon software engineering tasks Cognition is commercializing.

- **[Why $1B Exits are Dead](https://open.spotify.com/episode/7fENTLnNVumG8RhcbDD19g)** — Show: *a16z Podcast*. Connects to: the week's AI mega-round context — Anthropic at $965B and Cognition at $26B illustrate exactly the scale shift the episode argues has made $1B outcomes table stakes rather than targets.

- **[SK Hynix, Micron Join $1 Trillion Market Cap Club](https://open.spotify.com/episode/4jBdyqXAeq1hSSdxWufEDS)** — Show: *Bloomberg Technology*. Connects to: Anthropic's Series H announcement of strategic chip supply partnerships with Micron and SK Hynix — two of the same companies crossing the $1T threshold this week.

- **[What your Oura ring won't tell you](https://open.spotify.com/episode/4wCXKzeDY6B6oFwznjtCNs)** — Show: *Smashing Security*. Connects to: the CISA contractor AWS GovCloud key leak — the episode dedicates a segment to this exact story, covering the breadth of exposed credentials and the implications for government security posture.

- **[#216: Google I/O, Musk v. OpenAI Verdict, Andrej Karpathy Joins Anthropic & Meta Layoffs](https://open.spotify.com/episode/14RZiwdZAdx3FeMCEIssUW)** — Show: *The Artificial Intelligence Show*. Connects to: DuckDuckGo's 30% surge and the Google AI search disruption — the episode unpacks the full Google I/O AI search announcement that triggered the defection data reported this week.

- **[All Compute Is Food: Palisade's Jeffrey Ladish on AI Shutdown Resistance, Self-Replication & Ecology](https://open.spotify.com/episode/3QhQ7B3M7DNDOUuAMhZ2V6)** — Show: *Cognitive Revolution*. Connects to: the Anthropic Mythos AI kernel exploit discovery — as AI models demonstrate capability to find and exploit security vulnerabilities autonomously, Ladish's research on AI self-preservation and spread behavior is directly relevant context.

## Trending in Tech Podcasts

- **[How To Build Superintelligence Inside Your Company](https://open.spotify.com/episode/23lX5nM1jvBXm805zoxxq0)** — Show: *Y Combinator*. YC's Pete Koomen on how they built AI as the operating system for the whole organization — timely given the week's Devin and Opus 4.8 agentic capability announcements.

- **[China Expands Travel Curbs to Top AI Talent](https://open.spotify.com/episode/50ZdU3lfbSl0N693xaTdYP)** — Show: *Bloomberg Technology*. Covers China's tightening grip on AI talent mobility — geopolitical context for the compute and model capability race underscored by Anthropic's chip partnership announcements.

- **[ESM: The Bitter Lesson is Coming for Proteins — Alex Rives, BioHub](https://open.spotify.com/episode/2mcD6mLCvDumEQkYzu8IZp)** — Show: *Latent Space*. Scale-first protein language models at BioHub — an adjacent frontier to the AI capability gains documented across the week's briefings.

## Discovery Pick

- **[Your Biggest Lever: Designing your AI Career for Maximum Impact, with 80,000 Hours founder Ben Todd](https://open.spotify.com/episode/08zPTFfr59pGd47q7ZfZAd)** — Show: *Cognitive Revolution*. Ben Todd, co-founder of 80,000 Hours, applies the organization's career capital framework to the current AI moment — mapping where individual career moves have the highest expected impact on AI outcomes. A rare episode that reasons seriously about career positioning in the AI transition rather than just cheerleading it, and directly relevant to anyone rethinking their professional trajectory in the context of weeks like this one.

---

*Sources: May 29, May 30, May 31 dailies synthesized | Pre-fetch: Spotify API (2026-05-29), Apple Podcasts Charts, CISA KEV, NVD*
*Generated by BPG Tech News Agent*

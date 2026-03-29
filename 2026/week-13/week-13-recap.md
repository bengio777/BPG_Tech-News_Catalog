# BPG Tech News — Week 13 Recap

**March 23–29, 2026** | Weekly | 45 stories | Generated 9:00 AM MST

<!-- tab: Week in AI -->

## Top Stories

- **[Anthropic Accidentally Leaks Claude Mythos — A New Model Tier Above Opus 4.6](https://fortune.com/2026/03/26/anthropic-says-testing-mythos-powerful-new-ai-model-after-data-leak-reveals-its-existence-step-change-in-capabilities/)** — A misconfigured public database exposed ~3,000 unpublished Anthropic assets including a draft launch announcement for Claude Mythos, a model reportedly outperforming Opus 4.6 on reasoning, coding, and cybersecurity benchmarks. Anthropic confirmed the leak, acknowledged the model exists, and said it is restricting access to vetted cybersecurity defense customers. *Source: Fortune* *(Mon + Wed + Sat — 3 days)*

- **[Anthropic Launches Claude Computer Use for macOS](https://www.cnbc.com/2026/03/24/anthropic-claude-ai-agent-use-computer-finish-tasks.html)** — Claude can now autonomously open macOS apps, navigate browsers, run developer tools, and execute tasks triggered remotely from a phone, limited to Pro/Max subscribers with per-action permission prompts. Paired with the week's Channels launch, Anthropic shipped two major agent capability upgrades in four days before the Mythos leak upended the narrative. *Source: CNBC* *(Tue)*

- **[Anthropic Ships Claude Code Channels — Control Your Agent from Telegram or Discord](https://venturebeat.com/orchestration/anthropic-just-shipped-an-openclaw-killer-called-claude-code-channels)** — Built on MCP, Channels lets developers send commands to a running Claude Code session from any mobile device. Senders must be explicitly allowlisted; background polling is invoked with the --channels flag. Available in research preview for Pro, Max, Team, and Enterprise. *Source: VentureBeat* *(Mon)*

- **[Arm Launches First In-House CPU in 35 Years — 136-Core AGI Chip for AI Inference](https://www.cnbc.com/2026/03/24/arm-launches-its-own-cpu-with-meta-as-first-customer.html)** — After exclusively licensing chip designs since 1990, Arm introduced the AGI CPU: a 136-core, 3nm data center processor claiming 2x performance per rack versus x86 at lower capital cost, with Meta, OpenAI, Cloudflare, and SAP as launch customers. Meta co-developed the chip alongside its own MTIA accelerators. *Source: CNBC / Arm Newsroom* *(Wed + Sat — 2 days)*

- **[OpenAI Shuts Down Sora, Cancels $1B Disney Deal, Raises $10B at $120B Valuation](https://variety.com/2026/digital/news/openai-shutting-down-sora-video-platform-1236698277/)** — Wednesday was OpenAI's heaviest news day of the year: Sora discontinued after six months and low adoption, the Disney licensing deal scrapped, a $10B fundraise from MGX/Coatue/Thrive finalized at $120B, a new model codenamed "Spud" disclosed, CEO Altman restructuring to shift safety oversight to other executives, and the OpenAI Foundation committing $1B to scientific research. *Source: Variety / Bloomberg / The Information* *(Wed)*

- **[Musk Unveils Terafab — $25B Tesla/SpaceX/xAI Chip Factory Targeting One Terawatt of Compute](https://techcrunch.com/2026/03/22/elon-musk-unveils-chip-manufacturing-plans-for-spacex-and-tesla/)** — Announced at the Seaholm Historic Power Plant in Austin, Terafab consolidates chip design, lithography, fabrication, memory, packaging, and testing at Giga Texas North Campus. First product: Tesla's AI5 chip targeting late 2026 small-batch production. 80% of capacity allocated to space applications. *Source: TechCrunch* *(Tue)*

- **[Supermicro Co-Founder Arrested for $2.5B Nvidia Chip Smuggling to China](https://fortune.com/2026/03/23/supermicro-cofounder-china-nvidia-iran/)** — Wally Liaw and two colleagues charged with routing $510M in Nvidia-packed servers through a Southeast Asian intermediary to China; Fortune connected the arrest to Supermicro's prior 2013 Iran export violations, revealing a pattern of compliance failures. Supermicro stock fell 25%+. *Source: Fortune* *(Mon)*

- **[Trump Administration Publishes National AI Legislative Framework](https://www.whitehouse.gov/articles/2026/03/president-donald-j-trump-unveils-national-ai-legislative-framework/)** — The White House released the first coordinated federal AI policy blueprint of the Trump administration, outlining regulatory structure, U.S. AI leadership strategy, and broad American participation in AI-driven economic growth. *Source: The White House* *(Mon)*

- **[Apple Confirms WWDC 2026, June 8–12, Framing Around "AI Advancements" and iOS 27](https://techcrunch.com/2026/03/23/apple-wwdc-june-8-12-ai-advancements-siri-developers-conference/)** — Apple's most AI-forward WWDC framing to date; expected announcements include the Gemini-powered Siri overhaul, agentic Xcode coding tools, and personal-context AI features. Gemini-powered Siri itself slipped past iOS 26.4 and is now targeting iOS 26.5 beta. *Source: TechCrunch / 9to5Mac* *(Mon + Tue)*

- **[Amazon Acquires Fauna Robotics, Entering Consumer Humanoid Robot Market](https://www.bloomberg.com/news/articles/2026-03-24/amazon-acquires-fauna-robotics-entering-consumer-humanoid-market)** — First direct Amazon entry into consumer humanoid robots, giving Alexa and fulfillment AI a domestic hardware platform. Puts Amazon in competition with Figure AI and Boston Dynamics. *Source: Bloomberg* *(Wed)*

- **[Figma Launches AI Agent Tools with use_figma MCP Tool in Beta](https://x.com/figma/status/2036434766661296602)** — AI models can now design directly on a live Figma canvas via a use_figma MCP tool and agent skills, reading, writing, and iterating on design files without leaving Figma. *Source: Figma* *(Wed)*

## Emerging Themes

**The AI Hardware Race Is Now the Main Event**

Three stories in week 13 reframed AI hardware from background infrastructure to the central competitive battleground. Arm's move — breaking with 35 years of pure-licensing to build and sell its own CPU — signals that the architectures underlying AI inference are being redesigned from scratch, not adapted from prior-gen silicon. Simultaneously, Musk's $25B Terafab bet on vertical integration (design through packaging under one roof) and the Supermicro arrest (revealing the lengths state actors will go to acquire Nvidia silicon) together show that whoever controls AI compute controls the race. The chip layer is being contested at every level: by startups, nation-states, and the hyperscalers who are increasingly building their own.

**Anthropic Builds Toward Full Autonomy — Faster Than It's Announcing**

Claude Code Channels, macOS computer use, and the leaked Mythos model trace a coherent trajectory: Claude is gaining action surfaces (remote command, local OS control) faster than Anthropic is publicly releasing them. Channels connects a running agent to mobile; computer use gives it hands; Mythos, if the leaked materials are accurate, represents capabilities Anthropic is explicitly holding back from general access due to cybersecurity risk. The week's sequence — two agent launches followed by a leak confirming a third, more capable model — suggests Anthropic's public roadmap lags its internal one by at least a generation.

**OpenAI's Strategic Reset**

All of Wednesday's OpenAI headlines point in one direction: the company is consolidating and refocusing. Sora is dead. The Disney deal is gone. Spud is in development but safety oversight has been redistributed away from Altman. The $10B fundraise and $1B Foundation commitment suggest capital availability is not the constraint — internal prioritization is being reset. The simultaneous disclosure of Altman shifting safety responsibilities drew scrutiny given OpenAI's standing commitments; whether the restructure reflects growth, distraction, or something else is a question the company has not yet answered.

---

## By the Numbers

- **$10B** — OpenAI fundraise finalized at $120B valuation
- **$25B** — Terafab chip factory investment
- **$2.5B** — Value of Nvidia silicon in Supermicro smuggling case
- **$1B** — OpenAI Foundation commitment to AI-driven science
- **136 cores** — Arm AGI CPU core count (3nm, TSMC)
- **35 years** — Time since Arm last built its own chip
- **<1%** — Frontier AI score on ARC-AGI-3 versus 100% human baseline

---

<!-- tab: Breakthroughs Recap -->

## Breakthrough Moments

- **[ARC-AGI-3: Frontier AI Scores Below 1% Where Humans Score 100%](https://arxiv.org/abs/2603.24621)** — The ARC Prize Foundation released ARC-AGI-3, requiring agents to explore novel turn-based environments, infer goals, build internal models of dynamics, and plan without explicit instructions. The gap — below 1% AI vs. 100% human — is not a measurement artifact. It defines a specific capability frontier that current architectures, including frontier models, cannot cross: adaptive reasoning in genuinely novel environments without pre-trained task familiarity. The benchmark will become the defining target of the next wave of agent research. *Source: arXiv*

- **[Arm AGI CPU — 35-Year Licensing Model Abandoned for In-House Silicon](https://newsroom.arm.com/news/arm-agi-cpu-launch)** — Arm's first proprietary CPU is not an incremental product — it is a structural break. For 35 years Arm's business model was architecture licensing; the AGI CPU signals that the company believes the inference hardware market is large enough and differentiated enough to justify vertical integration. The 136-core 3nm design targeting AI inference with Meta, OpenAI, and Cloudflare as launch customers puts Arm in direct competition with Nvidia, AMD, and Google TPUs, compressing the number of viable inference hardware stacks. *Source: Arm Newsroom*

- **[Mistral Open-Sources Voxtral TTS — 4B-Parameter Speech Model with 90ms Latency](https://mistral.ai/news/voxtral-tts)** — Voxtral TTS achieves competitive quality in a 4B-parameter model: 9 languages, 90ms time-to-first-audio, 3-second voice cloning, and CC BY NC 4.0 open weights. At $0.016 per 1,000 characters via API it undercuts ElevenLabs on price while matching on quality claims. Open-weight TTS at this parameter count suggests the commodity floor for speech synthesis is dropping faster than the specialized voice providers anticipated. *Source: Mistral AI*

- **[Claude Computer Use for macOS — Agents With Hands on Local Software](https://www.cnbc.com/2026/03/24/anthropic-claude-ai-agent-use-computer-finish-tasks.html)** — Computer use on macOS extends agent autonomy to local applications rather than just browser environments. The ability to open apps, fill spreadsheets, and execute multi-step tasks via mobile trigger closes the gap between AI model capability and real-world workflow automation. Anthropic's caution (per-action permission, no sensitive data) reflects awareness that local computer access changes the risk profile significantly. *Source: CNBC*

- **[M-Trends 2026: Initial Access Handoff Compressed to 22 Seconds](https://www.securityweek.com/m-trends-2026-initial-access-handoff-shrinks-from-hours-to-22-seconds/)** — Mandiant's annual report, grounded in 500,000+ incident investigation hours, documents the collapse of defender response windows from 8+ hours in 2022 to 22 seconds in 2025. Pre-staged tooling deployed during first compromise removes the reconnaissance phase entirely. The report also introduces "recovery denial" ransomware that targets backup infrastructure — the last viable fallback in a standard incident response — rather than production systems. *Source: SecurityWeek*

---

<!-- tab: Cyber Weekly -->

## Persistent Threats

**TeamPCP / CanisterWorm (Mon + Wed + Sat — 3 days)**

The week's most persistent threat story ran continuously across four days. TeamPCP, first documented via the March 19 Trivy supply chain compromise, escalated every 48 hours. By Monday the self-propagating CanisterWorm had expanded the attack surface to 47 npm packages, using Internet Computer blockchain canisters as tamperproof dead-drop C2. By Wednesday, Krebs reported a geopolitically-targeted Kubernetes wiper payload zeroing clusters on Iranian systems — a significant escalation from credential theft. By Saturday, The Hacker News documented five total ecosystems compromised: GitHub Actions, Docker Hub, npm, OpenVSX, and PyPI.

The LiteLLM backdoor on March 24 was the campaign's highest-impact action: 3.4M daily downloads, ~3 hours of live malicious packages, a three-stage payload (credential harvester → Kubernetes lateral movement → persistent systemd backdoor). Any environment that ran `pip install litellm` without version pinning between 10:39–16:00 UTC on March 24 should be treated as fully compromised.

**NVD Router Wave (Mon + Tue — 2 days)**

More than 17 CVSS 8.8 CVEs were published across two consecutive days targeting consumer and SMB routers: D-Link DIR-513, UTT HiPER 1200GW/1250GW, Tenda A18 Pro/FH451/F453/AC21, Linksys MR9600, and Belkin F9K1122. All carry public proof-of-concept exploits. Attack vectors are remote and unauthenticated via stack-based buffer overflow or OS command injection. Most affected models have no patch available — network segmentation or replacement is the only mitigation.

## Week's Incidents

- **[LiteLLM v1.82.7–1.82.8 Backdoored via TeamPCP Supply Chain Attack — 3.4M Daily Downloads](https://www.bleepingcomputer.com/news/security/popular-litellm-pypi-package-compromised-in-teampcp-supply-chain-attack/)** — Three-stage payload: credential harvester (SSH keys, cloud creds, Kubernetes secrets, .env files), Kubernetes lateral movement toolkit, persistent systemd backdoor. Malicious packages live for ~3 hours. *Source: BleepingComputer*

- **[Crunchyroll Investigates Breach — 6.8M Records via Third-Party Zendesk Vendor](https://www.bleepingcomputer.com/news/security/crunchyroll-probes-breach-after-hacker-claims-to-steal-68m-users-data/)** — Threat actor claims 8M Zendesk ticket records via compromise of Telus India; 6.8M unique emails, IPs, usernames, and ticket content. $5M ransom demanded. Crunchyroll confirmed the incident is limited to customer service data. *Source: BleepingComputer*

- **[Aura Confirms Breach — 900,000 Marketing Contacts via Vishing Attack](https://www.bleepingcomputer.com/news/security/aura-confirms-data-breach-exposing-900-000-marketing-contacts/)** — ShinyHunters compromised an employee account via vishing for ~1 hour, exfiltrating names, emails, home addresses, and phone numbers. ShinyHunters claims 12GB total including internal corporate data. *Source: BleepingComputer*

- **[Proton Mail Provided Payment Metadata to Swiss Authorities — FBI Used It to Unmask Activist](https://www.404media.co/proton-mail-helped-fbi-unmask-anonymous-stop-cop-city-protestor/)** — Court records confirm Proton handed payment metadata under Swiss legal compulsion; Swiss authorities shared with FBI, who identified a Stop Cop City activist. Proton's privacy guarantees do not extend to payment records compelled under Swiss law. *Source: 404 Media*

- **[LangChain and LangGraph Flaws Expose Files, Secrets, and Databases (CVE-2025-68664, CVSS 9.3)](https://thehackernews.com/2026/03/langchain-langgraph-flaws-expose-files.html)** — Three CVEs in frameworks with 84M+ combined weekly downloads: CVE-2025-68664 (CVSS 9.3, deserialization of untrusted data), CVE-2026-34070 (CVSS 7.5, path traversal in prompt loading), CVE-2025-67644 (CVSS 7.3, SQLite injection in LangGraph checkpoint). *Source: The Hacker News*

## Active CVEs

- **CVE-2025-32975 (CVSS 10.0)** — Quest KACE SMA, actively exploited since March 9. Full auth bypass, Mimikatz drop, domain controller pivot via RDP. Patch to 13.0.385 / 13.1.81 / 13.2.183 / 14.0.341+.
- **CVE-2026-21992 (CVSS 9.8)** — Oracle Identity Manager, unauthenticated RCE. Possible in-wild exploitation. Patch immediately across identity infrastructure.
- **CVE-2026-3055 (CVSS 9.3)** — Citrix NetScaler ADC/Gateway, memory leak via SAML IDP. Patch to 14.1-66.59+ or 13.1-62.23+.
- **CVE-2026-33017 (CVSS 9.3)** — Langflow RCE, CISA KEV, exploited within 20 hours of disclosure. No credentials required, one HTTP request. Patch to v1.9.0; federal deadline April 8.
- **CVE-2025-53521** — F5 BIG-IP APM RCE, CISA KEV, federal remediation deadline March 30.
- **CVE-2026-22719 (CVSS 8.1)** — VMware Aria Operations, CISA KEV, federal patch deadline was March 24.

## By the Numbers

- **22 seconds** — Initial access handoff speed per M-Trends 2026 (down from 8+ hours in 2022)
- **CVSS 10.0** — Highest severity of week: CVE-2025-32975 (Quest KACE SMA, actively exploited)
- **3.4M** — Daily downloads of compromised LiteLLM packages
- **5 ecosystems** — TeamPCP scope: GitHub Actions, Docker Hub, npm, OpenVSX, PyPI
- **47 npm packages** — CanisterWorm expansion after initial Trivy compromise
- **17+** — Consumer/SMB router CVEs published across two days (all CVSS 8.8+, all with public PoCs)
- **6.8M** — Crunchyroll customer records stolen via Zendesk vendor
- **900K** — Aura breach records
- **70+** — Russian firms targeted by Bearlyfy/GenieLocker ransomware since January 2025
- **4 CISA KEV additions** — VMware Aria, Quest KACE, Langflow, F5 BIG-IP

---

<!-- tab: Podcasts -->

## News-Connected Episodes

- **[Emil Michael: Iran, Anthropic and the Future of AI at the Pentagon](https://open.spotify.com/episode/5iFDMBYs7FNszLLWaUZ3mB)** — Show: *a16z Podcast*. Connects to: Anthropic's agent capability launches and the Claude Mythos restrictions for defense customers; frames how AI labs are engaging with government and defense use cases. *Released March 13*

- **[Meta to Deploy Homegrown Chips, Uber to Offer Zoox Rides](https://open.spotify.com/episode/4xoLOSuS2b4vQZIQIsVM5K)** — Show: *Bloomberg Technology*. Connects to: Arm AGI CPU launch and the AI hardware race — Meta co-developed the Arm chip and this episode covers Meta's broader silicon strategy. *Released March 11*

- **[NVIDIA's AI Engineers: Agent Inference at Planetary Scale — Nader Khalil (Brev), Kyle Kranen (Dynamo)](https://open.spotify.com/episode/6n78hqHN0Cy5jnEuRaDJmz)** — Show: *Latent Space*. Connects to: AI hardware and inference infrastructure themes; Dynamo is directly relevant to the inference stack that Arm's AGI CPU targets. *Released March 10*

- **[How not to steal $46 million from the US government](https://open.spotify.com/episode/1of9PMnc5n56CD8pVc2zRY)** — Show: *Smashing Security*. Connects to: Week's cybersecurity themes — supply chain attacks, fraud, and M-Trends 2026 findings on attacker speed and sophistication. *Released March 12*

- **[Palantir CEO Alex Karp on the Zero-Sum AI Race](https://open.spotify.com/episode/3P8OYFu2TH5aZVlEX6OTIx)** — Show: *a16z Podcast*. Connects to: Musk's Terafab announcement, Supermicro chip smuggling, and the Trump AI framework — Karp's framing of AI as geopolitical competition directly echoes this week's hardware and policy stories. *Released March 12*

## Trending in Tech Podcasts

- **[Rewriting the Rules: The SEC & CFTC on Crypto, IPOs & the Future of American Markets](https://open.spotify.com/episode/0grVGMNJiS3oSdslaGKn55)** — Show: *All-In Podcast*. Relevant background to OpenAI's $10B fundraise at $120B and its Q4 2026 IPO trajectory. *Released March 11*

- **[Retrieval After RAG: Hybrid Search, Agents, and Database Design — Simon Hørup Eskildsen of Turbopuffer](https://open.spotify.com/episode/0Uhfa80vUBQ9vQPjn6uE6n)** — Show: *Latent Space*. Relevant to AI framework infrastructure discussions; Turbopuffer is part of the retrieval stack that LangChain/LangGraph depend on. *Released March 12*

- **[The Top 100 Gen AI Consumer Apps](https://open.spotify.com/episode/3rNMKrqBeYYLdYNuPY9VLV)** — Show: *a16z Podcast*. Context for Amazon's Fauna Robotics acquisition and the broader consumer AI landscape evolving this week. *Released March 10*

## Discovery Pick

- **[Bioinfohazards: Jassi Pannu on Controlling Dangerous Data from which AI Models Learn](https://open.spotify.com/episode/2zv51PGlZvtF2vq46uxyts)** — Show: *Cognitive Revolution*. Connects to: The Claude Mythos restrictions (Anthropic limiting a model's access to vetted customers due to capability risk) and the broader question of what AI models should and shouldn't learn. Pannu's work on bioinfohazardous training data is the intellectual frame for understanding Anthropic's decision to hold back Mythos — any sufficiently capable model trained on adversarial exploit data becomes a dual-use risk. *Released March 11*

---

*Sources: 2026-03-23, 2026-03-24, 2026-03-25, 2026-03-28 dailies synthesized (45 stories, 4 briefings) | Pre-fetch: Spotify API (2026-03-15), Apple Charts (2026-03-15 — no tracked tech shows in top 25 this cycle), CISA KEV, NVD*
*Generated by BPG Tech News Agent*

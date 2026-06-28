# BPG Tech News — Week 26 Recap

**June 28, 2026** | Weekly | 54 stories across 5 dailies | Generated 9:00 AM MDT

<!-- tab: Week in AI -->

## Top Stories

- **[Anthropic's Fable 5 and Mythos 5 Suspended, Then Cleared — A 15-Day Government Standoff](https://www.anthropic.com/news/fable-mythos-access)** — What began June 12 with a U.S. export-control directive suspending all foreign-national access to Fable 5 and Mythos 5 ended June 27 when the government officially cleared Anthropic to redeploy Mythos 5 to validated critical-infrastructure operators. Along the way: a jailbreak of Fable 5 was disclosed within days of launch, Congress sent a formal letter demanding Commerce Secretary Lutnick explain the suspension by June 26, and Anthropic co-founder Tom Brown replaced CEO Dario Amodei in negotiations. *Covered: June 24, 25, 27 (3 days). Sources: Anthropic, Schneier on Security, CyberSecurity News*

- **[OpenAI Launches GPT-5.6 in Three Tiers — Each Enterprise Access Individually White House-Approved](https://www.axios.com/2026/06/26/openai-gpt-sol-terra-luna-trump)** — On June 26, OpenAI began a limited preview of GPT-5.6 across Sol, Terra, and Luna tiers, available only to approximately 20 companies whose participation was individually approved by the U.S. government. Sol is OpenAI's most capable model to date, with a "max" reasoning mode optimized for cybersecurity; Terra matches GPT-5.5 at half the cost; Luna is the lowest-cost option. Broader rollout expected in coming weeks. *Source: Axios*

- **[Z.ai GLM-5.2: Open-Weights Model Beats GPT-5.5 on Coding Benchmarks at 1/6th the Cost](https://venturebeat.com/technology/z-ais-open-weights-glm-5-2-beats-gpt-5-5-on-multiple-long-horizon-coding-benchmarks-for-1-6th-the-cost/)** — Released under an MIT license, GLM-5.2 is a 753B-parameter MoE model with a 1M-token context window that scored 62.1 on SWE-bench Pro against GPT-5.5's 58.6 — at enterprise API pricing starting at $12.60/month. It topped the Artificial Analysis Intelligence Index and trended on Hacker News for multiple days. *Covered: June 23, 26 (2 days). Source: VentureBeat*

- **[Anthropic Launches Claude Tag — A Persistent AI Team Member That Lives in Slack](https://www.anthropic.com/news/introducing-claude-tag)** — Running on Opus 4.8, Claude Tag joins Slack channels, builds per-channel memory, executes work asynchronously, and in ambient mode surfaces updates without being prompted. Anthropic's own Claude Code team reports it already writes 65% of their code. Available in beta for Enterprise and Team customers; the legacy Claude Slack app retires August 3. *Covered: June 24, 26 (2 days). Source: Anthropic Blog*

- **[Google DeepMind Loses Four AlphaFold Researchers to Anthropic in One Week — Alphabet Sheds $270B](https://techcrunch.com/2026/06/24/ai-researchers-continue-to-leave-google-for-its-rivals/)** — Jonas Adler, Alexander Pritzel, John Jumper, and Arthur Conmy all announced Anthropic departures within a single week, with Conmy joining specifically to work on train-time alignment for upcoming models. Alphabet's market cap fell approximately $270 billion over the same period, coinciding with reports of Gemini 3.5 delays. *Covered: June 25, 27 (2 days). Source: TechCrunch*

- **[OpenAI's Leaked Financials: $13.1B Revenue Against $38.5B Total Loss — IPO Pending with SEC](https://fortune.com/2026/06/16/openai-financials-leaked-losses-revenue-profit/)** — Documents verified by the Financial Times show $13.1B in net revenue against a $38.5B total loss, though $41.6B in one-time accounting charges (converting early investor IOUs to equity) inflate the headline figure; the underlying operational loss is estimated at ~$8B. The company has an IPO pending with the SEC, and the financials went viral on Hacker News. *Source: Fortune*

## Emerging Themes

**The Age of Regulated AI Access**

This week crystallized a new paradigm: frontier model access is now subject to government gatekeeping with no clear or established legal process. The Anthropic standoff — 15 days, congressional intervention, CEO-level replacement in negotiations — demonstrated that export controls can suspend a lab's flagship products globally overnight. OpenAI then codified the new model: individual White House approval per enterprise customer for GPT-5.6 access. For AI companies building on frontier APIs, sovereign risk is now a first-class infrastructure concern.

**The Open-Weights Counterstrike**

GLM-5.2's performance against GPT-5.5 at one-sixth the cost, combined with SpaceX's $6.3B compute deal with the explicitly open-weight Reflection AI, signals that closed labs can no longer compete on capability alone. MIT-licensed models at frontier performance tiers rewrite the enterprise build-vs-buy calculus: organizations that previously paid premiums for closed frontier access now have a commercially licensable alternative. The open ecosystem absorbed one of the largest infrastructure bets in AI history this week.

**Anthropic's Gravitational Pull on Google**

Four elite Google/DeepMind researchers in one week isn't coincidence — it reflects a structural shift in where the most consequential AI work is happening. Anthropic's Project Glasswing (23,000+ vulnerabilities found across open-source infrastructure), the government's decision to clear Mythos 5 specifically for critical infrastructure defense, and Claude Tag's 65% code-authorship rate all point to a lab in deployment acceleration. Google appears to be in a talent retention crisis at exactly the moment Gemini 3.5 faces delays.

**AI Tools Weaponized Against AI Defenses**

Three separate stories this week converged on a single threat pattern: adversaries are now targeting AI tooling itself as a primary attack vector. macOS.Gaslight (North Korea) embeds a fabricated-error cascade to abort LLM triage agents. A separate malware developer injects nuclear/biological content to trigger AI safety filters and halt automated analysis. The Leo Platform npm supply chain attack specifically backdoors project repos that execute when opened in AI-assisted IDEs like Cursor or VS Code Copilot. The Five Eyes agencies warned on June 22 that this convergence is accelerating — this week's evidence confirms it.

---

<!-- tab: Breakthroughs Recap -->

## Breakthrough Moments

- **[OpenAI and Broadcom Unveil Jalapeño — First Custom LLM Inference Chip Built in Nine Months](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/)** — OpenAI's first custom AI inference processor was developed in a record nine-month cycle, itself accelerated by OpenAI's own models — a notable early instance of AI compressing hardware development timelines. Jalapeño delivers substantially better performance-per-watt than current accelerators and is the first chip in a planned multi-generation compute platform, with initial deployment targeted for end of 2026 at gigawatt-scale data centers alongside Microsoft and other partners. The development speed is as significant as the chip itself. *Covered: June 25, 27 (2 days). Source: TechCrunch*

- **[GLM-5.2: Open-Weights Frontier Model Crosses the Commercial-License Threshold](https://venturebeat.com/technology/z-ais-open-weights-glm-5-2-beats-gpt-5-5-on-multiple-long-horizon-coding-benchmarks-for-1-6th-the-cost/)** — A 753B-parameter, MIT-licensed model that outperforms GPT-5.5 on real software engineering benchmarks at one-sixth the cost isn't an incremental improvement — it's a category event. For the first time, an open model at this capability tier is freely commercially licensable with no usage restrictions, removing the last licensing barrier to frontier-class open model deployment at enterprise scale. *Covered: June 23, 26 (2 days). Source: VentureBeat*

- **[Project Glasswing: AI Autonomously Finds 23,000+ Vulnerabilities Across Open-Source Infrastructure](https://cybersecuritynews.com/anthropic-claude-mythos-5/)** — Anthropic's Project Glasswing, using Mythos Preview to autonomously hunt vulnerabilities, has identified more than 23,000 issues — including 6,200 high- or critical-severity flaws — across 1,000+ open-source projects. That the U.S. government's stated rationale for clearing Mythos 5 specifically includes this program signals that AI-driven vulnerability research has been embedded into national security posture at the infrastructure level. *Source: CyberSecurity News*

- **[Claude Tag: 65% of Anthropic's Own Engineering Code Is Now Written by AI](https://www.anthropic.com/news/introducing-claude-tag)** — Claude Tag isn't a chat interface — it's a persistent team member with per-channel memory, ambient mode, and asynchronous tool execution. The 65% code-authorship figure for Anthropic's own Claude Code team is the most concrete public benchmark yet for AI coding agents operating in production at a leading AI lab. The implication for software teams everywhere is direct. *Covered: June 24, 26 (2 days). Source: Anthropic Blog*

- **[Alibaba's HappyHorse 1.1 Rises to No. 2 in AI Video After Sora Discontinuation and Seedance Retreat](https://venturebeat.com/technology/alibabas-ai-video-model-rises-to-no-2-in-global-rankings-as-openais-sora-and-bytedances-seedance-fall-away)** — OpenAI discontinued Sora — which generated only $2.1M in total revenue while burning ~$1M/day — and ByteDance shelved Seedance 2.0's international rollout amid Hollywood copyright complaints. Alibaba's HappyHorse 1.1 (1357 Elo on Artificial Analysis's without-audio leaderboard) stepped into the leadership vacuum and is now live on Alibaba Cloud Model Studio with full API access. The AI video generation competitive field reshuffled in a single week. *Source: VentureBeat*

---

<!-- tab: Cyber Weekly -->

## Persistent Threats

- **[Cisco's Exploitation Streak: 8+ Events in 2026, Including a Zero-Day Pre-Disclosure Window](https://therecord.media/cisco-ransomware-interlock-firewalls)** — The Interlock ransomware group weaponized a Cisco firewall zero-day weeks before Cisco published an advisory, exploiting the pre-disclosure window to pivot into enterprise networks. CISA then added Cisco SD-WAN CVE-2026-20262 (federal deadline June 29) and Cisco Unified CM CVE-2026-20230 SSRF (federal deadline June 28) to the KEV catalog this week, marking the eighth and ninth confirmed Cisco exploitation events in 2026. Organizations running Cisco network-edge infrastructure should treat any unpatched CVE as actively targeted. *Sources: The Record, SecurityWeek, BleepingComputer*

- **[Splunk CVE-2026-20253 — CVSS 9.8 Unauthenticated RCE, Federal Deadline Passed June 28](https://www.bleepingcomputer.com/news/security/cisa-splunk-enterprise-flaw-actively-exploited-patch-by-sunday/)** — The first Splunk vulnerability added to the CISA KEV catalog: unauthenticated RCE via Splunk Enterprise's PostgreSQL sidecar endpoint, affecting versions before 10.2.4 and 10.0.7. Federal agency patch deadline was June 28. Any unpatched Splunk Enterprise installations network-reachable from untrusted hosts should be treated as compromised pending forensic review. Patched versions: 10.2.4, 10.0.7, or 10.4.0+. *Covered: June 23, 27 (2 days). Source: BleepingComputer*

- **[Shai-Hulud GitHub Supply Chain Worm — 1,729 Malicious Repos Still Live, Flaw Finally Resolved](https://therecord.media/github-dismissed-reports-shai-hulud-deep-specter)** — Researchers say GitHub rejected security disclosures about platform design flaws that Shai-Hulud variants have been actively exploiting to spread credential-harvesting code across npm and PyPI, hitting the European Commission, Mercor, LiteLLM, and Red Hat. As of June 16, 1,729 credential-harvesting repositories and 151 active malicious payload repos remained live. GitHub resolved the underlying repository-takeover vulnerability on June 27 under researcher pressure. *Covered: June 26, 27 (2 days). Source: The Record*

- **[Mistic Backdoor Tied to KongTuke Access Broker Targets Insurance, Education, and IT Since April](https://www.bleepingcomputer.com/news/security/stealthy-mistic-backdoor-linked-to-ransomware-access-broker-kongtuke/)** — Active since at least April 2026, Mistic is a stealthy backdoor deployed by KongTuke — an initial access broker that specializes in selling corporate footholds to ransomware groups. The malware is designed to remain dormant during the access-brokering phase before handing off to downstream ransomware operators, targeting insurance, education, IT, and professional services. *Covered: June 25, 27 (2 days). Source: BleepingComputer*

## Week's Incidents

- **[Aflac Breach: 22.65 Million Customers, Employees, and Agents Exposed](https://therecord.media/22-million-impacted-aflac-breach)** — A June social-engineering attack exposed names, contact details, health claims information, and Social Security numbers for approximately 22.65 million individuals. The breach was contained within hours and no ransomware was deployed; Aflac is offering two years of identity protection to affected parties. *Source: The Record*

- **[Tata Electronics Ransomware: 630GB of Alleged Apple Manufacturing and Tesla Assembly Files Leaked](https://www.bleepingcomputer.com/news/security/tata-electronics-confirms-cyberattack-as-hackers-leak-data/)** — The World Leaks extortion group published 200,000+ files including alleged Apple manufacturing specifications and Tesla assembly documents with confidentiality markings from Tata Electronics, which manufactures roughly a third of Apple's iPhones in India. The company says business operations remain unaffected. *Source: BleepingComputer*

- **[LastPass: Customer Data Exposed via Klue SaaS Supply Chain Attack by Icarus Group](https://www.bleepingcomputer.com/news/security/lastpass-confirms-data-breach-in-klue-supply-chain-attack/)** — The Icarus extortion group compromised Klue, an AI market intelligence SaaS, stole OAuth tokens connecting customers' Salesforce and Gong environments, and accessed LastPass customer names, phone numbers, addresses, and support interaction contents. Customer vaults and core infrastructure were not affected; stolen data began appearing on Icarus's leak site June 22. Multiple firms including Recorded Future, Tanium, and Jamf were also impacted. *Source: BleepingComputer*

- **[ShinyHunters Threatens to Leak 8.8TB of Amazon One Medical Patient Data](https://www.bankinfosecurity.com/shinyhunters-threatens-to-leak-amazon-one-medical-records-a-32027)** — The group claims to have stolen 8.8TB from One Medical's network serving 830,000+ patients across 250+ US clinics and issued a deadline before publishing. One Medical confirmed a separate limited incident: unauthorized access to a legacy Iora Health file storage platform between June 8–11; current patient EMR systems were not compromised. *Source: BankInfoSecurity*

- **[Microsoft Defender RoguePlanet Zero-Day (CVE-2026-41091, CVSS 7.8) — Patch in Development](https://www.bleepingcomputer.com/news/microsoft/microsoft-defender-rogueplanet-zero-day-grants-system-privileges/)** — A local privilege escalation flaw in Microsoft Defender allows attackers to gain SYSTEM-level privileges. Surfaced June 26 with no patch; Microsoft confirmed June 27 it is working on a fix after researcher pressure. No patch is available yet. *Covered: June 26, 27 (2 days). Source: BleepingComputer, SecurityWeek*

## By the Numbers

- **22.65M** — individuals exposed in the Aflac breach, the week's largest
- **8.8TB** — patient data ShinyHunters claims from One Medical
- **630GB / 200K files** — leaked from Tata Electronics by World Leaks
- **9.8 CVSS** — Splunk CVE-2026-20253 (unauthenticated RCE, actively exploited)
- **9** — Cisco exploitation events confirmed in 2026 as of this week
- **7+** — CVEs added to CISA KEV across the week (Splunk, Cisco SD-WAN, Cisco Unified CM, PTC Windchill, 4× Ubiquiti/Lantronix)
- **1,729** — credential-harvesting GitHub repositories still live as of June 16 (Shai-Hulud)
- **13,600** — weekly downloads of Leo Platform npm packages before supply chain compromise was discovered

---

<!-- tab: Podcasts -->

## News-Connected Episodes

- **[Socialists Sweep NYC, China Catches Up in Coding, AI Memory Crunch, Micron's Blowout Quarter](https://open.spotify.com/episode/23qldAMWwJ3Z3aIdD87VJl)** — Show: *All-In Podcast*. Connects to: GLM-5.2 and China's open-source AI challenge to closed frontier labs; OpenAI Jalapeño chip reveal and the AI memory constraints driving hardware investment.

- **[#221: Anthropic vs. the White House, Microsoft CEO on the Future of Firms & AI's Token Crisis](https://open.spotify.com/episode/5G1gQdOW8MSTD3iatw7CPQ)** — Show: *The Artificial Intelligence Show*. Connects to: The full Fable 5/Mythos 5 government standoff — the export-control suspension, the Lutnick letter, congressional demands, and what government-gated model access means for AI businesses.

- **[OpenAI Unveils First Custom AI Chip With Broadcom](https://open.spotify.com/episode/03lpcsYIc0VKcD8sNIwQLY)** — Show: *Bloomberg Technology*. Connects to: The Jalapeño chip story; includes Cerebras CEO Andrew Feldman's commentary on the custom silicon competitive landscape.

- **[Why the Frontier Ecosystem must be Open — Matei Zaharia and Reynold Xin, Databricks](https://open.spotify.com/episode/5DBvBVnYzuv4oIqJycpdlx)** — Show: *Latent Space*. Connects to: GLM-5.2 open-weights story and Reflection AI's $6.3B compute deal; Databricks co-founders make the case for open-frontier AI as closed labs face government access restrictions.

- **[Red-Teaming after Mythos — Zico Kolter & Matt Fredrikson, Gray Swan](https://open.spotify.com/episode/1is5quiBlHyPdNHreUqgN2)** — Show: *Latent Space*. Connects to: Fable 5 jailbreak disclosure and the Five Eyes warning on AI-supercharged offensive hacking; Gray Swan specializes in safety evaluations and red-teaming of frontier models.

- **[OpenAI Weighs IPO in 2027](https://open.spotify.com/episode/54vOvqDnjq2Mp5DN9PbPZ8)** — Show: *Bloomberg Technology*. Connects to: OpenAI's leaked financials ($13.1B revenue, $38.5B total loss) and IPO timing questions; covers SoftBank reactions and SpaceX bond sale context from the same news cycle.

## Trending in Tech Podcasts

- **[How to train your data](https://open.spotify.com/episode/6fYc7sxes78uZVT0O5l4ME)** — Show: *The Vergecast*. A deep look at what AI training data actually is, where it comes from, and the legal and ethical tensions involved — direct backdrop to the week's open-weights vs. closed-model debate.

- **[AI Is Crossing the Frontier of Human Knowledge | Kevin Weil](https://open.spotify.com/episode/0X3iGzFxVlONiv05BEdVB6)** — Show: *a16z Podcast*. Former OpenAI CPO on AI's accelerating scientific discovery capabilities; frames the capability context behind the week's GPT-5.6 launch and Mythos 5 critical infrastructure clearance.

- **[Pioneers of AI: Reid Hoffman says the AI race is not a cage match](https://open.spotify.com/episode/2kIgFyGJll9ROSICu5CPD9)** — Show: *Masters of Scale*. Contextualizes the OpenAI/Anthropic competitive and IPO dynamics after a week in which both labs appeared simultaneously in government negotiations, product launches, and capability disclosures.

## Discovery Pick

- **[473: How a hacker could have Rickrolled the entire World Cup](https://open.spotify.com/episode/0qRYT45CoYbREVkfTVsbEm)** — Show: *Smashing Security*. A concrete, witty case study in large-scale public infrastructure security failure — how a single unpatched vulnerability in stadium display systems could have hijacked screens visible to billions. A useful grounding counterpoint to the week's enterprise CVE coverage: the same classes of flaw operate at consumer scale too.

---

*Sources: June 23, 24, 25, 26, 27 dailies synthesized | Pre-fetch: Spotify API, Apple Charts, CISA KEV, NVD*
*Generated by BPG Tech News Agent*

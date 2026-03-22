---
type: concept
category: security/technology
tags: [concept, AI, warfare, autonomous-weapons, military-technology, drones]
---

# AI Warfare

## Definition

The application of artificial intelligence to military operations -- from intelligence analysis and targeting to autonomous weapons systems. AI warfare spans a spectrum: human-assisted AI (accelerating human decisions), human-on-the-loop (AI acts, human monitors), and fully autonomous systems (AI identifies, selects, and engages targets without human intervention).

The US military's decade-long pursuit of AI-powered warfare has been shaped by three tensions: speed vs. safety, secrecy vs. deterrence, and government control vs. Silicon Valley resistance.

## Key Programs

### Project Maven (2017-)

The Pentagon's foundational AI warfare program, officially the Algorithmic Warfare Cross-Functional Team. Established by a memo from Deputy Secretary of Defense Robert O. Work on April 26, 2017. Goal: create computer vision algorithms to analyze drone video, detect objects, and turn enormous volumes of data into "actionable intelligence and insights at speed."

**Key early leaders:**
- **Col. Drew Cukor (USMC)** -- project chief who ran the day-to-day team. The "Marine Colonel" of Katrina Manson's book subtitle.
- **Lt. Gen. Jack Shanahan (USAF)** -- senior program director; later became inaugural Director of the Joint Artificial Intelligence Center (JAIC).

**Evolution:**
- **2017**: Launched. Google was an early partner.
- **2018**: Google employee revolt -- thousands protested the contract. Google assured internal dissidents the work was for "non-offensive uses only," then ultimately did not renew its contract.
- **Present**: Every US military command globally uses Maven Smart System. NATO adopted a version in 2025. Now jointly administered by the NGA and the Chief Digital and AI Office (CDAO).

**Key contractors:**

| Company | Role |
|---------|------|
| [[Palantir]] | Built Maven Smart System |
| [[Amazon]] (AWS) | Secure cloud computing |
| [[Microsoft]] | Technology contributor |
| Clarifai | Computer vision |
| [[Anduril]] | Autonomous operating systems for drones |

The government intimated at the outset that Maven wouldn't be used for targeting during combat. People involved in the program say it was always clearly headed that way (reported, Katrina Manson, *Project Maven*).

### Maven Smart System

Palantir-built AI-enabled mission control system. Operational deployments:

| Deployment | Year | Scale |
|------------|------|-------|
| Ukraine targeting intelligence | 2022 | Shared targeting information |
| Iraq/Syria/Houthi strikes | 2024 | Combat targeting |
| **[[2026 Iran conflict]]** | 2026 | **~1,000 targets in first 24 hours** (2x shock-and-awe in Iraq 2003); 5,000 targets in 10 days |

The Iran campaign was the system's biggest test. The military's goal: identify and select 1,000 targets not in a day but in a single hour (reported, Bloomberg citing person familiar with the campaign).

Timothy Hawkins (CENTCOM spokesperson): tools generate "points of interest" and help personnel make decisions. "Bottom line, these tools help leaders -- humans -- make smarter decisions faster."

### Replicator / DAWG

Pentagon effort to deploy thousands of autonomous drones, primarily focused on a potential conflict with [[China]] over [[Taiwan]].

**Replicator (Biden era, 2023-2025):**
- Announced by Deputy Defense Secretary Kathleen Hicks in 2023
- Goal: quickly deploy thousands of autonomous air and maritime drones
- Hicks promised China would find US drones "harder to plan for, harder to hit and harder to beat"
- Prioritized systems completable by 2027 -- the year US officials say China could have capability to take Taiwan
- Delivered hundreds of drones by August 2025 deadline but fell far short of initial goals

**DAWG (Trump era, 2025-):**
- Rebranded as Defense Autonomous Warfare Group (some sources: "Working Group"). Housed within SOCOM.
- Marine Corps Lt. Gen. Frank Donovan, then SOCOM Vice Commander, oversaw the transition. He reduced number of autonomous platforms and focused on simpler drones for Taiwan defense before being nominated to lead SOUTHCOM (confirmed December 2025, assumed command February 5, 2026).
- "Drone Dominance" initiative launched under DAWG: first phase targets 30,000 one-way attack drones from 12 vendors at ~$5,000/unit (reported, Breaking Defense).
- **January 2026**: Announced $100 million prize challenge for LLM-powered drone swarm control -- translate verbal human commands into instructions for autonomous drone swarms
  - Anthropic bid but was not selected
  - Two selected bids involved OpenAI technology
  - Other participants: Palantir, SpaceX
  - Later stages require "target-related awareness and sharing" and ultimately "launch to termination" -- Pentagon terminology for a killer drone's full mission cycle

### Taiwan-Focused AI Development

Starting in 2022, Maven's team began collecting enormous amounts of imagery of Chinese vessels in the Pacific for AI training data.

- Senior defense officials -- including the chairman of the Joint Chiefs -- were shown videos demonstrating AI automatically identifying Chinese destroyers (summer 2025)
- "We're basically watching the PLA all the time now to get AI training data" (defense official, Bloomberg)
- Maven's models had more imagery of Chinese vessels than commercial AI companies
- The Pentagon wants AI that can exist entirely on a self-flying drone, identifying and hitting targets without human intervention -- critical for jammed communications environments near China

**Challenges:**
- Software delivery delays; models hard to make compatible with drone computers
- AI struggled to detect multiple vessels simultaneously
- Camera lens ocean spray degraded object tracking
- Commercial drone makers claimed their own models worked fine without Maven

### Covert Programs

**Goalkeeper** (Office of Naval Research):
- "Expeditionary loitering munitions" with "autonomous government-provided software and auxiliary systems" (per Navy budget documents)
- Drones designed to fly, pick targets, and attack without human intervention

**Whiplash:**
- Program to transform 600 jet skis into bomb-carrying autonomous watercraft
- CIA secretly tested rudimentary versions in the Black Sea off Ukraine (reported, Bloomberg citing people familiar)
- In July 2024, an explosive-laden jet ski washed ashore in Turkey -- Pentagon feared cover was blown

Both programs disappeared from public budget documents under Trump 2.0 but production continues per 2026 budget estimate documents (confirmed, Bloomberg).

## The June 2025 GARC Incident

Channel Islands Harbor Marina, Southern California. Global autonomous reconnaissance crafts (GARCs) were being tested as part of Replicator. Two companies -- [[L3Harris]] and [[Anduril]] -- had built competing autonomous operating systems for the boats.

**What happened:**
1. An operator on the dock inadvertently sent a message remotely disabling the safety lock on a drone running L3Harris software -- a "fat-finger mistake"
2. The drone's autonomy mode activated. Its programming required maintaining 80 meters from all objects.
3. The drone lurched forward while still tethered to a towboat, crisscrossing erratically
4. The towboat capsized, throwing its captain into the water
5. The drone then advanced at rapid speed toward the floating captain
6. Another vessel captain intervened, positioning between the drone and the man in the water
7. A third boat pulled the captain out. He escaped without serious injury. Total elapsed time: ~3 minutes.

**Fixes:** Physical button added to block accidental autonomy commands; companies began sharing safety lessons.

**Significance:** Replicator still had not progressed to putting live ammunition on unmanned vessels at that point. The incident illustrated that fundamental safety problems remained unsolved -- problems that couldn't be fixed with "the addition of another button or two" (Manson).

## Silicon Valley and the Pentagon

### Google Revolt (2018)

Thousands of Google employees protested the company's Maven contract. Google assured dissidents the work was for "non-offensive uses only." The company ultimately did not renew its contract -- the first major corporate break with military AI.

### The Anthropic Blacklisting (February 27, 2026)

The most significant confrontation between Silicon Valley and the Pentagon over AI weapons:

- **February 26**: Anthropic rejected the Pentagon's latest offer, citing two red lines -- no mass domestic surveillance, no autonomous weapons (confirmed, NPR)
- **February 27**: [[Pete Hegseth]] formally designated Anthropic PBC (valued at $380 billion) a "supply chain risk to national security" -- a classification historically reserved for foreign adversaries (Huawei, ZTE). Trump on social media: "Radical Left AI company." Hegseth on X: Anthropic attempting to "seize veto power over the operational decisions of the United States military."
- **February 27 (~8 hours later)**: US bombed [[Iran]]. Same day, OpenAI announced a deal to provide the Pentagon the same services.
- **March 3**: Sam Altman (OpenAI CEO) admitted the Pentagon deal "looked opportunistic and sloppy" and that he "shouldn't have rushed." OpenAI amended its contract to add surveillance protections, barring intentional use for "domestic surveillance of U.S. persons and nationals" (confirmed, CNBC, Axios). Critics noted the amended language remained "purposefully vague" with carve-outs (reported, The Intercept).
- **March 4**: Defense tech companies began dropping Anthropic's Claude (confirmed, CNBC).
- **March 9**: Anthropic filed lawsuits in San Francisco and Washington federal courts (confirmed, CNN).
- **March 16-17**: Nearly 150 retired federal/state judges filed amicus brief supporting Anthropic (confirmed, CNN).
- **March 18**: Pentagon filed rebuttal calling Anthropic an "unacceptable risk" (confirmed, TechCrunch).
- **March 24**: Preliminary injunction hearing scheduled.

Anthropic CEO Dario Amodei: his AI systems are "simply not ready to produce fully autonomous weapons that would be reliable enough to be safe."

**Despite the blacklisting**, Anthropic's large language models are still being used by the military for intelligence analysis and speeding up administrative processes involved in strikes (reported, Bloomberg citing people familiar).

### Company Roles in Military AI

| Company | Role | Stance |
|---------|------|--------|
| **Palantir** | Built Maven Smart System; DAWG participant | Full cooperation |
| **OpenAI** | Replaced Anthropic (Feb 2026); tech in DAWG selections | Full cooperation |
| **Anthropic** | Blacklisted Feb 27, 2026; LLMs still used for intel analysis | Refused autonomous weapons / mass surveillance |
| **Amazon (AWS)** | Secure cloud computing | Full cooperation |
| **Microsoft** | Maven Smart System contributor | Full cooperation |
| **Anduril** | Autonomous systems; $60B target valuation (raising ~$4B round; previous: $30.5B, June 2025); $20B US Army contract (March 14, 2026) | Founded for defense; full cooperation |
| **Google** | Early Maven partner (2017-2018) | Withdrew after employee revolt |
| **L3Harris** | Autonomous navigation for maritime drones | Full cooperation |
| **SpaceX** | DAWG drone swarm challenge participant | Full cooperation |
| **AeroVironment** | Drone manufacturer; AI target recognition | Full cooperation |
| **Clarifai** | Computer vision for Maven | Full cooperation |

## The Autonomy Debate

### Arguments For
- **Speed**: AI processes targets faster than humans -- goal is 1,000 targets/hour vs. 1,000/day
- **Scale**: Enables drone swarms impossible for humans to coordinate
- **Survivability**: Drones can operate when communications are severed (critical for jammed environments near China)
- **Cost**: Cheap drones ($30K [[Shahed]]-type) vs. $3.6M Tomahawks -- see cost asymmetry in [[Defense Industry]]

### Arguments Against

> "No LLM, anywhere, in its current form, should be considered for use in a fully lethal autonomous weapons system. Overreliance on them at this stage is a recipe for catastrophe."
> -- Jack Shanahan, retired three-star general, former director of Project Maven

- **Reliability**: AI hallucinations, faulty data, and algorithm drift (accuracy loss over time)
- **Accountability**: Who is responsible when an autonomous weapon kills civilians?
- **Testing**: Jane Pinelis (Maven testing lead, 2023): US military needed higher risk tolerance but the only realistic approach was to "plan for how AI would fail"
- **Demonstrated risk**: The June 2025 GARC incident -- a single operator error caused an autonomous boat to capsize a crewed vessel and advance toward a man in the water

### Internal Pentagon Tensions

| Debate | Faction A | Faction B |
|--------|-----------|-----------|
| Build vs. buy | Pentagon builds AI in-house | Purchase from Silicon Valley |
| Simple vs. complex | Cheap drones shippable to Pacific allies | Elaborate coordinated swarms |
| Secrecy vs. deterrence | Maintain surprise | Telegraph capabilities to deter China |
| Risk tolerance | Accept AI failures as inevitable | Demand perfection before deployment |

### Emotional Dimension

Those building autonomous weapons describe a visceral reaction to the technology:

> "There's really nothing quite like seeing a machine aim. There is an alien aspect, some otherworld feeling. I don't want to say 'religious,' that's not the right word. God, it's terrifying."
> -- Person involved in Pentagon AI efforts (Bloomberg)

## AI in the 2026 Iran Campaign

The [[2026 Iran conflict]] was the largest test of AI-enabled warfare to date:

- **Maven Smart System**: ~1,000 targets identified and struck in first 24 hours; 5,000 in 10 days
- **Semiautonomous drones**: First US combat use; CENTCOM commander called them "indispensable"
- **AI for intel analysis**: Anthropic LLMs still used despite blacklisting (reported)
- **Civilian casualties**: Over 1,300 civilians killed as of March 12 (Iranian officials), including 175+ at a girls' school from what news reports attributed to a Tomahawk strike relying on outdated intelligence. Pentagon has not said whether AI was involved.
- **Scale comparison**: Approximately twice the first-day target count of the 2003 Iraq shock-and-awe campaign

"Iran is an amazing precursor to what could happen with China over Taiwan" (person familiar with US operations, Bloomberg).

## Strategic Implications

### For US-China Competition
- The entire autonomous weapons development pipeline is oriented toward a potential [[Taiwan]] scenario
- Pentagon building AI that operates independently when wireless communications are severed -- a near-certainty in a China conflict
- UK national security official: US officials assure allies the US would be ready for Taiwan, then "drop their voices and confess: 'We're not ready'" (reported, Bloomberg)

### For International Norms
- No binding international treaty on autonomous weapons despite a decade of UN CCW Group of Governmental Experts (GGE) meetings on LAWS (Lethal Autonomous Weapons Systems)
- **November 2025**: UNGA First Committee adopted resolution on autonomous weapons -- 156 in favor, 5 against, 8 abstentions. States blocking negotiations: US, Russia, Israel, India, Australia, South Korea -- the same states most actively developing autonomous weapons.
- **November 2026**: CCW Seventh Review Conference scheduled -- widely seen as the decisive moment for potential treaty
- **US position**: DoD Directive 3000.09 (originally 2012, updated January 2023) requires "appropriate levels of human judgment over the use of force" but does **not** ban autonomous weapons. It establishes an approval process requiring senior DoD sign-off. "Appropriate" is deliberately flexible. Human Rights Watch criticized the 2023 update for not clarifying what "appropriate" means.
- The Anthropic blacklisting signals the government will not tolerate corporate limits on military AI use
- OpenAI's willingness to step in may set industry precedent: cooperate or be replaced

### Other Countries' AI Weapons Programs

| Country | Key Programs | Status |
|---------|-------------|--------|
| **China** | "Intelligentization" (third PLA modernization phase); DeepSeek AI integrated into military procurement; Norinco autonomous combat vehicle | September 2025 parade showcased uncrewed ground/air/underwater drones; ~$278B military budget (+7%) |
| **Israel** | **Lavender** (marks people for targeting) and **Gospel/Habsora** (marks buildings) AI targeting systems | First used in Gaza; deployed at largest-ever scale in [[2026 Iran conflict]]; 20-second human verification windows (reported) |
| **Turkey** | Baykar **K2 Kamikaze Drone**: 2,000 km range, 200 kg warhead, AI-enabled swarming without GPS | Unveiled March 14, 2026; $2.2B exports in 2025; deals with 37 countries |
| **Russia** | Geran-2 drones (based on Iranian Shahed) with Nvidia Jetson-powered AI for autonomous target recognition; 5,000+/month production | Putin ordered Russia-China AI collaboration |
| **South Korea** | SGR-A1 robot sentries on DMZ; 78% FY2026 budget increase for AI unmanned combat systems | Among states blocking LAWS treaty |
| **India** | Fast-tracking orders for 50 Israeli Harop loitering munitions after May 2025 India-Pakistan war | Used Harop in combat |

### For Civilian Protection
- AI-enabled targeting allows faster, larger-scale campaigns -- but faster does not mean more accurate
- The gap between "AI identifies a target" and "that target is correctly identified" remains poorly understood in combat conditions
- Jack Shanahan's warning about LLM unreliability applies directly to the Iran campaign's scale

## Key Figures

| Person | Role | Position |
|--------|------|----------|
| **Lt. Gen. Jack Shanahan (USAF, Ret.)** | Directed Project Maven; first JAIC director; now CNAS adjunct senior fellow | LLMs not ready for lethal autonomy |
| **Col. Drew Cukor (USMC)** | Project Maven day-to-day chief | The "Marine Colonel" of Manson's book |
| **Kathleen Hicks** | Biden deputy SecDef | Launched Replicator; 1,000s of drones by 2027 |
| **Frank Donovan** | Marine Lt. Gen., SOCOM Vice Commander; now SOUTHCOM commander | Oversaw DAWG transition; simplified drone focus |
| **Jane Pinelis** | Maven testing/evaluation lead | "Plan for how AI would fail" |
| **Dario Amodei** | Anthropic CEO | Systems not reliable enough for autonomy |
| **Sam Altman** | OpenAI CEO | Admitted Pentagon deal "looked opportunistic" |
| **[[Pete Hegseth]]** | Secretary of War | Anthropic "seizing veto power" |

## Related Concepts

- [[Technology Competition]] -- AI as commanding heights of great power rivalry
- [[Precise Mass]] -- the production-side thesis: cheap autonomous weapons at scale inverting attack-defense economics
- [[Defense Industry]] -- production base for autonomous systems
- [[Deterrence]] -- AI capabilities as deterrent signal
- [[2026 Iran conflict]] -- first major test of Maven Smart System at scale
- [[Taiwan]] -- primary scenario driving autonomous weapons development
- [[Cyber Warfare]] -- overlapping domain
- [[Nuclear Command and Control]] -- AI risks to nuclear C2
- [[Hybrid Warfare]] -- AI-enabled gray zone operations

### Cross-vault
- [Investing: Defense sector](obsidian://open?vault=investing&file=Sectors%2FDefense) -- defense tech companies (Palantir, Anduril) as investment theme

## Sources

- Katrina Manson, "How the Pentagon Got Hooked on AI War Machines," *Bloomberg Businessweek* (March 12, 2026). Adapted from *Project Maven: A Marine Colonel, His Team, and the Dawn of AI Warfare* (W.W. Norton, March 25, 2026).
- NPR: [Trump bans Anthropic](https://www.npr.org/2026/02/27/nx-s1-5729118/trump-anthropic-pentagon-openai-ai-weapons-ban) (February 27, 2026)
- CNN: [Anthropic sues](https://www.cnn.com/2026/03/09/tech/anthropic-sues-pentagon) (March 9, 2026)
- CNN: [Former judges support Anthropic](https://www.cnn.com/2026/03/17/tech/former-judges-support-anthropic) (March 17, 2026)
- CNBC: [Altman admits Pentagon deal "sloppy"](https://www.cnbc.com/2026/03/03/openai-sam-altman-pentagon-deal-amended-surveillance-limits.html) (March 3, 2026)
- Breaking Defense: [DAWG and Drone Dominance](https://breakingdefense.com/2025/12/its-alive-biden-era-replicator-drone-initiative-lives-on-as-dawg-looking-at-bigger-uass/) (December 2025)
- TechCrunch: [Anduril $20B Army contract](https://techcrunch.com/2026/03/14/us-army-announces-contract-with-anduril-worth-up-to-20b/) (March 14, 2026)

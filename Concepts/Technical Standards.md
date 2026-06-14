---
type: concept
category: technology/political-economy
tags: [concept, technology, standards, governance, political-economy]
---

# Technical Standards

## Definition

Technical standards are the agreed specifications that let products, networks, and software interoperate — from the width of a railway gauge to the protocols AI agents use to talk to each other. The power to set them is a form of **structural power** (Susan Strange's term): the standard-setter shapes the environment everyone else must operate within, often invisibly and durably. Whoever writes the standard captures licensing rents, embeds its own values and assumptions into the technology, and forces rivals to build on its terms. Standard-setting has become an explicit arena of great-power competition — a quieter complement to [[Technology Competition]], [[Techno-Nationalism]], and export controls.

## Why standards are geopolitical

Standards create lock-in. Once adopted, network effects and switching costs make them extraordinarily sticky — control of a standard can outlast control of a product. Three things make this strategic:

- **Rents** — owners of standard-essential patents collect royalties on every device that complies (the 3G/4G/5G patent pools are the classic case; Qualcomm and, increasingly, Huawei).
- **Embedded values** — a standard encodes choices about privacy, surveillance, censorship, and control. An internet architecture that makes traffic easy to trace is a political artifact, not a neutral one.
- **First-mover advantage** — early standards shape the whole stack built on top, so setting the standard for an emerging layer (today: AI agents) is a bid to shape the next decade's digital economy.

## Three models of standard-setting power

The major powers pursue standard-setting through structurally different channels:

| Power | Channel | Mechanism |
|-------|---------|-----------|
| United States | Firm-led, de facto | Dominant private firms set market standards; multi-stakeholder bodies (IETF, IEEE, W3C) |
| China | State-led, de jure | National strategy to capture formal standards bodies (ISO, IEC, ITU) and export standards via [[Belt and Road Initiative]] |
| European Union | Regulation-led | Sets rules of market access; the [[#The Brussels Effect\|Brussels Effect]] makes EU compliance a global default |

### United States — de facto standards by dominant firms

The US has historically set standards through market dominance rather than state direction. Its internet-era standards emerged from the **multi-stakeholder** model — industry, academia, and civil society in bodies like the IETF and ICANN, not governments. The current frontier is the AI-agent protocol layer, where the de facto standards are again US-firm-originated (see below). The state's role is mostly indirect (procurement, [[Export controls]], antitrust), though the [[American AI Export Program]] and the push to make US AI models a global default are a more deliberate standards play.

### China — Standards 2035 and the state as rule-maker

China treats standard-setting as statecraft. **China Standards 2035**, a sequel to Made in China 2025, reframes the goal from manufacturing dominance to controlling "the rules and systems of production and transactions" — moving from the world's factory to its rule-maker. The strategy has several arms:

- Placing Chinese officials in leadership of international standards bodies (ISO, IEC, ITU working groups) to expand China's "discursive power" over the rules.
- The **New IP** proposal — unveiled by Huawei at the ITU in 2018 — would have replaced the internet's decentralized architecture with a more centralized, state-controllable design. It was rejected at the ITU (critics warned it would enable surveillance and fragment the net), but the effort persists through domestic "future internet" testbeds.
- The **Digital Silk Road**, exporting Chinese standards, equipment, and architecture across [[Belt and Road Initiative]] partners, so adopting countries build on Chinese rather than Western specifications.

A recurring tension: China favors **multilateral** governance (state-to-state, via the UN's ITU) over the **multi-stakeholder** model (industry/civil-society-led, via IETF/ICANN) — because the former gives governments more control over the rules.

### European Union — regulation as a standard

Lacking dominant platform champions, the EU sets standards through **market-access regulation**. The [[#The Brussels Effect\|Brussels Effect]] (Anu Bradford, Columbia Law) describes how the size of the single market forces global firms to comply with EU rules everywhere, exporting EU standards by default. Instruments include the GDPR, the [[AI Act]], the DSA/DMA, and the **EU Data Act** (in force 2025), which mandates interoperability, curbs cloud vendor lock-in, and phases out data-egress fees by 2027 — a direct attempt to legislate the kind of portability that US firms otherwise control through proprietary formats. This is [[Digital Sovereignty]] pursued through rule-writing rather than invention.

## The agentic-AI frontier (2025–26)

The newest standards battleground is the set of protocols AI agents use to reach tools, talk to each other, and read organizational knowledge. As of mid-2026 these are almost entirely US-firm-originated, with governance migrating to neutral foundations to win cross-industry adoption:

| Standard | Function | Originator | Governance |
|----------|----------|------------|------------|
| MCP (Model Context Protocol) | Agent ↔ tools/data | Anthropic (Nov 2024) | Agentic AI Foundation (Linux Foundation), Dec 2025 |
| A2A (Agent2Agent) | Agent ↔ agent | Google (Apr 2025) | Linux Foundation, June 23 2025; 100+ firms |
| Open Knowledge Format | Org knowledge → agents | Google (Jun 2026) | Google repo, contributions invited |
| Open Semantic Interchange | Semantic/metric model | Snowflake consortium (Sep 2025) | 50+ vendor consortium |
| llms.txt | Website → LLMs | Answer.AI (Sep 2024) | Community proposal |

The strategic pattern: a US firm publishes a protocol, then donates it to a neutral foundation precisely to defuse the "single-vendor control" objection and accelerate adoption — the soft-power move of making your standard the commons so that the ecosystem, rents, and tooling accrue to you anyway. China is conspicuously absent from these specific protocols, consistent with its preference for building parallel domestic stacks rather than adopting Western-origin standards. If the agentic economy standardizes on these interfaces, the rules of how autonomous software acts in the world will have been written, once again, by American firms — the structural-power question restated for the AI era.

## The Brussels Effect

The mechanism by which EU regulation becomes a global standard: because the EU market is too large to forgo and compliance is cheaper to apply globally than to bifurcate, multinationals adopt EU rules worldwide. Coined by Anu Bradford (Columbia Law). It is the EU's substitute for de facto standard-setting power — it cannot make the dominant platforms, so it writes the rules they must follow to sell into Europe.

## Stakes

- **Structural power** — setting the standard is a durable, low-visibility form of control that outlasts any single product cycle.
- **Fragmentation risk** — if powers entrench incompatible standards, the result is a [[Splinternet]] of standards: separate technical universes (Chinese New IP vs the IETF internet; sovereign clouds vs hyperscalers).
- **Values lock-in** — standards bake in assumptions about surveillance, openness, and control that are hard to reverse once adopted at scale.
- **Multi-stakeholder vs multilateral** — beneath the specific fights is a governance contest: bottom-up, industry-led standard-setting (US/EU-defended) versus top-down, state-led standard-setting (China-preferred). The outcome shapes who gets a vote on the rules of the digital world.

## Related Concepts

- [[Technology Competition]] — standards are one of its quietest, most durable instruments
- [[Techno-Nationalism]] — standards as a tool of technology-bloc formation
- [[Digital Sovereignty]] — the EU's regulation-as-standard strategy
- [[Splinternet]] — what incompatible standards produce
- [[Internet Geopolitics]] — the multi-stakeholder vs multilateral governance contest
- [[Chokepoint Power]] — standards as control points in the stack
- [[Digital Colonialism]] — exporting standards as a form of dependency
- [[Data as a Factor of Production]] — the asset the agentic-standards layer organizes
- [[Belt and Road Initiative]] — the Digital Silk Road export channel
- [[Milton Mueller]] — internet-governance scholar on multi-stakeholder vs multilateral models

### Cross-vault
- [Technologies: Open Knowledge Format](obsidian://open?vault=technologies&file=Open%20Knowledge%20Format) — the technical spec for one agentic-AI standard
- [Technologies: MCP](obsidian://open?vault=technologies&file=MCP) — the agent-to-tool protocol layer
- [Investing: Data catalog disruption](obsidian://open?vault=investing&file=Concepts%2FData%20catalog%20disruption) — the market read-through of the OKF/OSI standards contest

## Sources

- China Standards 2035 / "from manufacturing powerhouse to global rule-maker" — analyses via The Diplomat (2021), Horizon Advisory, Leiden Asia Centre
- New IP at the ITU — Chatham House (2022), TIA, Internet Society analyses; Huawei proposal 2018
- EU Data Act (interoperability, anti-lock-in, egress-fee phase-out by 2027) — in force 2025; Fenwick, TechInformed summaries
- Brussels Effect — Anu Bradford, *The Brussels Effect* (Columbia Law)
- A2A donated to the Linux Foundation — Linux Foundation press release, June 23 2025

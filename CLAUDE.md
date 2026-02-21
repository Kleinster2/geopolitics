# Claude Code Instructions for Geopolitics Vault

## Project Overview
Obsidian vault building a comprehensive knowledge base of geopolitics: actors, concepts, frameworks, and events. Uses wiki-style linking (`[[Note Name]]`) and YAML frontmatter.

### Scope Principle
**All geopolitically relevant information is equally relevant.** The vault is not limited to "active" or "trending" topics. Information is incorporated based on its relevance to understanding global dynamics—not because we have recently worked on it or because it is in the news cycle.

Recent developments and active flashpoints are tracked as **additional** information layered onto this broader base. A Cold War-era treaty framework, a 19th-century geopolitical concept, and today's breaking crisis are all valid subjects if they contribute to understanding how the world works.

Do not filter information by recency or activity level. Filter by relevance to the structure of international relations.

## Folder Structure
```
geopolitics/
├── Actors/           # States, organizations, decision-makers
├── Thinkers/         # Academics whose frameworks shape discourse
├── Analysts/         # Commentators who interpret events
├── Concepts/         # Theories, frameworks, terms
├── Current Events/   # Ongoing situations, flashpoints
├── Daily/            # Daily notes tracking changes
├── Regions/          # Geographic areas
├── Templates/        # Note templates
```

## Note Types

| Type | Folder | Examples |
|------|--------|----------|
| Country | Actors | [[United States]], [[China]], [[Brazil]] |
| Organization | Actors | [[NATO]], [[BRICS]], [[United Nations]] |
| Decision-maker | Actors | [[Elbridge Colby]], [[María Corina Machado]] |
| Think Tank | Actors | [[CFR]], [[Chatham House]] |
| Thinker | Thinkers | [[Hal Brands]], [[Stephen Walt]], [[Ian Bremmer]] |
| Analyst | Analysts | [[Maurício Moura]], [[Roberto Dumas]] |
| Concept | Concepts | [[Deterrence]], [[Hegemony]], [[Melian Dialogue]] |
| Flashpoint | Current Events | [[Taiwan]], [[Greenland Crisis]] |
| Region | Regions | [[Middle East]], [[Asia-Pacific]] |

## Principles

### Bidirectional Linking
Obsidian shows backlinks automatically in sidebar. Explicit "Related Concepts" sections are for **intentional navigation** - curated paths, not exhaustive lists.

Think of it like a museum: backlinks show everything that mentions a topic, but Related Concepts is the curated "you might also like" that guides exploration.

**Add to Related Concepts if:**
- Conceptually central to understanding the topic
- Reader would likely want to navigate there
- Key sub-concept or example
- Mutual relevance (both notes benefit)

**Don't add if:**
- Tangential or passing mention
- Structural reference (indexes, templates)
- Would bloat the list

**Example - International Order:**
- ✅ [[Melian Dialogue]] - Essential for understanding 2026 order erosion
- ✅ [[Hal Brands]] - Primary analyst of developments
- ✅ [[UNCLOS]] - Supports Freedom of Navigation section
- ❌ [[Council on Foreign Relations]] - They study it, but tangential
- ❌ [[Concepts Index]] - Structural, not conceptual

**Hub notes** (International Order, United States, China, Russia, NATO) - be extra selective about what links back, or Related sections become unmanageable.

### Creating Notes
1. Use YAML frontmatter (see `Templates/` folder)
2. Add to relevant index (`Actors/Index.md`, `Concepts/Index.md`, etc.)
3. Link to related notes using `[[Note Name]]`
4. Apply bidirectional linking principle above

### Processing Articles/News
1. Identify which existing notes need updating
2. Create new concept notes for important terms
3. Link concepts back to source analysis
4. Update all relevant indexes
5. Check for orphan links that should become notes
6. **Maintain attribution** - Track who said what; don't flatten analysis into anonymous facts

### Deep Research
**Always run deep research.** Every note creation or update session should include background research subagents to verify facts, catch gaps, find corrections, and identify missing related concepts.

This is not optional and is not limited to "active" topics. A note on the Treaty of Westphalia deserves the same research rigor as a note on today's crisis. The vault's value depends on accuracy, and accuracy requires verification against current sources.

**What it catches:**
- Outdated numbers (e.g., arsenal estimates that changed)
- Date errors (e.g., proposal was September, not February)
- Missing major developments (e.g., treaties signed while you weren't looking)
- Related concepts that should exist but don't
- Expert voices to add as Analysts/Thinkers
- Contradictions between vault content and current scholarship
- New analytical frameworks applied to established topics

**Workflow:**
1. Create/update notes from source material
2. Launch background research subagents on the topic cluster (multiple in parallel when possible)
3. Continue other work while they run
4. Review findings: apply corrections, create suggested notes, add new sources

**For broad update sessions** (e.g., "what's new"), launch parallel research agents across all major topic areas—not just the ones recently edited. The goal is to surface developments the vault hasn't captured yet, regardless of which notes were last touched.

## Style

### Formatting
- No emojis unless requested
- Tables for structured comparisons
- Blockquotes for key quotes with attribution
- H1: Note title only; H2: Major sections; H3: Subsections

### Dates
- YAML: `2026-01-15` (ISO format)
- Text: January 15, 2026 (readable)

### Sources
- Add Sources section at bottom when based on specific articles
- Summarize rather than reproduce copyrighted text
- Short quotes (<15 words) with attribution are fine

### Attribution & Intellectual Rigor

**This vault prioritizes accuracy over volume.** Every claim should be traceable to its source.

**Distinguish between:**
- **Verified facts**: Events that happened, official statements, published data
- **Analysis/characterization**: Someone's interpretation, framework, or argument
- **Unverified claims**: Assertions without clear sourcing

**Attribution rules:**
1. **Always name the source** when recording someone's analysis or interpretation
   - ❌ "The 2025 NSS identifies 4 theaters"
   - ✅ "Victoria Coates (Heritage) argues the 2025 NSS identifies 4 theaters"

2. **Full identifier on first reference per note** - Name + affiliation so future readers know who this is
   - ❌ "Dumas argues..."
   - ✅ "Roberto Dumas (Insper economist) argues..." then "Dumas" for subsequent references

3. **Don't launder opinions as facts** - If an analyst says X, write "Analyst argues X," not just "X"

3. **Flag uncertainty** - Use phrases like "per [source]," "according to," "[source] claims"

4. **Preserve the chain** - When processing transcripts/articles, note who said what, don't flatten into anonymous assertions

5. **Primary vs secondary** - Prefer primary sources; when using secondary, note it
   - ✅ "Trump told NYT: 'It's psychological'"
   - ⚠️ "Coates says the 2025 NSS prioritizes Western Hemisphere" (her characterization, not the document)

**When in doubt, attribute.** It's better to over-cite than to present contested claims as settled fact.

**Red flags to catch:**
- Statements without a clear "who says this?"
- Frameworks presented as objective truth
- Death tolls, statistics without sourcing
- Policy descriptions not tied to documents or officials

### Inclusion Standards

**Attribution does not justify inclusion.** Just because someone said something doesn't mean it belongs in the vault.

**Include if:**
- Verifiable fact (events, data, official statements)
- Testable analytical framework (can be checked against observable behavior)
- Established theory with academic grounding
- Direct quote that illuminates a position

**Exclude even if attributed:**
- Unverifiable claims (unnamed sources, private meetings, internal deliberations)
- Assertions about others' psychology or motivations
- Characterizations contradicted by observable behavior
- Politically loaded labels presented as analysis

**The core issue is verifiability, not source type.**

Unnamed sources are still sources—not opinion. But claims based on them can't be:
- Confirmed (did the source exist? say that?)
- Checked (is the source in position to know?)
- Updated (how do we know when it's no longer true?)

Journalism relies on unnamed sources to break news. This vault builds durable knowledge. Different purposes, different standards.

**The test:** Could this be wrong, and would we ever know?

**Examples:**

| Claim | Verdict | Reason |
|-------|---------|--------|
| "Brazil exports to China up 6%" | ✅ Include | Verifiable trade data |
| "Twin deficits identity means X" | ✅ Include | Established economic framework |
| "Trump quickly perceived it wasn't a winning cause" | ❌ Exclude | Unverifiable (his perception) |
| "Rubio faction believes only China matters" | ❌ Exclude | Unverifiable + contradicted by observable behavior |
| "Republican sources describe it as very risky" | ❌ Exclude | Unverifiable (unnamed sources) |
| "China's response was more for appearances" | ❌ Exclude | Unverifiable (motivation) |

**Volume is not value.** A sparse vault of verified facts beats a cluttered one full of unverifiable claims.

### Person Note Criteria

People go in different folders based on their role:

| Category | Folder | Who | Examples |
|----------|--------|-----|----------|
| **Actors** | Actors/ | Decision-makers - officials, leaders | Colby, Machado |
| **Thinkers** | Thinkers/ | Academics shaping discourse | Brands, Walt, Mearsheimer |
| **Analysts** | Analysts/ | Commentators interpreting events | Moura, Dumas, Loureiro |

**All cited people get notes.** The folder reflects their role, not their importance.

**The distinctions:**
- **Actors** make decisions that shape events
- **Thinkers** create frameworks that influence how actors think
- **Analysts** interpret and explain what's happening

### Handling Conflicting Sources

Sources often disagree, especially on:
- Death tolls (government vs. activists vs. international observers)
- Economic figures (official vs. independent estimates)
- Motivations and intentions
- What actually happened in closed-door meetings

**Approach:**
1. **Present the range** - Don't pick one number; show the spread
   - ✅ "Death toll estimates range from 2,500 (HRANA) to 10,000+ (activist estimates)"
   - ❌ "10,000 killed"

2. **Name each source** - Let reader assess credibility
   - ✅ "Iranian government claims 200; Amnesty International reports 2,500+"

3. **Note the bias** - Governments undercount; activists may overcount; both have incentives

4. **Don't split the difference** - The truth isn't always in the middle

### Confidence Markers

Use these markers to signal certainty level:

| Marker | Meaning | Example |
|--------|---------|---------|
| **(confirmed)** | Multiple reliable sources, official records | "Maduro captured (confirmed)" |
| **(reported)** | Credible reporting, not independently verified | "Banks failing (reported, Coates)" |
| **(claimed)** | Single source assertion, possibly biased | "800 hangings cancelled (claimed, Trump)" |
| **(disputed)** | Sources actively contradict each other | "Death toll disputed: 2,500 to 12,000" |
| **(unverified)** | Plausible but no solid sourcing | "Possibly 4-5x higher (unverified)" |

When updating notes with new information, add the marker rather than just stating the claim.

### Updating Contradictory Information

When new information contradicts existing notes:

1. **Don't silently overwrite** - Keep record of evolution
2. **Add, don't delete** - Unless prior info was clearly wrong
3. **Date the update** - "As of January 2026..." or use Latest section
4. **Note the contradiction** - "Earlier reports said X; now Y"
5. **Explain if possible** - Why did the story change?

**Example structure:**
```
## Death Toll
- **Initial reports (Jan 8)**: 1,850 (HRANA)
- **Updated (Jan 14)**: 2,403 (HRANA)
- **Activist estimates (Jan 18)**: 2,500+, possibly 4-5x higher (unverified)
```

### Statistics and Numbers

Numbers require extra rigor because they create false precision.

**Always ask:**
- Who produced this number?
- What's their methodology?
- What's their incentive?
- Is this an estimate, count, or projection?

**Common traps:**
- GDP figures for sanctioned economies (often guesses)
- Casualty figures in active conflicts (fog of war)
- Refugee/migration numbers (definitional issues)
- Poll numbers (methodology matters)

**Best practice:** Give ranges, name sources, note uncertainty.

## YAML Frontmatter

Every note needs frontmatter. Common patterns:

**Country:**
```yaml
---
type: country
region: [region]
population: [number]
gdp: [amount]
government: [type]
tags: [country, region, ...]
---
```

**Concept:**
```yaml
---
type: concept
category: [theory|security|economics|...]
tags: [concept, ...]
---
```

**Person:**
```yaml
---
type: person
affiliation: [institutions]
focus: [areas]
tags: [thinker, ...]
---
```

## Daily Notes

### Purpose
Track vault changes and developments each session. Located in `Daily/` folder with format `YYYY-MM-DD.md`.

### Requirement
**Always log all vault changes.** Every session that creates or updates notes must be recorded in the daily note. This is mandatory, not optional.

### When to Update
- When creating any new note
- When updating any existing note
- When processing news or articles
- At end of work sessions

### Template Sections
- **Key Developments**: News or events analyzed
- **Notes Created**: New notes added
- **Notes Updated**: Existing notes modified
- **Sources Consulted**: Articles, podcasts, reports used
- **Follow-ups**: Questions or tasks for future sessions

### In Obsidian
Configure daily notes plugin to use `Daily/` folder and `Templates/Daily Note.md` template.

## Maintenance

### Index Updates
When creating new notes, update relevant indexes:
- `Actors/Index.md`
- `Concepts/Index.md`
- `Current Events/Index.md`
- `Regions/Index.md`

### Orphan Links
Periodically check for referenced notes that don't exist and create them.

## Cross-Vault Linking

The **investing vault** (`C:\Users\klein\financial-charts\investing\`, Obsidian vault name `investing`, repo `Kleinster2/financial-charts`) covers the same topics from a market/trade angle. When a note has a meaningful counterpart in the other vault, add clickable `obsidian://` URI links.

**Format:**
```markdown
### Cross-vault
- [Investing: Note Name](obsidian://open?vault=investing&file=Folder%2FNote%20Name) — what the other perspective adds
```

**Rules:**
- Place under `### Cross-vault` subheading at end of Related section (before Sources if present)
- URL-encode paths: spaces → `%20`, slashes → `%2F`
- Brief description of what the other vault's perspective adds
- Only cross-link notes with meaningful counterparts — not every shared entity
- These links won't appear in graph view or backlinks — navigation aids only

---

## Current Context (February 2026)

Major ongoing situations:
- Trump 2.0 reshaping international order
- [[New START Expiration]] - Last US-Russia nuclear treaty expires Feb 5
- [[Greenland Crisis]] - US threatening NATO ally, Golden Dome connection
- [[Venezuela]] - US intervention (Operation Absolute Resolve)
- [[Ukraine Crisis]] - France/UK troop deployment
- [[Iran Protests 2025-2026]] - Regime crisis
- [[Taiwan]] - Largest-ever Chinese military exercises
- [[China Nuclear Program]] - Rapid expansion toward parity

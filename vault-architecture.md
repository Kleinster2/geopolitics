# Vault Architecture

Three Obsidian vaults form an integrated knowledge system. Each covers the same world from a different temporal and analytical lens.

## The Three Vaults

| Vault | Path | Obsidian Name | Repo | Lens |
|-------|------|---------------|------|------|
| **Investing** | `~/financial-charts/investing/` | `investing` | `Kleinster2/financial-charts` | Market positioning, investment flows, company analysis, forward theses |
| **Geopolitics** | `~/obsidian/geopolitics/` | `geopolitics` | `Kleinster2/geopolitics` | Statecraft, alliances, power dynamics, diplomatic frameworks |
| **History** | `~/obsidian/history/` | `history` | `Kleinster2/history` | Long-arc economic progress, how we got here |

## How They Relate

```
        History
       (backstory)
       /        \
      /          \
  precedent    precedent
  + breaks     + breaks
    /              \
   v                v
Investing  <----->  Geopolitics
(markets)   feed    (statecraft)
```

### Investing <-> Geopolitics (two-way feed)
- Same events, different lenses. Overlap is expected and desirable.
- **Post-ingestion gate**: after creating a new event or major update in either vault, ask whether it also belongs in the other.
- Investing includes geopolitical context when it affects investment flows. Geopolitics includes economic context when it shapes statecraft.
- Don't strip content just because it "belongs" in the other vault — strip it only if it's irrelevant to the host vault's purpose.

### History -> Investing/Geopolitics (precedent lookup)
- When writing about a topic with deep historical roots (sanctions, trade wars, infrastructure control, monetary policy, commodity economics, alliance theory, etc.), check the history vault for relevant precedent.
- The history vault provides the backstory; the other two apply it to the present.

### Investing/Geopolitics -> History (structural breaks)
- When an event represents a genuine first-of-its-kind precedent or structural break (novel sanctions mechanism, new form of economic statecraft, industry-reshaping consolidation, institutional transformation), flag it for the history vault.
- Today's inflection points become tomorrow's history.

### History vault scope
- Not just civilizational themes — includes business and institutional history that explains the present.
- Investing vault actor notes include an **Evolution** section (key inflection points explaining current positioning). The history vault provides the broader arc those company stories sit within.

## Cross-Vault Links

Use clickable `obsidian://` URI links for cross-references between vaults.

**Format:**
```markdown
### Cross-vault
- [Vault: Note Name](obsidian://open?vault=VAULT&file=Folder%2FNote%20Name) — what the other perspective adds
```

**Rules:**
- Place under `### Cross-vault` subheading at end of Related section (before Sources if present)
- URL-encode paths: spaces -> `%20`, slashes -> `%2F`
- Brief description of what the other vault's perspective adds
- Only cross-link notes with meaningful counterparts — not every shared entity
- These links won't appear in Obsidian graph view or backlinks — they're navigation aids only

## Principles

1. **Overlap is desirable** — both forward-looking vaults need core facts; each adds its own lens
2. **Don't silently skip** — the default is to flag cross-vault relevance to the user
3. **Routine updates don't trigger cross-vault gates** — only new events and major updates
4. **Each vault follows its own conventions** — the investing vault has compliance checks, chart requirements; the geopolitics vault has attribution standards, confidence markers; the history vault has period structure and predecessor research

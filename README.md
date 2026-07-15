# Learn AI Safety — Neural Map

An explorable, Obsidian-style knowledge graph of the AI safety field: **64 concepts** across **8 tracks**, connected by **161 edges**, with ~200 curated links to the best available papers, courses, wikis, and articles. Inspired by [learnanything.xyz](https://learnanything.xyz).

**Live demo:** open `index.html` in any browser — that's the whole site.

## What's in the map

| # | Track | Covers |
|---|-------|--------|
| 01 | Foundations | What AI safety is, ML/transformer basics, scaling laws, timelines |
| 02 | Core risk arguments | Alignment problem, specification gaming, power-seeking, deceptive alignment, x-risk debate |
| 03 | Technical alignment | RLHF, Constitutional AI, scalable oversight, AI control, ELK, agent foundations |
| 04 | Interpretability | Superposition, sparse autoencoders, circuits, CoT monitoring, hands-on tools |
| 05 | Evaluations & red-teaming | Dangerous capability evals, propensity evals, benchmarks, safety cases |
| 06 | Governance & policy | Compute governance, RSPs, AI safety institutes, EU AI Act, summits, open weights |
| 07 | Frontier & adjacent | Forecasting, AI welfare, multi-agent safety, economics of TAI |
| 08 | Getting involved | Career paths, courses & fellowships, jobs, funding, staying current |

Each node carries a plain-language summary plus typed, attributed resource links (paper / course / wiki / video / org / tool).

## Using the map

- **Scroll** to zoom, **drag** the background to pan, **drag nodes** to rearrange (physics reacts)
- **Hover** a node to highlight its neighborhood
- **Click** a node for its summary, resources, and connected concepts
- **Search** (top bar) to spotlight matching concepts
- **Legend** (bottom left) toggles tracks on/off

Suggested path: start at the *Foundations* hub and follow the chain; cross-track edges show where ideas connect (e.g. *Deceptive alignment → AI control → Chain-of-thought monitoring*).

## Files

| File | Description |
|------|-------------|
| `index.html` | The neural map — deploy-ready, fully self-contained (D3 v7.9.0 inlined, zero external requests) |
| `learn-ai-safety.html` | Alternative dashboard view: same content as a searchable checklist with progress tracking |
| `Learn-AI-Safety-Vault.zip` | The same map as a real Obsidian vault (73 linked markdown notes) |


## Security & privacy

- No cookies, storage, forms, analytics, or network requests — nothing about visitors is collected or transmitted
- D3 is inlined from the official npm distribution (no CDN, no supply-chain exposure)
- Strict Content-Security-Policy blocks external scripts/styles/embedding; all outbound links use `rel="noopener noreferrer"` with a `no-referrer` policy
- External resource links (arXiv, BlueDot, etc.) load only when clicked


# wikiclaw brand

The identity is derived from the wiki's own marketing knowledge, not picked for looks. Two
concept pages drove every decision:

- **`differentiation-and-positioning`** — "brands happen in the minds of consumers"; a
  difference is only worth promoting if it's *distinctive, superior, and **preemptive***. So the
  brand leads with the one thing RAG tools (NotebookLM, ChatGPT uploads) **cannot** claim:
  knowledge that *compounds into a persistent, interlinked graph* instead of being re-derived on
  every query (`llm-wiki-pattern`), an asset that only grows (`building-an-asset-base`).
- **`branding-strategy`** — position at the *strongest* level, **beliefs & values**, not
  *product attributes* ("weakest — easily copied"). So the mark depicts the **belief** (connected,
  compounding knowledge), and the name was checked against the book's name test (suggests the
  category *wiki* + the LLM *claw/Claude*; distinctive; memorable; registrable).

## The mark — "constellation"

An **`index.md` hub** (cream node) from which **associative trails** (Vannevar Bush's Memex
lineage, per `llm-wiki-pattern`) sweep out to **knowledge nodes**, with the outer nodes
*cross-linked* — a small interlinked graph that also reads as a **claw** (the LLM that maintains
it). It encodes the differentiator directly: a graph that accumulates and connects.

## Positioning statement (Geoffrey Moore form, per `differentiation-and-positioning`)

> **For** knowledge workers and teams whose reading evaporates instead of accumulating,
> **wikiclaw** is an LLM-maintained wiki that compiles every source into a persistent, interlinked
> graph and keeps it current.
> **Unlike** RAG tools that re-derive answers from scratch every time, wikiclaw's knowledge
> **compounds** — and it's just a git repo of markdown you own.

Value proposition: **more for less** (more: compounding, owned, linkable, private · less: free,
open, plain markdown).

## Assets

| File | Use | Size |
| --- | --- | --- |
| `wikiclaw-avatar.svg` / `.png` | **Org avatar** — constellation on ink. Primary. | 1024² (+ `-512`) |
| `wikiclaw-avatar-coral.svg` / `.png` | Inverse avatar — ink graph on coral. | 1024² |
| `wikiclaw-mark.svg` | The mark alone (no background), for embedding | vector |
| `wikiclaw-mark-mono.svg` | **Monochrome** single-color mark (`currentColor`) — stamps, one-color contexts | vector |
| `favicon.svg` + `favicon-{16,32,48,512}.png` + `favicon.ico` | **Favicon** — simplified mark (cross-links dropped for legibility) on ink | 16–512 |
| `apple-touch-icon.png` | iOS/home-screen icon | 180² |
| `social-org.png` | Org / general social card | 1280×640 |
| `social-wikiclaw.png` | `wikiclaw/wikiclaw` repo social preview | 1280×640 |
| `social-skills.png` | `wikiclaw/skills` repo social preview | 1280×640 |

## Palette

| Token | Hex | Use |
| --- | --- | --- |
| Ink | `#1B1A17` | background |
| Ink tile | `#221F1B` | avatar tile on dark cards |
| Coral | `#D97757` | trails, nodes, "claw" in the wordmark |
| Cream | `#F4ECE2` | the hub node, "wiki" in the wordmark, light text |
| Muted clay | `#C9A38F` | subtitles |
| Muted grey | `#8A8078` | kicker / repo path |

Wordmark: **Noto Sans**, weight 800 — `wiki` cream + `claw` coral. The two-tone split mirrors the
positioning: *wiki* (the category) + *claw* (the LLM that earns the differentiator).

## Re-rendering

```sh
rsvg-convert -w 1024 -h 1024 wikiclaw-avatar.svg -o wikiclaw-avatar.png
```

## Applying (GitHub UI only — no API)

- **Org avatar:** Organization → Settings → Profile → *Profile picture* → upload `wikiclaw-avatar.png`.
- **Repo social preview:** repo → Settings → *Social preview* → upload the matching `social-*.png`.

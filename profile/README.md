# wikiclaw

**LLM-maintained knowledge wikis.** You curate the sources and ask the questions; an LLM agent
reads each book / article / talk / paper, extracts the durable ideas, and keeps a connected,
queryable wiki of source-neutral concept pages current. It's just a git repo of markdown — so
version history, browsing, and collaboration come for free.

### Why, not RAG?

RAG re-derives knowledge from scratch on every question and nothing accumulates. Here the agent
*integrates* each source as it arrives — updating concept pages, weaving in new claims, flagging
contradictions — so the wiki is a **persistent, compounding artifact** that gets richer with every
source added and every question asked.

### Repositories

- **[wikiclaw](https://github.com/wikiclaw/wikiclaw)** — the template. Clone it to start your own
  LLM-maintained wiki (schema + skills + conversion scripts + a worked demo source).
- **[skills](https://github.com/wikiclaw/skills)** — the four agent skills (`ingest-book`,
  `ingest-clip`, `lint-concepts`, `lint-coverage`), standalone for any project.

### Roadmap — a shared public corpus

The longer game is a **community-curated corpus** of ingested public content (openly-licensed
articles, public-domain books, talks) that compounds via cross-source links. Design principles we
intend to hold to:

- **Cathedral core, bazaar edges** — anyone contributes a source via PR; trusted maintainers own
  the integrity of the concept graph.
- **Idempotent ingestion as a merge gate** — the convergence test (order-independent concept
  pages) and the coverage test run as CI on every PR, so independently-ingested sources still
  converge to one wiki.
- **License-clean only** — the public corpus is restricted to public-domain / openly-licensed /
  fair-use-paraphrase material; copyrighted raw text stays out.
- **Topic-scoped corpora** rather than one unbounded mono-wiki.

Interested in helping shape it? Open an issue on the template repo.

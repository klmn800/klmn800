# Ben Keilman

Boston-based builder of internal AI tools - and the person who makes sure they actually get used.

I find what's broken in how a team works, build an AI-assisted tool to fix it, and drive the adoption that makes it stick. Operations-analyst judgment, three years building on the Anthropic API (RAG, agents, automation), and a background in training and enablement - so the tool ships *and* people use it.

## How I work

I work with Claude Code as a co-builder. That compresses "I have an idea" to "the tool exists and runs against real data" from weeks to hours - whether it's a one-afternoon utility or a system that grows over months. Everything pinned below was built this way: solo, end-to-end, against problems I or my colleagues actually had.

## What's here

- **policy-navigator** - My biggest RAG build: a multi-source RAG system over U.S. public-assistance (SNAP) policy. It indexes four authoritative sources - federal program regulations, the federal quality-control standard, a state's regulations, and that agency's ~1,200-page internal staff guide (10,000+ searchable chunks in a shared vector store) - so staff can ask a policy question and get a synthesized, cited answer. It also cross-checks the sources against each other to surface gaps and conflicts, drafts new policy pages from research, and analyzes quality-control error findings. FastAPI + HTMX web UI; Claude API for structured synthesis, Claude Code CLI for the agentic, resumable work. Proof the AI-assisted approach scales well past small tools.
- **options_scanner** - My longest-running system, now public: a personal options-flow research platform that has run unattended every trading day since 2025. Real-time flow monitoring over a ~820-symbol universe, open-interest time series, earnings intelligence, and a SQLite datalake whose main scan table holds 23M+ rows. It files its own bug reports into Claude Code sessions (autofix), and five autonomous Claude Code agents audit its data quality and research trades overnight - the agent framework is published separately as **agent_lab**. Shared as a read-only showcase.
- **doc-review-pipeline** - Batch document reviewer that pulls .docx attachments out of emails (.msg/.eml), runs them through Claude, and writes structured analysis to a tracker. Built to replace a manual review queue.
- **query-db-direct** - SQLite exploration tool with schema discovery and dynamic query suggestion. Designed so AI agents can use it as readily as humans can.
- **media-wall** - Local masonry-grid media viewer with autoplay, tagging, and filtering. A self-hosted alternative to cloud galleries.
- **archive-cracker** - Utility for recovering personal media from locked .rar archives.

More in progress.

## Background

Business Operations Analyst by day. The options_scanner system above is my own - a 100GB+ market-analytics datalake with a multi-agent system, built and operated solo as a live production system for over a year. I also run a freelance practice partnering with domain experts who have deep knowledge but limited engineering capacity (most recently a building-code RAG for an architecture firm). I'm used to translating between business problems and technical systems, scoping the work, shipping the fix, and making sure it gets adopted.

## What I'm looking for

Roles where I build the internal tooling an organization needs and help people adopt it - AI implementation and enablement, internal tools and automation, or applied AI engineering. Boston - in-office or hybrid preferred, open to remote.

## Reach me

[LinkedIn](https://www.linkedin.com/in/ben-keilman/)

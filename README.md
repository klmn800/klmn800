# Ben Keilman

Solutions Architect in Boston, looking for **GTM Engineer** roles.

I build AI-assisted tools that solve real workflow problems — from quick utilities
to full multi-source systems. The kind of internal leverage that revenue and
operations teams need but rarely have time to ship themselves.

## How I work

I work with Claude Code as a co-builder. That lets me move from "I have an idea" to
"the tool exists and runs against real data" fast — whether it's a one-afternoon
utility or a system that grows over months. Everything pinned below was built this
way: solo, end-to-end, against problems I or my colleagues actually had.

Pairing engineering with AI to compress build cycles is the same approach I'd bring
to a GTM Engineering team.

## What's here

- **policy-navigator** — My biggest build: a multi-source RAG system over U.S.
public-assistance (SNAP) policy. It indexes four authoritative sources — federal
program regulations, the federal quality-control standard, a state's regulations,
and that agency's ~1,200-page internal staff guide (10,000+ searchable chunks in a
shared vector store) — so staff can ask a policy question and get a synthesized,
cited answer. It also cross-checks the sources against each other to surface gaps
and conflicts, drafts new policy pages from research, and analyzes quality-control
error findings. FastAPI + HTMX web UI; Claude API for structured synthesis, Claude
Code CLI for the agentic, resumable work. Proof the AI-assisted approach scales well
past small tools.
- **doc-review-pipeline** — Batch document reviewer that pulls .docx attachments out
of emails (.msg/.eml), runs them through Claude, and writes structured analysis to a
tracker. Built to replace a manual review queue.
- **query-db-direct** — SQLite exploration tool with schema discovery and dynamic
query suggestion. Designed so AI agents can use it as readily as humans can.
- **media-wall** — Local masonry-grid media viewer with autoplay, tagging, and
filtering. A self-hosted alternative to cloud galleries.
- **archive-cracker** — Utility for recovering personal media from locked .rar archives.

More in progress.

## Background

Solutions Architect by trade. I'm used to translating between business problems and
technical systems, scoping work, and shipping fixes that stick. GTM Engineering is the
natural extension — same instinct for unblocking revenue motions, more code in the mix.

## Reach me

[LinkedIn](https://www.linkedin.com/in/ben-keilman/)

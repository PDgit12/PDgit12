# Piyush Dua

Building tools AI coding agents actually need: local-first memory, prompt-to-harness generation, and knowledge layers with real audit trails instead of blind trust.

[Portfolio](https://pdgit12.github.io/piyush-dua-portfolio/) · [LinkedIn](https://www.linkedin.com/in/piyush-dua-56b4aa2a1/)

## What I'm building

**[harnage](https://github.com/PDgit12/harnage)**: generates a complete, type-checked AI agent harness from a plain-language description, an alternative to a Claude Code or Goose subscription rather than a wrapper around one. Runs a compile-and-repair loop before handing anything back.

**[knitbrain](https://github.com/PDgit12/knitbrain)**: local-first memory layer so coding agents keep real context across sessions instead of re-reading the whole codebase every time. 37 MCP tools, roughly 46% token reduction on real usage, published on npm.

**[Comb](https://github.com/PDgit12/open-company-brain)**: self-hosted knowledge layer any AI tool can query, with cited answers and a full audit log. Requires human approval before any AI-proposed action executes.

**[ZenithDB](https://github.com/PDgit12/zenithdb)**: vector search engine written from scratch in C with hand-written SIMD, not a wrapper around a general-purpose library. 4.7x faster than a standard loop.

**Self-Healing Vision Model**: production vision-drift detection pipeline. Compares a student model against a frozen teacher model to catch accuracy drops without new labeled data, then repairs only the responsible part of the model instead of a full retrain.

## Stack

TypeScript · Python · C · PyTorch · PostgreSQL · Docker

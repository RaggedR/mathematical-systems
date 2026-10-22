# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

A literature review workspace for research on variable elliptic structures (VES) and related mathematics. Contains academic papers, AI-generated summaries, knowledge graphs, and a LaTeX document on VES combinatorics.

## Structure

- `papers/` — Source PDFs (arXiv papers on variable elliptic structures)
- `summaries/` — AI-generated LaTeX summaries of each paper
- `meta-summaries/` — Higher-level synthesis across papers
- `imagination/` — Exploratory LaTeX writing (VES combinatorics)
- `chroma_db/` — ChromaDB vector store for semantic search over papers
- `knowledge_graph.html` / `level2_knowledge_graph.html` — Interactive D3.js knowledge graphs
- `extraction_cache.json` — Cached concept extractions

## Key Commands

```bash
# View knowledge graph
open knowledge_graph.html

# Compile LaTeX
cd imagination && pdflatex ves_combinatorics.tex
```

## Notes

This is a research/reading workspace, not a software project. No build system or test suite.

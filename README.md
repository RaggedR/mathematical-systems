# Solarz

A literature review workspace for research on variable elliptic structures (VES) and related mathematics. Contains arXiv papers, AI-generated LaTeX summaries, higher-level synthesis documents, interactive D3.js knowledge graphs, and exploratory writing on VES combinatorics.

This is a research reading workspace, not a software project. No build system or test suite.

## Tech Stack
- ChromaDB (vector store for semantic search over papers)
- D3.js (interactive knowledge graphs)
- LaTeX (summaries and exploratory writing)

## Setup
```bash
# View interactive knowledge graphs
open knowledge_graph.html
open level2_knowledge_graph.html

# Compile exploratory LaTeX
cd imagination && pdflatex ves_combinatorics.tex
```

## License
MIT

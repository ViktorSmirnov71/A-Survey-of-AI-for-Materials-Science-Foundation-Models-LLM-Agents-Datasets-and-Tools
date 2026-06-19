# A Survey of AI for Materials Science: Foundation Models, LLM Agents, Datasets, and Tools

An MSci (Imperial College London, Department of Chemistry) **literature review and research
proposal** prepared around the survey paper of the same name, for the final-year research
project **"Project 5: AI agents for materials discovery."**

> Survey under review: Minh-Hao Van, Prateek Verma, Chen Zhao, Xintao Wu.
> *A Survey of AI for Materials Science: Foundation Models, LLM Agents, Datasets, and Tools.*
> arXiv:2506.20743, 2025.

## Project topic

Retrieval-Augmented Generation (RAG) couples large language models (LLMs) with external
knowledge so their answers are grounded in evidence, but LLMs remain weak at the continuous,
numerical reasoning that materials science demands. The project extends a materials-RAG
framework into a tool-using **LLM agent** that:

1. delegates **material property prediction** to dedicated machine-learning models (e.g. GNNs
   such as CGCNN / MEGNet), and
2. supports **query-based crystal generation** via diffusion models (e.g. CDVAE / MatterGen),

turning a literature-retrieval assistant into an end-to-end, query-driven discovery engine for
inorganic crystalline materials.

## Contents

| File | Description |
|------|-------------|
| `Literature_Review_Proposal.html` | The literature review + research proposal (open in a browser). |
| `Literature_Review_Proposal.pdf`  | Print-ready A4 version (Times New Roman; ~10-page body plus references). |
| `A SURVEY OF AI FOR MATERIALS SCIENCE- FOUNDATION MODELS, LLM AGENTS, DATASETS, AND TOOLS.pdf` | The source survey paper under review. |
| `Literature Review and Research Proposal 2026.pdf` | The MSci assignment brief. |

The review (~8 pages) funnels from foundation models and the AI-for-materials task landscape,
through RAG and LLM agents, property prediction, and generative/diffusion models, to the
integration gap the project addresses; the proposal (~2 pages) gives aims, objectives,
methodology, a month-by-month work plan, and a risk/fall-back assessment.

## Notes

- The document is a **draft** intended to be refined in the author's own voice; citation
  formatting should be verified in a reference manager before submission.
- All figures are original schematics (not reproductions of the survey's figures).
- Intermediate tooling artifacts (page renders, text extractions, QA screenshots) are not
  tracked; the deliverables above are self-contained.

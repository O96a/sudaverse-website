✅ UPDATED & REFINED SPECIFICATION — documentation.html REVAMP

Target file:

file:///C:/dev/sudaverse-website/sudaverse-website/documentation.html

1. New Introduction Section

Replace the current introduction with a clean, structured overview of the Sudaverse Ecosystem.

Requirements

Write a polished, welcoming introduction summarizing:

The purpose of the Sudaverse ecosystem

Its mission to build Sudanese-Arabic-centric AI tools

A high-level overview of the components (data pipelines, LLM tools, benchmarks, apps, etc.)

Reference content and structure from:

https://github.com/O96a/sudaverse

2. Remove Entire "Quick Start Guides" Section

This section is not needed and must be fully removed from the page.

3. Replace "API Documentation" with "Documentation"

Rename the section header:

Before:

API Documentation

After:

Documentation

NEW CONTENT FOR THIS SECTION

For each Sudaverse application below, create a clean sub-section with:

Title

Repository link

One-paragraph overview

Bullet-point features list (exact text below)

A — SuData

Repo: https://github.com/O96a/SuData

Description:
End-to-end data normalization and curation pipeline for Sudanese Arabic text processing.

Features:

Robust cleaning (noise, emojis, HTML)

Dialect-aware spelling normalization

PII removal & deduplication

Multiple export formats: JSON, JSONL, CSV

B — Corpus Refinery (LLMCorpusKit)

Repo: https://github.com/O96a/LLMCorpusKit

Description:
Large-scale Arabic corpus cleaning and polishing toolkit with AI-powered semantic repairs.

Features:

Deep-cleaning workflows

Sentence repair & structural fixing

API integration (Gemini & other LLMs)

Bulk and streaming processors

C — Synthetic Data Generator

Repo: Coming soon

Description:
High-quality Sudanese dialect synthetic text generator with regional awareness.

Features:

Region-aware dialect generation (Khartoum, Darfur, East, South)

Multiple formats (dialogue, scenarios, instructions)

Style & sentiment controls

Scalable generation pipeline

D — Sudanese Dialect Benchmark

Repo: Coming soon

Description:
Comprehensive tokenizer & model evaluation suite for Sudanese Arabic.

Features:

Tokenization accuracy metrics

Coverage tests for slang & variants

Multi-tokenizer comparison

Dialect fitness scoring

E — Data Hub (Planned)

Description:
A central registry and metadata catalog for all Sudanese Arabic datasets.

Planned Features:

Dataset manifests & licensing

Contributor credits & versioning

Sample previews

Download & API access

4. Datasets and Corpora (Keep, but Adjust)
Keep this section, but modify as follows:

Remove dataset size labels

Remove license labels

Change Dataset Access into:
“Access available upon request via email.”

Keep the table/list structure intact.

5. Models Zoo

Keep the Models Zoo section, but:

Remove all Download buttons or links

Replace with:
“Under development — planned models will be added soon.”

6. Remove Entire Sections

These sections must be fully deleted from the page:

Developer SDKs

Community and Support

Need More Information?

7. Keep

Only one section should remain unchanged:

Contribution Guidelines

✔ Final Expected Structure

Your updated documentation.html should follow this clean structure:

Introduction to the Sudaverse Ecosystem

❌ (Removed) Quick Start Guides

Documentation

SuData

LLMCorpusKit

Synthetic Data Generator

Sudanese Dialect Benchmark

Data Hub (Planned)

Datasets and Corpora (with modified access rules)

Models Zoo (marked as under development)

Contribution Guidelines

❌ (Removed) Developer SDKs

❌ (Removed) Community and Support

❌ (Removed) Need More Information?
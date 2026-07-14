# Eticas AI Risk Taxonomy (Public)

This is the public subset of the [Eticas AI Risk Taxonomy](https://eticas.ai) — a structured, machine-readable vocabulary of AI risk categories used across Eticas' audit methodologies, assessment frameworks, and reporting outputs.

This repository contains only the concepts and mappings that are already published on the public taxonomy site. The full internal taxonomy — including emerging and retired concepts, and the risk-assessment mechanisms layer — is proprietary to Eticas and maintained separately.

## What's in this repository

- `src/taxonomy.yaml` — established-maturity categories, sub-groups, and subcategories, with their definitions, scope, lifecycle stages, and mappings to external frameworks
- `src/mappings.yaml` — definitions of the external frameworks referenced in `taxonomy.yaml` (EU AI Act, NIST AI RMF, ISO/IEC 42001, MIT AI Risk Repository, and others)
- `src/config.yaml` — namespace and versioning metadata

## What's excluded

- Concepts marked `emerging` maturity or `retired` status
- The `mechanisms` field (internal risk-assessment methodology, not part of the public risk vocabulary)
- Editorial notes on individual frameworks in `mappings.yaml`

## License

Published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`.

## Citation

```
Eticas. (2026). Eticas AI Risk Taxonomy.
https://taxonomy.eticas.ai/risk/
```

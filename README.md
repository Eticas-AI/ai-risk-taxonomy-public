# Eticas AI Risk Taxonomy

Eticas AI Risk Taxonomy is a structured, machine-readable vocabulary of AI risks used across Eticas' audit methodologies, assessment frameworks, and reporting outputs. The taxonomy consolidates AI risks from diverse sources and aligns them with governance frameworks based on prior research, and  our real-world expertised in the field. 

This repository contains the concepts and mappings that are already published on the public taxonomy site.

Read the paper: [The Eticas AI Risk Taxonomy: Open Infrastructure for Operationalizing AI Audits](https://arxiv.org/abs/2607.02201)  
Browse the taxonomy: [taxonomy.eticas.ai](https://taxonomy.eticas.ai)

## Risk categories

The taxonomy is organized into eight top-level categories:

- **Bias & Fairness**
- **Privacy & Confidentiality**
- **Reliability**
- **Governance**
- **Security & Misuse**
- **Environmental Impact**
- **Transparency & Explainability**
- **Agentic AI**

## What's in this repository

- `taxonomy.yaml` — established-maturity categories, sub-groups, and subcategories, with their definitions, scope, lifecycle stages, and mappings to external frameworks
- `mappings.yaml` — definitions of the external frameworks referenced in `taxonomy.yaml` (EU AI Act, NIST AI RMF, ISO/IEC 42001, MIT AI Risk Repository, and others)
- `config.yaml` — namespace and versioning metadata

## License

Published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`.

## Citation

If you use this taxonomy in your work, please cite:

```bib
@article{galdonclavell2026eticas,
      title={The Eticas AI Risk Taxonomy: Open Infrastructure for Operationalizing AI Audits},
      author={Galdon Clavell, Gemma and Accuosto, Pablo and Gohar, Usman},
      year={2026},
      eprint={2607.02201},
      archivePrefix={arXiv},
      primaryClass={cs.CY},
      url={https://arxiv.org/abs/2607.02201},
}

```

Eticas. (2026). Eticas AI Risk Taxonomy.

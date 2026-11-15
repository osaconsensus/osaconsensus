# OSAConsensus — Human OSA × Animal CIH Transcriptomic Resource

**Live resource: https://osa.erbihou.org/**

OSAConsensus is a curated, uniformly reanalysed transcriptomic resource for obstructive sleep apnoea (OSA), built entirely from public data. It integrates human OSA cohorts with animal chronic intermittent hypoxia (CIH) models under one pipeline, and subjects every headline claim of the resource to a frozen, pre-declared adjudication.

## Contents

- **Human core:** 11 GEO series, 352 samples (peripheral blood and other tissues), plus an external adenoid single-cell atlas (23 donors, 238,093 cells)
- **Animal strict core:** 14 series, 249 samples (mouse CIH models), with a separate disease-background layer and a dedicated GSE214530 panel stratum
- **Adjudication:** of the resource's 22 headline claims, 18 stand, 3 are downgraded and 1 is revoked under the frozen rule set; every claim carries a stated evidence tier and permitted wording
- **Cross-species bridge:** animal CIH pathway profiles do not reproduce the human OSA blood profile — fidelity is reported as ranked positions only, never as "most human-like model" claims

## Website features

- **Cohorts** — full metadata for every curated series, human and animal
- **Gene lookup** — a gene's evidence across the human, animal and single-cell layers
- **Adenoid atlas** — the external single-cell atlas of adenoid tissue, with its severity-gradient results stated at their correct evidence tier
- **CPAP** — treatment-cohort views, including where reversal does and does not hold
- **Fidelity** — the cross-species comparison layer
- **Scorer** — in-browser scoring tools
- **Framework** — the ConsensusAudit claim-audit framework grown from this resource's production assets: https://osa.erbihou.org/framework.html (code: https://github.com/osaconsensus/ConsensusAudit)
- **Downloads & methods** — the frozen result tables, the full pipeline, and known limitations stated in full

## Data availability

All processed results, the curation table, the reproduction audit and the adjudication outputs are downloadable from the resource website (https://osa.erbihou.org). The frozen data archive is deposited on Zenodo (concept DOI: [10.5281/zenodo.24032136](https://doi.org/10.5281/zenodo.24032136); version 2: [10.5281/zenodo.24186895](https://doi.org/10.5281/zenodo.24186895)).

## Repository layout

- This repository is the static website itself, served via GitHub Pages at the address above.

## Contact

Peiliang Lei (of@live.com), Department of Otolaryngology, The Third Hospital of Shijiazhuang, Shijiazhuang, Hebei, China.

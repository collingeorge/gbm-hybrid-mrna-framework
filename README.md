# A Translational Framework for a Hybrid mRNA Vaccine Targeting Glioblastoma

## Integrating Innate Priming, Personalized Neoantigens, and Blood–Brain Barrier Penetrating Delivery

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)

> **Repository Description:** A theoretical framework proposing a hybrid mRNA vaccine strategy for Glioblastoma (GBM). It integrates innate immune priming, personalized neoantigens, and focused ultrasound (FUS) for blood-brain barrier (BBB) penetration to overcome immunoresistance.

---

## Author Information

- **Author:** Collin B. George, BS
- **Affiliation:** Independent Clinical Researcher & Medical School Applicant
- (University of Washington; research not affiliated with or endorsed by UW Medicine)
- **Initial Publication Date:** November 30, 2024  
- **Status:** Independent research manuscript, – Active Development
- **ORCID:** [0009-0007-8162-6839](https://orcid.org/0009-0007-8162-6839)

---

## Project Metadata

| Attribute | Details |
|-----------|---------|
| **Repository Initialization** | November 25, 2025 |
| **Document Type** | Narrative Review and Translational Framework |
| **Status** | Pre-print / Manuscript Under Preparation |
| **Keywords** | glioblastoma; mRNA vaccine; blood-brain barrier; neoantigens; focused ultrasound; immunotherapy; IL-12; RIG-I ligands |

---

## Abstract

Glioblastoma (GBM) remains lethal despite multimodal therapy, with median survival under 15 months. Immunotherapy has failed in over 100 clinical trials due to three fundamental barriers: inadequate immune priming in "cold" tumors, blood–brain barrier (BBB) exclusion of therapeutics, and profound local immunosuppression.

We present a **translational framework** for a hybrid mRNA vaccine that addresses all three barriers simultaneously:

1. **Innate Priming:** Universal innate immune primers (poly(I:C)/RIG-I ligands, IL-12) activate dendritic cells
2. **Adaptive Targeting:** Patient-specific neoantigen mRNA drives tumor-targeted T-cell responses
3. **BBB Penetration:** Peptide-modified lipid nanoparticles or focused ultrasound-guided delivery

Timed checkpoint blockade exploits vaccine-induced PD-L1 upregulation to unleash infiltrating T cells.

### Validation Strategy

We propose stepwise validation:
- **Computational modeling** to optimize dosing
- **In-vitro co-cultures** to confirm antigen presentation
- **Patient-derived xenografts** to demonstrate BBB crossing and tumor control
- **Phase I trial** using post-resection focused ultrasound delivery with PET and ctDNA endpoints

This approach aligns with current two-week manufacturing timelines and offers a modular strategy to convert GBM from immunologically cold to responsive.

---

## Repository Contents

```
.
├── main.tex              # Primary LaTeX source file
├── references.bib        # BibTeX citation database (2024-2025 focus)
├── figures/              # TikZ/PGFPlots source code and generated diagrams
│   ├── figure1_bbb.tex
│   ├── figure2_mechanism.tex
│   └── figure3_validation.tex
└── README.md             # This file
```

### File Descriptions

- **`main.tex`**: The primary LaTeX manuscript configured for standard academic document classes
- **`references.bib`**: BibTeX database with citations from clinical trials and translational studies (2024–2025)
- **`figures/`**: Source code (TikZ/PGFPlots) and generated assets for manuscript diagrams

---

## Compilation Instructions

This manuscript is written in **LaTeX**. To compile the PDF from source, a standard TeX distribution is required.

### Requirements

- **TeX Distribution:** TeX Live, MacTeX, or MiKTeX
- **LaTeX Packages:**
  - `geometry`, `amsmath`, `siunitx`, `booktabs`
  - `graphicx`, `tikz`, `pgfplots`
  - `enumitem`, `lineno`, `natbib`, `hyperref`

### Build Commands

#### Using `latexmk` (Recommended)

```bash
latexmk -pdf -pvc main.tex
```

#### Manual Compilation

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

#### Overleaf

1. Upload all files to a new Overleaf project
2. Set compiler to `pdfLaTeX`
3. Compile normally

---

## Citation Information

To cite this repository or the draft manuscript:

### BibTeX

```bibtex
@misc{George2025GBM,
  author       = {George, Collin B.},
  title        = {A Translational Framework for a Hybrid mRNA Vaccine Targeting Glioblastoma: 
                  Integrating Innate Priming, Personalized Neoantigens, and 
                  Blood--Brain Barrier Penetrating Delivery},
  year         = {2025},
  month        = {November},
  note         = {Pre-print repository},
  howpublished = {\url{https://github.com/[USERNAME]/gbm-hybrid-mrna-framework}},
  doi          = {[DOI if available]}
}
```

### APA Format

```
George, C. B. (2025). A translational framework for a hybrid mRNA vaccine targeting 
glioblastoma: Integrating innate priming, personalized neoantigens, and blood-brain 
barrier penetrating delivery [Manuscript in preparation]. University of Washington 
Medical Center. https://github.com/[USERNAME]/gbm-hybrid-mrna-framework
```

---

## Disclaimer

This independent narrative review was conducted as part of premedical research and **does not represent the views of UW Medicine**.

- No external funding was received for this conceptual framework
- No conflicts of interest declared
- No patents or proprietary technologies claimed

---

## License

This work is licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made

---

## Related Resources

- **ORCID Profile:** [0009-0007-8162-6839](https://orcid.org/0009-0007-8162-6839)
- **Contact:** [cbg24@uw.edu](mailto:cbg24@uw.edu)

---

## Project Status

- [x] Manuscript drafted
- [x] Figures generated (TikZ/inline)
- [ ] Peer review submission
- [ ] Pre-print publication
- [ ] Journal submission

---

## Acknowledgments

The author thanks mentors and colleagues at UW Medicine for valuable discussions on translational immunotherapy, focused ultrasound applications in neuro-oncology, and mRNA vaccine development. Special appreciation to the GBM research community for openly sharing clinical trial data and preclinical insights that informed this framework.

---

**Last Updated:** November 25, 2025  
**Repository Version:** 1.0.0

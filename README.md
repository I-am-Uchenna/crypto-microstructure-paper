# 📝 Root `README.md`


# Early Warning Detection of Liquidity Stress in Cryptocurrency Markets

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📌 Overview
This repository contains all materials related to the research paper **"Early Warning Detection of Liquidity Stress in Cryptocurrency Markets"**.  

Cryptocurrency markets are characterized by high volatility, fragmented liquidity, and frequent regime shifts. These conditions can result in sudden liquidity stress, which may trigger cascading effects across exchanges and asset classes.  

The objective of this project is to **design, implement, and evaluate early-warning indicators (EWIs)** that can detect the build-up of liquidity stress in digital asset markets.  

Specifically, we investigate:
- Statistical and econometric methods to measure liquidity dynamics.  
- Market microstructure signals (e.g., bid-ask spreads, order book depth).  
- Time series approaches (cointegration, regime-switching, structural breaks).  
- Machine learning–based risk indicators for stress detection.  

Our aim is to contribute to both the **academic literature on financial stability** and the **practical monitoring of cryptocurrency risks**, offering tools that can potentially be adopted by researchers, regulators, and industry practitioners.  

We plan to first release this work as a **preprint on arXiv** and subsequently target submission to **IEEE or other peer-reviewed venues**.

---

## 📂 Repository Structure

```bash
.
├── data/       # Small datasets, metadata
├── code/       # Python/R/Matlab scripts for analysis
├── paper/      # LaTeX drafts, figures, submission files
├── docs/       # Project documentation, notes, literature review
└── README.md   # Project overview (this file)
````

Each folder contains its own `README.md` to guide navigation and usage.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/liquidity-stress-crypto.git
cd liquidity-stress-crypto
```

### Requirements

* Python 3.10+
* R (optional, for additional econometrics)
* LaTeX (for compiling paper drafts)

Install Python dependencies:

```bash
pip install -r requirements.txt
```

---

## 🧑‍🤝‍🧑 Team Roles

* **Lead / Editor-in-Chief** – Scope, coherence, final edit, submission
* **Methods & Experiments Lead** – Liquidity measures, econometric analysis
* **Literature & Related Work Lead** – Survey of financial stability & crypto liquidity research
* **Results & Discussion Lead** – Experimental results, robustness checks, visualizations

---

## 🗓️ Project Timeline

* **Week 1** – Repository setup, task allocation, reference collection
* **Week 2** – Draft introduction & methodology, implement baseline models
* **Week 3** – Run experiments, gather results, refine visualizations
* **Week 4** – Assemble full draft, internal review, arXiv submission

---

## 📖 References

Key references and background materials are maintained in:

* `paper/references.bib` (for LaTeX citations)
* `docs/literature-review.md` (summary notes)

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


# 📂 `data/README.md`

# Data

This folder contains **datasets and metadata** used in the project.  
Due to size and confidentiality restrictions, only **small sample data** or synthetic versions are provided here.  

---

## 📌 Contents
- `sample_data.csv` – Example dataset for demonstration and testing.  
- `metadata/` – Notes on original data sources and collection process.  

---

## 🔗 Data Sources
The project makes use of:
- Public cryptocurrency market APIs (e.g., Binance, Coinbase).  
- Aggregated order book and trade data from [CryptoCompare](https://www.cryptocompare.com/).  
- Academic/research data repositories (when available).  

---

## ⚠️ Note
- **Raw, large-scale data is not hosted here.**  
- For replication, please refer to the instructions in `docs/methodology-notes.md` or contact the authors.  

# 📂 `code/README.md`


# Code

This folder contains all **scripts and code** used to process data, run models, and generate figures for the research paper.  

---

## 📌 Structure
- `preprocessing/` – Scripts for cleaning, transforming, and normalizing raw data.  
- `analysis/` – Econometric and statistical analysis methods.  
- `ml_models/` – Machine learning workflows for early-warning indicators.  
- `visualization/` – Scripts for plots, charts, and paper-ready figures.  
- `utils/` – Helper functions and configuration files.  

---

## ▶️ Usage
1. Prepare data (see `data/README.md`).  
2. Run preprocessing scripts:  

```bash
   python preprocessing/clean_data.py
````

3. Execute model analysis:

   ```bash
   python analysis/cointegration_test.py
   ```
4. Generate results and figures:

   ```bash
   python visualization/plot_liquidity_indicators.py
   ```

---

## 🔗 Dependencies

All requirements are listed in the root `requirements.txt`.


---

# 📂 `paper/README.md`

# Paper

This folder contains **drafts, figures, and submission files** for the research paper.  

---

## 📌 Structure
- `drafts/` – Working versions of the paper (LaTeX/Overleaf exports).  
- `figures/` – Final figures and diagrams used in the paper.  
- `references.bib` – Bibliography file for LaTeX.  
- `submission/` – Versions prepared for submission to arXiv / IEEE.  

---

## 📖 Workflow
1. Draft chapters in `drafts/`.  
2. Export figures from `code/visualization/` into `figures/`.  
3. Compile LaTeX using:
```bash
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex
````

4. Store final version in `submission/`.

---

## 🗂️ Citation Management

All references are centralized in `references.bib`.
Please update this file rather than embedding raw citations in LaTeX.

---

# 📂 `docs/README.md`


# Documentation

This folder contains **supporting documentation** for the project.  

---

## 📌 Contents
- `literature-review.md` – Summary of prior work on liquidity and financial stability.  
- `methodology-notes.md` – Technical notes on econometric models and machine learning methods.  
- `project-plan.md` – Timeline, milestones, and deliverables.  

---

## 🔗 Usage
- Use these notes to stay consistent across team contributions.  
- Update literature review as new papers are discovered.  
- Keep methodology notes synced with implemented code.  

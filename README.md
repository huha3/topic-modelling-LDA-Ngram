# Topic Modelling of Mathematics Undergraduate Theses at PTKIN in Java Using LDA + N-gram

This repository contains the **public research artifacts** for the study on **topic modelling of undergraduate thesis abstracts from Mathematics Study Programs at PTKIN across Java Island**.

The study applies **Latent Dirichlet Allocation (LDA)** combined with **bigram and trigram N-gram modeling** to map research trends from student thesis abstracts.

## 📌 Research Overview

The main objective of this research is to:

* identify the **optimal number of topics** from thesis abstracts
* map the **dominant research themes** in Mathematics undergraduate theses
* evaluate the contribution of **N-gram integration** in improving topic coherence

The best model in this study produced:

* **6 optimal topics**
* **Coherence Score: 0.6913**
* **Iteration: 1000**

The discovered themes broadly include:

1. finance and stock analysis
2. biomathematics and health
3. machine learning
4. algebra
5. time series forecasting
6. epidemic modeling

## 📂 Repository Structure

```text
├── data/                 # sample cleaned dataset or metadata
├── notebooks/            # public notebooks for visualization and topic modelling
├── figures/              # charts, pyLDAvis, topic distribution, pie/bar charts
├── results/              # coherence comparison and extracted topics
└── README.md
```

## ⚙️ Methods

The pipeline includes:

1. **Web scraping** from PTKIN repositories
2. **Text preprocessing**

   * cleaning
   * case folding
   * tokenization
   * stopword removal
   * stemming
3. **Bigram and trigram generation**
4. **Bag of Words representation**
5. **LDA topic modelling**
6. **Evaluation using coherence score**
7. **Visualization with Intertopic Distance Map**

## 📊 Main Findings

The integration of **LDA + N-gram** improved semantic consistency by preserving domain-specific compound terms such as:

* `harga_saham`
* `fungsi_kernel`
* `model_matematika`
* `value_risk`

This made the resulting topics more specific and contextually meaningful compared with unigram-based baselines.

## 🔒 Access to Full Experimental Resources

This public repository only provides the **research-ready code structure, selected notebooks, and reproducible outputs**.

The **full experimental notebooks, raw scraping pipeline, and complete preprocessing workflow** are available **for academic purposes upon request**.

Please contact:
**[anisahusna044@gmail.com](mailto:anisahusna044@gmail.com)**

Suggested request details:

* full name
* institution
* research purpose
* GitHub username or email

## 📖 Citation

If you use this repository for academic purposes, please cite the corresponding publication or thesis.

```text
Anisa Husna Nuha. Pemodelan Topik Skripsi Program Studi Matematika Menggunakan Metode Latent Dirichlet Allocation dan N-gram. 2026.
```

## 🤝 Academic Use

This repository is intended for:

* thesis references
* topic modelling experiments
* educational reproducibility
* curriculum research mapping

Please use responsibly and provide proper attribution.

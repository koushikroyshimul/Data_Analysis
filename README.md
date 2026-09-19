# Visualization of the Human vs. AI-Rewritten Bengali Text Dataset

This repository contains Python-based scripts and visualizations for exploring the **Human vs. AI-Rewritten Bengali Text Dataset**.

The visualizations provide an exploratory view of the dataset, including class distribution, source distribution, category distribution, word-count patterns, and other characteristics of Bengali human-written and AI-rewritten texts.

---

## Dataset Overview

The dataset used for visualization contains **4,008 Bengali text samples**, consisting of:

- **2,004 Human-written texts**
- **2,004 AI-Rewritten texts**
- **2,004 Human–AI text pairs**

Each human-written text is paired with its corresponding AI-rewritten version using a unique `Pair_ID`.

The dataset covers multiple Bengali content domains, including:

- Education
- Bengali Literature
- News

---

## Data Sources

The human-written texts were collected from authentic Bengali sources, including:

- **National Curriculum and Textbook Board (NCTB)** textbooks
- **Bengali literary works available through Wikisource**
- **Bengali WikiNews articles published before 2020**

The AI-rewritten texts were generated from the corresponding human-written texts using multiple large language models, including:

- ChatGPT
- Claude
- Gemini
- DeepSeek

A standardized rewriting procedure was used to generate the AI-rewritten texts while attempting to preserve the original semantic meaning and overall content.

---

## Visualizations

This repository includes Python-based exploratory data analysis and visualizations covering different characteristics of the dataset.

The visualizations include:

- Human vs. AI-Rewritten class distribution
- Category-wise distribution
- Source-wise distribution
- Word-count distribution
- Comparison of word counts between Human and AI-Rewritten texts
- Other exploratory data analysis (EDA) visualizations

These visualizations provide an overview of the dataset composition and text characteristics before applying machine learning or deep learning models.

---
## Requirements

The visualizations were created using Python and commonly used data analysis and visualization libraries.

### Python

- Python 3.x

### Required Libraries

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `openpyxl`

Install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn openpyxl

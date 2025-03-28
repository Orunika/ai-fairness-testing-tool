# 🧠 Fairness Testing Tool for AI Models

This repository contains an intelligent interactive tool for testing and mitigating unfair bias in machine learning models, developed as part of the Intelligent Software Engineering assignment at the University of Birmingham.

## 📌 Overview

The goal of this tool is to improve over the baseline **Random Search** method for fairness testing by integrating smarter, more interpretable techniques such as:

- ✅ Group fairness metrics (accuracy, selection rate, TPR, FPR)
- ✅ Intersectional fairness analysis (race + gender)
- ✅ Individual Disparate Impact (IDI) testing
- ✅ Fairness mitigation using in-processing methods (ExponentiatedGradient)

The core dataset used is the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult).

---

## 📁 Contents

- `fairness_tool.ipynb` – Google Colab notebook with all implementation steps
- `requirements.pdf` – Required Python packages
- `manual.pdf` – User instructions
- `replication.pdf` – Step-by-step replication guide

---

## 🚀 How to Run

You can run this notebook directly in Google Colab:
[Click to Open in Colab](https://colab.research.google.com/drive/1nj5d2ITG_lCqkELe10p3dJxe7j4YnzqW?usp=sharing)

Or clone the repo locally and run:
```bash
pip install -r requirements.txt

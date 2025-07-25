# 📊 TOPSIS — A Python Package for Multi-Criteria Decision Making

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.6%2B-blue)](https://www.python.org/downloads/)

> This package implements the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** algorithm — a widely used multi-criteria decision analysis method.

---

## 📌 What is TOPSIS?

**TOPSIS** is an algorithm that helps in ranking and selecting from a set of alternatives based on multiple criteria.  
It is based on the concept that the chosen alternative should have the **shortest distance from the ideal solution** and the **farthest from the negative-ideal solution**.

It is especially useful in areas like:
- Decision-making systems
- Recommendation engines
- Business and financial analysis
- Supply chain and logistics

---

## 🚀 Features

- Simple and clean API
- Accepts CSV or pandas DataFrame input
- Supports weighted and normalized decision matrices
- Command-line interface support
- Generates final rankings of alternatives
---

## 📦 Installation

Install the package directly from [PyPI](https://pypi.org):

```bash
pip install topsis-nandini==0.1.11
```

## 🛠️ Usage

```bash
# 1. Command Line Interface
Once installed, you can use `topsis` as a CLI tool:
topsis input.csv "0.3,0.5,0.2" "+,+,-" output.csv

This will:
Read data from input.csv
Apply weights 0.3,0.5,0.2
Apply impacts +,+,-
Write ranked output to output.csv


# 2. Use inside Python script
pip install topsis-nandini
!topsis input.csv "0.3,0.5,0.2" "+,+,-" output.csv
```

## Example:
<img width="1540" height="440" alt="Screenshot 2025-07-24 145432" src="https://github.com/user-attachments/assets/48ae7be7-fb09-454e-aecf-29c6dca1e999" />

## 📁 Project Structure
```bash
topsis_nandini/
│
├── topsis
│ ├── __init__.py 
│ ├── __main__.py 
│ └── topsis.py 
├── README.md 
├── LICENSE 
├── setup.py 
└── pyproject.toml 
```
## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.



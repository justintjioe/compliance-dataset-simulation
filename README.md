# Compliance Dataset Simulation

A data science project simulating a DLP (Data Loss Prevention) email compliance review workflow, built on the Enron email dataset with synthetic schema mapping and rule-based text classification.

## Project Overview

This project replicates the structure and logic of a real-world corporate email compliance review process. Outbound emails are classified as compliant or flagged for review based on sender department, recipient domain, and email content — mirroring how a compliance analyst applies judgment in a DLP tool like Microsoft Purview.

## Tech Stack

- Python, pandas, scikit-learn, NLTK
- Streamlit (dashboard)
- Jupyter Notebooks (EDA)
- Hugging Face Spaces (deployment)

## Project Structure
## Setup

```bash
git clone https://github.com/justintjioe/compliance-dataset-simulation.git
cd compliance-dataset-simulation
pip install -r requirements.txt
```

## Status

In progress
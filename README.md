# CrowdSafe Analytics

> Analyzing crowd behavior patterns to identify leading indicators of dangerous congestion in high-density event environments.

---

## Project Overview

This project presents a data analytics study of crowd density and movement patterns across large-scale public events. The objective is to identify measurable, early warning signals that precede dangerous crowd surges — enabling data-driven decision support for event safety managers.

This is not a machine learning product. It is an analytical investigation into *when*, *where*, and *why* dangerous crowd conditions develop — and what the data reveals about how they can be anticipated.

---

## Motivation

Crowd crush incidents — such as the 2021 Astroworld Festival tragedy and the 2022 Kanjuruhan Stadium disaster — share a common factor: dangerous density conditions developed gradually, with detectable patterns, before the critical moment. This project asks: **what does the data look like in the 15 minutes before a surge?**

---

## Analytical Chapters

| Chapter | Title | Focus |
|---------|-------|-------|
| 1 | Problem Definition & Data | Domain framing, dataset description, schema design |
| 2 | Exploratory Data Analysis | Density distributions, spatial patterns, temporal trends |
| 3 | Feature Engineering | Surge velocity, exit pressure ratio, spatial spread index |
| 6 | Risk Scoring & Decision Support | Composite risk model, threshold analysis, safety recommendations |
| 7 | Venue Graph Analysis | Choke point detection, evacuation route optimization |

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10 | Core analysis language |
| PostgreSQL | Structured data storage |
| Pandas / NumPy | Data manipulation |
| Plotly / Seaborn | Visualization |
| NetworkX | Venue graph analysis |
| Streamlit | Interactive dashboard |
| Jupyter Notebooks | Analysis and documentation |

---

## Repository Structure
crowdsafe-analytics/

├── data/

│   ├── raw/              # Original datasets

│   └── processed/        # Cleaned and transformed data

├── notebooks/            # Jupyter notebooks per chapter

├── src/                  # Reusable Python modules

├── dashboard/            # Streamlit application

└── reports/              # Final report and figures

---

## Status

🔄 In Progress — Phase 1: Data Design & Database Setup

---
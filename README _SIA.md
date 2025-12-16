[![Shipping files](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml)
# King County Housing Data – Exploratory Data Analysis (EDA)

## Project Overview

This project is an Exploratory Data Analysis (EDA) of the housing market in King County (Seattle/Bellevue area), USA.

**Goal:** To provide the property owner Timothy Stevens with clear, data-based insights and recommendations for selling his high-value houses.

## Key Insights (Findings)

The analysis provided the following main insights for Timothy Stevens:

*   **Seasonality:** May and June have the highest median sales prices, significantly above the yearly average.
*   **Renovation:** Renovated houses sell for a much higher median price (our analysis showed a price jump of approx. +35%).
*   **Geography:** The most expensive properties are in clear hotspots near Seattle Downtown and Bellevue zip codes.
*   **Value Drivers:** The size of the living area (`sqft_livingsquare`) and the house quality (`grade`) are the biggest reasons for a high price.

## Recommendations (Advice for Timothy)

1.  **Time the Sale:** List properties in **April and May** to get the highest price.
2.  **Renovate First:** Invest in smart renovations before selling to get the high price premium we observed.
3.  **Focus on Location in Marketing:** Use the "luxury location" angle in all marketing. The proximity to city centers makes the houses valuable.

## Setup and How to Run

### Requirements

We use `pyenv` and a specific Python version: `python==3.11.3`. All required libraries (Pandas, Seaborn, etc.) are listed in the `requirements.txt` file.

### Environment Setup (macOS & Windows)

Follow these steps to create and activate your virtual environment:

**macOS (Terminal commands):**

```bash
# Set Python version locally and create environment
pyenv local 3.11.3
python -m venv .venv

# Activate the environment and install packages
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt

### Environment Setup (WindowsOS)

Follow these steps for the Windows operating system:

For `PowerShell` CLI :

```PowerShell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt

```
### Project Files & Data Access

*   **`eda_analysis_main.ipynb`**: This is the main Jupyter Notebook containing all the analysis steps, code, plots, insights, and recommendations.
*   `Images/`: Folder that contains all saved plots for the presentation.

***Note on Data:*** The raw data files are **not** included in this repository. If the data is required to replicate the analysis, please contact the repository owner via email: [asimeoa@gmail.com](mailto:asimeoa@gmail.com).

# AI Macroeconomics and Finance Analysis of Ecuador

## Overview

This project uses Python and AI-based document analysis to analyse the International Monetary Fund's (IMF) 2026 country report on Ecuador.

### Pipeline Components

- PDF text extraction
- Token-aware chunking
- LLM-based financial summarisation
- Structured economic indicator extraction
- Retrieval-Augmented Generation (RAG) using sentence-transformers and FAISS
- LLM-as-a-Judge evaluation
- Macroeconomic and financial dashboard visualisation

## Technologies Used

- **Programming Language:** Python
- **Development Environment:** Google Colab
- **Data Processing:** Pandas
- **Visualisation:** Matplotlib
- **Semantic Search:** sentence-transformers and FAISS
- **AI Processing:** Large Language Model (LLM) API

## Data Source

**International Monetary Fund (2026).** *Ecuador: Fifth Review Under the Extended Fund Facility*. IMF Country Report No. 26/84.

The original IMF PDF is not included in this repository. The notebook uses the official IMF report as its data source.

## How to Run the Project

1. Open the `.ipynb` notebook in Google Colab.
2. Install the required Python packages using the setup cells.
3. Download the IMF report using the official source link provided in the notebook, or upload it manually if necessary.
4. Configure the required LLM API key using Google Colab Secrets.
5. Run the notebook cells in order.

**Note:** API keys and other credentials must not be included in publicly shared code.

## Project Outputs

The pipeline produces:

- Financial and macroeconomic summary
- Structured economic indicators
- RAG-based financial question answering
- Automated LLM evaluation scores
- Four-panel macroeconomic and financial dashboard

## Licence

The original code in this repository is available under the MIT License. Third-party libraries and IMF source materials remain subject to their respective licences.

## Project Structure

### 1. Folder "datos"
This folder contains the base information used for the analysis, including:
- **Extracted data:** Files with the information collected for the analysis.
- **Prompt base:** File with the prompts used as input for the analysis model.

### 2. File "Extraccion.ipynb"
This file documents the process of extracting comments using the YouTube API. It includes:
- **Selection criteria:** Details about the filters and rules applied to select relevant comments for analysis.

### 3. File "Procesamiento.ipynb"
This file describes the use of the OpenAI Batch API service to perform sentiment analysis. It includes:
- **Prompts used:** Mechanisms for structuring and sending prompts to the model.
- **Results obtained:** Process of interpreting the model's responses.

### 4. File "Analisis.ipynb"
Contains the statistical and exploratory analysis of the prompts, highlighting:
- **Principal Component Analysis (PCA):** Study of relationships between prompts.
- **Coincidence matrix:** Approximations generated based on prompt coincidences.
- **Vectorization:** Process of transforming prompts into numerical vectors.
- **Additional results:** Analysis in Wolfram to obtain results from the Pearson Chi-squared test.

---
This README provides an overview of the project's structure and methodologies used at each stage. For more details, it is recommended to explore each file in the order presented here.

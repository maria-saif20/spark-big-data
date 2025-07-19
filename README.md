# CS246 Colab 1 – Mining Massive Datasets

This repository contains solutions and experiments from **CS246: Mining Massive Datasets**, specifically the **Colab 1 assignment**. The notebook demonstrates hands-on implementations of:

- **PageRank Algorithm**
- **Jaccard Similarity**
- **Locality Sensitive Hashing (LSH)** for near-duplicate detection

---

##  Overview

This assignment focuses on analyzing a large-scale dataset of movie ratings using concepts from web search and data mining. The notebook is organized into the following sections:

### 1. PageRank Implementation
- Construct a graph of movie co-ratings.
- Apply the PageRank algorithm using power iteration.
- Analyze convergence behavior and compare results.

### 2. Jaccard Similarity
- Calculate Jaccard similarity between users’ rating sets.
- Use it to find similar users or items based on interaction history.

### 3. Locality Sensitive Hashing (LSH)
- Apply minhashing to generate signatures.
- Use LSH to efficiently detect similar users or items.
- Evaluate the accuracy and efficiency of approximate similarity search.

---

##  Files

- `Copy_of_CS246_Colab_1(Hmaria).ipynb`: Main Jupyter notebook containing code and explanations for the assignment.

---

##  Requirements

To run the notebook, you need:

- Python 3.x
- Jupyter Notebook or Google Colab
- The following Python libraries:
  - `numpy`
  - `scipy`
  - `pandas`
  - `matplotlib`

Install dependencies (if needed):

```bash
pip install numpy scipy pandas matplotlib

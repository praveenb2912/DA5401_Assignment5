# DA5401 — Assignment 5: Visualizing Data Veracity Challenges in Multi-Label Classification  

**Student Name:** Praveen  
**Roll Number:** MM22B014  
**Course Code:** DA5401  
**Assignment:** A5 — Visual Exploration of Data Quality and Label Ambiguity in Multi-Label Datasets  

---

## ▶️ How to Run

1. Open the notebook **`DA5401_assignment5_MM22B014.ipynb`** in **Google Colab** or Jupyter Notebook.  
2. Ensure that the required dataset is placed in the same working directory.  
3. Run all cells in order to reproduce the visualizations and analysis.  

---

## 📌 Summary of Work

- Conducted a **visual analysis of label consistency and quality** in a multi-label classification dataset.  
- Explored the **impact of noisy, overlapping, and ambiguous labels** on model interpretability and classifier performance.  
- Implemented **dimensionality reduction techniques** to visualize high-dimensional gene expression features:  
  - **t-SNE** for local neighborhood preservation  
  - **Isomap** for global manifold structure preservation  
- Analyzed and compared how each technique reveals different aspects of the data manifold.  
- Identified and interpreted **three major data veracity challenges**:  
  1. **Noisy / Ambiguous Labels** — samples visually misplaced in clusters of other labels.  
  2. **Outliers** — isolated points far from any major cluster, possibly due to data errors or rare cases.  
  3. **Hard-to-Learn Samples** — regions where colors mix heavily, indicating ambiguous or overlapping feature patterns.  
- Compared visualization outcomes across **multiple perplexity values** (t-SNE) and discussed their effect on structure preservation.  

---

## 🔎 Key Findings

- **Label Ambiguity:** Clear visual evidence of cross-label contamination in several regions, suggesting either labeling noise or biological overlap.  
- **Outlier Behavior:** A few samples consistently appeared distant from main manifolds across all visualizations, indicating possible measurement or preprocessing artifacts.  
- **Hard-to-Learn Regions:** Central mixed-color areas in t-SNE plots revealed inherently confusing samples for classifiers.  
- **Isomap vs t-SNE:**  
  - **Isomap** preserved the **global manifold geometry**, revealing meaningful inter-cluster relationships.  
  - **t-SNE** emphasized **local clusters**, helping detect subtle sub-group patterns but at the cost of global continuity.  



---

# 07 — Clustering

two versions:
- `clustering-full.tex` — the complete lecture, e.g. `clustering-full.pdf`
- `clustering-short.tex` — a condensed intro version, e.g. `clustering-short.pdf`

## What this chapter covers

The unsupervised-learning chapter: finding structure in data that has no
labels at all.

- Supervised vs unsupervised learning, revisited from chapter 02
- What clustering is: grouping similar points with no predefined categories
- **K-Means**: the core algorithm — initializing centers, assigning points,
  updating centers, iterating to convergence
- The **elbow method** for choosing K (the number of clusters)
- **Hierarchical clustering**: building a dendrogram bottom-up, with no need
  to choose K in advance
- **DBSCAN**: density-based clustering that finds arbitrary shapes and
  automatically flags noise/outliers
- Comparing the three algorithms: speed, shape assumptions, need for K
- Evaluating clustering without labels: the **Silhouette Score**
- Why normalization matters even more here than in supervised learning
- A complete workflow template and two practice exercises (customer
  segmentation, and comparing algorithms on `make_moons`)

The `-short` version is a good standalone session if you only have time to
cover K-Means and the elbow method.

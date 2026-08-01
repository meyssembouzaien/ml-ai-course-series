# AS-CFL — Article Review (Data Mining and Machine Learning)

Review and critical analysis of:

> G. Yi, Z. Wu, X. Zhang, X. Li, **"Clustered Federated Learning with Adaptive Similarity for Non-IID Data,"** *Electronics*, 14(22), 4454, 2025.

Prepared by **Meyssem Bouzaien** — Data Mining & Machine Learning course, supervised by Prof. Ben Othman Leila.

## Contents

| File | Description |
|---|---|
| `fr/rapport_AS-CFL_fr.pdf` | Original report (French) |
| `fr/presentation_AS-CFL_fr.pdf` | Original slide deck, 25 slides (French) |
| `en/report_AS-CFL_en.pdf` | English translation of the report |
| `en/presentation_AS-CFL_en.pdf` | English translation of the slide deck (25 slides) |


## Summary

The report and slides examine **AS-CFL** (Adaptive Similarity Clustered Federated Learning), which tackles non-IID data in federated learning through:
1. Dynamic clustering with no predefined number of clusters (via the dispersion/separation ratio $G_k$)
2. A positive incentive mechanism that only admits a client into a cluster if it improves accuracy on a proxy validation set
3. Low-rank approximation of the similarity matrix, cutting server-side complexity from $O(S^2d)$ to $O(Srd)$
4. Differentially private aggregation ($\epsilon=1.0,\ \delta=10^{-5}$)

On MNIST/EMNIST, AS-CFL reaches 90% accuracy in 20% fewer communication rounds than CFL, and degrades more gracefully than FedAvg/IFCA/CFL as heterogeneity increases. The report and slides also include a critical discussion of the paper's limitations (dataset simplicity, empirical thresholds, no formal convergence proof) and directions for future work.

## Reference

Yi, G.; Wu, Z.; Zhang, X.; Li, X. Clustered Federated Learning with Adaptive Similarity for Non-IID Data. *Electronics* **2025**, *14*, 4454.

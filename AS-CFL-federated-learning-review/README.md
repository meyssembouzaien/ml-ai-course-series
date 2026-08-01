# AS-CFL Article Review (Data Mining and Machine Learning)

This project reviews and critically analyzes this paper:

> G. Yi, Z. Wu, X. Zhang, X. Li, "Clustered Federated Learning with Adaptive Similarity for Non-IID Data," Electronics, 14(22), 4454, 2025.

Prepared by Meyssem Bouzaien. Data Mining and Machine Learning course, supervised by Prof. Ben Othman Leila.

## Contents

| File | Description |
|---|---|
| `fr/rapport_AS-CFL_fr.pdf` | Original report, written in French |
| `fr/presentation_AS-CFL_fr.pdf` | Original slide deck, 25 slides, in French |
| `en/report_AS-CFL_en.pdf` | English translation of the report |
| `en/presentation_AS-CFL_en.pdf` | English translation of the slide deck, 25 slides |

## What is AS-CFL

Federated learning lets many devices train one model together without sharing their raw data. A common problem is that each device has different data. This is called non-IID data. It slows down training and hurts accuracy.

AS-CFL is a method that groups similar devices into clusters. Each cluster trains its own model. This works better than training one single model for everyone.

AS-CFL has four main ideas:

1. It builds clusters on its own. It does not need a fixed number of clusters ahead of time. It uses a score called $G_k$ to decide when to split or merge a cluster.
2. It only lets a device join a cluster if that device actually improves the cluster's accuracy. This keeps clusters clean and useful.
3. It uses a math shortcut called low rank approximation. This makes the similarity calculation much faster, so it can work with many devices.
4. It adds random noise to protect privacy. This is called differential privacy.

## Main results

The tests use two datasets: MNIST and EMNIST.

AS-CFL reaches 90 percent accuracy using 20 percent fewer communication rounds than the CFL method. It also stays more accurate than FedAvg, IFCA, and CFL when the data across devices becomes very different from each other.

The report and slides also point out the paper's weak points. For example, the tests only use simple datasets, some thresholds are chosen by trial and error, and there is no formal proof that the method always converges. The report ends with ideas for future work.

## Reference

Yi, G.; Wu, Z.; Zhang, X.; Li, X. Clustered Federated Learning with Adaptive Similarity for Non-IID Data. Electronics 2025, 14, 4454.

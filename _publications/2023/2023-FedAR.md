---
title:          "Federated adaptive reweighting for medical image classification"
date:           2023-12-1 00:01:00 +0800
selected:       true
pub:            "Pattern Recognition (PR)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"

abstract: >-
 Medical data sharing across institutes is crucial to large-scale multi-center studies and the development of real-world AI applications but suffers from serious privacy issues. A promising solution to address this challenge is federated learning, which typically aggregates a global model from heterogeneous data spread across numerous clients without exchanging data. However, the traditional federated learning algorithm (i.e., FedAvg) merely aggregates the locally distributed models according to the amount of data on each client and lacks the consideration of data heterogeneity. In this paper, we propose a novel Federated Adaptive Reweighting (FedAR) algorithm for medical image classification. FedAR employs a flexible re-weighting scheme that can balance adaptively the contributions of the amount of data and the performance of the local model on each client to the weight of that client. Specifically, we allow the amount of local data to contribute more to the weight of each client in the early training stage and let the performance of the local model play a more important role in the late stage. We have evaluated the proposed FedAR algorithm against the locally trained model, globally trained baseline, and two existing federated learning algorithms on the ISIC2018 dataset and Chest X-ray14 dataset under the settings with a variable number of clients. Our results suggest that FedAR is an effective federated learning algorithm that substantially outperforms existing federated learning approaches.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Yu Feng*
  - Benteng Ma*
  - Geng Chen
  - Changyang Li
  - Yong Xia
links:
  Paper: https://www.sciencedirect.com/science/article/abs/pii/S0031320323005782
---

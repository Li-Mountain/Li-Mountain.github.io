---
title: "Byzantine-Robust Federated Learning for Unreliable Environments by Random-Matching Verification and Credibility Table"
collection: publications
category: conferences
permalink: /publication/2025-09-04-random-matching-byzantine-fl
excerpt: 'BRFLUE: a Byzantine-robust federated learning framework combining anonymous random-matching verification among clients with credibility-table-based global aggregation.'
date: 2025-09-04
venue: 'International Conference on Security and Privacy in Communication Networks (SecureComm)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-94445-1_1'
citation: 'Y. Li, X. Li, H. Wan, and C. Wang, &quot;Byzantine-Robust Federated Learning for Unreliable Environments by Random-Matching Verification and Credibility Table,&quot; in <i>Security and Privacy in Communication Networks (SecureComm 2024)</i>, LNICST, Springer, 2025, pp. 3–13. doi: 10.1007/978-3-031-94445-1_1.'
---
Federated learning (FL) is a technique that establishes a global model based on distributed data across multiple clients, while preserving data privacy. However, the frequent client-server communication in FL provides an opportunity for Byzantine clients, who can tamper with or falsify model parameters. Consequently, the presence of Byzantine clients impacts the convergence of the global model. To address this issue, we propose a framework that maintains Byzantine-robustness for FL in unreliable environments (BRFLUE). Specifically, BRFLUE consists of two components: a random-matching verification module and a credibility-table-based aggregation module. The former randomly matches clients and allows them to verify each other's behavior anonymously. The latter updates clients' credibility after receiving the client verification results and aggregates the global model based on the credibility table. The combination of these two modules can effectively identify possible Byzantine clients and reduce their adverse impact on the global model. Through implementations in different scenarios with classical datasets, we demonstrate the effectiveness of the proposed BRFLUE.

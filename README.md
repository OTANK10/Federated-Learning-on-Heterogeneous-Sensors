# Federated-Learning-on-Heterogeneous-Sensors


* Research Overview

This study examines how data heterogeneity and adversarial attacks impact federated learning (FL) systems, addressing two fundamental challenges that limit global model convergence and generalization capabilities. Through systematic evaluation across five benchmark datasets, we reveal critical trade-offs between robustness, efficiency, and model performance.

* Key Contributions

Systematic Heterogeneity Analysis: Dirichlet alpha partitioning (0.1-10.0) across 5 datasets  
Adversarial Robustness Study: Full-knowledge trim attacks targeting 40% of clients  
Comprehensive Evaluation: 100-client federated environment with CNN models  
Trade-off Analysis: Homogeneity vs. heterogeneity impact on attack resilience  
Practical Insights: Guidelines for robust FL system design  

* Datasets Evaluated

![image](https://github.com/user-attachments/assets/9596fdac-866c-4d4d-90de-e2bc3a96b6d1)  


* Attack Specification

Attack Type: Full-knowledge trim attack  
Target Clients: 40% of total clients (randomly selected)  
Data Manipulation: 60% of targeted client data  
Attack Strategy: Class elimination during training  

* Key Insights

✅ Homogeneity Benefits: Higher accuracy, faster convergence, better communication efficiency  
⚠️ Homogeneity Risks: Overfitting, reduced generalization, vulnerability to specific attacks  
✅ Heterogeneity Benefits: Better generalization, model diversity, robustness to some attacks  
⚠️ Heterogeneity Costs: Slower convergence, higher communication overhead, attack vulnerability  

* Evaluation Metrics

Global Model Accuracy: Aggregated performance across all clients  
Convergence Rate: Accuracy improvement over epochs  
Attack Impact: Performance degradation under adversarial conditions  
Communication Efficiency: Rounds needed for convergence  

* Academic Impact

Research Contributions  

Novel Attack-Heterogeneity Analysis: First systematic study of interaction effects  
Comprehensive Dataset Coverage: Five diverse datasets spanning complexity levels  
Practical Design Guidelines: Evidence-based recommendations for FL systems  
Trade-off Quantification: Measurable impacts of design choices  

Industry Relevance  

IoT Sensor Networks: Heterogeneous device capabilities and data distributions  
Healthcare Systems: Privacy-preserving collaborative learning with diverse institutions  
Smart Cities: Distributed sensing with varying data quality and availability  
Autonomous Systems: Collaborative learning across diverse environments  

* Related Publications

Key References  

McMahan et al. (2017) - FederatedAveraging foundation  
Kumar et al. (2024) - Adversarial attack survey in FL  
Darzi et al. (2024) - Medical imaging FL vulnerabilities  
Queyrut et al. (2023) - TEE-based FL defense mechanisms  

Dataset Papers  

MNIST: LeCun et al. (1998)  
CIFAR-100: Krizhevsky (2009)  
SVHN: Netzer et al. (2011)  
FashionMNIST: Xiao et al. (2017)  

For questions about the research methodology, experimental setup, or potential collaborations, please contact the authors.

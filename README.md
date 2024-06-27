# REU-AI-Cybersecurity-SM
REU Project Overleaf link: https://www.overleaf.com/project/6661f42fac3b60ef6a4f1b45

PPT: [https://docs.google.com/presentation/d/1z5sr9k3j24NHAuz8u-bZl0Wzn8QQzbkR56Wk5UkNN7Y/edit#slide=id.p](https://mailmissouri-my.sharepoint.com/:p:/r/personal/tasn78_umsystem_edu/Documents/REU-IDS-QNN-Selam-Tom%20-%20Copy.pptx?d=w429a22e021794fa399e8c1938b34d3fe&csf=1&web=1&e=BwwOWt)

GAT reproduced implementation: https://github.com/smitike/pytorch-GAT/tree/main 

Literature Review doc: https://docs.google.com/document/d/144FEUBrRvgYVvr7Msp3vgGPa3wk0qb8HoKravFoO0Us/edit

###IoT

GAT Base Model Testing - https://youtu.be/QnovHpuHaXU

# Main Purpose
Develop algorithms that utilize the temporal and spatial relationships captured by the GNN to trace the origin of an attack within the network graph. Question: Can dynamic GNNs accurately trace back and identify the source of cybersecurity attacks within a network?

# Expected Outcomes
Accurate Source Tracing: tracing the origin of attacks, preventing the spread, and predicting the impact of the spread on the whole network.
# Approach
Attack Source Identification
 Approach: Utilize the temporal and spatial dependencies captured by the dynamic GNN to trace back the source of an attack.
 Techniques: Graph traversal algorithms, backtracking methods in the GNN framework.

# Quantum Integration
How QNNs Help: QNNs can improve the traceability of attack sources by analyzing the temporal and spatial relationships in network data more effectively. Quantum algorithms can analyze these relationships in a highly parallel manner, leading to faster and more accurate identification of attack sources. Example Approach: Developing quantum-enhanced graph traversal algorithms that leverage the principles of quantum entanglement to trace the origin of attacks​ (SpringerLink)​.

# GitHub codes
https://github.com/gordicaleksa/pytorch-GAT/blob/main/The%20Annotated%20GAT%20(Cora).ipynb: GAT implementation

https://github.com/VainF/Torch-Pruning: works with different neural network architectures, including GNNs. Could easily adapt to our needs without requiring architecture-specific modifications. Structural pruning is useful for real-time requirements.
Integration: Check how well the pruning technique can be integrated with your existing GNN model for source tracing. The integration should not disrupt your model's primary function.

# Datasets
Preprocessed: https://research.unsw.edu.au/projects/toniot-datasets and https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15/data (includes attacks)

https://www.kaggle.com/datasets/vigneshvenkateswaran/bot-iot/data (includes attacks)

https://rpaudel42.github.io/pages/dataset.html

https://www.kaggle.com/datasets/agungpambudi/network-malware-detection-connection-analysis/data (malware capture dataset, includes duration of the connection)

https://www.stratosphereips.org/datasets-malware (Multi-Modality): 

Weblogs (Device Behavior Logs): Captured HTTP requests and responses, including timestamps, ports, response codes, sizes, IP addresses, content types, referers, and user agents.

Netflows (Network Traffic): Captured network flows including detailed connection records with labels indicating the type of traffic (e.g., SPAM, TCP-Attempt, UDP, DNS).
Labels are added to netflow records for identifying malicious activity.


# Literature Review
chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://arxiv.org/pdf/2104.03654: approach to anti-spoofing using GATs. deep residual network (ResNet-18) architecture [32] which is used to extract high-level representation and then the GAT framework. Finally, we discuss the application of temporal and spectral attention. The architecture is illustrated in Figure

https://www.sciencedirect.com/science/article/abs/pii/S156625352200104X MST-GAT: A multimodal spatial–temporal graph attention network for time series anomaly detection.


# Other options:

Enhanced Vulnerability Detection: A model that flags vulnerable devices in real time. (GCN)
Comprehensive Impact Assessment: A framework to measure attack impact on network performance. (TGN)
Improved Attack Detection and Prediction: A robust system for identifying and predicting attacks.
Effective Protection and Recovery: Strategies to isolate compromised nodes and ensure rapid recovery.



https://ieeexplore.ieee.org/document/10136827

https://arxiv.org/pdf/2309.01829 (Tom) - Mitigating overfitting in QCNN

Datasets:
https://paperswithcode.com/dataset/sorel-20m - SOREL-20M is a large-scale dataset consisting of nearly 20 million files with pre-extracted features and metadata

Portable executable:
https://www.kaggle.com/datasets/joebeachcapital/windows-malwares/data

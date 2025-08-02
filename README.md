# GPSN---DFN
Deploy GPSN - DFN: "Detecting Fake News Based on Graph Propagation Structure and Sequential Network"
# Overview
Combine user profiles/preferences, news propagation context, and sequential chain of time-based interactions to detect fake news. User features are encoded as nodes in a news propagation graph and sequential chain. Then, use GNN layers (GCN, GAT, GraphSage, GTN) to process the news propagation graph and Transformer/LSTM to process the sequential information layer . These vectors are aggregated and trained to create a fake news detector.

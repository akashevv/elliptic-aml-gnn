# elliptic-aml-gnn

Code for the article "Graph-Based Methods for Detecting Suspicious Activities in Financial Networks"
(B. Akashev, Y. Kanapiya, O. Baitakov).

Illicit transaction detection on the Elliptic Bitcoin dataset: Random Forest, MLP, GCN, GAT.

- Notebook: `elliptic_experiments.ipynb` (run top to bottom in Google Colab, GPU: T4)
- Data: Elliptic Data Set (CC BY-NC-ND 4.0), downloaded automatically via
  `torch_geometric.datasets.EllipticBitcoinDataset`; the data are not stored in this repository
- Models: RF-local, RF-graph, MLP, GCN, GAT; random seeds 17, 29, 43
- Hardware: Intel Xeon @ 2.00 GHz, 13.6 GB RAM, NVIDIA Tesla T4
- Software versions: see `requirements.txt`
- Runtime: about 20 minutes for the full notebook
- Licence: MIT

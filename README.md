Federated-learning

Federated Learning is a machine learning approach that enables model training across decentralized edge devices (such as mobile phones, IoT devices) or local servers while keeping the data localized. 
In traditional machine learning, data is typically collected and sent to a central server for model training. However, this raises concerns about data privacy and security.

This in an implementation of FedNCF along with FedAvg where the weight updates are transferred locally. A networking layer can be added to perform weight updates over the network and averaged at the server. 

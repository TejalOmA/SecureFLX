# Privacy-Preserving Federated Learning with Homomorphic Encryption 🔒🤖

This project combines **Federated Learning (FL)** and **Homomorphic Encryption (HE)** to create a secure, decentralized machine learning framework. It enables collaborative training on distributed data without compromising privacy, using technologies like **Flower**, **TenSEAL**, and **PyTorch**. The **CIFAR-10 dataset** is utilized to simulate real-world non-IID scenarios, addressing challenges in sectors like healthcare and finance.

---

## 🚀 Features
- **Federated Learning**: Decentralized model training with privacy-preserving updates.
- **Homomorphic Encryption**: Secure computations on encrypted data using CKKS.
- **Custom Aggregation**: Enhanced privacy and accuracy for non-IID data distributions.
- **Modular Implementation**: Separate training and evaluation functions for streamlined operations.

---

## 🛠️ Technologies and Libraries
- **Flower (flwr)**: Federated learning framework for client-server communication.
- **TenSEAL**: CKKS-based homomorphic encryption library for encrypted computations.
- **PyTorch**: Deep learning library for model definition and training.
- **Matplotlib/Seaborn**: Visualization tools for performance analysis.

---

## 📊 Results
# Federated Learning Performance:
- Improved privacy with encrypted client-server communication.
- Custom aggregation optimized for non-IID data distributions.
# Evaluation Metrics:
- High accuracy in both IID and non-IID setups.
- Zero data leakage through end-to-end encryption.


## 🧑‍💻 Usage
# Prerequisites
Python 3.8+

1. Clone the repository:

   ```bash
   git clone https://github.com/TejalOmA/SecureFLX.git
   cd SecureFLX
   ```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start Jupyter Notebook:

Type
```bash
jupyter notebook
```
in command prompt. 
Open the notebook (secureflx.ipynb) in your browser and run the cells.

2. Run on Google Colab


# Workflow
1. Each client loads a local partition of CIFAR-10 data.
2. Clients train models locally, encrypt updates, and send them to the server.
3. The server aggregates encrypted updates and refines the global model.
4. Results are visualized and stored in the results/ folder.

---

## 🛡️ Future Work

-**Bootstrapping Techniques**: Maintain ciphertext integrity in longer training sequences.
-**Gradient Compression**: Optimize communication overhead.
-**Quantum Encryption**: Explore quantum-resistant algorithms for future-proofing.

---

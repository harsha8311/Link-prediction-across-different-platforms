# 🔗 Cross-Domain Link Prediction using Heterogeneous GNNs

A graph-based machine learning system that predicts potential connections between **Twitter users** and **GitHub repositories**, such as whether a user is likely to **star** a repository. Built using **Heterogeneous Graph Neural Networks (GNNs)**, the project showcases the potential of **cross-platform recommendation systems** through intelligent graph modeling and link prediction.

---

## 🚀 Features

- 🌐 **Cross-Platform Modeling**: Combines data from **Twitter** and **GitHub** to create a unified graph structure.
- 🧩 **Heterogeneous Graph**: Represents multiple types of nodes (users, repositories, hashtags, tweets) and edges (stars, posts, tags, follows).
- 🧠 **Graph Neural Networks**: Utilizes **Heterogeneous GNN models** like **HAN (Heterogeneous Attention Network)** and **HGT (Heterogeneous Graph Transformer)**.
- 🔗 **Link Prediction**: Predicts whether a **Twitter user** will interact with (e.g., star) a **GitHub repository**.
- 📊 **Real-World Application**: Demonstrates a novel use case for **cross-domain recommendation systems** in social-coding platforms.

---

## 🛠️ Tech Stack

| Component        | Technology / Library            |
|------------------|----------------------------------|
| Graph Modeling   | PyTorch Geometric, DGL           |
| GNN Models       | HAN, HGT                         |
| Data Processing  | Python, Pandas, NetworkX         |
| ML Framework     | PyTorch                          |
| Visualization    | Matplotlib, seaborn              |

---

## 🧪 How It Works

1. **Data Collection**: 
   - Twitter data: User interactions, tweets, hashtags.
   - GitHub data: Repositories, stars, contributors.

2. **Graph Construction**:
   - Nodes: Twitter users, tweets, hashtags, GitHub repos.
   - Edges: Tweet-posts, hashtags-used, repo-starred, user-follows.

3. **Model Training**:
   - Train heterogeneous GNN (e.g., HAN or HGT) to learn representations.
   - Perform **link prediction** between user and repo nodes.

4. **Evaluation**:
   - Evaluate model performance using metrics like AUC, F1-score, Precision/Recall.

---

## 📦 Installation & Setup

```bash
git clone https://github.com/your-username/cross-domain-link-prediction.git
cd cross-domain-link-prediction
pip install -r requirements.txt
python train.py
# Link-prediction-across-platforms

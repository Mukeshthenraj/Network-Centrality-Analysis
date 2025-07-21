
# 🧠 Network Centrality Analysis with NetworkX

This project explores various centrality measures and algorithms on **real-world graph datasets** using the Python library `NetworkX`. It is divided into two parts:

---

## 📁 Dataset Structure

```
📦 Network-Centrality-Analysis/
├── data/
│   ├── friendships.gml            # Undirected graph of university friendships
│   ├── blogs.gml                  # Directed graph of political blog links
├── network_centrality_assignment.py  # Full code answering Q1–Q9
├── README.md
```

---

## 📌 Project Overview

### 🔹 **Part 1: University Friendships Network (`friendships.gml`)**
- Undirected graph where:
  - Nodes = individuals
  - Edges = friendship links
- Tasks:
  1. Compute **degree**, **closeness**, and **betweenness** centralities
  2. Choose the best person to send a 1-hop voucher
  3. Optimize for fastest full-network spread
  4. Identify critical **bridge node** a competitor might remove

### 🔹 **Part 2: Political Blogs Network (`blogs.gml`)**
- Directed graph where:
  - Nodes = blogs
  - Edges = hyperlinks between blogs
- Tasks:
  5. Apply **PageRank** to find influence of `realclearpolitics.com`
  6. Get top 5 blogs by PageRank
  7. Compute **HITS algorithm** (hub & authority scores) for `realclearpolitics.com`
  8. List top 5 **hub** blogs
  9. List top 5 **authority** blogs

---

## 🧮 Techniques Used
- `NetworkX` Graph Algorithms:
  - `degree_centrality()`
  - `closeness_centrality()`
  - `betweenness_centrality()`
  - `pagerank()`
  - `hits()`

---

## ▶️ How to Run

Install NetworkX if needed:

```bash
pip install networkx
```

Run the code in `network_centrality_assignment.py` using Jupyter Notebook or any Python environment.

---

## 💡 Learning Outcomes

- Understand and interpret centrality metrics in graphs
- Apply PageRank and HITS to real data
- Choose optimal nodes for influence and disruption
- Practice working with `.gml` graph datasets

---

## 🧑‍💻 Author
**Mukesh Thenraj**  
Master's in Automation & Safety  
University of Duisburg-Essen

---

## 📜 License
This project is licensed under the MIT License.

# 🚚 Smart Logistics Network Using Dijkstra's Algorithm and Huffman Coding

A Smart Logistics Network modeled as a **Weighted Undirected Graph** to optimize delivery operations between multiple distribution centers.

This project demonstrates the practical application of:

- Dijkstra's Algorithm
- Huffman Coding
- Graph Theory
- Greedy Algorithms
- Priority Queue (Min-Heap)
- Adjacency List & Matrix Representation

The system contains 8 distribution centers and 17 transportation routes with even-weighted delivery costs.

---

## 📄 Project Report

<div align="center">

### 📘 Detailed Project Documentation

<a href="./Smart_Logistics_Network_Using_Dijkstra_Algorithm_and_Huffman_Coding.pdf">
    <img src="https://img.shields.io/badge/📄-View%20Full%20Report-red?style=for-the-badge">
</a>

</div>

---

## 🎯 Project Objectives

- Find the minimum-cost delivery route using Dijkstra's Algorithm
- Generate a message from shortest-path distances
- Compress the generated message using Huffman Coding
- Verify lossless decoding
- Analyze algorithm correctness and efficiency

---

## 🏢 Distribution Centers

| Node | Distribution Center |
|--------|---------------------|
| A | Source Distribution Center |
| B | Distribution Center B |
| C | Distribution Center C |
| D | Distribution Center D |
| E | Distribution Center E |
| F | Distribution Center F |
| G | Distribution Center G |
| H | Destination Distribution Center |

---

## 🔗 Graph Information

| Property | Value |
|-----------|---------|
| Graph Type | Weighted Undirected Graph |
| Nodes | 8 |
| Edges | 17 |
| Edge Weights | Even Numbers |

---

## 🧠 Algorithms Implemented

### 1️⃣ Dijkstra's Algorithm

Computes the shortest delivery path from source node A to destination node H.

**Time Complexity**

```text
O((V + E) log V)
```

### Shortest Distance Results

| Node | Distance from A |
|---------|----------------|
| A | 0 |
| B | 4 |
| C | 2 |
| D | 4 |
| E | 8 |
| F | 8 |
| G | 8 |
| H | 14 |

### Optimal Delivery Paths

```text
A → C → D → G → H
Cost = 14
```

```text
A → C → D → H
Cost = 14
```

```text
A → H
Cost = 14
```

---

### 2️⃣ Message Generation

Shortest-path distances are converted into ASCII characters.

Generated Message:

```text
DBDHHHN
```

---

### 3️⃣ Huffman Coding

Compresses the generated message using optimal prefix-free encoding.

#### Huffman Codes

| Character | Code |
|------------|--------|
| H | 0 |
| D | 11 |
| B | 100 |
| N | 101 |

#### Encoded Bit Stream

```text
1110011000101
```

---

## 📊 Compression Results

| Metric | Value |
|----------|---------|
| Original Message | DBDHHHN |
| Original Size | 56 bits |
| Compressed Size | 13 bits |
| Bits Saved | 43 bits |
| Space Reduction | 76.8% |

---

## ✅ Verification

### Decoding Result

```text
Original Message : DBDHHHN
Decoded Message  : DBDHHHN
```

✔ Perfect Match

✔ Lossless Compression Verified

✔ End-to-End Validation Passed

---

## 📂 Repository Structure

```text
smart-logistics-network/
│
├── README.md
├── Smart_Logistics_Network_Using_Dijkstra_Algorithm_and_Huffman_Coding.pdf
├── graph-diagram.png
├── shortest-path-diagram.png
├── huffman-tree.png
└── source-code/
```

---

## 🚀 Key Features

- Weighted Undirected Graph Modeling
- Shortest Path Computation
- Min-Priority Queue Implementation
- Huffman Compression
- Message Encoding & Decoding
- Algorithm Validation
- Complexity Analysis
- Real-World Logistics Optimization

---

## ⚙️ Technologies & Concepts

- Algorithms
- Data Structures
- Graph Theory
- Dijkstra Algorithm
- Huffman Coding
- Greedy Algorithms
- Priority Queue
- Min Heap
- Adjacency List
- Adjacency Matrix
- Complexity Analysis

---

## 📈 Complexity Analysis

| Algorithm | Time Complexity | Space Complexity |
|------------|----------------|------------------|
| Dijkstra's Algorithm | O((V+E) log V) | O(V) |
| Huffman Encoding | O(n log n) | O(n) |
| Huffman Decoding | O(n) | O(n) |

---

## 🎓 Learning Outcomes

This project demonstrates how shortest-path algorithms and lossless data compression techniques can be integrated to solve real-world logistics optimization problems efficiently. The system combines graph traversal, greedy algorithms, and information theory to create a complete end-to-end solution.

---

## 👨‍💻 Author

**Ifty Anwar**

Computer Science & Engineering Student  
Web Developer | Problem Solver | Technology Enthusiast

---

## 📜 License

This project is created for academic and educational purposes.

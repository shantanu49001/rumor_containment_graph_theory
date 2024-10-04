# 🌐 Rumor Containment in Peer-to-Peer Message Sharing Online Social Networks

## 📋 Overview
This project explores the dynamics of rumor propagation and containment in online social networks using models like the **Independent Cascade (IC)** and **Linear Threshold (LT)**. It focuses on understanding how influence (both positive and negative) spreads across peer-to-peer networks and how effective containment strategies can be applied.

## 🚀 Key Features
- **Social Network Representation**: Individuals are represented as nodes, and their connections/interactions are edges between the nodes.
- **Influence Propagation**: Information (truthful or rumor) spreads through the network, affecting the nodes.
- **Containment Models**:
  - **Independent Cascade (IC) Model**: Each node influences its neighbors independently based on a probability threshold.
  - **Linear Threshold (LT) Model**: Nodes adopt the information based on cumulative influence from neighbors.
- **📊 Comparison of Broadcast and Peer-to-Peer Models**: Evaluates the differences between centralized (broadcast) and decentralized (peer-to-peer) information propagation.

---

## 📑 Table of Contents
1. [Introduction](#introduction)
2. [Models](#models)
   - [Independent Cascade (IC) Model](#independent-cascade-ic-model)
   - [Linear Threshold (LT) Model](#linear-threshold-lt-model)
3. [Extension to Peer-to-Peer Models](#extension-to-peer-to-peer-models)
4. [How to Run the Project](#how-to-run-the-project)
5. [Dependencies](#dependencies)
6. [References](#references)
7. [Author](#author)
8. [License](#license)

---

## 🧑‍💻 Introduction
This project investigates the control of rumors in **peer-to-peer message-sharing networks**. The effectiveness of rumor containment depends on factors like **seed node selection** and **influence thresholds**, which determine how information is spread, adopted, or dismissed in the network.

---

## 📉 Models

### Independent Cascade (IC) Model
In the **IC Model**, each node influences its neighbors based on a probability threshold. If the probability condition is met, the neighboring node adopts the information, whether it is accurate or a rumor.

**Figure 1**: Independent Cascade Model Visualization  
![IC Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/IC.png)

### Linear Threshold (LT) Model
In the **LT Model**, nodes are influenced by the combined strength of their neighbors' edge weights. A node adopts the information when the sum of the incoming edge weights exceeds its threshold.

**Figure 2**: Linear Threshold Model Visualization  
![LT Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/LT.png)

---

## 🔄 Extension to Peer-to-Peer Models
In this project, we extend the investigation to **peer-to-peer (P2P) models** by analyzing the shift from centralized (broadcast) to decentralized (P2P) rumor propagation. Various network topologies were simulated to understand the influence dynamics.

**Algorithm Flow Diagram**  
![Algorithm Flow](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/algo.png)

**Simulation 1**  
![Simulation 1](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/sim1.png)

**Simulation 2**  
![Simulation 2](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/sim2.png)

**Simulation 3**  
![Simulation 3](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/sim3.png)

---

## 💻 How to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/rumor-containment.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd rumor-containment
    ```

3. **Compile the LaTeX Presentation**:
    If you want to generate the presentation, run:
    ```bash
    pdflatex presentation.tex
    ```

4. **Run Simulations**:
    Depending on the simulation scripts provided, use either Python or MATLAB to run the simulations. Ensure the correct libraries are installed.

---

## 📦 Dependencies

- **LaTeX** (Beamer for presentation slides)
- **Python** or **MATLAB** for running simulation models
- **Graph Visualization Libraries** (Optional for generating network graphs)

---

## 📚 References

- **Independent Cascade and Linear Threshold Models**: [Deep dive into these models](https://link_to_reference_paper).
- **Peer-to-Peer Communication Models**: [Read more on decentralized propagation](https://link_to_reference_paper).

---

## 👨‍💻 Author

**Shantanu Tiwari**  
Indian Institute of Information Technology, Guwahati (IIIT-G)

Feel free to contribute to this project or reach out if you have any questions!

---

## 📄 License

This project is licensed under the [CC BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

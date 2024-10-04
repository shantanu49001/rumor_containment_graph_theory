# Rumor Containment in Peer-to-Peer Message Sharing Online Social Networks

## Overview
This project explores the dynamics of rumor propagation and containment in online social networks, using models like the Independent Cascade (IC) and Linear Threshold (LT). It focuses on understanding how influence (both positive and negative) spreads across a peer-to-peer network and how effective containment strategies can be applied.

## Key Features
- **Social Network Representation**: Nodes represent individuals, and edges represent connections or interactions between them.
- **Influence Propagation**: Both correct information and misinformation (rumors) can spread through the network.
- **Containment Models**:
  - **Independent Cascade (IC) Model**: Each node independently influences its neighbors based on a probability threshold.
  - **Linear Threshold (LT) Model**: Nodes are influenced based on edge weights and cumulative thresholds.
- **Comparison of Broadcast and Peer-to-Peer Models**: Evaluates the differences between centralized and decentralized information propagation.

## Table of Contents
1. [Introduction](#introduction)
2. [Models](#models)
   - [Independent Cascade (IC) Model](#independent-cascade-ic-model)
   - [Linear Threshold (LT) Model](#linear-threshold-lt-model)
3. [Extension to Peer-to-Peer Models](#extension-to-peer-to-peer-models)

## Introduction
This project investigates how rumors can be controlled in peer-to-peer message-sharing networks. Key parameters include seed selection and influence thresholds, which impact how information is adopted or dismissed by individuals in the network.

## Models

### Independent Cascade (IC) Model
In the IC model, each node (person) influences its neighbors with a random probability that, if exceeded, causes the neighbor to adopt the information (either true or false).

![IC Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/IC.png)

### Linear Threshold (LT) Model
In the LT model, nodes are influenced based on cumulative edge weights from their neighbors. If the sum of the incoming weights exceeds a node's threshold, the node adopts the information.

![LT Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/LT.png)

## Extension to Peer-to-Peer Models
We extend the research by analyzing the shift from a centralized broadcast model to a decentralized peer-to-peer model. This is done by simulating rumor spread in various network topologies.
![LT Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/algo.png)
![LT Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/sim1.png)
![LT Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/sim2.png)
![LT Model](https://github.com/shantanu49001/rumor_containment_graph_theory/blob/main/sim3.png)

## How to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/rumor-containment.git
    ```
2. Navigate to the project folder:
    ```bash
    cd rumor-containment
    ```
3. Compile the LaTeX presentation (if required):
    ```bash
    pdflatex presentation.tex
    ```
4. Run the simulations using the provided scripts.

## Dependencies
- LaTeX (Beamer for the presentation)
- Python or MATLAB for simulations (depending on the scripts)
- Graph visualization libraries (optional for generating network graphs)

## References
- **Broadcast Rule vs Peer-to-Peer Models**: [Explore the broadcast rule in more detail](link_to_reference_paper).
  
## Author
**Shantanu Tiwari**  
Indian Institute of Information Technology, Guwahati (IIIT-G)

Feel free to contribute or reach out if you have any questions.

## License
This project is licensed under the [CC BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

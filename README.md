# Redundancy-Aware-Closed-High-Utility-Sequential-Pattern-Mining

## Introduction

**CloHusp** is an advanced algorithm designed for mining *Closed High Utility Sequence Patterns (CHUSPs)* from large datasets. By leveraging efficient pruning techniques and a depth-first search strategy, CloHusp effectively identifies sequences that are both frequent and of high utility, making it suitable for applications in fields like market basket analysis, sequence analysis, and recommendation systems.

**RA-CloHusp** extends the capabilities of CloHusp by introducing a clustering-based approach to enhance pattern interpretability and reduce redundancy. RA-CloHusp clusters similar CHUSPs, allowing users to focus on the most significant and informative patterns, further improving the usability of the mined data.

## Key Contributions of the Research

- **Efficient Mining**: Utilizes pruning techniques and a depth-first search strategy for efficient identification of CHUSPs.
- **High Utility Sequences**: Focuses on mining sequences that are both frequent and of high utility, ensuring relevance and value.

- **Novel Problem Formulation:** This research pioneers the exploration of redundancy-aware closed high-utility sequential patterns (RA-CHUSPs), addressing a significant gap in the field of data mining.
- **Innovative Data Representation:** A novel dynamic vector-based vertical representation is introduced to efficiently store and access the dataset.
- **Advanced Pruning Techniques:** 
   * The research leverages state-of-the-art upper bounds (SWU, RBU, and RLBU) to intelligently prune the search space, significantly reducing computational costs.
   * A new early elimination technique based on support and SWU equivalence is proposed to further optimize the mining process.
- **Efficient Mining Algorithm:** The CloHusp algorithm is designed to efficiently mine CHUSPs using a depth-first search approach.
- **Pattern Clustering (RA-CloHusp)**: Groups similar CHUSPs to reduce redundancy and improve interpretability.
- **Significant Pattern Highlighting**: In RA-CloHusp, clusters reveal the most informative patterns, aiding in data analysis and decision-making.
- **Redundancy-Aware Clustering:** The RA-CloHusp algorithm introduces a novel clustering technique to identify and group redundant CHUSPs, improving the interpretability of the mined patterns.
- **Pattern Density and Dissimilarity Metrics:** The research defines a pattern density concept and a dissimilarity metric to effectively cluster CHUSPs based on their support, utility, and itemset composition.


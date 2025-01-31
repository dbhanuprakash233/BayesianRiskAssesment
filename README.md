# Bayesian Risk Assesment Using Cybersecurity Data

In the realm of data analysis and modeling, Bayesian statistics and machine learning (ML) offer powerful tools, each with distinct strengths and applications. Bayesian statistics excels in probabilistic analysis, allowing the incorporation of prior knowledge and handling uncertainty through a transparent, interpretable framework. It is particularly effective with small datasets and in scenarios requiring sequential data updating and decision-making under uncertainty. On the other hand, machine learning shines in processing large, complex datasets, identifying patterns and anomalies, and performing real-time analysis. It is ideal for automation and handling unstructured data, providing robust solutions for dynamic and evolving environments. Understanding when and why to use each approach can significantly enhance your analytical capabilities and decision-making processes.

In the realm of data analysis and modeling, Bayesian statistics provides a principled framework for probabilistic reasoning, enabling the incorporation of prior knowledge, quantification of uncertainty, and dynamic updating of beliefs as new data becomes available. Unlike frequentist methods, Bayesian inference treats parameters as probability distributions, making it particularly well-suited for small datasets, decision-making under uncertainty, and problems requiring sequential learning. Its applications span diverse fields, from finance and healthcare to cybersecurity and artificial intelligence, where interpretability and adaptability are crucial. While machine learning excels in pattern recognition and handling large-scale unstructured data, Bayesian methods enhance predictive modeling by integrating domain expertise and providing uncertainty-aware estimates. Mastering Bayesian techniques can significantly improve analytical depth, making them indispensable for robust decision-making in uncertain environments.

In this project, we work on four datasets dealing with the relationship among **four** nodes: Assets, Vulnerabilities, Threat Actors, Attack Vectors. These datasets give relationship between these four nodes as follows: 1. Dataset 1: Asset-Vulnerability Dataset: Asset, Vulnerability, CVSS_Score,Exploit Probability  2. Vulnerability-Attack Vector Dataset: Vulnerability, Attack Vector, Success Probability 3. Threat Actor - Asset Dataset: Threat Actor, Asset, Target Probability 4. Threat Actor - Attack Vector Dataset: Threat Actor, Attack Vector, Success Rate. 

# Project Overview  

In this project, we analyze four datasets that capture the relationships among **four key nodes**:  

- **Assets**  
- **Vulnerabilities**  
- **Threat Actors**  
- **Attack Vectors**  

These datasets define the interactions between these nodes as follows:  

1. **Asset-Vulnerability Dataset**  
   - **Fields**: `Asset`, `Vulnerability`, `CVSS_Score`, `Exploit Probability`  

2. **Vulnerability-Attack Vector Dataset**  
   - **Fields**: `Vulnerability`, `Attack Vector`, `Success Probability`  

3. **Threat Actor - Asset Dataset**  
   - **Fields**: `Threat Actor`, `Asset`, `Target Probability`  

4. **Threat Actor - Attack Vector Dataset**  
   - **Fields**: `Threat Actor`, `Attack Vector`, `Success Rate`  

This structured approach enables us to model relationships between assets, vulnerabilities, and threats effectively, forming the foundation for Bayesian Network construction and analysis.  

Outcomes: 
1. We constructed a Bayesian Network based on the given data.
2. We calculate the **posterior probabilities** of successful exploitation for each asset by integrating prior attack probabilities, conditional probabilities of attack success, and relationships between assets, vulnerabilities, and attack vectors.
3. We ranked assets based on risk and provide insights into which assets are most vulnerable.

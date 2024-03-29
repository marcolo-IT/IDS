# Intrusion Detection System
Intrusion Detection System using machine learning

# Data

The dataset comes from Kaggle. It consists of a wide variety of intrusions simulated in a military network
environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes. For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two categories:
- Normal
- Anomalous

# Summary

Three models were used in this experiment: Bernoulli Naive Baye, Decision Tree, and Logistic Regression. The results of each model are printed as outputs on [detect.ipynb](https://github.com/DamoNeer/IDS/blob/main/detect.ipynb). In order to get better results, I would try combining the ML models or implementing a voting ensemble.


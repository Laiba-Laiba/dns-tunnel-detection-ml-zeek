DNS Tunnel Detection with ML and Zeek
Overview

This project enhances DNS threat detection by combining Zeek network monitoring with Machine Learning classifiers (RandomForest & XGBoost). It detects malicious DNS tunneling queries that may bypass traditional SIEM rules in Wazuh.

Features

Real-time DNS monitoring using Zeek

ML-based classification of DNS queries (entropy, subdomain length, character ratios)

Detection of subtle or encoded tunneling domains

Integration with Wazuh for baseline alerts

Tools & Technologies

Zeek

Wazuh

Python

Scikit-learn & XGBoost

Iodine (for generating test DNS tunneling queries)

Jupyter Notebook

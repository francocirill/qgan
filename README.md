# **Quantum-Enhanced Generative Adversarial Network (QGAN)**  

This repository contains a Python implementation of a **Quantum Generative Adversarial Network (QGAN)** using PyTorch and Qiskit. The project explores the integration of quantum circuits for the generator and classical neural networks for the discriminator, aimed at generating synthetic data that mimics real data distributions for Intrusion Detection.  

## **Project Overview**  

This implementation leverages quantum machine learning to train a hybrid **Quantum-Classical Generative Adversarial Network**.  
- The **generator** utilizes quantum circuits based on Qiskit's `SamplerQNN`, a parameterized quantum circuit architecture enhanced with feature maps and ansatzes.  
- The **discriminator** is a classical feedforward neural network built using PyTorch for binary classification.  

The project demonstrates:  
1. **Quantum circuit design** for generative models.  
2. **Training adversarial networks** combining quantum and classical components.  
3. Evaluation techniques to measure statistical similarity between real and generated data.  
4. An **interpret function** that maps quantum outputs (measurements of qubit states) to input features resembling real data distributions.  

## **Citation**  

@conference{qaio25,
author={Franco Cirillo and Christian Esposito},
title={Intrusion Detection System Based on Quantum Generative Adversarial Network},
booktitle={Proceedings of the 17th International Conference on Agents and Artificial Intelligence - Volume 1: QAIO},
year={2025},
pages={830-838},
publisher={SciTePress},
organization={INSTICC},
doi={10.5220/0013397800003890},
isbn={978-989-758-737-5},
issn={2184-433X},
}

## Acknowledgment
This research is funded by the NGIsargasso project (Europe Horizon Grant No. 101092887), Open Call 4  FRQGAN4AD project. 

## Contact
Franco Cirillo fracirillo@unisa.it

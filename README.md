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

If you plan to use this code for your work, please cite the associated paper once it is published. Kindly check back on this GitHub page for updates regarding the publication status and citation information.

## Contact
Franco Cirillo fracirillo@unisa.it

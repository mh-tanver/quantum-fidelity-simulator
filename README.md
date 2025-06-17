# quantum-fidelity-simulator

This project explores the simulation of noisy quantum circuits and the application of quantum error correction techniques to improve fidelity. Using Qiskit, we model depolarizing noise and evaluate fidelity before and after correction. We then apply machine learning techniques to predict fidelity outcomes based on circuit and noise parameters. An interactive dashboard will allow users to simulate quantum behavior, visualize results, and experiment with predictive models. This repository serves both as a scientific exploration and a portfolio demonstration of quantum computing, data science, and ML engineering skills.

📖 Prerequisites

Quantum Computing

Qubits, gates (X, Z, H, CNOT), measurement

Quantum errors: bit-flip, phase-flip, depolarizing noise

Error correction: repetition code, Shor code

Fidelity: similarity metric between quantum states

Tools

Qiskit

Python, NumPy, pandas

scikit-learn, XGBoost

Streamlit / Dash

Matplotlib / Plotly

📏 Phase 1: Simulation & Data Collection

1. Simulate Noisy Circuits

Choose simple 3-5 qubit circuits

Apply depolarizing noise using Qiskit Aer

2. Apply Error Correction

Use repetition codes

Measure fidelity before and after correction

3. Dataset Structure

| Circuit_ID | Noise_Level | Error_Correction | Pre_Fidelity | Post_Fidelity |

Run 1000+ trials with varied parameters.

📊 Phase 2: ML Modeling

- Problem

- Regression: Predict Post_Fidelity

- Classification: Predict high/low fidelity outcome

Models

- Random Forest, XGBoost, Linear Regression

- Evaluate with RMSE, MAE, Confusion Matrix

- Visualization

- Feature importance

- Fidelity distribution plots

🌐 Phase 3: Dashboard & Presentation

Interactive Dashboard

Inputs: circuit type, noise level, error correction

Outputs: simulated fidelity + predicted fidelity

Comparison graphs: pre vs post error correction

Deployment

Host on Streamlit Share / HuggingFace Spaces

GitHub repo with clean README, notebooks, images

Optional blog post walkthrough

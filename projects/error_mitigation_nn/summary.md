# Quantum Error Mitigation with Adaptive Neural Networks

This project presents a novel approach to quantum error mitigation using an adaptive neural network architecture (ANN-QEM) that dynamically adjusts to different types of quantum noise. Rather than relying on static mitigation techniques, this method integrates a classifier and a regression neural network that respond in real-time to the characteristics of the quantum system’s errors.

Using simulations and real quantum hardware (127-qubit IBM Brisbane), we generated over 5,000 noisy quantum circuits incorporating Pauli, amplitude damping, and depolarizing noise models. The classifier module identifies the type of noise affecting a circuit, while the regression module predicts corrected expectation values using features such as circuit depth, gate sequences, and measurement statistics.

Our fully neural adaptive model achieved **99.99% accuracy** and outperformed traditional digital Zero Noise Extrapolation (ZNE) in both accuracy and runtime. The architecture scales efficiently and generalizes across quantum processors, offering a robust solution for near-term quantum devices (NISQ era).

**Key Contributions:**
- Introduced a dual-module adaptive neural network (classifier + regressor)
- Demonstrated significant error reduction and speedup over ZNE methods
- Validated on realistic IBM hardware with minimal computational overhead

**Publication:**  
Adeniyi, T., & Kumar, S. (2025). *Adaptive Neural Network for Quantum Error Mitigation*. Quantum Machine Intelligence, 7:13.  
[DOI: 10.1007/s42484-024-00234-4](https://doi.org/10.1007/s42484-024-00234-4)

---

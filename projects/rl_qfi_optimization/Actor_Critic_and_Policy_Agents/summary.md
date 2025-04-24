# Reinforcement Learning for Optimizing Quantum Sensor Circuits

In this project, I applied reinforcement learning to the problem of quantum sensor circuit design—specifically targeting circuits that maximize Quantum Fisher Information (QFI), which is essential for achieving high-precision measurements in quantum metrology.

I trained two types of RL agents—a policy gradient agent and an actor-critic agent—to learn gate sequences that prepare optimal sensing states in a four-qubit Ramsey interferometer setup. Both agents successfully discovered circuits that reached QFI = 1, but in different ways: the policy gradient agent learned faster, while the actor-critic agent found more gate-efficient solutions.

What made this project exciting was seeing how the agents navigated the design space without prior knowledge of quantum physics—just through trial, error, and QFI-based rewards. It was also one of the first times I got to build a full simulation environment from scratch, model quantum circuits as a Markov Decision Process, and train policies that generalize across different configurations.

This work was accepted at IEEE QCE 2024 and gave me a much deeper understanding of how machine learning can help automate quantum design in meaningful ways.

**Publication:**  
Adeniyi, T., & Kumar, S. (2024). *Reinforcement Learning Based Actor Critic and Policy Agent for Optimized Quantum Sensor Circuit Design*. IEEE Quantum Computing and Engineering Conference (QCE).  
[DOI: 10.1109/QCE60285.2024.00146](https://doi.org/10.1109/QCE60285.2024.00146)


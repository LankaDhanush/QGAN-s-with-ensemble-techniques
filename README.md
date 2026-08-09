# QGAN-s-with-ensemble-techniques
Quantum Generative Adversarial Network (QGAN) implementation utilizing ensemble techniques for fashion image synthesis. Features PyTorch model checkpoints (disc_epoch60.pt) and progressive output samples across training epochs.
# Quantum GAN (QGAN) with Ensemble Techniques for Fashion Synthesis

A hybrid Quantum-Classical Generative Adversarial Network (QGAN) enhanced with ensemble strategies for fashion image generation and discrimination.

## Project Summary

* **Architecture:** Quantum Generative Adversarial Network (QGAN) with Ensemble Learning
* **Frameworks:** PyTorch + Quantum Machine Learning (e.g., Qiskit / PennyLane)
* **Training Run:** `fashion_20251117_160350`
* **Artifacts:** Progressive epoch sample images (`Epoch 0` and `Epoch 20`) and saved Discriminator weights (`disc_epoch60.pt`)

---

## Technical Highlights

* **Quantum Generator / Discriminator Integration:** Explores quantum circuits to enhance sample diversity and training stability in generative tasks.
* **Ensemble Techniques:** Uses ensemble strategies across quantum/classical components to improve output fidelity and reduce mode collapse.
* **Progressive Evaluation:** Tracking image quality across early (`samples_epoch_0.png`) and intermediate (`samples_epoch_20.png`) epochs.

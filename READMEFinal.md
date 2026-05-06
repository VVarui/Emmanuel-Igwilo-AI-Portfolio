# Emmanuel Igwilo — AI Portfolio
### Deep Learning · ITAI 2376 · Houston City College · Spring 2026

---

## About

This repository documents hands-on lab work completed in **ITAI 2376: Deep Learning** as part of the AI & Robotics Program at Houston City College. Each module builds progressively from foundational neural networks through modern generative and reinforcement learning systems.

---

## Repository Structure

```
Emmanuel-Igwilo-AI-Portfolio/
├── README.md
└── DeepLearning-ITAI2376/
    ├── Module_02_Neural_Network_Foundations/
    │   └── Module_02_Lab_02_Emmanuel_Igwilo.ipynb
    ├── Module_03_CNNs_Image_Classification/
    │   └── Module_03_Lab_Emmanuel_Igwilo.ipynb
    ├── Module_05_RNNs_vs_Transformers/
    │   └── Module_05_Emmanuel_Igwilo_ITAI_2376.ipynb
    ├── Module_08_Diffusion_Models/
    │   └── L08_Diffusion_Emmanuel_Igwilo_ITAI_2376.ipynb
    └── Module_09_Reinforcement_Learning/
        └── ITAI_2376_Module09_Emmanuel_Igwilo_Lab.ipynb
```

---

## Projects

### Module 02 — Neural Network Foundations
**File:** `Module_02_Lab_02_Emmanuel_Igwilo.ipynb`

Built neural networks from scratch using NumPy, then replicated the same architecture in PyTorch and TensorFlow/Keras. Explored the practical differences between dynamic (PyTorch) and static (TensorFlow) computation graphs. Dataset: Fashion-MNIST.

**Key concepts:** Backpropagation, gradient descent, activation functions, dropout regularization, hyperparameter tuning, framework comparison.

---

### Module 03 — CNNs for Image Classification
**File:** `Module_03_Lab_Emmanuel_Igwilo.ipynb`

Trained a convolutional neural network on the "Puppy or Bagel?" Kaggle dataset — a binary image classification challenge inspired by Karen Zack's viral meme. Applied transfer learning with ResNet50 and MobileNetV2.

**Key concepts:** Convolutional layers, pooling, feature maps, transfer learning, fine-tuning, ImageDataGenerator, confusion matrices.

---

### Module 05 — RNNs vs. Transformers vs. Vision Transformers
**File:** `Module_05_Emmanuel_Igwilo_ITAI_2376.ipynb`

Head-to-head comparison of three major architecture families on the same text dataset (AG News), then extended Transformer ideas to image classification with Vision Transformers (ViT) on CIFAR-10.

| Part | Architecture | Task |
|------|-------------|------|
| A | LSTM & GRU | News topic classification |
| B | DistilBERT | News topic classification (same data) |
| C | ViT | Image classification (CIFAR-10) |

**Key concepts:** Sequence modeling, attention mechanisms, BERT fine-tuning, positional encoding, multi-head attention, apples-to-apples benchmarking.

---

### Module 08 — Diffusion Models
**File:** `L08_Diffusion_Emmanuel_Igwilo_ITAI_2376.ipynb`

Implemented a diffusion model to generate realistic handwritten digits from pure noise. Visualized the forward noising process and reverse denoising process step-by-step. Dataset: MNIST.

**Key concepts:** Forward/reverse diffusion, U-Net architecture, denoising score matching, noise schedules, `einops` tensor operations, generative evaluation.

---

### Module 09 — Reinforcement Learning Foundations
**File:** `ITAI_2376_Module09_Emmanuel_Igwilo_Lab.ipynb`

Compared a random agent against a Q-Learning agent in the CartPole-v1 environment (Gymnasium). Observed the learning curve from random failure to stable pole balancing, then connected classical RL concepts to RLHF — the training paradigm used in LLMs like GPT-4 and Claude.

**Key concepts:** State/action/reward loop, Q-table, exploration vs. exploitation, epsilon-greedy policy, RLHF connection, CartPole benchmark.

---

## Technologies Used

- **Frameworks:** PyTorch, TensorFlow/Keras, Hugging Face Transformers
- **Libraries:** NumPy, Matplotlib, scikit-learn, einops, Gymnasium
- **Datasets:** Fashion-MNIST, MNIST, CIFAR-10, AG News, Puppy-or-Bagel (Kaggle)
- **Environment:** Google Colab (free tier)

---

## Course Information

| Field | Detail |
|-------|--------|
| Course | ITAI 2376 — Deep Learning |
| Institution | Houston City College |
| Program | AI & Robotics |
| Semester | Spring 2026 |
| Instructor | Patricia McManus, M.S. |
| Student | Emmanuel Igwilo |

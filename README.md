# Ilya Sutskever's AI Resources

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md) [![Markdown](https://img.shields.io/badge/format-Markdown-000000.svg)](https://www.markdownguide.org/)

> A beginner-friendly, chronological roadmap from foundational mathematics and neural networks to modern large language model architectures.

## 📚 Introduction

There is a well-known piece of AI lore about a conversation between **Ilya Sutskever** and **John Carmack**. Ilya shared a compact list of roughly 30 papers and suggested that truly understanding them would cover **“90% of what matters”** in modern artificial intelligence.

The list is powerful—but it is also dense, mathematical, and difficult to approach without a technical background. This repository reorganizes those ideas into a practical, step-by-step curriculum for learners starting from zero.

The mission is simple: **bridge the gap between curiosity and comprehension**. You do not need to be an expert mathematician or experienced researcher to begin. Follow the sequence, build intuition before diving into formalism, and use each phase as a foundation for the next.

## 🧭 Table of Contents

- [The Roadmap](#-the-roadmap)
  - [Phase 1: Prerequisites](#phase-1-prerequisites)
  - [Phase 2: Building Intuition](#phase-2-building-intuition)
  - [Phase 3: Formal Deep Learning](#phase-3-formal-deep-learning)
  - [Phase 4: The Vision Revolution](#phase-4-the-vision-revolution)
  - [Phase 5: Memory Sequences and Reasoning](#phase-5-memory-sequences-and-reasoning)
  - [Phase 6: The Transformer Era](#phase-6-the-transformer-era)
  - [Phase 7: Scaling and Information Theory](#phase-7-scaling-and-information-theory)
- [How to Use This Guide](#-how-to-use-this-guide)
- [Contributing](#-contributing)
- [License](#-license)

## 🗺️ The Roadmap

Work through the phases in order, or use the checkboxes to create your own study log.

### Phase 1: Prerequisites

Build the minimum technical foundation needed to read the papers comfortably.

- [ ] **Python fundamentals:** variables, functions, control flow, data structures, classes, NumPy, and plotting.
- [ ] **Probability:** random variables, distributions, expectation, variance, conditional probability, Bayes' theorem, and maximum likelihood.
- [ ] **Linear algebra:** vectors, matrices, dot products, matrix multiplication, transposes, norms, eigenvalues, and basic derivatives.
- [ ] **Calculus and optimization:** derivatives, gradients, the chain rule, and gradient descent.

> Target level: the equivalent of **Class 12 mathematics**, with enough Python to implement small experiments from scratch.

### Phase 2: Building Intuition

Develop a mental model for how neural networks process sequences before tackling the formal papers.

- [ ] Read **“The Unreasonable Effectiveness of Recurrent Neural Networks”** by Andrej Karpathy.
- [ ] Read **“Understanding LSTM Networks”** by Christopher Olah.
- [ ] Implement a small character-level RNN and experiment with sequence prediction.
- [ ] Implement or modify a simple LSTM to understand hidden state, memory, and gating.

### Phase 3: Formal Deep Learning

Learn the vocabulary, mathematics, and engineering patterns used throughout modern deep learning.

- [ ] Complete the relevant lectures from **Stanford CS231n: Convolutional Neural Networks for Visual Recognition**.
- [ ] Understand forward passes, loss functions, backpropagation, regularization, and optimization.
- [ ] Study convolution, pooling, normalization, activation functions, and residual connections.
- [ ] Build and train a small image classifier in a modern deep learning framework.

### Phase 4: The Vision Revolution

See how a combination of data, computation, and architectural improvements transformed computer vision.

- [ ] Read **“ImageNet Classification with Deep Convolutional Neural Networks”** (AlexNet).
- [ ] Read **“Deep Residual Learning for Image Recognition”** (ResNet).
- [ ] Explain why depth, GPUs, large datasets, ReLU activations, and residual connections matter.
- [ ] Reproduce a simplified CNN and compare it with a residual network.

### Phase 5: Memory, Sequences, and Reasoning

Explore architectures designed to store information, manipulate relationships, and reason over structured inputs.

- [ ] Read **“Neural Turing Machines”** by Graves, Wayne, and Danihelka.
- [ ] Understand differentiable memory, attention-based read/write operations, and algorithmic generalization.
- [ ] Read **“Relational Reasoning in Neural Networks”** by Santoro et al.
- [ ] Study how explicit relations and pairwise interactions can improve reasoning.

### Phase 6: The Transformer Era

Understand the architecture that powers most modern large language models.

- [ ] Read **“Attention Is All You Need”** by Vaswani et al.
- [ ] Understand self-attention, queries, keys, values, positional encoding, masking, and multi-head attention.
- [ ] Work through **The Annotated Transformer** by Harvard NLP.
- [ ] Implement a minimal Transformer and train it on a small text dataset.
- [ ] Connect the original encoder-decoder design to decoder-only LLMs such as GPT-style models.

### Phase 7: Scaling and Information Theory

Finish by studying why modern models improve with scale and how information-theoretic ideas shape learning.

- [ ] Read **“Scaling Laws for Neural Language Models”** by Kaplan et al.
- [ ] Understand the relationships among model size, dataset size, compute, and loss.
- [ ] Study the **Minimum Description Length (MDL) principle** and its connection to compression and generalization.
- [ ] Reflect on how scaling, data quality, architecture, and inference-time computation interact.

## 🧑‍💻 How to Use This Guide

1. **Follow the sequence.** Each phase introduces ideas that make the next phase easier.
2. **Learn actively.** Reimplement small pieces, draw diagrams, and explain concepts in your own words.
3. **Use papers as references.** Read the abstract, introduction, architecture diagrams, and conclusions first; return to the proofs and experiments later.
4. **Keep a study log.** Check off topics only when you can describe the core idea and its motivation without copying the paper.
5. **Expect multiple passes.** Difficult papers become much clearer after you have built the relevant intuition and code.

> 💡 **Beginner's Tip:** Don't read papers front-to-back on the first try. Skip the heavy math initially and focus on the architecture, the problem being solved, and the conclusions. Come back for the details once the big picture is familiar.

## 🤝 Contributing

Contributions are welcome! Help make this roadmap more useful and approachable by submitting:

- Clear study notes or beginner-friendly explanations.
- Accurate summaries of the papers and their historical context.
- Small, well-documented code implementations or notebooks.
- Corrections, resource recommendations, diagrams, and improved learning sequences.

Please keep contributions educational, reproducible, and respectful. Open an issue for a larger proposal, or submit a pull request with a focused change and a short explanation of what it adds.

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for the full text.

The papers and external resources referenced here remain the property of their respective authors and publishers. Please follow each source's licensing and citation requirements.

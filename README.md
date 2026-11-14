# Ilya Sutskever's AI Resources

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md) [![Markdown](https://img.shields.io/badge/format-Markdown-000000.svg)](https://www.markdownguide.org/)

## Introduction

There is a famous piece of AI lore about a conversation between **Ilya Sutskever** and **John Carmack**. Ilya shared a compact list of roughly 30 foundational papers and suggested that mastering them would cover **“90% of what matters”** in artificial intelligence.

The original list is dense, mathematical, and intimidating to approach without a technical background. This repository turns it into a structured curriculum for complete beginners: start with intuition and practical foundations, progress through landmark architectures, and finish with the ideas behind modern LLMs, scaling, information theory, and complexity.

The mission is to **bridge the gap between curiosity and comprehension**. You do not need to be an expert mathematician or experienced researcher to begin. Follow the sequence, build intuition before diving into formalism, and use each phase as a foundation for the next.

## Table of Contents

- [The Roadmap](#-the-roadmap)
  - [Phase 1: Foundations and Introductions](#phase-1-foundations-and-introductions)
  - [Phase 2: Foundational Architectures](#phase-2-foundational-architectures)
  - [Phase 3: Sequence, Sets, and Relational Reasoning](#phase-3-sequence-sets-and-relational-reasoning)
  - [Phase 4: Scaling and Applied Deep Learning](#phase-4-scaling-and-applied-deep-learning)
  - [Phase 5: Information Theory, Complexity, and Compression](#phase-5-information-theory-complexity-and-compression)
- [How to Use This Guide](#-how-to-use-this-guide)
- [Contributing](#-contributing)
- [License](#-license)

## The Roadmap

Work through the phases in order, or use the checkboxes to create your own study log. Each paper is linked to its original or canonical source.

### Phase 1: Foundations and Introductions

Build the mathematical, conceptual, and practical foundation needed to read the papers that follow.

- [ ] **Prerequisites:** Review Python fundamentals, vectors and matrices, probability, derivatives, gradients, and gradient descent.
- [ ] [**CS231n: Convolutional Neural Networks for Visual Recognition**](http://cs231n.stanford.edu/) — Build a formal foundation in deep learning and computer vision.
- [ ] [**The Unreasonable Effectiveness of Recurrent Neural Networks**](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) — Develop intuition for recurrent models through hands-on examples.
- [ ] [**Understanding LSTM Networks**](https://colah.github.io/posts/2015-08-Understanding-LSTMs/) — Learn how gated memory helps neural networks model long-range dependencies.
- [ ] [**The Annotated Transformer**](https://nlp.seas.harvard.edu/2018/04/03/attention.html) — Connect theory to an accessible implementation of the Transformer architecture.

> **Checkpoint:** You should be able to explain a neural network's forward pass, loss, gradient update, recurrent state, and attention at a high level.

### Phase 2: Foundational Architectures

Study the architectural breakthroughs that reshaped computer vision, sequence modeling, and machine translation.

- [ ] [**ImageNet Classification with Deep Convolutional Neural Networks**](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) — **AlexNet, 2012**; understand the deep CNN breakthrough.
- [ ] [**Deep Residual Learning for Image Recognition**](https://arxiv.org/abs/1512.03385) — **ResNet, 2015**; learn why residual connections enable very deep networks.
- [ ] [**Identity Mappings in Deep Residual Networks**](https://arxiv.org/abs/1603.05027) — **2016**; examine the design choices behind stable residual learning.
- [ ] [**Neural Machine Translation by Jointly Learning to Align and Translate**](https://arxiv.org/abs/1409.0473) — **2014**; study the origins of neural attention for translation.
- [ ] [**Multi-Scale Context Aggregation by Dilated Convolutions**](https://arxiv.org/abs/1511.07122) — **2015**; understand how dilation expands receptive fields without losing resolution.
- [ ] [**Attention Is All You Need**](https://arxiv.org/abs/1706.03762) — **2017**; learn the Transformer architecture that underpins modern LLMs.

### Phase 3: Sequence, Sets, and Relational Reasoning

Explore models that handle memory, ordering, permutation structure, pointers, and relationships among entities.

- [ ] [**Recurrent Neural Network Regularization**](https://arxiv.org/abs/1409.2329) — **2014**; understand practical techniques for improving recurrent models.
- [ ] [**Pointer Networks**](https://arxiv.org/abs/1506.03134) — **2015**; see how attention can point to positions in an input sequence.
- [ ] [**Order Matters: Sequence to sequence for sets**](https://arxiv.org/abs/1511.06391) — **2015**; study how neural networks can represent sets and ordering information.
- [ ] [**Neural Turing Machines**](https://arxiv.org/abs/1410.5401) — **2014**; investigate differentiable memory and algorithmic generalization.
- [ ] [**A simple neural network module for relational reasoning**](https://arxiv.org/abs/1706.01427) — **2017**; learn how explicit pairwise relations support reasoning.
- [ ] [**Relational recurrent neural networks**](https://arxiv.org/abs/1806.01822) — **2018**; combine recurrent memory with relational interactions.
- [ ] [**Neural Message Passing for Quantum Chemistry**](https://arxiv.org/abs/1704.01212) — **2017**; understand graph-based message passing as a general reasoning pattern.

### Phase 4: Scaling and Applied Deep Learning

See how computation, systems engineering, data, and model scale turn research ideas into practical capabilities.

- [ ] [**Scaling Laws for Neural Language Models**](https://arxiv.org/abs/2001.08361) — **2020**; study how model size, data, compute, and loss relate.
- [ ] [**GPipe: Easy Scaling with Micro-Batch Pipeline Parallelism**](https://arxiv.org/abs/1811.06965) — **2018**; learn how large networks are distributed across hardware.
- [ ] [**Deep Speech 2: End-to-End Speech Recognition in English and Mandarin**](https://arxiv.org/abs/1512.02595) — **2015**; examine large-scale end-to-end learning for speech.
- [ ] [**Variational Lossy Autoencoder**](https://arxiv.org/abs/1611.02731) — **2016**; connect latent-variable modeling, reconstruction, and generative learning.

### Phase 5: Information Theory, Complexity, and Compression

Finish by exploring the deeper principles that connect learning, compression, description length, randomness, and complex behavior.

- [ ] [**Keeping Neural Networks Simple by Minimizing the Description Length of the Weights**](https://www.cs.toronto.edu/~hinton/absps/colt93.pdf) — **1993**; connect generalization to minimum description length.
- [ ] [**A Tutorial Introduction to the Minimum Description Length Principle**](https://arxiv.org/abs/math/0406077) — **2004**; build a practical information-theoretic perspective on model selection.
- [ ] [**Kolmogorov Complexity and Algorithmic Randomness**](https://link.springer.com/book/10.1007/978-3-540-39333-8) — Study the limits of describing objects and sequences algorithmically.
- [ ] [**The First Law of Complexodynamics**](https://scottaaronson.blog/?p=762) — **2013**; consider how complexity can evolve in computational systems.
- [ ] [**Quantifying the Rise and Fall of Complexity in Closed Systems: The Coffee Automaton**](https://arxiv.org/abs/1405.6903) — **2014**; investigate measurable complexity dynamics in closed systems.
- [ ] [**Machine Super Intelligence**](https://arxiv.org/abs/0812.4432) — **2008**; reflect on long-term questions surrounding machine intelligence and capability.

> **Final checkpoint:** You should be able to explain how representations, memory, attention, scale, computation, compression, and generalization fit together in modern AI.

## How to Use This Guide

1. **Follow the sequence.** Each phase introduces ideas that make the next phase easier.
2. **Learn actively.** Reimplement small pieces, draw diagrams, and explain concepts in your own words.
3. **Use papers as references.** Read the abstract, introduction, architecture diagrams, and conclusions first; return to proofs and experiments later.
4. **Keep a study log.** Check off a resource only when you can describe its core idea and motivation without copying the paper.
5. **Expect multiple passes.** Difficult papers become much clearer after you have built the relevant intuition and code.

> **Beginner's Tip:** Don't read papers front-to-back on the first try. Skip the heavy math initially and focus on the architecture, the problem being solved, and the conclusions. Come back for the details once the big picture is familiar.

## Contributing

Contributions are welcome! Help make this roadmap more useful and approachable by submitting:

- Clear study notes or beginner-friendly explanations.
- Accurate paper summaries and historical context.
- Small, well-documented code implementations or notebooks.
- Corrections, resource recommendations, diagrams, and improved learning sequences.

Please keep contributions educational, reproducible, and respectful. Open an issue for a larger proposal, or submit a focused pull request with a short explanation of what it adds.

## License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for the full text.

The papers and external resources referenced here remain the property of their respective authors and publishers. Please follow each source's licensing and citation requirements.

# **Deep Dive Into Legendary Self-Attention Mechanism**

**"Attention Is All You Need"** — Vaswani et al. (2017)

This repository contains the presentation slides and code demonstration resources from my webinar: **"Deep Dive Into Legendary Self-Attention Mechanism"**.

The goal of this material is to demystify the core mechanism behind modern Large Language Models (LLMs) like GPT-4, Gemini, and Claude, moving from high-level intuition to mathematical implementation.

## **Content Overview**

The material is structured into 6 main sessions, covering the evolution from RNNs to Transformers.

### **1\. The "Legendary" Status**

* Why Self-Attention is the "Big Bang" of modern AI.  
* The shift from Sequential (RNN) to Parallel (Transformer) processing.  
* Impact on fields beyond NLP (AlphaFold, Vision Transformers).

### **2\. The Bottleneck (Problems with RNN/LSTM/GRU)**

* The limitation of sequential computation ($O(N)$ path length).  
* The "Vanishing Gradient" and Long-term Dependency problem ("Amnesia").  
* Why "Large" Language Models were impossible before 2017\.

### **3\. The Core Concept: Q, K, V**

* Intuitive analogy: The "Database Retrieval" system.  
* Understanding **Query (Asking)**, **Key (Advertising)**, and **Value (Content)**.  
* Visualizing how words "attend" to each other.

### **4\. The Math & Normalization**

* Breakdown of the legendary formula:  
  $$Attention(Q, K, V) \= softmax\\left(\\frac{QK^T}{\\sqrt{d\_k}}\\right)V$$  
* Why we use **Dot Product** for similarity.  
* The importance of **Scaling Factor** ($\\sqrt{d\_k}$) to prevent vanishing gradients.

### **5\. Multi-Head Attention & Positional Encoding**

* Why one head is not enough (Syntax vs. Semantics).  
* How **Multi-Head Attention** captures different perspectives simultaneously.  
* **Positional Encoding**: Giving order to parallel processing.

### **6\. Implementation Demo (PyTorch)**

* A clean, step-by-step implementation of Scaled Dot-Product Attention in Python.  
* Heatmap visualization of attention weights.  
* [Click here to view the Notebook](https://colab.research.google.com/drive/1HDgc09qN3n_G1sz60On8yVj0n70jbgSD?usp=sharing)

## **Tech Stack**

* **Concept:** Natural Language Processing, Deep Learning, Transformers.  
* **Tools:** Python, PyTorch, Matplotlib, Seaborn (for visualization).

## **References**

* [Attention Is All You Need (Original Paper)](https://arxiv.org/abs/1706.03762)  
* [The Illustrated Transformer (Jay Alammar)](https://jalammar.github.io/illustrated-transformer/)

## **How to Cite**

If you find this repository useful for your research or educational content, please cite it as follows:

```
@misc{self\_attention\_webinar\_2025,  
  author \= {Lhuqita Fazry},  
  title \= {Deep Dive Into Legendary Self-Attention Mechanism: Webinar Materials},  
  year \= {2025},  
  publisher \= {GitHub},  
  howpublished \= {\\url{\[https://github.com/lhfazry/legendary-self-attention\](https://github.com/lhfazry/legendary-self-attention)}},  
}
```

## **Connect**

If you find this material helpful, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/lhuqita-fazry/) or give this repo a ⭐\!

*Created by \[Lhuqita Fazry\]*

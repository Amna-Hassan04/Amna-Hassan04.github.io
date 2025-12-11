---
title: GPT-2 Activation Patching App
date: 2025-01-11
links:
  - type: repo
    url: https://github.com/Amna-Hassan04/gpt-2-activation-patching-app
tags:
  - GPT-2
  - Interpretability
  - Activation Patching
  - AI Explainability
featured: true
---

The **GPT-2 Activation Patching App** is an interactive tool that demonstrates *mechanistic interpretability* concepts through a visual, user-friendly interface.  
It enables users to explore how specific layers and attention heads inside GPT-2 influence model predictions by performing *activation patching*—a technique used to understand causal contributions inside transformer models.

<!--more-->

## 🚀 Overview

This project turns advanced interpretability research into a hands-on application.  
It allows users to:

- Run **activation patching** between a *clean* and a *corrupted* prompt
- Inspect how activations differ across layers and heads
- Visualize the effects of patching using intuitive plots and heatmaps
- Understand which components of GPT-2 are responsible for specific behaviors
- Experiment with model internals without writing code

The app is perfect for students, researchers, or anyone curious about how transformer-based language models actually work under the hood.

## 🧠 Key Features

### 🔍 **Layer & Head-Level Patching**
Select any layer or attention head to patch its activations and observe how the model’s output changes.

### 📊 **Visualizations**
The app provides:
- Activation difference heatmaps
- Logit difference graphs
- Causal tracing visualizations
- Step-by-step interpretability insights

These help users interpret *why* a model makes specific predictions.

### ✏️ **Side-by-Side Prompts**
Users can input:
- A **clean prompt** (ground truth)
- A **corrupted prompt** (misleading or modified)

The app then applies activation patching to show how the clean prompt components improve or restore predictions.

### ⚡ **Built for Accessibility**
The interface makes complex research methods—normally used in mechanistic interpretability labs—accessible to anyone.

## 🧱 Tech Stack

- **Python**
- **Hugging Face Transformers**
- **PyTorch**
- **Streamlit**
- **NumPy / Matplotlib for visualizations**

## 📂 Repository

All source code is available here:  
👉 **https://github.com/Amna-Hassan04/gpt-2-activation-patching-app**

The repo includes:
- Core activation patching utilities
- GPT-2 visualization tools
- Streamlit frontend
- Example prompts and patching experiments

## 🧪 Example Use Cases

- Understanding how GPT models process factual vs. mis-info prompts
- Educational demos for LLM interpretability
- Research experiments on causal tracing
- Comparing activation patterns across layers

## 📌 Status

This is an evolving project. Contributions, suggestions, and experiments are welcome!
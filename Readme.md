# AI Research Engineer --- 90-Day Roadmap

> **AI/ML → Research Engineering → AI + Quantum Communication + QKD +
> 6G**

A focused 90-day roadmap for building strong **AI/ML fundamentals,
research-engineering skills, deployable AI systems, and an AI + QKD/6G
research profile**.

The roadmap is designed around one principle:

> **Optimize for depth of understanding, not the number of courses or
> papers completed.**

------------------------------------------------------------------------

## 🎯 End Goal

By the end of 90 days, the target is to be able to:

-   Build practical AI applications using Python, FastAPI, PostgreSQL
    and Next.js.
-   Understand classical ML mathematically and evaluate models
    correctly.
-   Understand neural networks, gradients and backpropagation.
-   Implement a CNN and **ResNet** in PyTorch.
-   Understand and implement **Transformers from scratch**.
-   Understand the evolution from **Word Embeddings → Seq2Seq →
    Attention → Transformers → BERT/GPT → LLMs**.
-   Build an end-to-end **RAG** system.
-   Understand practical LLM engineering: LoRA, QLoRA, quantization and
    evaluation.
-   Read research papers critically rather than passively.
-   Reproduce an experiment and perform ablations/error analysis.
-   Apply ML to **BB84/QKD security analysis**.
-   Build a coherent GitHub portfolio for **AI/ML internships, Master's
    applications and research opportunities**.

------------------------------------------------------------------------

# 🧭 Roadmap Structure

The roadmap has three parallel tracks:

### 1. Engineering

``` text
Python
  ↓
Git/GitHub
  ↓
FastAPI + PostgreSQL
  ↓
React / Next.js
  ↓
LLM APIs + RAG
  ↓
Docker + Deployment
```

### 2. AI / ML Research Foundations

``` text
Mathematics
  ↓
Classical ML
  ↓
Deep Learning
  ↓
CNN → ResNet
  ↓
NLP → Seq2Seq → Attention
  ↓
Transformer → BERT/GPT
  ↓
LLMs → RAG → LLM Engineering
```

### 3. Research Specialization

``` text
BB84
  ↓
QKD
  ↓
QBER
  ↓
Channel / Noise / Attack Simulation
  ↓
Dataset
  ↓
Classical ML
  ↓
Ablation + Robustness
  ↓
AI + QKD Security
  ↓
AI + 6G Security
```

------------------------------------------------------------------------

# 📅 12-Week Roadmap

## Month 1 --- Foundations + AI Engineering

### Week 1 --- Python + Git + Linear Algebra

**Engineering** - Python refresh - NumPy - Pandas - Matplotlib - APIs /
JSON - Exceptions - Virtual environments - Type hints - Git/GitHub

**Math --- Krish Naik**

### 🟢 Study

-   Section 2 --- Introduction To Linear Algebra
-   Section 3 --- Introduction To Functions And Transformation
-   Section 5 --- Eigen Vectors And Eigen Values

### 🟡 Selective

-   Section 4 --- Inverse Functions Or Transformation
-   Section 6 --- Equation Of A Line, Plane, Hyperplane

**Checkpoint** - Explain vectors, matrices, dot product and matrix
multiplication. - Explain linear transformations and eigenvalues at an
intuitive level.

------------------------------------------------------------------------

## Week 2 --- Mathematics + Classical ML

**Math --- Krish Naik**

### 🟢 Study

-   Section 7 --- Introduction To Statistics
-   Section 8 --- Descriptive Statistics
-   Section 9 --- Introduction To Probability
-   Section 10 --- Probability Distribution Function And Types Of
    Distribution
-   Section 18 --- Application Of Linear Algebra, Stats And Differential
    Calculus In Data Science
-   Section 19 --- Application Of Linear Algebra In Dimensionality
    Reduction

### 🟡 Selective / Later

-   Section 11 --- Inferential Stats And Hypothesis Testing
-   Section 12 --- Chi Square Test With Solved Examples
-   Section 13 --- ANOVA Test With Solved Examples

**Classical ML** - Linear Regression - Logistic Regression - Decision
Trees - Random Forest - SVM - K-Means - PCA - Evaluation metrics -
Overfitting / underfitting

**Checkpoint** - Explain why a model works, not just how to call
`fit()`. - Understand mean, variance, covariance, probability and PCA.

------------------------------------------------------------------------

## Week 3 --- FastAPI + PostgreSQL

**Engineering** - REST APIs - FastAPI - Pydantic - Validation -
Authentication - Error handling - Async basics - PostgreSQL - SQL CRUD -
Joins - Relationships - Indexes

**Math** - No new math. - Use Week 1--2 concepts only when required.

**Checkpoint** - Build a documented FastAPI backend connected to
PostgreSQL.

------------------------------------------------------------------------

## Week 4 --- AI Resume Analyzer + NLP Foundations

**Project 1 --- AI Resume Analyzer**

``` text
Resume PDF
   ↓
Text Extraction
   ↓
LLM
   ↓
Skills / Experience Extraction
   ↓
Job Description
   ↓
Semantic Matching
   ↓
Score + Suggestions
```

**Study** - NLP basics - Word embeddings - Semantic similarity - Cosine
similarity - LLM API integration - FastAPI + database integration

**Math** - Revise vectors, dot product and cosine similarity.

**Checkpoint** - Ship a working AI application rather than another
tutorial project.

------------------------------------------------------------------------

# Month 2 --- Deep Learning + Transformers

## Week 5 --- Deep Learning + PyTorch

**Math --- Krish Naik**

### 🟢 Study

-   Section 14 --- Differential Calculus
-   Section 15 --- Power Rules And Derivative Rules
-   Section 16 --- Product Rules In Derivative
-   Section 17 --- Chain Rule Of Derivatives
-   Section 20 --- Application Of Derivatives In Deep Learning Neural
    Network

### 🔴 Deep Study

Especially: - Chain Rule - Backpropagation - Weight updates -
Derivatives during backpropagation

**Deep Learning** - Perceptron - Neural networks - Forward propagation -
Backpropagation - Loss functions - Gradient descent - SGD - Adam -
Regularization - Dropout - Weight initialization

**PyTorch** - Tensor - Dataset / DataLoader - `nn.Module` - Autograd -
Optimizers - Training loop - GPU

**Checkpoint** - Derive and explain basic backpropagation without
blindly memorizing it.

------------------------------------------------------------------------

## Week 6 --- CNN + ResNet

**Study** - CNN fundamentals - Convolution - Padding - Pooling - Feature
maps - Flattening - Fully connected layers

**Paper --- Deep Read**

**Deep Residual Learning for Image Recognition --- He et al., 2015**

**Project 2 --- ResNet**

Implement:

``` text
Baseline CNN
     ↓
ResNet
     ↓
No-residual ablation
     ↓
Compare results
```

**Evaluate** - Accuracy - Loss - Training time - Convergence - Failure
cases

**Checkpoint** - Explain the degradation problem. - Explain why residual
connections help. - Complete at least one meaningful ablation.

------------------------------------------------------------------------

## Week 7 --- Transformers

**Prerequisite revision** - Vectors - Matrix multiplication - Dot
product - Probability - Softmax

**Paper --- Deep Read**

**Attention Is All You Need --- Vaswani et al., 2017**

**Study** - Self-attention - Query / Key / Value - Scaled dot-product
attention - Multi-head attention - Positional encoding - Feed-forward
network - Layer normalization - Residual connections - Encoder -
Decoder - Masked attention

**Project 3 --- Transformer From Scratch**

Implement the core components in PyTorch without starting with a
high-level Hugging Face abstraction.

**Checkpoint** - Derive:

``` text
Attention(Q,K,V)
= softmax(QKᵀ / √dₖ)V
```

-   Explain every term.
-   Implement basic attention yourself.

------------------------------------------------------------------------

## Week 8 --- NLP → BERT → GPT → LLMs

Follow the evolution:

``` text
Word Embeddings
      ↓
Seq2Seq
      ↓
Attention
      ↓
Transformer
      ↓
BERT
      ↓
GPT
      ↓
Modern LLMs
```

**Krish Naik** - RNN intuition - Seq2Seq - Attention mechanism -
Transformer architecture

### 🟡 Do not over-invest in

-   Full RNN implementation projects
-   Multiple LSTM/GRU projects
-   Bidirectional RNN variations

Understand the historical reason they existed and **why Transformers
replaced the recurrent approach for many modern NLP workloads**.

**Papers** - BERT - GPT-3 - InstructGPT

**Practice** - Fine-tune a pretrained BERT/GPT-style checkpoint on a
downstream task.

**Checkpoint** - Explain why attention was needed. - Explain the
difference between encoder-oriented BERT and decoder-oriented GPT.

------------------------------------------------------------------------

# Month 3 --- RAG + LLM Engineering + Research

## Week 9 --- RAG + AI Research Assistant

### Information Retrieval Evolution

``` text
TF-IDF / BM25
      ↓
Dense Retrieval
      ↓
DPR
      ↓
REALM
      ↓
RAG
      ↓
Reranking
```

**Study** - Chunking - Embeddings - Vector databases - Semantic
retrieval - Reranking - Context construction - Generation - Retrieval
evaluation

**Paper --- Deep Read**

**Retrieval-Augmented Generation --- Lewis et al., 2020**

### Project 4 --- AI Research Assistant

``` text
Research Paper PDF
        ↓
Text Extraction
        ↓
Chunking
        ↓
Embeddings
        ↓
Vector Database
        ↓
Retriever
        ↓
Reranker
        ↓
LLM
        ↓
Answer + Evidence
```

The assistant should help with: - Explaining methodology - Finding
limitations - Comparing papers - Identifying assumptions - Finding
potential research gaps

**Checkpoint** - Deploy a usable RAG application.

------------------------------------------------------------------------

## Week 10 --- LLM Engineering + MLOps

**Study only what is useful for your research-engineering direction.**

### LLM Engineering

-   Tokenization
-   Prompting
-   Structured outputs
-   Function calling
-   Streaming
-   Pretraining --- conceptual understanding
-   Instruction tuning
-   RLHF --- conceptual understanding
-   DPO
-   LoRA
-   QLoRA
-   Quantization
-   Evaluation
-   Hallucination
-   Tool use

### MLOps / Deployment

-   Git/GitHub
-   Docker
-   MLflow
-   DVC
-   DagsHub
-   CI/CD concepts
-   Deployment

### 🟡 Do not do

-   Full LLM pretraining
-   Heavy RLHF implementation
-   Large-scale distributed training

**Practice** - Run one small LoRA/QLoRA experiment. - Track an
experiment properly.

**Checkpoint** - Explain the difference between prompting, fine-tuning,
LoRA/QLoRA and RAG.

------------------------------------------------------------------------

## Week 11 --- Research Reproduction + Methodology

This week changes from **learning mode → research mode**.

### Research workflow

``` text
Research Question
      ↓
Hypothesis
      ↓
Baseline
      ↓
Experiment Design
      ↓
Implementation
      ↓
Evaluation
      ↓
Ablation
      ↓
Error Analysis
      ↓
Limitations
      ↓
Research Gap
```

### Formal reproduction

Recommended candidate:

**ResNet degradation/ablation experiment**

Why: - Low compute requirement - Clear experimental setup - Directly
trains ablation methodology - Relevant to the research process needed in
Week 12

### Statistics revision

Revisit: - Mean - Variance - Standard deviation - Correlation -
Covariance - Hypothesis testing - P-values - Confidence intervals

Use Chi-square / ANOVA only if the experiment genuinely requires them.

**Checkpoint** - Reproduce an experiment. - Document discrepancies. -
Explain why your result differs from the paper, if it does.

------------------------------------------------------------------------

# Week 12 --- AI + QKD + 6G

## Final Research Project

### Project 5 --- ML-Based Security Analysis of BB84/QKD

``` text
BB84 Simulator
      ↓
Channel / Noise / Attack Simulation
      ↓
Experimental Dataset
      ↓
Feature Extraction
      ↓
QBER + Other Security Features
      ↓
Classical ML
      ↓
Attack / Anomaly Detection
      ↓
Evaluation
      ↓
Ablation
      ↓
Robustness / Generalization
      ↓
Research Gap
```

### Possible models

Start with classical baselines:

-   Logistic Regression
-   Decision Tree
-   Random Forest
-   SVM
-   XGBoost

Then consider a neural network **only if it adds scientific value**.

### Features may include

-   QBER
-   Channel loss
-   Noise characteristics
-   Sifted key rate
-   Error rate
-   Temporal/statistical features

Avoid trivial label leakage such as always associating one attack with
one obvious noise setting.

### Evaluation

Use appropriate metrics:

-   Precision
-   Recall
-   F1
-   Confusion matrix
-   ROC-AUC where appropriate
-   Training time
-   Inference time

For security/anomaly detection, pay particular attention to **false
negatives and false positives**, not accuracy alone.

### Research questions

Examples:

-   Can ML reliably detect anomalous QKD behavior from simulated BB84
    observations?
-   Which features contribute most to attack detection?
-   Does QBER alone provide enough information?
-   How robust is the model when channel conditions change?
-   Does a more complex model actually outperform classical baselines?

------------------------------------------------------------------------

# 📚 Research Paper Strategy

There is **no artificial paper-count limit**.

Read as many papers as necessary to understand the dependency chain.

## Paper Priority

  Label           Meaning
  --------------- --------------------------------------
  🔴 Deep Read    Full technical understanding
  🧠 Conceptual   Understand the central research idea
  👀 Skim         Know what the work contributes
  💻 Implement    Code the important idea
  🧪 Reproduce    Recreate an experiment
  ⏳ Later        Useful, but not required now

## Core Paper Chain

### Vision

``` text
CNN
 ↓
VGG-style deep CNN
 ↓
Degradation Problem
 ↓
ResNet
```

### NLP / LLM

``` text
Word Embeddings
 ↓
Seq2Seq
 ↓
Attention
 ↓
Transformer
 ↓
BERT / GPT
 ↓
Pretraining
 ↓
Instruction Tuning
 ↓
RLHF / DPO
 ↓
LoRA / QLoRA
 ↓
RAG / Agents
```

### Retrieval / RAG

``` text
TF-IDF / BM25
 ↓
Dense Retrieval
 ↓
DPR
 ↓
REALM
 ↓
RAG
```

### AI + QKD

``` text
BB84
 ↓
QBER
 ↓
ML Anomaly Detection
 ↓
Temporal / Adversarial ML
 ↓
AI + 6G Integration
```

------------------------------------------------------------------------

# 📝 How To Read Every Important Paper

Do **not** automatically read every paper from page 1 to the end.

Use this sequence:

1.  Prerequisites
2.  Title
3.  Abstract
4.  Introduction
5.  Figures / architecture
6.  Conclusion
7.  Research story
8.  Related work
9.  Method
10. Architecture
11. Core equations
12. Algorithm / pseudocode
13. Experimental setup
14. Results
15. Ablations
16. Limitations
17. Implementation
18. Reproduction
19. Critical analysis
20. Research gap
21. Research question

For Tier-1 papers, aim to reach **implementation-level understanding**.

------------------------------------------------------------------------

# 🧮 Krish Naik Mathematics --- Exact Roadmap

The math course is **not meant to be completed end-to-end during the 90
days**.

## 🟢 Study

-   Section 2 --- Introduction To Linear Algebra
-   Section 3 --- Introduction To Functions And Transformation
-   Section 5 --- Eigen Vectors And Eigen Values
-   Section 7 --- Introduction To Statistics
-   Section 8 --- Descriptive Statistics
-   Section 9 --- Introduction To Probability
-   Section 10 --- Probability Distribution Function And Types Of
    Distribution
-   Section 14 --- Differential Calculus
-   Section 15 --- Power Rules And Derivative Rules
-   Section 16 --- Product Rules In Derivative
-   Section 17 --- Chain Rule Of Derivatives
-   Section 18 --- Application Of Linear Algebra, Stats And Differential
    Calculus In Data Science
-   Section 19 --- Application Of Linear Algebra In Dimensionality
    Reduction
-   Section 20 --- Application Of Derivatives In Deep Learning Neural
    Network

## 🟡 Selective / Later

-   Section 4 --- Inverse Functions Or Transformation
-   Section 6 --- Equation Of A Line, Plane, Hyperplane
-   Section 11 --- Inferential Stats And Hypothesis Testing
-   Section 12 --- Chi Square Test With Solved Examples
-   Section 13 --- ANOVA Test With Solved Examples

## ❌ Leave for Later

Do not spend time completing sections simply because they exist.

The objective is to learn the mathematics required to understand:

``` text
ML → PCA → Gradients → Backpropagation → Attention → Research Experiments
```

------------------------------------------------------------------------

# 🛠️ Portfolio Projects

Only five major projects are maintained.

  -----------------------------------------------------------------------
  \#                      Project                 Main Purpose
  ----------------------- ----------------------- -----------------------
  1                       **AI Resume Analyzer**  Full-stack AI
                                                  engineering

  2                       **ResNet + Ablation**   Deep learning +
                                                  research methodology

  3                       **Transformer From      Mathematical +
                          Scratch**               architectural
                                                  understanding

  4                       **AI Research           RAG + LLM engineering
                          Assistant**             

  5                       **AI + QKD Security     Research specialization
                          Study**                 
  -----------------------------------------------------------------------

These should become a coherent GitHub portfolio rather than five
unrelated projects.

------------------------------------------------------------------------

# 🎓 Research / FYP Direction

The final-year project acts as the **research spine** of the roadmap.

### Core direction

**AI-Based Security Analysis of BB84/QKD for Secure 6G Communication**

### Research progression

``` text
Quantum Communication Basics
        ↓
QKD
        ↓
BB84
        ↓
BB84 Simulator
        ↓
Channel / Noise / Attack Models
        ↓
Dataset
        ↓
Classical ML Baselines
        ↓
Advanced ML / DL
        ↓
Ablation
        ↓
Robustness
        ↓
Research Gap
        ↓
Potential New Research Question
```

The AI component should be scientifically justified. **Do not add AI
simply to make the project sound advanced.**

------------------------------------------------------------------------

# 🚫 What NOT To Do During These 90 Days

-   Do not complete every lecture of every course.
-   Do not take multiple ML courses simultaneously.
-   Do not read papers just to increase the paper count.
-   Do not jump into advanced LLM papers without understanding
    Transformers.
-   Do not start with agents before understanding RAG and tool use.
-   Do not pretrain an LLM from scratch.
-   Do not start deep RL unless the research direction requires it.
-   Do not jump to deep learning before establishing classical ML
    baselines.
-   Do not use accuracy as the only research metric.
-   Do not claim "quantum advantage" without evidence.
-   Do not claim a QKD system is secure simply because an ML model
    detects attacks.
-   Do not build many shallow projects.

------------------------------------------------------------------------

# ✅ Day-90 Definition of Done

## Engineering

-   [ ] Python fluency
-   [ ] Git/GitHub workflow
-   [ ] NumPy/Pandas/Matplotlib
-   [ ] FastAPI backend
-   [ ] Authentication + validation
-   [ ] PostgreSQL + SQL
-   [ ] React/Next.js application
-   [ ] LLM API integration
-   [ ] RAG application
-   [ ] Docker
-   [ ] At least two deployed projects

## AI / ML

-   [ ] Classical ML models understood
-   [ ] Evaluation metrics understood
-   [ ] Backpropagation derived and explained
-   [ ] PyTorch training loop implemented
-   [ ] CNN implemented
-   [ ] ResNet implemented
-   [ ] ResNet ablation completed
-   [ ] Transformer implemented from scratch
-   [ ] BERT/GPT concepts understood
-   [ ] One downstream fine-tuning experiment completed
-   [ ] RAG pipeline completed
-   [ ] LoRA/QLoRA experiment completed

## Research

-   [ ] Tier-1 paper notes completed
-   [ ] ResNet paper deeply understood
-   [ ] Transformer paper deeply understood
-   [ ] One formal reproduction completed
-   [ ] Ablation completed
-   [ ] Error analysis completed
-   [ ] At least 3 AI + QKD papers critically evaluated
-   [ ] Research question written
-   [ ] Hypothesis written
-   [ ] AI + QKD experiment completed

## Portfolio

-   [ ] AI Resume Analyzer
-   [ ] ResNet + Ablation
-   [ ] Transformer From Scratch
-   [ ] AI Research Assistant
-   [ ] AI + QKD Security Study

------------------------------------------------------------------------

# 📈 Weekly Operating System

Every week should contain:

### 1. Learn

Understand the required theory.

### 2. Implement

Write the important concepts yourself.

### 3. Build

Apply them to a real project.

### 4. Read

Read only the papers needed for the current dependency chain.

### 5. Experiment

Change something, compare results and analyze why.

### 6. Document

Update GitHub and the research notebook.

------------------------------------------------------------------------

# 📓 Research Notebook Template

For every important paper or experiment:

``` text
## Research Question

## Hypothesis

## Background

## Previous Approach

## Limitation

## Proposed Idea

## Mathematical Formulation

## Architecture

## Algorithm

## Dataset

## Experimental Setup

## Baselines

## Results

## Ablation

## Error Analysis

## Limitations

## Reproducibility

## Research Gap

## Next Experiment
```

------------------------------------------------------------------------

# 🔬 Research Mindset

The roadmap is designed to move through this progression:

``` text
Foundation
   ↓
Understanding
   ↓
Mathematical Understanding
   ↓
Paper Reading
   ↓
Implementation
   ↓
Experimentation
   ↓
Reproduction
   ↓
Critical Analysis
   ↓
Research Gap
   ↓
Hypothesis
   ↓
Original Research
```

The goal is **not** to finish 90 days with a long list of certificates.

The goal is to finish with the ability to say:

> **I understand the mathematics, I can implement the model, I can
> reproduce the experiment, I can evaluate the evidence, and I can
> identify what should be investigated next.**

------------------------------------------------------------------------

# 🚀 After Day 90

Continue with two parallel tracks:

``` text
50% Internship / Job Preparation
        +
50% Research / Master's Preparation
```

### Internship track

-   DSA
-   System/API design
-   Portfolio improvement
-   Applications
-   Technical interviews
-   AI/ML internships
-   GenAI internships
-   ML Engineer internships
-   AI Research internships

### Research track

-   Deeper AI literature
-   AI + QKD
-   Quantum communication
-   AI + cybersecurity
-   AI + 6G
-   Paper reproduction
-   Research proposal
-   Master's applications
-   Professor outreach

------------------------------------------------------------------------

# ⭐ Final Direction

``` text
E&TC Engineering
       ↓
AI / ML Engineering
       ↓
Research Engineering
       ↓
AI + Quantum Computing
       ↓
Quantum Communication / QKD
       ↓
AI + QKD Security
       ↓
AI + 6G Research
```

**Build → Read → Implement → Experiment → Reproduce → Critique →
Research.**

That is the core of this roadmap.

# AIDEN Benchmarks

This repository documents the **benchmarking methodology and relative performance results**
of **AIDEN (MVP 1.0.1)**, the first Latin American Artificial Intelligence developed independently
by **JMC Studio Creativo**.

All benchmarks presented here correspond to **prototype-level evaluations** conducted during
the early validation phase of AIDEN, without external funding and without industrial-scale
infrastructure.

---

## 🔍 Scope and Context

- **Model version:** AIDEN MVP 1.0.1  
- **Development approach:** Self-taught, self-funded  
- **Deployment stage:** Functional prototype  
- **Primary languages:** Spanish (LATAM) / English  
- **Modalities:** Text and Voice  
- **Architecture:** Proprietary (details intentionally undisclosed)

These benchmarks are **not intended to claim state-of-the-art performance**, but to demonstrate
**technical viability, coherence, emotional alignment, and scalability potential**.

---

## 🧠 Models Evaluated

The following AIDEN models were evaluated:

| Model | Parameters (approx.) | Context Window |
|------|----------------------|----------------|
| AIDEN Core | [matches published repo] | [matches published repo] |
| AIDEN Azul Deep | [matches published repo] | [matches published repo] |
| AIDEN API Azul Dark | [matches published repo] | [matches published repo] |

> Parameter counts and context windows are consistent with the values published
> in the official AIDEN GitHub repositories.

---

## 📊 Benchmarks Overview

### 1. Conversational Coherence Test

**Objective:**  
Evaluate conversational fluency, context retention, and logical continuity across multi-turn interactions.

**Methodology:**
- 20 multi-turn conversations (10–25 turns)
- Mixed topics: technical, emotional, advisory
- Context carryover evaluated every 5 turns

**Results (relative):**
- Strong coherence across medium-length conversations
- Context retention stable within defined context window
- Comparable performance to early-stage conversational models
- Particularly strong performance in Spanish (LATAM) natural phrasing

---

### 2. Emotional Alignment Test

**Objective:**  
Measure empathy, emotional appropriateness, and human-like response tone.

**Methodology:**
- Emotionally charged prompts (stress, uncertainty, support-seeking)
- Responses evaluated on:
  - Empathy alignment
  - Tone appropriateness
  - Cultural naturalness

**Results (relative):**
- High emotional alignment for a prototype-stage model
- Responses perceived as warm and culturally authentic
- Notably effective in Latin American Spanish expressions
- Competitive with larger models in emotional tone, despite smaller scale

---

### 3. Latency & Responsiveness

**Objective:**  
Evaluate real-time usability for text and voice interaction.

**Metrics:**
- Time to first token (TTFT)
- Voice response initiation time

**Results (relative):**
- Low-latency responses suitable for live interaction
- Stable performance under prototype infrastructure
- Voice response times within acceptable conversational thresholds
- Clear potential for optimization with dedicated infrastructure

---

### 4. Multilingual Handling (Optional Evaluation)

**Objective:**  
Assess language switching and response quality between Spanish (LATAM) and English.

**Results (relative):**
- Spanish (LATAM): primary strength, high naturalness
- English: functional, clear, and contextually correct
- Smooth switching when language intent is explicit

---

## 🚀 Key Observations

- AIDEN demonstrates **strong conversational and emotional capabilities** at prototype scale.
- Performance achieved **without external funding** or large-scale compute.
- Results suggest **significant upside potential** with investment in training, optimization, and infrastructure.
- Cultural and linguistic authenticity represents a key differentiator.

---

## 🔐 Intellectual Property & Disclaimer

This repository contains **methodological descriptions only**.

- No training data
- No model weights
- No proprietary algorithms
- No implementation details

All intellectual property remains the exclusive property of **JMC Studio Creativo** and its author.

---

## 📌 Note for Investors

These benchmarks represent **early validation signals**, not final performance claims.

Detailed technical evaluations, expanded benchmarks, and live demonstrations
are available upon request during the investment process.

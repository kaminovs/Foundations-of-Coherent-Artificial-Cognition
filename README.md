# Coherent Cognition Framework — Phase I Prototype

This repository contains a structural prototype of a coherence-regulated cognitive architecture. The system implements a Global State, Claim Dependency Graph, Coherence Metrics (C1–C6), and a Coherence Regulator. It demonstrates belief revision, confidence decay under unsupported claims, identity stability, and coherence-driven control dynamics.

---

## 📄 Main Theory

This implementation is based on the theoretical framework described in:

**Foundations of Coherent Artificial Cognition: A Structural-Dynamical Framework, Global State Architecture, and the A-Test Protocol**

arXiv: *(add link when public)*  
DOI: https://doi.org/10.5281/zenodo.18445064

The goal of this repository is to provide a computational demonstration of structural coherence principles proposed in the paper.

---

## 🧠 What This Prototype Demonstrates

This Phase I prototype illustrates:

- Coherence as a control variable rather than a diagnostic metric  
- Structured belief representation via a Claim Dependency Graph  
- Suppression of unsupported high-confidence claims (hallucination-like nodes)  
- Graceful degradation under semantic contradiction  
- Identity stability as an attractor phenomenon  
- Observable coherence dynamics across cognitive ticks  

---

## ⚠️ What This Is NOT

This is a structural toy prototype, not a full AI system.

- No real semantic understanding  
- Contradiction detection is heuristic  
- Evidence modeling is simplified  
- Scale is minimal  

The purpose is to demonstrate architectural and dynamical principles, not task performance.

---

## ▶️ How to Run (Google Colab)

1. Open the notebook in Google Colab  
2. Run all cells  

Expected outputs:

- Coherence metric plots (C1–C6)  
- Total coherence dynamics over time  
- Claim dependency graph visualization  
- Repair loop logs when coherence drops below threshold  

---

## 🔬 Experimental Regimes Demonstrated

| Regime | System Response |
|--------|-----------------|
| Contradiction | Coherence decreases without system collapse |
| No Evidence | Confidence decays via coherence regulation |
| Task Variation | Identity anchors remain stable |

These regimes arise from coherence-driven regulation rather than explicit rule programming.

---

## 🚀 Future Work

- A-Test Lite experimental evaluation  
- Scaling the Claim Graph structure  
- Integration with LLM backends  
- Learning coherence thresholds  
- Empirical studies of coherence regimes  

---

## 📜 License

MIT License

---

This repository represents Phase I of a research program exploring coherence-regulated cognition and structural self-stabilization mechanisms in artificial systems.

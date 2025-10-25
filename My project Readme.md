# 🧠 Circuits for Intelligence  
**Based on MIT OpenCourseWare — RES.9-003: Brains, Minds, and Machines (Summer 2015)**  
Instructors: Gabriel Kreiman, Leyla Isik, Bill Lotter, Joseph Olson  
Course URL: [MIT OCW — Brains, Minds, and Machines](https://ocw.mit.edu/courses/res-9-003-brains-minds-and-machines-summer-course-summer-2015/)  

---

## 📘 Overview  
This repository reproduces and extends two neuroscience-inspired computational projects from **MIT OpenCourseWare’s “Brains, Minds, and Machines” (Summer 2015)** program under the research area **“Circuits for Intelligence.”**  
The goal is to bridge biological neural computation and artificial intelligence models through simulation, decoding, and analysis.  

---

## 🔬 Project 2.1 — *What is there? Representations of Visual Information in Neuronal Responses and Computer Vision Models*  

### Instructors  
Gabriel Kreiman, Leyla Isik, Bill Lotter  

### Description  
Understanding the visual world requires constructing internal representations where behaviorally important variables can be easily "read out."  
The brain achieves this via the **ventral visual stream**, transforming visual input into structured neural response patterns.  
In this project, you will explore how **information can be decoded** from both **neural data** and **computer vision models**, and compare the two using machine learning.  

### Subprojects  

#### 🧩 2.1.1 — Decoding Object Representations  
- Dataset: A set of single-object images `{p1, …, pN}`  
- Data sources:  
  - Behavioral data  
  - Neurophysiological recordings (humans and monkeys)  
  - Computational model outputs (HMAX and/or CNNs)  
- Objective:  
  - Use machine learning classifiers to decode and discriminate objects based on single-trial data.  
  - Compare performance between biological and artificial representations.  

#### 🌀 2.1.2 — Tolerance to Transformations  
- Study **object recognition robustness** under transformations such as:  
  - Scale  
  - Position  
  - Viewpoint  

#### 🧠 2.1.3 — Cross-Domain Comparison  
- Compare results across:  
  - Behavioral experiments  
  - Neurophysiological data  
  - Computational model predictions  

### References  
- Serre, T. et al. (2005). *A theory of object recognition: Computations and circuits in the feedforward path of the ventral stream in primate visual cortex.* MIT CSAIL Memo 2005-036.  
- Liu, H. et al. (2014). *Fast decoding of object information from intracranial field potentials in human visual cortex.* *Neuron, 62(2), 281-290.*  
- Isik, L. et al. (2014). *The dynamics of invariant object recognition in the human visual system.* *Journal of Neurophysiology, 111, 91-102.*  
- Tang, H. et al. (2014). *Spatiotemporal dynamics underlying object completion in human ventral visual cortex.* *Neuron, 83, 736-748.*  

---

## ⚡ Project 2.2 — *The Role of STDP in Neural Networks*  

### Instructors  
Gabriel Kreiman, Joseph Olson  

### Description  
**Spike-Timing Dependent Plasticity (STDP)** is a key biological mechanism driving neural learning and circuit formation.  
It refines the Hebbian learning rule — *“neurons that fire together wire together.”*  
This project investigates, through simulation, how different biologically observed STDP rules shape network connectivity and function.  

### Objectives  
- Implement various STDP learning rules (LTP/LTD).  
- Explore how timing differences between pre- and post-synaptic firing affect synaptic weights.  
- Simulate and analyze how heterogeneous STDP rules produce distinct local network architectures.  
- Relate emergent circuit structures to cognitive functions observed in biological systems.  

### Core Concepts  
- **LTP (Long-Term Potentiation):** Strengthening when pre-synaptic firing precedes post-synaptic.  
- **LTD (Long-Term Depression):** Weakening when firing order is reversed.  
- **Biological Variants:** Region-specific or dendrite-specific STDP patterns.  

### References  
- Markram, H. et al. (1997). *Regulation of synaptic efficacy by coincidence of postsynaptic APs and EPSPs.* *Science.*  
- Abbott, L. F. & Nelson, S. B. (2000). *Synaptic plasticity: Taming the beast.* *Nature Neuroscience Supplement, 3, 1178-1183.*  
- Caporale, N. & Dan, Y. (2008). *Spike timing-dependent plasticity: A Hebbian learning rule.* *Annual Review of Neuroscience, 31, 25-46.*  
- Douglas, R. J. & Martin, K. A. C. (2004). *Neuronal circuits of the neocortex.* *Annual Review of Neuroscience, 27, 419-451.*  
- Burbank, K. & Kreiman, G. (2011). *Temporally reversed STDP is required for learning stable, diverse, weak feedback connections.* COSYNE Conference.  

---

## 🧰 Tools & Technologies  
- **Python 3.10+**, **NumPy**, **PyTorch**, **Matplotlib**, **Brian2**  
- **Machine Learning:** SVM, Logistic Regression, CNNs  
- **Neural Simulation:** STDP protocol implementations, plasticity models  
- **Visualization:** PCA projections, weight evolution plots, and connectivity matrices  

---

## 📊 Expected Results  
- Quantitative comparison between biological and computational representations.  
- Visualization of transformation-tolerant recognition performance.  
- Emergence of structured connectivity patterns from simulated STDP rules.  

---

## 🧠 Learning Outcomes  
- Understand how **biological vision systems** inspire modern **deep learning architectures**.  
- Develop simulations to observe **plasticity-driven learning** in artificial neural circuits.  
- Apply **cross-domain analysis** linking physiology, behavior, and computation.  

---

## 📚 Source & Attribution  
This work is adapted from:  

> **MIT OpenCourseWare**  
> *Brains, Minds and Machines Summer Course, Project Ideas (2015).*  
> Tomaso Poggio & Gabriel Kreiman, Massachusetts Institute of Technology.  
> Available at: [https://ocw.mit.edu/courses/res-9-003-brains-minds-and-machines-summer-course-summer-2015/](https://ocw.mit.edu/courses/res-9-003-brains-minds-and-machines-summer-course-summer-2015/)  
> © Massachusetts Institute of Technology. Used under a **Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.  

For terms of use, visit: [MIT OCW Terms of Use](https://ocw.mit.edu/pages/privacy-and-terms-of-use/)  

**Attribution Required:**  
> “This work is based on materials from MIT OpenCourseWare, *Brains, Minds, and Machines (RES.9-003, Summer 2015)*, licensed under CC BY-NC-SA 4.0.”  

---

## 👨‍💻 Author  
**Your Name**  
GitHub: [@yourusername](https://github.com/yourusername)  
Date: 2025  

---

## ⚖️ License  
This repository and all derivative works are shared under:  
**Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International (CC BY-NC-SA 4.0)**  

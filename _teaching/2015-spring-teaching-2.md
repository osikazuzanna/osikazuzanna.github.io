---
title: "Learning to Watch the Skies: Reinforcement Learning for Space Surveillance"
collection: teaching
type: "Master thesis"
permalink: /teaching/master_thesis
venue: "EEMCS Faculty, TU Delft"
date: 2025-11-01
location: "Delft, Netherlands"
---

Master's thesis project on applying reinforcement learning for detecting space debris for spacecraft safety and sustainable space operations.

# Summary

Since the dawn of the space age, humanity has launched over **23,000 satellites** into orbit (as of September 2025) [1]. These machines form the invisible backbone of modern civilization — powering everything from global communication and navigation to weather forecasting and defense operations.  

But Earth’s orbits are no longer pristine: alongside the functional satellites now drift **millions of debris fragments**, relics of past missions [1]. As orbital density continues to rise, so does the risk of catastrophic chain reactions known as **collisional cascades** — where one collision spawns thousands of new debris pieces, exponentially increasing the likelihood of further impacts [3]. This scenario threatens not only spacecraft safety but also the **long-term sustainability of space operations**. Maintaining safe access to orbit has become a data-driven challenge of planetary scale.  

Enter **Space Situational Awareness (SSA)** — the science of mapping, monitoring, and predicting the dynamics of space objects. SSA relies on networks of ground- and space-based sensors that collect continuous streams of measurements to determine the location, trajectory, and characteristics of every detectable object in orbit. The richer this data, the better our models of the orbital ecosystem — and the smarter our predictions of its evolution.  

However, achieving reliable SSA comes with two key challenges:

### 1. Multi-objective sensing trade-offs
SSA systems must juggle three competing objectives —  
(a) searching for unknown objects,  
(b) tracking known ones, and  
(c) characterizing their properties.  
Prioritizing one inevitably limits resources for the others.

### 2. Resource scarcity
As orbital congestion increases, the demand for surveillance **outpaces the capabilities** of limited sensor networks [4].  

To maintain continuous and effective orbital coverage, **autonomous sensor tasking** is crucial. This involves making intelligent, real-time decisions about which sensors should observe which targets, and when — effectively turning sensor management into a **sequential decision-making problem**.  

This project approaches that challenge using **Reinforcement Learning (RL)**. By modeling sensor tasking as a **Markov Decision Process (MDP)**, RL agents can learn **adaptive policies** that balance multiple SSA objectives simultaneously.  
The goal: to design and evaluate **multi-objective RL algorithms** capable of orchestrating complex sensing operations in a dynamic, high-stakes environment.

---

# Objectives

The student will:

- Translate an existing **Java-based sensor tasking simulator** into **Python**.  
- Integrate it with the **Gym API** [5] for flexible experimentation.  
- Benchmark and compare different **RL algorithms** for solving the underlying MDP, with a focus on **multi-objective optimization**.

---

# Student Profile

This project is ideal for a student who:

- Has programming skills in **Java** and **Python**,  
- Understands the fundamentals of **Reinforcement Learning**, and  
- Is eager to explore **multi-objective optimization** and its applications in **real-world, safety-critical domains** like space systems.  

You’ll gain hands-on experience developing **intelligent agents** that make data-driven decisions in a complex physical environment — essentially applying AI to keep humanity’s access to space **safe and sustainable**.

---

# References

[1] European Space Agency, “esa.int,” June 2024. [URL](https://www.esa.int/Space_Safety/Space_Debris/Space_debris_by_the_numbers).  
[2] De Concini, A., and Toth, J. “The Future of the European Space Sector: How to Leverage Europe's Technological Leadership and Boost Investments for Space Ventures,” *European Investment Bank*, 2019.  
[3] Kessler, D.J., and Cour‐Palais, B. “Collision frequency of artificial satellites: The creation of a debris belt,” *Journal of Geophysical Research: Space Physics*, vol. 83, pp. 2637–2646, 1978.  
[4] Schrogl, K.U., et al. “*Handbook of Space Security: Policies, Applications and Programs*,” 2015.  
[5] Felten, F., Alegre, L. N., Nowé, A., Bazzan, A. L. C., Talbi, E. G., Danoy, G., & da Silva, B. C. (2023). “A toolkit for reliable benchmarking and research in multi-objective reinforcement learning.” *Proceedings of the 37th Conference on Neural Information Processing Systems (NeurIPS 2023)*.

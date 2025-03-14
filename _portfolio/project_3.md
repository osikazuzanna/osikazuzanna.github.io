---
title: "Developing Decision Support Method for Multi-Objective Reinforcement Learning"
excerpt: "We address the challenge of explainability in MORL by focusing on interpreting the solution set to provide insights into policies with diverse
trade-offs. Our aim is to assist decision-makers (DMs) in selecting and
implementing solutions by developing diverse methods to help them explore the solution sets. "
collection: portfolio
---


Multi-objective reinforcement learning (MORL) is used to solve problems involving multiple reward functions, which are not combined into a single reward. Consequently, an MORL agent must make decisions based on the diverse signals provided by these distinct reward functions. Training an MORL agent yields a solution set (collection of policies), where each solution (policy) presents distinct trade-offs among the objectives (expected returns). MORL enhances explainability by enabling fine-grained comparisons of policies in the solution set based on their trade-offs as opposed to having a single policy. However, the solution set is typically large and multi-dimensional, with each policy (e.g., a neural network) represented by its objective values.

We address the challenge of explainability in MORL by focusing on interpreting the solution set to provide insights into policies with diverse trade-offs. Our aim is to assist decision-makers (DMs) in selecting and implementing solutions by analysing the policies not only based on their cumulative returns, but also on their behaviour over time.  

This work requires designing and implementing decision support tools and analysing neural networks policies.

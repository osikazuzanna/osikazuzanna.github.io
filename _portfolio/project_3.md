---
title: "Bi-Objective Clustering of the Solution Set"
excerpt: "We address the challenge of explainability in MORL by focusing on interpreting the solution set to provide insights into policies with diverse
trade-offs. Our aim is to assist decision-makers (DMs) in selecting and
implementing solutions by proposing a clustering method of the solution
set. This approach enables DMs to identify overarching trends and insights in the solution set rather than examining each policy individually.
By considering both policy behavior and objective values, our clustering
method can reveal the relationship between policy behaviors and regions
in the objective space. This automated process simplifies the task for
DMs, who only need to assess a subset of policies, understanding that
the remainder share similar behaviors and objective values."
collection: portfolio
---


Multi-objective reinforcement learning (MORL) is used to solve problems involving multiple reward functions, which are not combined into a single reward. Consequently, an MORL agent must make decisions based on the diverse signals provided by these distinct reward functions. Training an MORL agent yields a solution set (collection of policies), where each solution (policy) presents distinct trade-offs among the objectives (expected returns). MORL enhances explainability by enabling fine-grained comparisons of policies in the solution set based on their trade-offs as opposed to having a single policy. However, the solution set is typically large and multi-dimensional, with each policy (e.g., a neural network) represented by its objective values.



We address the challenge of explainability in MORL by focusing on interpreting the solution set to provide insights into policies with diverse trade-offs. Our aim is to assist decision-makers (DMs) in selecting and implementing solutions by proposing a clustering method of the solution set. This approach enables DMs to identify overarching trends and insights in the solution set rather than examining each policy individually. By considering both policy behavior and objective values, our clustering method can reveal the relationship between policy behaviors and regions in the objective space. This automated process simplifies the task for DMs, who only need to assess a subset of policies, understanding that the remainder share similar behaviors and objective values.



This is work has been submited, expected publication: 2024.
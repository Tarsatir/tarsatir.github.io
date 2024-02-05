---
layout: post
title: "A thought-vomit on models"
date: 2023-07-12 09:56:00-0400
description: an example of a blog post with bibliography
tags: formatting bib
categories: sample-posts
giscus_comments: true
related_posts: false
---

Recent discussions I had often portray the difference between predictive and causal explanations as a fundamental one. Yet, from a practical viewpoint, this I feel this distinction isn't as clear-cut as it might seem.

The essence of any predictive model is a simplified portrayal of reality. This involves using reductions or idealizations to encapsulate the interplay among selected variables. The pivotal choice, though, is in determining which variables to monitor. Given this selection, the divergence between a causal and a predictive model becomes more apparent. Predictive models primarily concentrate on the outputs of the data generation process, judged by their accuracy. In contrast, causal models delve into the architecture of this process. Consequently, the criteria for acceptable data generation differ markedly between these two approaches.

One might argue that causal models typically face stricter constraints, but this largely hinges on the observable variables chosen. Take predicting the outcome of a dice roll, for instance. One could adopt a statistical approach or delve into Newtonian mechanics.

The goal of both methodologies is to extrapolate from known instances of a process to unknown ones. Understanding a system's causal structure enables predictions about the outcomes under altered conditions. Yet, in a static environment, the advantage of knowing the causal framework is minimal. Moreover, even with a grasp of the causal structure, some assumptions about constant environmental factors are inevitable. Thus, the primary distinction lies in the extent to which we can allow changes within the data generation process. For example, consider how much the distribution of a dice roll might vary if the dice is increasingly biased by weight.

Ultimately, it boils down to this: depending on your objective, how many variables can you realistically track (considering the complexity and cost of the model) versus how many can you afford to overlook (taking into account the potential loss in model accuracy)? The more you can overlook, the more you can classify your model as predictive. The more you can track, the more you can classify your model as causal. 
This implies that you can have both making these categories more orthogonal than opposed.
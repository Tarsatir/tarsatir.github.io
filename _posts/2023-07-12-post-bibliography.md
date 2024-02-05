---
layout: post
title: "Are Predictive and Causal Models Practically Different?"
date: 2023-07-12 09:56:00-0400
description: an example of a blog post with bibliography
tags: formatting bib
categories: sample-posts
giscus_comments: true
related_posts: false
---
Thought-Vomit:
The distinction between predictive and causal explanations is often treated as fundamental in various conversations I was in. Predictive models aim to forecast outcomes based on input data, while causal models seek to understand the underlying mechanisms that give rise to those outcomes. However, from a pragmatic standpoint, this distinction becomes blurrier.

At the core of any predictive model lies a simplified representation of reality, using reductions or idealizations, that  attempt to capture the relationships between variables of interest. However the most crucial decision, lies in the the choice which variable to observe. Conditioned on the choice of variables the difference between a causal and a predicitve model can be specified as follows: Predictive models focus more on the output of the data generating processes, and assess them based on their accuracy, while the causal models focus more on the structure of the data generating process itself. The constraints on acceptable data generation processes between these to perspectives are therefor different. 

One could argue that generally speaking, the constraints for causal models are higher. However this heavily depends on the choice of observables. In order to make a prediction on the outcome of casting a die, one could either reason statistically, or start involving some Newtonian mechanics, the utility of which is questionable.


Genereally speaking the purpose of both approaches is to generalize from known instances of a process to some yet unknown instances. Knowing the causal structure of a system offers the ability to predict what will happen under specified changes to the boundary conditions that process. However if the environment does not change, there is little practical advantage to knowing the causal structure. Furthermore even knowing the causal structure will make some assumptions about *some* constant environmental conditions. So the only difference between them seems to be to what extend observables within the data generating process are allowed to change. For example the degree to which the dies distribution changes if it is increasingly bias by weight. 

Its seems more like given your goal how much observables can you afford to track (cost for complexity of model) and how much can you afford to ignore (cost on inaccuracy of model).




---
title: "Learning Influence-Receptivity Network Structure with Guarantee"
date: 2019-04-01
publishDate: 2020-01-27T20:57:22.568191Z
authors: [ming-yu, "Varun Gupta", mladen-kolar]
publication_types: ["1"]
abstract: "Traditional works on community detection from observations of information cascade assume that a single adjacency matrix parametrizes all the observed cascades.  However, in reality the connection structure usually does not stay the same across cascades.  For example, different people have different topics of interest, therefore the connection structure depends on the information/topic content of the cascade.  In this paper we consider the case where we observe a sequence of noisy adjacency matrices triggered by information/events with different topic distributions.  We propose a novel latent model using the intuition that a connection is more likely to exist between two nodes if they are interested in similar topics, which are common with the information/event.  Specifically, we endow each node with two node-topic vectors: an influence vector that measures how influential/authoritative they are on each topic; and a receptivity vector that measures how receptive/susceptible they are to each topic.  We show how these two node-topic structures can be estimated from observed adjacency matrices with theoretical guarantee on estimation error, in cases where the topic distributions of the information/events are known, as well as when they are unknown. Experiments on synthetic and real data demonstrate the effectiveness of our model and superior performance compared to state-of-the-art methods."
featured: false
publication: "*Proceedings of the 22nd International Conference on Artificial Intelligence and Statistics*"
url_pdf: "http://proceedings.mlr.press/v89/yu19c.html"
---

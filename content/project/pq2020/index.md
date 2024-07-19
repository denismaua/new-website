---

title: Predictive Uncertainty Estimators for Sum-Product Networks
summary: Predictive Uncertainty Estimators for Sum-Product Networks
date: "2020-03-01T00:00:00Z"
tags:
- Productivity Scholarhip
- Sum-Product Networks
- Tractable Probabilistic Models
# Optional external URL for project (replaces project detail page).
external_link: ""
---

## Funding Agency

CNPq grant 304012/2019-0 (ended)

## Coordinator

Denis Deratani Mauá

## Participants

- Denis Deratani Mauá
- Julissa G. Villanueva, PhD candidate at IME-USP
- Renato Lui Geh, MSc student at IME-USP
- Decio L. Soares, MSc student at IME-USP
- Jonas Gonçalves, Undergraduate student at IME-USP

## Abstract

  Deep models have recently obtained impressive results in a
  wide range of tasks and domains, from computer vision to
  image and text processing to diagnosis and automated
  reasoning. Sum-product networks are special type of neural
  networks targeted at the representation of
  high-dimensionality probability distributions. Notably, the
  structure of a sum-product network (i.e., its graph) encodes
  a number of probabilistic independence assertions. In
  addition, each node of the network computes a valid
  distribution over its part of the variables. Such
  probabilistic semantics facilitates debugging, allows a wide
  range of queries and data (including missing and noisy data)
  to be handled properly and efficiently, and enables
  efficient structure learning algorithms.

  In many applications, it is desirable to have not only a
  prediction (e.g., the probability of observing a certain
  object, say an image), but a confidence measure about its
  prediction. As sum-product networks are learned from data,
  the probabilities they calculate can be overly confident or
  too sensitive to hyperparameters on regions where data was
  scarce, conflicting or too noisy. In this research project,
  we plan on following two possible approaches to estimating
  the uncertainty of a sum-product network prediction. The
  first approach estimates uncertainty by analyzing the effect
  that small perturbations of the data have on the prediction.
  The second approach considers the variability of predictions
  among different networks (learned from the same data).
  
  This research investigates predictive uncertainty estimators for sum-product
  networks.


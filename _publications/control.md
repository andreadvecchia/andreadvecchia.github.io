---
title: "Error Propagation in Dynamic Programming: From Stochastic Control to Option Pricing"
authors: "A. Della Vecchia, D. Filipović"
venue: "arXiv, under review at ICLR26"
date: 2025-09-18
year: 2025
paperurl: "https://arxiv.org/abs/2509.20239"
pdf: "/files/papers/control.pdf"
selected: true

excerpt: >-
  **Abstract:** This paper investigates theoretical and methodological foundations for stochastic
  optimal control (SOC) in discrete time. We start formulating the control problem in a general
  dynamic programming framework, introducing the mathematical structure needed for a detailed
  convergence analysis. The associated value function is estimated through a sequence of
  approximations combining nonparametric regression methods and Monte Carlo subsampling. The
  regression step is performed within reproducing kernel Hilbert spaces (RKHSs), exploiting the
  classical KRR algorithm, while Monte Carlo sampling methods are introduced to estimate the
  continuation value. To assess the accuracy of our value function estimator, we propose a natural
  error decomposition and rigorously control the resulting error terms at each time step. We then
  analyze how this error propagates backward in time — from maturity to the initial stage — a
  relatively underexplored aspect of the SOC literature. Finally, we illustrate how our analysis
  naturally applies to a key financial application: the pricing of American options.
---

---
title: "The Nyström Method for Convex Loss Functions"
authors: "A. Della Vecchia, E. De Vito, J. Mourtada, L. Rosasco"
venue: "Journal of Machine Learning Research (JMLR)"
date: 2024-11-30
year: 2024
paperurl: "https://scholar.google.it/citations?view_op=view_citation&hl=en&user=aaeUheEAAAAJ&citation_for_view=aaeUheEAAAAJ:UeHWp8X0CEIC"   # replace with actual JMLR page
pdf: "/files/papers/DellaVecchiaNystrom.pdf"
selected: true
excerpt: >-
  **Abstract:** We investigate an extension of classical empirical risk minimization, where the
  hypothesis space consists of a random subspace within a given Hilbert space. Specifically, we
  examine the Nyström method where the subspaces are defined by a random subset of the data. This
  approach recovers Nyström approximations used in kernel methods as a specific case. Using random
  subspaces naturally leads to computational advantages, but a key question is whether it
  compromises the learning accuracy. Recently, the tradeoffs between statistics and computation
  have been explored for the square loss and self-concordant losses, such as the logistic loss. In
  this paper, we extend these analyses to general convex Lipschitz losses, which may lack
  smoothness, such as the hinge loss used in support vector machines. Our main results show the
  existence of various scenarios where computational gains can be achieved without sacrificing
  learning performance. When specialized to smooth loss functions, our analysis recovers most
  previous results. Moreover, it allows to consider classification problems and translate the
  surrogate risk bounds into classification error bounds. Indeed, this gives the opportunity to
  compare the effect of Nyström approximations when combined with different loss functions such as
  the hinge or the square loss.
---

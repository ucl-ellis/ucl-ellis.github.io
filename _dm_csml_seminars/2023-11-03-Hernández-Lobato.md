---
layout: dm_csml_seminar_event
event_start_time: 2023-11-03 12:00
event_end_time: 2023-11-03 13:00
img: ellis-logo.png
alt: image-alt
join_link: https://ucl.zoom.us/j/97245943682
location: Function Space, UCL Centre for Artificial Intelligence, 1st Floor, 90 High Holborn, London WC1V 6BH
speaker: José Miguel Hernández Lobato
affiliation: University of Cambridge
title: "Normalizing Flows for Molecular Modeling"
summary: "Normalizing flows are tractable density models that can approximate complicated target distributions, e.g. Boltzmann distributions of physical systems. However, current methods for training flows either suffer from mode-seeking behavior, use samples from the target generated beforehand by expensive MCMC methods, or use stochastic losses that have high variance. To avoid these problems, we augment flows with annealed importance sampling (AIS) and minimize the mass-covering α-divergence with α=2, which minimizes importance weight variance. Our method, Flow AIS Bootstrap (FAB), uses AIS to generate samples in regions where the flow is a poor approximation of the target, facilitating the discovery of new modes. We apply FAB to multimodal targets and show that we can approximate them very accurately where previous methods fail. To the best of our knowledge, we are the first to learn the Boltzmann distribution of the alanine dipeptide molecule using only the unnormalized target density, without access to samples generated via Molecular Dynamics (MD) simulations: FAB produces better results than training via maximum likelihood on MD samples while using 100 times fewer target evaluations. After reweighting the samples, we obtain unbiased histograms of dihedral angles that are almost identical to the ground truth."
bio: "José Miguel is Professor of Machine Learning at the Department of Engineering in the University of Cambridge, UK. Before joining Cambridge as faculty, he was a postdoctoral fellow in the Harvard Intelligent Probabilistic Systems group at Harvard University, working with Ryan Adams, and before this, also a postdoctoral research associate in the Machine Learning Group at the University of Cambridge (UK), working with Zoubin Ghahramani. Jose Miguel completed his Ph.D. and M.Phil. in Computer Science at the Computer Science Department from Universidad Autónoma de Madrid (Spain), where he also obtained a B.Sc. in Computer Science from this institution, with a special prize to the best academic record on graduation. José Miguel's research focuses on probabilistic machine learning, with a particular interest in deep generative models, Bayesian optimization, approximate inference, Bayesian neural networks and applications of these methods to real-world problems such as the problem of automatic molecular design."
---

---
title: "Beyond Grids: Neural Networks in Fluid Dynamics"
collection: publications
category: manuscripts
permalink: /publication/masters
excerpt: 'Master's Thesis'
date: 2024-04-15
venue: 'Journal 2'
# slidesurl: ''
paperurl: 'https://toobarahimnia.github.io/PersonalHub/files/Thesis_Paper.pdf'
citation: 'Rahimnia, Tooba (2024)'
---

Fluid mechanics simulation is a crucial domain in real-world simulation, addressing a wide range of scenarios, including pouring liquids and vast ocean views, often becoming an indispensable tool for directors and artists. The Eulerian methodology stands as a significant approach in fluid simulation, segmenting the simulation space into grid cells to monitor
fluid properties like velocity, pressure, and temperature. To ensure fluid incompressibility, the Eulerian technique engages in solving the Poisson equation, generating a sparse, symmetric, and positive definite linear system during projection, which can be solved iteratively; however, the iterative method, reliant on conventional numerical procedures, proves computationally intensive, particularly compared to other stages of the simulation.

In enhancing simulation speed, one avenue involves employing deep learning techniques to handle pressure projection, circumventing the need for analytical solutions via linear equations. In our present endeavor, we introduce a machine learning solution, distinct from traditional numerical approaches, training our model to comprehend fluid system behavior, thereby expediting the determination of fluid pressure values.
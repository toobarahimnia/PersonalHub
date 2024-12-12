---
title: "Beyond Grids: Neural Networks in Fluid Dynamics"
collection: publications
category: preprint # must include feature
permalink: /publication/deeplearning-for-fluid-simulation
excerpt: 'Review paper'
date: 2024-04-15
# venue: 'Journal 1'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://toobarahimnia.github.io/PersonalHub/files/Thesis_Paper.pdf'
# citation: 'Rahimnia, Tooba. (2024). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Fluid mechanics simulation is a crucial domain in real-world simulation, addressing a wide range of scenarios, including pouring liquids and vast ocean views, often becoming an indispensable tool for directors and artists. The Eulerian methodology stands as a significant approach in fluid simulation, segmenting the simulation space into grid cells to monitor fluid properties like velocity, pressure, and temperature. To ensure fluid incompressibility, the Eulerian technique engages in solving the Poisson equation, generating a sparse, symmetric, and positive definite linear system during projection, which can be solved iteratively; however, the iterative method, reliant on conventional numerical procedures, proves computationally intensive, particularly compared to other stages of the simulation. In enhancing simulation speed, one avenue involves employing deep learning techniques to handle pressure projection, circumventing the need for analytical solutions via linear equations. In our present endeavor, we introduce a machine
learning solution, distinct from traditional numerical approaches, training our model to comprehend fluid system behavior, thereby expediting the determination of fluid pressure values.
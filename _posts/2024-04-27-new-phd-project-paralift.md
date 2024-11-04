---
layout: post
title: "New PhD Project: ParaLift"
date: 2024-04-27
categories: [PhD Projects]
---

**Project Title:** ParaLift: A Parallel framework for lifted training of neural networks

**Supervisor:** Professor Martin Benning

**Project summary**

**Existing background work:**
- The project is based on innovative advancements in distributed neural network training.
- The framework proposed in [1] replaces the traditional neural network consistency constraint with quadratic penalisations.
- These penalisations remove the need for back-propagation and enable distributed optimisation algorithms.
- The framework requires the introduction of auxiliary variables to lift the parameter search space into a higher dimensional space.
- The framework has been augmented by constraining the auxiliary variables to convex sets [2] and replacing the quadratic penalties with more bespoke penalty functions [3, 4].
- In [4], the penalty functions have been replaced with tailored Bregman distance functions that, in combination with suitable optimisation algorithms, bypass the requirement of differentiating activation functions.

**Main objectives of the project:**
- The project aims to tap the full potential of the distributed lifted Bregman framework in distributed neural network training.
- The main objective is to develop a user-friendly software toolbox for implementing deep neural network training for large-scale datasets using the lifted Bregman framework.
- The toolbox will be designed to be as straightforward to use as existing toolboxes like PyTorch or JAX.
- The toolbox will have the capacity for massive parallelisation, enabling the distribution of parameter updates across various workers for individual layers, while concurrently avoiding the need for differentiating non-differentiable operations.
- The project will focus on developing a comprehensive software toolbox for implementing the lifted Bregman framework.
- The toolbox will be designed to be efficient and effective, with a focus on ease of use and high performance.
- The project will also focus on advancing medical imaging techniques, such as magnetic resonance imaging (MRI) and positron emission tomography (PET), for large-scale datasets.
- The project will also focus on enhancing variational regularisations, with a focus on the training of variational regularisations with optimal source condition elements as a novel use-case.
- The project will also focus on inverting deep neural networks, particularly in contexts involving large-scale datasets.

**Details of Software/Data Deliverables:**
- The project aims to promote the use of the lifted Bregman framework.
- The project involves the development of a Python library or Julia package for distributed optimization of lifted Bregman objectives.
- The library or package will make it easy to set up complex use cases, such as training deep transformer-based neural networks.
- The library or package will support popular training techniques, such as batch normalization.
- The library or package will feature a variety of distributed, non-smooth optimization routines, including distributed proximal gradient descent, proximal incremental aggregated gradient, and proximal stochastic averaged gradient.
- The library or package will utilize distributed hardware architectures with little to no user input to enable both data and layer parallelism.
- This project aims to elevate the lifted Bregman framework from its current state of limited use-cases to widespread use in the research community.
- The project will develop either a Python library or a Julia package, depending on the candidate’s programming expertise and skills.
- The tool will facilitate distributed optimisation of lifted Bregman objectives.
- The tool will make the setup of complex scenarios as effortless as using established automatic differentiation and deep learning frameworks like PyTorch and JAX.
- The tool will focus on the efficient employment of distributed training routines specific to the lifted Bregman framework.
- The tool will not require users to engage with the intricate details of manual implementation.
- Key features of the library or package include:
- Versatile Architecture and Optimisation Setup: Enabling users to effortlessly configure a broad spectrum of deep neural network architectures, loss functions, constraints, and optimisation problems.
- Support for Established Training Techniques: Incorporating widely used training methodologies, including batch normalisation, to ensure compatibility with current best practices.
- Advanced Distributed Optimisation Routines: Offering an array of sophisticated distributed, non-smooth optimisation techniques, such as distributed proximal gradient descent, proximal incremental aggregated gradient, and proximal stochastic averaged gradient.
- Optimised Utilisation of Distributed Hardware: Designed to leverage distributed hardware architectures with minimal user intervention, thereby facilitating both data and layer parallelism for enhanced computational efficiency.

**Eligibility:**
Applicants should have a strong background in applied mathematics, computer science, or related fields, with experience in inverse problems, optimisation, and machine learning.

**Application Details:**
Interested candidates should sign up for the [CCMI Online Open Day](https://ccmi-cdt.org/events/posts/open_day.html). For more information on the project, please visit the [ParaLift Project Page](https://ccmi-cdt.org/phd_projects/entries/Benning_Paralift.html).

**References**
- [1] Miguel Carreira-Perpinan, and Weiran Wang. “Distributed optimization of deeply nested systems.” PMLR, 2014. 
- [2] Armin Askari, et al. “Lifted neural networks.” arXiv preprint arXiv:1805.01532 (2018). 
- [3] Fangda Gu, Armin Askari, and Laurent El Ghaoui. “Fenchel lifted networks: A Lagrange relaxation of neural network training.” PMLR, 2020.
- [4] Xiaoyu Wang, and Martin Benning. “Lifted Bregman training of neural networks.” Journal of Machine Learning Research 24, no. 232 (2023): 1-51.
- [5] Xiaoyu Wang, and Martin Benning. “A lifted Bregman formulation for the inversion of deep neural networks.” Frontiers in Applied Mathematics and Statistics 9 (2023): 1176850.
- [6] Martin Benning, Tatiana A. Bubba, Luca Ratti, and Danilo Riccio. “Trust your source: quantifying source condition elements for variational regularisation methods.” arXiv preprint arXiv:2303.00696 (2023).

**Contact Information:**
- **Email:** [martin.benning@ucl.ac.uk](mailto:martin.benning@ucl.ac.uk)
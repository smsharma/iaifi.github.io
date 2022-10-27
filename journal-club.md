---
layout: article
title: Journal Club
---

* [Upcoming Journal Clubs](#upcoming-journal-clubs)
* [Fall 2022 Journal Clubs](#fall-2022-journal-clubs)
* [Spring 2022 Journal Clubs](#spring-2022-journal-clubs)
* [Fall 2021 Journal Clubs](#fall-2021-journal-clubs)
* [Spring 2021 Journal Clubs](#spring-2021-journal-clubs)
* [Fall 2020 Journal Clubs](#fall-2020-journal-clubs)


## Upcoming Journal Clubs
The IAIFI Journal Club is only open to IAIFI members and affiliates. 

[Sign up to lead a discussion!](https://forms.gle/zfpT4QQdXg8tu6VB7)

* **Sona Najafi, Researcher, IBM**
  * **October 25, 2022, 11:00am-12:00pm**
  * *Quantum machine learning from algorithms to hardware*
  * Abstract: The rapid progress of technology over the past few decades has led to the emergence of two powerful computational paradigms known as quantum computing and machine learning. While machine learning tries to learn the solutions from data, quantum computing harnesses the quantum laws for more powerful computation compared to classical computers. In this talk, I will discuss three domains of quantum machine learning, each harnessing a particular aspect of quantum computers and targeting specific problems. The first domain scrutinizes the power of quantum computers to work with high-dimensional data and speed-up algebra, but raises the caveat of input/output due to the quantum measurement rules. The second domain circumvents this problem by using a hybrid architecture, performing optimization on a classical computer while evaluating parameterized states on a quantum circuit, chosen based on a particular issue. Finally, the third domain is inspired by brain-like computation and uses a given quantum system's natural interaction and unitary dynamic as a source for learning


## Fall 2022 Journal Clubs

* **Kim Nicoli, Grad Student, Technical University of Berlin** 
  * **October 18, 2022, 11:00am-12:00pm**
  * Deep Learning approaches in lattice quantum field theory: recent advances and future challenges**
  * Abstract: Normalizing flows are deep generative models that leverage the change of variable formula to map simple base densities to arbitrary complex target distributions. Recent works have shown the potential of such methods in learning normalized Boltzmann densities in many fields ranging from condensed matter physics to molecular science to lattice field theory. Though sampling from a flow-based density comes with many advantages over standard MCMC sampling, it is known that these methods still suffer from several limitations. In my talk, I will start to give an overview on how to deploy deep generative models to learn Boltzmann densities in the context of a phi^4 lattice field theory. Specifically, I’ll focus on how these methods open up the possibility to estimate thermodynamic observables, i.e., physical observables which depend on the partition function and hence are not straightforward to estimate using standard MCMC methods. In the second part of my talk, I will present two ideas that have been proposed to mitigate the well-known problem of mode-collapse which often occurs when normalizing flows are trained to learn a multimodal target density.  More specifically I’ll talk about a novel “mode-dropping estimator” and path gradients. In the last part of my talk, I’ll present a new idea which aims at using flow-based methods to mitigate the sign problem.

* **Adriana Dropulic, Grad Student, Princeton**
  * **October 4, 2022, 11:00am-12:00pm**
  * *Machine Learning the 6th Dimension: Stellar Radial Velocities from 5D Phase-Space Correlations*
  * Abstract: The Gaia satellite will observe the positions and velocities of over a billion Milky Way stars. In the early data releases, most observed stars do not have complete 6D phase-space information. We demonstrate the ability to infer the missing line-of-sight velocities until more spectroscopic observations become available. We utilize a novel neural network architecture that, after being trained on a subset of data with complete phase-space information, takes in a star's 5D astrometry (angular coordinates, proper motions, and parallax) and outputs a predicted line-of-sight velocity with an associated uncertainty. Working with a mock Gaia catalog, we show that the network can successfully recover the distributions and correlations of each velocity component for stars that fall within ~5 kpc of the Sun. We also demonstrate that the network can accurately reconstruct the velocity distribution of a kinematic substructure in the stellar halo that is spatially uniform, even when it comprises a small fraction of the total star count. We apply the neural network to real Gaia data and discuss how the inferred information augments our understanding of the Milky Way's formation history. 

* **Iris Cong, Grad Student, Harvard**
  * **September 27, 2022, 11:00am-12:00pm**
  * *Quantum Convolutional Neural Networks*
  * Abstract: Convolutional neural networks (CNNs) have recently proven successful for many complex applications ranging from image recognition to precision medicine. In the first part of my talk, motivated by recent advances in realizing quantum information processors, I introduce and analyze a quantum circuit-based algorithm inspired by CNNs. Our quantum convolutional neural network (QCNN) uses only O(log(N)) variational parameters for input sizes of N qubits, allowing for its efficient training and implementation on realistic, near-term quantum devices. To explicitly illustrate its capabilities, I show that QCNN can accurately recognize quantum states associated with a one-dimensional symmetry-protected topological phase, with performance surpassing existing approaches. I further demonstrate that QCNN can be used to devise a quantum error correction (QEC) scheme optimized for a given, unknown error model that substantially outperforms known quantum codes of comparable complexity. The design of such error correction codes is particularly important for near-term experiments, whose error models may be different from those addressed by general-purpose QEC schemes. 
If time permits, I will also present our latest results on generalizing the QCNN framework to more accurately and efficiently identify two-dimensional topological phases of matter.

* **Miles Cranmer, Grad Student, Princeton**
  * **September 20, 2022, 11:00am–12:00pm**
  * *Interpretable Machine Learning for Physics*
  * Abstract: Would Kepler have discovered his laws if machine learning had been around in 1609? Or would he have been satisfied with the accuracy of some black box regression model, leaving Newton without the inspiration to find the law of gravitation? In this talk I will present a review of some industry-oriented machine learning algorithms, and discuss a major issue facing their use in the natural sciences: a lack of interpretability. I will then outline several approaches I have created with collaborators to help address these problems, based largely on a mix of structured deep learning and symbolic methods. This will include an introduction to the PySR software (https://astroautomata.com/PySR), a Python/Julia package for high-performance symbolic regression. I will conclude by demonstrating applications of such techniques and how we may gain new insights from such results.
  * Resources: [https://arxiv.org/abs/2207.12409](https://arxiv.org/abs/2207.12409); [https://arxiv.org/abs/2202.02306](https://arxiv.org/abs/2202.02306); [https://arxiv.org/abs/2006.11287](https://arxiv.org/abs/2006.11287)

* **Anindita Maiti, Grad Student, Northeastern**
  * **September 13, 2022, 11:00am-12:00pm**
  * *A Study of Neural Network Field Theories*
  * Abstract: I will present a systematic exploration of field theories arising in Neural Networks, using a dual framework given by Neural Network parameters. The infinite width limit of NN architectures, combined with i.i.d. parameters, lead to Gaussian Processes in Neural Networks by the Central Limit Theorem (CLT), corresponding to generalized free field theories. Small and large violations of the CLT respectively lead to weakly coupled and non-perturbative non-Lagrangian field theories in Neural Networks. Non-Gaussianity, locality (via cluster decomposition), and symmetries of Neural Network field theories are examined via NN parameter space, without necessitating the knowledge of field theoretic actions. Thus, Neural Network field theories, in conjunction to this duality via parameters, may have potential implications for Physics and Machine Learning both.
  * Resources: [https://arxiv.org/abs/2106.00694](https://arxiv.org/abs/2106.00694)

## Spring 2022 Journal Clubs
* **Jessie Micallef, PhD Student, Michigan State University & Incoming IAIFI Fellow**
  * **March 10, 2022, 11:00am-12:00pm**
  * *"Adapting CNNs to Reconstruct Sparse, GeV-Scale IceCube Neutrino Events"*
  * Resources:
    * [Reconstructing Neutrino Energy using CNNs for GeV Scale IceCube Events](https://pos.sissa.it/395/1053/pdf)
    * [Direction Reconstruction using a CNN for GeV-Scale Neutrinos in IceCube](https://pos.sissa.it/395/1054/pdf)
* **Denis Boyda, Postdoctoral Appointee, Argonne National Laboratory & Incoming IAIFI Fellow**
  * **RESCHEDULED: March 17, 2022, 11:00am-12:00pm**
  * *"Overview of some popular Machine Learning frameworks for data parallelism"*
  * Resources: 
    * [S. Li et. al. PyTorch Distributed: Experiences on Accelerating Data Parallel Training. 2020.](https://arxiv.org/abs/2006.15704) arXiv:2006.15704
    * [A. Sergeev and Mike Del Balso. Horovod: fast and easy distributed deep learning in TensorFlow. 2018.](https://arxiv.org/abs/1802.05799) arXiv:1802.05799
    * [S. Rajbhandari et.al. ZeRO: Memory Optimizations Toward Training Trillion Parameter Models. 2020.](https://arxiv.org/abs/1910.02054) arXiv:1910.02054​
* **Yin Lin, Postdoctoral Researcher, MIT**
  * **April 7, 2022, 11:00am-12:00pm**
  * *"Accelerating Dirac equation solves in lattice QFT with neural-network preconditioners"*
  * Resources:
    * [An Introduction to the Conjugate Gradient Method Without the Agonizing Pain](https://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf)
    * [Iterative Methods for Sparse Linear Systems](https://www-users.cse.umn.edu/~saad/IterMethBook_2ndEd.pdf)
    * [Deep Learning of Preconditioners for Conjugate Gradient Solvers in Urban Water Related Problems](https://arxiv.org/abs/1906.06925)
    * [Learning to Optimize Non-Rigid Tracking](https://arxiv.org/abs/2003.12230)
* **Anatoly Dymarsky, Associate Professor, University of Kentucky**
  * **April 14, 2022, 11:00am-12:00pm**
  * *Tensor network to learn the wave function of data*
  * Abstract: We use tensor network-based architecture to train a network which simultaneously accomplishes two tasks: image classification and image sampling. We argue that simultaneous performance of these tasks means our network has successfully learned the whole "manifold of data" (using the terminology from the literature) - namely all possible images of a particular kind. We use a black and white version of MNIST, hence our network learns all possible images depicting a particular digit. We access global properties of the "manifold of data" by calculating its size. Thus, we found there are 2^72 possible images of digit 3. We explain this number is robust and largely independent of the details of training process etc. 
  * Resources: 
    * [Tensor network to learn the wavefunction of data](https://arxiv.org/abs/2111.08014)
* **Carolina Cuesta, PhD Student, Durham University & Incoming IAIFI Fellow**
  * **April 21, 2022, 11:00am-12:00pm**
  * *Equivariant normalizing flows and their application to cosmology*
  * Resources:
    * [https://arxiv.org/abs/2202.05282](https://arxiv.org/abs/2202.05282)
    * [https://arxiv.org/abs/2105.09016](https://arxiv.org/abs/2105.09016)
* **Benjamin Fuks, Professor, Sorbonne University**
  * **April 28, 2022, 11:00am-12:00pm**
  * *Precision simulations for new physics*
  * Resources:
    * [https://arxiv.org/abs/1907.04898](Precision simulations for new physics (JHEP 12 (2019) 008))
    * [https://arxiv.org/abs/1901.09937](How precision allows us to design new variables to look for signals (Phys. Rev. D 100, 074010 (2019))
    * [https://arxiv.org/abs/2109.11815](Trying to do better with boosted decision trees on the basis of tree-level simulations  (JHEP 04 (2022) 015))
* **Dylan Hadfield, Assistant Professor, MIT** 
  * **May 5, 2022, 11:00am-12:00pm**
  * *Overoptimization, Incompleteness, and Goodhart's Law*
  * Resources:
    * [https://arxiv.org/abs/1611.08219](https://arxiv.org/abs/1611.08219)
    * [https://arxiv.org/abs/1705.09990](https://arxiv.org/abs/1705.09990)
    * [https://arxiv.org/abs/2102.03896](https://arxiv.org/abs/2102.03896)
* **Mark Hamilton, Graduate Student, MIT**
  * **May 12, 2022, 11:00am-12:00pm**
  * *Unsupervised Semantic Segmentation by Distilling Feature Correspondences*
  * Resources:
    * [Website](https://mhamilton.net/stego.html)
    * [Paper](https://arxiv.org/abs/2203.08414)
    * [Code](https://aka.ms/stego-code)
* **Manami Kanemura, Undergraduate Student, Northeastern University (completed co-op with Bryan Ostdiek)**
  * **May 26, 2022, 11:00am-12:00pm**
  * *Using Soft-Introspection to improve anomaly detection at LHC*
  * Resources:
    * [Soft-IntroVAE: Analyzing and Improving the Introspective Variational Autoencoder](https://arxiv.org/abs/2012.13253)
    * [Challenges for Unsupervised Anomaly Detection in Particle Physics](https://arxiv.org/abs/2110.06948)

## Fall 2021 Journal Clubs
  * **Michael Douglas**
    * **Thursday, September 23, 11:00am-12:00pm**
    * *"Solving Combinatorial Problems using AI/ML"*
    * Abstract/Resources: [Bright et al 1907.04408](https://arxiv.org/abs/1907.04408); [Heule et al 1905.10192](https://arxiv.org/abs/1905.10192); [Halverson et al 1903.11616](https://arxiv.org/abs/1903.11616); [McAleer et al 1805.07470](https://arxiv.org/abs/1805.07470); [Gukov et al 2010.16263](https://arxiv.org/abs/2010.16263); General sources on reinforcement learning: [Sutton and Bardo](https://www.davidsilver.uk/teaching), [The MathCheck SAT+CAS system](https://uwaterloo.ca/mathcheck)

  * **Ziming Liu**
    * **Thursday, October 7, 11:00am-12:00pm**
    * *"Dynamics in Modern Deep Learning Models"*
    * Abstract/Resources: [Transient Chaos in BERT](https://arxiv.org/pdf/2106.03181.pdf); [Memory and attention in deep learning](https://arxiv.org/pdf/2107.01390.pdf); [The Brownian motion in the transformer model](https://arxiv.org/pdf/2107.05264.pdf)

  * **Ge Yang**
    * **Thursday, October 21, 11:00am-12:00pm**
    * *"Learning and Generalization: Revisiting Neural Representations"*
    * Abstract/Resources: Understanding how deep neural networks learn and generalize has been a central pursuit of intelligence research. This is because we want to build agents that can learn quickly from a small amount of data, that also generalizes to a wider set of scenarios. In this talk, we take a systems approach by identifying key bottleneck components that limits learning and generalization. We will present two key results — overcoming the simplicity bias of neural value approximation via random Fourier features and going beyond the training distribution via invariance through inference.

  * **Eric Michaud, PhD Student, MIT**
    * **Thursday, November 18, 11:00am-12:00pm**
    * *"Curious Properties of Neural Networks"*
    * Abstract/Resources: In this informal talk/discussion, I will highlight some facts about neural networks which I find to be particularly fun and surprising. Possible topics could include the Lottery Ticket Hypothesis (https://arxiv.org/abs/1803.03635), Double Descent (https://arxiv.org/abs/1912.02292), and “grokking” (https://mathai-iclr.github.io/papers/papers/MATHAI_29_paper.pdf). There will be time for discussion and for attendees to bring up their own favorite surprising facts about deep learning.

  * **Murphy Niu, Google Quantum AI**
    * **Thursday, December 3, 11:00am-12:00pm**
    * *"Entangling Quantum Generative Adversarial Networks using Tensorflow Quantum"*
    * Abstract/Resources: [https://arxiv.org/pdf/2105.00080.pdf](https://arxiv.org/pdf/2105.00080.pdf); [https://arxiv.org/pdf/2003.02989.pdf%20-%20Page%202.pdf](https://arxiv.org/pdf/2003.02989.pdf%20-%20Page%202.pdf)

## Spring 2021 Journal Clubs
  * **Anindita Maiti**
    * **Wednesday, February 17**
    * *"Neural Networks and Quantum Field Theory"*
    * Abstract/Resources: [https://arxiv.org/abs/2008.08601](https://arxiv.org/abs/2008.08601)

  * **Jacob Zavatone-Veth**
    * **Tuesday, March 2**
    * *"Non-Gaussian Processes and Neural Networks at Finite Widths"*
    * Abstract/Resources: [https://arxiv.org/abs/1910.00019](https://arxiv.org/abs/1910.00019)

  * **Di Luo**
    * **Tuesday, April 6**
    * *"Simulating Quantum Many-Body Physics with Neural Network Representation"*
    * Abstract/Resources: [https://arxiv.org/abs/1807.10770](https://arxiv.org/abs/1807.10770); [https://arxiv.org/pdf/1912.11052.pdf](https://arxiv.org/pdf/1912.11052.pdf); [https://arxiv.org/abs/2012.05232](https://arxiv.org/abs/2012.05232)

  * **Anna Golubeva**
    * **Tuesday, April 27**
    * *"Are Wider Nets Better Given the Same Number of Parameters?"*
    * Abstract/Resources: [https://arxiv.org/abs/2010.14495](https://arxiv.org/abs/2010.14495)

  * **Siddharth Mishra-Sharma**
    * **Tuesday, May 11**
    * *Simulation-Based Inference Focusing on Astrophysical Applications*
    * Abstract/Resources: [https://arxiv.org/abs/1911.01429](https://arxiv.org/abs/1911.01429); [https://arxiv.org/abs/1909.02005](https://arxiv.org/abs/1909.02005)

## Fall 2020 Journal Clubs
  * **Bhairav Mehta**
    * **Tuesday, October 20**
    * *"Learning Invariances"*
    * Abstract/Resources: [https://arxiv.org/abs/2009.00329](https://arxiv.org/abs/2009.00329)

  * **Andrew Tan**
    * **Wednesday, November 4**
    * *"Estimating Mutual Information"*
    * Abstract/Resources: [https://arxiv.org/abs/1905.06922](https://arxiv.org/abs/1905.06922)

  * **Ziming Liu**
    * **Wednesday, November 18**
    * *"Scaling Laws of Learning"*
    * Abstract/Resources: [https://arxiv.org/abs/2010.14701](https://arxiv.org/abs/2010.14701); [https://arxiv.org/abs/2004.10802](https://arxiv.org/abs/2004.10802); [https://arxiv.org/abs/2001.08361](https://arxiv.org/abs/2001.08361)

   * **Dan Roberts**
     * **Wednesday, December 2**
     * *"Effective Theory of Deep Learning"*

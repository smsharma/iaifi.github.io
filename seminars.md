---
layout: article
title: Internal Discussion Seminars
---

* [Upcoming Internal Discussion Seminars](#upcoming-internal-discussion-seminars)
* [Fall 2022 Seminars](#fall-2022-seminars)
* [Spring 2022 Seminars](#spring-2022-seminars)


## Upcoming Internal Discussion Seminars
Unless otherwise noted, discussion seminars will be held in person (MIT Kolker Room, Building 26, Room 414) and over [Zoom](https://www.google.com/url?q=https://mit.zoom.us/j/92183041364?pwd%3DN3pMelhpV3JUOVkzcjl1cTR4UVd6Zz09&sa=D&source=calendar&usd=2&usg=AOvVaw0SMrjNzSOUddjpaY3nOnCC).

[Access recordings of past seminars (for IAIFI members only)](https://docs.google.com/document/d/1ZGLuC_-eqMwyeeJNbwR5YhEg_S18E8akbDE9m39oYsY/edit?usp=sharing)

* **Abiy Tasissa, Professor, Tufts**
    * **Friday, October 28, 2022 2:00-3:00pm** 
    * *Geometric sparse coding with learned archetypes: Theory and applications*
    * Given a set of data points, archetypal analysis is a method which represents each data as a convex combination of exemplars called "archetypes". The benefit of this analysis is the interpretable archetypes along with information that can be gleaned from the representation coefficients. We propose a method that combines manifold learning and archetypal analysis by positing that each data point can be written as a convex combination of nearby landmarks. To encourage representing a data point via closeby landmarks, we propose a locality regularizer. We discuss how this regularizer relates to graph matching, K-means and Laplacian smoothness. Under the assumption that the data is exactly generated from vertices of a Delaunay triangulation,the proposed regularizer exactly recovers the underlying sparse solution. Moreover, for fixedrepresentation coefficients, we show that the optimal landmarks can be computed in closed form. To solve the optimization problem of finding the coefficients and the landmarks, we use algorithm unrolling to derive a neural network that efficiently solves the problem. We discuss how the sparseembeddings derived from our algorithm can be used for downstream tasks such as clustering. 

* **Aleksander Madry, Professor, MIT**
    * **Friday, December 9, 2022 2:00-3:00pm** 
    * *Details to come*

## Fall 2022 Seminars

* **Kaća Bradonjić, Professor, Hampshire College**
    * **Friday, October 21, 2022, 2:00–3:00 pm**
    * *Return to the phenomenal: An exploration of the subjective, internal representations of physical theories and their relation to the collective pursuits of knowledge* 
    * Physicists study the physical world on spatial, temporal and complexity scales inaccessible through ordinary human perception. *How, then, does a person ground their understanding of physics at these scales in the sensory impressions and emotional states made possible by their body?* In relation to the field as a whole, we can also ask: *To what extent and how does a physicist’s research methodology (theoretical, experimental, or computational) shape the features of the mental models they use in their work? Conversely, to what extent and how do a physicist’s mental models affect the way they approach and engage with a research problem? Finally, what is the nature of the dynamic relation between the individual mental models and their collectively-accepted representational counterparts, and how does it impact physics research?* In this talk, I will sketch out the framing of my approach to these questions that integrates artistic and intellectual practices, and is informed by the history and philosophy of science, theories of embodied cognition, and philosophy of phenomenology. I will then describe the exploratory stages of my first project in this vein, carried out at IAIFI, with the particular focus on the role of AI in particle physics research. 

* **Jessie Micallef, IAIFI Fellow**
    * **Friday, September 30, 2022 2:00-3:00pm** 
    * *Neutrinos and Neural Networks: Need for Speed and Adaptability*
    * Abstract: Neutrinos remain an elusive and intriguing fundamental particle that is useful for probing inconsistencies of the Standard Model: neutrinos have mass when the Standard Model predicts they should not, they potentially exhibit charge parity violation, and there are possible hints of a fourth, sterile neutrino flavor. Data from neutrino detectors is particularly valuable due to the neutrinos’ weakly interacting nature, thus it is crucial that we maximize the information per detected interaction. In this talk, I will show how we are using machine learning to better analyze the precious data from various types of neutrino detectors. I will discuss optimizing convolutional neural networks (CNNs) to reconstruct GeV-scale neutrino events in the IceCube detector and how these measurements can help improve our understanding of these difficult-to-detect particles. I will focus on the challenges of reconstructing sparse, noisy neutrino events along with the speedup advantages of using machine learning methods. I will also touch on challenges that machine learning reconstructions face with the current and next generation of neutrino experiments, which will leverage Liquid Argon (LAr) detectors that use charge and light to record neutrino interactions.

## Spring 2022 Seminars
* **Anna Golubeva, IAIFI Fellow**
    * **Friday, March 11, 2022 2:00-3:00pm** 
    * *"The role of symmetry in machine learning"*
    * Abstract: In physics, symmetry is a concept of fundamental importance. It has served as a powerful guiding principle that allows us to find regularities in complex phenomena and to deduce the underlying simple laws of nature. Can we leverage the principle of symmetry to gain insights into Machine Learning? There are three separate but interconnected parts of a ML system where we could look for symmetries: The neural network architecture, the input data and the loss function. I will give an overview of the existing research on this topic and discuss the implications for practical ML.

* **Boaz Borak, Professor, Computer Science, Harvard**
    * **Friday, April 8, 2022 2:00-3:00pm** 
    * *Deep learning, generalization, and rationality*
    * Abstract: Deep learning often operates in a regime where traditional generalization bounds fail to hold, and indeed are not even true, in the sense that there is a non vanishing gap between empirical and population performance. Yet, deep neural networks still generalize and perform well beyond their training set.  In this talk we will present: (1) Empirical evidence that deep networks have similar internal representations regardless of whether they are trained in the traditional "full supervised" manner or trained in a "self supervised + simple" (SSS) method, where all but their last layer are trained without access to the labels; (2)  Empirical evidence that for SSS algorithms, generalization is true in practice, along with a theoretical bound on the generalization gap of such algorithms which is non vacuous in several practical setting. The bound does not make structural or conditional independence assumptions on the training distribution, but rather assumes the algorithm is "rational" in a certain precise sense, which is empirically shown to hold in practice.
The talk will not require background in deep learning. Based on joint works with Yamini Bansal, Gal Kaplun, and Preetum Nakkiran.

* **Siddharth Mishra-Sharma, IAIFI Fellow**
    * **Friday, April 22, 2022 4:00-5:00pm** 
    * *Flows for inference and interpretability: a Galactic Center Excess case study*
    * Abstract: The source of the so-called Galactic Center Excess (GCE)---an excess of gamma-rays observed from the central regions of the Milky Way---remains an open question. Disentangling the various possibilities, such as annihilating dark matter and astrophysical point sources, is a challenging modeling and inference task. I will describe some recent attempts at making progress in this direction by leveraging neural simulation-based inference techniques. Time permitting, I will describe some ongoing work using generative modeling as a test of robustness of neural network-based inference methods in the context of the GCE.

* **Special Seminar: Junyu Liu**
  * **Wednesday, June 1, 2022 2:30-3:30pm** 
  * *An analytic theory for the dynamics of wide quantum neural networks*
  * Abstract: Parametrized quantum circuits can be used as quantum neural networks and have the potential to outperform their classical counterparts when trained for addressing learning problems. To date, much of the results on their performance on practical problems are heuristic in nature. In particular, the convergence rate for the training of quantum neural networks is not fully understood. Here, we analyze the dynamics of gradient descent for the training error of a class of variational quantum machine learning models. We define wide quantum neural networks as parameterized quantum circuits in the limit of a large number of qubits and variational parameters. We then find a simple analytic formula that captures the average behavior of their loss function and discuss the consequences of our findings. For example, for random quantum circuits, we predict and characterize an exponential decay of the residual training error as a function of the parameters of the system. We finally validate our analytic results with numerical experiments.


## Fall 2021 Seminars

  * **Fabian Ruehle, Assistant Professor, Northeastern University**
    * **Friday, September 24, 2:00-3:00pm** 
    * *"Learning metrics in extra dimensions"*
    * Abstract: String theory is a very promising candidate for a fundamental theory of our universe. An interesting prediction of string theory is that spacetime is ten-dimensional. Since we only observe four spacetime dimensions, the extra six dimensions are small and compact, thus evading detection. These extra six-dimensional spaces, known as Calabi-Yau spaces, are very special and elusive. They are equipped with a special metric needed to make string theory consistent. This special property is given in terms of a (notoriously hard) type of partial differential equation. While we know, thanks to the heroic work of Calabi and Yau, that this PDE has a unique solution and hence that the metric exists, we neither know what it looks like nor how to construct it explicitly. However, the metric is an important quantity that enters in many physical observables, e.g. particle masses. Thinking of the metric as a function that satisfies three constraints that enter in the Calabi-Yau theorem, we can parameterize the metric as a neural network and formulate the problem as multiple continuous optimization tasks. The neural network is trained (akin to self-supervision) by sampling points from the Calabi-Yau space and imposing the constraints entering the theorem as customized loss functions.

  * **Di Luo, IAIFI Fellow**
    * **Friday, October 8, 2:00-3:00pm**
    * *"Machine Learning for Quantum Many-body Physics"*
    * Abstract: The study of quantum many-body physics plays an crucial role across condensed matter physics, high energy physics and quantum information science. Due to the exponential growing nature of Hilbert space, challenges arise for exact classical simulations of high dimensional wave function which is the core object in quantum many-body physics. A natural question comes as whether machine learning, which is powerful for processing high dimensional probability distribution, can provide new methods for studying quantum many-body physics. In contrast to the standard high dimensional probability distribution, the wave function further exhibits complex phase structure and rich symmetries besides high dimensionality. It opens up a series of interesting questions for high dimensional optimization, sampling and representation imposed by quantum many-body physics. In this talk, I will discuss recent advancement of the field and present (1) neural network representations for quantum states with Fermionic anti-symmetry and gauge symmetries; (2) neural network simulations for ground state and real time dynamics in condensed matter physics, high energy physics and quantum information science; (3) quantum control protocol discovery with machine learning.

  * **Cengiz Pehlevan, Assistant Professor, Applied Mathematics, Harvard University (SEAS)**
    * **Friday, October 22, 2:00-3:00pm**
    * *"Inductive bias of neural networks"*
    * Abstract: A learner’s performance depends crucially on how its internal assumptions, or inductive biases, align with the task at hand. I will present a theory that describes the inductive biases of neural networks in the infinite width limit using kernel methods and statistical mechanics. This theory elucidates an inductive bias to explain data with "simple functions" which are identified by solving a related kernel eigenfunction problem on the data distribution. This notion of simplicity allows us to characterize whether a network is compatible with a learning task, facilitating good generalization performance from a small number of training examples. I will present applications of the theory to deep networks (at finite width) trained on synthetic and real datasets, and recordings from the mouse primary visual cortex. Finally, I will briefly present an extension of the theory to out-of-distribution generalization.
    
  * **Bryan Ostdiek, Postdoctoral Fellow, Theoretical Particle Physics, Harvard University**
    * **Friday, November 5, 2:00-3:00pm**
    * *"Lessons from the Dark Machines Anomaly Score Challenge"*
    * Abstract: With LHC experiments producing strong exclusion bounds on theoretical new physics models, there has been recent interest in model agnostic methods to search for physics beyond the standard model. The Dark Machines group conducted a "challenge" as an open playground to examine unsupervised anomaly detection methods on simulated collider events. In this discussion, I briefly motivate and introduce anomaly detection, along with the public data set. We found that the methods which performed best across a wide range of signals shared a common feature; the metric for determining how anomalous an event is depends only on how the event can be encoded into a small representation - there is no decoding step. The discussion will start with speculations about why the "fixed target" encoding can work and look to future tests.

  * **Tess Smidt, Assistant Professor, EECS, MIT**
    * **Friday, November 19, 2:00-3:00pm**
    * *"Unexpected properties of symmetry equivariant neural networks"*
    * Abstract: Physical data and the way that it is represented contains rich context, e.g. symmetries, conserved quantities, and experimental setups. There are many ways to imbue machine learning models with this context (e.g. input representation, training schemes, constraining model structure) and each vary in their flexibility and robustness. In this talk, I’ll give examples of some surprising consequences of what happens when we impose constraints on the functional forms of our models. Specifically, I’ll discuss properties of Euclidean Neural Networks which are constructed to preserve 3D Euclidean symmetry. Perhaps unsurprisingly, symmetry preserving algorithms are extremely data-efficient; they are able to achieve better results with less training data. More unexpectedly, Euclidean Neural Networks also act as “symmetry-compilers”: they can only learn tasks that are symmetrically well-posed and they can also help uncover when there is symmetry implied missing information. I’ll give examples of these properties and how they can be used to craft useful training tasks for physical data. To conclude, I’ll highlight some open questions in symmetry equivariant neural networks particularly relevant to representing physical systems.

  * **Harini Suresh, PhD Student, Computer Science, MIT**
    * **Friday, December 3, 2:00-3:00pm**
    * *"Understanding Sources of Harm throughout the Machine Learning Life Cycle"* 
    * As machine learning increasingly affects people and society, awareness of its potential harmful effects has also grown. To anticipate, prevent, and mitigate undesirable downstream consequences, it's important that we understand when and how harm might be introduced throughout the ML life cycle. This talk will walk through a framework that identifies seven distinct potential sources of downstream harm in machine learning, spanning the data collection, development, and deployment processes.  It will also explore how different sources of harm might motivate different mitigation techniques.  

## Spring 2021 Seminars

  * **Justin Solomon**
    * **Thursday, February 11, 11am-noon**
    * *"Geometric Data Processing at MIT"*

  * **Phil Harris, Anjali Nambrath, Karna Morey, Michal Szurek, Jade Chongsathapornpong**
    * **Thursday, February 25, 11am-noon**
    * *"Open Data Science in Physics Courses"*

  * **Ge Yang**
    * **Thursday, Mar 11, 11am-noon**
    * *"Learning Task Informed Abstractions"*

  * **Christopher Rackauckas**
    * **Thursday, Mar 25, 11am-noon**
    * *"Overview of SciML"*
    
  * **George Barbastathis/Demba Ba**
    * **Thursday, April 8, 11am-noon**
    * *"On the Countinuum between Dictionaries and Neural Nets for Inverse Problems"*
    
  * **David Kaiser**
    * **Thursday, April 22, 11am-noon**
    * *"Ethics and AI"*
        
  * **Alexander Rakhlin**
    * **Thursday, May 6, 11am-noon**
    * *"Deep Learning: A Statistical Viewpoint"*
        
  * **Edo Berger**
    * **Thursday, May 20, 11am-noon**
    * *"Machine Learning for Cosmic Explosions"*

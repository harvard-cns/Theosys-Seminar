# Harvard Systems-Theory Seminar

## Description
We are hoping to spur more fruitful collaborations between the theorists and the systems folks through Systems-Theory seminar. The seminar will be in Harvard SEC 2.330, with talks starting at 3:45 and snacks at 3:00.

## Schedule

- 09/28/2022: **Algorithms for Programmable Switches**
  * Speaker: [Minlan Yu](http://minlanyu.seas.harvard.edu/) (Harvard)
  * Abstract: Minlan Yu will be talking about her work about building algorithms and data structures into programmable switches.  But we'll also be talking about building up a community of people working at the interface of systems and theory, and how we think it can lead to great research synergies.  
  * Slides: [link](slides/theosys-22fall-1.pptx)
- 10/12/2022: **Lossy Compression schemes for Federated and Distributed Learning Systems**
  * Speaker: [Michael Mitzenmacher](https://www.eecs.harvard.edu/~michaelm/) (Harvard)
  * Abstract: Michael Mitzenmacher will talk about his work with several others on lossy compression schemes for federated and distributed learning systems, and the corresponding distributed mean estimation problem.  In particular, we’ll look at some of the properties of random rotations on high-dimensional spheres, and why they end up being useful in this setting. He’ll also talk a bit about his thoughts on working at the intersection of systems and theory, and how both sides need to talk more with each other.

- 10/26/2022: **Unleashing the Algorithmic Power of Approximate Computing Systems**
  * Speaker: [Alan Liu](https://zaoxing.github.io/) (Boston University)
  * Abstract: Today’s computing systems, such as big data, networked, and steaming analytics systems, face increasing demands on performance, reliability, and energy efficiency. In the last few decades, rapidly evolving microprocessors have largely fulfilled these demands. However, with the slow-down of Moore’s Law, existing data processing systems are ill-suited for analyzing large-scale, dynamic data and face key underlying algorithmic challenges.
In this talk, I will present my research on scaling data systems with approximation techniques for dynamic connected data processing. I will discuss efficient algorithms and implementations that enable mining complex structures in large-scale graph data. I will describe how bridging theory and practice with probabilistic and sampling theory can significantly speed up computations without specialized hardware. Finally, I will end the talk with my vision for building energy-efficient data-intensive and machine learning systems
 
- 11/09/2022: **Towards instance-optimized data systems**
  * Speaker: [Tim Kraska](https://people.csail.mit.edu/kraska/) (MIT)
  * Abstract: Recently, there has been a lot of excitement around ML-enhanced (or learned) algorithms and data structures. For example, there has been work on applying machine learning to improve query optimization, indexing, storage layouts, scheduling, log-structured merge trees, sorting, compression, sketches, among many other data management tasks. Arguably, the ideas behind these techniques are similar: machine learning is used to model the data and/or workload in order to derive a more efficient algorithm or data structure. Ultimately, what these techniques will allow us to build are “instance-optimized” systems; systems that self-adjust to a given workload and data distribution to provide unprecedented performance and avoid the need for tuning by an administrator.
This talk will be an updated version of my VLDB 2022 keynote. I will  provide an overview of somet ML-enhanced algorithms and data structures and present initial results of SageDB, a first instance-optimized system. 


- 12/07/2022: **CausalSim: A Causal Inference Framework for Unbiased Trace-Driven Simulation**
  * Speaker: [Muhammad Alizadeh](https://people.csail.mit.edu/alizadeh/) (MIT)
  * Abstract: Trace-driven simulation is a widely used method for evaluating new ideas in systems. Today's trace-driven simulators assume that the interventions being simulated (e.g., a new algorithm or architectural choice) would not affect the validity of the traces. However, real-world traces are often biased by the environment used during trace collection, and hence replaying traces under an intervention may lead to incorrect results. This talk will present CausalSim, a causal inference framework for unbiased trace-driven simulation that addresses this challenge. CausalSim learns a causal model of the system dynamics and latent factors capturing the underlying system conditions during trace collection. It learns these models using an initial randomized control trial (RCT) under a fixed set of algorithms and uses them to remove biases from trace data when simulating new algorithms.<br />I will describe CausalSim’s key ideas, in particular, a connection between trace-driven simulation and a certain tensor completion task with extremely sparse observations. I will discuss how CasualSim exploits a basic distributional invariance property present in RCT data to solve this tensor completion problem. Finally, I will present CasualSim’s evaluation, including a real-world case study on the Puffer video streaming system in which CasualSim provides markedly different insights about adaptive bitrate (ABR) protocols compared to current biased simulators.

- 01/24/2023
- 02/07/2023
- 02/21/2023 Brighten Godfrey
- 03/07/2023 
- 03/21/2023 Jim Xu
- 04/04/2023 Rachit Agarwal
- 04/18/2023 Michael Schapira

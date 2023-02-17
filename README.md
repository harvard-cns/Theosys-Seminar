# Harvard Systems-Theory Seminar

## Description
We are hoping to spur more fruitful collaborations between the theorists and the systems folks through Systems-Theory seminar. The seminar will be in Harvard SEC 2.330, with talks starting at 3:45 and snacks at 3:00.

If you'd like to join our seminar announcement mailing list, please email Gioia Sweetland at gioia@seas.harvard.edu.

## Schedule

### Spring 2023
- 01/24/2023 **Scheduling Challenges for DNN Training Workloads**
  * Speaker: [Amar Phanishayee](https://www.microsoft.com/en-us/research/people/amar/) (Microsoft Research)
  * Abstract: In this talk, I'll highlight some scheduling challenges for DNN training workloads that we have tackled in the context of Project Fiddle.  Scheduling is a rather broad term. I am first going to show you how current DNN frameworks are culpable in excluding the masses from being able to develop, debug, or train large DNN models on modest deployments, and how changes to task scheduling within a DNN job can push the envelope for democratizing large model development.  I'll then talk about multi-tenancy and some of the cross-job scheduling opportunities that improve cluster utilization, fairness, performance, etc.  Time permitting, I'll end by describing a toolkit for developing research schedulers that we have been building using our experience of working on many cluster schedulers for DNN workloads in the past. 

- 02/07/2023 **A New Toolbox for Scheduling Theory**
  * Speaker: [Ziv Scully](https://ziv.codes/) (Cornell)
  * Abstract: Queueing delays are ubiquitous in many domains, including computer systems, service systems, communication networks, supply chains, and transportation. Queueing and scheduling theory provide a rigorous basis for understanding how to reduce delays with scheduling, including evaluating policy performance and guiding policy design. Unfortunately, state-of-the-art theory fails to address many practical concerns. For example, scheduling theory seldom treats nontrivial preemption limitations, and there is very little theory for scheduling in multiserver queues. We present two new, broadly applicable tools that greatly expand the reach of scheduling theory, using each to solve multiple open problems. The first tool, called “SOAP”, is a new unifying theory of scheduling in single-server queues, specifically the M/G/1 model. SOAP characterizes the delay distribution of a broad space of policies, most of which have never been analyzed before. Such policies include the Gittins index policy, which minimizes mean delay in low-information settings, and many policies with preemption limitations. The second tool, called “WINE”, is a new queueing identity that complements Little’s law. WINE enables a new method of analyzing complex queueing systems by relating them to simpler systems. This results in the first delay bounds for SRPT (shortest remaining processing time) and the Gittins index policy in multiserver queues, specifically the M/G/k model.

- 02/21/2023 **Networking at the Speed of Light**
  * [Brighten Godfrey](https://pbg.cs.illinois.edu/) (UIUC) (on zoom)
  * Abstract: Low latency is a requirement for a variety of interactive network applications, from web browsing to emerging applications like virtual reality. But latency is also one of the most fundamentally challenging performance objectives.  We'll explore this challenge in two domains.
First, we tackle whether it is possible to build an Internet that moves data at nearly the speed of light in vacuum. Our speed-of-light ISP (cISP) design provides ultra-low latency with an optimized topology using free-space microwave links, accounting for practical factors ranging from transmission tower availability to reliability in inclement weather.  cISP achieves mean latencies within 5% of what's possible using great-circle paths at the speed of light.
Next, we move to the wireless edge, where 5G has high bandwidth but little latency improvement for common applications.  We address the difficult bandwidth-latency tradeoff with DChannel, a system that utilizes two channels – one high bandwidth, one low latency – simultaneously, making them appear like one channel to the application. DChannel steers packets intelligently so that even when the low-latency channel offers <1% of the bandwidth of eMBB, using both channels can improve page load time and mobile apps by 16-40%. We'll close with an open theoretical question of how to design optimal packet steering algorithms.

- 03/07/2023 Xiaoqi Chen (in person)
- 03/21/2023 Jim Xu (in person)
- 04/04/2023 Rachit Agarwal (in person)
- 04/20/2023 Michael Schapira (in person)

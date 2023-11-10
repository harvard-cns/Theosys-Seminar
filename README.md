# Harvard Systems-Theory Seminar

## Description
We are hoping to spur more fruitful collaborations between the theorists and the systems folks through Systems-Theory seminar. The seminar will be in Harvard SEC 2.330, with talks starting at 3:45 and snacks at 3:00.

If you'd like to join our seminar announcement mailing list, please email Gioia Sweetland at gioia@seas.harvard.edu.

## Schedule

### Fall 2023
- Oct 3, 2023: Ramesh Sitaraman (UMass Amherst)

   Title: Living on the Edge for a Quarter Century: A Personal Retrospective
  
Abstract:
As the creation of the edge turns 25, we look back at the critical role that it has played in the evolution of internet services. The story of the edge started in the late 1990s when servers were deployed worldwide at the internet’s edge to provide content delivery services for web pages and videos. The quest to move dynamic content and application logic closer to users created the first edge computing services a few years later. Currently, edge services are accessed by billions of users daily, accounting for most of the users and traffic on the internet today. Close interactions between theory and practice enabled the dramatic rise of the edge over the last quarter century. Theoretical ideas became part of production systems and practice drove new theoretical formulations. In telling the story of the edge, we will emphasize a few of these interactions to highlight the role of theory in practice. 



- Oct 17, 2023: Sandeep Silwal (MIT)

     Title: Improved Frequency Estimation Algorithms with and without Predictions 

Abstract: Estimating frequencies of elements appearing in a data stream is a key task in large-scale data analysis. Popular sketching approaches to this problem (e.g., CountMin and CountSketch) come with worst-case guarantees that probabilistically bound the error of the estimated frequencies for any possible input. The work of Hsu et al. introduced the idea of using machine learning to tailor sketching algorithms to the specific data distribution they are being run on. In particular, their learning-augmented frequency estimation algorithm uses a learned heavy-hitter oracle which predicts which elements will appear many times in the stream. We give a novel algorithm, which in some parameter regimes, already theoretically outperforms the learning based algorithm of Hsu et al. without the use of any predictions. Augmenting our algorithm with heavy-hitter predictions further reduces the error and improves upon the state of the art. Empirically, our algorithms achieve superior performance in all experiments compared to prior approaches.

- Oct 31, 2023: Alex Conway (Cornell Tech)
  
   Title: Data Structures for Fast Memory Systems

Abstract: In this talk, I’ll show how algorithms can yield surprising new designs for virtual memory systems. I’ll present an algorithmic approach to co-designing TLB hardware and the paging mechanism to increase TLB reach without the fragmentation issues incurred by huge pages. Along the way, I’ll introduce a new hash-table design that overcomes existing tradeoffs, and achieves better performance than state-of-the-art hash tables both in theory and in practice. Key to these results are “tiny pointers,” an algorithmic technique for compressing pointers.


- Nov 14, 2023: Junchen Jiang (University of Chicago)
  
  Title: : Perception-Driven Internet Systems

Abstract: Internet systems serve as vital infrastructure, but what should they optimize for? Traditional approaches optimize system performance metrics, but the ways consumers of applications perceive the system performance are often more nuanced. For instance, viewers might be less discerning about video quality in general gameplay during a sports broadcast than pivotal moments like scores. This talk will introduce a paradigm shift to optimize for the perception of consumers rather than performance metrics. The new paradigm also embraces the trend that consumers are increasingly ML models (vision models and large language models) in AI applications, and these ML consumers also exhibit a wide range of sensitivities to system performance. The perception-driven paradigm offers new potential to enhance user experience for a broader audience without the necessity of new infrastructure or increased resource usage.


- Dec 5, 2023: Michael Cafarella (MIT)


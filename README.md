# We will release the pretrained models soon!!


# RAPiD: Real-time Deterministic Trajectory Planning via Diffusion Behavior Priors for Safe and Efficient Autonomous Driving

![My Image](assets/teaser.png)

The official repository of the paper with supplementary: [RAPiD](https://arxiv.org/abs/2602.07339)


## About the project

This project is a collaboration between [Monash University, Malaysia campus](https://www.monash.edu.my/) and [Data Science & AI Lab](https://www.monash.edu/it/dsai) in the [Faculty of Information Technology](https://www.monash.edu/it), [Monash University, Melbourne (Clayton), Australia](https://www.monash.edu/).

Project Members -

[Ruturaj Reddy](https://scholar.google.com/citations?user=L31atXwAAAAJ&hl=en) [(Monash University, Melbourne, Australia)](https://www.monash.edu/),                                                                                                                                                     
[Hrishav Bakul Barua](https://www.researchgate.net/profile/Hrishav-Barua)  [(Monash University and TCS Research, Kolkata, India)](https://www.tcs.com/what-we-do/research),  
[Loo Junn Yong](https://research.monash.edu/en/persons/loo-junn-yong/) [(Monash University, Malaysia)](https://www.monash.edu.my/),                                                                                                                                                                                                                                                                             
[Thanh Thi Nguyen](https://sites.google.com/view/thanh-thi-nguyen) [(Monash University, Melbourne, Australia)](https://www.monash.edu/), and                                                                                                                                                                                                                                                                        
[Ganesh Krishnasami](https://research.monash.edu/en/persons/ganesh-krishnasamy) [(Monash University, Malaysia)](https://www.monash.edu.my/).


### <ins>Funding details<ins>

This work is supported by the prestigious [`Global Excellence and Mobility Scholarship (GEMS)`](https://www.monash.edu.my/research/support-and-scholarships/gems-scholarship), Monash University.

## Overview

Diffusion-based trajectory planners have demonstrated strong capability for modeling the multimodal nature of human driving behavior, but their reliance on iterative stochastic sampling poses critical challenges for real-time, safety-critical deployment. In this work, we present RAPiD, a deterministic policy extraction framework that distills a pretrained diffusion-based planner into an efficient policy while eliminating diffusion sampling. Using score-regularized policy optimization, we leverage the score function of a pre-trained diffusion planner as a behavior prior to regularize policy learning. To promote safety and passenger comfort, the policy is optimized using a critic trained to imitate a predictive driver controller, providing dense, safety-focused supervision beyond conventional imitation learning. Evaluations demonstrate that RAPiD achieves competitive performance on closed-loop nuPlan scenarios with an 8X speedup over diffusion baselines, while achieving state-of-the-art generalization among learning-based planners on the interPlan benchmark.

### Overall Architecture

![My Image](assets/architecture.png)


## Qualitative Results (check out the videos!!)


### nuPlan simulation: starting right turn (top) and low magnitude speed (bottom)

https://github.com/user-attachments/assets/e2459be8-253f-48e3-bb3f-1a8fcee762a9

https://github.com/user-attachments/assets/d8688e2a-d366-41d0-b1fd-9d3e10a42382


### interPlan simulation: pedestrian jaywalking (top) and overtaking parked vehicle (bottom)


https://github.com/user-attachments/assets/e9c598e1-ff45-43c9-984c-d9652e118d1b

https://github.com/user-attachments/assets/55e62e93-4108-44cc-aedc-e906351378df


# Best-Deep-Learning-Optimizers</br>
Collection of the latest, greatest, deep learning optimizers (for Pytorch) - CNN, NLP suitable
</br></br>
Current top performers = DeepMemory and Ranger.  this is only on initial testing.
</br></br>
![](images/1120-optimizer-testing.jpg)
</br>
12/27 - added DiffGrad, and unofficial version 1 support (coded from the paper). 
</br>
12/28 - added Diff_RGrad = diffGrad + Rectified Adam to start off....seems to work quite well. 

Medium article (summary and FastAI example usage):
https://medium.com/@lessw/meet-diffgrad-new-deep-learning-optimizer-that-solves-adams-overshoot-issue-ec63e28e01b2

Official diffGrad paper:  https://arxiv.org/abs/1909.11015v2

12/31 - AdaMod and DiffMod added.  Initial SLS files added (but more work needed).


<b>In Progress:</b></br></br>
A - Parabolic Approximation Line Search:  https://arxiv.org/abs/1903.11991v2

B - Stochastic Line Search (SLS): pending (needs param group support)

c - AvaGrad 


<b>General papers of relevance:</b>

Does Adam stick close to the optimal point?  https://arxiv.org/abs/1911.00289v1


Probabalistic line searches for stochastic optimization (2017, matlab only but good theory work):  https://arxiv.org/abs/1703.10034v2  

Main repository: https://github.com/lessw2020/Best-Deep-Learning-Optimizers/tree/master/adamod
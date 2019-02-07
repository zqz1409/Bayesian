[AstroML: Machine Learning and Data Mining for Astronomy](http://www.astroml.org/index.html)

[Basic Stats](http://slittlefair.staff.shef.ac.uk/teaching/phy217/lectures/stats/L18/index.html)
    
- Error propagation
    
      ![](http://latex.codecogs.com/gif.latex?\sigma_y^2=\left(\frac{\partial f}{\partial x_1}\right)^2 \sigma_{x_1}^2 + \left( \frac{\partial f}{\partial x_2} \right) ^2 \sigma_{x_2}^2 + \ldots + \left( \frac{\partial f}{\partial x_n}\right) ^2 \sigma_{x_n} ^2= \sum_i^n  \left( \frac{\partial f}{\partial x_i}\right) ^2 \sigma_{x_i}^2) 
    
- A magnitude error of 0.01 corresponds to a signal to noise ratio of 100, or a measure of the flux with 1% uncertainty.
    
[The Bayesian Astronomer](http://slittlefair.staff.shef.ac.uk/teaching/phy217/lectures/stats/L19/index.html)

- The **Likelihood** is the probability that we would obtain our data D, given a model M or a hypothesis H.
    
- They assume the **hypothesis** is true (the null hypothesis), and ask how likely their data is to occur, given the hypothesis. This probability is called the p-value. Typically, scientists will conclude there is reason to reject the null hypothesis if p<0.05. We will see later how this can lead to trouble.

- **Kolmogorov-Smirnov (KS) test**
A very useful test to see if two samples were drawn from the same distribution. The null hypothesis is that both distributions are the same. For example, we might have measured the masses of stars in two star clusters, and wish to test if they are drawn from the same mass distribution.

-  If you suspect your prior distributions are flat - independent of the parameter values - then Bayesian fitting and χ2 minimisation are identical

[Frequentism and Bayesianism I: A Practical Introduction](https://jakevdp.github.io/blog/2014/03/11/frequentism-and-bayesianism-a-practical-intro/)

    prior, likelihood, posterior

[Frequentism and Bayesianism II: When Results Differ](http://jakevdp.github.io/blog/2014/06/06/frequentism-and-bayesianism-2-when-results-differ/)

    The handling of nuisance parameters
    
    Outlier:
        [Huber loss](https://en.wikipedia.org/wiki/Huber_loss_function)
        Bayesian Approach: choose a mixture between a signal and a background
    
[Frequentism and Bayesianism III: Confidence, Credibility, and why Frequentism and Science do not Mix](http://jakevdp.github.io/blog/2014/06/12/frequentism-and-bayesianism-3-confidence-credibility/)

    The subtle difference between frequentist confidence intervals and Bayesian credible intervals
    
    

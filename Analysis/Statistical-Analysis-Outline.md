## Outline for Statistical Analysis section  

### Introduction to experimental design, Probability, Statistical Distributions, & Distribution testing
* [Gotelli Introduction to Statistics](http://www.uvm.edu/~ngotelli/Bio381Vids/L12_16Mar2021/A_StatsIntro.mp4) 
* Probability
  * [Tim Waring Probability Lecture](https://www.youtube.com/watch?v=lQ9zQ_s9ha8&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=5)
    * Probability notation & definitions
    * Contingency Tables
    * Conditional Probability
    * Math with Probability (Could be supplemented with some of MD's stuff)
* Discrete Distributions
  * [Tim Waring Discrete Distributions Lecture](https://www.youtube.com/watch?v=fc_VxxK10ps&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=6&t=1s)
    * Covers some statistical epistemology and introduction to distributions
    * Binomial Distribution (Theory, moments, & probability density function)
    * Geometric Distribution (Theory, moments, & probability density function0
    * Missing: Poisson, negative binomial, categorical/multinomial
  * [*jbstatistics* Video on Multinomial(Categorical) Distributions](https://www.youtube.com/watch?v=syVW7DgvUaY)
    * Expands the math and theory of the binomial distribution. Uses some mathmatical notation and gives an example using blood types.
  * [Working with Discrete Distributions in R](https://www.youtube.com/watch?v=ttZyFbECMDk&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=7)
    * covers: Binomial,Geometric, talks about the random number generator, pdf, cdf, & quantile functions.
* Continuous Distributions
  * [Tim Waring Continuous Distributions Lecture](https://www.youtube.com/watch?v=saKPgMgIKFo&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=8)
    * Properties of a continusous distrobution, a little math, mostly based on pictures.
    * Uniform distribution (theory, moments, & probability density function)
    * Exponential distribution (Theory, moments, & probability density function)
    * mentions poisson in relation to exponential 
  * [Working with Continuous Distributions in R](https://www.youtube.com/watch?v=kAeKAcZMOLM&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=9)
    * covers: exponential, uniform, talks about the random number generator, pdf, cdf, & quantile functions.
    * mentions poisson
* The Normal distribution
  * [Tim Waring Normal Distribution Lecture](https://www.youtube.com/watch?v=S6-LJEgCX8w&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=10)
    * History with Gauss
    * Distributional Assumptions
    * Distribution Moments
    * Standard Normal
  * [Working with the Normal Distribution in R](https://www.youtube.com/watch?v=JeIxShudFAE&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=13)
    * shows random number generator, pdf, cdf, & quantile functions
    * plots several sample distributions


### Inferential Statistics & Hypothesis Testing
* Estimating population parameters & Central Limit Theorum
  * [Tim Waring Central Limit Theorem Lecture](https://www.youtube.com/watch?v=Ly0NYnLw49s&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=12)
    * Law of Large numbers
    * CLT of means & sums
  * [Tim Waring Confidence Intervals Lecture](https://www.youtube.com/watch?v=oUV4jUMdGQs&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=14)
    * Inferential statistics & the value of doing it
    * Confidence levels, alpha levels
    * Student's t-distribution
    * Calculation of a confidence interval
    * sample size requirements for a given confidence level.
* Hypothesis testing basics
  * [Tim Waring One Sample Hypothesis Tests Theory Lecture](https://www.youtube.com/watch?v=3Pw7uKJU8LI&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=16)
    * Null & Alternative hypotheses
    * Type 1 & Type 2 Errors
    * p-values
    * Properties of a single sample test
  * [Tim Waring Two Sample Hypothesis Tests](https://www.youtube.com/watch?v=lFi39kCoiwM&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=18)
    * 0:00-11:37 Covers Theory:
      * Paired samples
      * Random variable differences
      * Pooled variance or standard deviations
      * Cohen's d

### Statistical Tests

#### Differences in Means & Proportions
* Differences in Means
  * [Tim Waring Two Sample Hypothesis Tests](https://www.youtube.com/watch?v=lFi39kCoiwM&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=18)
    * 11:38-End Covers Theory:
      * 2 samples with a known population variance: z-test
      * 2 sample populations without a known population variance: t-test
      * 2 sample proportions: proportion z-test
  * [Tim Waring One Sample Hypothesis Tests in R](https://www.youtube.com/watch?v=mlydrONjh04&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=17)
    * T-tests with one sample - testing if mean is a given value
    * proportion z test - testing if a proportion matches a hypothesized value
    * Binomial test - testing if the number of successes matches a hypothesized number
  * [Tim Waring Two Sample Hypothesis Tests in R](https://www.youtube.com/watch?v=tcrmxMibM0A&list=PLxdDmPeA5NKkqQKwo4hUZeMaoJzmdOddr&index=19)
    * T-tests with two samples
    * Cohen's D
    * two sample proportion tests

#### Dependence of 2 catagorical variables & contingency table analysis 
* Contingency table analysis: http://www.uvm.edu/~ngotelli/Bio381Vids/L12_16Mar2021/E_Contingency.mp4

#### ANOVA 
* ANOVA in R: http://www.uvm.edu/~ngotelli/Bio381Vids/L12_16Mar2021/C_ANOVA.mp4

#### Linear regression 
* Regression in R: http://www.uvm.edu/~ngotelli/Bio381Vids/L12_16Mar2021/B_Regression.mp4

#### Logistic regression 
* Logistic regression in R: http://www.uvm.edu/~ngotelli/Bio381Vids/L12_16Mar2021/D_Logistic.mp4



#### More advanced

##### Randomization tests
* Introduction: http://www.uvm.edu/~ngotelli/Bio381Vids/02April2020/A_IntroRandomizationTest.mp4
* Simple Example: http://www.uvm.edu/~ngotelli/Bio381Vids/02April2020/B_ToyExample.mp4
* Functions for randomization tests: http://www.uvm.edu/~ngotelli/Bio381Vids/02April2020/C_FunctionsForRandomization.mp4
* Running the analysis: http://www.uvm.edu/~ngotelli/Bio381Vids/02April2020/D_RunAnalysis.mp4

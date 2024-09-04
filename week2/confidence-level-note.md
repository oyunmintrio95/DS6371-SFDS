# Confidence-level-note.md

## Introducing Confidence Intervals
- Confidence intervals measure how large or small a parameter value could be.
- Example: Estimate a population mean mu from a sample.
  - If we take many multiple samples, we will se slightly different estimates of the mean.
  - The different estimates are a natural result of randomization.
  - Confidence intervals tell us where those answers should be.


## Samples From a Normally Distributed Population
- Suppose 300 student each draw arandom sample of 10 scores from a normally distributed population whose actual mena mu=10 and sigma = 1.5.
- Normal distribution theory says we should expect:
  - ~68% of the drawn values will be within 1sigma of mu.
  - ~95% of the drawn values will be within 2sigma of mu
  - ~99.7% of the drawn values will be within 3sigma of mu.
 
- If we have appropriately obtained sample menas, we can say:
  - 95% of the sample mean(x-bar_ will be fairly close to the actual population mean.
  - 5% of the sample mena(x-bar) values will be far away from mu.
 
## What the Confidence Interval Tells Us
- A 95% confidence interval means that, on average, we expect theendpoints of this particular interval to contain the poulation mean mu in 95% of random samples.
  - Remember: The measure is not necessarily confidence in te interval itself but in the procedure that produces the interval
- In other words, if we draw repeated samples of size n from a normally distributed population, 95% of the sample menas(x-bar) should lie within 1.96 standard errors of the actual mu.

## Estimating the confidence Interval
- To set up a confidence level estimate, we need to know:
  - A desired level of confidence (e.g., 95%, which is the most popular)
  - An estimate of the population's standard deviation
  - The sample mean x-bar
  - The sample size n
 - To calculate the confidence, we use the formula
   - CI = x-bar +- tcrit(s/sqrt(n))
  
## The Confidence interval Formula
- Note that we use s instead of sigma, where s is the sample standard deviation
- s is our estimate of sigma
- This substitution introduces error.
- So, confidence interval calculated with t-distribution instead of Normal distribution.
- t-distribution allows for error in estimate of standard deviation.

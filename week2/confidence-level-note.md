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
- t-distribution is like Normal distribution but with fatter tails that allow for error.
- since we hardly know the population standard deviation, we use t-distribution a lot

## EX: Emotional Inteligence Scores
- An estimate of the emotional intelligence(EI) of a random sample of children at a school for the gifted and talented
- The researcher's test
  - The sample mean x-bar = 130
  - The sample standard devation s = 15
  - The sample size n = 120
- The confidence interval formula
    - CO(Confidence Interval) = 130 += tcrit(15/sqrt(120))
- In our example, for a 95% confidence interval and n=120:
  - From a table, tcrit is 1.9790.
  - Note that 1.979 isclose to the 1.96 we'd get if we were using a Normal distribution
  - The values are close because we have a large sample size.
- CI = 127.29 to 132.71/
- We could say:
    - In the long run, "95% of the confidence intervals estimated with this procedure for random samples from the same population will contain the population mean mu."
    - "The other 5% of confidence intervals will not contain mu."
    - 
 ## calculating tcrit value   
- The tcrit value depends on your chosen confidence interval. (905, 95%, 99%. etc.)
- Look up the tcrit values in a table if you're calculating by hand
- tcrit is a function of:
  - the degrees of freedom(defined as n-1)
  - the confidence level(which you choose)

## How to interpret a 95 percent confidence interal for the mean?
- If we took many, many samples from the same population and constructed a confidence interval for the mean from each one, then approximately 95 percent of those intervals would contain the true mean. We hope that we have contained the mean in our interval, and thus we are 95 percent confident that our interval contains the mean.

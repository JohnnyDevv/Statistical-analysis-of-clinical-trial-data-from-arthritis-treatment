# Statistical-analysis-of-clinical-trial-data-from-arthritis-treatment

I have the data from the trial on the new arthritis treatment being developed by a hypothetical pharmaceutical company (Uji Pharma). The data contains 84 subjects for the trial, 41 which did take the medication and 43 “placebos” which didn’t.

## Questions to be answered

1. Can we prove with 99% certainty that the percentage of patients with "Marked" improvements is significantly higher for those that took the treatment vs the placebos?
2. On average, are we very confident that treated patients who showed marked improvements are older than those who didn't?

## Solution
1. For the 1st question, I computed the confidence interval for proportions in MS Excel, and arrived at the conclusion that we are 99% confident to expect the treatment to be more 
effective than the placebo by 10% - 60%  which is good news for Uji Pharma. There's still a 1% chance that the rate of effectiveness is outside the range of 10% - 60%(less than 10% or more than 60%).

2. For the 2nd question, I performed a hypothesis test (one tail to the right) in MS Excel, and arrived at the conclusion that we don't have sufficient evidence to prove that treated	patients who showed marked improvements are older than those who didn't, even though our sample statistics said otherwise.
Technical explanation: This was because the p-value was less than alpha (probability of error), hence we failed to reject the null hypothesis which stated that treated patients who showed marked improvements are the same age or younger than treated patients who didn't show marked improvements.

Access the full working of both solutions in the solution folder.




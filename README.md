# Interim_Analysis_of_Clinical_Trails

Blog post and R code by Frank Harrell at https://www.fharrell.com/post/bayes-seq/#disqus_thread.
 
Suppose we want to apply the idea in Frank Harrell’s post and program, but using the beta/binomial model in Ji and Yuan (2021) based on sequential interim analysis. Suppose the vaccine is considered efficacious if V E > 0.5 and futile if V E < 0.3. Allow trials to stop early for efficacy
or futility. Conduct the simulation based on distributed notes based on both Bayesian and frequentist’s inference. Report frequentist summary statistics, such as FWER and power. Also, report the summary statistics in Frank Harrell’s post, and in addition, report the false approval rate (FAR), false refusal rate (FRR), true approval rate (TAR). Also report the average sample size across all the trials, across those that lead to early stopping for efficacy, and across those that lead to early stopping for futility.
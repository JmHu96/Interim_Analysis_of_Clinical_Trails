# Interim_Analysis_of_Clinical_Trails

The purpose for this project is to analyze whether it was appropriate to end a clinical trial early if the test statistic had fallen into critical region when the number of tested samples was large enough although not all the samples got tested. If the result is that we can stop clinical trails early, it would be advantageous by saving people from being injected vaccines in trail that might be harmful to their health.

We will use the blog post and R code by Frank Harrell at https://www.fharrell.com/post/bayes-seq/#disqus_thread as a reference. We will apply the idea in Frank Harrell’s post and program, but using the beta/binomial model in Ji and Yuan (2021) based on sequential interim analysis. Let VE be the vaccine efficacy, namely, the proportion of patients who are projected from the virus after vaccination and  suppose the vaccine is considered efficacious if VE > 0.5 and futile if VE < 0.3. Allow trials to stop early for efficacy
or futility.

The other purpose of this project is to compare the Frequentist approach and the Bayesian approach. We will see that using Bayesian way of analyzing results would save 19\% of patients while achieve 95 \% test accuracy for drawing result of whether the data supports our hypothesis.

We will not only consider the accuracy of our conclusion about the hypothesis, but also other metrics such as power, false approval rate (FAR), false refusal rate (FRR), true approval rate (TAR). We will also report the average sample size across all the trials, across those that lead to early stopping for efficacy, and across those that lead to early stopping for futility.
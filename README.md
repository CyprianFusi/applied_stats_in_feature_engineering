# applied_stats_in_feature_engineering
Hypothesis testing and feature engineering in machine learning

Statistical analysis or studies are always done using samples drawn from a population. It is either impossible to collect data from all members of the population or the data might be too large to fit into memory during analysis. We therefore use the sample statistics to make conclusions or inference about the population. But there is always uncertainties associated with the sample statistics and this means the inferences made about the population based on the sample might be wrong! It is therefore necessary to make sure that the sample, truely, is a good representation of the population under study. This calls for a Statistical Hypothesis Test to be conducted on the sample(s).

For example we use Statistical Hypothesis Test to find out whether a sample mean ( 𝑥¯ ) indeed is the same as the population mean ( 𝜇 ) or whether the sample standard deviation ( 𝑠 ) is the same as the population standard deviation ( 𝜎 ).

Note that unlike sample parameters (e.g  𝑥¯  and  𝑠 ) the population parameters are indicated using Greek symbols (e.g  𝜇  and  𝜎 ) because they are unknown (they are Greek to us)!
It is also worth noting that there are two man types of Statistical Hypothesis Test: parametric and non-parametric. Parametric hypthosis test assumes that the sample is normally or Gaussian dsitributed and therefore apply the well known and well studies parameters of the Gaussian distribution. If the sample is not normally distribution the non-parametric hypothesis test is used.

Scipy's stats module includes several functions that can be used for Statistical Hypothesis Test as demonstrated in the examples in theis notebook.

Assignment 4

Briefly read the following paper, and download the data from this experiment:

Carlitz, E.H.D., Runge, J.-N., König, B., Winkler, L., Kirschbaum, C., Gao, W., Lindholm, A.K., 2019. Steroid hormones in hair reveal sexual maturity and competition in wild house mice ( Mus musculus domesticus ). Sci Rep 9, 1–10. https://doi.org/10.1038/s41598-019-53362-4

You can find both the data and the paper in Dryad: https://datadryad.org/stash/dataset/doi:10.5061/dryad.x95x69pd6

Produce an Rmarkdown document in which you answer the following questions. These questions fit together to produce a statistical workflow.

Provide a brief description of the study including the experimental set-up. What were the research questions being addressed?  What responses were measured? What factors were included in their models? (2 points)

Data exploration. Reproduce the scatterplots in Figures 1, 3, and 4, but add a geom_smooth() using either method=”lm” or method=”loess”. Also reproduce Figure 2. Comment on the patterns that you observe. (2 points)

Model fit. Fit models to the data that support (or contradict) the following statements from the Results section of the paper. It is important that you comment on the model output of your code using non-technical language. Also, check all model assumptions with residual plots.
“For corticosterone, age had a strong positive effect, while sex itself did not have explanatory power. However, fitting an interaction of age and sex showed that older males had higher corticosterone levels than older females. Adding body weight to the model did not yield better model fit.” (1 point)
“The level of injury had a strong predictive effect on corticosterone concentration which was additive to the effects of sex and age. Using the back-transformed estimate of the sex and age interaction term in model 7 of 1.0010 (95% CI = 0.9994–1.0026), we calculated that with each additional month of age corticosterone increased 3% more in males compared to females. The back-transformed estimate of effect of injury of 1.1539 (95% CI=1.0910–1.2206), predicts an increase of corticosterone by 15% with each level of injury, independent of the effects of age and sex.” (1 point)
“For females, adding the number of embryo implantations throughout life improved the fit of the model containing age and body weight (progesterone Model 5 females only vs. Model 3). Using the back-transformed slope estimates for age of 1.0091 (95% CI = 1.0042–1.0136), for body weight of 1.0289 (95% CI = 0.990–1.0725), and for number of embryo implantations of 1.0659 (95% CI = 1.0301–1.10; Fig. 3a), among females, progesterone was estimated to increase by 27.2% per month of age, by 3% per gram of body weight, and by 6.6% with each implanted embryo.” (1 point)
“Testosterone in males was significantly predicted by body weight (strongest predictor), age and testes weight. The number of sperm additionally improved the model fit. The back-transformed slope estimates for testes weight of 1.0064 (95% CI = 1.0025–1.0106) and for sperm number of 1.000013 (95% CI = 1.0–1.00017) indicate a testosterone increase by 0.6% per mg increased testes weight (mean testes weight = 134 mg, range = 13–221 mg) and 1.3% increase for each 1000 sperm counted (mean sperm count = 998, range = 0–7000).” (1 point)
Model selection using AIC: Explain briefly what AIC is and how it is used to compare and select models for data. (2 points)

# Model Selection and Model Fit

This repository contains tutorials that explore ways to select phylogenetic models for your data and then analyze how well those models fit the data.

First, we'll work through using RevBayes to select among substitution models using Bayes Factors. A tutorial is available [here](https://revbayes.github.io/tutorials/model_selection_bayes_factors/bf_subst_model.html) and data files and scripts are available [here]().

We can use Bayes factors to select models in many contexts beyond only substitution models. Here we'll use it to select a partition model. I am supplying you with simulated data for four genes, along with an example Rev script that will estimate the marginal likelihood for one possible partition model. You should modify this script to specify _a different_ partition model, estimate the marignal likelihood, and add your result to the class spreadsheet. You can download the data and scripts [here]().

The above exercises allow us to gauge relative model fit, which as 'Which model from a set of candidates fit my data the best?' A related question is 'Does the best fitting model describe the data well in an absolute sense?' If all the models in our set of candidates fit the data poorly, even the best of a bad bunch might mislead us. These tutorials will show you how to ask this question using the P<sup>3</sup> pipeline in RevBayes for both [data based](https://revbayes.github.io/tutorials/model_testing_pps/pps_data.html) and [inference based](https://revbayes.github.io/tutorials/model_testing_pps/pps_inference.html) test statistics. The relevant scripts and data files for these tutorials are available [here]().
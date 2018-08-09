# The Utility of Keeping it Simple
## David Braun & Catherine M. Arrington

This is a repository for the manuscript titled *The Utility of Keeping it Simple: Investigating How Reward is Processed During Motivated Allocation of Cognitive Control*. This repository contains original and summarized data, as well as the main R scripts used to summarize and analyze the data. The scripts are not exhaustive--if there was something that was reported in the paper that isn't represented in this repository, contact me and I'll find the code that produced it. This repository does however contain the code that produced the main analyses for each experiment. 

Because I was learning how to use R throughout this analysis, I used a variety of methods for summarizing code, including: plain `.R` script files, `.Rmd` R Markdown files, and `.ipynb` Jupyter Notebook files (using an R kernel). There are `.html` files included for both the R Markdown and Jupyter Notebook files and are intended to serve as an easily accessible summary of the scripts themselves (it's the same exact text, the only difference being that code cannot actually be *executed* through the HTML files). All filepaths in the scripts are relative to the directory that the script is in.

A brief index of this repository:

1. Experiment 1
  
	* [Data](experiment_one/data)

	* [Preprocessing Script](experiment_one/scripts/preprocessing.R)

		* This script converts the raw data from Experiment 1 into several summarized datasets.

	*  [Main Analysis](experiment_one/scripts/main_analysis.ipynb)

		* This script contains the main analysis reported in Experiment 1, along with some exploratory analyses that didn't get reported in the manuscript.

2. Experiment 2

	* [Data](experiment_two/data)

	*  [Preprocessing Script](experiment_two/scripts/preprocessing.R)

		* This script converts the raw data from Experiment 1 into several summarized datasets.

	* [Preregistered Analyses](experiment_two/scripts/preregistered.ipynb)

		* This script contains the analyses preregistered in a time-frozen OSF [repository](https://osf.io/uex5x/register/5730e99a9ad5a102c5745a8a)

	* [Mixed Mode](experiment_two/scripts/mixed_model.ipynb)

		* This script contains a mixed-model analysis of Experiment 2 data (reported in Appendix B of the manuscript).

3. [Performance Data](https://htmlpreview.github.io/?https://github.com/dab414/keeping_it_simple/blob/master/performance_data/Performance%20Summary.nb.html)
		
	* This script contains the analysis of performance data (for both experiments).

If you have any questions, don't hesitate to email -> dab414@lehigh.edu

Best,
Dave Braun

## List of Dependencies

* ez
* tidyverse
* data.table
* lsmeans
* lme4
* repr
* plyr




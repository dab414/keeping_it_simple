# The Utility of Keeping it Simple
## David Braun & Catherine M. Arrington

This is a repository for the manuscript titled *The Utility of Keeping it Simple: Investigating How Reward is Processed During Motivated Allocation of Cognitive Control*. This repository contains original and summarized data, as well as the main R scripts used to summarize and analyze the data. The scripts are not exhaustive--if there was something that was reported in the paper that isn't represented in this repository, contact me and I'll find the code that produced it. This repository does however contain the code that produced the main analyses for each experiment. 

Throughout this analysis I was exploring using different methods for analyzing data in R, including: plain `.R` script files, `.Rmd` R Markdown files, and `.ipynb` Jupyter Notebook files (using an R kernel). There are `.html` files included for both the R Markdown and Jupyter Notebook files and are intended to serve as an easily accessible summary of the scripts themselves (it's the same exact text, the only difference being that code cannot actually be *executed* through the HTML files). `.R` scripts and `.Rmd` markdown files should be fully reproducible by using a tool such as [rstudio](https://www.rstudio.com/). `.ipynb` files can be run by opening in a Jupyter Notebook (or labs) with an R kernel (slightly more complicated, but see guides [here](https://www.datacamp.com/community/blog/jupyter-notebook-r) or [here](https://richpauloo.github.io/2018-05-16-Installing-the-R-kernel-in-Jupyter-Lab/). All filepaths in the scripts are relative to the directory that the script is in.

A brief index of this repository:

* [var_coding.txt](var_coding.txt) -- A brief explanation about the coding of variables in the data for both experiments.

1. Experiment 1
  
	* [Data](experiment_one/data)

		* `disconnect_original.csv` -- this is the raw data.

		* `disconnect.csv` -- this is the trimmed data.

	* [Preprocessing Script](experiment_one/scripts/preprocessing.R)

		* This script converts the raw data from Experiment 1 into several summarized datasets.

	*  [Main Analysis](experiment_one/scripts/main_analyses.ipynb)

		* This script contains the main analysis reported in Experiment 1, along with some exploratory analyses that didn't get reported in the manuscript.

2. Experiment 2

	* [Data](experiment_two/data)

		* `disconnect_green1-18.csv` -- this is the raw data.

		* `disconnect_green.csv` -- this is the trimmed data.

	*  [Preprocessing Script](experiment_two/scripts/preprocessing.R)

		* This script converts the raw data from Experiment 1 into several summarized datasets.

	* [Preregistered Analyses](experiment_two/scripts/preregistered.ipynb)

		* This script contains the analyses that were preregistered in a time-frozen OSF [repository](https://osf.io/uex5x/register/5730e99a9ad5a102c5745a8a)

	* [Mixed Model](experiment_two/scripts/mixed_model.ipynb)

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




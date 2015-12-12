Data from the study described in the paper of Preti et al (2015)
-

In this repository you can find the dataset and the codes for reproducing the analyses that were summarized in the article:

Preti A., Siddi S., Vellante M., Scanu R., Muratore T., Gabrielli M., Tronci D., Masala C., Petretto D. R. (2015). Bifactor structure of the schizotypal personality questionnaire (SPQ). *Psychiatry Research*.

This material is provided to the aims of reproducibility and replicability of the findings reported in the paper.

"There are two major components to a reproducible study: that the raw data from the experiment are available; and that the statistical code and documentation to reproduce the analysis are also available". Roger Peng. The reproducibility crisis in science: A statistical counterattack. Significance, 2015; 12: 30-32.

For this reason, we have decided to make the raw data and the statistical code available, which we used to perform the analyses described in the paper. The documentation required to reproduce the analysis is also available.

There is no restriction to use this material for teaching purpose,  but we were glad if you cite the paper and this repository as the source.

If you use the data for purposes that respond to the same or related aims of the study to which they belong (in this case, the determination of the factor structure of the SPQ), you are expected to involve the principal investigator of the study as co-author and to share your analyses and conclusions with him/her.

Please, read the "General statement" for further information and details.

To use the dataset, click on "mmc6.csv", then click on "Raw", then save the file as "dataset.csv" in your working directory.

All codes are in R language, and are commented to favour understanding of the less known commands.

To load into the R environment the dataset, use this command:
d <- read.csv2(file.choose(), header=TRUE, strip.white=TRUE)

We cannot provide tutoring on the use of R as a statistical computing and graphic environment. People using these codes are expected to have a general understanding of how R works. 

We can provide some clarification for sections of the codes that are not completely clear.  At our best, we tried to provide explanations of all passages that are not usual.

### Reference

Preti A., Siddi S., Vellante M., Scanu R., Muratore T., Gabrielli M., Tronci D., Masala C., Petretto D. R. (2015). Bifactor structure of the schizotypal personality questionnaire (SPQ). *Psychiatry Research*. http://dx.doi.org/10.1016/j.psychres.2015.11.010

Pubmed URL: http://www.ncbi.nlm.nih.gov/pubmed/26607431

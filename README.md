# funding.disagree
Code and data for our analysis of AIBS grant applications. Paper title: "[Do funding applications where peer reviewers disagree
have higher citations?](https://f1000research.com/articles/7-1030/v1)"

The four files are:
1. `AIBS.RData`, R data file with the following variables:
* "Anon_PropID" - Application ID number
* "Review Year" - Year application was reviewed
* "Web TRC" - Total relative citations (primary outcome)
* "score.mean" - Mean of peer reviewers' scores
* "score.sd" - Standard deviance of peer reviewers' scores
* "Min Score" - Minimum of peer reviewers' scores  
* "Max Score" - Maximum of peer reviewers' scores
* "range" - Range of peer reviewers' scores
* "N Votes" - Number of peer reviewers
* "Panel" - Panel ID

2. `AIBS.csv`, csv data with same rows and variables as AIBS.RData.

3. `grant.outcomes.github.Rmd`, Rmarkdown file to perform the analyses using `AIBS.RData`. Was created using R version 3.4.4. The following R packages need to be installed:
* doBy
* dplyr
* ellipse 
* ggplot2
* influence.ME
* lme4
* merTools
* mice 
* mitools 
* pander
* plyr
* reshape2
* stargazer 

4. `grant.outcomes.github.docx`, Word output from the Rmarkdown file.

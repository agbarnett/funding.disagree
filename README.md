# funding.disagree
Code and data for our analysis of AIBS grant applications. Do funding applications where peer reviewers disagree
have higher citations?

The files are:
1. AIBS.RData, R data file with the following variables:
  
  -- "Anon_PropID" - Application ID number
  
  -- "Review Year" - Year application was reviewed
  
  -- "Web TRC" - Total relative citations (primary outcome)
  
  -- "score.mean" - Mean of peer reviewers' scores
  
  -- "score.sd" - Standard deviance of peer reviewers' scores
  
  -- "Min Score" - Minimum of peer reviewers' scores  
  
  -- "Max Score" - Maximum of peer reviewers' scores
  
  -- "range" - Range of peer reviewers' scores
  
  -- "N Votes" - Number of peer reviewers
  
  -- "Panel" - Panel ID

2. grant.outcomes.github.Rmd, Rmarkdown file to perform the analyses

3. grant.outcomes.github.docx, Word output from the Rmarkdown file

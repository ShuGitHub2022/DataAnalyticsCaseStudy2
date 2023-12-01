# Data Analytics Case Study2
Data Analytics Case Study EuroCup Soccer. This is Data in Motion data analysis challenge #2. This case study was done using R tidyverse package. Steps are:
1. Set up environments install package tidyverse and dplry for sorting and select.

       #an argument repos is added to the function that gives it the web address of the repository.
       install.packages("tidyverse", repos = "http://cran.us.r-project.org")
2. Load data. Save the data set into local file directory. change working directory to where the file is. load the data into data frame eurocup_soccer.
   
       setwd("C:/Users/liuch/OneDrive/Documents/DataAnalytics/Portfolio/case_study_2")
       eurocup_soccer <- read_csv("Euro_2012_stats_TEAM.csv")
3. After loading data, First take a glimpse

       glimpse(eurocup_soccer)
4. Start to analyze data. Check the final report for analyze results.


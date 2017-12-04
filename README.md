## Statistical Inference Final Project (GSS Survey -ANOVA)

This analysis is part of an online course on Inferential Statistics which I completed. The information for this analysis has been drawn from the the General Social Survey (http://gss.norc.org/About-The-GSS). The GSS survey asks respondents questions about their attitudes, behaviours and attributes. This survey has been carried out using face-to-face interviews. The sample was selected randomly, using a mapping system to cover a cross section of the nation. The mapping methodology is not detailed, but could affect the randomization.

Which group over the years forms the majority in terms of political views (liberal, conservative, etc.)? Is there a correlation between level of education and political views? Which group (separated by political views) has, on average, the highest number of completed years of education? Which group has completed the fewest? I have attempted to answer these questions in the project using ANOVA pairwise testing.


You will need to install R. It is also recommended that you install R Studio, and run both data file and code through R Studio. 

Install R: Go to https://cran.r-project.org/ and follow the link for your operating system.
Install RStudio: Go to https://www.rstudio.com/products/rstudio/download/ and click on the installer link for your operating system.


Also install the following packages and libraries in this sequence:

install.packages("devtools")
library(devtools)

install.packages("dplyr")
install.packages("rmarkdown")
install.packages("ggplot2")
install.packages("broom")
install.packages("gridExtra")
install.packages("shiny")
install.packages("cubature")
install.packages("dplyr")
install.packages("ggplot2")
install.packages("GGally")
install_github("StatsWithR/statsr")

Once you open R studio, load data file 'gss.Rdata'


# NYC Apartment Bayesian Regression Modeling

This is an individual research project, analyzing apartment sale trends across the five boroughs in New York City. With the New York City Property Sales Data, I aimed to explore how the property sale prices differ by borough. Property sale prices can be seen as a marker of economic strength and development potential, but they also betray economic disparities. Studying the differences in property sale prices can shed light on the gaps in development and help locate areas of inequality, so city officials and urban planners may allocate more funding to boost economic activity as well as provide support to low-income residents living in boroughs with high levels of inequality.

I hypothesized that property sale prices differ by borough. Specifically, I predicted that as the land square footage of properties increase, the rate at which the property sale prices increase differs by borough.

I fit Bayesian regression models for this analysis. Bayesian methods quantify uncertainy in the model using probability and simulation; they combine data with prior information, which usually comes from prior research on the subject, to make the coefficient estimates more stable. For this research challenge, I used default priors that are weakly informative (mean 0 and standard deviation 2.5 for all coefficients except the intercept) that come with the ‘rstanarm’ Bayesian modeling package. 

The detailed report contains my exploratory data analysis, Bayesian models, predictive checks, and recommendations for future work. The report and the accompanying code are stored in the folders. 

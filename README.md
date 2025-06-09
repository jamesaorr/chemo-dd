Data and code associated with the paper: "Density dependence revisited: strong evidence for superlinear population growth" by James A Orr, Kaleigh E Davis, Alicia H Williams, Jan Engelstadter, Daniel B Stouffer, and Andrew D Letten.

"data" folder contains the raw data used in this study: cfu, od, outflow, and chibio. It also contains the processed data that is used for plotting and modelling, the estimated Monod parameters for the E. coli strain used in our study (in the fits subfolder), and theoretical predictions based on consumer-resource theory (in the theory subfolder). 

`1-data-prep.Rmd` is an R notebook that combines and organises the different types of data from the different experiment replicates and saves the processed data into the data folder.

`2-supplementary-plots.Rmd` is an R notebook that uses the processed data to create a range of figures.

`3-supplementary-models.Rmd` is an R notebook that uses the processed data to fit a range of non-linear models to different subsets of the data.

`4-main-analysis.Rmd` is an R notebook that integrates our findings and previous empirical data from the Letten lab with consumer-resource theory. The models and figures found in the manuscript are generated in this notebook. 
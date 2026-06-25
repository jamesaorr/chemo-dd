Data and code associated with the paper: "Growth-density inversion in \textit{E. coli} reveals superlinear, not sublinear, density dependence" by James A Orr, Kaleigh E Davis, Alicia H Williams, Jan Engelstadter, Daniel B Stouffer, and Andrew D Letten.

"data" folder contains the raw data used in this study. It also contains the processed data that is used for modelling and plotting, the estimated Monod parameters for the E. coli strain used in our study (in the fits subfolder), and theoretical predictions based on consumer-resource theory (in the theory subfolder). 

`1-data-prep.Rmd` is an R notebook that combines and organises the different types of data from the different experiments and saves the processed data into the data folder.

`2-supplementary-plots.Rmd` is an R notebook that uses the processed data to create a range of supplementary figures.

`3-supplementary-models.Rmd` is an R notebook that uses the processed data to fit a range of supplementary models. 

`4-main-analysis.Rmd` is an R notebook that contains the code used to reproduce the models and figures found in the manuscript.
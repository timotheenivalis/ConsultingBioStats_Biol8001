The purpose of this assignment is for each student to select and begin to explore a published dataset that they find interesting. After these have been submitted/marked, you will form groups, and each group will select one of your datasets to analyse for your Major Project over the rest of the semester.
 

The final dataset that you choose should almost surely not be the first one you look at. To that end, please look at at least five candidate datasets, and choose the best of those.


There are two ways to find a dataset:


Start by searching for data on an online repository, check the data are well organized, then peruse the associated paper. Repositories include:

    https://datadryad.org/stash
    https://osf.io/
    https://zenodo.org/
    https://dataverse.harvard.edu/
    https://www.scidb.cn/en


Or, find a paper of interest that has open data, and then check the data is appropriate. Journals that often have good open data include:

    PLoS Computational Biology
    Proceedings of the Royal Society B

 
When you look at the data, you should think about how easy it will be to work with. You should consider:

    Are the data organized in a rectangular way (either in a csv, or appropriately in a spreadsheet)?
    Are all of the measurements/observations present, or are the data only summary statistics? (please choose data with the observations present)
    Are the columns named / organized in an understandable way?
    Can you identify one or more response variables?
    Are there a range of experimental, blocking, or observational factors? Are there many observations or multiple experiments?
    When you look at the figures in the paper, do you believe that the data contains all of the information necessary to reproduce them, if you wished to do this?

 
Once you have chosen a dataset, produce an Rmarkdown document that includes:

    A reference to the paper, and a link to the online location of the data. (1 point)
    A brief description of the purpose of the paper. (1 point)
    A brief description of how the data were obtained. (1 point)
    Read your chosen dataset into R. Demonstrate your data wrangling skills by filtering, selecting columns, sorting, creating new columns or summarising using group_by() / summarise(). (2 points)
    Produce at least 3 data visualisations relevant to the research question. Make sure to label axes and make use of colour palettes and themes as needed. Comment on the patterns you observe. (5 points)

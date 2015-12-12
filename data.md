# data-ecology
All of the ecology lessons use the same data set throughout. The data is tabular (rows and columns), similar in structure to what you might have in a spreadsheet. 

## The Portal Project Teaching Database

Available on FigShare: [http://figshare.com/articles/Portal_Project_Teaching_Database/1314459](http://figshare.com/articles/Portal_Project_Teaching_Database/1314459)

The data used in the ecology lessons is a time-series for a small mammal community
in southern Arizona. This is part of a project studying the effects of rodents
and ants on the plant community that has been running for almost 40 years. The
rodents are sampled on a series of 24 plots, with different experimental
manipulations controlling which rodents are allowed to access which plots.

This is a real dataset that has been used in over 100 publications. We've simplified
it just a little bit for the workshop, but you can download the full dataset and work
with it using exactly the same tools we'll learn about today.

Files we use in this dataset:

- [surveys.csv](http://files.figshare.com/1919744/surveys.csv) - the survey data  
Fields: record_id, month, day, year, plot_id, species_id, sex, hindfoot_length, weight
- [plots.csv](http://files.figshare.com/1919741/plots.csv) - information on plot number and type  
Fields: plot_id, plot_type
- [species.csv](http://files.figshare.com/1919741/species.csv) - information on species codes and scientific name  
Fields: species_id, genus, species, taxa
- [portal_mammals.sqlite](http://files.figshare.com/1919743/portal_mammals.sqlite) - database of survey, plots and species tables

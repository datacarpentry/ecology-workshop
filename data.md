---
title: Workshop Data
---

All of the ecology lessons use the same data set throughout. The data is tabular (rows and columns), similar in structure to what you might have in a spreadsheet.

## The Portal Project Teaching Database

Available on FigShare: [http://figshare.com/articles/Portal\_Project\_Teaching\_Database/1314459](https://figshare.com/articles/Portal_Project_Teaching_Database/1314459)

The data used in the ecology lessons is a time-series for a small mammal community
in southern Arizona. This is part of a project studying the effects of rodents
and ants on the plant community that has been running for almost 40 years. The
rodents are sampled on a series of 24 plots, with different experimental
manipulations controlling which rodents are allowed to access which plots.

This is a real dataset that has been used in over 100 publications. We've simplified
it just a little bit for the workshop, but you can download the full dataset and work
with it using exactly the same tools we'll learn about today.

::::::::::::::::::::::::::::::::::::::::::  prereq

## Portal Project Teaching Dataset

The Portal Project Teaching Database is a simplified version of the Portal Project Database designed for teaching. It provides a real world example of life-history, population, and ecological data, with sufficient complexity to teach many aspects of data analysis and management, but with many complexities removed to allow students to focus on the core ideas and skills being taught.

The database is currently available in csv, json, and sqlite.

This database is not designed for research as it intentionally removes some of the real-world complexities. The original database is published at [Ecological Archives](https://esapubs.org/archive/ecol/E090/118/) and this version of the database should be used for research purposes. The Python code used for converting the original database to this teach version is included as 'create\_portal\_teach\_dataset.py'. Suggested changes or additions to this dataset can be requested or contributed in the project GitHub repository [https://github.com/weecology/portal-teachingdb](https://github.com/weecology/portal-teachingdb).

**CITATION:** Ernest, Morgan; Brown, James; Valone, Thomas; White, Ethan P. (2017): Portal Project Teaching Database. figshare. [https://doi.org/10.6084/m9.figshare.1314459.v6](https://doi.org/10.6084/m9.figshare.1314459.v6)

::::::::::::::::::::::::::::::::::::::::::::::::::

Files we use in this dataset:

- [surveys.csv](https://ndownloader.figshare.com/files/2292172) - the survey data
  Fields: record\_id, month, day, year, plot\_id, species\_id, sex, hindfoot\_length, weight
- [plots.csv](https://ndownloader.figshare.com/files/3299474) - information on plot number and type
  Fields: plot\_id, plot\_type
- [species.csv](https://ndownloader.figshare.com/files/3299483) - information on species codes and scientific name
  Fields: species\_id, genus, species, taxa
- [portal\_mammals.sqlite](https://ndownloader.figshare.com/files/2292171) - database of survey, plots and species tables



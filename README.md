# Using Python for SQL queries

*Source: IBM Coursera course (cognitiveclass.ai)*

In this notebook I have utilized SQL queries to work with relational dataset on database server.

### Understand the datasets:
Three datasets that are available on the city of Chicago's Data Portal:

1. *Socioeconomic Indicators in Chicago*
This dataset contains a selection of six socioeconomic indicators of public health significance and a “hardship index,” for each Chicago community area, for the years 2008 – 2012.

A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2

2. *Chicago Public Schools*
This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year. This dataset is provided by the city of Chicago's Data Portal.

A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t

3. *Chicago Crime Data*
This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days.

A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

**Note: To analyze the data using SQL, it first needs to be stored in the database.**

While it is easier to read the dataset into a Pandas dataframe and then PERSIST it into the database, it results in mapping to default datatypes which may not be optimal for SQL querying. For example a long textual field may map to a CLOB instead of a VARCHAR.

*Acknowledgement*: cognitiveclass.ai

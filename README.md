# Ford Go Bike Analysis

## Table of contents
1. [Installation](#installation)
2. [Project Motivation](#projectmotivation)
3. [File Descriptions](#filedescriptions)
4. [Results](#results)
5. [Liscensing, Authors and Acknowledgements](#liscense)

### Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

### Project Motivation
In a world of ever-changing transportation technologies, the traditional method of driving a car from point A to point B isn't the only thing we can do anymore. Knowing how evident this change is, I have analysed Ford’s real world Go Bike data to answer bussiness questions which can help understand trends better. This analysis is meant to have more visual representations of the findings in order to convey these conclusions to the business & marketting teams. The link to the data are mentioned in the Licenses, Authors & Acknowledgements section below.

### File Descriptions
Ford-Go-Bike.ipynb - This jupyter notebook contains the python code used to read the data from a csv (comma seperated values) file, clean the data visually & programmatically & use various plots to visualize findings using univariate, bivariate & multi-variate plots.

### Results
The outcome of the analysis are as follows;
1. During the day, there are more trips in the morning & afternoon than the number of trips in the evening & night. 
2. The number of subscribers are greater than the number of active customers which use the bike service. Further investigation could be beneficial here as it might shed light as to what is causing the customers to subscribe only & not use the service. Causality is not determined in this analysis.
3. The number of male riders are 3 times greater than the number of female riders. This is true as can be found in [this](https://slate.com/human-interest/2014/09/gender-gap-alert-men-ride-bikes-way-more-than-women-do.html) article which states that in the U.S., 1 woman for every 3 men gets around on a bicycle. This could be related to why the number of female cyclers are also less & can be further investigated by pooling a few more datasets together.
4. The age group for most of the riders are between 30 to 40 years of age & the average duration of trips is around 10 minutes.
5. There is also a negative correlation between age & the duration of trips with the correlation coefficient not very strong indicating a week negative correlation. This may determine causality due to the fact that with an increase in age, there is a lower capacity to sit on a bike's seat for longer durations as it can get uncomfortable due to the lack of back & lumbar support.

### Licensing, Authors, Acknowledgements
This data is provided by Ford's GoBike project and is available for use [here](https://www.fordgobike.com/system-data).

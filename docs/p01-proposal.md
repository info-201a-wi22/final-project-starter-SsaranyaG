# Seattle Crime : Project Proposal

**Code name** : Happy neighborhoods    
**Project title** : Seattle Crime  
**Authors** : Alexander Valentino Evans (ave5@uw.edu), Saranya Gores (saranya@uw.edu), Noah Adam Hellyer (hellynoa@uw.edu), Ryan Trieu (dtrieu99@uw.edu)

**Affiliation** : INFO-201: Technical Foundations of Informatics - The Information School - University of Washington    
**Date** : Winter 2022  
**Abstract** :  We are interested in identifying trends within crime rates in Seattle. This is an important topic to understand because it can ultimately be used to influence policy that makes our lives safer. To address this question, we will utilize data collected over the past decade regarding crime rates in Seattle.  
**Keywords** :  Seattle crime, Violent Crime, Property Crime, Income by Location, Crime rate and Income

## 1.0 Introduction
Crime is an issue that many people deeply care about. Crime influences important issues such as our economy and political opinions. Crime rates can vary wildly between different neighborhoods within a city. As an example, downtown Seattle is known for having a higher rate of crime compared to the rest of the city. Our area of research for this project intends to dive deeply into crime data and understand trends that exist within that data. Additionally, we want to identify what kinds of correlations we can draw with crime from other data such as income rates. We will utilize two datasets containing crime and income data within Seattle neighborhoods over the past decade. Our goal is to capture meaningful information that Seattle politicians can utilize to make informed policy decisions that reduce crime in our city. We all would like to make Seattle a safer place to live.

## 2.0 Design Situation

**Framing**: The topic of concern is crime in Seattle. There are multiple elements making this topic, namely: crime types, crime rates, areas of crime, income. Moreover, there are several questions to be asked about:
- Does *income* have a causal relationship with *crime rates*?
- What are the *factors* of a neighborhood in Seattle that affect *crime rate* in that area?
- What are the most prominent *types of crime* in Seattle?

**Human values**: Our project concerns with moral values categorized into these factors: *Personal-sexual*, *Social Trust*, *Legal-illegal*, *Self-interest*, which are the moral factors discussed in the article _MORAL VALUES, SOCIAL TRUST AND INEQUALITY: Can Values Explain Crime?_ [^1] In this study, general measures of moral values and tolerances have little to no relationships with the covariants of crime, but a sub-set of *Self-interest* items offer some explanations. *Self-interest* values directly associates with crime rates at national levels. Surprisingly, *Standard of Living* and *Social Trust* was not found to be responsible for crime rates, rather, they offered to be conditions for the variance of crime in difference settings.

**Stakeholders**: Our project is open to the public, therefore citizens, politicians, journalists, law practitioners get access to our data. These individuals then can help influence the policies and laws to make people' lives safer. Internally, the criminal justice system includes those who are responsible for enforcing and interpreting the law. Internal stakeholders of the criminal justice system could potentially include persons who are suspected of crimes and convicted. Externally, the media, groups that serve victims of crime, families, businesses, school and society can be impacted. [^3] People who consume media that use our project's
data can be influenced by the media' narratives. Similarly, people who are influenced by the politicians' and law practitioners' interpretations of our data can have a different viewpoint about these crimes and the elements surrounding them.

**Benefits and Harms**: In general, since these data about crimes are unbiased,
the public are expected to have an objective and more comprehensive view of the crimes, the income, and the direct stakeholders. Law enforcement can better make a case to acquire these resources needed to fight crime. [^2] Crime-fighting problems can be addressed to find solutions.  On the other hand, direct stakeholders can misinterpret the data in order to spread mis/disinformation for unethical/selfish motives. Insufficient data could also cause data errors that shape the results in unintentional ways. Moreover, social media can have a bias view of this data, representing a false narrative of crime data. This following figure shows the difference between frequencies of different types of crimes against crime-related tweets. [^4]

![`ALT` Observed frequency of different types of crime against crime-related tweets.](/images/crime-tweet.jpg)


## 3.0 Research questions
Our questions revolve around identifying trends in crime rates within Seattle. The questions that we want to explore are:
 - What _types_ of crime are the most common in Seattle?
 - How have the crime rates _changed_ over the decade?
 - How does the crime rate _differ_ between neighborhoods within Seattle?
 - What _areas_ of Seattle have the highest crime rates?
 - What is the _relationship_ between income and crime rates in Seattle?  

We will address these questions by creating visualizations of crime rates over the different neighborhoods within the city. The answer to these questions will help us understand whether crime in Seattle is improving or getting worse. We can compare trends within different neighborhoods to identify which neighborhoods handle crime better than others. We want to see if a correlation exists between crime rates and income rates within Seattle.

## 4.0 The Dataset
The datasets that we chose to analyze are crime data in Seattle that ranges from 2008 to present and then data about Seattle's household income that has average household income by location from 2013 to 2019.
### Data set size and complexity
The data consists of 2 csv files with the crime data having 950,000 observations and 17 columns and the income data having 915 observations and 8 columns.
### Data Provenance
For both data sets the data being represented is based off of the population in King County for a given year. Observations in the crime data set are represented by a report number and broken down into the time the crime took place, location, and offense. The observations of the income data are broken down into year, average household income, and location. The crime data was collected and maintained by Seattle Police Department until May 2019 when the preservation and upkeep of the data moved to the National Incident-Based Reporting System (NIBRS). The main purpose of this data is to obviously keep track of crimes in Seattle for keeping records but also beneficial to understand more about crime in Seattle when it is represented in such a large dataset. This data benefits the people of Seattle and the United States as a whole because it represents how crime has evolved and changed in the last 14 years and allows us to determine if we are making a meaningful difference at combating crime and if not where we can improve. The income by location data we found is presented by DATAUSA but originated from the U.S. Census Bureau. The purpose of the income by location dataset is to understand how Seattle’s income has evolved over the years and also to compare different parts of Seattle. The data alone doesn’t necessarily benefit anyone in particular but is useful to understand the trend of our economy and shows how certain areas of Seattle are more expensive than others. Overall both of these datasets should be considered credible and trustworthy because they originate from government agencies.

## 5.0 Expected Implications
Answering the research questions would create implications for a lot of important settings. Technologists, designers and policymakers could make many implications based on our topic answers. An implication that might come up based on our research and our topic is that crime rates are or are not affected by income levels. Technologists finding a way to use more advanced technology to lower crime rates would be very effective and has been very effective for other cities. A designer creating a better built environment with better takes on zoning, designs of streets and housing, locations of public transit, and land uses would shape the built environment in ways that could possibly reduce crime. A policymaker could help lower crime rates by creating more incentives for people who need treatment or vocational programs in prison so when they get out they have something to look forward to instead of doing something to get them back in jail.  


## 6.0 Limitations
There are many limitations when it comes to research on certain topics, especially when they might be specific to a smaller group. Some limitations that could very possibly come up that could have to do with our topic is a lack of data. Since our topic is specific to one city instead of a state or even the world, there could be a shortage of data we can actually find, which could also lead to a lack of sample sizes for the important information we need to collect for our specific topic. Also data that is being reported based on one's self could also be a problem, as everyone has biases when it comes to race and culture, other things take place when people try to give out information in these situations like having selective memory, telescoping, attribution, or exaggeration. Problems like prior research and time constraint would be based on our dedication to getting our work complete.

## Acknowledgements
We have no acknowledgements at this time.

## Appendix A : Questions
We don't have any questions at this time.

## References

[^1]: [Halpern, D. (2001). MORAL VALUES, SOCIAL TRUST AND INEQUALITY: Can Values Explain Crime? The British Journal of Criminology, 41(2), 236–251.]( http://www.jstor.org/stable/23638820) .

[^2]: [The benefits of criminal justice data: Beyond policing](https://sunlightfoundation.com/2015/05/01/the-benefits-of-criminal-justice-data-beyond-policing/) .

[^3]: [Identifying Criminal Justice Stakeholders](https://study.com/academy/lesson/identifying-criminal-justice-stakeholders.html#:~:text=Internal%20stakeholders%20include%20police%20officers,court%20personnel%2C%20and%20other%20individuals.) .

[^4]: [Prieto Curiel, R., Cresci, S., Muntean, C.I. et al. Crime and its fear in social media. Palgrave Commun 6, 57 (2020). ](https://doi.org/10.1057/s41599-020-0430-7)

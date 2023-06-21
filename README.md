# UofWProject1

1.	Are there trends in job satisfaction geographically? (the one I am answering)

    What we have found in the provincial data is a rather weak relationship between province and satisfaction level.

    ![Satisfaction percentages by province](canada_project/results/province_bar_percent.png)
    Satisfaction percentages by province
    
    
    Doing some statistical analysis to verify if this data set is to be met with caution, we have the following:
    The actual reported numbers in the values column for "persons" counts, as they are by units of 1000s, represent a little over half the population of Canade as of 2016, thus population representation is not something to worry
    The way data is represented as bulk values, as well as the fact that there are only 3 qualitative responses, indicate that there is not much that can be done from a regressive state of analysis
    Due to previous point mentioned, normality and homogeneity of variance (independence in this case) would be hard to find, yet we decided to test them, at least on one the first variable set.

    With all that said, a hypothesis test was done twice on these variables. The null hypothesis is this: the various geographic divisions of Canada have no bearing on job satisfaction levels. The p-values tested on an alpha of 0.05 with the anova one-way test have shown both the general response and the responses of only satifaction are statistically significant, being both less than 0.001, thus initially there would seem to be an impact on data. 
    These would be the following: British Columbia on Prince Edward Island: New Brunswick on Ontario, Newfoundland and Labrador on Ontario, Ontario on Prince Edward Island, and Ontario on Saskatchewan. While the sheer number of appearances Ontario has in significance, it does not compare to the majority of the data. Aside from this, the appearances are to be taken with caution as there is not normality present in this data set.

    The implications of this are very diverse, but two come to mind. One is that Canada is politically unified enough that no one political region has a significant benefit or hinderance to the others in relation to the labor force. The second is that there is a generally steady flow of employment opportunities present throughout Canada, as the satisfaction levels are all greater than 70% but less than 95%.

2.	Is there a correlation between gender and job satisfaction?
3.	Does age have an impact on job satisfaction?

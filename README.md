A non-governmental organization called HELP plans to allocate its humanitarian aid to the countries that need it the most. For this purpose, it has provided a data set that includes information related to the social, economic and health factors so that the level of development of each country can be examined in general. Therefore, the goal of the problem is to correctly cluster the set of countries according to the information available in the data and their level of development. The descriptions of the data columns are as follows.
• country: Name of the country
• child_mort: Death of children under 5 years of age per 1000 live births
• exports: Exports of goods and services per capita. Given as age of the GDP per capita
• health: Total health spending per capita. Given as age of GDP per capita
• imports: Imports of goods and services per capita. Given as age of the GDP per capita
• Income: Net income per person
• Inflation: The measurement of the annual growth rate of the Total GDP
• life_expec: The average number of years a newborn child would live if the current mortality patterns are to remain
the same
• total_fer: The number of children that would be born to each woman if the current age-fertility rates remain the
same
• gdpp: The GDP per capita. Calculated as the Total GDP divided by the total population
In this project, methods K-means, GMM and Spectral Clustering have been used for clustering, and method Spectral Clustering has been implemented manually. The optimal selection criterion for the number of clusters was elbow and silhouette.

Tool used for analysis - RapidMiner Student Edition

---

# Cost of living 2022

1. Data preparation

The data preparation phase of CRISP-DM aims to transform the raw data into a format that is suitable and ready for the data mining project, and to improve the quality and reliability of the data

In this case, the data preparation phase involves the following steps:

- Selecting the data: The data selection step involves choosing the relevant and appropriate data for the data mining project, based on the data mining problem definition and the data understanding results. The data selection step also involves defining the criteria and methods for selecting the data, such as the scope, granularity, and level of detail of the data, the inclusion and exclusion of the data, the sampling and partitioning of the data, etc. In this case, the data selection step involves selecting the cost of living 2022 dataset from Kaggle, which contains 4898 cities and 59 attributes related to the cost of living, quality of life, health care, etc. The data selection step also involves selecting the relevant attributes for the data mining project, such as the cost of living index, the rent index, the groceries index, the restaurant price index, etc. The data selection step also involves selecting the target variable for the data mining project, which is the development status of the cities, based on the human development index (HDI)
- Cleaning the data: The data cleaning step involves detecting and correcting the errors and inconsistencies in the data, such as the missing values, outliers, noise, duplicates, biases, etc. The data cleaning step also involves defining the criteria and methods for cleaning the data, such as the rules and thresholds for identifying and handling the errors and inconsistencies, the techniques and tools for cleaning the data, the verification and validation of the cleaning results, etc. In this case, the data cleaning step involves handling the missing values in the cost of living 2022 dataset, which occur when there is no data stored for certain cities or attributes. The data cleaning step also involves using the average of each country to fill the gaps for the missing values, and removing the rest of the examples with missing values. The data cleaning step also involves using pandas, a Python library for data analysis, to fill the missing values, and using RapidMiner, a software tool for data mining, machine learning, and analytics, to perform the rest of the data cleaning process 

Constructing the data: The data construction step involves creating and adding new data or features to the existing data, such as the derived attributes, the aggregated attributes, the generated attributes, etc. The data construction step also involves defining the criteria and methods for constructing the data, such as the rules and formulas for creating and adding the new data or features, the techniques and tools for constructing the data, the verification and validation of the construction results, etc. In this case, the data construction step involves creating and adding new attributes to the cost of living 2022 dataset, such as the region, the subregion, the HDI, the gini index, the essentials (sum of essential attributes), the time required to buy a vw car, and the time required to buy an 85sqm apartment. The data construction step also involves using a left join operation to merge the cost of living 2022 dataset with other datasets that contain the new attributes, such as the world development indicators dataset, the world happiness report dataset, and the cost of living dataset from Numbeo. The data construction step also involves using pandas and RapidMiner to create and add the new attributes.

- Integrating the data: The data integration step involves combining and merging the data from different sources and formats into a single and consistent data set, such as the relational databases, the flat files, the web pages, the text documents, the images, the videos, etc. The data integration step also involves defining the criteria and methods for integrating the data, such as the rules and techniques for identifying and resolving the conflicts and redundancies in the data, the methods and tools for integrating the data, the verification and validation of the integration results, etc. In this case, the data integration step involves integrating the cost of living 2022 dataset with the other datasets that contain the new attributes, such as the world development indicators dataset, the world happiness report dataset, and the cost of living dataset from Numbeo. The data integration step also involves using a left join operation to merge the datasets based on the common key, which is the city name. The data integration step also involves using pandas and RapidMiner to perform the data integration process.
- Formatting the data: The data formatting step involves transforming and converting the data into a standard and uniform format that is suitable and ready for the data mining project, such as the data type, the data structure, the data format, the data encoding, the data scale, the data unit, etc. The data formatting step also involves defining the criteria and methods for formatting the data, such as the rules and techniques for transforming and converting the data, the methods and tools for formatting the data, the verification and validation of the formatting results, etc. In this case, the data formatting step involves formatting the cost of living 2022 dataset into a standard and uniform format that is suitable and ready for the data mining project, such as the numeric data type, the tabular data structure, the csv data format, the utf-8 data encoding, the ratio data scale, the US dollar data unit, etc. The data formatting step also involves using pandas and RapidMiner to perform the data formatting process.
  ![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.001.png)



2. Data modelling

Data modeling is the process of creating and applying a mathematical and statistical representation of the data, such as the algorithms, the techniques, the methods, the parameters, the assumptions, the constraints, etc., to discover and extract the patterns, the relationships, the insights, the knowledge, etc., from the data, and to solve the data mining problem, such as the classification, the regression, the clustering, the association, the anomaly detection, etc. (Shearer, 2000).

These models are used:

1. A decision tree is a machine learning algorithm that uses a tree-like structure to classify or regress data based on a series of rules or questions. Each node in the tree represents a test or a condition on a feature, and each branch represents an outcome or a decision. The leaf nodes represent the final class or value of the data. Decision trees are easy to interpret and visualize, but they can suffer from overfitting, instability and bias.
1. A random forest is a machine learning algorithm that uses an ensemble of decision trees to improve the accuracy and robustness of the prediction. Each decision tree in the random forest is trained on a random subset of the data and features, and the final prediction is obtained by averaging or voting the predictions of all the trees. Random forests can handle large and complex data sets, but they can be slow, memory-intensive and hard to explain. 
1. K-nn, or k-nearest neighbors, is a machine learning algorithm that uses the similarity or distance between the data points to classify or regress new data. For a given data point, the algorithm finds the k closest or most similar data points in the training set, and assigns the class or value based on the majority or average of the k neighbors. K-nn is simple, flexible and non-parametric, but it can be computationally expensive, sensitive to noise and irrelevant features, and affected by the choice of k. 
1. Naive bayes is a machine learning algorithm that uses the Bayes’ theorem and the assumption of conditional independence to calculate the probability of a class given the features of the data. The algorithm multiplies the prior probability of the class and the likelihood of the features given the class, and chooses the class with the highest posterior probability. Naive bayes is fast, efficient and scalable, but it can be inaccurate, unrealistic and biased. 

3. Descriptive analytics

Descriptive analytics is the process of summarizing and visualizing the data to describe and understand the characteristics and patterns of the data, such as the distribution, the frequency, the mean, the median, the mode, the standard deviation, the correlation, the outliers, etc. Descriptive analytics can help to explore and analyze the data, and to communicate and present the findings and insights from the data. 

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.002.png)

3.1 Correlation

Correlation is a statistical measure that indicates the strength and direction of the linear relationship between two variables, such as the cost of living index and the HDI. Correlation can help to identify and analyze the associations and dependencies between the variables, and to infer and predict the values of one variable based on the values of another variable. Correlation can range from -1 to 1, where -1 means a perfect negative correlation, 0 means no correlation, and 1 means a perfect positive correlation. Correlation can be calculated using various methods, such as the Pearson correlation coefficient, the Spearman rank correlation coefficient, the Kendall rank correlation coefficient, etc. Correlation can be visualized using various plots, such as the scatter plot, the line plot, the heat map, etc.

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.003.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.004.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.005.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.006.png)

3.2 Exploration by continents

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.007.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.008.png)


3.2.1 Africa

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.009.png)

Niger is a landlocked country in West Africa that is one of the poorest and least developed countries in the world. The cost of living in Niger is relatively high compared to its low income and human development index. According to Numbeo (2023), the average monthly net salary in Niger is **$146**, while the average monthly rent for a one-bedroom apartment in the city centre is **$200**. The prices of food, transportation, utilities and other goods and services are also high due to inflation, import dependence, corruption and insecurity. The cost of living in Niger is a major challenge for its population of over 24 million people, most of whom live in rural areas and depend on subsistence farming and livestock rearing.

3.2.2 America

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.010.png)

In the above graph, it is clear that in the North American continent, the cost of essentials, average salary, and the HDI index have the highest peak in the United States of America. It indicates that the higher the HDI index, the higher the average salary in an area. 

3.2.3 Europe

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.011.png)

The graph above suggests that in the European continent, the cost of essentials and the average monthly salary is the highest in Switzerland. This correlates with the other research and data that suggests that Switzerland is the most expensive country to live in in the EU region.

3.2.4 Asia
![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.012.png)

The graph above reflects that in the Asian continent, the cost of essentials is the highest in Singapore, more than the average monthly salary. In Hong Kong, the cost of essentials is also considerably higher than the average monthly salary. Interesting to note here that the average monthly salary is the highest in the Qatar region. 

3.2.5 Oceania

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.013.png)

In the Oceanic continent, the cost of essentials is the highest in Papua New Guinea, with Australia and New Zealand, showing high peaks in average monthly salary and high HDI index. 

The cost of essentials in Papua New Guinea is high because the cost of living in Papua New Guinea is high. According to Expatistan (2023), Papua New Guinea has a **Cost of Living Index** of **134**, which means that living there is **34% more expensive** than living in Prague, the central reference city. Some of the factors that contribute to the high cost of living in Papua New Guinea are:

- The complicated customary land title system, which means the price of land is high.
- The high import costs and taxes, which increase the prices of goods and services.
- The low supply and high demand of housing, especially in urban areas, which drive up the rents and mortgages.
- The lack of infrastructure and public services, which affect the quality and availability of water, electricity, health, education, etc.
- The high crime and security risks, which require extra precautions and expenses for safety and protection.

3.3 Exploration by subregions

Then, to comparison across sub-regions. 

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.014.png)

The image shows the sub-regional comparison process in Rapid Miner

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.015.png)

From the above graph, we can conclude that In Northern America, Australia, and New Zealand, the average monthly salary is the highest with high peaks of the HDI index- this finding is consistent with the fact that the higher the HDI index in a region, that is, high skilled labor force earns higher composition. Interesting to note here that the Melanesia region reflects a high cost of essentials, higher than any subregion. 

The cost of essentials in Melanesia is high because the cost of living in Melanesia is high. Melanesia is a region in the South Pacific that includes the countries of Papua New Guinea, Fiji, Solomon Islands, Vanuatu and New Caledonia. The cost of living in Melanesia varies depending on the country, but some of the factors that contribute to the high cost of living in Melanesia are:

- The lack of adequate healthcare facilities and services, which means that expats may need to use private hospitals or travel abroad for medical treatment.
- The high import costs and taxes, which increase the prices of goods and services, especially food, as most of the land is not suitable for cultivation.
- The low supply and high demand of housing, especially in urban areas, which drive up the rents and mortgages.
- The high crime and security risks, which require extra precautions and expenses for safety and protection.
- The high prevalence of chronic diseases, which affect the health and well-being of older people of color, who face the highest costs for getting sick.


3.4 Least and most expensive cities

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.016.png)


![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.017.png)

Kermanshah is showing highest cost of living due to abnormal apartment rent cost in the dataset. The apartment rent cost in Kermanshah is based on the location, size, quality and amenities of the apartment. The average monthly rent for an 800 sq. ft. apartment in Kermanshah is between $152 and $248, depending on the location. The apartment rent cost for an 800 sq. ft. apartment in Kermanshah would not be $12,000, unless the apartment is very special or the landlord is very greedy.

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.018.png)

 
3.5 Time required to buy car or apartment

Finally, we ran a prediction to determine the required time to be able to purchase an 85sq meter apartment or a Volkswagen car.

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.019.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.020.png)



![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.021.png)


![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.022.png)



![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.023.png)




4. Predictive analytics

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.024.png)

4.1 Decision tree

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.025.png)

Average monthly salary was selected as label. Maximum depth was set to 5

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.026.png)

Tree indicates that apartment rent cost and preschool cost are the most important after HDI.

4.2 Naive bayes

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.027.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.028.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.029.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.030.png)

**Performance Vector**

accuracy: 92.46% +/- 1.27% (micro average: 92.46%)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	2896	27

Not Developed:	327	1443

precision: 81.62% +/- 2.88% (micro average: 81.53%) (positive class: Not Developed)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	2896	27

Not Developed:	327	1443

recall: 98.16% +/- 0.79% (micro average: 98.16%) (positive class: Not Developed)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	2896	27

Not Developed:	327	1443

AUC (optimistic): 0.990 +/- 0.005 (micro average: 0.990) (positive class: Not Developed)

AUC: 0.990 +/- 0.005 (micro average: 0.990) (positive class: Not Developed)

AUC (pessimistic): 0.990 +/- 0.005 (micro average: 0.990) (positive class: Not Developed)


4.3 Random Forest

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.031.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.032.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.033.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.034.png)

PerformanceVector:

accuracy: 99.55% +/- 0.27% (micro average: 99.55%)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	3211	9

Not Developed:	12	1461

precision: 99.19% +/- 0.69% (micro average: 99.19%) (positive class: Not Developed)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	3211	9

Not Developed:	12	1461

recall: 99.39% +/- 0.75% (micro average: 99.39%) (positive class: Not Developed)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	3211	9

Not Developed:	12	1461

AUC (optimistic): 1.000 +/- 0.000 (micro average: 1.000) (positive class: Not Developed)

AUC: 1.000 +/- 0.000 (micro average: 1.000) (positive class: Not Developed)

AUC (pessimistic): 1.000 +/- 0.000 (micro average: 1.000) (positive class: Not Developed)

4.4 K-NN

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.035.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.036.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.037.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.038.png)

PerformanceVector:

accuracy: 87.24% +/- 1.57% (micro average: 87.24%)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	2944	320

Not Developed:	279	1150

precision: 80.53% +/- 2.74% (micro average: 80.48%) (positive class: Not Developed)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	2944	320

Not Developed:	279	1150

recall: 78.23% +/- 3.68% (micro average: 78.23%) (positive class: Not Developed)

ConfusionMatrix:

True:	Developed	Not Developed

Developed:	2944	320

Not Developed:	279	1150

AUC (optimistic): 0.950 +/- 0.009 (micro average: 0.950) (positive class: Not Developed)

AUC: 0.925 +/- 0.016 (micro average: 0.925) (positive class: Not Developed)

AUC (pessimistic): 0.904 +/- 0.025 (micro average: 0.904) (positive class: Not Developed)

4.5 Compare ROCs

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.039.png)

![](Aspose.Words.aacf8ed5-b6c0-45c6-96ef-b1789c81a9d3.040.png)

From this graph, K-NN has the worst prediction accuracy out of 3 models. Random forest is the most accurate followed by the naive Bayes model. Although for a small range, Naive Bayes is the most accurate among the three.

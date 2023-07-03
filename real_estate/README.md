# Analysis of Real Estate Advertisements

[Notebook Preview](https://nbviewer.org/github/ootho/data_analysis/blob/main/real_estate/real_estate.ipynb)

## Objective and Research Goals

We have access to data from the Yandex.Real Estate service, which includes a collection of advertisements for the sale of apartments in St. Petersburg and neighboring areas over several years. The objective of this research is to determine the market value of real estate properties.

For each apartment listing, two types of data are available. The first type is provided by the user, while the second type is automatically generated based on cartographic data. For example, it includes information such as distance to the city center, airport, nearest park, and water bodies.

## Conclusion

During the data preprocessing stage, the following operations were performed:
- Data type conversion
- Identification and removal of duplicates
- Handling missing values
- Correction and interpretation of anomalous data

New columns with calculated data were added, which were subsequently used in the analysis. In the exploratory data analysis stage, the main parameters of the properties and the time it took for properties to be sold were studied and interpreted.

During the final stage, dependencies between various parameters of the properties and their prices were discovered. The correlation between the property prices and the distance to the city center was also examined. The most significant findings include the identification of correlations between price and the following parameters: total area, living area, kitchen area, number of rooms, and distance to the city center.

The results of this analysis can be valuable for evaluating deviations in property prices from the market averages, assessing new real estate properties, and building a recommendation system for property valuation.
# IMO Country Rankings Prediction using Deep Neural Networks

## Introduction
The purpose of this project is to predict the ranking of the countries in the International Mathematical Olympiad (IMO) 2020. The ranking of the countries in the IMO is significant as it reflects the relative comparison of the country's mathematical education with others and can be used to justify the spent money on education by the country officials. This ranking can also serve as a motivation for high school students to excel in their education and compete with the best students of other countries.

## Methodology
The dataset was obtained by parsing IMO websites and collecting information about the countries, including the ranking of the past 10 years. The dataset consisted of numerical variables such as first participation, participation, all, males, dist, avg.persis, gold, silver, bronze, honor mention, budget per capita, population density, and ranking from 2010 to 2019. The data was preprocessed by cleaning and converting it to integer and float types. The max-min normalization method was used to overcome quick overfitting and variations in inputs.

The Deep Neural Networks model was trained on 70% of the data, and 15% each was used for validation and testing. The data was randomly split into training, validation, and test datasets using the 70/15/15 principle. Three dataset classes and custom modules were created, including linear regression, shallow neural network, and deep neural network modules.

## Results and Conclusion
The results of this project showed that Deep Neural Networks can effectively predict the ranking of the countries in the IMO. The implementation of max-min normalization and the use of custom modules for linear regression, shallow neural network, and deep neural network improved the performance of the model. The project highlights the importance of considering the ranking of the countries in the IMO, as it has practical usage and can play a significant role in determining the progress rate of the country in general.

In conclusion, this project serves as a continuation of the previous study, where the common belief about the giftedness of Asian children in science subjects was investigated, and population density was found to play a significant role compared to budget per capita. The findings of this study contribute to the understanding of the mathematical education of the countries and provide insights into the ranking of the countries in the IMO.




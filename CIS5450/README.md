# Global Temperature Forecasting & Investigation
This project is for the course *CIS5450: Big Data Analytics (Spring 2023)*. 

## Abstract
Accurate temperature forcasting and tracking of climate change and global 
warming is vital since extreme temperature trends can, among other things, 
adversely affect agriculture and public health. Predicting future trends, 
understanding differences between regions, and investigating the factors that 
affect temperature can help countries better prepare for the consequences of 
climate change and global warming.

In this project we aim to investigate and visualize the patterns of temperature 
change for different regions across the world. To better understand the factors 
that affect temperature, we also aim to investigate the impact on temperature of 
potentially related development indicators. Finally, we build temperature 
forecasting models based on traditional (SARIMA) and deep learning (RNN, LSTM, 
GRU) methods, and compare the performances of our models on test data. For the 
modeling we focus specifically on United States (US) country-level and 
state-level temperature data.

To achieve our objectives, we have used the [Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data?select=GlobalLandTemperaturesByCountry.csv) 
dataset from Kaggle. The dataset contains earth surface temperature data and is 
a repackaging of a compilation put together by Berkeley Earth, which is 
affiliated with Lawrence Berkeley National Laboratory. The dataset allows for 
slicing into interesting subsets, including at the global-level, country-level, 
state-level and city-level. To understand the factors that affect temperature, 
we join the dataset with the [World Development Indicators](https://www.kaggle.com/datasets/kaggle/world-development-indicators?select=Indicators.csv) dataset from Kaggle. The 
dataset is from the World Bank and contains over a thousand annual indicators of 
economic development from hundreds of countries around the world.

## Contributors
- Andrew Wang
- Randy Chou
- Rohan Saraogi
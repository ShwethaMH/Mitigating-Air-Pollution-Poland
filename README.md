# Omdena-Mitigating-Air-Pollution-Poland

### INTRODUCTION
Air pollution is a growing concern in Poland, with the country consistently ranking among the
countries with the worst air quality in Europe. This poor air quality not only affects the health and
well-being of the population, but also puts a strain on the healthcare system. In order to address
this issue, it is important to identify the main factors contributing to air pollution in Poland and to
develop an effective tool for predicting air quality.

### Project Summary
The aim of this project was to investigate the primary factors responsible for air pollution in Poland and develop an effective tool to predict air quality. To achieve this, three datasets were utilized: daily air quality data, daily weather data, and Static annual data from the Polish Central Statistical Office, all from 2017 to 2021. The annual data provided information on various features related to human acitivities, such as area by land use, crop production, emission of particulates and pollutant gases, forest area and fires, population density, production of electricity, vehicle types, and air pollution reduction systems. To achieve the project's objectives, a methodology was adopted, which involved translating and cleaning the data, combining data from different years and pollutants, followed by data analysis and machine learning. The cleaned datasets were analyzed to identify the key factors contributing to air pollution in Poland.

The results revealed that the concentration of pollutants varies during different times of the year. PM10 and PM2.5 are primarily emitted from sources such as solid fuel combustion, road traffic, dust from construction sites, and agricultural activities. Industrial plants such as coking plants, steel mills, and coal-fired power plants are also significant sources of air pollution in many places in Poland. NO2 is primarily emitted from combustion processes in energy production, manufacturing industry, and road transport, with diesel engines being a significant contributor to nitrogen oxide emissions. O3 is a secondary pollutant formed by the influence of solar radiation on a combination of airborne pollutants, including NOx and VOCs.

To standardize the measurement of air quality and communicate it to the public, the Common Air Quality Index (CAQI) was used. It considers various pollutants, including PM10, PM2.5, O$_3$, NO$_2$, and SO$_2$, and assigns a value to indicate the level of air pollution. The CAQI levels are higher during weekdays and lower during weekends, potentially indicating that weekly pollutant concentrations depend on human activities.

The dataset was preprocessed, and two datasets were created for training classification and regression models. Various techniques, including feature engineering, feature selection, cross-validation, and hyperparameter optimization, were utilized. A range of models were trained and tested to predict CAQI classes and indexes, and their performance was evaluated using metrics such as F1 score and RMSE. Finally, an XGBoost regressor model was used to forecast future CAQI levels of Warsaw, and the model’s short-term forecasts was really close to the actual CAQI levels for the forecasting period.

Daily monitoring and recording of the various features that affect air quality in Poland can play a significant role in identifying the overall air quality levels. By analyzing and interpreting such data, policymakers and stakeholders can gain valuable insights into the trends and patterns of air pollution in the region. This information can help them identify areas of concern and take appropriate actions to mitigate the impact of air pollution on public health and the environment. Overall, a data-driven approach to air quality monitoring and policymaking can contribute significantly to creating a healthier and sustainable environment in Poland.

### Data Sources
We used publicly available data sources:

Local time-resolved (daily) air quality data: from Chief Inspectorate for Environmental Protection (https://powietrze.gios.gov.pl/pjp/archives) - in Polish

Local time-resolved (daily) weather data: from European Climate Assessment and Dataset (ECAD) project (https://www.ecad.eu/) - in English

Local annual data of contributing factors: from GUS - BDL (https://bdl.stat.gov.pl/bdl/start) - in English


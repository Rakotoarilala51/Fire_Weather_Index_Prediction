# Fire_Weather_Index_Prediction

This repository contains a machine learning model built using **scikit-learn** to predict the Fire Weather Index (FWI) based on various meteorological and environmental factors. The dataset includes columns such as day, month, year, temperature, relative humidity (RH), wind speed (WS), rain, and several indices (FFMC, DMC, DC, ISI, BUI). The model aims to predict the FWI, which is crucial for wildfire risk assessment.

## Dataset

The dataset contains the following columns:

- **jour**: Day of the observation.
- **mois**: Month of the observation.
- **année**: Year of the observation.
- **temperature**: Temperature in Celsius.
- **rh**: Relative Humidity (%) - The percentage of moisture in the air.
- **ws**: Wind Speed (km/h).
- **rain**: Rainfall (mm).
- **ffmc**: Fine Fuel Moisture Code - Represents moisture content in fine fuels.
- **dmc**: Duff Moisture Code - Represents moisture in the duff (organic material on the forest floor).
- **dc**: Drought Code - Indicates long-term drying trends in the forest.
- **isi**: Initial Spread Index - Reflects the rate of fire spread in fine fuels.
- **bui**: Build Up Index - Reflects the amount of fuel available for combustion.
- **fwi**: Fire Weather Index - The target variable for the prediction model.
- **classe**: Class label (Feu ou Pas Feu) indicating if a fire occurred or not.

## Objective

The goal is to create a machine learning model using **scikit-learn** that predicts the **FWI** based on the features from the dataset. The FWI is a crucial metric used to evaluate fire risk, and predicting it accurately can aid in fire prevention and response strategies.

## Setup and Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Rakotoarilala51/Fire_Weather_Index_Prediction.git
   cd Fire_Weather_Index_Prediction


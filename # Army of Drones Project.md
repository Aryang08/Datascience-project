# Army of Drones Project

## Overview
The **Army of Drones** is a collaborative initiative between the General Staff of the Armed Forces, the State Special Communications Service, and the Ministry of Digital Transformation. This project focuses on analyzing and predicting personnel losses caused by Russian drones since the summer of 2023. 

### Project Details
The dataset includes only Russian losses (Equipment & Death Toll) attributable to the project drones. Losses inflicted by other drones are not included. The input data comprises a set of images provided weekly (sometimes bi-weekly) by officials from various sources, all stored in the `images` folder. 

All information extracted from these images has been compiled into the `russia_losse.csv` file, which details the following losses:
- Armored Personnel Vehicles (APV)
- Ammunition/Fuel Depots
- Anti-Aircraft Warfare Systems
- Cannons
- Multiple Rocket Launchers (MRL)
- Mortar/Anti-Tank Guided Missiles/Machine Guns
- Radio Equipment
- Self-Propelled Artillery
- Strongpoints
- Tanks
- Vehicles
- Personnel

## Related Datasets
- **2022 Russia-Ukraine War**: Updated weekly, JSON format on GitHub (updated daily) - the Russia Equipment and Personnel losses.
- **Massive Missile Attacks on Ukraine**: Updated weekly - information about launched and shot down missiles and drones during Russian strikes on infrastructure since October 2022.
- **2022 Ukraine-Russia War Losses**: Oryx + Images (updated quarterly) - Equipment losses based on Oryx investigations.
- **Russian Navy**: Details on surface combatants, submarines, littoral warfare ships, rescue, and auxiliary ships lost during the 2022 Russian invasion of Ukraine.
- **Social Media Athletes from Russia & Belarus**: Information about athletes from these countries who participated in the Beijing 2022 Olympic Winter Games.

## Methodology
To predict total personnel losses, multiple regression models have been utilized to ensure accuracy. Additionally, the ARIMA (AutoRegressive Integrated Moving Average) model has been applied to forecast based on previous data. The development environment for this project is Jupyter Notebook, and Python is used for implementing the AI/ML models.

## Usage
1. Clone this repository or download the dataset{https://www.kaggle.com/datasets/piterfm/the-army-of-drones}.
2. Ensure you have the required libraries installed (e.g., `pandas`, `numpy`, `statsmodels`).
3. Run the Jupyter Notebook to analyze and visualize the data.
4. Utilize the regression models and ARIMA for predictions and forecasts.

## Acknowledgements
- General Staff of the Armed Forces
- State Special Communications Service
- Ministry of Digital Transformation

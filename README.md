# PEOWT - Power Generation

## Project Overview

This project focuses on predicting the electrical energy output of wind turbines using historical weather data and turbine operational parameters. Accurate prediction of wind energy output is crucial for efficient grid management, energy trading, and optimizing wind farm operations. This project leverages machine learning techniques to build a predictive model that can forecast energy generation based on real-time and historical data.

## Key Objectives

- **Predict Energy Output:** Develop a model to accurately predict the energy output (Active Power) of wind turbines.
- **Utilize Weather Data:** Incorporate weather variables like wind speed and wind direction as key predictors.
- **Leverage Turbine Data:** Utilize turbine operational data, such as the turbine's theoretical power curve, to enhance prediction accuracy.
- **Model Evaluation:** Employ regression algorithms, such as polynomial regression, and evaluate model performance using metrics like R-squared (R2 score).
- **Deployment:** Demonstrate a basic deployment strategy using Node-RED for data processing and visualization.

## Technical Details

- **Independent Variables:**
  - Wind Speed
  - LV Active Power (Low Voltage Active Power)
- **Dependent Variables:**
  - Theoretical Power
  - Wind Direction
- **Tools and Technologies:**
  - Python (for data analysis, model building, and evaluation)
  - Regression Algorithms (e.g., Polynomial Regression)
  - Node-RED (for data flow management, basic deployment, and user interface)
  - HTTP Request, Timestamp, Message Payload (within Node-RED)

## Dataset Sources

- **Open Power System Data:** [https://data.open-power-system-data.org/time_series/](https://data.open-power-system-data.org/time_series/)
- **Elia Grid Data:** [https://www.elia.be/en/grid-data/power-generation](https://www.elia.be/en/grid-data/power-generation)
- **Open Power System Weather Data:** [https://data.open-power-system-data.org/weather_data/](https://data.open-power-system-data.org/weather_data/)

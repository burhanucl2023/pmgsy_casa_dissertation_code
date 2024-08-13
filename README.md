# Roads to Prosperity: Assessing the Impact of Rural Road Infrastructure on Economic Development in India using Satellite Derived Night Time Light (NTL) Data as Development Proxy

This repository contains the code used in the analysis for the project titled "Roads to Prosperity: Assessing the Impact of Rural Road Infrastructure on Economic Development in India using Satellite Derived Night Time Light (NTL) Data as Development Proxy." This project is presented in partial fulfillment of the requirements for the degree of MSc Urban Spatial Science by Burhan Ahmad Wani at University College London.

The Pradhan Mantri Gram Sadak Yojana (PMGSY) program, launched in 2000, aimed to enhance rural connectivity across India by constructing all-weather roads in unconnected villages. This study employs advanced econometric methodologies, such as Difference-in-Differences (DiD), Propensity Score Matching (PSM), and Regression Kink Design (RKD), to evaluate the program's impact on economic development, as indicated by changes in nighttime light intensity. Nighttime light data serves as a proxy for economic activity, capturing the nuanced effects of infrastructure development in diverse geographic and socioeconomic contexts.

## Methodology Overview

The analytical approach used in this study involves:

- **Propensity Score Matching (PSM):** To address potential selection biases by matching treated and control villages with similar characteristics.
- **Difference-in-Differences (DiD):** To estimate the causal effect of PMGSY road construction on changes in nighttime light intensity.
- **Triple Differences (DiDiD):** To explore heterogeneous effects across different regions and terrain types.
- **Regression Kink Design (RKD):** To identify changes in the slope of nighttime light intensity relative to the timing of road construction, providing a nuanced understanding of the program's impact over time.

The flowchart below summarizes the code used in the various stages of the analysis:

![Dissertation Flowchart](images/dissertation_data_flow_.png)

This flowchart illustrates the key steps in the research methodology, from data collection and processing to the application of econometric models. The analysis results contribute to a deeper understanding of how rural road infrastructure influences economic development in India, offering insights for policymakers and development practitioners.

## Cholera Response Simulator resources
This repo contains:
- ```Pilot Recommendations.ipynb```: report on recommendations for a Cholera Response Simulator pilot using System Dynamics;
- ```datasets```: a few useful datasets, on which some viz + exploratory analysis work has been done over the course of the fellowship. This includes:
    - ```acaps_2021.xlsx```: ACAPS Crisis InSight dataset including both data on cholera incidence and a number of other indicators of the humanitarian situation in the country. Only includes 2019-2021;
    - ```IATI_data.csv```: a datasets with IATI data on activities in Yemen for 2017-2018;
    - ```cholera_cases_1718.xslx```: monthly data on cholera cases;
    - ```rainfall.csv```: World Bank data on rainfall volume for Yemen (country-wide);
    - ```temperature.csv```: World Bank data on temperature for Yemen (country-wide);
    - ```yem-administrative-divisions-shapefiles```: geo data, used for plotting
- ```explore_acaps_ds.ipynb```: Some preliminary exploration of the ACAPS dataset, including both viz on number of cases in Yemen between 2017 and 2020 and some analysis to get a sense of the predictive accuracy of different types of non-dynamic multivariate models in predicting cholera cases and deaths. Code is not tidy at all, but this was just a "proof of concept" to concretely see how poorly non-dynamic models perform, given the data that are currently available;
- ```viz_cases+env.ipynb```: Some plotting of cases against rainfall and temperature data, showing clear decoupling between environmental variables and cases after 2017. Take-home message: interventions matter, and transition to endemic transmission modalities also matter: we need to add these components to CRM and ESA-like models;
- ```viz_IATI.ipynb```: data on funding for WASH activities or activities mentioning cholera in Yemen for 2017-2018
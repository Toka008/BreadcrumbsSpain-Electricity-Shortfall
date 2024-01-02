# Spain Electricity Shortfall Case Study: Predicting Daily Shortfall With Machine Learning (AI)

## Overview
The Spanish government is thinking about making more purchases of renewable energy. They require data regarding Spain's present trends and patterns in the generation of both renewable and non-renewable energy in order to do this. In particular, they want to be able to forecast the load shortfall under specific circumstances (wind speed, pressure, humidity, etc.) on any given day. The distinction between the generation of renewable and non-renewable energy is load deficiticly.

## Expected Outcomes
1. Identify energy generation trends and patterns
2. Create a regression model that predicts load shortfall
3. Present findings

## Tools Used
- Python
  SK Learn
  Pandas
  NumPys
- Flask
- AWS EC

## Output
With an RMSE of 3184 for the ensemble model, we came in second out of 38 teams on the https://www.kaggle.com/competitions/spain-electricity-shortfall-challenge-2023. This implies that we could forecast the load deficit with accuracy.

![monthly](https://github.com/Toka008/Spain-Electricity-Shortfall/assets/63381061/98494122-f440-4c12-968d-10172b127035)
- This bar graph shows the load shortfall per month.Possibly due to higher solar generation
![weekly](https://github.com/Toka008/Spain-Electricity-Shortfall/assets/63381061/77ddf74f-8a11-46e7-806c-4a53f916715a)
- This bar graph shows the load shortfall per week.Possibly due to lower power consumption
![hour of day](https://github.com/Toka008/Spain-Electricity-Shortfall/assets/63381061/c7abbcdb-34d0-44f1-82c1-a3886bb09c45)
- This bar graph shows the load shortfall for hour of day

## Recommendations

- The reason why there is less of a load shortage on weekends needs more research.
  Should this be the result of reduced electricity usage, the Spanish government ought to give priority to generating power on weekdays when demand is higher.
  If not, weekend power generating ought to take priority in order to boost the quantity of renewable energy.
- The summer months produce a large amount of electricity from renewable sources, hence other seasons ought to take precedence. This can entail turning to energy sources like wind energy, which produce more in different seasons.

## Acknowledgements
Special thanks to the project team members for their contributions:

- Tise Onadipe
- Sandisiwe Mtsha
- Macdaniel Ogechukwu
- Chijioke Nnabueze

## Note
Due to the sensitive nature of the project, code cannot be shared publicly.




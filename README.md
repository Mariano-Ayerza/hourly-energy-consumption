# energy-hourly-consumption

Project to analyze and build a model to predict energy hourly consumption in Argentina based in different time zones.

In recent weeks, a debate began in Argentina about the time zone that the country should have. Currently, Argentina has the UTC-3 time zone, and this is maintained throughout the year for the entire length and breadth of the country. Experts on the subject affirm that the time zone that would correspond to the country is UTC-4.

This debate aroused great interest in me and, taking advantage of the latest tools that I was studying, I decided to try to contribute to the debate with a model that predicts energy consumption based on the time zone that is adopted.

The project consists of 4 stages, the first where I import the information, do the EDA and end up building a time series model. Then comes a stage where I add variables to the dataset that explain the energy consumption. The third stage is the construction of different non-linear models that predict energy consumption based on the variables that were added in stage 2. Finally, using the best model created in the previous stage, energy consumption is predicted for different time zones. 

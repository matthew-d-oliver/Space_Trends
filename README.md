# SPACE TRENDS
Matthew Oliver

## Project Outline
Presentation: https://docs.google.com/presentation/d/1E20EOmdIhKCCQjmyYJTAfbWW0bZ7-Bio9ckfyph84RQ/edit?usp=sharing
How does (US) Interest in Space Exploration change over time? 
Are there seasonal dependencies or external factors?
The goal of this project is to build a forecasting model for public interest in space exploration using data from Google Trends on searches for space exploration in the US over the last decade. Several exogenous features were selected for the forecasting model from potentially corolary trends.

## Data Collection
### Google Trends
Historical search interest data was obtained through the PyTrends python package for a selection of space-related terms. Time decompositions of different earch terms were done, with differing results. 'Space Exploration' was the term brought forward for modelling due to its consistent seasonality and lack of search peaks. Other terms such as 'Space-X' or 'Mars Exploration' were not used due to the search interest being highly erratic, peaking from random company press releases or events, which are hard to account for in the model.

### Space Stocks


### SCI-FI Movie Prevalence

### NASA Budget

## Models

### Arima Time Decompostion

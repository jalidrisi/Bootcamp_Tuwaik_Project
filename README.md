
## Question/need
The goal of this project is to use classification models to predict whether it is going to rain the next day or not based on weather observations from the previous day. This is helpful because as a software developer in the National Center of Meteorology, I can help weather forecasters and meteorologists in their weather forecasting and issuing weather alerts to the public or to other governmental sectors. In addition, predicting rain assists farmers managing and improving their produce and it also helps event organizers plan their outdoor events better.

## Data Description:
In order to predict rain, I am going to use a dataset from Kaggle that has daily weather observations from weather stations in Australia. I am going to obtain the data by using Kaggle API. 

### Data Sample
| Date    | Location | MinTemp | MaxTemp | Rainfall | Evaporation | Sunshine | WindGustDir | WindGustSpeed | WindDir9am | WindDir3pm | WindSpeed9am | WindSpeed3pm | Humidity9am | Humidity3pm | Pressure9am | Pressure3pm | Cloud9am | Cloud3pm | Temp9am | Temp3pm | RainToday | RainTomorrow |
|---------|----------|---------|---------|----------|-------------|----------|-------------|---------------|------------|------------|--------------|--------------|-------------|-------------|-------------|-------------|----------|----------|---------|---------|-----------|--------------|
| 12/1/08 | Albury   | 13.4    | 22.9    | 0.6      | NA          | NA       | W           | 44            | W          | WNW        | 20           | 24           | 71          | 22          | 1007.7      | 1007.1      | 8        | NA       | 16.9    | 21.8    | No        | No           |
| 12/2/08 | Albury   | 7.4     | 25.1    | 0        | NA          | NA       | WNW         | 44            | NNW        | WSW        | 4            | 22           | 44          | 25          | 1010.6      | 1007.8      | NA       | NA       | 17.2    | 24.3    | No        | No           |
| 12/3/08 | Albury   | 12.9    | 25.7    | 0        | NA          | NA       | WSW         | 46            | W          | WSW        | 19           | 26           | 38          | 30          | 1007.6      | 1008.7      | NA       | 2        | 21      | 23.2    | No        | No           |
| 12/4/08 | Albury   | 9.2     | 28      | 0        | NA          | NA       | NE          | 24            | SE         | E          | 11           | 9            | 45          | 16          | 1017.6      | 1012.8      | NA       | NA       | 18.1    | 26.5    | No        | No           |
| 12/5/08 | Albury   | 17.5    | 32.3    | 1        | NA          | NA       | W           | 41            | ENE        | NW         | 7            | 20           | 82          | 33          | 1010.8      | 1006        | 7        | 8        | 17.8    | 29.7    | No        | No           |
| 12/6/08 | Albury   | 14.6    | 29.7    | 0.2      | NA          | NA       | WNW         | 56            | W          | W          | 19           | 24           | 55          | 23          | 1009.2      | 1005.4      | NA       | NA       | 20.6    | 28.9    | No        | No           |# Final

The dataset contains 10 years of weather observations with 23 features. The highlighted features that will help predict rain are :
- MinTemp: The minimum temperature registered in the day 
- MaxTemp: The maximum temperature registered in the day
- Humidity9am: Humidity at 9 AM
- Humidity3pm: Humidity at 3 PM
- 


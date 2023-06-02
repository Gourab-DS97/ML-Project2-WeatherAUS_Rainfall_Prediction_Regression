# Weather Analytics- <br>Rainfall Prediction in Australia (Regression Project)
### Abstract:
The weatherAUS.csv dataset contains n = 36,881 daily observations from 45 Australian weather stations. The weather data were obtained from the Australian Commonwealth Bureau of Meteorology. The data has been processed to provide a binary target variable RainTomorrow (whether there is rain during the next day; No/Yes) and a continuous target (risk) variable RISK_MM (the amount of rain recorded during the next day).

### Objective:
This project will predict amount of rain recorded during the next day from the given input features.

### Attribute Information:
* **Date:** The date of observation (a date object). <br>
* **Location:** The common name of the location of the weather station. <br>
* **MinTemp:** The minimum temperature in degrees centigrade. <br>
* **MaxTemp:** The maximum temperature in degrees centigrade. <br>
* **Rainfall:** The amount of rainfall recorded for the day in millimeters. <br>
* **Evaporation:** Class A pan evaporation (in millimeters) during 24 h (until 9 AM). <br>
* **Sunshine:** The number of hours of bright sunshine in the day. <br>
* **WindGustDir:** The direction of the strongest wind gust in the 24 h to midnight. <br>
* **WindGustSpeed:** The speed (in kilometers per hour) of the strongest wind gust in the 24 h to midnight.<br>
* **WindDir9am:** The direction of the wind gust at 9 AM. <br>
* **WindDir3pm:** The direction of the wind gust at 3 PM. <br>
* **WindSpeed9am:** Wind speed (in kilometers per hour) averaged over 10 min before 9 AM. <br>
* **WindSpeed3pm:** Wind speed (in kilometers per hour) averaged over 10 min before 3 PM. <br>
* **RelHumid9am:** Relative humidity (in percent) at 9 AM. <br>
* **RelHumid3pm:** Relative humidity (in percent) at 3 PM. <br>
* **Pressure9am:** Atmospheric pressure (hpa) reduced to mean sea level at 9 AM <br>
* **Pressure3pm:** Atmospheric pressure (hpa) reduced to mean sea level at 3 PM. <br>
* **Cloud9am:** Fraction of sky obscured by cloud at 9 AM. This is measured in ”oktas,” which are a unit of eighths. It records how many eighths of the sky are obscured by cloud. A 0 measure indicates completely clear sky, while an 8 indicates that it is completely overcast. <br>
* **Cloud3pm:** Fraction of sky obscured by cloud at 3 PM; see Cloud9am for a description of the values. <br>
* **Temp9am:** Temperature (degrees C) at 9 AM <br>
* **Temp3pm:** Temperature (degrees C) at 3 PM. <br>
* **RainToday:** Integer 1 if precipitation (in millimeters) in the 24 h to 9 AM exceeds 1 mm, otherwise 0.<br>
* **RISK_MM:** The continuous target variable; the amount of rain recorded during the next day. <br>

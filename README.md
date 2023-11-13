# python-api-challenge
This was completed in conjunction with my study group (Paul Moses, Mitchell Lor, Waynei Mebrahtu, Eric Johnson). I also used stackoverflow, class work from the preceding two weeks and pandas documentation.
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.dt.strftime.html
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html

Analysis from WeatherPy:
Temperature and latitude are positively correlated based on the r-squared values obtained and on common sense. We know the weather gets warmer the closer to the equater(0 deg latitutde) you are and cooler the farther away you are.  R-squared values of 0.4 (southern hemisphere) and 0.7(northern hemisphere) as we see here in the temperature vs latitude plots with linear regression analyis, are both postive correlations and hosw a linear relationship between the data.

There appears a less direct correlation between latitude and humidity. In both hemispheres the r-square number (southern=0.002, northern=0.05) does not indicate a strong relationship. These numbers do indicate a stronger correlation in the northern hemisphere. It might be better to look at humidity data using a different type of analysis as the data is more complicated and both tropical regions and regions closer to large water bodies tend to be higher in humidity indicating that latitude in only a small part of what determines humidity.

The same lack of correlation as humitdity and latitidue can be said for cloudiness and latitude. This is not a linear relationship.

There also appears to be a low correlation between wind speed and latitidue.  This is also not a linear relationship that is well describe by linear regression. 

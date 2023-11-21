=========================================
Dataset characteristics
=========================================	
day.csv have the following fields
	
	- instant record index
	- dteday  date
	- season  season (1spring, 2summer, 3fall, 4winter)
	- yr  year (0 2018, 12019)
	- mnth  month ( 1 to 12)
	- holiday  weather day is a holiday or not (extracted from httpdchr.dc.govpageholiday-schedule)
	- weekday  day of the week
	- workingday  if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit  
		- 1 Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2 Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3 Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4 Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp  temperature in Celsius
	- atemp feeling temperature in Celsius
	- hum humidity
	- windspeed wind speed
	- casual count of casual users
	- registered count of registered users
	- cnt count of total rental bikes including both casual and registered
	
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication

[1] Fanaee-T, Hadi, and Gama, Joao, Event labeling combining ensemble detectors and background knowledge, Progress in Artificial Intelligence (2013) pp. 1-15, Springer Berlin Heidelberg, doi10.1007s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={httpdx.doi.org10.1007s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

=========================================
Contact
=========================================
	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)
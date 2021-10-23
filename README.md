# WeatherandVacation
- utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api to create a representative model of weather across world cities

- from the weather analyze, create a vacation plan with hotel search using Google Place API and plot google heat map

How to run
	- add file "api_keys.py" to the main working folder (same level with .ipynp files)
	- add this content to the "api_keys.py" file
 # OpenWeatherMap API Key
weather_api_key = "your weather api key"

# Google API Key
g_key = "your google api key"
	- Note:
		weather api key is generated from https://openweathermap.org/api
		google api key is generated from https://cloud.google.com/maps-platform/
	- Run the Weather.ipynb
		- the project will export below file in the "output_data" folder
			city_weather.csv: contain the city weather data getting from API
			log[timestamp].text: contain logs with cities which are processed to request API
			11 image files with timestamp which are saved from graphs
	- Run the Vacation.ipynp
		the project will read the city_weather.csv file above and process required requirements
		
----------------------------
Good Luck
			